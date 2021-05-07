# Spatial signal processing toolkit (btk2.0)

## Introduction
Open source C++ and Python libraries to facilitate research and development 
for spatial signal processing

Please see http://distantspeechrecognition.sourceforge.net/ for project details.

## Install on ubuntu

**  1. install dependent packages for btk **

```
$ sudo apt install camke
$ sudo apt install swig
$ sudo apt install python
$ sudo apt install python-dev
$ sudo apt install python-numpy
$ sudo apt install python-numpy-dev
$ sudo apt install libgslcblas0 libgsl23 gsl-bin
$ sudo apt install libgsl-dev
$ sudo apt install libsndfile1
$ sudo apt install libsndfile1-dev
$ sudo apt install sndfile-programs
```

** 2. downloading BTK2.0**
```
$ git clone https://github.com/kkumatani/distant_speech_recognition.git
```



**  3. Installing BTK2.0 **

```
$ cd ${your_btk_git_repository_directory}/btk20_src
$ mkdir build
$ cd build
$ cmake -DCMAKE_INSTALL_PREFIX=$HOME/local .. && make install
```

## references docs

https://distantspeechrecognition.sourceforge.io/btk20_documentation/index.html