# OMERO.matlab

[![Actions Status](https://github.com/ome/omero-matlab/workflows/Gradle/badge.svg)](https://github.com/ome/omero-matlab/actions)

OMERO MATLAB client library

## Usage

Full developer documentation is available from
https://docs.openmicroscopy.org/latest/omero/developers/Matlab.html

## Build from source

The compilation, testing, launch, and delivery of the application are
automated by means of a Gradle (https://gradle.org/) build file.
In order to perform a build, all you need is
a JDK -- version 1.8 or later.
Clone this GitHub repository `git clone https://github.com/ome/omero-matlab.git`.
Go to the directory and enter:

  gradle build

This will compile, build, test and create a distribution bundle.

## Unit tests
 * Run `gradle test`
