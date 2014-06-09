# Aerofoil-Debs

#### Table of Contents

1. [Overview](#overview)
2. [Module Description - What the module does and why it is useful](#module-description)
3. [Setup - The basics of getting started with Aerofoil-Debs](#setup)
    * [What Aerofoil-Debs affects](#list-of-packages)
    * [Beginning with Aerofoil-Debs](#beginning-with-aerofoil-Debs)
4. [Usage - Configuration options and additional functionality](#usage)
5. [Reference - An under-the-hood peek at what the module is doing and how](#reference)
6. [Limitations - OS compatibility, etc.](#limitations)
7. [Development - Guide for contributing to the module](#development)
8. [Development - List of Contributors](#contributors)

## Overview

Source control files for creating Debian metapackages to be used with Aerofoil.

## Module Description

This repo contains several metapackages for setting up an Aerofoil system.

Each package will install a set of applications, and can be selectively
installed based upon need.

## Setup

### List of Packages

* af-audio: Installs audio packages
* af-cad: Installs Computer Aided Drafting and Design applications
* af-cpp: Installs C++ development tools
* af-desktop: Installs the default Aerofoil window manager, i3WM
* af-graphics: Installs artwork packages for Aerofoil
* af-java: Installs Java development tools
* af-utils: Installs desktop utilities for Aerofoil.

### Beginning with Aerofoil-Debs

Setup is easy. Simply install the .deb packages on your system.

## Usage

Put the classes, types, and resources for customizing, configuring, and doing
the fancy stuff with your module here.

## Reference
Metapackages are created based upon [Ubuntu's
documentation.](https://help.ubuntu.com/community/MetaPackages)

Many scripts are based upon [Crunchbang Linux](http://crunchbang.org/)'s
configurations.

## Limitations

This repo requires a Debian-based OS.
Ubuntu, Debian, Crunchbang linux are all supported out of the box.

## Development

All development is done in a feature branch, so that the master branch is kept
as stable as possible.

If you would like to contribute, please feel free to refer to our Contributing
documentation.

## Contributors

* Flynn Milligan - Creator
* Tom Swartz - Package Management, Documentation

