Go
========

Ansible module and role that installs Go (http://golang.org/). This module currently supports Linux and installs the latest Linux stable release for the current host by default.

Module
======

The module is called golang_install. The module accepts only one argument;

name: the release version to download (see http://golang.org/ for possible downloads). The value must be one of the linux binary releases. The module defaults to downloading the latest linux binary distribution for the current host if the argument is not provided.

License
-------

The MIT License (MIT)

Copyright (c) 2014 Davis Abubakr-Sadik Nii Nai

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Author Information
------------------

Davis Abubakr-Sadik Nii Nai
https://github.com/ttousai
@ttousai
