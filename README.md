# Backend Repository

[![Build Status](https://travis-ci.org/Studio-Link-v2/backend.svg?branch=master)](https://travis-ci.org/Studio-Link-v2/backend)

This repository contains the studio link - baresip modules and build environment

## Build Requirements

- OpenSSL
- LV2 (optional)

## Build on Linux

```export TRAVIS_OS_NAME="linux"; build/build.sh```

## Build on OSX

```export TRAVIS_OS_NAME="osx"; build/build.sh```

## Build for Windows on Archlinux

```export BUILD_OS="windows64"; build/build_windows.sh```
