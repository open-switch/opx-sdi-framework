# opx-sdi-framework
This repository contains the components of the implementation of the OPX SDI API for Dell-branded hardware (S6000-ON, S4000-ON, and S3000-ON series switches) based on XML and driver configuration files.

The platform adapation service (PAS) uses the SDI API to access the platform hardware devices.

## Description
The `opx-sdi-framework` is at the core of the SDI implementation. It operates together with the opx-sdi-sys (high-level functionality) and `opx-sdi-device-drivers` (low-level device access).The framework provides a mechanism in which drivers can register themselves and their resources, buses and other facilities that can be used either by other drivers or by the `opx-sdi-sys`. 

There are also a number of hardware BUS utility functions used by the `opx-sdi-device-drivers`.

## Build
See [opx-nas-manifest](https://github.com/open-switch/opx-nas-manifest) for more details on the common build tools. 

### Build dependencies

- `opx-logging` 
- `opx-common-utils`
- `opx-sdi-api`

Dependent packages: libopx-logging1 libopx-logging-dev libopx-common1 libopx-common-dev  opx-sdi-api-dev

(c) Dell 2017
