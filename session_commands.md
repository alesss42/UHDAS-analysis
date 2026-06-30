# CODAS Installation Session — Command Reference

## 1. Create the conda environment

```bash
conda env create --file codas_processing.yml
```
Creates a new conda environment called `pycodas` from the spec file. This installs Python 3.13 and all required packages (numpy, matplotlib, scipy, cartopy, netcdf4, etc.).

---

## 2. Conda housekeeping

```bash
conda config --set auto_activate_base false
```
Stops conda from auto-activating the `base` environment every time you open a terminal.

```bash
conda activate base
conda update conda
conda deactivate
```
Activates base, updates conda itself to the latest version, then deactivates.

```bash
conda config --add channels conda-forge
conda config --set channel_priority strict
```
Sets conda-forge as the primary package channel and enforces strict priority (packages come from conda-forge first, avoids conflicts).

```bash
cat .condarc
```
Prints your conda configuration file to verify the settings took effect.

---

## 3. Activate the working environment

```bash
conda activate pycodas
conda list
```
Activates the `pycodas` environment. `conda list` shows all installed packages — used to verify the environment is correct.

---

## 4. Check Xcode command line tools

```bash
xcode-select --install
```
Installs Apple's command line developer tools (C compiler, etc.), required to compile `codas3` from source. (Was already installed in this case.)

---

## 5. Create the directory structure

```bash
mkdir ~/adcpcode
mkdir ~/adcpcode/programs
mkdir ~/adcpcode/topog
```
Creates the top-level working directory with two subdirectories: one for code repositories, one for topography data.

---

## 6. Clone the three CODAS repositories

```bash
cd ~/adcpcode/programs
git clone -b stable https://currents.soest.hawaii.edu/git/uh-currents-group/shipboard-adcp/codas3.git
git clone -b stable https://currents.soest.hawaii.edu/git/uh-currents-group/shipboard-adcp/pycurrents.git
git clone -b stable https://currents.soest.hawaii.edu/git/uh-currents-group/shipboard-adcp/onship.git
```
Clones the `stable` branch of three repos from the UH Currents Group:
- **codas3** — core C library for ADCP data I/O and processing
- **pycurrents** — Python interface to codas3; main package for reading/analyzing ADCP data
- **onship** — scripts for at-sea UHDAS operations and processing

---

## 7. Compile and install codas3

```bash
cd ~/adcpcode/programs/codas3
./conda-install.sh
cd ~
```
Runs the build script, which calls `waf configure`, `waf build`, and `waf install` to compile the C library and install binaries (e.g., `showdb`, `adcpsect`, `loadping`) into the `pycodas` conda environment.

---

## 8. Install pycurrents and onship (Python packages)

```bash
cd ~/adcpcode/programs/pycurrents
pip install --no-build-isolation .

cd ../onship
pip install --no-build-isolation .
cd ~
```
Installs both packages into `pycodas` using pip. `--no-build-isolation` means pip uses the already-active conda environment rather than creating an isolated build environment (needed because these packages depend on the just-compiled codas3 C library).

---

## 9. Download documentation and demo data

```bash
cd ~/adcpcode/programs
curl -O https://currents.soest.hawaii.edu/docs/zipped/adcp_doc.zip
unzip adcp_doc.zip
curl -O https://currents.soest.hawaii.edu/docs/zipped/codas_demos.zip
unzip codas_demos.zip
```
Downloads and unpacks:
- **adcp_doc** — full HTML documentation for CODAS/UHDAS (open `adcp_doc/index.html` in a browser)
- **codas_demos** — example cruise datasets (`km1001c` UHDAS data, `ps0918` VMDAS data) for practicing processing

---

## 10. Download topography

```bash
cd ~/adcpcode/topog
mkdir etopo
cd etopo
curl -O https://currents.soest.hawaii.edu/downloads/etopo1_for_pycurrents.zip
unzip etopo1_for_pycurrents.zip
```
Downloads ETOPO1 global topography in the binary format expected by pycurrents. Used for map backgrounds in plots.

---

## 11. Link topography so pycurrents can find it

```bash
cd ~/miniforge3
ln -s ~/adcpcode/topog .
cd ~
```
Creates a symlink inside the miniforge3 directory pointing to the topography folder. pycurrents looks for topography relative to the conda prefix by default.

---

## 12. Verify the install

```bash
ipython
```
```python
import pycurrents
pycurrents?   # shows the package docstring
exit
```
Quick sanity check that pycurrents imported successfully.

---

## 13. Explore a demo dataset

```bash
cd ~/adcpcode/programs/codas_demos/uhdas_data/km1001c/proc/os38nb
ls
```
Navigates into the processed directory for the `os38nb` instrument from cruise `km1001c`. Contains subdirectories: `adcpdb`, `cal`, `contour`, `edit`, `nav`, `ping`, etc.

```bash
showdb adcpdb/a_km
```
Opens the CODAS binary database interactively. Used to inspect what variables are stored (U, V, W, AMP, PERCENT_GOOD, etc.) and peek at raw values. Interactive menu: option 7 = data list, option 16 = get data.

```bash
figview.py --type png
```
Opens a GUI to browse PNG plots already generated for this cruise (calibration plots, contour sections, etc.).

```bash
dataviewer.py
```
Opens the full CODAS interactive data viewer — the main GUI for viewing and editing ADCP profiles, applying masks, and inspecting data quality.

---

## 14. Check available environments

```bash
conda env list
```
Lists all conda environments. At the end of the session: `base`, `garmin`, `jupyter`, `ocean`, `pycodas` (active), `swot_download`.
