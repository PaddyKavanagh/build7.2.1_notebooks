# build7.2.1_notebooks

This repository contains Jupyter notebooks demonstrating the use of the JWST calibration pipeline (build 7.2.1, jwst0.12.3) for MIRI data within python.

build7.2.1 can be installed into an Anaconda environment as follows:

conda create --name jwst7.2.1 --file <file>

where <file> is:

Linux: http://ssb.stsci.edu/releases/jwstdp/0.12.3/latest-linux

OS X: http://ssb.stsci.edu/releases/jwstdp/0.12.3/latest-osx

The CRDS context should be set to jwst_0500.pmap for this build. Also, standard CRDS environment variables should be set. E.g., for bash:

export CRDS_PATH=/path/to/your/crds

export CRDS_SERVER_URL="https://jwst-crds.stsci.edu"

export CRDS_CONTEXT="jwst_0500.pmap"

Note that the CRDS_CONTEXT environment variable is also defined in the notebooks.
