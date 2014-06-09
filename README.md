Aerofoil Debian packages
---

0. [overview](#overview)
0. [getting started with Aerofoil Debian packages](#getting-started)
0. [list of packages](#packages)
0. [system requirements](#requirements)
0. [development reference](#reference)
0. [contributors](#contributors)

## Overview

This repository contains several metapackages (and their contents) for setting up an Aerofoil system. Each package installs a set of applications and can be selectively installed based upon need.

## list of packages

* af-audio: audio packages
* af-cad: Computer Aided Drafting and Design packages
* af-cpp: C++ development tools
* af-desktop: i3 and other elements of the Aerofoil desktop environment
* af-graphics: photography and graphic design packages
* af-java: Java development tools
* af-utils: common utilities

## system requirements

Debian packages may only be installed on APT-based distributions (Debian, Aerofoil, Ubuntu, CrunchBang, et al.).

## development reference

All development is done in feature branches so that the master branch is kept as stable as possible. If you would like to contribute, please refer to [the relevant documentation]().

Metapackages are created based upon [Ubuntu's documentation](https://help.ubuntu.com/community/MetaPackages).

Many configurations and defaults are based upon those of [Crunchbang Linux](http://crunchbang.org/).

## Contributors

| Name           |  Duty                                 |
|----------------|---------------------------------------|
| Flynn Milligan | creator                               |
| Tom Swartz     | package maintenance and documentation |
