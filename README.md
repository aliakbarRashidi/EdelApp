**EdelApp**

A Qt application template using the CMake build system, including CTest for unit testing and CPack for installation packages creation.

## Supported platforms

EdelApp has been developed and tested on Mac OS X 10.6.8, Qt 4.8.3 and CMake 2.8.9.

## Usage

### Build
* git clone git@github.com:edeltech/EdelApp.git
* mkdir EdelApp-build
* cd EdelApp-build
* cmake ../EdelApp
* make

### Build and run unit tests
* make check

### Create package
* make package

## Authors

* [Jean-Pierre Gehrig, Edeltech Sarl](http://www.edeltech.ch/about)
* [Samuel Gaist, Edeltech Sarl](http://www.edeltech.ch/about)

## Thank you

* Thanks to [Mike McQuaid](http://mikemcquaid.com/2012/01/04/deploying-qt-applications-with-deployqt4/) for his DeployQt4 module and the [Fabula](https://github.com/mikemcquaid/Fabula/blob/master/CMakeLists.txt) example.

## Changelog

#### 0.1.0 (Jan 7, 2013)

* Initial release

## License

See LICENSE file.