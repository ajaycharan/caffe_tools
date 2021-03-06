Summary
==============
A small wrapper library to extract activations of deep neural networks using the popular Caffe toolbox.

Requirements / Dependencies
==============
* A compiled version of Caffe, tested with 2016-08-20 (hash 14643685a4693df0ea8364f468821 )
* The source code was developed in Matlab 8.2

Installation
==============
* setup required paths and 3rd-party dependencies via `initWorkspaceCaffeTools.m` (if caffe is not found on your system, a possible code mirror is suggested)

Common errors
==============
* Do not forget to add caffe's dependencies (e.g., cuda, gflgs, protobuf, leveldb, lmdb, and mkl) to your LD_LIBRARY_PATH and PATH variable before starting Matlab

COPYRIGHT
=========
This software is licensed under the non-commercial license [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/). For usage beyond the scope of this license, please contact [Alex Freytag](http://www.inf-cv.uni-jena.de/freytag.html).

