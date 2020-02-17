# Instruction how to install python 3.7 on GCP AI Platform Notebooks.
## Install requirements
```sudo apt-get install -y build-essential checkinstall libreadline-gplv2-dev libncursesw5-dev libssl-dev libsqlite3-dev tk-dev libgdbm-dev libc6-dev libbz2-dev zlib1g-dev openssl libffi-dev python3-dev python3-setuptools wget```

## Prepare to build
* Create temporary directory
```mkdir /temp/Python37 ```
* Change directory
```cd /temp/Python37```

## Pull down Python 3.7, build, and install
* Download Python 3.7:
```wget https://www.python.org/ftp/python/3.7.0/Python-3.7.0.tar.xz```
* Unpack python
```tar xvf Python-3.7.0.tar.xz```
* Change directory to Python
```cd /temp/Python37/Python-3.7.0```
* Run configuration script
```./configure```
* Build and install Python:
```sudo make altinstall```