# buildOpenCVUbuntu

These scripts build OpenCV version 3.3 for Ubuntu 16.04 and Python 3



OpenCV is a rich environment which can be configured in many different ways. You should configure OpenCV for your needs, by modifying the build file "buildOpenCV.sh". Note that selecting different options in OpenCV may also have additional library requirements which are not included in these scripts.

To run the the build file

$ cd buildOpenCVUbuntu

$ ./buildOpenCV.sh

The build system has been known at times to have issues. It's worth doing a sanity check after the build is complete:

$ cd $HOME/opencv/build

$ make

This should ensure that everything has been built.

After this, you can install the new build:

$ cd $HOME/opencv/build

$ sudo make install



## Release Notes
November 2017
* Ubuntu 16.04
* Python 3 and 2.7
* OpenCV 3.3
* GStreamer support added to build script 



## License
MIT License

Copyright (c) 2017 

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
 
