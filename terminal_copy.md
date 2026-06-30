-rw-r--r--@  1 alesan  staff        4236 May 19 13:50 UHDAS_functional_areas.md
-rw-r--r--@  1 alesan  staff         996 May 19 14:50 codas_processing.yml
alesan@Alejandras-MacBook-Pro-2 Downloads % conda env create --file codas_processing.yml
Retrieving notices: done
Channels:
 - conda-forge
Platform: osx-arm64
Collecting package metadata (repodata.json): done
Solving environment: done

==> WARNING: A newer version of conda exists. <==
    current version: 26.1.1
    latest version: 26.5.0

Please update conda by running

    $ conda update -n base -c conda-forge conda

Downloading and Extracting Packages:

Preparing transaction: done                                                     
Verifying transaction: done                                                     
Executing transaction: done                                                     
#                                                                               
# To activate this environment, use                                             
#                                                                               
#     $ conda activate pycodas                                                  
#                                                                               
# To deactivate an active environment, use                                      
#                                                                               
#     $ conda deactivate                                                        

alesan@Alejandras-MacBook-Pro-2 Downloads % cd 
alesan@Alejandras-MacBook-Pro-2 ~ % cat .conda
cat: .conda: Is a directory
alesan@Alejandras-MacBook-Pro-2 ~ % ls .conda  
environments.txt
alesan@Alejandras-MacBook-Pro-2 ~ % conda config --set auto_activate_base false
WARNING conda.cli.condarc:set_key(484): Key auto_activate_base is an alias of auto_activate; setting value with latter
alesan@Alejandras-MacBook-Pro-2 ~ % conda update conda

DirectoryNotACondaEnvironmentError: The target directory exists, but it is not a conda environment.
Use 'conda create' to convert the directory to a conda environment.
  target directory: /Users/alesan/miniforge3/envs

alesan@Alejandras-MacBook-Pro-2 ~ % conda activate base
(base) alesan@Alejandras-MacBook-Pro-2 ~ % conda update conda 
Channels:
 - conda-forge
Platform: osx-arm64
Collecting package metadata (repodata.json): done
Solving environment: done

## Package Plan ##

  environment location: /Users/alesan/miniforge3

  added / updated specs:
    - conda

The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    annotated-types-0.7.0      |     pyhd8ed1ab_1          18 KB  conda-forge
    click-8.4.0                |     pyhc90fa1f_0         102 KB  conda-forge
    conda-26.5.0               |  py313h8f79df9_1         1.3 MB  conda-forge
    conda-index-0.11.0         |     pyhd8ed1ab_0         200 KB  conda-forge
    conda-libmamba-solver-26.4.2|     pyhd8ed1ab_0          59 KB  conda-forge
    conda-lockfiles-0.2.0      |     pyhd8ed1ab_0          20 KB  conda-forge
    conda-pypi-0.9.0           |  py313h8f79df9_3         258 KB  conda-forge
    conda-rattler-solver-0.1.0 |     pyhcf101f3_0          36 KB  conda-forge
    conda-self-0.2.0           |     pyhd8ed1ab_0          22 KB  conda-forge
    filelock-3.29.0            |     pyhd8ed1ab_0          33 KB  conda-forge
    markupsafe-3.0.3           |  py313h65a2061_1          25 KB  conda-forge
    py-rattler-0.23.2          |  py310hbaa5893_1         9.7 MB  conda-forge
    pydantic-2.13.4            |     pyhcf101f3_0         338 KB  conda-forge
    pydantic-core-2.46.4       |  py313h212e517_0         1.6 MB  conda-forge
    pyproject_hooks-1.2.0      |     pyhd8ed1ab_1          15 KB  conda-forge
    python-build-1.5.0         |     pyhc364b38_0          28 KB  conda-forge
    python-installer-1.0.1     |     pyh332efcf_0         234 KB  conda-forge
    typing-inspection-0.4.2    |     pyhcf101f3_2          20 KB  conda-forge
    unearth-0.18.2             |     pyhd8ed1ab_0         280 KB  conda-forge
    ------------------------------------------------------------
                                           Total:        14.3 MB

The following NEW packages will be INSTALLED:

  _python_abi3_supp~ conda-forge/noarch::_python_abi3_support-1.0-hd8ed1ab_2 
  annotated-types    conda-forge/noarch::annotated-types-0.7.0-pyhd8ed1ab_1 
  anyio              conda-forge/noarch::anyio-4.13.0-pyhcf101f3_0 
  cached-property    conda-forge/noarch::cached-property-1.5.2-hd8ed1ab_1 
  cached_property    conda-forge/noarch::cached_property-1.5.2-pyha770c72_1 
  click              conda-forge/noarch::click-8.4.0-pyhc90fa1f_0 
  colorama           conda-forge/noarch::colorama-0.4.6-pyhd8ed1ab_1 
  conda-index        conda-forge/noarch::conda-index-0.11.0-pyhd8ed1ab_0 
  conda-lockfiles    conda-forge/noarch::conda-lockfiles-0.2.0-pyhd8ed1ab_0 
  conda-pypi         conda-forge/osx-arm64::conda-pypi-0.9.0-py313h8f79df9_3 
  conda-rattler-sol~ conda-forge/noarch::conda-rattler-solver-0.1.0-pyhcf101f3_0 
  conda-self         conda-forge/noarch::conda-self-0.2.0-pyhd8ed1ab_0 
  cpython            conda-forge/noarch::cpython-3.13.13-py313hd8ed1ab_100 
  exceptiongroup     conda-forge/noarch::exceptiongroup-1.3.1-pyhd8ed1ab_0 
  filelock           conda-forge/noarch::filelock-3.29.0-pyhd8ed1ab_0 
  h11                conda-forge/noarch::h11-0.16.0-pyhcf101f3_1 
  httpcore           conda-forge/noarch::httpcore-1.0.9-pyh29332c3_0 
  httpx              conda-forge/noarch::httpx-0.28.1-pyhd8ed1ab_0 
  importlib-metadata conda-forge/noarch::importlib-metadata-8.8.0-pyhcf101f3_0 
  jinja2             conda-forge/noarch::jinja2-3.1.6-pyhcf101f3_1 
  markupsafe         conda-forge/osx-arm64::markupsafe-3.0.3-py313h65a2061_1 
  py-rattler         conda-forge/osx-arm64::py-rattler-0.23.2-py310hbaa5893_1 
  pydantic           conda-forge/noarch::pydantic-2.13.4-pyhcf101f3_0 
  pydantic-core      conda-forge/osx-arm64::pydantic-core-2.46.4-py313h212e517_0 
  pyproject_hooks    conda-forge/noarch::pyproject_hooks-1.2.0-pyhd8ed1ab_1 
  python-build       conda-forge/noarch::python-build-1.5.0-pyhc364b38_0 
  python-gil         conda-forge/noarch::python-gil-3.13.13-h4df99d1_100 
  python-installer   conda-forge/noarch::python-installer-1.0.1-pyh332efcf_0 
  sniffio            conda-forge/noarch::sniffio-1.3.1-pyhd8ed1ab_2 
  tomli              conda-forge/noarch::tomli-2.4.1-pyhcf101f3_0 
  typing-extensions  conda-forge/noarch::typing-extensions-4.15.0-h396c80c_0 
  typing-inspection  conda-forge/noarch::typing-inspection-0.4.2-pyhcf101f3_2 
  typing_extensions  conda-forge/noarch::typing_extensions-4.15.0-pyhcf101f3_0 
  unearth            conda-forge/noarch::unearth-0.18.2-pyhd8ed1ab_0 
  zipp               conda-forge/noarch::zipp-4.1.0-pyhcf101f3_0 

The following packages will be UPDATED:

  ca-certificates                      2026.2.25-hbd8a1cb_0 --> 2026.4.22-hbd8a1cb_0 
  certifi                            2026.2.25-pyhd8ed1ab_0 --> 2026.4.22-pyhd8ed1ab_0 
  conda                              26.1.1-py313h8f79df9_0 --> 26.5.0-py313h8f79df9_1 
  conda-libmamba-so~                   25.11.0-pyhd8ed1ab_1 --> 26.4.2-pyhd8ed1ab_0 
  openssl                                  3.6.1-hd24854e_1 --> 3.6.2-hd24854e_0 

Proceed ([y]/n)? y

Downloading and Extracting Packages:

Preparing transaction: done                                                     
Verifying transaction: done                                                     
Executing transaction: done                                                     
(base) alesan@Alejandras-MacBook-Pro-2 ~ % conda deactivate
alesan@Alejandras-MacBook-Pro-2 ~ % conda config --add channels conda-forge
conda config --set channel_priority strict
Warning: 'conda-forge' already in 'channels' list, moving to the top
alesan@Alejandras-MacBook-Pro-2 ~ % locate .condarc

WARNING: The locate database (/var/db/locate.database) does not exist.
To create the database, run the following command:

  sudo launchctl load -w /System/Library/LaunchDaemons/com.apple.locate.plist

Please be aware that the database can take some time to generate; once
the database has been created, this message will no longer appear.

alesan@Alejandras-MacBook-Pro-2 ~ % ls -a
. .python_history
.. .subversion
.bash_history .Trash
.bundle .urs_cookies
.cache .viminfo
.CFUserTextEncoding .vscode
.claude .vscode-shared
.claude.json .zprofile
.claude.json.backup .zsh_history
.conda .zsh_sessions
.condarc .zshrc
.config Applications
.copilot bitmap.png
.dodsrc Desktop
.DS_Store Documents
.gitconfig Downloads
.ipynb_checkpoints Library
.ipython miniforge3
.jupyter Miniforge3-MacOSX-arm64.sh
.local Movies
.mamba Music
.matlab Pictures
.matplotlib Public
.netrc TMP_DATA
.npm Zotero
.oracle_jre_usage Zotero_old
alesan@Alejandras-MacBook-Pro-2 ~ % cat .condarc
channels:
  - conda-forge
mirrored_channels:
  conda-forge:
    - https://conda.anaconda.org/conda-forge
    - https://prefix.dev/conda-forge

auto_activate: false
channel_priority: strict
alesan@Alejandras-MacBook-Pro-2 ~ % conda activate pycodas
(pycodas) alesan@Alejandras-MacBook-Pro-2 ~ % conda list
# packages in environment at /Users/alesan/miniforge3/envs/pycodas:
#
# Name                       Version          Build                    Channel
_openmp_mutex                4.5              7_kmp_llvm               conda-forge
_python_abi3_support         1.0              hd8ed1ab_2               conda-forge
appnope                      0.1.4            pyhd8ed1ab_1             conda-forge
asttokens                    3.0.1            pyhd8ed1ab_0             conda-forge
aws-c-auth                   0.10.1           ha7d4cc1_3               conda-forge
aws-c-cal                    0.9.13           h6ee9776_1               conda-forge
aws-c-common                 0.12.6           hc919400_0               conda-forge
aws-c-compression            0.3.2            h3e7f9b5_0               conda-forge
aws-c-http                   0.10.13          h95cdebe_0               conda-forge
aws-c-io                     0.26.3           h4137820_2               conda-forge
aws-c-s3                     0.12.2           h07b101a_1               conda-forge
aws-c-sdkutils               0.2.4            h16f91aa_4               conda-forge
aws-checksums                0.2.10           h3e7f9b5_0               conda-forge
basemap                      2.0.0            py313hf1025b9_5          conda-forge
basemap-data                 2.0.0            basemap_0                conda-forge
basemap-data-hires           2.0.0            basemap_0                conda-forge
blosc                        1.21.6           h7dd00d9_1               conda-forge
brotli                       1.2.0            h7d5ae5b_1               conda-forge
brotli-bin                   1.2.0            hc919400_1               conda-forge
bzip2                        1.0.8            hd037594_9               conda-forge
c-ares                       1.34.6           hc919400_0               conda-forge
ca-certificates              2026.4.22        hbd8a1cb_0               conda-forge
cairo                        1.18.4           he0f2337_1               conda-forge
cartopy                      0.25.0           py313h7d16b84_1          conda-forge
certifi                      2026.4.22        pyhd8ed1ab_0             conda-forge
cftime                       1.6.5            py313hf5115c3_1          conda-forge
colorama                     0.4.6            pyhd8ed1ab_1             conda-forge
comm                         0.2.3            pyhe01879c_0             conda-forge
contourpy                    1.3.3            py313h2af2deb_4          conda-forge
cpython                      3.13.13          py313hd8ed1ab_100        conda-forge
cycler                       0.12.1           pyhcf101f3_2             conda-forge
cyrus-sasl                   2.1.28           hb961e35_1               conda-forge
cython                       3.2.4            py313hf5aebd8_0          conda-forge
debugpy                      1.8.20           py313h1188861_0          conda-forge
decorator                    5.3.1            pyhd8ed1ab_0             conda-forge
double-conversion            3.4.0            hf6b4638_0               conda-forge
exceptiongroup               1.3.1            pyhd8ed1ab_0             conda-forge
executing                    2.2.1            pyhd8ed1ab_0             conda-forge
font-ttf-dejavu-sans-mono    2.37             hab24e00_0               conda-forge
font-ttf-inconsolata         3.000            h77eed37_0               conda-forge
font-ttf-source-code-pro     2.038            h77eed37_0               conda-forge
font-ttf-ubuntu              0.83             h77eed37_3               conda-forge
fontconfig                   2.17.1           h2b252f5_0               conda-forge
fonts-conda-ecosystem        1                0                        conda-forge
fonts-conda-forge            1                hc364b38_1               conda-forge
fonttools                    4.63.0           py313h65a2061_0          conda-forge
freetype                     2.14.3           hce30654_0               conda-forge
geos                         3.14.1           h5afe852_0               conda-forge
git                          2.54.0           pl5321hc9deb11_0         conda-forge
gitdb                        4.0.12           pyhd8ed1ab_0             conda-forge
gitpython                    3.1.50           pyhd8ed1ab_0             conda-forge
graphite2                    1.3.14           hec049ff_2               conda-forge
harfbuzz                     14.2.0           h3103d1b_0               conda-forge
hdf4                         4.2.15           h2ee6834_7               conda-forge
hdf5                         2.1.0            nompi_he586413_105       conda-forge
icu                          78.3             hef89b57_0               conda-forge
importlib-metadata           8.8.0            pyhcf101f3_0             conda-forge
iniconfig                    2.3.0            pyhd8ed1ab_0             conda-forge
ipykernel                    7.2.0            pyh5552912_1             conda-forge
ipython                      9.13.0           pyh53cf698_0             conda-forge
ipython_pygments_lexers      1.1.1            pyhd8ed1ab_0             conda-forge
jedi                         0.19.2           pyhd8ed1ab_1             conda-forge
jupyter_client               8.8.0            pyhcf101f3_0             conda-forge
jupyter_core                 5.9.1            pyhc90fa1f_0             conda-forge
kiwisolver                   1.5.0            py313h2af2deb_0          conda-forge
krb5                         1.22.2           h385eeb1_0               conda-forge
lcms2                        2.19.1           hdfa7624_0               conda-forge
lerc                         4.1.0            h1eee2c3_0               conda-forge
libaec                       1.1.5            h8664d51_0               conda-forge
libblas                      3.11.0           7_h51639a9_openblas      conda-forge
libbrotlicommon              1.2.0            hc919400_1               conda-forge
libbrotlidec                 1.2.0            hc919400_1               conda-forge
libbrotlienc                 1.2.0            hc919400_1               conda-forge
libcblas                     3.11.0           7_hb0561ab_openblas      conda-forge
libclang13                   22.1.5           default_h6dd9417_1       conda-forge
libcurl                      8.20.0           hd5a2499_0               conda-forge
libcxx                       22.1.5           h55c6f16_1               conda-forge
libdeflate                   1.25             hc11a715_0               conda-forge
libedit                      3.1.20250104     pl5321hafb1f1b_0         conda-forge
libev                        4.33             h93a5062_2               conda-forge
libexpat                     2.8.0            hf6b4638_0               conda-forge
libffi                       3.5.2            hcf2aa1b_0               conda-forge
libfreetype                  2.14.3           hce30654_0               conda-forge
libfreetype6                 2.14.3           hdfa99f5_0               conda-forge
libgcc                       15.2.0           hcbb3090_19              conda-forge
libgfortran                  15.2.0           h07b0088_19              conda-forge
libgfortran5                 15.2.0           hdae7583_19              conda-forge
libglib                      2.88.1           ha08bb59_2               conda-forge
libiconv                     1.18             h23cfdf5_2               conda-forge
libintl                      0.25.1           h493aca8_0               conda-forge
libjpeg-turbo                3.1.4.1          h84a0fba_0               conda-forge
liblapack                    3.11.0           7_hd9741b5_openblas      conda-forge
libllvm22                    22.1.5           h89af1be_1               conda-forge
liblzma                      5.8.3            h8088a28_0               conda-forge
libmpdec                     4.0.0            h84a0fba_1               conda-forge
libnetcdf                    4.10.0           nompi_h28ce51b_104       conda-forge
libnghttp2                   1.68.1           h8f3e76b_0               conda-forge
libntlm                      1.8              h5505292_0               conda-forge
libopenblas                  0.3.33           openmp_he657e61_0        conda-forge
libpng                       1.6.58           h132b30e_0               conda-forge
libpq                        18.4             ha770aab_0               conda-forge
libsodium                    1.0.22           h1a92334_1               conda-forge
libsqlite                    3.53.1           h1b79a29_0               conda-forge
libssh2                      1.11.1           h1590b86_0               conda-forge
libtiff                      4.7.1            h4030677_1               conda-forge
libwebp-base                 1.6.0            h07db88b_0               conda-forge
libxcb                       1.17.0           hdb1d25a_0               conda-forge
libxml2                      2.15.3           h5654f7c_0               conda-forge
libxml2-16                   2.15.3           h5ef1a60_0               conda-forge
libxslt                      1.1.43           hb2570ba_1               conda-forge
libzip                       1.11.2           h1336266_0               conda-forge
libzlib                      1.3.2            h8088a28_2               conda-forge
llvm-openmp                  22.1.5           hc7d1edf_1               conda-forge
lz4-c                        1.10.0           h286801f_1               conda-forge
matplotlib                   3.10.9           py313h39782a4_0          conda-forge
matplotlib-base              3.10.9           py313h36cb854_0          conda-forge
matplotlib-inline            0.2.2            pyhd8ed1ab_0             conda-forge
mercurial                    7.1.2            py313h0b74987_0          conda-forge
meson                        1.11.1           pyhcf101f3_0             conda-forge
meson-python                 0.19.0           pyh7e86bf3_2             conda-forge
munkres                      1.1.4            pyhd8ed1ab_1             conda-forge
ncurses                      6.6              h1d4f5a5_0               conda-forge
nest-asyncio                 1.6.0            pyhd8ed1ab_1             conda-forge
netcdf4                      1.7.4            nompi_py311hfd37af6_107  conda-forge
ninja                        1.13.2           h49c215f_0               conda-forge
numpy                        2.3.5            py313h16eae64_1          conda-forge
openjpeg                     2.5.4            hd9e9057_0               conda-forge
openldap                     2.6.13           hf7f56bc_0               conda-forge
openssl                      3.6.2            hd24854e_0               conda-forge
packaging                    25.0             pyh29332c3_1             conda-forge
parso                        0.8.7            pyhcf101f3_0             conda-forge
pcre2                        10.47            h30297fc_0               conda-forge
perl                         5.32.1           7_h4614cfb_perl5         conda-forge
pexpect                      4.9.0            pyhd8ed1ab_1             conda-forge
pillow                       12.2.0           py313h45e5a15_0          conda-forge
pip                          26.1.1           pyh145f28c_0             conda-forge
pixman                       0.46.4           h81086ad_1               conda-forge
platformdirs                 4.9.6            pyhcf101f3_0             conda-forge
pluggy                       1.6.0            pyhf9edf01_1             conda-forge
pmw                          2.1.1            py313h8f79df9_0          conda-forge
proj                         9.8.1            ha88f16d_0               conda-forge
prompt-toolkit               3.0.52           pyha770c72_0             conda-forge
psutil                       7.2.2            py313h6688731_0          conda-forge
pthread-stubs                0.4              hd74edd7_1002            conda-forge
ptyprocess                   0.7.0            pyhd8ed1ab_1             conda-forge
pure_eval                    0.2.3            pyhd8ed1ab_1             conda-forge
pygments                     2.20.0           pyhd8ed1ab_0             conda-forge
pyparsing                    3.3.2            pyhcf101f3_0             conda-forge
pyproj                       3.7.2            py313h9902f63_4          conda-forge
pyproject-metadata           0.11.0           pyhd8ed1ab_0             conda-forge
pyshp                        2.3.1            pyhd8ed1ab_1             conda-forge
pyside6                      6.11.1           py313h1eb42aa_1          conda-forge
pytest                       9.0.3            pyhc364b38_1             conda-forge
pytest-qt                    4.5.0            pyhdecd6ff_0             conda-forge
python                       3.13.13          h20e6be0_100_cp313       conda-forge
python-dateutil              2.9.0.post0      pyhe01879c_2             conda-forge
python-gil                   3.13.13          h4df99d1_100             conda-forge
python_abi                   3.13             8_cp313                  conda-forge
pyzmq                        27.1.0           py312h022ad19_2          conda-forge
qhull                        2020.2           h420ef59_5               conda-forge
qt6-main                     6.11.1           pl5321h01fc3ab_0         conda-forge
qtconsole-base               5.7.2            pyha770c72_0             conda-forge
qtpy                         2.4.3            pyhd8ed1ab_1             conda-forge
readline                     8.3              h46df422_0               conda-forge
ruff                         0.15.13          hbd3f8a3_0               conda-forge
scipy                        1.17.1           py313hc753a45_0          conda-forge
setuptools                   82.0.1           pyh332efcf_0             conda-forge
setuptools-scm               9.2.2            pyhd8ed1ab_0             conda-forge
shapely                      2.1.2            py313h10b2fc2_2          conda-forge
six                          1.17.0           pyhe01879c_1             conda-forge
smmap                        5.0.3            pyhd8ed1ab_0             conda-forge
snappy                       1.2.2            hada39a4_1               conda-forge
sqlite                       3.53.1           h85ec8f2_0               conda-forge
stack_data                   0.6.3            pyhd8ed1ab_1             conda-forge
tk                           8.6.13           h010d191_3               conda-forge
toml                         0.10.2           pyhcf101f3_3             conda-forge
tomli                        2.4.1            pyhcf101f3_0             conda-forge
tornado                      6.5.5            py313h0997733_0          conda-forge
traitlets                    5.15.0           pyhcf101f3_0             conda-forge
typing-extensions            4.15.0           h396c80c_0               conda-forge
typing_extensions            4.15.0           pyhcf101f3_0             conda-forge
tzdata                       2025c            hc9c84f9_1               conda-forge
wcwidth                      0.7.0            pyhd8ed1ab_0             conda-forge
xorg-libxau                  1.0.12           hc919400_1               conda-forge
xorg-libxdmcp                1.1.5            hc919400_1               conda-forge
zeromq                       4.3.5            h10816f8_11              conda-forge
zipp                         4.1.0            pyhcf101f3_0             conda-forge
zlib-ng                      2.3.3            hed4e4f5_1               conda-forge
zstd                         1.5.7            hbf9d68e_6               conda-forge
(pycodas) alesan@Alejandras-MacBook-Pro-2 ~ % xcode-select --install
xcode-select: note: Command line tools are already installed. Use "Software Update" in System Settings or the softwareupdate command line interface to install updates
(pycodas) alesan@Alejandras-MacBook-Pro-2 ~ % mkdir ~/adcpcode
mkdir ~/adcpcode/programs
mkdir ~/adcpcode/topog
(pycodas) alesan@Alejandras-MacBook-Pro-2 ~ % cd ~/adcpcode/programs
git clone -b stable https://currents.soest.hawaii.edu/git/uh-currents-group/shipboard-adcp/codas3.git
git clone -b stable https://currents.soest.hawaii.edu/git/uh-currents-group/shipboard-adcp/pycurrents.git
git clone -b stable https://currents.soest.hawaii.edu/git/uh-currents-group/shipboard-adcp/onship.git
Cloning into 'codas3'...
remote: Enumerating objects: 2479, done.
remote: Counting objects: 100% (7/7), done.
remote: Compressing objects: 100% (7/7), done.
remote: Total 2479 (delta 1), reused 2 (delta 0), pack-reused 2472 (from 1)
Receiving objects: 100% (2479/2479), 3.34 MiB | 67.12 MiB/s, done.
Resolving deltas: 100% (1686/1686), done.
Cloning into 'pycurrents'...
remote: Enumerating objects: 22485, done.
remote: Counting objects: 100% (331/331), done.
remote: Compressing objects: 100% (229/229), done.
remote: Total 22485 (delta 93), reused 331 (delta 93), pack-reused 22154 (from 1)
Receiving objects: 100% (22485/22485), 56.41 MiB | 62.38 MiB/s, done.
Resolving deltas: 100% (17160/17160), done.
Cloning into 'onship'...
remote: Enumerating objects: 10370, done.
remote: Counting objects: 100% (158/158), done.
remote: Compressing objects: 100% (70/70), done.
remote: Total 10370 (delta 96), reused 144 (delta 88), pack-reused 10212 (from 1)
Receiving objects: 100% (10370/10370), 10.71 MiB | 54.54 MiB/s, done.
Resolving deltas: 100% (6290/6290), done.
(pycodas) alesan@Alejandras-MacBook-Pro-2 programs % python --version
Python 3.13.13
(pycodas) alesan@Alejandras-MacBook-Pro-2 programs % cd ~/adcpcode/programs/codas3
./conda-install.sh
cd ~
+ date
+ ./waf configure --python_env
+ tee -a configure.log
/Users/alesan/adcpcode/programs/codas3/./waf:101: DeprecationWarning: Python 3.14 will, by default, filter extracted tar archives and reject files or modify their metadata. Use the filter argument to control this behavior.
  for x in t: t.extract(x)
Setting top to                           : /Users/alesan/adcpcode/programs/codas3 
Setting out to                           : /Users/alesan/adcpcode/programs/codas3/build 
Checking for 'clang' (C compiler)        : /usr/bin/clang 
Checking for code snippet                : yes 
Checking for endianness                  : little 
'AR' ['/usr/bin/ar']
'ARCH_ST' ['-arch']
'ARFLAGS' ['rcs']
'BINDIR' '/Users/alesan/miniforge3/envs/pycodas/bin'
'CC' ['/usr/bin/clang']
'CCLNK_SRC_F' []
'CCLNK_TGT_F' ['-o']
'CC_NAME' 'clang'
'CC_SRC_F' []
'CC_TGT_F' ['-c', '-o']
'CC_VERSION' ('17', '0', '0')
'CFLAGS' ['-fPIC']
'CFLAGS_MACBUNDLE' ['-fPIC']
'CFLAGS_cshlib' ['-fPIC']
'COMPILER_CC' 'clang'
'CPPPATH_ST' '-I%s'
'DEFINES' ['WAF_CONF_BIG_ENDIAN=0']
'DEFINES_ST' '-D%s'
'DEFINE_COMMENTS' {'WAF_CONF_BIG_ENDIAN': ''}
'DEST_BINFMT' 'mac-o'
'DEST_CPU' 'aarch64'
'DEST_OS' 'darwin'
'FRAMEWORKPATH_ST' '-F%s'
'FRAMEWORK_ST' ['-framework']
'LIBDIR' '/Users/alesan/miniforge3/envs/pycodas/lib'
'LIBPATH_ST' '-L%s'
'LIB_ST' '-l%s'
'LINKFLAGS_MACBUNDLE' ['-bundle', '-undefined', 'dynamic_lookup']
'LINKFLAGS_cshlib' ['-dynamiclib']
'LINKFLAGS_cstlib' []
'LINK_CC' ['/usr/bin/clang']
'PREFIX' '/Users/alesan/miniforge3/envs/pycodas'
'RPATH_ST' '-Wl,-rpath,%s'
'SHLIB_MARKER' []
'SONAME_ST' []
'STLIBPATH_ST' '-L%s'
'STLIB_MARKER' []
'STLIB_ST' '-l%s'
'cprogram_PATTERN' '%s'
'cshlib_PATTERN' 'lib%s.dylib'
'cstlib_PATTERN' 'lib%s.a'
'define_key' ['WAF_CONF_BIG_ENDIAN']
'libm' 'm'
'macbundle_PATTERN' '%s.bundle'
'undo_stack' []
'configure' finished successfully (1.175s)
+ date
+ ./waf build
+ tee -a build.log
Waf: Entering directory /Users/alesan/adcpcode/programs/codas3/build'
Using static library.
[  1/312] Compiling ocean/bvfreq.c
[  2/312] Compiling dbsource/dberror.c
[  3/312] Compiling dbsource/dbopsrch.c
[  4/312] Compiling dbsource/dblscale.c
[  5/312] Compiling dbsource/dbget_f.c
[  6/312] Compiling matlab/matscan.c
[  7/312] Compiling dbsource/time_.c
[  8/312] Compiling matlab/isnan.c
[  9/312] Compiling dbsource/dbgetput.c
[ 10/312] Compiling matlab/savematx.c
[ 11/312] Compiling matlab/savematc.c
[ 12/312] Compiling dbsource/mc0.c
[ 13/312] Compiling dbsource/dbput_f.c
[ 14/312] Compiling use_db/pos_io.c
[ 15/312] Compiling dbsource/dbset.c
[ 16/312] Compiling dbsource/find_def.c
[ 17/312] Compiling vstat/histo.c
[ 18/312] Compiling ioserv/errchk.c
[ 19/312] Compiling dbsource/dbcreate.c
[ 20/312] Compiling vector/s_regrli.c
[ 21/312] Compiling vector/scomplex.c
[ 22/312] Compiling ioserv/rept_msg.c
[ 23/312] Compiling vector/flatfile.c
[ 24/312] Compiling vector/fillgaps.c
[ 25/312] Compiling ioserv/yr4digit.c
[ 26/312] Compiling dbsource/scale.c
[ 27/312] Compiling dbsource/dbadd_f.c
[ 28/312] Compiling dbsource/io_nc.c
[ 29/312] Compiling vector/regrid.c
[ 30/312] Compiling vector/s_intgrd.c
[ 31/312] Compiling ioserv/misc.c
[ 32/312] Compiling vector/regridli.c
[ 33/312] Compiling vector/interp.c
[ 34/312] Compiling ioserv/getln_nc.c
[ 35/312] Compiling dbsource/dbmove.c
[ 36/312] Compiling vector/rotate.c
[ 37/312] Compiling vector/intgrid.c
[ 38/312] Compiling ioserv/new_ext.c
[ 39/312] Compiling vector/refcalc.c
[ 40/312] Compiling ocean/svel.c
[ 41/312] Compiling ioserv/errnf.c
[ 42/312] Compiling dbsource/dbloadsd.c
[ 43/312] Compiling dbsource/dbput.c
[ 44/312] Compiling ocean/theta.c
[ 45/312] Compiling ocean/press.c
[ 46/312] Compiling ioserv/option.c
[ 47/312] Compiling ocean/svan.c
[ 48/312] Compiling ocean/sal78.c
[ 49/312] Compiling ioserv/param.c
[ 50/312] Compiling dbsource/dbget_n.c
[ 51/312] Compiling ocean/grav.c
[ 52/312] Compiling ocean/depth.c
[ 53/312] Compiling dbsource/dbcommon.c
[ 54/312] Compiling ocean/atg.c
[ 55/312] Compiling dbsource/defstruc.c
[ 56/312] Compiling use_db/m_to_pos.c
[ 57/312] Compiling use_db/dbdpmask.c
[ 58/312] Compiling adcp/use_adcp/sscanpos.c
[ 59/312] Compiling use_db/check_db.c
[ 60/312] Compiling use_db/nblkprf.c
[ 61/312] Compiling use_db/dbputcnf.c
[ 62/312] Compiling adcp/use_adcp/readping.c
[ 63/312] Compiling dbsource/prtstruc.c
[ 64/312] Compiling dbsource/dbprtstr.c
[ 65/312] Compiling dbsource/dbdelete.c
[ 66/312] Compiling vector/s_regrid.c
[ 67/312] Compiling matlab/loadmatx.c
[ 68/312] Compiling use_db/checkdbf.c
[ 69/312] Compiling use_db/dbaddcnf.c
[ 70/312] Compiling dbsource/sort.c
[ 71/312] Compiling dbsource/prtspecl.c
[ 72/312] Compiling use_db/db_cnf.c
[ 73/312] Compiling use_db/jdtime.c
[ 74/312] Compiling vector/deriv.c
[ 75/312] Compiling use_db/chktim.c
[ 76/312] Compiling ioserv/main/main_cnt.c
[ 77/312] Compiling vector/vectors.c
[ 78/312] Compiling dbsource/dbshow.c
[ 79/312] Compiling dbsource/posn.c
[ 80/312] Compiling dbsource/dbget.c
[ 81/312] Compiling vector/matrix.c
[ 82/312] Compiling dbsource/unscale.c
[ 83/312] Compiling use_db/time_io.c
[ 84/312] Compiling dbsource/mem_.c
[ 85/312] Compiling use_db/pos_to_m.c
[ 86/312] Compiling dbsource/io_.c
[ 87/312] Compiling use_db/range_io.c
[ 88/312] Compiling vector/detrend.c
[ 89/312] Compiling vstat/unistat.c
[ 90/312] Compiling dbsource/prtarray.c
[ 91/312] Compiling use_db/lon_180.c
[ 92/312] Compiling vstat/mulstat.c
[ 93/312] Compiling util/chtime.c
[ 94/312] Compiling util/db2todb3.c
[ 95/312] Compiling util/vc.c
[ 96/312] Compiling util/delblk.c
[ 97/312] Compiling util/fixnbyte.c
[ 98/312] Compiling util/lst_prof.c
[ 99/312] Compiling util/lstblock.c
[100/312] Compiling util/mc1.c
[101/312] Compiling util/mkblkdir.c
[102/312] Compiling util/showdb.c
[103/312] Compiling util/to_date.c
[104/312] Compiling util/to_day.c
[105/312] Compiling util/to_week.c
[106/312] Compiling util/asc_dump.c
[107/312] Compiling util/blk_asc.c
[108/312] Compiling util/chprodid.c
[109/312] Compiling util/ldcodas.c
[110/312] Linking build/libcodas3_static.a
[111/312] Compiling util/codas_prefix.c
[112/312] Compiling ocean/cmd/atg.c
[113/312] Compiling ocean/cmd/bvfreq.c
[114/312] Compiling ocean/cmd/depth.c
[115/312] Compiling ocean/cmd/grav.c
[116/312] Compiling ocean/cmd/press.c
[117/312] Compiling ocean/cmd/sal78.c
[118/312] Compiling ocean/cmd/svan.c
[119/312] Compiling ocean/cmd/svel.c
[120/312] Compiling ocean/cmd/theta.c
[121/312] Compiling grid/llgrid.c
[122/312] Compiling grid/timegrid.c
[123/312] Compiling vecplot/vector.c
[124/312] Compiling vecplot/initps.c
[125/312] Compiling vecplot/drawmap.c
[126/312] Compiling vecplot/vecsub.c
[127/312] Compiling vecplot/extract.c
[128/312] Compiling profstat/profstat.c
[129/312] Compiling adcp/adcpsect/confile.c
[130/312] Compiling adcp/adcpsect/vgrid.c
[131/312] Compiling adcp/adcpsect/flux.c
[132/312] Compiling adcp/adcpsect/ctd.c
[133/312] Compiling adcp/adcpsect/adcpsect.c
[134/312] Compiling adcp/adcpsect/shipref.c
[135/312] Compiling adcp/adcpsect/detide.c
[136/312] Compiling adcp/adcpsect/seqcor.c
[137/312] Compiling adcp/adcpsect/innercor.c
[138/312] Compiling adcp/edit/depthcng.c
[139/312] Compiling adcp/edit/depth_change_os.c
[140/312] Compiling adcp/edit/depth_change_ec.c
[141/312] Compiling adcp/edit/dbedit.c
[142/312] Compiling adcp/edit/badbin.c
[143/312] Compiling adcp/edit/dbedit.c
[144/312] Compiling adcp/edit/unbadbin.c
[145/312] Compiling adcp/edit/blkscan.c
[146/312] Compiling adcp/edit/dbedit.c
[147/312] Compiling adcp/edit/botmpas3.c
[148/312] Linking build/util/chtime
[149/312] Linking build/util/db2todb3
[150/312] Linking build/util/delblk
[151/312] Linking build/util/fixnbyte
[152/312] Linking build/util/lst_prof
[153/312] Linking build/util/lstblock
[154/312] Linking build/util/mkblkdir
[155/312] Linking build/util/showdb
[156/312] Linking build/util/to_date
[157/312] Linking build/util/to_day
[158/312] Linking build/util/to_week
[159/312] Linking build/util/asc_dump
[160/312] Linking build/util/chprodid
[161/312] Linking build/util/ldcodas
[162/312] Linking build/util/codas_prefix
[163/312] Linking build/ocean/cmd/atg
[164/312] Linking build/ocean/cmd/bvfreq
[165/312] Linking build/ocean/cmd/depth
[166/312] Linking build/ocean/cmd/grav
[167/312] Linking build/ocean/cmd/press
[168/312] Linking build/ocean/cmd/sal78
[169/312] Linking build/ocean/cmd/svan
[170/312] Linking build/ocean/cmd/svel
[171/312] Linking build/ocean/cmd/theta
[172/312] Linking build/grid/llgrid
[173/312] Linking build/grid/timegrid
[174/312] Linking build/vecplot/vector
[175/312] Linking build/vecplot/extract
[176/312] Linking build/profstat/profstat
[177/312] Linking build/adcp/adcpsect/adcpsect
[178/312] Linking build/adcp/edit/depthcng
[179/312] Linking build/adcp/edit/depth_change_os
[180/312] Linking build/adcp/edit/depth_change_ec
[181/312] Linking build/adcp/edit/badbin
[182/312] Linking build/adcp/edit/unbadbin
[183/312] Linking build/adcp/edit/blkscan
[184/312] Compiling adcp/edit/dbedit.c
[185/312] Compiling adcp/edit/fix_temp.c
[186/312] Compiling adcp/edit/fix_hdg.c
[187/312] Compiling adcp/edit/dbedit.c
[188/312] Compiling adcp/edit/flag.c
[189/312] Compiling adcp/edit/dbedit.c
[190/312] Compiling adcp/edit/getmat.c
[191/312] Compiling adcp/edit/last_85.c
[192/312] Compiling adcp/edit/dbedit.c
[193/312] Compiling adcp/edit/logscan.c
[194/312] Compiling adcp/edit/dbedit.c
[195/312] Compiling adcp/edit/set_top.c
[196/312] Linking build/adcp/edit/fix_temp
[197/312] Compiling adcp/edit/dbedit.c
[198/312] Linking build/adcp/edit/fix_hdg
[199/312] Linking build/adcp/edit/botmpas3
[200/312] Compiling adcp/edit/updscan.c
[201/312] Compiling adcp/edit/dbedit.c
[202/312] Linking build/adcp/edit/getmat
[203/312] Compiling adcp/edit/dbupdate.c
[204/312] Linking build/adcp/edit/flag
[205/312] Linking build/adcp/edit/set_top
[206/312] Compiling adcp/edit/dbedit.c
[207/312] Linking build/adcp/edit/last_85
[208/312] Compiling adcp/edit/fillgap.c
[209/312] Linking build/adcp/edit/logscan
[210/312] Compiling adcp/edit/dbedit.c
[211/312] Compiling adcp/edit/newflag.c
[212/312] Compiling adcp/edit/setflags.c
[213/312] Linking build/adcp/edit/updscan
[214/312] Compiling adcp/edit/set_lgb.c
[215/312] Compiling adcp/edit/dbedit.c
[216/312] Compiling adcp/cal/is_jump.c
[217/312] Linking build/adcp/edit/dbupdate
[218/312] Compiling adcp/cal/arrdep.c
[219/312] Compiling adcp/cal/read_ref.c
[220/312] Linking build/adcp/edit/fillgap
[221/312] Compiling adcp/cal/get_ref.c
[222/312] Compiling adcp/cal/refabsbt.c
[223/312] Compiling adcp/cal/read_ref.c
[224/312] Linking build/adcp/edit/setflags
[225/312] Compiling adcp/cal/fix2vel.c
[226/312] Compiling adcp/cal/is_jump.c
[227/312] Linking build/adcp/edit/newflag
[228/312] Compiling adcp/cal/is_turn.c
[229/312] Compiling adcp/cal/timslip.c
[230/312] Compiling adcp/cal/vrefabs.c
[231/312] Compiling adcp/cal/fminbr.c
[232/312] Linking build/adcp/edit/set_lgb
[233/312] Compiling adcp/cal/get_ref.c
[234/312] Compiling adcp/cal/read_ref.c
[235/312] Compiling adcp/cal/fix2vel.c
[236/312] Linking build/adcp/cal/arrdep
[237/312] Linking build/adcp/cal/refabsbt
[238/312] Compiling adcp/cal/rotate.c
[239/312] Compiling adcp/cal/rotnav.c
[240/312] Compiling adcp/cal/fix_bt_ss_bug.c
[241/312] Compiling adcp/scanload/loadping.c
[242/312] Compiling adcp/scanload/scanping.c
[243/312] Compiling adcp/ping2mat/ping2mat.c
[244/312] Compiling adcp/util/bt2tobt3.c
[245/312] Compiling adcp/util/convadcp.c
[246/312] Compiling adcp/util/convadc2.c
[247/312] Compiling adcp/util/fixunits.c
[248/312] Compiling adcp/util/getnav.c
[249/312] Linking build/adcp/cal/fix_bt_ss_bug
[250/312] Compiling adcp/util/lst_temp.c
[251/312] Linking build/adcp/cal/rotnav
[252/312] Linking build/adcp/cal/timslip
[253/312] Linking build/adcp/cal/rotate
[254/312] Linking build/adcp/scanload/scanping
[255/312] Linking build/adcp/ping2mat/ping2mat
[256/312] Linking build/adcp/scanload/loadping
[257/312] Linking build/adcp/util/convadcp
[258/312] Linking build/adcp/util/convadc2
[259/312] Linking build/adcp/util/bt2tobt3
[260/312] Linking build/adcp/util/getnav
[261/312] Linking build/adcp/util/fixunits
[262/312] Compiling adcp/util/lst_npings.c
[263/312] Compiling adcp/util/lst_hdg.c
[264/312] Compiling adcp/util/pgbin.c
[265/312] Compiling adcp/util/set_bit.c
[266/312] Compiling adcp/util/setpmask.c
[267/312] Compiling adcp/util/lst_conf.c
[268/312] Compiling adcp/util/lst_alfa.c
[269/312] Linking build/adcp/util/lst_temp
[270/312] Compiling adcp/nav/edfix.c
[271/312] Compiling adcp/nav/lst_btrk.c
[272/312] Compiling adcp/nav/nav2dir.c
[273/312] Compiling adcp/nav/putnav.c
[274/312] Compiling adcp/nav/put_txy.c
[275/312] Linking build/adcp/util/lst_npings
[276/312] Linking build/adcp/util/lst_hdg
[277/312] Linking build/adcp/util/pgbin
[278/312] Linking build/adcp/util/setpmask
[279/312] Linking build/adcp/util/set_bit
[280/312] Linking build/adcp/util/lst_conf
[281/312] Compiling adcp/nav/put_tuv.c
[282/312] Linking build/adcp/nav/edfix
[283/312] Linking build/adcp/util/lst_alfa
[284/312] Linking build/adcp/nav/lst_btrk
[285/312] Linking build/adcp/nav/nav2dir
[286/312] Linking build/adcp/nav/put_txy
[287/312] Compiling adcp/nav/ref2mat.c
[288/312] Compiling adcp/nav/fix2vel.c
[289/312] Compiling adcp/nav/refabs.c
[290/312] Compiling adcp/nav/read_ref.c
[291/312] Linking build/adcp/nav/putnav
[292/312] Linking build/adcp/nav/put_tuv
[293/312] Compiling adcp/nav/sm2mat.c
[294/312] Compiling adcp/nav/smoothr.c
[295/312] Compiling adcp/nav/optpos.c
[296/312] Compiling adcp/nav/ubprint.c
[297/312] Compiling adcp/nav/ubwrite.c
[298/312] Linking build/adcp/nav/ref2mat
[299/312] Compiling adcp/nav/nmea_gps.c
[300/312] Compiling ctd/load/load_bot.c
[301/312] Compiling ctd/load/load_ctd.c
[302/312] Compiling ctd/load/load_odf.c
[303/312] Compiling ctd/util/conv_ctd.c
[304/312] Linking build/adcp/nav/refabs
[305/312] Linking build/adcp/nav/sm2mat
[306/312] Linking build/adcp/nav/smoothr
[307/312] Linking build/ctd/load/load_bot
[308/312] Linking build/adcp/nav/ubprint
[309/312] Linking build/ctd/load/load_ctd
[310/312] Linking build/ctd/load/load_odf
[311/312] Linking build/ctd/util/conv_ctd
[312/312] Linking build/adcp/nav/nmea_gps
Waf: Leaving directory /Users/alesan/adcpcode/programs/codas3/build'
'build' finished successfully (4.263s)
+ date
+ ./waf install
+ tee -a install.log
Waf: Entering directory /Users/alesan/adcpcode/programs/codas3/build'
Using static library.
+ install /Users/alesan/miniforge3/envs/pycodas/lib/libcodas3_static.a (from build/libcodas3_static.a)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/chtime (from build/util/chtime)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/db2todb3 (from build/util/db2todb3)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/delblk (from build/util/delblk)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/fixnbyte (from build/util/fixnbyte)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/lst_prof (from build/util/lst_prof)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/lstblock (from build/util/lstblock)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/mkblkdir (from build/util/mkblkdir)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/showdb (from build/util/showdb)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/to_date (from build/util/to_date)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/to_day (from build/util/to_day)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/to_week (from build/util/to_week)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/asc_dump (from build/util/asc_dump)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/chprodid (from build/util/chprodid)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/ldcodas (from build/util/ldcodas)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/codas_prefix (from build/util/codas_prefix)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/atg (from build/ocean/cmd/atg)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/bvfreq (from build/ocean/cmd/bvfreq)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/depth (from build/ocean/cmd/depth)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/grav (from build/ocean/cmd/grav)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/press (from build/ocean/cmd/press)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/sal78 (from build/ocean/cmd/sal78)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/svan (from build/ocean/cmd/svan)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/svel (from build/ocean/cmd/svel)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/theta (from build/ocean/cmd/theta)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/llgrid (from build/grid/llgrid)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/timegrid (from build/grid/timegrid)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/vector (from build/vecplot/vector)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/extract (from build/vecplot/extract)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/profstat (from build/profstat/profstat)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/adcpsect (from build/adcp/adcpsect/adcpsect)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/depthcng (from build/adcp/edit/depthcng)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/depth_change_os (from build/adcp/edit/depth_change_os)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/depth_change_ec (from build/adcp/edit/depth_change_ec)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/badbin (from build/adcp/edit/badbin)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/unbadbin (from build/adcp/edit/unbadbin)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/blkscan (from build/adcp/edit/blkscan)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/botmpas3 (from build/adcp/edit/botmpas3)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/fix_temp (from build/adcp/edit/fix_temp)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/fix_hdg (from build/adcp/edit/fix_hdg)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/flag (from build/adcp/edit/flag)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/getmat (from build/adcp/edit/getmat)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/last_85 (from build/adcp/edit/last_85)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/logscan (from build/adcp/edit/logscan)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/set_top (from build/adcp/edit/set_top)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/updscan (from build/adcp/edit/updscan)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/dbupdate (from build/adcp/edit/dbupdate)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/fillgap (from build/adcp/edit/fillgap)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/newflag (from build/adcp/edit/newflag)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/setflags (from build/adcp/edit/setflags)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/set_lgb (from build/adcp/edit/set_lgb)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/arrdep (from build/adcp/cal/arrdep)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/refabsbt (from build/adcp/cal/refabsbt)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/timslip (from build/adcp/cal/timslip)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/rotate (from build/adcp/cal/rotate)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/rotnav (from build/adcp/cal/rotnav)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/fix_bt_ss_bug (from build/adcp/cal/fix_bt_ss_bug)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/loadping (from build/adcp/scanload/loadping)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/scanping (from build/adcp/scanload/scanping)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/ping2mat (from build/adcp/ping2mat/ping2mat)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/bt2tobt3 (from build/adcp/util/bt2tobt3)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/convadcp (from build/adcp/util/convadcp)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/convadc2 (from build/adcp/util/convadc2)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/fixunits (from build/adcp/util/fixunits)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/getnav (from build/adcp/util/getnav)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/lst_temp (from build/adcp/util/lst_temp)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/lst_npings (from build/adcp/util/lst_npings)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/lst_hdg (from build/adcp/util/lst_hdg)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/pgbin (from build/adcp/util/pgbin)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/set_bit (from build/adcp/util/set_bit)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/setpmask (from build/adcp/util/setpmask)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/lst_conf (from build/adcp/util/lst_conf)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/lst_alfa (from build/adcp/util/lst_alfa)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/edfix (from build/adcp/nav/edfix)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/lst_btrk (from build/adcp/nav/lst_btrk)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/nav2dir (from build/adcp/nav/nav2dir)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/putnav (from build/adcp/nav/putnav)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/put_txy (from build/adcp/nav/put_txy)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/put_tuv (from build/adcp/nav/put_tuv)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/ref2mat (from build/adcp/nav/ref2mat)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/refabs (from build/adcp/nav/refabs)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/sm2mat (from build/adcp/nav/sm2mat)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/smoothr (from build/adcp/nav/smoothr)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/ubprint (from build/adcp/nav/ubprint)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/nmea_gps (from build/adcp/nav/nmea_gps)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/load_bot (from build/ctd/load/load_bot)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/load_ctd (from build/ctd/load/load_ctd)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/load_odf (from build/ctd/load/load_odf)
+ install /Users/alesan/miniforge3/envs/pycodas/bin/conv_ctd (from build/ctd/util/conv_ctd)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/config.h (from build/include/config.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/adcp.h (from include/adcp.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/adcp_old.h (from include/adcp_old.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/adcpflag.h (from include/adcpflag.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/cal.h (from include/cal.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/common.h (from include/common.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/data_id.h (from include/data_id.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/data_lst.h (from include/data_lst.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/dbdcl.h (from include/dbdcl.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/dbedit.h (from include/dbedit.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/dbext.h (from include/dbext.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/dbglo.h (from include/dbglo.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/dbhost.h (from include/dbhost.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/dbinc.h (from include/dbinc.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/dblscale.h (from include/dblscale.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/dpmask.h (from include/dpmask.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/find_def.h (from include/find_def.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/geninc.h (from include/geninc.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/io_.h (from include/io_.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/io_nc.h (from include/io_nc.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/ioserv.h (from include/ioserv.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/jdtime.h (from include/jdtime.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/matfile.h (from include/matfile.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/mc0.h (from include/mc0.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/mem_.h (from include/mem_.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/misc.h (from include/misc.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/ocean.h (from include/ocean.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/pos_to_m.h (from include/pos_to_m.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/posn.h (from include/posn.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/profmask.h (from include/profmask.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/prtarray.h (from include/prtarray.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/prtspecl.h (from include/prtspecl.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/prtstruc.h (from include/prtstruc.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/readping.h (from include/readping.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/scale.h (from include/scale.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/sort.h (from include/sort.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/time_.h (from include/time_.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/unscale.h (from include/unscale.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/use_adcp.h (from include/use_adcp.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/use_db.h (from include/use_db.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/userbuff.h (from include/userbuff.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/valuelst.h (from include/valuelst.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/vector.h (from include/vector.h)
+ install /Users/alesan/miniforge3/envs/pycodas/include/codas3/vstat.h (from include/vstat.h)
Waf: Leaving directory /Users/alesan/adcpcode/programs/codas3/build'
'install' finished successfully (0.090s)
(pycodas) alesan@Alejandras-MacBook-Pro-2 ~ % cd ~/adcpcode/programs/pycurrents
pip install --no-build-isolation .
Processing ./.
  Preparing metadata (pyproject.toml) ... done
Building wheels for collected packages: pycurrents
  Building wheel for pycurrents (pyproject.toml) ... done
  Created wheel for pycurrents: filename=pycurrents-0.0.0-cp313-cp313-macosx_11_0_arm64.whl size=2014390 sha256=2274beaacbf812a36ef217a07fcf859b7ae1a257999afdb21a6fa63088f9c9f7
  Stored in directory: /private/var/folders/5c/smywlzq57_qg2mnkknkggdqh0000gn/T/pip-ephem-wheel-cache-jvvetb13/wheels/69/41/b6/8cb3356e1de4977855dd49fe205e6e581231c71760dcb8601c
Successfully built pycurrents
Installing collected packages: pycurrents
Successfully installed pycurrents-0.0.0
(pycodas) alesan@Alejandras-MacBook-Pro-2 pycurrents % cd ../onship
pip install --no-build-isolation .
cd ~
Processing ./.
  Preparing metadata (pyproject.toml) ... done
Building wheels for collected packages: onship
  Building wheel for onship (pyproject.toml) ... done
  Created wheel for onship: filename=onship-2026.2.2.0.dev2135+gb45e1e868-cp313-cp313-macosx_26_0_arm64.whl size=1206221 sha256=e012d5382d45974f2148075517f9de56916d3e0b97e28a9522ac91f17170b798
  Stored in directory: /private/var/folders/5c/smywlzq57_qg2mnkknkggdqh0000gn/T/pip-ephem-wheel-cache-1ndjpoj2/wheels/10/a8/dd/4ef36b1c6694bce150043d661f2bf2f5425c99b1c5a8ab5570
Successfully built onship
Installing collected packages: onship
Successfully installed onship-2026.2.2.0.dev2135+gb45e1e868
(pycodas) alesan@Alejandras-MacBook-Pro-2 ~ % cd ~/adcpcode/programs
curl -O https://currents.soest.hawaii.edu/docs/zipped/adcp_doc.zip
unzip adcp_doc.zip
curl -O https://currents.soest.hawaii.edu/docs/zipped/codas_demos.zip
unzip codas_demos.zip
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100 66.5M  100 66.5M    0     0  88.3M      0 --:--:-- --:--:-- --:--:-- 88.2M
Archive:  adcp_doc.zip
   creating: adcp_doc
   creating: adcp_doc/_downloads
   creating: adcp_doc/_downloads/b201a93a1cc5311fd9b766efd19e6b5c
  inflating: adcp_doc/_downloads/b201a93a1cc5311fd9b766efd19e6b5c/codas_processing_m1-m2.yml  
   creating: adcp_doc/_downloads/2059e0b012e99babc7448d86eb36e1b0
  inflating: adcp_doc/_downloads/2059e0b012e99babc7448d86eb36e1b0/uhdas_overview.pdf  
   creating: adcp_doc/_downloads/3259747eb59191f1a6fdfde427d004a7
  inflating: adcp_doc/_downloads/3259747eb59191f1a6fdfde427d004a7/trigger.pdf  
   creating: adcp_doc/_downloads/ce45eb9ec9885a4c390a80f421fa7852
  inflating: adcp_doc/_downloads/ce45eb9ec9885a4c390a80f421fa7852/load_getmat.m  
   creating: adcp_doc/_downloads/aaf979775ac603fe0aed3f8ab48ca583
  inflating: adcp_doc/_downloads/aaf979775ac603fe0aed3f8ab48ca583/ADCP_checklist_kilomoana.pdf  
   creating: adcp_doc/_downloads/3b04696bc0b4168ce675f969d2a6d82e
  inflating: adcp_doc/_downloads/3b04696bc0b4168ce675f969d2a6d82e/UHDAS_VMDAS2.pdf  
   creating: adcp_doc/_downloads/11b87e0235d073047a292f0ca2e642e5
  inflating: adcp_doc/_downloads/11b87e0235d073047a292f0ca2e642e5/codas_focal_vbox.txt  
   creating: adcp_doc/_downloads/c3a77cffd8275a62d72683daa6632fea
  inflating: adcp_doc/_downloads/c3a77cffd8275a62d72683daa6632fea/original_manual.pdf  
   creating: adcp_doc/_downloads/ebcdceebbc8a9adf76e76dde1d8e1353
  inflating: adcp_doc/_downloads/ebcdceebbc8a9adf76e76dde1d8e1353/UHDAS_101_cheatsheet.pdf  
   creating: adcp_doc/_downloads/f2cd0959da125f33ac207ec4693831df
  inflating: adcp_doc/_downloads/f2cd0959da125f33ac207ec4693831df/M1-M2_install_steps.txt  
   creating: adcp_doc/_downloads/1b1dee4ef81e36a0135db3c56654c08e
  inflating: adcp_doc/_downloads/1b1dee4ef81e36a0135db3c56654c08e/wtcal1.png  
   creating: adcp_doc/_downloads/1bbf9fe7142be462ef441b63cd6587a5
  inflating: adcp_doc/_downloads/1bbf9fe7142be462ef441b63cd6587a5/codas_processing_intel.yml  
   creating: adcp_doc/_downloads/927bf55d16d33e0334e4b4ad453c2e69
  inflating: adcp_doc/_downloads/927bf55d16d33e0334e4b4ad453c2e69/HOWTO-start-UHDAS-GUI-and-collect-data-remotely-without-screen-share.pdf  
   creating: adcp_doc/_downloads/a28a31c042dac8fa338dc3c8abd015d0
  inflating: adcp_doc/_downloads/a28a31c042dac8fa338dc3c8abd015d0/load_netcdf.m  
   creating: adcp_doc/codas_setup
   creating: adcp_doc/codas_setup/updating
  inflating: adcp_doc/codas_setup/updating/index.html  
  inflating: adcp_doc/codas_setup/updating/hg_update.html  
  inflating: adcp_doc/codas_setup/updating/hg_intro.html  
   creating: adcp_doc/codas_setup/virtual_computer
  inflating: adcp_doc/codas_setup/virtual_computer/vbox_import.html  
  inflating: adcp_doc/codas_setup/virtual_computer/vbox_configuration.html  
  inflating: adcp_doc/codas_setup/virtual_computer/vbox_startup.html  
  inflating: adcp_doc/codas_setup/virtual_computer/vbox_reset_MAC.html  
  inflating: adcp_doc/codas_setup/virtual_computer/index.html  
  inflating: adcp_doc/codas_setup/virtual_computer/vbox_navigation.html  
  inflating: adcp_doc/codas_setup/virtual_computer/vbox_intro.html  
  inflating: adcp_doc/codas_setup/index.html  
   creating: adcp_doc/codas_setup/anaconda_install
  inflating: adcp_doc/codas_setup/anaconda_install/index.html  
   creating: adcp_doc/codas_setup/test_it
  inflating: adcp_doc/codas_setup/test_it/index.html  
   creating: adcp_doc/codas_setup/codas_config
  inflating: adcp_doc/codas_setup/codas_config/topo.html  
  inflating: adcp_doc/codas_setup/codas_config/index.html  
  inflating: adcp_doc/codas_setup/codas_config/toml.html  
  inflating: adcp_doc/codas_setup/codas_config/compile_install.html  
  inflating: adcp_doc/codas_setup/codas_config/zip_codas.html  
  inflating: adcp_doc/codas_setup/codas_config/hg_codas.html  
   creating: adcp_doc/codas_setup/ubuntu_install
  inflating: adcp_doc/codas_setup/ubuntu_install/index.html  
   creating: adcp_doc/ADCP_INTERPRETATION
   creating: adcp_doc/ADCP_INTERPRETATION/interpretation
   creating: adcp_doc/ADCP_INTERPRETATION/interpretation/adcp-gps-horizontal-offset
  inflating: adcp_doc/ADCP_INTERPRETATION/interpretation/adcp-gps-horizontal-offset/index.html  
   creating: adcp_doc/ADCP_INTERPRETATION/interpretation/scatteringlayer
  inflating: adcp_doc/ADCP_INTERPRETATION/interpretation/scatteringlayer/index.html  
   creating: adcp_doc/ADCP_INTERPRETATION/interpretation/refsource_uvship_nav
  inflating: adcp_doc/ADCP_INTERPRETATION/interpretation/refsource_uvship_nav/index.html  
   creating: adcp_doc/ADCP_INTERPRETATION/interpretation/electric_interference
  inflating: adcp_doc/ADCP_INTERPRETATION/interpretation/electric_interference/index.html  
   creating: adcp_doc/ADCP_INTERPRETATION/interpretation/triggering
  inflating: adcp_doc/ADCP_INTERPRETATION/interpretation/triggering/index.html  
   creating: adcp_doc/ADCP_INTERPRETATION/interpretation/singleping_ringing
  inflating: adcp_doc/ADCP_INTERPRETATION/interpretation/singleping_ringing/index.html  
  inflating: adcp_doc/ADCP_INTERPRETATION/interpretation/index.html  
   creating: adcp_doc/ADCP_INTERPRETATION/interpretation/underway_bias_crosstrack
  inflating: adcp_doc/ADCP_INTERPRETATION/interpretation/underway_bias_crosstrack/index.html  
   creating: adcp_doc/ADCP_INTERPRETATION/interpretation/bottom_interference
  inflating: adcp_doc/ADCP_INTERPRETATION/interpretation/bottom_interference/index.html  
   creating: adcp_doc/ADCP_INTERPRETATION/interpretation/underway_bias_scalefactor
  inflating: adcp_doc/ADCP_INTERPRETATION/interpretation/underway_bias_scalefactor/index.html  
   creating: adcp_doc/ADCP_INTERPRETATION/interpretation/singleping_bubbles
  inflating: adcp_doc/ADCP_INTERPRETATION/interpretation/singleping_bubbles/index.html  
   creating: adcp_doc/ADCP_INTERPRETATION/interpretation/acoustic_interference_avg
  inflating: adcp_doc/ADCP_INTERPRETATION/interpretation/acoustic_interference_avg/index.html  
   creating: adcp_doc/ADCP_INTERPRETATION/interpretation/previous_ping_interference
  inflating: adcp_doc/ADCP_INTERPRETATION/interpretation/previous_ping_interference/index.html  
   creating: adcp_doc/ADCP_INTERPRETATION/interpretation/acoustic_electric_noise
  inflating: adcp_doc/ADCP_INTERPRETATION/interpretation/acoustic_electric_noise/index.html  
   creating: adcp_doc/ADCP_INTERPRETATION/interpretation/alongtrack_bias_avg
  inflating: adcp_doc/ADCP_INTERPRETATION/interpretation/alongtrack_bias_avg/index.html  
   creating: adcp_doc/ADCP_INTERPRETATION/interpretation/acoustic_interference_singleping
  inflating: adcp_doc/ADCP_INTERPRETATION/interpretation/acoustic_interference_singleping/index.html  
   creating: adcp_doc/ADCP_INTERPRETATION/interpretation/average_ringing
  inflating: adcp_doc/ADCP_INTERPRETATION/interpretation/average_ringing/index.html  
   creating: adcp_doc/ADCP_INTERPRETATION/interpretation/singleping_weather
  inflating: adcp_doc/ADCP_INTERPRETATION/interpretation/singleping_weather/index.html  
  inflating: adcp_doc/ADCP_INTERPRETATION/index.html  
   creating: adcp_doc/ADCP_INTERPRETATION/adcp_failure_modes
  inflating: adcp_doc/ADCP_INTERPRETATION/adcp_failure_modes/index.html  
   creating: adcp_doc/ADCP_INTERPRETATION/realistic_ranges
  inflating: adcp_doc/ADCP_INTERPRETATION/realistic_ranges/index.html  
   creating: adcp_doc/ADCP_INTERPRETATION/adcp_transformations
  inflating: adcp_doc/ADCP_INTERPRETATION/adcp_transformations/index.html  
  inflating: adcp_doc/.buildinfo     
  inflating: adcp_doc/genindex.html  
 extracting: adcp_doc/objects.inv    
  inflating: adcp_doc/search.html    
  inflating: adcp_doc/index.html     
   creating: adcp_doc/_sources
   creating: adcp_doc/_sources/codas_setup
   creating: adcp_doc/_sources/codas_setup/updating
  inflating: adcp_doc/_sources/codas_setup/updating/hg_intro.rst.txt  
  inflating: adcp_doc/_sources/codas_setup/updating/hg_update.rst.txt  
  inflating: adcp_doc/_sources/codas_setup/updating/index.rst.txt  
   creating: adcp_doc/_sources/codas_setup/virtual_computer
  inflating: adcp_doc/_sources/codas_setup/virtual_computer/vbox_startup.rst.txt  
  inflating: adcp_doc/_sources/codas_setup/virtual_computer/vbox_navigation.rst.txt  
  inflating: adcp_doc/_sources/codas_setup/virtual_computer/vbox_intro.rst.txt  
  inflating: adcp_doc/_sources/codas_setup/virtual_computer/vbox_reset_MAC.rst.txt  
  inflating: adcp_doc/_sources/codas_setup/virtual_computer/index.rst.txt  
  inflating: adcp_doc/_sources/codas_setup/virtual_computer/vbox_import.rst.txt  
  inflating: adcp_doc/_sources/codas_setup/virtual_computer/vbox_configuration.rst.txt  
   creating: adcp_doc/_sources/codas_setup/anaconda_install
  inflating: adcp_doc/_sources/codas_setup/anaconda_install/index.rst.txt  
   creating: adcp_doc/_sources/codas_setup/test_it
  inflating: adcp_doc/_sources/codas_setup/test_it/index.rst.txt  
  inflating: adcp_doc/_sources/codas_setup/index.rst.txt  
   creating: adcp_doc/_sources/codas_setup/codas_config
  inflating: adcp_doc/_sources/codas_setup/codas_config/hg_codas.rst.txt  
  inflating: adcp_doc/_sources/codas_setup/codas_config/zip_codas.rst.txt  
  inflating: adcp_doc/_sources/codas_setup/codas_config/toml.rst.txt  
  inflating: adcp_doc/_sources/codas_setup/codas_config/topo.rst.txt  
  inflating: adcp_doc/_sources/codas_setup/codas_config/index.rst.txt  
  inflating: adcp_doc/_sources/codas_setup/codas_config/compile_install.rst.txt  
   creating: adcp_doc/_sources/codas_setup/ubuntu_install
  inflating: adcp_doc/_sources/codas_setup/ubuntu_install/index.rst.txt  
   creating: adcp_doc/_sources/ADCP_INTERPRETATION
   creating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation
   creating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/adcp-gps-horizontal-offset
  inflating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/adcp-gps-horizontal-offset/index.rst.txt  
   creating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/scatteringlayer
  inflating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/scatteringlayer/index.rst.txt  
   creating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/refsource_uvship_nav
  inflating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/refsource_uvship_nav/index.rst.txt  
   creating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/electric_interference
  inflating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/electric_interference/index.rst.txt  
   creating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/triggering
  inflating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/triggering/index.rst.txt  
   creating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/singleping_ringing
  inflating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/singleping_ringing/index.rst.txt  
   creating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/underway_bias_crosstrack
  inflating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/underway_bias_crosstrack/index.rst.txt  
   creating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/bottom_interference
  inflating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/bottom_interference/index.rst.txt  
   creating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/underway_bias_scalefactor
  inflating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/underway_bias_scalefactor/index.rst.txt  
   creating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/singleping_bubbles
  inflating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/singleping_bubbles/index.rst.txt  
   creating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/acoustic_interference_avg
  inflating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/acoustic_interference_avg/index.rst.txt  
   creating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/previous_ping_interference
  inflating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/previous_ping_interference/index.rst.txt  
   creating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/acoustic_electric_noise
  inflating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/acoustic_electric_noise/index.rst.txt  
   creating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/alongtrack_bias_avg
  inflating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/alongtrack_bias_avg/index.rst.txt  
   creating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/acoustic_interference_singleping
  inflating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/acoustic_interference_singleping/index.rst.txt  
  inflating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/index.rst.txt  
   creating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/average_ringing
  inflating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/average_ringing/index.rst.txt  
   creating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/singleping_weather
  inflating: adcp_doc/_sources/ADCP_INTERPRETATION/interpretation/singleping_weather/index.rst.txt  
   creating: adcp_doc/_sources/ADCP_INTERPRETATION/adcp_failure_modes
  inflating: adcp_doc/_sources/ADCP_INTERPRETATION/adcp_failure_modes/index.rst.txt  
  inflating: adcp_doc/_sources/ADCP_INTERPRETATION/index.rst.txt  
   creating: adcp_doc/_sources/ADCP_INTERPRETATION/realistic_ranges
  inflating: adcp_doc/_sources/ADCP_INTERPRETATION/realistic_ranges/index.rst.txt  
   creating: adcp_doc/_sources/ADCP_INTERPRETATION/adcp_transformations
  inflating: adcp_doc/_sources/ADCP_INTERPRETATION/adcp_transformations/index.rst.txt  
  inflating: adcp_doc/_sources/acknowledgements.rst.txt  
   creating: adcp_doc/_sources/APPENDIX
   creating: adcp_doc/_sources/APPENDIX/image_wrappers
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/UHDAS_101_cheatsheet.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/daily_report.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/rot36_topog.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/low_shallow_percentgood.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/rot2_uvt.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/rot28_uvt.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/ADCP_GUI_Settings.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/ping-mode-topofig_annot.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/rot0_topogt.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/rot0_uv.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/ping-mode-panels_annot.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/km1001c_proc_annot.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/btwt_caltxt.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/ResetEditButton.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/5minute_annot.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/compare_mode_gui_plot_tab_annot.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/Atsea_Monitoring_ashtech_gyrodh.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/rot2_topogt.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/trigger.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/rot2uvt.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/RDI_trigger_settings.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/uhdas_codas_processing_flowchart_annot.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/edit_mode_dataviewer_topofig_annot.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/rot36_uvt.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/ping-mode-plot_tab_annot.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/compare_mode_dataviewer_topofig_annot.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/lastens_annotated.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/bottom_edit.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/edit_mode_gui_plot_tab_annot.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/edit_mode_dataviewer_selector_annot.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/vmdas_info_notes.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/vmdas_reform_staged_annot.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/beam_orientation.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/edit_mode_dataviewer_panels_annot.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/vmdas_info_reform.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/view_mode_gui_plot_tab_annot.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/CW_CX.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/fill_database_processing_steps.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/rot28_topog.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/glossary-tree_annot.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/uhdas_overview.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/compare_mode_dataviewer_panels_annot.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/atsea_web.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/UHDAS_Monitorbad.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/data_proc03b_annot.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/rot36uvt.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/edit_mode_gui_panel_threshold_annot.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/index.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/30min_timer.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/Atsea_Monitoring_phins_gyrodh.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/Atsea_Monitoring_posmv_gyrodh.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/vmdas_reform_NxR_annot.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/wire_EV.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/rot0_topog.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/calibration_bad.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/calibration.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/adjust_threshold.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/rot36_uv.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/rot36_topogt.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/ringing_annot.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/rot28_uv.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/rot2_topog.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/5minute_timer.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/proc_starter_components.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/heading_device.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/uhdas_codas_processing_flowchart.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/rot0_uvt.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/edit_mode_masking.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/bottom_edit_tool.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/rot28_topogt.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/rot2_uv.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/image_wrappers/atsea_athome.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/file_support_table.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/changes_updates.rst.txt  
   creating: adcp_doc/_sources/APPENDIX/VmDAS_ops
  inflating: adcp_doc/_sources/APPENDIX/VmDAS_ops/index.rst.txt  
   creating: adcp_doc/_sources/APPENDIX/txtfile_wrappers
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/os75bb_LTA.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/make_dirs_for_demos.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/pingdata_commands.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/quick_adcp_help.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/q_py_enr_heredoc.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/quick_ltapy_help.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/ps0918_os75bb_LTA_info.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/btwt_caltxt.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/quick_flow.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/calibration_aliases.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/vmdas_quicklta_proc_help.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/km1001c_proc.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/ue4_doc.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/singleping_overview.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/uhdaspy_demodir_cheatsheet.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/quick_postproc_help.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/vmdas2uhdas.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/reform_defs.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/ps0918_LTA_postproc.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/available_demos.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/uvshipxy.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/directory-layout.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/quick_flow_annot_old.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/codas_focal_vbox.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/q_py_heredoc.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/q_py_lta_heredoc.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/ps0918_ltaproc_lta_info.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/os75bb_ENR.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/km1001c_fullproc_os38nb.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/manual_anaconda_install.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/cruise_info.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/quick_pingdata_help.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/km1001c_postproc_os38nb.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/quick_uhdaspy_help.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/quick_enrpy_help.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/quick_outline.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/index.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/uhdaspy_anydir_cheatsheet.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/gbin_lesson.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/calib_new_instrument.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/adcpsect_cnt.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/windows_weirdness.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/ps0918_os75bb_LTA_proc.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/vmdas_commandline_summary.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/patch_hcorr_help.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/adcptree_summary_help.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/quick_adcp_vardoc_help.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/ps0918_enrproc_os75bb.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/txtfile_wrappers/dataviewer_help.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/index.rst.txt  
   creating: adcp_doc/_sources/APPENDIX/pflags_doc
  inflating: adcp_doc/_sources/APPENDIX/pflags_doc/pflag_details.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/pflags_doc/dpmask.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/pflags_doc/index.rst.txt  
  inflating: adcp_doc/_sources/APPENDIX/best_practices.rst.txt  
   creating: adcp_doc/_sources/APPENDIX/uhdas_vmdas_comparison
  inflating: adcp_doc/_sources/APPENDIX/uhdas_vmdas_comparison/index.rst.txt  
   creating: adcp_doc/_sources/UHDAS_OPERATIONS
   creating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_computer
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_computer/UHDAS_States.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_computer/install.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_computer/UHDAS_Flags.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_computer/repeaters.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_computer/Configuration_Files.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_computer/UHDAS_Actions.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_computer/index.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_computer/headless.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_computer/TS_What_Should_Be_Updating.rst.txt  
   creating: adcp_doc/_sources/UHDAS_OPERATIONS/HOWTOs
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/HOWTOs/tk_terminal.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/HOWTOs/Calibration.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/HOWTOs/convert_uhdas_dates.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/HOWTOs/stopping_email.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/HOWTOs/temporarily_securing_one_adcp.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/HOWTOs/three-beams.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/HOWTOs/index.rst.txt  
   creating: adcp_doc/_sources/UHDAS_OPERATIONS/troubleshooting
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/troubleshooting/TS_Hopelessly_Confused.rst.txt  
   creating: adcp_doc/_sources/UHDAS_OPERATIONS/troubleshooting/speedlog
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/troubleshooting/speedlog/index.rst.txt  
   creating: adcp_doc/_sources/UHDAS_OPERATIONS/troubleshooting/diagnostic_tools
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/troubleshooting/diagnostic_tools/index.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/troubleshooting/zmq_troubleshooting.rst.txt  
   creating: adcp_doc/_sources/UHDAS_OPERATIONS/troubleshooting/ntp
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/troubleshooting/ntp/index.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/troubleshooting/index.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/troubleshooting/TS_StrangeState.rst.txt  
   creating: adcp_doc/_sources/UHDAS_OPERATIONS/troubleshooting/serial_nmea
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/troubleshooting/serial_nmea/seapath_diagnostics.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/troubleshooting/serial_nmea/mahrs_diagnostics.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/troubleshooting/serial_nmea/posmv_diagnostics.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/troubleshooting/serial_nmea/index.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/troubleshooting/serial_nmea/ashtech_diagnostics.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/index.rst.txt  
   creating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_techdoc
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_techdoc/UHDAS_GuiTour.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_techdoc/UHDAS_cheatsheets.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_techdoc/ADCP_instructions.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_techdoc/index.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_techdoc/best_practices.rst.txt  
   creating: adcp_doc/_sources/UHDAS_OPERATIONS/monitoring
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/monitoring/Atsea_Monitoring.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/monitoring/ticketing.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/monitoring/index.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/monitoring/Uhdas_Dailyreport.rst.txt  
   creating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_atsea
   creating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_atsea/web-site-tour
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_atsea/web-site-tour/index.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_atsea/unols_datapolicy.rst.txt  
   creating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_atsea/adcp_access
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_atsea/adcp_access/agetmat_output.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_atsea/adcp_access/matlab_read_raw.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_atsea/adcp_access/extract_adcpsect.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_atsea/adcp_access/read_adcpsect.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_atsea/adcp_access/read_netCDF.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_atsea/adcp_access/netcdf_output.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_atsea/adcp_access/python_read_raw.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_atsea/adcp_access/python_read_codas.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_atsea/adcp_access/index.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_atsea/adcp_access/extract_netCDF.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_atsea/adcp_access/read_getmat.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_atsea/adcp_access/extract-getmat.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_atsea/uhdas_data_atsea.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_atsea/Conventions.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_atsea/UHDAS_CODAS_Overview.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_atsea/index.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_atsea/meta_data.rst.txt  
  inflating: adcp_doc/_sources/UHDAS_OPERATIONS/UHDAS_atsea/cruisedir_contents.rst.txt  
  inflating: adcp_doc/_sources/index.rst.txt  
   creating: adcp_doc/_sources/codas_doc
   creating: adcp_doc/_sources/codas_doc/CODAS_docs
   creating: adcp_doc/_sources/codas_doc/CODAS_docs/pingdemo
  inflating: adcp_doc/_sources/codas_doc/CODAS_docs/pingdemo/CODAS_mat_pingdemo.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/CODAS_docs/pingdemo/watertrk_python.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/CODAS_docs/pingdemo/CODAS_py_pingdemo.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/CODAS_docs/pingdemo/btrk_python.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/CODAS_docs/pingdemo/timslip5.rst.txt  
   creating: adcp_doc/_sources/codas_doc/quickpy_doc
  inflating: adcp_doc/_sources/codas_doc/quickpy_doc/quick_help.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/quickadcp_overview.rst.txt  
   creating: adcp_doc/_sources/codas_doc/adcp_database_maker
  inflating: adcp_doc/_sources/codas_doc/adcp_database_maker/postprocessing_LTA.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/adcp_database_maker/adcp_database_maker_ENR.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/adcp_database_maker/adcp_database_maker_LTA.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/adcp_database_maker/index.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/adcp_database_maker/adcp_database_maker_uhdas.rst.txt  
   creating: adcp_doc/_sources/codas_doc/dataviewer
  inflating: adcp_doc/_sources/codas_doc/dataviewer/underway_bias.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/dataviewer/dataviewer_edit_mode.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/dataviewer/dataviewer_view_mode.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/dataviewer/amplitude.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/dataviewer/manual_undo_editing.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/dataviewer/dataviewer_compare_mode.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/dataviewer/dataviewer_reset_editing.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/dataviewer/phase.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/dataviewer/xducer_dxdy.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/dataviewer/dataviewer_ping_mode.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/dataviewer/index.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/dataviewer/jitter_cutoff.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/dataviewer/dataviewer_save_settings.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/pingdata_note.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/demos_intro.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/introduction.rst.txt  
   creating: adcp_doc/_sources/codas_doc/postprocessing
  inflating: adcp_doc/_sources/codas_doc/postprocessing/postprocessing_uhdas.rst.txt  
   creating: adcp_doc/_sources/codas_doc/troubleshooting_datasets
  inflating: adcp_doc/_sources/codas_doc/troubleshooting_datasets/exploring_uhdas_data.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/troubleshooting_datasets/finding_information.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/troubleshooting_datasets/index.rst.txt  
   creating: adcp_doc/_sources/codas_doc/troubleshooting_datasets/special_processing_issues
  inflating: adcp_doc/_sources/codas_doc/troubleshooting_datasets/special_processing_issues/older_cruise_compatibility.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/troubleshooting_datasets/special_processing_issues/adcp_nc2odv.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/troubleshooting_datasets/special_processing_issues/reuse_editing.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/troubleshooting_datasets/special_processing_issues/regenerating_uhdas.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/troubleshooting_datasets/special_processing_issues/add_wtpoints.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/troubleshooting_datasets/special_processing_issues/index.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/troubleshooting_datasets/special_processing_issues/add_btpoints.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/troubleshooting_datasets/special_processing_issues/mixed_pings.rst.txt  
   creating: adcp_doc/_sources/codas_doc/troubleshooting_datasets/special_processing_issues/calibration
  inflating: adcp_doc/_sources/codas_doc/troubleshooting_datasets/special_processing_issues/calibration/index.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/tools_used.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/index.rst.txt  
   creating: adcp_doc/_sources/codas_doc/commandline_demos
  inflating: adcp_doc/_sources/codas_doc/commandline_demos/commandline_from_scratch_uhdas.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/commandline_demos/commandline_from_scratch_ENR.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/commandline_demos/index.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/commandline_demos/commandline_quick_lta.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/commandline_demos/commandline_from_scratch_LTA.rst.txt  
  inflating: adcp_doc/_sources/codas_doc/patch_hcorr.rst.txt  
   creating: adcp_doc/_sources/codas_doc/quick_web
  inflating: adcp_doc/_sources/codas_doc/quick_web/index.rst.txt  
   creating: adcp_doc/_sources/glossary
  inflating: adcp_doc/_sources/glossary/index.rst.txt  
  inflating: adcp_doc/acknowledgements.html  
   creating: adcp_doc/_static
  inflating: adcp_doc/_static/sphinxdoc.css  
  inflating: adcp_doc/_static/plus.png  
  inflating: adcp_doc/_static/uhdas_icon_small.png  
  inflating: adcp_doc/_static/searchtools.js  
  inflating: adcp_doc/_static/minus.png  
  inflating: adcp_doc/_static/navigation.png  
  inflating: adcp_doc/_static/basic.css  
  inflating: adcp_doc/_static/documentation_options.js  
  inflating: adcp_doc/_static/doctools.js  
  inflating: adcp_doc/_static/contents.png  
  inflating: adcp_doc/_static/language_data.js  
  inflating: adcp_doc/_static/ADCP_checklist_kilomoana.html  
 extracting: adcp_doc/_static/file.png  
  inflating: adcp_doc/_static/sphinx_highlight.js  
  inflating: adcp_doc/_static/pygments.css  
   creating: adcp_doc/APPENDIX
  inflating: adcp_doc/APPENDIX/best_practices.html  
   creating: adcp_doc/APPENDIX/image_wrappers
  inflating: adcp_doc/APPENDIX/image_wrappers/view_mode_gui_plot_tab_annot.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/rot0_uvt.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/glossary-tree_annot.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/UHDAS_101_cheatsheet.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/UHDAS_Monitorbad.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/compare_mode_dataviewer_panels_annot.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/heading_device.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/calibration_bad.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/atsea_web.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/rot36_topogt.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/vmdas_reform_NxR_annot.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/wire_EV.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/rot28_topogt.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/edit_mode_masking.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/ping-mode-panels_annot.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/uhdas_codas_processing_flowchart_annot.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/5minute_annot.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/RDI_trigger_settings.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/km1001c_proc_annot.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/rot36_topog.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/edit_mode_dataviewer_topofig_annot.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/proc_starter_components.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/Atsea_Monitoring_ashtech_gyrodh.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/atsea_athome.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/compare_mode_dataviewer_topofig_annot.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/rot2_topogt.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/30min_timer.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/rot2_uv.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/ping-mode-plot_tab_annot.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/daily_report.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/rot2_topog.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/index.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/5minute_timer.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/edit_mode_gui_panel_threshold_annot.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/vmdas_reform_staged_annot.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/CW_CX.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/data_proc03b_annot.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/rot36_uv.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/uhdas_codas_processing_flowchart.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/ResetEditButton.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/edit_mode_gui_plot_tab_annot.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/uhdas_overview.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/trigger.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/Atsea_Monitoring_posmv_gyrodh.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/fill_database_processing_steps.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/rot0_topogt.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/ADCP_GUI_Settings.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/beam_orientation.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/rot0_topog.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/bottom_edit.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/ping-mode-topofig_annot.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/rot2uvt.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/rot2_uvt.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/rot28_uv.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/rot36uvt.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/compare_mode_gui_plot_tab_annot.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/rot0_uv.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/btwt_caltxt.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/edit_mode_dataviewer_panels_annot.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/lastens_annotated.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/bottom_edit_tool.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/rot28_uvt.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/calibration.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/rot28_topog.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/Atsea_Monitoring_phins_gyrodh.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/adjust_threshold.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/vmdas_info_notes.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/vmdas_info_reform.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/ringing_annot.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/rot36_uvt.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/low_shallow_percentgood.html  
  inflating: adcp_doc/APPENDIX/image_wrappers/edit_mode_dataviewer_selector_annot.html  
  inflating: adcp_doc/APPENDIX/index.html  
   creating: adcp_doc/APPENDIX/VmDAS_ops
  inflating: adcp_doc/APPENDIX/VmDAS_ops/index.html  
   creating: adcp_doc/APPENDIX/txtfile_wrappers
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/vmdas_commandline_summary.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/ps0918_os75bb_LTA_info.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/quick_outline.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/gbin_lesson.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/dataviewer_help.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/patch_hcorr_help.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/uhdaspy_anydir_cheatsheet.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/adcpsect_cnt.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/reform_defs.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/singleping_overview.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/km1001c_fullproc_os38nb.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/ps0918_os75bb_LTA_proc.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/index.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/quick_flow_annot_old.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/q_py_enr_heredoc.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/vmdas2uhdas.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/vmdas_quicklta_proc_help.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/quick_adcp_help.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/adcptree_summary_help.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/quick_postproc_help.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/q_py_lta_heredoc.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/ps0918_LTA_postproc.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/make_dirs_for_demos.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/quick_ltapy_help.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/quick_adcp_vardoc_help.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/manual_anaconda_install.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/calibration_aliases.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/uhdaspy_demodir_cheatsheet.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/quick_enrpy_help.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/quick_flow.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/quick_pingdata_help.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/ps0918_ltaproc_lta_info.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/directory-layout.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/cruise_info.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/km1001c_proc.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/btwt_caltxt.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/pingdata_commands.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/uvshipxy.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/windows_weirdness.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/available_demos.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/ue4_doc.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/ps0918_enrproc_os75bb.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/km1001c_postproc_os38nb.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/codas_focal_vbox.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/os75bb_LTA.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/os75bb_ENR.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/calib_new_instrument.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/q_py_heredoc.html  
  inflating: adcp_doc/APPENDIX/txtfile_wrappers/quick_uhdaspy_help.html  
  inflating: adcp_doc/APPENDIX/changes_updates.html  
  inflating: adcp_doc/APPENDIX/file_support_table.html  
   creating: adcp_doc/APPENDIX/pflags_doc
  inflating: adcp_doc/APPENDIX/pflags_doc/dpmask.html  
  inflating: adcp_doc/APPENDIX/pflags_doc/index.html  
  inflating: adcp_doc/APPENDIX/pflags_doc/pflag_details.html  
   creating: adcp_doc/APPENDIX/uhdas_vmdas_comparison
  inflating: adcp_doc/APPENDIX/uhdas_vmdas_comparison/index.html  
   creating: adcp_doc/UHDAS_OPERATIONS
   creating: adcp_doc/UHDAS_OPERATIONS/UHDAS_computer
  inflating: adcp_doc/UHDAS_OPERATIONS/UHDAS_computer/TS_What_Should_Be_Updating.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/UHDAS_computer/UHDAS_Actions.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/UHDAS_computer/index.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/UHDAS_computer/UHDAS_States.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/UHDAS_computer/headless.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/UHDAS_computer/UHDAS_Flags.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/UHDAS_computer/repeaters.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/UHDAS_computer/install.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/UHDAS_computer/Configuration_Files.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/index.html  
   creating: adcp_doc/UHDAS_OPERATIONS/HOWTOs
  inflating: adcp_doc/UHDAS_OPERATIONS/HOWTOs/tk_terminal.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/HOWTOs/temporarily_securing_one_adcp.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/HOWTOs/index.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/HOWTOs/Calibration.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/HOWTOs/stopping_email.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/HOWTOs/three-beams.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/HOWTOs/convert_uhdas_dates.html  
   creating: adcp_doc/UHDAS_OPERATIONS/troubleshooting
  inflating: adcp_doc/UHDAS_OPERATIONS/troubleshooting/zmq_troubleshooting.html  
   creating: adcp_doc/UHDAS_OPERATIONS/troubleshooting/speedlog
  inflating: adcp_doc/UHDAS_OPERATIONS/troubleshooting/speedlog/index.html  
   creating: adcp_doc/UHDAS_OPERATIONS/troubleshooting/diagnostic_tools
  inflating: adcp_doc/UHDAS_OPERATIONS/troubleshooting/diagnostic_tools/index.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/troubleshooting/index.html  
   creating: adcp_doc/UHDAS_OPERATIONS/troubleshooting/ntp
  inflating: adcp_doc/UHDAS_OPERATIONS/troubleshooting/ntp/index.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/troubleshooting/TS_Hopelessly_Confused.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/troubleshooting/TS_StrangeState.html  
   creating: adcp_doc/UHDAS_OPERATIONS/troubleshooting/serial_nmea
  inflating: adcp_doc/UHDAS_OPERATIONS/troubleshooting/serial_nmea/posmv_diagnostics.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/troubleshooting/serial_nmea/index.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/troubleshooting/serial_nmea/seapath_diagnostics.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/troubleshooting/serial_nmea/mahrs_diagnostics.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/troubleshooting/serial_nmea/ashtech_diagnostics.html  
   creating: adcp_doc/UHDAS_OPERATIONS/UHDAS_techdoc
  inflating: adcp_doc/UHDAS_OPERATIONS/UHDAS_techdoc/best_practices.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/UHDAS_techdoc/UHDAS_cheatsheets.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/UHDAS_techdoc/ADCP_instructions.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/UHDAS_techdoc/index.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/UHDAS_techdoc/UHDAS_GuiTour.html  
   creating: adcp_doc/UHDAS_OPERATIONS/monitoring
  inflating: adcp_doc/UHDAS_OPERATIONS/monitoring/ticketing.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/monitoring/index.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/monitoring/Atsea_Monitoring.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/monitoring/Uhdas_Dailyreport.html  
   creating: adcp_doc/UHDAS_OPERATIONS/UHDAS_atsea
  inflating: adcp_doc/UHDAS_OPERATIONS/UHDAS_atsea/unols_datapolicy.html  
   creating: adcp_doc/UHDAS_OPERATIONS/UHDAS_atsea/web-site-tour
  inflating: adcp_doc/UHDAS_OPERATIONS/UHDAS_atsea/web-site-tour/index.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/UHDAS_atsea/Conventions.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/UHDAS_atsea/UHDAS_CODAS_Overview.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/UHDAS_atsea/index.html  
   creating: adcp_doc/UHDAS_OPERATIONS/UHDAS_atsea/adcp_access
  inflating: adcp_doc/UHDAS_OPERATIONS/UHDAS_atsea/adcp_access/agetmat_output.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/UHDAS_atsea/adcp_access/read_adcpsect.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/UHDAS_atsea/adcp_access/python_read_raw.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/UHDAS_atsea/adcp_access/index.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/UHDAS_atsea/adcp_access/extract_netCDF.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/UHDAS_atsea/adcp_access/extract-getmat.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/UHDAS_atsea/adcp_access/python_read_codas.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/UHDAS_atsea/adcp_access/read_netCDF.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/UHDAS_atsea/adcp_access/read_getmat.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/UHDAS_atsea/adcp_access/netcdf_output.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/UHDAS_atsea/adcp_access/extract_adcpsect.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/UHDAS_atsea/adcp_access/matlab_read_raw.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/UHDAS_atsea/uhdas_data_atsea.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/UHDAS_atsea/meta_data.html  
  inflating: adcp_doc/UHDAS_OPERATIONS/UHDAS_atsea/cruisedir_contents.html  
   creating: adcp_doc/codas_doc
   creating: adcp_doc/codas_doc/CODAS_docs
   creating: adcp_doc/codas_doc/CODAS_docs/pingdemo
  inflating: adcp_doc/codas_doc/CODAS_docs/pingdemo/btrk_python.html  
  inflating: adcp_doc/codas_doc/CODAS_docs/pingdemo/watertrk_python.html  
  inflating: adcp_doc/codas_doc/CODAS_docs/pingdemo/CODAS_mat_pingdemo.html  
  inflating: adcp_doc/codas_doc/CODAS_docs/pingdemo/CODAS_py_pingdemo.html  
  inflating: adcp_doc/codas_doc/CODAS_docs/pingdemo/timslip5.html  
   creating: adcp_doc/codas_doc/quickpy_doc
  inflating: adcp_doc/codas_doc/quickpy_doc/quick_help.html  
  inflating: adcp_doc/codas_doc/quickadcp_overview.html  
  inflating: adcp_doc/codas_doc/tools_used.html  
  inflating: adcp_doc/codas_doc/index.html  
   creating: adcp_doc/codas_doc/adcp_database_maker
  inflating: adcp_doc/codas_doc/adcp_database_maker/adcp_database_maker_uhdas.html  
  inflating: adcp_doc/codas_doc/adcp_database_maker/index.html  
  inflating: adcp_doc/codas_doc/adcp_database_maker/adcp_database_maker_ENR.html  
  inflating: adcp_doc/codas_doc/adcp_database_maker/adcp_database_maker_LTA.html  
  inflating: adcp_doc/codas_doc/adcp_database_maker/postprocessing_LTA.html  
   creating: adcp_doc/codas_doc/dataviewer
  inflating: adcp_doc/codas_doc/dataviewer/manual_undo_editing.html  
  inflating: adcp_doc/codas_doc/dataviewer/dataviewer_edit_mode.html  
  inflating: adcp_doc/codas_doc/dataviewer/amplitude.html  
  inflating: adcp_doc/codas_doc/dataviewer/dataviewer_view_mode.html  
  inflating: adcp_doc/codas_doc/dataviewer/underway_bias.html  
  inflating: adcp_doc/codas_doc/dataviewer/index.html  
  inflating: adcp_doc/codas_doc/dataviewer/jitter_cutoff.html  
  inflating: adcp_doc/codas_doc/dataviewer/phase.html  
  inflating: adcp_doc/codas_doc/dataviewer/dataviewer_save_settings.html  
  inflating: adcp_doc/codas_doc/dataviewer/xducer_dxdy.html  
  inflating: adcp_doc/codas_doc/dataviewer/dataviewer_reset_editing.html  
  inflating: adcp_doc/codas_doc/dataviewer/dataviewer_ping_mode.html  
  inflating: adcp_doc/codas_doc/dataviewer/dataviewer_compare_mode.html  
  inflating: adcp_doc/codas_doc/demos_intro.html  
   creating: adcp_doc/codas_doc/postprocessing
  inflating: adcp_doc/codas_doc/postprocessing/postprocessing_uhdas.html  
  inflating: adcp_doc/codas_doc/pingdata_note.html  
   creating: adcp_doc/codas_doc/troubleshooting_datasets
  inflating: adcp_doc/codas_doc/troubleshooting_datasets/finding_information.html  
  inflating: adcp_doc/codas_doc/troubleshooting_datasets/index.html  
  inflating: adcp_doc/codas_doc/troubleshooting_datasets/exploring_uhdas_data.html  
   creating: adcp_doc/codas_doc/troubleshooting_datasets/special_processing_issues
  inflating: adcp_doc/codas_doc/troubleshooting_datasets/special_processing_issues/index.html  
  inflating: adcp_doc/codas_doc/troubleshooting_datasets/special_processing_issues/reuse_editing.html  
  inflating: adcp_doc/codas_doc/troubleshooting_datasets/special_processing_issues/add_wtpoints.html  
  inflating: adcp_doc/codas_doc/troubleshooting_datasets/special_processing_issues/mixed_pings.html  
  inflating: adcp_doc/codas_doc/troubleshooting_datasets/special_processing_issues/regenerating_uhdas.html  
  inflating: adcp_doc/codas_doc/troubleshooting_datasets/special_processing_issues/adcp_nc2odv.html  
  inflating: adcp_doc/codas_doc/troubleshooting_datasets/special_processing_issues/older_cruise_compatibility.html  
   creating: adcp_doc/codas_doc/troubleshooting_datasets/special_processing_issues/calibration
  inflating: adcp_doc/codas_doc/troubleshooting_datasets/special_processing_issues/calibration/index.html  
  inflating: adcp_doc/codas_doc/troubleshooting_datasets/special_processing_issues/add_btpoints.html  
  inflating: adcp_doc/codas_doc/patch_hcorr.html  
  inflating: adcp_doc/codas_doc/introduction.html  
   creating: adcp_doc/codas_doc/commandline_demos
  inflating: adcp_doc/codas_doc/commandline_demos/commandline_quick_lta.html  
  inflating: adcp_doc/codas_doc/commandline_demos/commandline_from_scratch_ENR.html  
  inflating: adcp_doc/codas_doc/commandline_demos/commandline_from_scratch_uhdas.html  
  inflating: adcp_doc/codas_doc/commandline_demos/index.html  
  inflating: adcp_doc/codas_doc/commandline_demos/commandline_from_scratch_LTA.html  
   creating: adcp_doc/codas_doc/quick_web
  inflating: adcp_doc/codas_doc/quick_web/index.html  
  inflating: adcp_doc/searchindex.js  
   creating: adcp_doc/_images
  inflating: adcp_doc/_images/select_data_annot.png  
  inflating: adcp_doc/_images/full_underwaybias.png  
  inflating: adcp_doc/_images/edit_mode_gui_plot_tab_annot0.png  
  inflating: adcp_doc/_images/60-runquick.png  
  inflating: adcp_doc/_images/lta-vs-enr-unedited.png  
  inflating: adcp_doc/_images/03a_raw02.png  
  inflating: adcp_doc/_images/compare_mode_dataviewer_panels_annot.png  
  inflating: adcp_doc/_images/02_stats_interpolated.png  
  inflating: adcp_doc/_images/instructions_examplebad_03.png  
  inflating: adcp_doc/_images/60-after-quickadcp_annot.png  
  inflating: adcp_doc/_images/singleping_editing_interference.png  
  inflating: adcp_doc/_images/config-success.png  
  inflating: adcp_doc/_images/HUD_calibration.png  
  inflating: adcp_doc/_images/calibration.png  
  inflating: adcp_doc/_images/before-apply-edits.png  
  inflating: adcp_doc/_images/os75nb_diurnal_3days.png  
  inflating: adcp_doc/_images/Screenshot_2017-09-20_00-38-53.png  
  inflating: adcp_doc/_images/Atsea_Monitoring_posmv_gyrodh.png  
  inflating: adcp_doc/_images/rot0_topog.png  
  inflating: adcp_doc/_images/kn195_03_kn2009_027_14400.png  
  inflating: adcp_doc/_images/LTA_databasemaker_automated_dirs.png  
  inflating: adcp_doc/_images/09-save.png  
  inflating: adcp_doc/_images/compare_mode_dataviewer_topofig_annot.png  
  inflating: adcp_doc/_images/ringing2.png  
  inflating: adcp_doc/_images/default-control_annot.png  
  inflating: adcp_doc/_images/bottom_interference_afteredit.png  
  inflating: adcp_doc/_images/os75nb_electricnoise.png  
  inflating: adcp_doc/_images/os75bb_biased.png  
  inflating: adcp_doc/_images/panels_after_all_editing.png  
  inflating: adcp_doc/_images/btcaluv_diag.png  
  inflating: adcp_doc/_images/virtualization-disabled_expanded.png  
  inflating: adcp_doc/_images/Screenshot_2017-09-20_00-40-39.png  
  inflating: adcp_doc/_images/5.png  
  inflating: adcp_doc/_images/08-enshcorr_annotated.png  
  inflating: adcp_doc/_images/os75nb_otherping01.png  
  inflating: adcp_doc/_images/os75nb_panelN.png  
  inflating: adcp_doc/_images/seapath_gyrodh.png  
  inflating: adcp_doc/_images/glossary-tree_annot.png  
  inflating: adcp_doc/_images/02b_transformation.png  
  inflating: adcp_doc/_images/03f_runquick.png  
  inflating: adcp_doc/_images/rot2_uvt.png  
  inflating: adcp_doc/_images/13-reform-uhdas-before-set-up-proc_cfg_annot.png  
  inflating: adcp_doc/_images/uhdas-vmdas-acquisition-serial-setup.png  
  inflating: adcp_doc/_images/adjust_threshold.png  
  inflating: adcp_doc/_images/os75_noisy_temps.png  
  inflating: adcp_doc/_images/os75nb_shallow.png  
  inflating: adcp_doc/_images/atsea_athome.png  
  inflating: adcp_doc/_images/LTA_databasemaker_automated_manual_dirs.png  
  inflating: adcp_doc/_images/vbox_introB.png  
  inflating: adcp_doc/_images/Screenshot_2017-09-20_00-37-39.png  
  inflating: adcp_doc/_images/scattering_layer_old_example.png  
  inflating: adcp_doc/_images/11-reform-vmdas-before-make-conversion_annot.png  
  inflating: adcp_doc/_images/beams-scattering-velocity.png  
  inflating: adcp_doc/_images/reset-edits01.png  
  inflating: adcp_doc/_images/instructions_examplebad_01.png  
  inflating: adcp_doc/_images/os75bb_lastens.png  
  inflating: adcp_doc/_images/ws1409_calib.png  
  inflating: adcp_doc/_images/os38bb_scatteringlayer.png  
  inflating: adcp_doc/_images/rot36_uv.png  
  inflating: adcp_doc/_images/manually-edit-in-seclector-window.png  
  inflating: adcp_doc/_images/06-choose-uhdas-style-data_annot.png  
  inflating: adcp_doc/_images/heading_device.png  
  inflating: adcp_doc/_images/01_control.png  
  inflating: adcp_doc/_images/NBP_400m_underwaybias_xy.png  
  inflating: adcp_doc/_images/UHDAS_101_cheatsheet.pdf  
  inflating: adcp_doc/_images/vmdas_form_before_annot.png  
  inflating: adcp_doc/_images/pingdemo_btcal.png  
  inflating: adcp_doc/_images/30min_timer.png  
  inflating: adcp_doc/_images/nb150_bubbles02.png  
  inflating: adcp_doc/_images/00-before_annotated.png  
  inflating: adcp_doc/_images/45-proc-starter-after-make-config_annot.png  
  inflating: adcp_doc/_images/52-before-processing_annot.png  
  inflating: adcp_doc/_images/os75nb_clean00.png  
  inflating: adcp_doc/_images/edit_mode_km1001_postproc_layout_annot.png  
  inflating: adcp_doc/_images/51-before-qpy_cnt_annot.png  
  inflating: adcp_doc/_images/bias_ringing.png  
  inflating: adcp_doc/_images/reform_vmdas_prefilled.png  
  inflating: adcp_doc/_images/sensor_cfg_01.png  
  inflating: adcp_doc/_images/dirlayout_afterconfig_annot.png  
  inflating: adcp_doc/_images/ping-mode-control2_annot.png  
  inflating: adcp_doc/_images/tk_terminal_diagnostics.png  
  inflating: adcp_doc/_images/instructions_checkdaily_05.png  
  inflating: adcp_doc/_images/50-qpy.png  
  inflating: adcp_doc/_images/instructions_checkdaily_02.png  
  inflating: adcp_doc/_images/5minute_timer.png  
  inflating: adcp_doc/_images/postprocessing_step3.png  
  inflating: adcp_doc/_images/os75_underway_bias.png  
  inflating: adcp_doc/_images/50-adcptree-before-procdir_annot.png  
  inflating: adcp_doc/_images/proc-starter-manual-annotated.png  
  inflating: adcp_doc/_images/scattering_layer_diagram.png  
  inflating: adcp_doc/_images/03a_raw01.png  
  inflating: adcp_doc/_images/vbox_import.png  
  inflating: adcp_doc/_images/04_transformation.png  
  inflating: adcp_doc/_images/default-topo.png  
  inflating: adcp_doc/_images/choose-network-adapter.png  
  inflating: adcp_doc/_images/ggatime_posmv_zoom.png  
  inflating: adcp_doc/_images/dbmaker-overview.png  
  inflating: adcp_doc/_images/ringing_annot.png  
  inflating: adcp_doc/_images/demo_layout_dirs.png  
  inflating: adcp_doc/_images/Screenshot_2017-09-20_00-38-12.png  
  inflating: adcp_doc/_images/vbox_terminalwindow.png  
  inflating: adcp_doc/_images/dbmaker_vmdas_launch.png  
  inflating: adcp_doc/_images/xducerxy_annot.png  
  inflating: adcp_doc/_images/UHDAS_Control.png  
  inflating: adcp_doc/_images/npings_2012.png  
  inflating: adcp_doc/_images/low_shallow_percentgood.png  
  inflating: adcp_doc/_images/rot2_topog.png  
  inflating: adcp_doc/_images/daily_report.png  
  inflating: adcp_doc/_images/os38nb_ice.png  
  inflating: adcp_doc/_images/uhdas-vmdas-monitoring.png  
  inflating: adcp_doc/_images/manually-edit-in-selector-window-unmask00.png  
  inflating: adcp_doc/_images/vmdas_reform_staged_annot.png  
  inflating: adcp_doc/_images/codas_demos_layout.png  
  inflating: adcp_doc/_images/04c_transformation.png  
  inflating: adcp_doc/_images/wh300_otherping.png  
  inflating: adcp_doc/_images/ping-mode-plot_tab_annot.png  
  inflating: adcp_doc/_images/05-vmdas-to-uhdas-after_annot.png  
  inflating: adcp_doc/_images/ping-mode-editing_annot.png  
  inflating: adcp_doc/_images/panels.png  
  inflating: adcp_doc/_images/view-mode-panels.png  
  inflating: adcp_doc/_images/04b_transformation.png  
  inflating: adcp_doc/_images/os75bb_cont.png  
  inflating: adcp_doc/_images/after_dbmaker_lta_annot.png  
  inflating: adcp_doc/_images/after-splash_new_annot.png  
  inflating: adcp_doc/_images/selectYourProject_new2_annot.png  
  inflating: adcp_doc/_images/prev-ping.png  
  inflating: adcp_doc/_images/os75bb_electricnoise.png  
  inflating: adcp_doc/_images/speedlog.png  
  inflating: adcp_doc/_images/rot0_uv.png  
  inflating: adcp_doc/_images/os75bb_ktvecprof.png  
  inflating: adcp_doc/_images/vbox_gpuram.png  
  inflating: adcp_doc/_images/RESET_MAC04.png  
  inflating: adcp_doc/_images/doppler_01.png  
  inflating: adcp_doc/_images/vmdas_form_after_annot.png  
  inflating: adcp_doc/_images/rot28_topogt.png  
  inflating: adcp_doc/_images/tk_terminal_wakeup.png  
  inflating: adcp_doc/_images/ping-mode-control_annot.png  
  inflating: adcp_doc/_images/Screenshot_2017-09-20_00-40-27.png  
  inflating: adcp_doc/_images/os75bb_vect.png  
  inflating: adcp_doc/_images/10.png  
  inflating: adcp_doc/_images/01_startUHDAS.png  
  inflating: adcp_doc/_images/compare-mode-control_annot.png  
  inflating: adcp_doc/_images/compare-mode-layout.png  
  inflating: adcp_doc/_images/previous-ping-graph.png  
  inflating: adcp_doc/_images/vmdas_info_reform.png  
  inflating: adcp_doc/_images/rot36_topogt.png  
  inflating: adcp_doc/_images/os150_underway_bias.png  
  inflating: adcp_doc/_images/postprocessing_step5.png  
  inflating: adcp_doc/_images/uhdas-vmdas-acquisition-overview.png  
  inflating: adcp_doc/_images/os75bb_lastfewvec.png  
  inflating: adcp_doc/_images/shutdown1.png  
  inflating: adcp_doc/_images/alongtrack_bias.png  
  inflating: adcp_doc/_images/os75nb_diurnal_5daysEpac.png  
  inflating: adcp_doc/_images/after-apply-edits.png  
  inflating: adcp_doc/_images/vbox_docs.png  
  inflating: adcp_doc/_images/vmdas_reform_NxR_annot.png  
  inflating: adcp_doc/_images/vbox_configureB.png  
  inflating: adcp_doc/_images/fill_database_processing_steps.png  
  inflating: adcp_doc/_images/lastens_annotated.png  
  inflating: adcp_doc/_images/altered-topo.png  
  inflating: adcp_doc/_images/uhdas_codas_processing_flowchart.png  
  inflating: adcp_doc/_images/lidex_bump.png  
  inflating: adcp_doc/_images/rot36uvt.png  
  inflating: adcp_doc/_images/edit_mode_dataviewer_panels.png  
  inflating: adcp_doc/_images/edit_mode_dataviewer_controls.png  
  inflating: adcp_doc/_images/npings.png  
  inflating: adcp_doc/_images/instructions_checkdaily_01.png  
  inflating: adcp_doc/_images/view-mode-layout.png  
  inflating: adcp_doc/_images/Screenshot_2017-09-20_00-39-15.png  
  inflating: adcp_doc/_images/40-after-adcptree.png  
  inflating: adcp_doc/_images/vbox_intro.png  
  inflating: adcp_doc/_images/wire_EV.png  
  inflating: adcp_doc/_images/maneuver_lag_error.png  
  inflating: adcp_doc/_images/adapter-not-found.png  
  inflating: adcp_doc/_images/edit_mode_gui_plot_tab_annot.png  
  inflating: adcp_doc/_images/PCF1_annot.png  
  inflating: adcp_doc/_images/bottom_interference_atsea.png  
  inflating: adcp_doc/_images/rot2_uv.png  
  inflating: adcp_doc/_images/convert-lta_annot.png  
  inflating: adcp_doc/_images/03b_rbin01.png  
  inflating: adcp_doc/_images/ping-mode-amp_annot.png  
  inflating: adcp_doc/_images/os75bb_latcont.png  
  inflating: adcp_doc/_images/UHDAS_Monitor.png  
  inflating: adcp_doc/_images/compare_mode_gui_plot_tab_annot.png  
  inflating: adcp_doc/_images/before_after.png  
  inflating: adcp_doc/_images/01a_transformation.png  
  inflating: adcp_doc/_images/bad-practice.png  
  inflating: adcp_doc/_images/dbmaker_uhdas_launch.png  
  inflating: adcp_doc/_images/refuv_source_uvship.png  
  inflating: adcp_doc/_images/RESET_MAC01.png  
  inflating: adcp_doc/_images/Atsea_Monitoring_phins_gyrodh.png  
  inflating: adcp_doc/_images/04e_transformation.png  
  inflating: adcp_doc/_images/best-practices.png  
  inflating: adcp_doc/_images/instructions_checkdaily_03.png  
  inflating: adcp_doc/_images/02_startcruise.png  
  inflating: adcp_doc/_images/sensor_cfg_01b.png  
  inflating: adcp_doc/_images/RESET_MAC03.png  
  inflating: adcp_doc/_images/06_transformation.png  
  inflating: adcp_doc/_images/12-reform-vmdas-before-convert-to-uhdas_annot.png  
  inflating: adcp_doc/_images/cutoffs.png  
  inflating: adcp_doc/_images/manually-edit-in-selector-window-unmask01.png  
  inflating: adcp_doc/_images/panels_after_rotation_annot.png  
  inflating: adcp_doc/_images/panels_before_rotation_annot.png  
  inflating: adcp_doc/_images/os75nb_thrusternoise00_annotated.png  
  inflating: adcp_doc/_images/Endeavor-dxdy.png  
  inflating: adcp_doc/_images/CW_CX.png  
  inflating: adcp_doc/_images/edit_mode_dataviewer_topofig.png  
  inflating: adcp_doc/_images/prev-ping-panels.png  
  inflating: adcp_doc/_images/instructions_checkdaily_07.png  
  inflating: adcp_doc/_images/00-ens_hcorr_before.png  
  inflating: adcp_doc/_images/NBP_400m_underwaybias.png  
  inflating: adcp_doc/_images/LTA_btcal.png  
  inflating: adcp_doc/_images/UHDAS_Monitorbad.png  
  inflating: adcp_doc/_images/os75nb_tsstats.png  
  inflating: adcp_doc/_images/00_beam_orientation.png  
  inflating: adcp_doc/_images/rot36_uvt.png  
  inflating: adcp_doc/_images/nb150_bubbles01.png  
  inflating: adcp_doc/_images/after-splash-uhdas-data_new_annot.png  
  inflating: adcp_doc/_images/uhdasicon_profile.png  
  inflating: adcp_doc/_images/RESET_MAC02.png  
  inflating: adcp_doc/_images/PC4_new_annot.png  
  inflating: adcp_doc/_images/nb150_otherping00.png  
  inflating: adcp_doc/_images/os38nb_scatteringlayer.png  
  inflating: adcp_doc/_images/vbox_ram.png  
  inflating: adcp_doc/_images/cross_track_error.png  
  inflating: adcp_doc/_images/uhdas_dir_aftergbins_annot.png  
  inflating: adcp_doc/_images/rot28_uv.png  
  inflating: adcp_doc/_images/05_transformation.png  
  inflating: adcp_doc/_images/5minute_annot.png  
  inflating: adcp_doc/_images/02_transformation.png  
  inflating: adcp_doc/_images/uhdas-website-overview2.png  
  inflating: adcp_doc/_images/04a_transformation.png  
  inflating: adcp_doc/_images/compare-mode-panels.png  
  inflating: adcp_doc/_images/00-run_adcp_dbmaker.png  
  inflating: adcp_doc/_images/ping-mode-beams_annot.png  
  inflating: adcp_doc/_images/km1001c_nav.png  
  inflating: adcp_doc/_images/dirlayout_after_adcptree_annot.png  
  inflating: adcp_doc/_images/bottom_edit.png  
  inflating: adcp_doc/_images/refuv_source_nav.png  
  inflating: adcp_doc/_images/rot36_topog.png  
  inflating: adcp_doc/_images/01_stats.png  
  inflating: adcp_doc/_images/44-proc-starter-before-make-config_annot.png  
  inflating: adcp_doc/_images/doppler_02.png  
  inflating: adcp_doc/_images/jitter35.png  
  inflating: adcp_doc/_images/g_layout_before_editing.png  
  inflating: adcp_doc/_images/proc_starter_components.png  
  inflating: adcp_doc/_images/em710_os75bb_annot.png  
  inflating: adcp_doc/_images/kn195_03_kn2009_025_14400.png  
  inflating: adcp_doc/_images/kn195_04_kn2009_074_00000.png  
  inflating: adcp_doc/_images/ping-mode-pflags_annot.png  
  inflating: adcp_doc/_images/calibration_bad.png  
  inflating: adcp_doc/_images/edit_mode_dataviewer_topofig_annot.png  
  inflating: adcp_doc/_images/data_proc03b_annot.png  
  inflating: adcp_doc/_images/HUD_calib_after.png  
  inflating: adcp_doc/_images/uhdas_codas_processing_flowchart_annot.png  
  inflating: adcp_doc/_images/deep_tails.png  
  inflating: adcp_doc/_images/instructions_checkdaily_04.png  
  inflating: adcp_doc/_images/data_proc04_annot.png  
  inflating: adcp_doc/_images/03e_lastens.png  
  inflating: adcp_doc/_images/data_proc02_1_annot.png  
  inflating: adcp_doc/_images/ping-mode-panels_annot.png  
  inflating: adcp_doc/_images/virtualization-disabled.png  
  inflating: adcp_doc/_images/save-dialog.png  
  inflating: adcp_doc/_images/ps0918_nav.png  
  inflating: adcp_doc/_images/rot2uvt.png  
  inflating: adcp_doc/_images/PCF4_buttons_new2_annot.png  
  inflating: adcp_doc/_images/jitter20.png  
  inflating: adcp_doc/_images/beam_orientation.png  
  inflating: adcp_doc/_images/uhdas-vmdas-processing-comparison.png  
  inflating: adcp_doc/_images/ping-mode-topography.png  
  inflating: adcp_doc/_images/ktvec_day.png  
  inflating: adcp_doc/_images/compare_mode_topography.png  
  inflating: adcp_doc/_images/13_pcolor_before_after.png  
  inflating: adcp_doc/_images/os38nb_shortbias_zoom_.png  
  inflating: adcp_doc/_images/scattering_layer_toon.png  
  inflating: adcp_doc/_images/scalefactor.png  
  inflating: adcp_doc/_images/04d_transformation.png  
  inflating: adcp_doc/_images/rot0_uvt.png  
  inflating: adcp_doc/_images/shutdown2.png  
  inflating: adcp_doc/_images/10-apply-and-quit.png  
  inflating: adcp_doc/_images/change_display.png  
  inflating: adcp_doc/_images/after-splash-vmdas_annot.png  
  inflating: adcp_doc/_images/RDI_trigger_settings.png  
  inflating: adcp_doc/_images/bottom_edit_tool.png  
  inflating: adcp_doc/_images/ping-mode-panels-deep.png  
  inflating: adcp_doc/_images/reset-edits-after-RESET.png  
  inflating: adcp_doc/_images/2017-229-1440os38nb_contN.png  
  inflating: adcp_doc/_images/Atsea_Monitoring_ashtech_gyrodh.png  
  inflating: adcp_doc/_images/03_transformation.png  
  inflating: adcp_doc/_images/edit_mode_dataviewer_panels_annot.png  
  inflating: adcp_doc/_images/bottomtrack.png  
  inflating: adcp_doc/_images/10-after-save-OKdialog.png  
  inflating: adcp_doc/_images/vbox_thunar.png  
  inflating: adcp_doc/_images/03b_rbin02.png  
  inflating: adcp_doc/_images/em710_os75nb_annot.png  
  inflating: adcp_doc/_images/amplitude.png  
  inflating: adcp_doc/_images/instructions_checkdaily_00.png  
  inflating: adcp_doc/_images/scattering_migration_bias.png  
  inflating: adcp_doc/_images/poor-practice.png  
  inflating: adcp_doc/_images/vectors_before_after_rotation.png  
  inflating: adcp_doc/_images/sfc_underwaybias.png  
  inflating: adcp_doc/_images/os75bb_loncont.png  
  inflating: adcp_doc/_images/PCF2_SelectYourProject_new_annot.png  
  inflating: adcp_doc/_images/03d_gbin.png  
  inflating: adcp_doc/_images/reform-vmdas-splash_annot.png  
  inflating: adcp_doc/_images/10-after-save-in-your-face-cals.png  
  inflating: adcp_doc/_images/vmdas_info_notes.png  
  inflating: adcp_doc/_images/uhdas-vmdas-acquisition-data-logging.png  
  inflating: adcp_doc/_images/config-ok.png  
  inflating: adcp_doc/_images/rot28_topog.png  
  inflating: adcp_doc/_images/edit_mode_gui_panel_threshold_annot.png  
  inflating: adcp_doc/_images/30-make-config.png  
  inflating: adcp_doc/_images/0-select-uhdas-dir_new_annot.png  
  inflating: adcp_doc/_images/instructions_checkdaily_06.png  
  inflating: adcp_doc/_images/trigger.pdf  
  inflating: adcp_doc/_images/vbox_desktop.png  
  inflating: adcp_doc/_images/tk_terminal_start.png  
  inflating: adcp_doc/_images/vbox_firefox.png  
  inflating: adcp_doc/_images/view-mode-topography.png  
  inflating: adcp_doc/_images/os75bb_clean_bottom.png  
  inflating: adcp_doc/_images/vbox_change_scale.png  
  inflating: adcp_doc/_images/ResetEditButton.png  
  inflating: adcp_doc/_images/00_transformation.png  
  inflating: adcp_doc/_images/nav_plot.png  
  inflating: adcp_doc/_images/btwt_caltxt.png  
  inflating: adcp_doc/_images/edit_mode_masking.png  
  inflating: adcp_doc/_images/view-mode-control.png  
  inflating: adcp_doc/_images/sensor_cfg_01a.png  
  inflating: adcp_doc/_images/instructions_examplebad_02.png  
  inflating: adcp_doc/_images/dir_layout_initial_annot.png  
  inflating: adcp_doc/_images/jitter5.png  
  inflating: adcp_doc/_images/altered_control_annot.png  
  inflating: adcp_doc/_images/km1001c_proc_annot.png  
  inflating: adcp_doc/_images/01_transformation.png  
  inflating: adcp_doc/_images/amp_dday228.png  
  inflating: adcp_doc/_images/rot28_uvt.png  
  inflating: adcp_doc/_images/ping-mode-topofig_annot.png  
  inflating: adcp_doc/_images/uhdas-vmdas-accessing-data-products.png  
  inflating: adcp_doc/_images/UHDAS_Terminal.png  
  inflating: adcp_doc/_images/rot2_topogt.png  
  inflating: adcp_doc/_images/prev-ping-topofig.png  
  inflating: adcp_doc/_images/reset-edits-annot.png  
  inflating: adcp_doc/_images/atsea_web.png  
  inflating: adcp_doc/_images/uvship_fixes_stripes.png  
  inflating: adcp_doc/_images/rot0_topogt.png  
  inflating: adcp_doc/_images/after-splash_annot.png  
  inflating: adcp_doc/_images/doppler_03.png  
  inflating: adcp_doc/_images/edit_mode_dataviewer_selector_annot.png  
  inflating: adcp_doc/_images/ADCP_GUI_Settings.png  
  inflating: adcp_doc/_images/panels_before_after_all.png  
  inflating: adcp_doc/_images/uhdas_overview.pdf  
  inflating: adcp_doc/_images/view_mode_gui_plot_tab_annot.png  
  inflating: adcp_doc/_images/00_overview.png  
   creating: adcp_doc/glossary
  inflating: adcp_doc/glossary/index.html  
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100  285M  100  285M    0     0   109M      0  0:00:02  0:00:02 --:--:--  109M
Archive:  codas_demos.zip
   creating: codas_demos
   creating: codas_demos/vmdas_data
   creating: codas_demos/vmdas_data/ps0918
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge005_000000.N1R  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge005_000000.N3R  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge006_000000.N1R  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge006_000001.ENS  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge006_000000.ENX  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge006_000000.LTA  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge007_000000.NMS  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge006_000002.ENX  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge006_000003.ENX  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge005_000000.VMO  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge006_000004.ENS  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge006_000001.N3R  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge005_000000.LOG  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge007_000000.ENX  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge007_000000.VMO  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge006_000000.NMS  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge006_000000.STA  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge006_000004.ENR  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge007_000000.LOG  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge005_000000.ENX  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge006_000002.ENS  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge006_000002.ENR  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge006_000001.ENX  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge007_000000.STA  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge005_000000.NMS  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge006_000003.ENS  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge007_000000.ENS  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge005_000000.ENS  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge007_000000.N2R  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge006_000001.N1R  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge005_000000.ENR  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge006_000000.LOG  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge005_000000.N2R  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge006_000004.ENX  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge005_000000.STA  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge006_000000.ENS  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge006_000000.ENR  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge006_000003.ENR  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge007_000000.ENR  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge005_000000.LTA  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge006_000000.N3R  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge006_000000.N2R  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge007_000000.N1R  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge007_000000.N3R  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge006_000001.ENR  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge006_000000.VMO  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge007_000000.LTA  
  inflating: codas_demos/vmdas_data/ps0918/Collins_PtSur_Ridge006_000001.N2R  
  inflating: codas_demos/vmdas_data/.DS_Store  
   creating: codas_demos/uhdas_data
   creating: codas_demos/uhdas_data/km1001c
   creating: codas_demos/uhdas_data/km1001c/rbin
   creating: codas_demos/uhdas_data/km1001c/rbin/ashtech
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_031_07200.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_031_16997.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_031_17854.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_031_17261.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_029_63671.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_031_00851.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_83730.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_031_43200.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_83559.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_031_28800.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_83559.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_029_64800.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_031_17781.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_50400.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_69097.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_14400.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_83674.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_50400.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_031_17538.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_43200.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_031_43200.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_14400.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_85516.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_79200.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_00000.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_72000.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_83730.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_031_17854.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_029_72000.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_031_17467.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_07200.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_84666.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_031_28800.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_031_36000.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_07200.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_85516.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_031_50400.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_57600.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_031_14400.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_029_72000.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_031_07200.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_57600.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_69097.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_031_17186.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_031_21600.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_031_50400.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_031_00851.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_031_16997.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_83674.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_031_28018.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_28800.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_031_17538.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_031_17186.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_031_17781.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_031_36000.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_031_14400.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_031_21600.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_36000.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_031_28018.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_64800.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_21600.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_64800.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_43200.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_029_63671.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_029_79200.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_029_79200.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_84666.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_031_17467.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_28800.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_00000.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_79200.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_21600.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_031_17261.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_72000.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_029_64800.adu.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/ashtech/km2010_030_36000.adu.rbin  
   creating: codas_demos/uhdas_data/km1001c/rbin/posmv
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_21600.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_031_00851.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_031_17854.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_031_17261.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_031_36000.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_83730.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_83559.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_031_28800.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_36000.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_84666.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_029_64800.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_031_17781.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_50400.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_69097.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_14400.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_83674.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_031_17538.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_029_79200.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_43200.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_031_43200.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_85516.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_031_16997.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_00000.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_72000.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_69097.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_031_17781.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_029_72000.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_84666.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_029_72000.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_07200.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_031_50400.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_031_14400.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_031_17467.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_031_07200.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_50400.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_57600.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_031_17186.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_031_00851.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_031_17538.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_031_16997.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_031_28800.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_14400.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_031_28018.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_28800.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_64800.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_031_07200.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_031_21600.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_029_64800.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_83674.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_83730.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_031_36000.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_031_14400.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_031_21600.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_36000.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_00000.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_79200.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_21600.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_64800.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_029_63671.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_031_50400.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_029_79200.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_031_28018.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_83559.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_031_17467.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_07200.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_72000.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_85516.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_031_17186.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_029_63671.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_031_17261.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_79200.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_031_17854.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_43200.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_28800.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_030_57600.pmv.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/posmv/km2010_031_43200.pmv.rbin  
   creating: codas_demos/uhdas_data/km1001c/rbin/gyro
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_031_17781.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_031_17261.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_030_14400.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_031_17467.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_030_36000.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_030_83674.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_031_43200.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_030_43200.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_031_50400.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_030_85516.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_029_63671.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_031_14400.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_031_17186.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_031_36000.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_030_83559.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_029_64800.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_030_69097.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_029_79200.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_030_21600.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_031_28018.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_031_16997.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_030_50400.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_029_72000.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_031_28800.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_031_21600.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_031_07200.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_030_07200.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_030_84666.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_031_00851.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_030_79200.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_030_72000.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_030_00000.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_031_17538.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_030_57600.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_031_17854.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_030_28800.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_030_64800.hdg.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/gyro/km2010_030_83730.hdg.rbin  
   creating: codas_demos/uhdas_data/km1001c/rbin/simrad
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_031_17854.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_031_17261.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_030_83730.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_030_83559.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_031_28800.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_029_64800.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_031_17781.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_030_50400.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_030_69097.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_030_14400.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_030_83674.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_031_17538.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_030_43200.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_031_43200.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_030_85516.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_030_00000.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_030_72000.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_029_72000.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_030_84666.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_030_07200.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_031_50400.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_031_07200.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_030_57600.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_031_17186.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_031_00851.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_031_16997.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_031_28018.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_030_28800.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_031_36000.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_031_14400.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_031_21600.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_030_36000.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_030_21600.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_030_64800.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_029_63671.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_029_79200.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_031_17467.gps.rbin  
  inflating: codas_demos/uhdas_data/km1001c/rbin/simrad/km2010_030_79200.gps.rbin  
   creating: codas_demos/uhdas_data/km1001c/proc
   creating: codas_demos/uhdas_data/km1001c/proc/os38bb
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/os38bb_qpy.cnt  
   creating: codas_demos/uhdas_data/km1001c/proc/os38bb/quality
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/quality/arrdepos.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/quality/stn_udw.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/quality/arrdepuw.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/quality/profstuw.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/quality/profstos.cnt  
   creating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/override_flagit.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/asetup.m__  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/a_bt.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/agetmat_hdg.txt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/a_km.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/a_amp.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/do_mkbadprf.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/threshld.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/fix_temp.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/abadprf_tmp.asc  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/a_depth.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/aflagit_setup.m__  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/setflags.tmp  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/aedit.m__  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/mkbadtimes.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/asetup.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/aedit_tmp.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/Tempplot_script.py  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/setup.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/a_km.tem  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/a_pf.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/abottom_tmp.asc  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/aREADME_basics.txt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/a_e.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/profst00.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/lst_temp.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/a_refsmnav.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/a_other.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/lst_temp.tmp  
 extracting: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/autoflagged.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/plotpg.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/profst02.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/setflags.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/lst_hdg_getmat.tmp  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/plottemp.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/abadbin_tmp.asc  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/aflagit_setup.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/a_pg.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/a_raw_amp.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/temp_plot.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/a_tseries_stats.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/a_v.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/a_u.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/a_w.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/a_sw.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/set_rawcfg.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/setflags.log  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/a_resid_stats.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/pltemp.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/setup.m__  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/edit/newflag.cnt  
   creating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal
   creating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/heading
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/heading/cal_hdg.m  
   creating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/botmtrk
 extracting: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/botmtrk/a_km.ref  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/botmtrk/a_km.btm  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/botmtrk/Btplot_script.py  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/botmtrk/refabsbt.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/botmtrk/refabsbt.tmp  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/botmtrk/lst_btrk.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/botmtrk/lst_btrk.tmp  
   creating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/watertrk
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/watertrk/a_km_7.cal  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/watertrk/wtcal2.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/watertrk/Wtplot_script.py  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/watertrk/wtcal1.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/watertrk/adcpsect.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/watertrk/adcpcal.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/watertrk/timslip.tmp  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/watertrk/recip.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/watertrk/adcpcal.out  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/watertrk/timslip.cnt  
   creating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/rotate
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/rotate/print_hcorrstats_all.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/rotate/hcorr_mpl_029.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/rotate/lst_hdg.tmp  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/rotate/rotnav.cnt  
 extracting: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/rotate/ens_hcorr_err.txt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/rotate/lst_hdg.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/rotate/ashrot.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/rotate/ens_hcorr.asc  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/rotate/rotate.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/rotate/rotate.log  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/rotate/ens_hcorr.ang  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/rotate/plot_hcorrstats_all.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/rotate/scn.hdg  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/rotate/Hcorrplot_script.py  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/cal/rotate/rotate.tmp  
   creating: codas_demos/uhdas_data/km1001c/proc/os38bb/vector
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/vector/vector.vec  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/vector/vector_uv.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/vector/vector_xy.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/vector/a_km.tmp  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/vector/as_vect.tmp  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/vector/vector.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/vector/adcpsect.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/vector/vector.sta  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/vector/a_km.tmg  
   creating: codas_demos/uhdas_data/km1001c/proc/os38bb/stick
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/stick/runstick.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/stick/adcpsect.cnt  
   creating: codas_demos/uhdas_data/km1001c/proc/os38bb/contour
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/contour/allbins_u.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/contour/allbins_other.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/contour/contour_uv.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/contour/allbins_w.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/contour/allbins_v.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/contour/as_cont.tmp  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/contour/allbins_sw.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/contour/a_km.tmp  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/contour/allbins_raw_amp.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/contour/contour.cpa  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/contour/adcpsect.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/contour/contour.sta  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/contour/allbins_pg.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/contour/allbins_e.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/contour/allbins_depth.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/contour/allbins_pf.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/contour/allbins_resid_stats.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/contour/allbins_amp.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/contour/a_km.tmg  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/contour/allbins_bt.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/contour/contour_xy.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/contour/allbins_tseries_stats.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/cruise_info.txt  
   creating: codas_demos/uhdas_data/km1001c/proc/os38bb/png_archive
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/png_archive/030_os38bb_latcont.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/png_archive/029_os38bb_ddaycont.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/png_archive/031_os38bb_shallow.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/png_archive/031_os38bb_ddaycont.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/png_archive/030_os38bb_loncont.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/png_archive/029_os38bb_loncont.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/png_archive/031_os38bb_latcont.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/png_archive/029_os38bb_latcont.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/png_archive/030_os38bb_ddaycont.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/png_archive/030_os38bb_shallow.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/png_archive/030_os38bb_cor_history.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/png_archive/031_os38bb_loncont.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/png_archive/029_os38bb_shallow.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/png_archive/030_os38bb_bin_history.png  
   creating: codas_demos/uhdas_data/km1001c/proc/os38bb/scan
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/scan/ub_1920.def  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/scan/ub_1020.def  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/scan/ub_1320.def  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/scan/scan_tmp.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/scan/clkrate.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/scan/ub_2240.def  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/scan/a_km.tr  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/scan/ub_720.def  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/scan/scanping.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/scan/ub_1280.def  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/scan/ub_1281.def  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/scan/a_km.scn  
   creating: codas_demos/uhdas_data/km1001c/proc/os38bb/nav
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/nav/xducerxy.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/nav/refabs.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/nav/smoothr.tmp  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/nav/callrefp.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/nav/a_km.gps  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/nav/putnav.tmp  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/nav/smoothr.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/nav/a_km.ref  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/nav/a_km.log  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/nav/reflayer_029.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/nav/refabs.tmp  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/nav/a_km.sm  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/nav/callrefp.m__  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/nav/edfix.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/nav/Refplot_script.py  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/nav/reflayer_031.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/nav/a_km_xy.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/nav/putnav.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/nav/adcpsect.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/nav/Refsm_script.py  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/nav/a_km.sta  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/nav/a_km.bin  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/nav/getnav.cnt  
 extracting: codas_demos/uhdas_data/km1001c/proc/os38bb/nav/a_km_uv.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/nav/Navplot_script.py  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/nav/cruistrk.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/nav/refsm.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/nav/ubprint.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/nav/a_km.nav  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/nav/attplot.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/nav/a_km_refsm.asc  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/nav/as_nav.tmp  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/nav/nav_plot.png  
   creating: codas_demos/uhdas_data/km1001c/proc/os38bb/ping
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/ping/loadrun.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/adcp_processing.html  
   creating: codas_demos/uhdas_data/km1001c/proc/os38bb/grid
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/grid/timegrid.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/grid/llgrid.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/template_rpt.txt  
   creating: codas_demos/uhdas_data/km1001c/proc/os38bb/config
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/config/km1001c_proc.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/config/procsetup_onship.py  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/config/km1001c_cfg.m  
 extracting: codas_demos/uhdas_data/km1001c/proc/os38bb/config/instping.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/config/cruise_cfg.m__  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/config/sensor_cfg.py  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/config/cruise_proc.m__  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/km1001c.runlog  
   creating: codas_demos/uhdas_data/km1001c/proc/os38bb/load
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk004.gps2  
 extracting: codas_demos/uhdas_data/km1001c/proc/os38bb/load/new_ens_TF  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk007.gps1  
 extracting: codas_demos/uhdas_data/km1001c/proc/os38bb/load/wrote_ens_time  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/lastens.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/lastens_amp1.sbin  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk002.bin  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk007.gps2  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk003.cmd  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk005.gps2  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk002.cmd  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/lastens_t.sbin  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ldcodas.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/override_editcfg.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/prepedit.log  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk004.cmd  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk001.gps1  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk003.gps1  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk002.gps2  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk008.gps1  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk002.gps1  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/load_uhblk_tmp.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk006.log  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk006.gps1  
 extracting: codas_demos/uhdas_data/km1001c/proc/os38bb/load/load.log  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk005.bin  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk003.log  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk007.log  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk009.gps2  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/loadping.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/vmadcp.def  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk001.cmd  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk001.log  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk009.cmd  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/loadpc.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk004.log  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ldcodas_path.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ldcodas.cnt__  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/lastens_v.sbin  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk007.bin  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk008.log  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/write_ensblk.log  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk006.cmd  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk004.gps1  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/lastens_z.sbin  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk001.bin  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ldcodas.tmp  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk006.bin  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk008.cmd  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/lastens_u.sbin  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/lastens_instpflag.sbin  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk009.log  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk004.bin  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk007.cmd  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk006.gps2  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk009.gps1  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk009.bin  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk002.log  
 extracting: codas_demos/uhdas_data/km1001c/proc/os38bb/load/hcorr_rbin.log  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk001.gps2  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk003.bin  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk003.gps2  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/load_uh.m__  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk008.gps2  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk005.log  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk005.cmd  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk008.bin  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/load/ens_blk005.gps1  
   creating: codas_demos/uhdas_data/km1001c/proc/os38bb/adcpdb
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/adcpdb/a_km006.blk  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/adcpdb/a_km005.blk  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/adcpdb/a_km.cnh  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/adcpdb/mkblkdir.tmp  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/adcpdb/adcp1320.def  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/adcpdb/a_km003.blk  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/adcpdb/lst_conf.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/adcpdb/a_kmdir.blk  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/adcpdb/a_km007.blk  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/adcpdb/a_km.bbn  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/adcpdb/adcp2240.def  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/adcpdb/adcp720.def  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/adcpdb/a_km009.blk  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/adcpdb/mkblkdir.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/adcpdb/a_km008.blk  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/adcpdb/a_km.lst  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/adcpdb/a_km.tr  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/adcpdb/ademo.def  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/adcpdb/a_km002.blk  
 extracting: codas_demos/uhdas_data/km1001c/proc/os38bb/adcpdb/lstblock.errs  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/adcpdb/lst_prof.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/adcpdb/adcp1281.def  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/adcpdb/lst_conf.tmp  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/adcpdb/a_km004.blk  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/adcpdb/a_km001.blk  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38bb/adcpdb/adcp1920.def  
   creating: codas_demos/uhdas_data/km1001c/proc/os38nb
   creating: codas_demos/uhdas_data/km1001c/proc/os38nb/quality
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/quality/arrdepos.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/quality/stn_udw.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/quality/arrdepuw.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/quality/profstuw.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/quality/profstos.cnt  
   creating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/override_flagit.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/asetup.m__  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/a_bt.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/agetmat_hdg.txt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/a_km.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/a_amp.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/do_mkbadprf.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/threshld.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/fix_temp.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/abadprf_tmp.asc  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/a_depth.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/aflagit_setup.m__  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/setflags.tmp  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/aedit.m__  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/mkbadtimes.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/asetup.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/aedit_tmp.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/Tempplot_script.py  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/setup.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/a_km.tem  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/a_pf.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/abottom_tmp.asc  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/aREADME_basics.txt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/a_e.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/profst00.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/lst_temp.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/a_refsmnav.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/a_other.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/lst_temp.tmp  
 extracting: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/autoflagged.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/plotpg.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/profst02.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/setflags.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/lst_hdg_getmat.tmp  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/plottemp.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/abadbin_tmp.asc  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/aflagit_setup.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/a_pg.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/a_raw_amp.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/temp_plot.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/a_tseries_stats.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/a_v.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/a_u.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/a_w.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/a_sw.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/set_rawcfg.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/setflags.log  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/a_resid_stats.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/pltemp.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/setup.m__  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/edit/newflag.cnt  
   creating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal
   creating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/heading
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/heading/cal_hdg.m  
   creating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/botmtrk
 extracting: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/botmtrk/a_km.ref  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/botmtrk/a_km.btm  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/botmtrk/Btplot_script.py  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/botmtrk/refabsbt.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/botmtrk/refabsbt.tmp  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/botmtrk/lst_btrk.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/botmtrk/lst_btrk.tmp  
   creating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/watertrk
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/watertrk/a_km_7.cal  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/watertrk/wtcal2.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/watertrk/Wtplot_script.py  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/watertrk/wtcal1.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/watertrk/adcpsect.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/watertrk/adcpcal.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/watertrk/timslip.tmp  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/watertrk/recip.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/watertrk/adcpcal.out  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/watertrk/timslip.cnt  
   creating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/rotate
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/rotate/print_hcorrstats_all.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/rotate/hcorr_mpl_029.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/rotate/lst_hdg.tmp  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/rotate/rotnav.cnt  
 extracting: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/rotate/ens_hcorr_err.txt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/rotate/lst_hdg.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/rotate/ashrot.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/rotate/ens_hcorr.asc  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/rotate/rotate.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/rotate/rotate.log  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/rotate/ens_hcorr.ang  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/rotate/plot_hcorrstats_all.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/rotate/scn.hdg  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/rotate/Hcorrplot_script.py  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/cal/rotate/rotate.tmp  
   creating: codas_demos/uhdas_data/km1001c/proc/os38nb/vector
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/vector/vector.vec  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/vector/vector_uv.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/vector/vector_xy.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/vector/a_km.tmp  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/vector/as_vect.tmp  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/vector/vector.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/vector/adcpsect.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/vector/vector.sta  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/vector/a_km.tmg  
   creating: codas_demos/uhdas_data/km1001c/proc/os38nb/stick
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/stick/runstick.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/stick/adcpsect.cnt  
   creating: codas_demos/uhdas_data/km1001c/proc/os38nb/contour
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/contour/allbins_u.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/contour/allbins_other.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/contour/contour_uv.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/contour/allbins_w.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/contour/allbins_v.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/contour/as_cont.tmp  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/contour/allbins_sw.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/contour/a_km.tmp  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/contour/allbins_raw_amp.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/contour/contour.cpa  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/contour/adcpsect.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/contour/contour.sta  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/contour/allbins_pg.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/contour/allbins_e.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/contour/allbins_depth.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/contour/allbins_pf.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/contour/allbins_resid_stats.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/contour/allbins_amp.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/contour/a_km.tmg  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/contour/allbins_bt.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/contour/contour_xy.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/contour/allbins_tseries_stats.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/os38nb_qpy.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/cruise_info.txt  
   creating: codas_demos/uhdas_data/km1001c/proc/os38nb/png_archive
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/png_archive/030_os38nb_shallow.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/png_archive/031_os38nb_loncont.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/png_archive/029_os38nb_ddaycont.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/png_archive/031_os38nb_ddaycont.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/png_archive/030_os38nb_ddaycont.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/png_archive/030_os38nb_latcont.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/png_archive/030_os38nb_loncont.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/png_archive/029_os38nb_latcont.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/png_archive/031_os38nb_latcont.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/png_archive/029_os38nb_loncont.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/png_archive/030_os38nb_cor_history.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/png_archive/031_os38nb_shallow.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/png_archive/029_os38nb_shallow.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/png_archive/030_os38nb_bin_history.png  
   creating: codas_demos/uhdas_data/km1001c/proc/os38nb/scan
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/scan/ub_1920.def  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/scan/ub_1020.def  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/scan/ub_1320.def  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/scan/scan_tmp.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/scan/clkrate.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/scan/ub_2240.def  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/scan/a_km.tr  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/scan/ub_720.def  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/scan/scanping.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/scan/ub_1280.def  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/scan/ub_1281.def  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/scan/a_km.scn  
   creating: codas_demos/uhdas_data/km1001c/proc/os38nb/nav
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/nav/xducerxy.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/nav/refabs.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/nav/smoothr.tmp  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/nav/callrefp.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/nav/a_km.gps  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/nav/putnav.tmp  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/nav/smoothr.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/nav/a_km.ref  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/nav/a_km.log  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/nav/reflayer_029.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/nav/refabs.tmp  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/nav/a_km.sm  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/nav/callrefp.m__  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/nav/edfix.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/nav/Refplot_script.py  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/nav/reflayer_031.png  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/nav/a_km_xy.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/nav/putnav.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/nav/adcpsect.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/nav/Refsm_script.py  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/nav/a_km.sta  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/nav/a_km.bin  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/nav/getnav.cnt  
 extracting: codas_demos/uhdas_data/km1001c/proc/os38nb/nav/a_km_uv.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/nav/Navplot_script.py  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/nav/cruistrk.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/nav/refsm.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/nav/ubprint.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/nav/a_km.nav  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/nav/attplot.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/nav/a_km_refsm.asc  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/nav/as_nav.tmp  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/nav/nav_plot.png  
   creating: codas_demos/uhdas_data/km1001c/proc/os38nb/ping
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/ping/loadrun.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/adcp_processing.html  
   creating: codas_demos/uhdas_data/km1001c/proc/os38nb/grid
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/grid/timegrid.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/grid/llgrid.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/template_rpt.txt  
   creating: codas_demos/uhdas_data/km1001c/proc/os38nb/config
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/config/km1001c_proc.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/config/procsetup_onship.py  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/config/km1001c_cfg.m  
 extracting: codas_demos/uhdas_data/km1001c/proc/os38nb/config/instping.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/config/cruise_cfg.m__  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/config/sensor_cfg.py  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/config/cruise_proc.m__  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/km1001c.runlog  
   creating: codas_demos/uhdas_data/km1001c/proc/os38nb/load
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk004.gps2  
 extracting: codas_demos/uhdas_data/km1001c/proc/os38nb/load/new_ens_TF  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk007.gps1  
 extracting: codas_demos/uhdas_data/km1001c/proc/os38nb/load/wrote_ens_time  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/lastens.mat  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/lastens_amp1.sbin  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk002.bin  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk007.gps2  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk003.cmd  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk005.gps2  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk002.cmd  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/lastens_t.sbin  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ldcodas.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/override_editcfg.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/prepedit.log  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk004.cmd  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk001.gps1  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk003.gps1  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk002.gps2  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk008.gps1  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk002.gps1  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/load_uhblk_tmp.m  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk006.log  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk006.gps1  
 extracting: codas_demos/uhdas_data/km1001c/proc/os38nb/load/load.log  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk005.bin  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk003.log  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk007.log  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk009.gps2  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/loadping.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/vmadcp.def  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk001.cmd  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk001.log  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk009.cmd  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/loadpc.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk004.log  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ldcodas_path.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ldcodas.cnt__  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/lastens_v.sbin  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk007.bin  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk008.log  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/write_ensblk.log  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk006.cmd  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk004.gps1  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/lastens_z.sbin  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk001.bin  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ldcodas.tmp  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk006.bin  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk008.cmd  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/lastens_u.sbin  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/lastens_instpflag.sbin  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk009.log  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk004.bin  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk007.cmd  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk006.gps2  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk009.gps1  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk009.bin  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk002.log  
 extracting: codas_demos/uhdas_data/km1001c/proc/os38nb/load/hcorr_rbin.log  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk001.gps2  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk003.bin  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk003.gps2  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/load_uh.m__  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk008.gps2  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk005.log  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk005.cmd  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk008.bin  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/load/ens_blk005.gps1  
   creating: codas_demos/uhdas_data/km1001c/proc/os38nb/adcpdb
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/adcpdb/a_km006.blk  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/adcpdb/a_km005.blk  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/adcpdb/a_km.cnh  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/adcpdb/mkblkdir.tmp  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/adcpdb/adcp1320.def  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/adcpdb/a_km003.blk  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/adcpdb/lst_conf.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/adcpdb/a_kmdir.blk  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/adcpdb/a_km007.blk  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/adcpdb/a_km.bbn  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/adcpdb/adcp2240.def  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/adcpdb/adcp720.def  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/adcpdb/a_km009.blk  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/adcpdb/mkblkdir.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/adcpdb/a_km008.blk  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/adcpdb/a_km.lst  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/adcpdb/a_km.tr  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/adcpdb/ademo.def  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/adcpdb/a_km002.blk  
 extracting: codas_demos/uhdas_data/km1001c/proc/os38nb/adcpdb/lstblock.errs  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/adcpdb/lst_prof.cnt  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/adcpdb/adcp1281.def  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/adcpdb/lst_conf.tmp  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/adcpdb/a_km004.blk  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/adcpdb/a_km001.blk  
  inflating: codas_demos/uhdas_data/km1001c/proc/os38nb/adcpdb/adcp1920.def  
  inflating: codas_demos/uhdas_data/km1001c/proc/.DS_Store  
   creating: codas_demos/uhdas_data/km1001c/raw
   creating: codas_demos/uhdas_data/km1001c/raw/ashtech
  inflating: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_031_28800.adu.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_030_43200.adu.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_031_50400.adu  
 extracting: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_030_83674.adu.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_029_72000.adu.gz  
 extracting: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_031_17261.adu.gz  
 extracting: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_031_17186.adu.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_030_14400.adu.gz  
 extracting: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_031_17781.adu.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_031_36000.adu.gz  
 extracting: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_030_84666.adu.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_031_28018.adu.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_030_00000.adu.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_030_50400.adu.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_031_16997.adu.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_030_36000.adu.gz  
 extracting: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_030_83559.adu.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_030_57600.adu.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_031_17854.adu.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_031_14400.adu.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_030_85516.adu.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_031_17538.adu.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_030_69097.adu.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_031_00851.adu.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_030_72000.adu.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_029_79200.adu.gz  
 extracting: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_031_17467.adu.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_029_64800.adu.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_030_07200.adu.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_030_83730.adu.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_030_79200.adu.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_029_63671.adu.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_031_21600.adu.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_030_64800.adu.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_030_21600.adu.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_031_07200.adu.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_031_43200.adu.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/ashtech/km2010_030_28800.adu.gz  
   creating: codas_demos/uhdas_data/km1001c/raw/posmv
  inflating: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_031_36000.pmv.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_030_69097.pmv.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_030_72000.pmv.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_029_79200.pmv.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_031_16997.pmv.gz  
 extracting: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_030_84666.pmv.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_030_43200.pmv.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_029_64800.pmv.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_031_50400.pmv  
  inflating: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_030_28800.pmv.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_030_64800.pmv.gz  
 extracting: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_031_17781.pmv.gz  
 extracting: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_031_17186.pmv.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_031_17854.pmv.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_030_14400.pmv.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_030_85516.pmv.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_030_07200.pmv.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_030_00000.pmv.gz  
 extracting: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_030_83559.pmv.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_031_00851.pmv.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_030_36000.pmv.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_030_57600.pmv.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_030_83730.pmv.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_031_17538.pmv.gz  
 extracting: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_030_83674.pmv.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_031_07200.pmv.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_031_28018.pmv.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_029_63671.pmv.gz  
 extracting: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_031_17467.pmv.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_030_79200.pmv.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_031_14400.pmv.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_030_50400.pmv.gz  
 extracting: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_031_17261.pmv.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_030_21600.pmv.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_031_21600.pmv.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_029_72000.pmv.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_031_43200.pmv.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/posmv/km2010_031_28800.pmv.gz  
   creating: codas_demos/uhdas_data/km1001c/raw/log
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termwh300log2010_030_86377.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_030_85325.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_030_84300.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_029_15093.txt.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_029_63625.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/3dayplots_os38nb.warn  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_030_84175.txt.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termwh300log2010_031_17552.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_031_00875.txt.err  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/3dayplots_wh300.warn  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termwh300log2010_028_05770.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_027_63774.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_031_57168.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_029_14172.txt.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_030_84392.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_027_63471.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/DAS_while_logging.log.2  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termwh300log2010_030_85325.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_028_57422.txt.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termwh300log2010_028_09221.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termwh300log2010_028_65835.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_031_00026.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_028_57447.txt.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/lastensq_wh300.log  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_030_84120.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/DAS_while_logging.warn.2010-01-30  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_027_56485.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/DAS_while_logging.log.4  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/termwh300log2010_030_84120.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termwh300log2010_031_17351.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_028_06245.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_030_84868.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/DAS_while_logging.log.5  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/DAS_while_cruise.log  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_030_84375.txt.err  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/termwh300log2010_028_06129.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_029_14172.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_028_09221.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_027_56485.txt.err  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_027_56441.txt.err  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/termwh300log2010_030_84175.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/Cruise_km1001c.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_031_00026.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_030_84497.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/Cruise_test_02.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/quick_os38nb.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_027_56011.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_031_17506.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_029_63625.txt.err  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_030_84375.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/DAS_while_logging.log.8  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_027_56441.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_027_63753.txt.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_027_63831.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_027_56485.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/hcorrstats_posmv.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_030_84497.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_028_06245.txt.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_027_63564.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/daily.py.warn  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_027_63662.txt.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_029_15093.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_030_84375.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_028_06245.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/asc2bin.log  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_031_57168.txt.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/Cruise_junk.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_031_00688.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_031_00875.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_028_57422.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/Cruise_test_nostring.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/Cruise_test_03.log  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_027_63564.txt.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/DAS_main.log.1  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/termwh300log2010_027_55377.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/hg_km1001a.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_029_63625.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_031_17552.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_031_17506.txt.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_027_63471.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_027_55377.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_028_65835.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_030_84624.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termwh300log2010_031_00875.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/termwh300log2010_027_56485.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_030_86377.txt.err  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_030_84937.txt.err  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_030_84392.txt.err  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_031_17351.txt.err  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_030_85039.txt.err  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_028_05770.txt.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/DAS_while_cruise.log.1  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_028_06129.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_028_06129.txt.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/Cruise_km1001d.log  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_027_63471.txt.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/quick_os38nb.warn  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_028_05770.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/hg_test_03.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_029_14172.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_028_06129.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/hg_test_02.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/3dayplots_os38bb.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termwh300log2010_027_63471.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_030_84736.txt.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_030_84120.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/termwh300log2010_027_56441.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_031_17351.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termwh300log2010_027_55430.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_031_17506.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/lastensq_os38nb.warn  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_030_84175.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_030_84937.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/hg_test_nostring.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/Cruise_km1001b.log  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_027_63774.txt.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/quick_os38bb.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/DAS_while_cruise.warn  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/DAS_while_logging.warn  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_030_84392.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_027_63753.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/lastensq_os38nb.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_031_17441.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_031_17351.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termwh300log2010_030_84868.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_027_63831.txt.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termwh300log2010_028_57447.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_030_86377.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/3dayplots_wh300.log  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/termwh300log2010_031_17506.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_030_84868.txt.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_029_15093.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_030_84624.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_028_09221.txt.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/DAS_while_logging.log.3  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_031_17441.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_030_84300.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_030_84736.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termwh300log2010_029_63625.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_031_17552.txt.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/DAS_while_logging.log.7  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/hg_km1001d.log  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_030_84624.txt.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_031_00688.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termwh300log2010_031_00688.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termwh300log2010_030_84937.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/hg_test_01.log  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_030_84120.txt.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termwh300log2010_028_06245.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_030_84175.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/hg_junk.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_027_56011.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/daily.py.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/3dayplots_os38nb.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termwh300log2010_027_63831.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_027_55377.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_030_85039.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_028_65835.txt.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termwh300log2010_030_84736.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/termwh300log2010_028_57422.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_028_57447.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/lastensq_os38bb.warn  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_027_55430.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_027_56441.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_027_55377.txt.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_028_57422.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_030_84868.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_031_00688.txt.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_030_84736.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_028_05770.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_030_85325.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/quick_wh300.warn  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termwh300log2010_029_15093.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/hg_km1001b.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_028_09221.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/DAS_main.log  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/termwh300log2010_030_84624.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_031_17441.txt.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termwh300log2010_029_14172.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/lastensq_wh300.warn  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_027_55430.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/Cruise_km1001a.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_028_65835.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/oswh_term.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/DAS_while_logging.log.1  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_030_84937.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/quick_wh300.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/DAS_while_logging.log.6  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/termwh300log2010_031_57168.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_030_85325.txt.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termwh300log2010_027_63564.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_027_56011.txt.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/DAS_while_logging.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/lastensq_os38bb.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_031_57168.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/termwh300log2010_030_84375.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/quick_os38bb.warn  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termwh300log2010_027_56011.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/hcorrstats_posmv.warn  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_030_84300.txt.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/hg_km1001c.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_030_86377.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_031_00026.txt.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_031_17552.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_027_63831.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termwh300log2010_030_84300.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_028_57447.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/Cruise_test_01.log  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_027_55430.txt.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_031_00875.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/3dayplots_os38bb.warn  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_027_63662.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/termos38log2010_027_63564.txt  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/log2010_030_85039.txt  
 extracting: codas_demos/uhdas_data/km1001c/raw/log/log2010_030_84497.txt.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/log/DAS_while_logging.log.9  
   creating: codas_demos/uhdas_data/km1001c/raw/os38
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_50400.raw.log.bin  
 extracting: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_17261.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_17265.raw.err  
 extracting: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_83559.raw.log  
 extracting: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_83559.raw  
   creating: codas_demos/uhdas_data/km1001c/raw/os38/pygbin
   creating: codas_demos/uhdas_data/km1001c/raw/os38/pygbin/os38
   creating: codas_demos/uhdas_data/km1001c/raw/os38/pygbin/os38/time
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_029_64800.raw.log.bin  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_83730.raw.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_28018.raw.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_28800.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_43200.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_17538.raw.log.bin  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_84666.raw.log.bin  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_28800.raw.log.bin  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_00000.raw  
 extracting: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_17781.raw.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_85516.raw.log.bin  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_16997.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_14400.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_17538.raw.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_14400.raw.log.bin  
 extracting: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_83674.raw.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_21600.raw.log.bin  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_029_64800.raw.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_50400.raw.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_07200.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_029_79200.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_36000.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_28018.raw.log.bin  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_14400.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_83559.raw.log.bin  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_17854.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_17538.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_21600.raw.log.bin  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_36000.raw.log.bin  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_79200.raw.log.bin  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_43200.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_14400.raw.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_029_72000.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_84666.raw.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_17854.raw.log  
 extracting: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_17467.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_00000.raw.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_17781.raw.log.bin  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_36000.raw.log.bin  
 extracting: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_17186.raw.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_36000.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_21600.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_50400.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_14400.raw.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_79200.raw.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_17190.raw.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_029_72000.raw.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_64800.raw.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_64800.raw.log.bin  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_17088.raw.err  
 extracting: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_17781.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_84666.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_43200.raw.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_00000.raw.log.bin  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_00851.raw.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_50400.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_00851.raw.log.bin  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_50400.raw.log.bin  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_17467.raw.log.bin  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_72000.raw.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_72000.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_029_79200.raw.log.bin  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_07200.raw.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_17186.raw.log.bin  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_57600.raw.log.bin  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_14400.raw.log.bin  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_85516.raw.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_43200.raw.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_57600.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_17470.raw.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_83730.raw.log.bin  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_07200.raw.log.bin  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_43200.raw.log.bin  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/current.cmd  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_16997.raw.log.bin  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_17854.raw.log.bin  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_17785.raw.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_07200.raw.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_17261.raw.log.bin  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_28018.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_85516.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_28800.raw.log.bin  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_07200.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_28800.raw.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_83564.raw.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_07200.raw.log.bin  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_50400.raw.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_69097.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_16997.raw.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_28800.raw.log  
 extracting: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_17467.raw.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_00851.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_21600.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_64800.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_72000.raw.log.bin  
 extracting: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_83674.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_83674.raw.log.bin  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_029_63671.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_029_63671.raw.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_21600.raw.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_029_64800.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_43200.raw.log.bin  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_029_72000.raw.log.bin  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_36000.raw.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_69097.raw.log  
 extracting: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_17261.raw.log  
 extracting: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_17186.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_28800.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_029_63671.raw.log.bin  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_83679.raw.err  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_031_36000.raw.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_21600.raw.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_57600.raw.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_83730.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_79200.raw  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_029_79200.raw.log  
  inflating: codas_demos/uhdas_data/km1001c/raw/os38/km2010_030_69097.raw.log.bin  
   creating: codas_demos/uhdas_data/km1001c/raw/gyro
  inflating: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_029_72000.hdg.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_031_00851.hdg.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_030_64800.hdg.gz  
 extracting: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_031_17186.hdg.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_030_57600.hdg.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_031_17538.hdg.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_030_00000.hdg.gz  
 extracting: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_031_17781.hdg.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_031_21600.hdg.gz  
 extracting: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_031_17467.hdg.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_030_69097.hdg.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_030_50400.hdg.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_030_85516.hdg.gz  
 extracting: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_030_83674.hdg.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_031_28800.hdg.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_030_07200.hdg.gz  
 extracting: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_030_83559.hdg.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_029_64800.hdg.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_031_17261.hdg.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_031_28018.hdg.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_031_07200.hdg.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_030_36000.hdg.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_031_36000.hdg.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_030_72000.hdg.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_030_14400.hdg.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_031_14400.hdg.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_030_21600.hdg.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_029_79200.hdg.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_031_43200.hdg.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_030_83730.hdg.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_030_79200.hdg.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_029_63671.hdg.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_030_43200.hdg.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_030_28800.hdg.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_031_50400.hdg  
  inflating: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_030_84666.hdg.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_031_16997.hdg.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/gyro/km2010_031_17854.hdg.gz  
   creating: codas_demos/uhdas_data/km1001c/raw/simrad
  inflating: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_029_72000.gps.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_029_64800.gps.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_030_79200.gps.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_031_36000.gps.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_030_69097.gps.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_031_50400.gps  
 extracting: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_031_17538.gps.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_030_28800.gps.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_031_28800.gps.gz  
 extracting: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_030_83674.gps.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_031_28018.gps.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_030_07200.gps.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_030_57600.gps.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_030_50400.gps.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_030_21600.gps.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_030_72000.gps.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_030_14400.gps.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_030_36000.gps.gz  
 extracting: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_030_84666.gps.gz  
 extracting: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_031_17781.gps.gz  
 extracting: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_031_17186.gps.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_030_85516.gps.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_030_83730.gps.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_030_64800.gps.gz  
 extracting: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_031_16997.gps.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_030_00000.gps.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_031_07200.gps.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_031_17854.gps.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_031_21600.gps.gz  
 extracting: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_030_83559.gps.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_030_43200.gps.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_029_79200.gps.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_031_00851.gps.gz  
 extracting: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_031_17261.gps.gz  
 extracting: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_031_17467.gps.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_031_43200.gps.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_029_63671.gps.gz  
  inflating: codas_demos/uhdas_data/km1001c/raw/simrad/km2010_031_14400.gps.gz  
   creating: codas_demos/uhdas_data/km1001c/raw/config
  inflating: codas_demos/uhdas_data/km1001c/raw/config/km1001c_proc.m  
  inflating: codas_demos/uhdas_data/km1001c/raw/config/procsetup_onship.py  
  inflating: codas_demos/uhdas_data/km1001c/raw/config/km1001c_proc.py  
  inflating: codas_demos/uhdas_data/km1001c/raw/config/km1001c_cfg.m  
  inflating: codas_demos/uhdas_data/km1001c/raw/config/sensor_cfg.py  
   creating: codas_demos/uhdas_data/km1001c/gbin
  inflating: codas_demos/uhdas_data/km1001c/gbin/ztimefit.txt  
   creating: codas_demos/uhdas_data/km1001c/gbin/os38
   creating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_031_17538.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_57600.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_83559.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_031_14400.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_031_17467.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_50400.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_83730.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_83674.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_031_28018.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_031_50400.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_031_28800.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_031_21600.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_69097.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_031_07200.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_031_16997.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_64800.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_83674.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_72000.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_84666.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_85516.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_79200.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_07200.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_031_17186.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_029_64800.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_83730.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_031_00851.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_79200.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_029_79200.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_031_28018.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_031_17781.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_36000.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_031_36000.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_21600.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_031_00851.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_28800.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_85516.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_21600.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_57600.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_031_17467.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_031_36000.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_031_17538.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_69097.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_43200.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_029_72000.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_031_14400.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_00000.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_029_79200.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_07200.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_72000.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_031_43200.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_029_63671.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_64800.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_031_50400.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_031_07200.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_029_72000.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_43200.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_031_28800.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_00000.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_28800.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_031_17854.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_031_17854.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_031_16997.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_36000.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_031_17261.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_031_43200.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_14400.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_031_17781.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_031_21600.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_029_64800.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_031_17261.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_83559.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_50400.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_14400.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_031_17186.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_029_63671.adu.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/ashtech/km2010_030_84666.gps.gbin  
   creating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_031_14400.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_50400.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_031_21600.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_21600.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_031_28800.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_031_14400.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_83559.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_031_17467.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_031_17186.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_83730.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_031_28018.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_031_43200.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_85516.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_69097.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_79200.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_031_16997.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_64800.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_83674.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_72000.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_031_16997.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_79200.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_07200.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_031_17186.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_84666.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_029_63671.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_031_17854.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_64800.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_57600.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_029_64800.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_031_00851.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_72000.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_031_00851.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_029_72000.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_031_28018.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_031_50400.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_029_79200.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_029_64800.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_031_17781.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_031_17781.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_14400.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_21600.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_28800.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_85516.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_57600.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_28800.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_031_17467.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_031_36000.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_031_17538.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_031_36000.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_43200.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_031_43200.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_029_63671.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_029_79200.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_07200.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_83674.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_031_50400.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_031_07200.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_031_17538.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_029_72000.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_43200.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_031_28800.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_00000.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_031_17261.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_031_17854.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_83730.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_36000.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_031_17261.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_14400.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_00000.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_36000.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_031_07200.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_031_21600.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_83559.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_50400.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_69097.pmv.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/posmv/km2010_030_84666.gps.gbin  
   creating: codas_demos/uhdas_data/km1001c/gbin/os38/time
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_031_21600.best.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_031_43200.best.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_69097.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_36000.best.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_029_79200.best.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_84666.best.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_83730.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_029_64800.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_031_28800.best.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_031_28800.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_14400.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_14400.best.gbin  
 extracting: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_83559.best.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_031_16997.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_031_36000.best.gbin  
 extracting: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_031_17186.best.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_031_17854.best.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_83730.best.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_72000.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_031_50400.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_64800.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_50400.best.gbin  
 extracting: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_031_17781.best.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_57600.best.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_57600.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_83559.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_50400.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_031_07200.best.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_029_63671.tim.gbin  
 extracting: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_031_17467.best.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_031_17854.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_00000.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_031_28018.tim.gbin  
 extracting: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_031_16997.best.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_029_72000.best.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_07200.tim.gbin  
 extracting: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_83674.best.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_029_63671.best.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_84666.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_85516.best.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_72000.best.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_00000.best.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_031_17186.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_031_14400.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_07200.best.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_28800.best.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_031_00851.best.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_79200.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_28800.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_79200.best.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_43200.best.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_85516.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_029_79200.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_83674.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_64800.best.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_031_14400.best.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_36000.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_031_17781.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_21600.best.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_031_00851.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_031_21600.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_031_17538.best.gbin  
 extracting: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_031_17261.best.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_031_07200.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_031_36000.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_031_17538.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_43200.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_029_72000.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_031_17467.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_69097.best.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_029_64800.best.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_030_21600.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_031_28018.best.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_031_43200.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_031_17261.tim.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/time/km2010_031_50400.best.gbin  
   creating: codas_demos/uhdas_data/km1001c/gbin/os38/gyro
 extracting: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_031_17781.hdg.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_030_84666.hdg.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_030_72000.hdg.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_030_85516.hdg.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_031_00851.hdg.gbin  
 extracting: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_031_16997.hdg.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_031_36000.hdg.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_031_17538.hdg.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_029_63671.hdg.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_031_43200.hdg.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_030_64800.hdg.gbin  
 extracting: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_030_83674.hdg.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_029_64800.hdg.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_031_28800.hdg.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_030_69097.hdg.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_029_79200.hdg.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_030_83730.hdg.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_030_43200.hdg.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_031_21600.hdg.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_031_50400.hdg.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_030_36000.hdg.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_030_21600.hdg.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_030_79200.hdg.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_030_07200.hdg.gbin  
 extracting: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_031_17467.hdg.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_030_00000.hdg.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_031_17854.hdg.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_031_07200.hdg.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_030_57600.hdg.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_030_50400.hdg.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_030_28800.hdg.gbin  
 extracting: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_031_17186.hdg.gbin  
 extracting: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_031_17261.hdg.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_031_28018.hdg.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_029_72000.hdg.gbin  
 extracting: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_030_83559.hdg.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_031_14400.hdg.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/gyro/km2010_030_14400.hdg.gbin  
   creating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_031_14400.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_030_83730.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_031_28018.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_030_69097.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_031_16997.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_030_64800.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_030_83674.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_030_72000.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_030_79200.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_030_07200.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_031_17186.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_029_64800.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_031_00851.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_029_79200.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_031_17781.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_030_21600.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_030_28800.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_030_85516.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_030_57600.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_031_17467.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_031_36000.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_031_17538.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_031_43200.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_029_63671.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_031_50400.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_031_07200.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_029_72000.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_030_43200.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_031_28800.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_030_00000.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_031_17854.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_030_36000.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_031_17261.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_030_14400.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_031_21600.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_030_83559.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_030_50400.gps.gbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/os38/simrad/km2010_030_84666.gps.gbin  
   creating: codas_demos/uhdas_data/km1001c/gbin/heading
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_031_28800.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_031_00851.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_031_43200.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_031_14400.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_030_79200.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_030_07200.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_030_14400.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_030_85516.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_030_36000.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_030_72000.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_030_83559.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_031_17538.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_030_43200.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_030_83730.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_030_28800.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_031_28018.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_030_50400.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_030_21600.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_031_17261.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_031_07200.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_029_72000.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_031_17467.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_031_17854.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_031_21600.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_029_63671.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_031_17781.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_030_00000.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_030_84666.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_031_36000.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_030_69097.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_029_79200.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_030_64800.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_031_17186.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_031_50400.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_030_83674.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_030_57600.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_031_16997.hbin  
  inflating: codas_demos/uhdas_data/km1001c/gbin/heading/km2010_029_64800.hbin  
  inflating: codas_demos/uhdas_data/km1001c/.DS_Store  
  inflating: codas_demos/uhdas_data/.DS_Store  
   creating: codas_demos/uhdas_style_data
   creating: codas_demos/uhdas_style_data/ps0918_os75
   creating: codas_demos/uhdas_style_data/ps0918_os75/rbin
   creating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N3R
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N3R/zzz2009_264_61662.gps.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N3R/zzz2009_264_67032.gps.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N3R/zzz2009_264_77765.gps.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N3R/zzz2009_264_78932.gps.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N3R/zzz2009_264_52554.gps.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N3R/zzz2009_264_56851.gps.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N3R/zzz2009_264_83135.gps.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N3R/zzz2009_264_83609.gps.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N3R/zzz2009_264_72399.gps.rbin  
   creating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N1R
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N1R/zzz2009_264_72399.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N1R/zzz2009_264_83135.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N1R/zzz2009_264_78932.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N1R/zzz2009_264_61662.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N1R/zzz2009_264_83609.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N1R/zzz2009_264_77765.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N1R/zzz2009_264_56851.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N1R/zzz2009_264_67032.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N1R/zzz2009_264_52554.hdg.rbin  
   creating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_78932.at2.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_61662.at2.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_77765.at2.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_83609.adu.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_78932.adu.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_77765.adu.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_61662.gps.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_67032.gps.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_67032.adu.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_72399.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_77765.gps.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_72399.at2.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_67032.at2.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_83609.at2.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_61662.adu.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_72399.adu.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_78932.gps.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_52554.gps.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_56851.gps.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_83135.at2.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_83135.gps.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_83135.adu.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_83609.gps.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_52554.at2.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_72399.gps.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_56851.adu.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_83135.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_78932.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_61662.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_83609.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_77765.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_56851.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_56851.at2.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_52554.adu.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_67032.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/N2R/zzz2009_264_52554.hdg.rbin  
   creating: codas_demos/uhdas_style_data/ps0918_os75/rbin/synchro
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/synchro/zzz2009_264_72399.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/synchro/zzz2009_264_83135.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/synchro/zzz2009_264_78932.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/synchro/zzz2009_264_61662.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/synchro/zzz2009_264_83609.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/synchro/zzz2009_264_77765.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/synchro/zzz2009_264_56851.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/synchro/zzz2009_264_67032.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/rbin/synchro/zzz2009_264_52554.hdg.rbin  
   creating: codas_demos/uhdas_style_data/ps0918_os75/raw
   creating: codas_demos/uhdas_style_data/ps0918_os75/raw/os75
  inflating: codas_demos/uhdas_style_data/ps0918_os75/raw/os75/name_map.txt  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/raw/os75/zzz2009_264_83609.raw  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/raw/os75/zzz2009_264_83609.raw.log.bin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/raw/os75/zzz2009_264_72399.raw.log.bin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/raw/os75/zzz2009_264_56851.raw.log.bin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/raw/os75/zzz2009_264_77765.raw.log.bin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/raw/os75/zzz2009_264_61662.raw  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/raw/os75/zzz2009_264_83135.raw  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/raw/os75/zzz2009_264_67032.raw  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/raw/os75/zzz2009_264_56851.raw  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/raw/os75/zzz2009_264_83135.raw.log.bin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/raw/os75/zzz2009_264_52554.raw.log.bin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/raw/os75/zzz2009_264_77765.raw  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/raw/os75/zzz2009_264_78932.raw  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/raw/os75/zzz2009_264_78932.raw.log.bin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/raw/os75/zzz2009_264_72399.raw  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/raw/os75/zzz2009_264_52554.raw  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/raw/os75/zzz2009_264_61662.raw.log.bin  
  inflating: codas_demos/uhdas_style_data/ps0918_os75/raw/os75/zzz2009_264_67032.raw.log.bin  
   creating: codas_demos/uhdas_style_data/ps0918_manual
   creating: codas_demos/uhdas_style_data/ps0918_manual/rbin
   creating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N3R
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N3R/zzz2009_264_61662.gps.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N3R/zzz2009_264_67032.gps.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N3R/zzz2009_264_77765.gps.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N3R/zzz2009_264_78932.gps.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N3R/zzz2009_264_52554.gps.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N3R/zzz2009_264_56851.gps.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N3R/zzz2009_264_83135.gps.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N3R/zzz2009_264_83609.gps.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N3R/zzz2009_264_72399.gps.rbin  
   creating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N1R
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N1R/zzz2009_264_72399.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N1R/zzz2009_264_83135.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N1R/zzz2009_264_78932.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N1R/zzz2009_264_61662.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N1R/zzz2009_264_83609.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N1R/zzz2009_264_77765.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N1R/zzz2009_264_56851.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N1R/zzz2009_264_67032.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N1R/zzz2009_264_52554.hdg.rbin  
   creating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_78932.at2.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_61662.at2.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_77765.at2.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_83609.adu.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_78932.adu.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_77765.adu.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_61662.gps.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_67032.gps.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_67032.adu.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_72399.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_77765.gps.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_72399.at2.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_67032.at2.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_83609.at2.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_61662.adu.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_72399.adu.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_78932.gps.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_52554.gps.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_56851.gps.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_83135.at2.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_83135.gps.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_83135.adu.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_83609.gps.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_52554.at2.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_72399.gps.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_56851.adu.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_83135.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_78932.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_61662.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_83609.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_77765.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_56851.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_56851.at2.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_52554.adu.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_67032.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/N2R/zzz2009_264_52554.hdg.rbin  
   creating: codas_demos/uhdas_style_data/ps0918_manual/rbin/synchro
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/synchro/zzz2009_264_72399.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/synchro/zzz2009_264_83135.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/synchro/zzz2009_264_78932.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/synchro/zzz2009_264_61662.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/synchro/zzz2009_264_83609.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/synchro/zzz2009_264_77765.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/synchro/zzz2009_264_56851.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/synchro/zzz2009_264_67032.hdg.rbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/rbin/synchro/zzz2009_264_52554.hdg.rbin  
   creating: codas_demos/uhdas_style_data/ps0918_manual/raw
   creating: codas_demos/uhdas_style_data/ps0918_manual/raw/os75
  inflating: codas_demos/uhdas_style_data/ps0918_manual/raw/os75/name_map.txt  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/raw/os75/zzz2009_264_83609.raw  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/raw/os75/zzz2009_264_83609.raw.log.bin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/raw/os75/zzz2009_264_72399.raw.log.bin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/raw/os75/zzz2009_264_56851.raw.log.bin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/raw/os75/zzz2009_264_77765.raw.log.bin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/raw/os75/zzz2009_264_61662.raw  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/raw/os75/zzz2009_264_83135.raw  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/raw/os75/zzz2009_264_67032.raw  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/raw/os75/zzz2009_264_56851.raw  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/raw/os75/zzz2009_264_83135.raw.log.bin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/raw/os75/zzz2009_264_52554.raw.log.bin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/raw/os75/zzz2009_264_77765.raw  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/raw/os75/zzz2009_264_78932.raw  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/raw/os75/zzz2009_264_78932.raw.log.bin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/raw/os75/zzz2009_264_72399.raw  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/raw/os75/zzz2009_264_52554.raw  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/raw/os75/zzz2009_264_61662.raw.log.bin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/raw/os75/zzz2009_264_67032.raw.log.bin  
   creating: codas_demos/uhdas_style_data/ps0918_manual/gbin
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/ztimefit.txt  
   creating: codas_demos/uhdas_style_data/ps0918_manual/gbin/heading
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/heading/zzz2009_264_67032.hbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/heading/zzz2009_264_61662.hbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/heading/zzz2009_264_83135.hbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/heading/zzz2009_264_72399.hbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/heading/zzz2009_264_77765.hbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/heading/zzz2009_264_78932.hbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/heading/zzz2009_264_83609.hbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/heading/zzz2009_264_52554.hbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/heading/zzz2009_264_56851.hbin  
   creating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75
   creating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N3R
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N3R/zzz2009_264_61662.gps.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N3R/zzz2009_264_77765.gps.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N3R/zzz2009_264_52554.gps.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N3R/zzz2009_264_72399.gps.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N3R/zzz2009_264_56851.gps.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N3R/zzz2009_264_67032.gps.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N3R/zzz2009_264_83135.gps.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N3R/zzz2009_264_78932.gps.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N3R/zzz2009_264_83609.gps.gbin  
   creating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N1R
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N1R/zzz2009_264_52554.hdg.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N1R/zzz2009_264_72399.hdg.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N1R/zzz2009_264_56851.hdg.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N1R/zzz2009_264_61662.hdg.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N1R/zzz2009_264_83135.hdg.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N1R/zzz2009_264_77765.hdg.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N1R/zzz2009_264_67032.hdg.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N1R/zzz2009_264_78932.hdg.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N1R/zzz2009_264_83609.hdg.gbin  
   creating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/time
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/time/zzz2009_264_61662.tim.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/time/zzz2009_264_67032.tim.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/time/zzz2009_264_67032.best.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/time/zzz2009_264_56851.tim.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/time/zzz2009_264_72399.best.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/time/zzz2009_264_77765.tim.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/time/zzz2009_264_61662.best.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/time/zzz2009_264_83609.tim.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/time/zzz2009_264_83135.best.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/time/zzz2009_264_56851.best.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/time/zzz2009_264_72399.tim.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/time/zzz2009_264_77765.best.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/time/zzz2009_264_52554.tim.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/time/zzz2009_264_83135.tim.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/time/zzz2009_264_78932.best.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/time/zzz2009_264_83609.best.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/time/zzz2009_264_52554.best.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/time/zzz2009_264_78932.tim.gbin  
   creating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_52554.hdg.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_52554.at2.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_61662.at2.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_72399.hdg.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_56851.adu.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_77765.adu.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_67032.adu.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_61662.gps.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_61662.adu.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_78932.at2.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_56851.hdg.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_77765.gps.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_52554.gps.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_72399.adu.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_72399.at2.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_61662.hdg.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_67032.at2.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_78932.adu.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_77765.at2.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_83135.adu.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_83135.hdg.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_72399.gps.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_77765.hdg.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_56851.gps.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_67032.hdg.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_67032.gps.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_78932.hdg.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_83609.at2.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_83135.gps.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_83609.adu.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_78932.gps.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_52554.adu.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_56851.at2.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_83135.at2.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_83609.gps.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/N2R/zzz2009_264_83609.hdg.gbin  
   creating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/synchro
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/synchro/zzz2009_264_52554.hdg.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/synchro/zzz2009_264_72399.hdg.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/synchro/zzz2009_264_56851.hdg.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/synchro/zzz2009_264_61662.hdg.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/synchro/zzz2009_264_83135.hdg.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/synchro/zzz2009_264_77765.hdg.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/synchro/zzz2009_264_67032.hdg.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/synchro/zzz2009_264_78932.hdg.gbin  
  inflating: codas_demos/uhdas_style_data/ps0918_manual/gbin/os75/synchro/zzz2009_264_83609.hdg.gbin  
   creating: codas_demos/adcp_pyproc
   creating: codas_demos/adcp_pyproc/ps0918_vmdas
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/enr_manual_info.txt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/quality
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/quality/arrdepos.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/quality/arrdepuw.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/quality/profstuw.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/quality/profstos.cnt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/edit
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/edit/fix_temp.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/edit/aship_npings.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/edit/lst_npings.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/edit/clearflags.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/edit/setflags.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/edit/edit.log  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/edit/NPingplot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/edit/Tempplot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/edit/setup.m  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/edit/profst00.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/edit/lst_temp.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/edit/lst_temp.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/edit/profst02.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/edit/setflags.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/edit/codas_editparams.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/edit/temp_plot.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/edit/aship.tem  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/edit/nping_plot.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/edit/setflags.log  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/edit/aship.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/edit/newflag.cnt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal/heading
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal/botmtrk
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal/botmtrk/Btplot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal/botmtrk/aship.btm  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal/botmtrk/btcal.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal/botmtrk/refabsbt.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal/botmtrk/refabsbt.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal/botmtrk/aship.ref  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal/botmtrk/lst_btrk.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal/botmtrk/btcal_edited.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal/botmtrk/btcaluv.out  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal/botmtrk/lst_btrk.tmp  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal/watertrk
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal/watertrk/wtcal_edited.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal/watertrk/wtcal2.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal/watertrk/aship_7.cal  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal/watertrk/guess_xducerxy.out  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal/watertrk/Wtplot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal/watertrk/wtcal1.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal/watertrk/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal/watertrk/timslip.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal/watertrk/Guess_Xducerxy_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal/watertrk/adcpcal.out  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal/watertrk/timslip.cnt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal/rotate
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal/rotate/ens_hcorr_264.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal/rotate/lst_hdg.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal/rotate/rotnav.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal/rotate/lst_hdg.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal/rotate/ens_hcorr.asc  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal/rotate/rotate.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal/rotate/ens_hcorr.ang  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal/rotate/scn.hdg  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cal/rotate/Hcorrplot_script.py  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/vector
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/vector/vector.sub  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/vector/vector.vec  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/vector/aship.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/vector/vector_uv.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/vector/vector_xy.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/vector/as_vect.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/vector/vector.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/vector/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/vector/vector.sta  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/vector/aship.tmg  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/stick
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/stick/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/dbinfo.txt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/contour
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/contour/allbins_u.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/contour/contour.sub  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/contour/aship.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/contour/allbins_other.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/contour/contour_uv.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/contour/asdj.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/contour/allbins_w.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/contour/allbins_v.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/contour/as_cont.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/contour/allbins_sw.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/contour/allbins_raw_amp.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/contour/aspc.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/contour/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/contour/contour.sta  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/contour/allbins_pg.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/contour/allbins_e.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/contour/allbins_depth.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/contour/allbins_pf.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/contour/allbins_resid_stats.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/contour/allbins_tseries_diffstats.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/contour/allbins_amp.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/contour/allbins_bt.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/contour/contour_xy.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/contour/aship.tmg  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/contour/allbins_tseries_stats.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/cruise_info.txt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/scan
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/scan/Scanping_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/scan/aship.tr  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/scan/scanping.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/scan/aship.scn  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/nav
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/nav/aship_xy.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/nav/put_tuv.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/nav/put_txy.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/nav/refabs.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/nav/smoothr.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/nav/aship.bin  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/nav/smoothr.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/nav/aship.uvship  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/nav/aship.agt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/nav/refabs.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/nav/edfix.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/nav/put_txy.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/nav/Refplot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/nav/putnav.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/nav/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/nav/Refsm_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/nav/aship.sta  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/nav/put_tuv.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/nav/aship.gps  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/nav/getnav.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/nav/uvship_plot.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/nav/Navplot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/nav/aship.ref  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/nav/UVShipPlot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/nav/ubprint.cnt  
 extracting: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/nav/aship_uv.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/nav/aship.nav  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/nav/as_nav.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/nav/reflayer_264.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/nav/aship.log  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/nav/aship.sm  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/nav/nav_plot.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/nav/refsm_tuv.asc  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/ping
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/ping/datafile_list.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/quick_run.log  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/grid
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/grid/timegrid.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/grid/llgrid.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/grid/llcont.cnt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/config
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/config/ps0918_manual_proc.py  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/load
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/load/ens_blk001.tuv  
 extracting: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/load/wrote_ens_time  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/load/ens_blk002.gpst2  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/load/ens_blk002.bin  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/load/ens_blk002.cmd  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/load/ens_blk002.gps2  
 extracting: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/load/load.log  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/load/lastens.npz  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/load/loadping.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/load/vmadcp.def  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/load/ens_blk001.cmd  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/load/loadpc.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/load/ens_blk001.uvship  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/load/ens_blk001.gpst2  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/load/write_ensblk.log  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/load/ens_blk001.bin  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/load/PingAverage_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/load/ldcodas.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/load/ens_blk002.uvship  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/load/Pygbin_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/load/ens_blk001.gps2  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/load/ens_last_written.asc  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/load/ens_blk002.tuv  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/load/ping_editparams.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/q_py.cnt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/adcpdb
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/adcpdb/aship002.blk  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/adcpdb/ashipdir.blk  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/adcpdb/lst_conf.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/adcpdb/aship.lst  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/adcpdb/aship001.blk  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/adcpdb/mkblkdir.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/adcpdb/aship.tr  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/adcpdb/lst_prof.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/adcpdb/lst_conf.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual/adcpdb/aship.cnh  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/ps0918_quick_os75bb_LTA_info.txt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/quality
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/quality/arrdepos.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/quality/arrdepuw.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/quality/profstuw.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/quality/profstos.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/run_command.log  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/edit
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/edit/fix_temp.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/edit/aship_npings.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/edit/lst_npings.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/edit/clearflags.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/edit/setflags.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/edit/edit.log  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/edit/NPingplot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/edit/Tempplot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/edit/setup.m  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/edit/profst00.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/edit/lst_temp.cnt  
 extracting: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/edit/abadprf.asclog  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/edit/lst_temp.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/edit/profst02.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/edit/setflags.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/edit/codas_editparams.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/edit/temp_plot.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/edit/abadbin.asclog  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/edit/aship.tem  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/edit/nping_plot.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/edit/setflags.log  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/edit/aship.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/edit/newflag.cnt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/heading
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/botmtrk
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/botmtrk/Btplot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/botmtrk/aship.btm  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/botmtrk/btcal.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/botmtrk/refabsbt.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/botmtrk/refabsbt.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/botmtrk/aship.ref  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/botmtrk/lst_btrk.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/botmtrk/btcal_edited.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/botmtrk/btcaluv.out  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/botmtrk/lst_btrk.tmp  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/watertrk
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/watertrk/wtcal_edited.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/watertrk/wtcal2.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/watertrk/aship_7.cal  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/watertrk/guess_xducerxy.out  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/watertrk/Wtplot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/watertrk/wtcal1.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/watertrk/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/watertrk/timslip.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/watertrk/Guess_Xducerxy_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/watertrk/adcpcal.out  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/watertrk/timslip.cnt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/rotate
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/rotate/ens_hcorr_264.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/rotate/lst_hdg.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/rotate/rotnav.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/rotate/lst_hdg.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/rotate/ens_hcorr.asc  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/rotate/rotate.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/rotate/rotate.log  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/rotate/ens_hcorr.ang  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/rotate/scn.hdg  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/rotate/Hcorrplot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cal/rotate/rotate.tmp  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/vector
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/vector/vector.sub  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/vector/vector.vec  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/vector/aship.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/vector/vector_uv.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/vector/vector_xy.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/vector/as_vect.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/vector/vector.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/vector/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/vector/vector.sta  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/vector/aship.tmg  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/stick
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/stick/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/dbinfo.txt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/contour
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/contour/allbins_u.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/contour/contour.sub  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/contour/aship.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/contour/allbins_other.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/contour/contour_uv.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/contour/asdj.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/contour/allbins_w.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/contour/allbins_v.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/contour/as_cont.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/contour/allbins_sw.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/contour/allbins_raw_amp.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/contour/aspc.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/contour/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/contour/contour.sta  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/contour/allbins_pg.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/contour/allbins_e.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/contour/allbins_depth.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/contour/allbins_pf.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/contour/allbins_resid_stats.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/contour/allbins_tseries_diffstats.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/contour/allbins_amp.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/contour/allbins_bt.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/contour/contour_xy.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/contour/os75bb.nc  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/contour/aship.tmg  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/contour/allbins_tseries_stats.mat  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/os75bb_loncont000.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/os75bb_loncont001.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/os75bb_vect000.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/os75bb_txy000.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/os75bb_loncont002.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/os75bb_latcont000.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/os75bb_latcont002.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/os75bb_txy001.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/os75bb_loncont001.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/os75bb_vect002.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/os75bb_vect000.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/os75bb_loncont000.png  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/thumbnails
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/thumbnails/os75bb_latcont001_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/thumbnails/os75bb_loncont000_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/thumbnails/os75bb_vect002_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/thumbnails/os75bb_loncont002_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/thumbnails/os75bb_loncont001_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/thumbnails/os75bb_ddaycont002_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/thumbnails/os75bb_ddaycont001_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/thumbnails/os75bb_vect001_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/thumbnails/ADCP_vectoverview_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/thumbnails/os75bb_vect000_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/thumbnails/os75bb_overview_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/thumbnails/os75bb_txy000_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/thumbnails/os75bb_txy001_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/thumbnails/os75bb_latcont000_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/thumbnails/os75bb_txy002_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/thumbnails/os75bb_ddaycont000_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/thumbnails/small_vectoverview_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/thumbnails/os75bb_latcont002_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/os75bb_ddaycont000.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/os75bb_ddaycont002.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/ADCP_vectoverview.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/ADCP_vectoverview.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/index.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/os75bb_vect002.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/os75bb_latcont000.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/os75bb_txy001.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/os75bb_overview.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/os75bb_ddaycont002.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/os75bb_overview.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/secnames.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/os75bb_latcont001.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/os75bb_ddaycont001.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/os75bb_latcont002.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/os75bb_ddaycont000.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/os75bb_vect001.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/os75bb_txy000.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/os75bb_txy002.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/os75bb_ddaycont001.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/os75bb_vect001.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/os75bb_latcont001.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/os75bb_txy002.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/os75bb_loncont002.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/webpy/sectinfo.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/cruise_info.txt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/scan
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/scan/Scanping_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/scan/aship.tr  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/scan/scanping.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/scan/aship.scn  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav/aship_xy.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav/put_tuv.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav/put_txy.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav/refabs.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav/smoothr.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav/aship.bin  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav/smoothr.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav/aship.uvship  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav/aship.agt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav/refabs.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav/edfix.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav/put_txy.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav/Refplot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav/putnav.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav/Refsm_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav/aship.sta  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav/put_tuv.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav/aship.gps  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav/getnav.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav/uvship_plot.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav/Navplot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav/aship.ref  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav/UVShipPlot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav/ubprint.cnt  
 extracting: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav/aship_uv.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav/XducerXY_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav/aship.nav  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav/as_nav.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav/reflayer_264.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav/aship.log  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav/aship.sm  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav/nav_plot.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/nav/refsm_tuv.asc  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/ping
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/ping/datafile_list.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/quick_run.log  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/grid
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/grid/timegrid.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/grid/llgrid.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/grid/llcont.cnt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/config
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/config/ps0918_os75_proc.py  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/load
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/load/ens_blk001.tuv  
 extracting: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/load/wrote_ens_time  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/load/ens_blk002.gpst2  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/load/ens_blk002.bin  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/load/ens_blk002.cmd  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/load/ens_blk002.gps2  
 extracting: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/load/load.log  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/load/lastens.npz  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/load/loadping.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/load/vmadcp.def  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/load/ens_blk001.cmd  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/load/loadpc.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/load/ens_blk001.uvship  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/load/ens_blk001.gpst2  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/load/write_ensblk.log  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/load/ens_blk001.bin  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/load/PingAverage_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/load/ldcodas.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/load/ens_blk002.uvship  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/load/Pygbin_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/load/ens_blk001.gps2  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/load/ens_last_written.asc  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/load/ens_blk002.tuv  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/load/ping_editparams.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/q_py.cnt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/adcpdb
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/adcpdb/aship002.blk  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/adcpdb/ashipdir.blk  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/adcpdb/lst_conf.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/adcpdb/aship.lst  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/adcpdb/aship001.blk  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/adcpdb/mkblkdir.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/adcpdb/aship.tr  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/adcpdb/aship.bbn  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/adcpdb/lst_prof.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/adcpdb/lst_conf.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ENR/adcpdb/aship.cnh  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_enr.txt~  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75_enr_info.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/lta_manual_info.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/ps0918_os75bb_LTA_info.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/ps0918_os75bb_LTA_proc.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/compare.log  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/ps0918_quick_os75bb_LTA_proc.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_enrproc.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/lta_info.txt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/quality
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/quality/arrdepos.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/quality/arrdepuw.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/quality/profstuw.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/quality/profstos.cnt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/edit
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/edit/fix_temp.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/edit/setup.m  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/edit/profst00.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/edit/lst_temp.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/edit/profst02.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/edit/setflags.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/edit/newflag.cnt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/cal
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/cal/heading
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/cal/botmtrk
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/cal/botmtrk/refabsbt.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/cal/botmtrk/lst_btrk.cnt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/cal/watertrk
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/cal/watertrk/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/cal/watertrk/timslip.cnt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/cal/rotate
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/cal/rotate/rotnav.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/cal/rotate/lst_hdg.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/cal/rotate/rotate.cnt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/vector
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/vector/vector.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/vector/adcpsect.cnt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/stick
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/stick/adcpsect.cnt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/contour
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/contour/asdj.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/contour/aspc.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/contour/adcpsect.cnt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/scan
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/scan/scanping.cnt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/nav
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/nav/put_txy.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/nav/refabs.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/nav/smoothr.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/nav/edfix.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/nav/putnav.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/nav/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/nav/put_tuv.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/nav/getnav.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/nav/ubprint.cnt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/ping
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/grid
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/grid/timegrid.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/grid/llgrid.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/grid/llcont.cnt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/load
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/load/loadping.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/load/vmadcp.def  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/load/loadpc.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/q_py.cnt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/adcpdb
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/adcpdb/lst_conf.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/adcpdb/mkblkdir.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_manual_lta/adcpdb/lst_prof.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_lta.txt~  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os38nb_postproc.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os38nb_fullproc.txt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/config
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/config/ps0918_manual_proc.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/config/reform_defs_os75.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/config/reform_defs.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/config/vmdas2uhdas.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/config/vmdas2uhdas_os75.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/config/ps0918_os75_proc.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_ltaproc.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc.txt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/quality
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/quality/arrdepos.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/quality/arrdepuw.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/quality/profstuw.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/quality/profstos.cnt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/edit
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/edit/fix_temp.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/edit/aship_npings.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/edit/lst_npings.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/edit/clearflags.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/edit/setflags.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/edit/edit.log  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/edit/NPingplot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/edit/Tempplot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/edit/setup.m  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/edit/profst00.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/edit/lst_temp.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/edit/abadprf.asclog  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/edit/lst_temp.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/edit/profst02.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/edit/setflags.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/edit/codas_editparams.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/edit/temp_plot.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/edit/abadbin.asclog  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/edit/aship.tem  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/edit/nping_plot.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/edit/setflags.log  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/edit/aship.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/edit/newflag.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/edit/abottom.asclog  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cal
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cal/heading
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cal/botmtrk
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cal/botmtrk/Btplot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cal/botmtrk/aship.btm  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cal/botmtrk/btcal.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cal/botmtrk/refabsbt.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cal/botmtrk/refabsbt.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cal/botmtrk/aship.ref  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cal/botmtrk/lst_btrk.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cal/botmtrk/btcal_edited.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cal/botmtrk/btcaluv.out  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cal/botmtrk/lst_btrk.tmp  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cal/watertrk
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cal/watertrk/wtcal_edited.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cal/watertrk/wtcal2.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cal/watertrk/aship_7.cal  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cal/watertrk/guess_xducerxy.out  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cal/watertrk/Wtplot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cal/watertrk/wtcal1.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cal/watertrk/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cal/watertrk/timslip.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cal/watertrk/Guess_Xducerxy_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cal/watertrk/adcpcal.out  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cal/watertrk/timslip.cnt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cal/rotate
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cal/rotate/lst_hdg.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cal/rotate/rotnav.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cal/rotate/lst_hdg.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cal/rotate/rotate.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cal/rotate/rotate.log  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cal/rotate/scn.hdg  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cal/rotate/rotate.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cals.txt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/vector
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/vector/vector.sub  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/vector/vector.vec  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/vector/aship.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/vector/vector_uv.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/vector/vector_xy.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/vector/as_vect.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/vector/vector.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/vector/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/vector/vector.sta  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/vector/aship.tmg  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/stick
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/stick/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/dbinfo.txt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/contour
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/contour/allbins_u.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/contour/contour.sub  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/contour/aship.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/contour/allbins_other.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/contour/contour_uv.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/contour/asdj.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/contour/allbins_w.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/contour/allbins_v.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/contour/as_cont.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/contour/allbins_sw.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/contour/allbins_raw_amp.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/contour/aspc.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/contour/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/contour/CODAS_netcfd_variables.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/contour/contour.sta  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/contour/CODAS_processing_note.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/contour/allbins_pg.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/contour/allbins_e.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/contour/allbins_depth.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/contour/allbins_pf.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/contour/allbins_resid_stats.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/contour/allbins_tseries_diffstats.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/contour/allbins_amp.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/contour/allbins_bt.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/contour/contour_xy.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/contour/os75bb.nc  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/contour/aship.tmg  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/contour/allbins_tseries_stats.mat  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/os75bb_loncont000.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/os75bb_loncont001.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/os75bb_vect000.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/os75bb_txy000.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/os75bb_loncont002.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/os75bb_latcont000.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/os75bb_latcont002.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/os75bb_txy001.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/os75bb_loncont001.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/os75bb_vect002.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/os75bb_vect000.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/os75bb_loncont000.png  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/thumbnails
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/thumbnails/os75bb_latcont001_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/thumbnails/os75bb_loncont000_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/thumbnails/os75bb_vect002_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/thumbnails/os75bb_loncont002_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/thumbnails/os75bb_loncont001_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/thumbnails/os75bb_ddaycont002_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/thumbnails/os75bb_ddaycont001_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/thumbnails/os75bb_vect001_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/thumbnails/ADCP_vectoverview_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/thumbnails/os75bb_vect000_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/thumbnails/os75bb_overview_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/thumbnails/os75bb_txy000_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/thumbnails/os75bb_txy001_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/thumbnails/os75bb_latcont000_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/thumbnails/os75bb_txy002_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/thumbnails/os75bb_ddaycont000_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/thumbnails/small_vectoverview_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/thumbnails/os75bb_latcont002_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/os75bb_ddaycont000.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/os75bb_ddaycont002.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/ADCP_vectoverview.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/ADCP_vectoverview.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/index.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/os75bb_vect002.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/os75bb_latcont000.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/os75bb_txy001.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/os75bb_overview.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/os75bb_ddaycont002.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/os75bb_overview.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/secnames.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/os75bb_latcont001.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/os75bb_ddaycont001.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/os75bb_latcont002.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/os75bb_ddaycont000.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/os75bb_vect001.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/os75bb_txy000.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/os75bb_txy002.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/os75bb_ddaycont001.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/os75bb_vect001.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/os75bb_latcont001.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/os75bb_txy002.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/os75bb_loncont002.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/webpy/sectinfo.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/cruise_info.txt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/scan
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/scan/ScanLTA_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/scan/aship.tr  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/scan/scanping.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/scan/aship.scn  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/nav
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/nav/aship_xy.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/nav/put_tuv.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/nav/put_txy.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/nav/refabs.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/nav/smoothr.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/nav/aship.bin  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/nav/smoothr.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/nav/refabs.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/nav/edfix.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/nav/put_txy.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/nav/Refplot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/nav/putnav.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/nav/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/nav/Refsm_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/nav/aship.sta  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/nav/put_tuv.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/nav/aship.gps  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/nav/getnav.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/nav/Navplot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/nav/aship.ref  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/nav/UVShipPlot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/nav/ubprint.cnt  
 extracting: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/nav/aship_uv.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/nav/XducerXY_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/nav/aship.nav  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/nav/as_nav.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/nav/reflayer_264.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/nav/aship.log  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/nav/aship.sm  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/nav/nav_plot.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/nav/refsm_tuv.asc  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/ping
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/ping/data_filelist.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/quick_run.log  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/grid
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/grid/timegrid.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/grid/llgrid.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/grid/llcont.cnt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/load
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/load/Collins_PtSur_Ridge007_000000.LTA.cmd  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/load/Collins_PtSur_Ridge005_000000.LTA.gps2  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/load/Collins_PtSur_Ridge006_000000.LTA.bin  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/load/Collins_PtSur_Ridge005_000000.LTA.cmd  
 extracting: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/load/load.log  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/load/loadping.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/load/vmadcp.def  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/load/Collins_PtSur_Ridge005_000000.LTA.bin  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/load/loadpc.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/load/Collins_PtSur_Ridge006_000000.LTA.gps2  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/load/ldcodas.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/load/LoadLTA_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/load/Collins_PtSur_Ridge007_000000.LTA.gps2  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/load/Collins_PtSur_Ridge006_000000.LTA.cmd  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/load/Collins_PtSur_Ridge007_000000.LTA.bin  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/q_py.cnt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/adcpdb
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/adcpdb/aship002.blk  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/adcpdb/ashipdir.blk  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/adcpdb/lst_conf.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/adcpdb/aship.lst  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/adcpdb/aship001.blk  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/adcpdb/mkblkdir.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/adcpdb/aship.tr  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/adcpdb/aship.bbn  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/adcpdb/lst_prof.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/adcpdb/aship003.blk  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/adcpdb/lst_conf.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA/adcpdb/aship.cnh  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/quality
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/quality/arrdepos.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/quality/arrdepuw.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/quality/profstuw.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/quality/profstos.cnt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/edit
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/edit/fix_temp.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/edit/aship_npings.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/edit/lst_npings.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/edit/clearflags.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/edit/setflags.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/edit/edit.log  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/edit/NPingplot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/edit/Tempplot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/edit/setup.m  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/edit/profst00.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/edit/lst_temp.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/edit/abadprf.asclog  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/edit/lst_temp.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/edit/profst02.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/edit/setflags.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/edit/codas_editparams.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/edit/temp_plot.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/edit/abadbin.asclog  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/edit/aship.tem  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/edit/nping_plot.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/edit/setflags.log  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/edit/aship.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/edit/newflag.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/edit/abottom.asclog  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cal
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cal/heading
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cal/botmtrk
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cal/botmtrk/Btplot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cal/botmtrk/aship.btm  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cal/botmtrk/btcal.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cal/botmtrk/refabsbt.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cal/botmtrk/refabsbt.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cal/botmtrk/aship.ref  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cal/botmtrk/lst_btrk.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cal/botmtrk/btcal_edited.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cal/botmtrk/btcaluv.out  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cal/botmtrk/lst_btrk.tmp  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cal/watertrk
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cal/watertrk/wtcal_edited.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cal/watertrk/wtcal2.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cal/watertrk/aship_7.cal  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cal/watertrk/guess_xducerxy.out  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cal/watertrk/Wtplot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cal/watertrk/wtcal1.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cal/watertrk/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cal/watertrk/timslip.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cal/watertrk/Guess_Xducerxy_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cal/watertrk/adcpcal.out  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cal/watertrk/timslip.cnt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cal/rotate
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cal/rotate/lst_hdg.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cal/rotate/rotnav.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cal/rotate/lst_hdg.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cal/rotate/rotate.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cal/rotate/rotate.log  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cal/rotate/scn.hdg  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cal/rotate/rotate.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cals.txt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/vector
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/vector/vector.sub  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/vector/vector.vec  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/vector/aship.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/vector/vector_uv.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/vector/vector_xy.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/vector/as_vect.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/vector/vector.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/vector/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/vector/vector.sta  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/vector/aship.tmg  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/view.log  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/stick
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/stick/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/dbinfo.txt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/contour
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/contour/allbins_u.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/contour/contour.sub  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/contour/aship.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/contour/allbins_other.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/contour/contour_uv.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/contour/asdj.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/contour/allbins_w.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/contour/allbins_v.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/contour/as_cont.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/contour/allbins_sw.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/contour/allbins_raw_amp.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/contour/aspc.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/contour/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/contour/CODAS_netcfd_variables.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/contour/contour.sta  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/contour/os75bb_short.nc  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/contour/CODAS_processing_note.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/contour/allbins_pg.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/contour/allbins_e.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/contour/allbins_depth.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/contour/allbins_pf.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/contour/allbins_resid_stats.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/contour/allbins_tseries_diffstats.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/contour/allbins_amp.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/contour/allbins_bt.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/contour/contour_xy.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/contour/os75bb.nc  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/contour/aship.tmg  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/contour/allbins_tseries_stats.mat  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/webpy
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/webpy/os75bb_loncont000.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/webpy/os75bb_vect000.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/webpy/os75bb_txy000.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/webpy/os75bb_latcont000.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/webpy/os75bb_vect000.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/webpy/os75bb_loncont000.png  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/webpy/thumbnails
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/webpy/thumbnails/os75bb_loncont000_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/webpy/thumbnails/ADCP_vectoverview_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/webpy/thumbnails/os75bb_vect000_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/webpy/thumbnails/os75bb_overview_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/webpy/thumbnails/os75bb_txy000_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/webpy/thumbnails/os75bb_latcont000_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/webpy/thumbnails/os75bb_ddaycont000_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/webpy/thumbnails/small_vectoverview_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/webpy/os75bb_ddaycont000.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/webpy/ADCP_vectoverview.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/webpy/ADCP_vectoverview.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/webpy/index.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/webpy/os75bb_latcont000.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/webpy/os75bb_overview.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/webpy/os75bb_overview.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/webpy/secnames.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/webpy/os75bb_ddaycont000.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/webpy/os75bb_txy000.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/webpy/sectinfo.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/cruise_info.txt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/scan
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/scan/ScanLTA_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/scan/aship.tr  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/scan/scanping.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/scan/aship.scn  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/nav
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/nav/aship_xy.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/nav/put_tuv.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/nav/put_txy.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/nav/refabs.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/nav/smoothr.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/nav/aship.bin  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/nav/smoothr.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/nav/refabs.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/nav/edfix.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/nav/put_txy.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/nav/Refplot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/nav/putnav.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/nav/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/nav/Refsm_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/nav/aship.sta  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/nav/put_tuv.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/nav/aship.gps  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/nav/getnav.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/nav/Navplot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/nav/aship.ref  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/nav/UVShipPlot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/nav/ubprint.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/nav/aship_uv.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/nav/XducerXY_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/nav/aship.nav  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/nav/as_nav.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/nav/reflayer_264.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/nav/aship.log  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/nav/aship.sm  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/nav/nav_plot.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/nav/refsm_tuv.asc  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/ping
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/ping/data_filelist.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/quick_run.log  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/grid
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/grid/timegrid.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/grid/llgrid.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/grid/llcont.cnt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/load
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/load/Collins_PtSur_Ridge007_000000.LTA.cmd  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/load/Collins_PtSur_Ridge005_000000.LTA.gps2  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/load/Collins_PtSur_Ridge006_000000.LTA.bin  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/load/Collins_PtSur_Ridge005_000000.LTA.cmd  
 extracting: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/load/load.log  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/load/loadping.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/load/vmadcp.def  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/load/Collins_PtSur_Ridge005_000000.LTA.bin  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/load/loadpc.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/load/Collins_PtSur_Ridge006_000000.LTA.gps2  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/load/ldcodas.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/load/LoadLTA_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/load/Collins_PtSur_Ridge007_000000.LTA.gps2  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/load/Collins_PtSur_Ridge006_000000.LTA.cmd  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/load/Collins_PtSur_Ridge007_000000.LTA.bin  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/q_py.cnt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/adcpdb
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/adcpdb/aship002.blk  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/adcpdb/ashipdir.blk  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/adcpdb/lst_conf.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/adcpdb/aship.lst  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/adcpdb/aship001.blk  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/adcpdb/mkblkdir.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/adcpdb/aship.tr  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/adcpdb/aship.bbn  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/adcpdb/lst_prof.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/adcpdb/aship003.blk  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/adcpdb/lst_conf.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_LTA_postproc/adcpdb/aship.cnh  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/quality
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/quality/arrdepos.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/quality/arrdepuw.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/quality/profstuw.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/quality/profstos.cnt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/edit
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/edit/fix_temp.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/edit/aship_npings.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/edit/lst_npings.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/edit/clearflags.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/edit/setflags.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/edit/NPingplot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/edit/Tempplot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/edit/setup.m  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/edit/profst00.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/edit/lst_temp.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/edit/lst_temp.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/edit/profst02.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/edit/setflags.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/edit/codas_editparams.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/edit/temp_plot.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/edit/aship.tem  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/edit/nping_plot.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/edit/setflags.log  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/edit/aship.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/edit/newflag.cnt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/cal
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/cal/heading
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/cal/botmtrk
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/cal/botmtrk/Btplot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/cal/botmtrk/aship.btm  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/cal/botmtrk/btcal.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/cal/botmtrk/refabsbt.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/cal/botmtrk/refabsbt.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/cal/botmtrk/aship.ref  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/cal/botmtrk/lst_btrk.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/cal/botmtrk/btcal_edited.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/cal/botmtrk/btcaluv.out  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/cal/botmtrk/lst_btrk.tmp  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/cal/watertrk
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/cal/watertrk/wtcal_edited.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/cal/watertrk/wtcal2.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/cal/watertrk/aship_7.cal  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/cal/watertrk/guess_xducerxy.out  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/cal/watertrk/Wtplot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/cal/watertrk/wtcal1.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/cal/watertrk/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/cal/watertrk/timslip.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/cal/watertrk/Guess_Xducerxy_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/cal/watertrk/adcpcal.out  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/cal/watertrk/timslip.cnt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/cal/rotate
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/cal/rotate/lst_hdg.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/cal/rotate/rotnav.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/cal/rotate/lst_hdg.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/cal/rotate/rotate.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/cal/rotate/scn.hdg  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/cals.txt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/vector
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/vector/vector.sub  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/vector/vector.vec  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/vector/aship.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/vector/vector_uv.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/vector/vector_xy.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/vector/as_vect.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/vector/vector.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/vector/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/vector/vector.sta  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/vector/aship.tmg  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/stick
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/stick/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/dbinfo.txt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/contour
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/contour/allbins_u.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/contour/contour.sub  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/contour/aship.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/contour/allbins_other.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/contour/contour_uv.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/contour/asdj.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/contour/allbins_w.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/contour/allbins_v.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/contour/as_cont.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/contour/allbins_sw.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/contour/allbins_raw_amp.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/contour/aspc.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/contour/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/contour/CODAS_netcfd_variables.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/contour/contour.sta  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/contour/CODAS_processing_note.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/contour/allbins_pg.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/contour/allbins_e.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/contour/allbins_depth.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/contour/allbins_pf.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/contour/allbins_resid_stats.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/contour/allbins_tseries_diffstats.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/contour/allbins_amp.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/contour/allbins_bt.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/contour/contour_xy.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/contour/os75bb.nc  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/contour/aship.tmg  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/contour/allbins_tseries_stats.mat  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/webpy
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/webpy/os75bb_loncont000.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/webpy/os75bb_vect000.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/webpy/os75bb_txy000.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/webpy/os75bb_latcont000.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/webpy/os75bb_vect000.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/webpy/os75bb_loncont000.png  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/webpy/thumbnails
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/webpy/thumbnails/os75bb_loncont000_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/webpy/thumbnails/ADCP_vectoverview_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/webpy/thumbnails/os75bb_vect000_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/webpy/thumbnails/os75bb_overview_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/webpy/thumbnails/os75bb_txy000_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/webpy/thumbnails/os75bb_latcont000_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/webpy/thumbnails/os75bb_ddaycont000_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/webpy/thumbnails/small_vectoverview_thumb.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/webpy/os75bb_ddaycont000.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/webpy/ADCP_vectoverview.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/webpy/ADCP_vectoverview.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/webpy/index.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/webpy/os75bb_latcont000.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/webpy/os75bb_overview.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/webpy/os75bb_overview.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/webpy/secnames.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/webpy/os75bb_ddaycont000.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/webpy/os75bb_txy000.html  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/webpy/sectinfo.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/cruise_info.txt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/scan
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/scan/ScanLTA_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/scan/aship.tr  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/scan/scanping.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/scan/aship.scn  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/nav
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/nav/aship_xy.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/nav/put_tuv.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/nav/put_txy.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/nav/refabs.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/nav/smoothr.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/nav/aship.bin  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/nav/smoothr.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/nav/refabs.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/nav/edfix.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/nav/put_txy.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/nav/Refplot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/nav/putnav.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/nav/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/nav/Refsm_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/nav/aship.sta  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/nav/put_tuv.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/nav/aship.gps  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/nav/getnav.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/nav/Navplot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/nav/aship.ref  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/nav/UVShipPlot_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/nav/ubprint.cnt  
 extracting: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/nav/aship_uv.mat  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/nav/aship.nav  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/nav/as_nav.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/nav/reflayer_264.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/nav/aship.log  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/nav/aship.sm  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/nav/nav_plot.png  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/nav/refsm_tuv.asc  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/ping
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/ping/data_filelist.txt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/quick_run.log  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/grid
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/grid/timegrid.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/grid/llgrid.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/grid/llcont.cnt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/load
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/load/Collins_PtSur_Ridge007_000000.LTA.cmd  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/load/Collins_PtSur_Ridge005_000000.LTA.gps2  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/load/Collins_PtSur_Ridge006_000000.LTA.bin  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/load/Collins_PtSur_Ridge005_000000.LTA.cmd  
 extracting: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/load/load.log  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/load/loadping.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/load/vmadcp.def  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/load/Collins_PtSur_Ridge005_000000.LTA.bin  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/load/loadpc.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/load/Collins_PtSur_Ridge006_000000.LTA.gps2  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/load/ldcodas.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/load/LoadLTA_script.py  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/load/Collins_PtSur_Ridge007_000000.LTA.gps2  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/load/Collins_PtSur_Ridge006_000000.LTA.cmd  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/load/Collins_PtSur_Ridge007_000000.LTA.bin  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/q_py.cnt  
   creating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/adcpdb
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/adcpdb/aship002.blk  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/adcpdb/ashipdir.blk  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/adcpdb/lst_conf.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/adcpdb/aship.lst  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/adcpdb/aship001.blk  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/adcpdb/mkblkdir.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/adcpdb/aship.tr  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/adcpdb/lst_prof.cnt  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/adcpdb/aship003.blk  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/adcpdb/lst_conf.tmp  
  inflating: codas_demos/adcp_pyproc/ps0918_vmdas/os75bb_quicklta/adcpdb/aship.cnh  
   creating: codas_demos/adcp_pyproc/config
   creating: codas_demos/adcp_pyproc/km1001c_uhdas
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/quality
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/quality/arrdepos.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/quality/arrdepuw.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/quality/profstuw.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/quality/profstos.cnt  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/edit
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/edit/fix_temp.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/edit/aship_npings.txt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/edit/lst_npings.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/edit/clearflags.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/edit/setflags.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/edit/edit.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/edit/NPingplot_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/edit/Tempplot_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/edit/setup.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/edit/profst00.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/edit/lst_temp.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/edit/abadprf.asclog  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/edit/lst_temp.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/edit/profst02.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/edit/setflags.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/edit/codas_editparams.txt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/edit/temp_plot.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/edit/abadbin.asclog  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/edit/aship.tem  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/edit/nping_plot.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/edit/setflags.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/edit/aship.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/edit/newflag.cnt  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cal
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cal/heading
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cal/botmtrk
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cal/botmtrk/Btplot_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cal/botmtrk/aship.btm  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cal/botmtrk/refabsbt.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cal/botmtrk/refabsbt.tmp  
 extracting: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cal/botmtrk/aship.ref  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cal/botmtrk/lst_btrk.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cal/botmtrk/lst_btrk.tmp  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cal/watertrk
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cal/watertrk/wtcal_edited.txt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cal/watertrk/wtcal2.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cal/watertrk/aship_7.cal  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cal/watertrk/guess_xducerxy.out  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cal/watertrk/Wtplot_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cal/watertrk/wtcal1.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cal/watertrk/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cal/watertrk/timslip.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cal/watertrk/Guess_Xducerxy_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cal/watertrk/adcpcal.out  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cal/watertrk/timslip.cnt  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cal/rotate
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cal/rotate/lst_hdg.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cal/rotate/rotnav.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cal/rotate/lst_hdg.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cal/rotate/ens_hcorr.asc  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cal/rotate/rotate.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cal/rotate/ens_hcorr_029.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cal/rotate/rotate.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cal/rotate/ens_hcorr.ang  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cal/rotate/scn.hdg  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cal/rotate/Hcorrplot_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cal/rotate/rotate.tmp  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/vector
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/vector/vector.sub  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/vector/vector.vec  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/vector/aship.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/vector/vector_uv.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/vector/vector_xy.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/vector/as_vect.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/vector/vector.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/vector/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/vector/vector.sta  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/vector/aship.tmg  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/stick
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/stick/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/dbinfo.txt  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/contour
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/contour/allbins_u.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/contour/contour.sub  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/contour/aship.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/contour/allbins_other.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/contour/contour_uv.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/contour/asdj.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/contour/allbins_w.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/contour/allbins_v.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/contour/as_cont.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/contour/allbins_sw.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/contour/allbins_raw_amp.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/contour/aspc.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/contour/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/contour/contour.sta  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/contour/os38nb.nc  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/contour/allbins_pg.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/contour/allbins_e.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/contour/allbins_depth.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/contour/allbins_pf.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/contour/allbins_resid_stats.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/contour/allbins_tseries_diffstats.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/contour/allbins_amp.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/contour/allbins_bt.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/contour/contour_xy.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/contour/aship.tmg  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/contour/allbins_tseries_stats.mat  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_ddaycont004.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_ddaycont002.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_vect003.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_latcont004.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_loncont001.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_latcont001.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_txy001.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_ddaycont001.html  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/thumbnails
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/thumbnails/os38nb_vect004_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/thumbnails/os38nb_loncont001_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/thumbnails/os38nb_loncont003_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/thumbnails/os38nb_latcont004_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/thumbnails/os38nb_vect000_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/thumbnails/ADCP_vectoverview_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/thumbnails/os38nb_ddaycont001_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/thumbnails/os38nb_vect003_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/thumbnails/os38nb_txy000_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/thumbnails/os38nb_loncont000_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/thumbnails/os38nb_loncont002_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/thumbnails/os38nb_vect002_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/thumbnails/os38nb_latcont002_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/thumbnails/os38nb_latcont000_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/thumbnails/os38nb_ddaycont002_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/thumbnails/os38nb_loncont004_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/thumbnails/os38nb_ddaycont003_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/thumbnails/os38nb_txy003_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/thumbnails/os38nb_overview_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/thumbnails/os38nb_txy002_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/thumbnails/os38nb_txy001_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/thumbnails/os38nb_ddaycont000_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/thumbnails/os38nb_txy004_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/thumbnails/os38nb_vect001_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/thumbnails/os38nb_latcont001_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/thumbnails/small_vectoverview_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/thumbnails/os38nb_ddaycont004_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/thumbnails/os38nb_latcont003_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_loncont002.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_txy002.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_txy002.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_loncont003.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_loncont004.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/ADCP_vectoverview.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/ADCP_vectoverview.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_vect000.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/index.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_txy001.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_vect004.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_txy003.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_overview.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_latcont003.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_vect003.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_loncont004.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_ddaycont003.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/secnames.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_vect000.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_overview.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_txy003.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_vect001.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_ddaycont002.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_txy004.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_loncont000.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_latcont003.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_ddaycont004.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_latcont001.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_txy000.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_ddaycont003.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_loncont003.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_vect002.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_ddaycont001.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_txy004.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_vect002.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_latcont000.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_vect004.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_loncont000.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_ddaycont000.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_latcont000.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_ddaycont000.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_loncont001.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_latcont002.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_latcont002.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_vect001.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_latcont004.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_loncont002.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/sectinfo.txt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/webpy/os38nb_txy000.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/cruise_info.txt  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/scan
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/scan/Scanping_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/scan/aship.tr  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/scan/scanping.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/scan/aship.scn  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/aship_xy.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/put_tuv.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/put_txy.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/refabs.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/smoothr.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/aship.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/smoothr.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/aship.uvship  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/reflayer_029.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/aship.agt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/refabs.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/edfix.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/put_txy.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/Refplot_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/reflayer_031.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/putnav.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/Refsm_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/aship.sta  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/put_tuv.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/aship.gps  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/getnav.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/uvship_plot.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/Navplot_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/aship.ref  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/UVShipPlot_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/ubprint.cnt  
 extracting: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/aship_uv.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/XducerXY_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/aship.nav  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/as_nav.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/aship.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/aship.sm  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/nav_plot.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/nav/refsm_tuv.asc  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/ping
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/ping/datafile_list.txt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/quick_run.log  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/grid
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/grid/timegrid.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/grid/llgrid.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/grid/llcont.cnt  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/config
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/config/km1001c_manual_proc.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/config/km1001c_manual_proc.py~  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk004.gps2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk001.tuv  
 extracting: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/wrote_ens_time  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk002.gpst2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk002.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk007.gps2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk003.cmd  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk003.tuv  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk005.gps2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk002.cmd  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk004.cmd  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk004.tuv  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk004.gpst2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk002.gps2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk005.tuv  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk006.uvship  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk005.uvship  
 extracting: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/load.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk005.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/lastens.npz  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/loadping.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/vmadcp.def  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk001.cmd  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/loadpc.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk001.uvship  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk008.uvship  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk007.tuv  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk007.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk003.gpst2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk001.gpst2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/write_ensblk.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk006.cmd  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk004.uvship  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk001.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk007.uvship  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk003.uvship  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/PingAverage_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk006.tuv  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ldcodas.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk006.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk008.cmd  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk008.tuv  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk004.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk007.cmd  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk006.gps2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk002.uvship  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk007.gpst2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/Pygbin_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk008.gpst2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk001.gps2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk003.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk005.gpst2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_last_written.asc  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk002.tuv  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ping_editparams.txt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk006.gpst2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk003.gps2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk008.gps2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk005.cmd  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/load/ens_blk008.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/q_py.cnt  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/adcpdb
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/adcpdb/aship002.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/adcpdb/ashipdir.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/adcpdb/lst_conf.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/adcpdb/aship.lst  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/adcpdb/aship001.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/adcpdb/aship004.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/adcpdb/mkblkdir.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/adcpdb/aship.tr  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/adcpdb/aship007.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/adcpdb/aship005.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/adcpdb/aship.bbn  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/adcpdb/lst_prof.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/adcpdb/aship003.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/adcpdb/aship006.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/adcpdb/lst_conf.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/adcpdb/aship008.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc/adcpdb/aship.cnh  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/quality
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/quality/arrdepos.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/quality/stn_udw.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/quality/arrdepuw.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/quality/profstuw.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/quality/profstos.cnt  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/override_flagit.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/asetup.m__  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/a_bt.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/agetmat_hdg.txt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/a_km.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/a_amp.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/do_mkbadprf.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/threshld.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/fix_temp.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/abadprf_tmp.asc  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/a_depth.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/aflagit_setup.m__  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/setflags.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/aedit.m__  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/mkbadtimes.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/asetup.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/aedit_tmp.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/Tempplot_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/setup.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/a_km.tem  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/a_pf.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/abottom_tmp.asc  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/aREADME_basics.txt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/a_e.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/profst00.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/lst_temp.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/a_refsmnav.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/a_other.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/lst_temp.tmp  
 extracting: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/autoflagged.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/plotpg.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/profst02.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/setflags.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/lst_hdg_getmat.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/plottemp.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/abadbin_tmp.asc  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/aflagit_setup.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/a_pg.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/a_raw_amp.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/temp_plot.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/a_tseries_stats.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/a_v.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/a_u.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/a_w.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/a_sw.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/set_rawcfg.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/setflags.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/a_resid_stats.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/pltemp.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/setup.m__  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/edit/newflag.cnt  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/heading
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/heading/cal_hdg.m  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/botmtrk
 extracting: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/botmtrk/a_km.ref  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/botmtrk/a_km.btm  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/botmtrk/Btplot_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/botmtrk/refabsbt.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/botmtrk/refabsbt.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/botmtrk/lst_btrk.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/botmtrk/lst_btrk.tmp  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/watertrk
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/watertrk/a_km_7.cal  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/watertrk/wtcal2.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/watertrk/Wtplot_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/watertrk/wtcal1.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/watertrk/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/watertrk/adcpcal.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/watertrk/timslip.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/watertrk/recip.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/watertrk/adcpcal.out  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/watertrk/timslip.cnt  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/rotate
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/rotate/print_hcorrstats_all.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/rotate/hcorr_mpl_029.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/rotate/lst_hdg.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/rotate/rotnav.cnt  
 extracting: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/rotate/ens_hcorr_err.txt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/rotate/lst_hdg.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/rotate/ashrot.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/rotate/ens_hcorr.asc  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/rotate/rotate.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/rotate/rotate.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/rotate/ens_hcorr.ang  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/rotate/plot_hcorrstats_all.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/rotate/scn.hdg  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/rotate/Hcorrplot_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cal/rotate/rotate.tmp  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/vector
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/vector/vector.vec  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/vector/vector_uv.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/vector/vector_xy.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/vector/a_km.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/vector/as_vect.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/vector/vector.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/vector/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/vector/vector.sta  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/vector/a_km.tmg  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/stick
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/stick/runstick.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/stick/adcpsect.cnt  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/contour
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/contour/allbins_u.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/contour/allbins_other.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/contour/contour_uv.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/contour/allbins_w.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/contour/allbins_v.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/contour/as_cont.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/contour/allbins_sw.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/contour/a_km.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/contour/allbins_raw_amp.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/contour/contour.cpa  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/contour/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/contour/contour.sta  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/contour/allbins_pg.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/contour/allbins_e.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/contour/allbins_depth.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/contour/allbins_pf.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/contour/allbins_resid_stats.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/contour/allbins_amp.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/contour/a_km.tmg  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/contour/allbins_bt.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/contour/contour_xy.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/contour/allbins_tseries_stats.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/os38nb_qpy.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/cruise_info.txt  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/png_archive
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/png_archive/030_os38nb_shallow.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/png_archive/031_os38nb_loncont.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/png_archive/029_os38nb_ddaycont.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/png_archive/031_os38nb_ddaycont.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/png_archive/030_os38nb_ddaycont.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/png_archive/030_os38nb_latcont.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/png_archive/030_os38nb_loncont.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/png_archive/029_os38nb_latcont.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/png_archive/031_os38nb_latcont.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/png_archive/029_os38nb_loncont.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/png_archive/030_os38nb_cor_history.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/png_archive/031_os38nb_shallow.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/png_archive/029_os38nb_shallow.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/png_archive/030_os38nb_bin_history.png  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/scan
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/scan/ub_1920.def  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/scan/ub_1020.def  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/scan/ub_1320.def  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/scan/scan_tmp.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/scan/clkrate.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/scan/ub_2240.def  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/scan/a_km.tr  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/scan/ub_720.def  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/scan/scanping.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/scan/ub_1280.def  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/scan/ub_1281.def  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/scan/a_km.scn  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/nav
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/nav/xducerxy.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/nav/refabs.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/nav/smoothr.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/nav/callrefp.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/nav/a_km.gps  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/nav/putnav.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/nav/smoothr.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/nav/a_km.ref  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/nav/a_km.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/nav/reflayer_029.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/nav/refabs.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/nav/a_km.sm  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/nav/callrefp.m__  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/nav/edfix.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/nav/Refplot_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/nav/reflayer_031.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/nav/a_km_xy.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/nav/putnav.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/nav/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/nav/Refsm_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/nav/a_km.sta  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/nav/a_km.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/nav/getnav.cnt  
 extracting: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/nav/a_km_uv.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/nav/Navplot_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/nav/cruistrk.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/nav/refsm.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/nav/ubprint.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/nav/a_km.nav  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/nav/attplot.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/nav/a_km_refsm.asc  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/nav/as_nav.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/nav/nav_plot.png  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/ping
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/ping/loadrun.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/adcp_processing.html  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/grid
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/grid/timegrid.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/grid/llgrid.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/template_rpt.txt  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/config
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/config/km1001c_proc.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/config/procsetup_onship.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/config/km1001c_cfg.m  
 extracting: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/config/instping.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/config/cruise_cfg.m__  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/config/sensor_cfg.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/config/cruise_proc.m__  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/km1001c.runlog  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk004.gps2  
 extracting: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/new_ens_TF  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk007.gps1  
 extracting: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/wrote_ens_time  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/lastens.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/lastens_amp1.sbin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk002.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk007.gps2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk003.cmd  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk005.gps2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk002.cmd  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/lastens_t.sbin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ldcodas.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/override_editcfg.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/prepedit.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk004.cmd  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk001.gps1  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk003.gps1  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk002.gps2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk008.gps1  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk002.gps1  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/load_uhblk_tmp.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk006.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk006.gps1  
 extracting: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/load.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk005.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk003.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk007.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk009.gps2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/loadping.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/vmadcp.def  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk001.cmd  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk001.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk009.cmd  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/loadpc.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk004.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ldcodas_path.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ldcodas.cnt__  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/lastens_v.sbin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk007.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk008.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/write_ensblk.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk006.cmd  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk004.gps1  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/lastens_z.sbin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk001.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ldcodas.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk006.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk008.cmd  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/lastens_u.sbin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/lastens_instpflag.sbin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk009.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk004.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk007.cmd  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk006.gps2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk009.gps1  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk009.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk002.log  
 extracting: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/hcorr_rbin.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk001.gps2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk003.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk003.gps2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/load_uh.m__  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk008.gps2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk005.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk005.cmd  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk008.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/load/ens_blk005.gps1  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/adcpdb
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/adcpdb/a_km006.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/adcpdb/a_km005.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/adcpdb/a_km.cnh  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/adcpdb/mkblkdir.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/adcpdb/adcp1320.def  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/adcpdb/a_km003.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/adcpdb/lst_conf.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/adcpdb/a_kmdir.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/adcpdb/a_km007.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/adcpdb/a_km.bbn  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/adcpdb/adcp2240.def  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/adcpdb/adcp720.def  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/adcpdb/a_km009.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/adcpdb/mkblkdir.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/adcpdb/a_km008.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/adcpdb/a_km.lst  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/adcpdb/a_km.tr  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/adcpdb/ademo.def  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/adcpdb/a_km002.blk  
 extracting: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/adcpdb/lstblock.errs  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/adcpdb/lst_prof.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/adcpdb/adcp1281.def  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/adcpdb/lst_conf.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/adcpdb/a_km004.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/adcpdb/a_km001.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc_orig/adcpdb/adcp1920.def  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/quality
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/quality/arrdepos.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/quality/stn_udw.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/quality/arrdepuw.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/quality/profstuw.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/quality/profstos.cnt  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/override_flagit.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/asetup.m__  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/a_bt.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/agetmat_hdg.txt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/a_km.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/a_amp.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/do_mkbadprf.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/threshld.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/fix_temp.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/abadprf_tmp.asc  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/a_depth.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/aflagit_setup.m__  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/setflags.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/aedit.m__  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/mkbadtimes.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/asetup.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/aedit_tmp.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/edit.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/NPingplot_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/Tempplot_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/setup.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/a_km.tem  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/a_pf.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/abottom_tmp.asc  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/aREADME_basics.txt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/a_e.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/profst00.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/lst_temp.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/a_refsmnav.mat  
 extracting: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/abadprf.asclog  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/a_other.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/lst_temp.tmp  
 extracting: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/autoflagged.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/plotpg.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/profst02.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/setflags.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/lst_hdg_getmat.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/plottemp.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/temp_plot.pdf  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/abadbin_tmp.asc  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/aflagit_setup.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/codas_editparams.txt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/a_pg.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/a_raw_amp.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/temp_plot.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/a_tseries_stats.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/a_v.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/abadbin.asclog  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/a_u.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/a_w.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/a_sw.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/set_rawcfg.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/setflags.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/a_resid_stats.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/pltemp.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/setup.m__  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/edit/newflag.cnt  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/heading
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/heading/cal_hdg.m  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/botmtrk
 extracting: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/botmtrk/a_km.ref  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/botmtrk/a_km.btm  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/botmtrk/Btplot_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/botmtrk/refabsbt.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/botmtrk/refabsbt.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/botmtrk/lst_btrk.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/botmtrk/lst_btrk.tmp  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/watertrk
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/watertrk/a_km_7.cal  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/watertrk/wtcal_edited.txt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/watertrk/wtcal2.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/watertrk/guess_xducerxy.out  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/watertrk/wtcal2.pdf  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/watertrk/Wtplot_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/watertrk/wtcal1.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/watertrk/wtcal1.pdf  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/watertrk/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/watertrk/adcpcal.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/watertrk/timslip.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/watertrk/Guess_Xducerxy_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/watertrk/recip.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/watertrk/adcpcal.out  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/watertrk/timslip.cnt  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/rotate
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/rotate/print_hcorrstats_all.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/rotate/ens_hcorr_mpl_029.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/rotate/hcorr_mpl_029.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/rotate/lst_hdg.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/rotate/rotnav.cnt  
 extracting: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/rotate/ens_hcorr_err.txt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/rotate/lst_hdg.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/rotate/ens_hcorr_mpl_029.pdf  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/rotate/ashrot.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/rotate/ens_hcorr.asc  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/rotate/rotate.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/rotate/rotate.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/rotate/ens_hcorr.ang  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/rotate/plot_hcorrstats_all.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/rotate/scn.hdg  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/rotate/Hcorrplot_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cal/rotate/rotate.tmp  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/vector
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/vector/vector.sub  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/vector/vector.vec  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/vector/vector_uv.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/vector/vector_xy.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/vector/a_km.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/vector/as_vect.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/vector/vector.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/vector/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/vector/vector.sta  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/vector/a_km.tmg  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/stick
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/stick/runstick.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/stick/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/dbinfo.txt  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/contour
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/contour/allbins_u.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/contour/contour.sub  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/contour/allbins_other.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/contour/contour_uv.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/contour/allbins_w.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/contour/allbins_v.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/contour/as_cont.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/contour/os38nb_short.nc  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/contour/os38nb_long.nc  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/contour/allbins_sw.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/contour/a_km.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/contour/allbins_raw_amp.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/contour/contour.cpa  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/contour/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/contour/contour.sta  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/contour/os38nb.nc  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/contour/allbins_pg.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/contour/allbins_e.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/contour/allbins_depth.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/contour/allbins_pf.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/contour/allbins_resid_stats.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/contour/allbins_tseries_diffstats.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/contour/allbins_amp.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/contour/a_km.tmg  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/contour/allbins_bt.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/contour/contour_xy.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/contour/allbins_tseries_stats.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/os38nb_qpy.cnt  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_ddaycont004.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_ddaycont002.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_vect003.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_latcont004.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_loncont001.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_latcont001.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_txy001.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_ddaycont001.html  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/thumbnails
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/thumbnails/os38nb_vect004_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/thumbnails/os38nb_loncont001_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/thumbnails/os38nb_loncont003_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/thumbnails/os38nb_latcont004_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/thumbnails/os38nb_vect000_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/thumbnails/ADCP_vectoverview_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/thumbnails/os38nb_ddaycont001_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/thumbnails/os38nb_vect003_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/thumbnails/os38nb_txy000_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/thumbnails/os38nb_loncont000_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/thumbnails/os38nb_loncont002_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/thumbnails/os38nb_vect002_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/thumbnails/os38nb_latcont002_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/thumbnails/os38nb_latcont000_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/thumbnails/os38nb_ddaycont002_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/thumbnails/os38nb_loncont004_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/thumbnails/os38nb_ddaycont003_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/thumbnails/os38nb_txy003_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/thumbnails/os38nb_overview_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/thumbnails/os38nb_txy002_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/thumbnails/os38nb_txy001_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/thumbnails/os38nb_ddaycont000_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/thumbnails/os38nb_txy004_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/thumbnails/os38nb_vect001_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/thumbnails/os38nb_latcont001_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/thumbnails/small_vectoverview_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/thumbnails/os38nb_ddaycont004_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/thumbnails/os38nb_latcont003_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_loncont002.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_txy002.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_txy002.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_loncont003.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_loncont004.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/ADCP_vectoverview.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/ADCP_vectoverview.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_vect000.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/index.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_txy001.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_vect004.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_txy003.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_overview.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_latcont003.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_vect003.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_loncont004.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_ddaycont003.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/secnames.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_vect000.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_overview.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_txy003.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_vect001.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_ddaycont002.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_txy004.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_loncont000.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_latcont003.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_ddaycont004.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_latcont001.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_txy000.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_ddaycont003.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_loncont003.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_vect002.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_ddaycont001.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_txy004.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_vect002.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_latcont000.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_vect004.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_loncont000.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_ddaycont000.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_latcont000.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_ddaycont000.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_loncont001.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_latcont002.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_latcont002.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_vect001.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_latcont004.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_loncont002.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/sectinfo.txt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/webpy/os38nb_txy000.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/cruise_info.txt  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/png_archive
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/png_archive/030_os38nb_shallow.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/png_archive/031_os38nb_loncont.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/png_archive/029_os38nb_ddaycont.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/png_archive/031_os38nb_ddaycont.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/png_archive/030_os38nb_ddaycont.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/png_archive/030_os38nb_latcont.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/png_archive/030_os38nb_loncont.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/png_archive/029_os38nb_latcont.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/png_archive/031_os38nb_latcont.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/png_archive/029_os38nb_loncont.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/png_archive/030_os38nb_cor_history.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/png_archive/031_os38nb_shallow.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/png_archive/029_os38nb_shallow.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/png_archive/030_os38nb_bin_history.png  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/scan
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/scan/ub_1920.def  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/scan/ub_1020.def  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/scan/ub_1320.def  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/scan/scan_tmp.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/scan/clkrate.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/scan/ub_2240.def  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/scan/a_km.tr  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/scan/ub_720.def  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/scan/scanping.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/scan/ub_1280.def  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/scan/ub_1281.def  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/scan/a_km.scn  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/put_tuv.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/xducerxy.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/refabs.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/smoothr.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/callrefp.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/a_km.gps  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/putnav.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/smoothr.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/a_km.ref  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/a_km.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/reflayer_029.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/refabs.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/nav_plot.pdf  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/a_km.sm  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/callrefp.m__  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/reflayer_029.pdf  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/edfix.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/put_txy.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/Refplot_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/reflayer_031.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/a_km_xy.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/putnav.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/Refsm_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/a_km.sta  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/a_km.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/getnav.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/a_km_uv.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/Navplot_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/cruistrk.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/reflayer_031.pdf  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/refsm.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/UVShipPlot_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/ubprint.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/a_km.nav  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/attplot.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/a_km_refsm.asc  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/XducerXY_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/as_nav.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/nav_plot.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/nav/refsm_tuv.asc  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/ping
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/ping/loadrun.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/adcp_processing.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/quick_run.log  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/grid
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/grid/timegrid.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/grid/llgrid.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/template_rpt.txt  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/config
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/config/km1001c_proc.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/config/procsetup_onship.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/config/km1001c_cfg.m  
 extracting: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/config/instping.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/config/cruise_cfg.m__  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/config/sensor_cfg.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/config/cruise_proc.m__  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/km1001c.runlog  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk004.gps2  
 extracting: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/new_ens_TF  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk007.gps1  
 extracting: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/wrote_ens_time  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/lastens.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/lastens_amp1.sbin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk002.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk007.gps2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk003.cmd  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk005.gps2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk002.cmd  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/lastens_t.sbin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ldcodas.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/override_editcfg.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/prepedit.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk004.cmd  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk001.gps1  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk003.gps1  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk002.gps2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk008.gps1  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk002.gps1  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/load_uhblk_tmp.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk006.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk006.gps1  
 extracting: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/load.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk005.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk003.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk007.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk009.gps2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/loadping.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/vmadcp.def  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk001.cmd  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk001.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk009.cmd  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/loadpc.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk004.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ldcodas_path.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ldcodas.cnt__  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/lastens_v.sbin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk007.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk008.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/write_ensblk.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk006.cmd  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk004.gps1  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/lastens_z.sbin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk001.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ldcodas.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk006.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk008.cmd  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/lastens_u.sbin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/lastens_instpflag.sbin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk009.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk004.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk007.cmd  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk006.gps2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk009.gps1  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk009.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk002.log  
 extracting: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/hcorr_rbin.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk001.gps2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk003.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk003.gps2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/load_uh.m__  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk008.gps2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk005.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk005.cmd  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk008.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/load/ens_blk005.gps1  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/adcpdb
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/adcpdb/a_km006.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/adcpdb/a_km005.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/adcpdb/a_km.cnh  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/adcpdb/mkblkdir.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/adcpdb/adcp1320.def  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/adcpdb/a_km003.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/adcpdb/lst_conf.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/adcpdb/a_kmdir.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/adcpdb/a_km007.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/adcpdb/a_km.bbn  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/adcpdb/adcp2240.def  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/adcpdb/adcp720.def  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/adcpdb/a_km009.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/adcpdb/mkblkdir.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/adcpdb/a_km008.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/adcpdb/a_km.lst  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/adcpdb/a_km.tr  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/adcpdb/ademo.def  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/adcpdb/a_km002.blk  
 extracting: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/adcpdb/lstblock.errs  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/adcpdb/lst_prof.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/adcpdb/adcp1281.def  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/adcpdb/lst_conf.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/adcpdb/a_km004.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/adcpdb/a_km001.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc/adcpdb/adcp1920.def  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_postproc.txt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb_fullproc.txt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb.txt  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/config
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/config/km1001c_manual_proc.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/config/km_proc.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/config/km1001c_proc.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/config/km1001c_manual_proc.py~  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/quality
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/quality/arrdepos.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/quality/arrdepuw.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/quality/profstuw.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/quality/profstos.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/run_command.log  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/edit
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/edit/fix_temp.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/edit/aship_npings.txt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/edit/view.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/edit/lst_npings.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/edit/clearflags.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/edit/setflags.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/edit/edit.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/edit/NPingplot_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/edit/Tempplot_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/edit/setup.m  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/edit/profst00.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/edit/lst_temp.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/edit/abadprf.asclog  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/edit/lst_temp.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/edit/profst02.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/edit/setflags.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/edit/codas_editparams.txt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/edit/debug.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/edit/temp_plot.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/edit/abadbin.asclog  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/edit/aship.tem  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/edit/nping_plot.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/edit/setflags.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/edit/aship.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/edit/newflag.cnt  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cal
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cal/heading
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cal/botmtrk
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cal/botmtrk/Btplot_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cal/botmtrk/aship.btm  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cal/botmtrk/refabsbt.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cal/botmtrk/refabsbt.tmp  
 extracting: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cal/botmtrk/aship.ref  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cal/botmtrk/lst_btrk.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cal/botmtrk/lst_btrk.tmp  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cal/watertrk
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cal/watertrk/wtcal_edited.txt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cal/watertrk/wtcal2.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cal/watertrk/aship_7.cal  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cal/watertrk/guess_xducerxy.out  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cal/watertrk/Wtplot_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cal/watertrk/wtcal1.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cal/watertrk/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cal/watertrk/timslip.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cal/watertrk/Guess_Xducerxy_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cal/watertrk/adcpcal.out  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cal/watertrk/timslip.cnt  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cal/rotate
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cal/rotate/lst_hdg.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cal/rotate/rotnav.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cal/rotate/lst_hdg.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cal/rotate/ens_hcorr.asc  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cal/rotate/rotate.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cal/rotate/ens_hcorr_029.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cal/rotate/rotate.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cal/rotate/ens_hcorr.ang  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cal/rotate/scn.hdg  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cal/rotate/Hcorrplot_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cal/rotate/rotate.tmp  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/vector
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/vector/vector.sub  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/vector/vector.vec  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/vector/aship.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/vector/vector_uv.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/vector/vector_xy.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/vector/as_vect.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/vector/vector.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/vector/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/vector/vector.sta  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/vector/aship.tmg  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/stick
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/stick/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/dbinfo.txt  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/contour
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/contour/allbins_u.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/contour/contour.sub  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/contour/aship.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/contour/allbins_other.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/contour/contour_uv.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/contour/asdj.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/contour/allbins_w.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/contour/allbins_v.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/contour/as_cont.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/contour/allbins_sw.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/contour/allbins_raw_amp.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/contour/aspc.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/contour/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/contour/contour.sta  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/contour/os38nb.nc  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/contour/allbins_pg.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/contour/allbins_e.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/contour/allbins_depth.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/contour/allbins_pf.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/contour/allbins_resid_stats.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/contour/allbins_tseries_diffstats.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/contour/allbins_amp.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/contour/allbins_bt.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/contour/contour_xy.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/contour/aship.tmg  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/contour/allbins_tseries_stats.mat  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/os38nb_ddaycont002.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/os38nb_loncont001.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/os38nb_latcont001.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/os38nb_txy001.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/os38nb_ddaycont001.html  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/thumbnails
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/thumbnails/os38nb_loncont001_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/thumbnails/os38nb_vect000_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/thumbnails/ADCP_vectoverview_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/thumbnails/os38nb_ddaycont001_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/thumbnails/os38nb_txy000_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/thumbnails/os38nb_loncont000_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/thumbnails/os38nb_loncont002_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/thumbnails/os38nb_vect002_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/thumbnails/os38nb_latcont002_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/thumbnails/os38nb_latcont000_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/thumbnails/os38nb_ddaycont002_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/thumbnails/os38nb_overview_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/thumbnails/os38nb_txy002_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/thumbnails/os38nb_txy001_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/thumbnails/os38nb_ddaycont000_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/thumbnails/os38nb_vect001_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/thumbnails/os38nb_latcont001_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/thumbnails/small_vectoverview_thumb.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/os38nb_loncont002.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/os38nb_txy002.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/os38nb_txy002.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/ADCP_vectoverview.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/ADCP_vectoverview.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/os38nb_vect000.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/index.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/os38nb_txy001.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/os38nb_overview.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/secnames.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/os38nb_vect000.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/os38nb_overview.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/os38nb_vect001.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/os38nb_ddaycont002.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/os38nb_loncont000.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/os38nb_latcont001.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/os38nb_txy000.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/os38nb_vect002.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/os38nb_ddaycont001.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/os38nb_vect002.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/os38nb_latcont000.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/os38nb_loncont000.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/os38nb_ddaycont000.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/os38nb_latcont000.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/os38nb_ddaycont000.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/os38nb_loncont001.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/os38nb_latcont002.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/os38nb_latcont002.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/os38nb_vect001.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/os38nb_loncont002.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/sectinfo.txt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/webpy/os38nb_txy000.html  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/cruise_info.txt  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/scan
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/scan/Scanping_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/scan/aship.tr  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/scan/scanping.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/scan/aship.scn  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/aship_xy.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/put_tuv.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/put_txy.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/refabs.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/smoothr.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/aship.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/smoothr.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/aship.uvship  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/reflayer_029.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/aship.agt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/refabs.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/edfix.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/put_txy.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/Refplot_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/reflayer_031.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/putnav.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/adcpsect.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/Refsm_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/aship.sta  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/put_tuv.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/aship.gps  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/getnav.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/uvship_plot.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/Navplot_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/aship.ref  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/UVShipPlot_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/ubprint.cnt  
 extracting: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/aship_uv.mat  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/XducerXY_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/aship.nav  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/as_nav.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/aship.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/aship.sm  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/nav_plot.png  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/nav/refsm_tuv.asc  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/ping
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/ping/datafile_list.txt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/quick_run.log  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/grid
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/grid/timegrid.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/grid/llgrid.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/grid/llcont.cnt  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/config
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/config/km1001c_proc.py  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk004.gps2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk001.tuv  
 extracting: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/wrote_ens_time  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk002.gpst2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk002.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk007.gps2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk003.cmd  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk003.tuv  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk005.gps2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk002.cmd  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk004.cmd  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk004.tuv  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk004.gpst2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk002.gps2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk005.tuv  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk006.uvship  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk005.uvship  
 extracting: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/load.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk005.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/lastens.npz  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/loadping.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/vmadcp.def  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk001.cmd  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/loadpc.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk001.uvship  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk008.uvship  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk007.tuv  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk007.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk003.gpst2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk001.gpst2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/write_ensblk.log  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk006.cmd  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk004.uvship  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk001.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk007.uvship  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk003.uvship  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/PingAverage_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk006.tuv  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ldcodas.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk006.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk008.cmd  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk008.tuv  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk004.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk007.cmd  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk006.gps2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk002.uvship  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk007.gpst2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/Pygbin_script.py  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk008.gpst2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk001.gps2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk003.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk005.gpst2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_last_written.asc  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk002.tuv  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ping_editparams.txt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk006.gpst2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk003.gps2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk008.gps2  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk005.cmd  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/load/ens_blk008.bin  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/q_py.cnt  
   creating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/adcpdb
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/adcpdb/aship002.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/adcpdb/ashipdir.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/adcpdb/lst_conf.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/adcpdb/aship.lst  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/adcpdb/aship001.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/adcpdb/aship004.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/adcpdb/mkblkdir.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/adcpdb/aship.tr  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/adcpdb/aship007.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/adcpdb/aship005.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/adcpdb/aship.bbn  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/adcpdb/lst_prof.cnt  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/adcpdb/aship003.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/adcpdb/aship006.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/adcpdb/lst_conf.tmp  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/adcpdb/aship008.blk  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/os38nb/adcpdb/aship.cnh  
  inflating: codas_demos/adcp_pyproc/km1001c_uhdas/.DS_Store  
  inflating: codas_demos/adcp_pyproc/.DS_Store  
(pycodas) alesan@Alejandras-MacBook-Pro-2 programs % cd ~/adcpcode/topog
mkdir etopo
cd etopo
curl -O https://currents.soest.hawaii.edu/downloads/etopo1_for_pycurrents.zip
unzip etopo1_for_pycurrents.zip
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100  348M  100  348M    0     0   106M      0  0:00:03  0:00:03 --:--:--  106M
Archive:  etopo1_for_pycurrents.zip
  inflating: etopo1_ice_g_i2.bin     
  inflating: etopo1_ice_g_i2_s3.bin  
  inflating: etopo1_ice_g_i2_s9.bin  
  inflating: etopo1_ice_g_i2.hdr     
(pycodas) alesan@Alejandras-MacBook-Pro-2 etopo % cd ~/miniconda3
ln -s ~/adcpcode/topog .
cd
cd: no such file or directory: /Users/alesan/miniconda3
(pycodas) alesan@Alejandras-MacBook-Pro-2 ~ % ls | grep conda
(pycodas) alesan@Alejandras-MacBook-Pro-2 ~ % which conda
conda () {
\local cmd="${1-__missing__}"
case "$cmd" in
(activate | deactivate) __conda_activate "$@" ;;
(install | update | upgrade | remove | uninstall) __conda_exe "$@" || \return
__conda_activate reactivate ;;
(*) __conda_exe "$@" ;;
esac
}
(pycodas) alesan@Alejandras-MacBook-Pro-2 ~ % ipython
Python 3.13.13 | packaged by conda-forge | (main, Apr  8 2026, 02:29:07) [Clang 19.1.7 ]
Type 'copyright', 'credits' or 'license' for more information
IPython 9.13.0 -- An enhanced Interactive Python. Type '?' for help.
Tip: You can use files = !ls *.png

In [1]: import pycurrents

In [2]: pycurrents?
Type:        module
String form: <module 'pycurrents' from '/Users/alesan/miniforge3/envs/pycodas/lib/python3.13/site-packages/pycurrents/__init__.py'>
File:        ~/miniforge3/envs/pycodas/lib/python3.13/site-packages/pycurrents/__init__.py
Docstring:  
Package for a wide variety of routines used in adcp data
acquisition, processing, and analysis; some may be of much
wider usefulness.

More later...

In [3]: exit
(pycodas) alesan@Alejandras-MacBook-Pro-2 ~ % cd 
(pycodas) alesan@Alejandras-MacBook-Pro-2 ~ % cd miniforge3
(pycodas) alesan@Alejandras-MacBook-Pro-2 miniforge3 % ln -s ~/adcpcode/topog .
cd
(pycodas) alesan@Alejandras-MacBook-Pro-2 ~ % cd ~/adcpcode/programs/codas_demos
(pycodas) alesan@Alejandras-MacBook-Pro-2 codas_demos % ls
adcp_pyproc uhdas_data uhdas_style_data vmdas_data
(pycodas) alesan@Alejandras-MacBook-Pro-2 codas_demos % history
  579  cd ~/adcpcode/programs\ngit clone -b stable https://currents.soest.hawaii.edu/git/uh-currents-group/shipboard-adcp/codas3.git\ngit clone -b stable https://currents.soest.hawaii.edu/git/uh-currents-group/shipboard-adcp/pycurrents.git\ngit clone -b stable https://currents.soest.hawaii.edu/git/uh-currents-group/shipboard-adcp/onship.git
  580  python --version
  581  cd ~/adcpcode/programs/codas3\n./conda-install.sh\ncd ~
  582  cd ~/adcpcode/programs/pycurrents\npip install --no-build-isolation .
  583  cd ../onship\npip install --no-build-isolation .\ncd ~
  584  cd ~/adcpcode/programs\ncurl -O https://currents.soest.hawaii.edu/docs/zipped/adcp_doc.zip\nunzip adcp_doc.zip\ncurl -O https://currents.soest.hawaii.edu/docs/zipped/codas_demos.zip\nunzip codas_demos.zip
  585  cd ~/adcpcode/topog\nmkdir etopo\ncd etopo\ncurl -O https://currents.soest.hawaii.edu/downloads/etopo1_for_pycurrents.zip\nunzip etopo1_for_pycurrents.zip
  586  cd ~/miniconda3\nln -s ~/adcpcode/topog .\ncd
  587  ls | grep conda
  588  which conda
  589  ipython
  590  cd 
  591  cd miniforge3
  592  ln -s ~/adcpcode/topog .\ncd
  593  cd ~/adcpcode/programs/codas_demos
  594  ls
(pycodas) alesan@Alejandras-MacBook-Pro-2 codas_demos % ls
adcp_pyproc uhdas_data uhdas_style_data vmdas_data
(pycodas) alesan@Alejandras-MacBook-Pro-2 codas_demos % cd uhdas_data/km1001c/proc/os38nb
(pycodas) alesan@Alejandras-MacBook-Pro-2 os38nb % ls
adcp_processing.html cruise_info.txt nav scan
adcpdb edit os38nb_qpy.cnt stick
cal grid ping template_rpt.txt
config km1001c.runlog png_archive vector
contour load quality
(pycodas) alesan@Alejandras-MacBook-Pro-2 os38nb % showdb adcpdb/a_km

 DBOPEN DATABASE NAME = adcpdb/a_km

 BLK:     0   OPEN: 1    PRF:     0   OPEN: 1    IER:      0

 1 - Show BLK DIR HDR          10 - SRCH TIME
 2 - Show BLK DIR              11 - SRCH BLK/PRF
 3 - Show BLK DIR ENTRY        12 - MOVE
 4 - Show BLK HDR              13 - GET TIME
 5 - Show PRF DIR              14 - GET POS
 6 - Show PRF DIR ENTRY        15 - GET DEPTH RANGE
 7 - Show DATA LIST            16 - GET DATA
 8 - Show DATA DIR             17 - Show Data Present
 9 - Show STRUCT DEFN          18 - SHOW BLK FTR
                      99 - QUIT

 ENTER CHOICE ===> 7

 DATA LIST  NENTRIES: 82

 # name                 units      v_ty ac    ac0    ac1    offset     scale
----------------------------------------------------------------------------
 0 DEPTH                m             7  1  11376    280         0         1
 7 AMP_SOUND_SCAT       none          1  2      0      0         0         1
 8 U                    m/s           3  2      1      1         0     0.001
 9 V                    m/s           3  2      2      2         0     0.001
32 PROFILE_COMMENTS     none          2  2      3      3         0         1
33 BLOCK_COMMENTS       none          2  1      0      0         0         1
34 PROFILE_FLAGS        none          1  2      4      4         0         1
35 CONFIGURATION_1      none         11  1  11656     76         0         1
36 CONFIGURATION_2      none         11  1      0      0         0         1
37 ANCILLARY_1          none         11  2      5      5         0         1
38 ANCILLARY_2          none         11  2      6      6         0         1
39 ACCESS_VARIABLES     none         11  2      7      7         0         1
54 W                    m/s           3  2      8      8         0     0.001
55 ERROR_VEL            m/s           3  2      9      9         0     0.001
56 PERCENT_GOOD         none          1  2     10     10         0         1
57 PERCENT_3_BEAM       none          1  2     11     11         0         1
58 SPECTRAL_WIDTH       none          1  2     12     12         0         1
59 U_STD_DEV            m/s           3  2     13     13         0     0.001
60 V_STD_DEV            m/s           3  2     14     14         0     0.001
61 W_STD_DEV            m/s           3  2     15     15         0     0.001
62 EV_STD_DEV           m/s           3  2     16     16         0     0.001
63 AMP_STD_DEV          none          0  2     17     17         0         1
64 RAW_DOPPLER          none          3  2     18     18         0         1
65 RAW_AMP              none          1  2     19     19         0         1
66 RAW_SPECTRAL_WIDTH   none          1  2     20     20         0         1
67 BEAM_STATS           none          1  2     21     21         0         1
68 NAVIGATION           none         11  2     22     22         0         1
69 BOTTOM_TRACK         none         11  2     23     23         0         1
75 USER_BUFFER          none         11  2     24     24         0         1
76 ADCP_CTD             none         11  2     25     25         0         1
80 RESID_STATS          m/s           7  2     26     26         0         1
81 TSERIES_STATS        m/s           7  2     27     27         0         1
----------------------------------------------------------------------------

 ---Press enter to continue.---

 BLK:     0   OPEN: 1    PRF:     0   OPEN: 1    IER:      0

 1 - Show BLK DIR HDR          10 - SRCH TIME
 2 - Show BLK DIR              11 - SRCH BLK/PRF
 3 - Show BLK DIR ENTRY        12 - MOVE
 4 - Show BLK HDR              13 - GET TIME
 5 - Show PRF DIR              14 - GET POS
 6 - Show PRF DIR ENTRY        15 - GET DEPTH RANGE
 7 - Show DATA LIST            16 - GET DATA
 8 - Show DATA DIR             17 - Show Data Present
 9 - Show STRUCT DEFN          18 - SHOW BLK FTR
                      99 - QUIT

 ENTER CHOICE ===> 16

 ENTER VARIABLE NAME or CODE ===> U
 BLK:     0           TIME: 2010/01/30 17:46:23           LON: -125 12' 19.87"
 PRF:     0                                               LAT:   44 30' 14.07"
-------------------------------------------------------------------------------
 <Scale = 0.001>
                    U : in m/s (70 VALUES)

        3160        3183        3143        3159        3109        3143
        3083        3119        3098        3091        3110        3195
        3081        3020        3056        3084        3151        3146
        3109        3139        3070        3129        3027        2953
        2964        3017        3039        3064        3025        3062
        3103        3100        3129        3193        3090        3131
        3148        3085        3093        2924       32767       32767
       32767       32767       32767       32767       32767       32767
       32767       32767       32767       32767       32767       32767
       32767       32767       32767       32767       32767       32767
       32767       32767       32767       32767       32767       32767
       32767       32767       32767       32767
-------------------------------------------------------------------------------
 ENTER # OF PROFILES TO MOVE <return to quit> ===> 

 BLK:     0   OPEN: 1    PRF:     0   OPEN: 1    IER:      0

 1 - Show BLK DIR HDR          10 - SRCH TIME
 2 - Show BLK DIR              11 - SRCH BLK/PRF
 3 - Show BLK DIR ENTRY        12 - MOVE
 4 - Show BLK HDR              13 - GET TIME
 5 - Show PRF DIR              14 - GET POS
 6 - Show PRF DIR ENTRY        15 - GET DEPTH RANGE
 7 - Show DATA LIST            16 - GET DATA
 8 - Show DATA DIR             17 - Show Data Present
 9 - Show STRUCT DEFN          18 - SHOW BLK FTR
                      99 - QUIT

 ENTER CHOICE ===> 99
(pycodas) alesan@Alejandras-MacBook-Pro-2 os38nb % figview.py --type png
(pycodas) alesan@Alejandras-MacBook-Pro-2 os38nb % dataviewer.py
qt.qpa.fonts: Populating font family aliases took 46 ms. Replace uses of missing font family "?" with one that exists to avoid this cost. 
qt.qpa.window: Window position QRect(0,-540 702x486) outside any known screen, using primary screen
(pycodas) alesan@Alejandras-MacBook-Pro-2 os38nb % conda env list

# conda environments:
#
# * -> active
# + -> frozen
base                     /Users/alesan/miniforge3
garmin                   /Users/alesan/miniforge3/envs/garmin
jupyter                  /Users/alesan/miniforge3/envs/jupyter
ocean                    /Users/alesan/miniforge3/envs/ocean
pycodas              *   /Users/alesan/miniforge3/envs/pycodas
swot_download            /Users/alesan/miniforge3/envs/swot_download

(pycodas) alesan@Alejandras-MacBook-Pro-2 os38nb %

Show less

Thought process
Thought process
Here's a summary of what you did in this terminal session — it was a full installation and setup of the CODAS (Currents Database Software) ADCP processing environment, which is the UH Currents group's shipboard ADCP processing toolkit.

Environment setup:

Navigated to Downloads and deactivated conda's base environment
Created a new conda environment called pycodas from a codas_processing.yml file
Updated conda itself to v26.5.0
Set auto_activate_base false so conda doesn't auto-start
Code installation:

Created ~/adcpcode/ with subdirectories programs/ and topog/
Cloned three git repositories from currents.soest.hawaii.edu into programs/:
codas3 — the core C library for ADCP database management
pycurrents — Python interface for ADCP processing
onship — onship UHDAS processing tools
Compiled and installed codas3 using its conda-install.sh script (which ran waf configure, waf build, and waf install, compiling ~312 C source files)
Installed pycurrents and onship via pip install --no-build-isolation .
Documentation and demo data:

Downloaded and unzipped adcp_doc.zip (~66 MB) — full HTML documentation for UHDAS/CODAS
Downloaded and unzipped codas_demos.zip (~285 MB) — example datasets from real cruises (km1001c and ps0918)
Topography data:

Downloaded etopo1_for_pycurrents.zip (~348 MB) into ~/adcpcode/topog/etopo/
Created a symlink in ~/miniforge3/ pointing to the topog directory so pycurrents can find it
Verification:

Ran ipython and confirmed import pycurrents worked successfully
Navigated into a demo dataset (uhdas_data/km1001c/proc/os38nb)
Ran showdb to inspect the ADCP database structure and looked at U velocity data
Launched figview.py and dataviewer.py (the GUI data viewer) — confirming the full stack works
In short: you successfully installed the complete CODAS/UHDAS ADCP processing environment that the UH Currents group uses to process shipboard ADCP data. The adcpcode folder you're exploring is where all this software, demo data, and topography live.

read instructions and update
