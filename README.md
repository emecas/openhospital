# Open Hospital [![Build Status](https://travis-ci.org/informatici/openhospital.svg?branch=master)](https://travis-ci.org/informatici/openhospital)

This is the ***release*** repository for the [Open Hospital][openhospital]'s project. It is not meant for developers but only to publish releases packages called *portable* (means all-in-one, with embedded MySQL Server and JVM)   
[Here][releases] you can download the portable distribution of Open Hospital.

### For Developers (how to contribute)
Please read the [CONTRIBUTING.md](https://github.com/informatici/openhospital/blob/master/CONTRIBUTING.md) file

## How to create Open Hospital portable

To create the Open Hospital portable distributions,
make sure to have installed the following dependencies on a Linux machine:
_JDK 6+, Maven, asciidoctor-pdf, docker-compose, MySQL client, zip._
 
Then follow these simple steps:

 1. Clone this repository and initialize the submodules:

        git clone --recurse-submodules https://github.com/informatici/openhospital

 2. Run the script that compiles the projects *core* and *gui*, and assembles the portable distributions:

        cd openhospital
        ./build_poh.sh


 [openhospital]: https://www.open-hospital.org/
 [releases]: https://github.com/informatici/openhospital/releases
