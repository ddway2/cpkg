[![Build Status](https://travis-ci.org/chybz/cpkg.svg?branch=master)](https://travis-ci.org/chybz/cpkg)

cpkg
======
cpkg is a packaging software to simplify specific package creation (MacOS and Linux Debian)

## Install

### On Debian
Install dependencies
```
sudo apt-get install cmake \
    build-essential \
    debhelper \
    equivs \
    apt-file \
    tinycdb \
    pkg-config \
    rsync \
    git \
    lsb-release \
    lintian \
    sudo \
    apt-utils \
    g++ \
    make \
    binutils \
    autoconf \
    automake \
    autotools-dev \
    libtool \
    zlib1g-dev \
    devscripts \
    dh-autoreconf \
    dh-systemd
```
Git clone project, build and install it !
```
git clone https://github.com/ddway2/cpkg.git
cd cpkg
./cpkg/bin/cpkg build
./cpkg/bin/cpkg package -P
sudo dpkg -i *.deb
```
Let's go :)
## Tree file structure of cpkg project
TODO
