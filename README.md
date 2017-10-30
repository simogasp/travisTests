# testing travis
Just a collection to easily test travis features

By default trusty sports:

* gcc 4.8.4
* clang 3.9.0
* cmake 3.2.2

Options for gcc are:

* gcc-5 g++5 (5.4.1) with ubuntu-toolchain-r-test

Options for clang are:

* 3.8 using sources: llvm-toolchain-trusty and clang-3.8
* 3.9 using sources: llvm-toolchain-trusty-3.9 and clang-3.9
* 4.8 using sources: llvm-toolchain-trusty-4.0 and clang-4.8


Other sources are available here https://github.com/travis-ci/apt-source-whitelist/blob/master/ubuntu.json

[![Build Status](https://travis-ci.org/simogasp/travisTests.svg?branch=trustyMatrix)](https://travis-ci.org/simogasp/travisTests)
