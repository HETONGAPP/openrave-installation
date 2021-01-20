# openrave-installation

Bash scripts to install OpenRAVE from source. 

Supported distros:
* Ubuntu 14.04
* Ubuntu 16.04
* Ubuntu 18.04
* Ubuntu 20.04

## Travis - Continuous Integration

[![Build Status](https://travis-ci.org/crigroup/openrave-installation.svg?branch=master)](https://travis-ci.org/crigroup/openrave-installation)


## Installation
Run the scripts in the following order: sudo chmod +x ......
```bash
./install-dependencies.sh
./install-osg.sh
./install-fcl.sh
./install-openrave.sh
```
if use ubuntu20.04
git config --global user.name "FIRST_NAME LAST_NAME"
git config --global user.email "MY_NAME@example.com"

Always pay attention to prompts for sudo (and insert password):

cd  # go home
git clone https://github.com/crigroup/openrave-installation
cd openrave-installation
./install-dependencies.sh
./install-osg.sh
./install-fcl.sh
./install-openrave.sh
pip install ipython h5py numpy scipy wheel
