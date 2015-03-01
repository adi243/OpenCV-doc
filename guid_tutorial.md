##Install OpenCV on Ubuntu or Debian

This tutorial has been tested on Ubuntu 14.04 LTS with OpenCV 3.0.0 alpha. If you have successfully installed OpenCV 

####1. KEEP UBUNTU OR DEBIAN UP TO DATE
Open your terminal and execute:

`sudo apt-get update && sudo apt-get upgrade && sudo apt-get dist-upgrade && sudo apt-get autoremove`

###2.install the dependencies:

####Build tools:

`sudo apt-get install build-essential cmake`

####GUI:

`sudo apt-get install qt5-default libvtk6-dev`

####Media I/O:

`sudo apt-get install zlib1g-dev libjpeg-dev libwebp-dev libpng-dev libtiff5-dev libjasper-dev libopenexr-dev libgdal-dev`

####Video I/O:

`sudo apt-get install libdc1394-22-dev libavcodec-dev libavformat-dev libswscale-dev libtheora-dev libvorbis-dev libxvidcore-dev libx264-dev yasm libfaac-dev libopencore-amrnb-dev libopencore-amrwb-dev libv4l-dev libxine-dev`

####Parallelism and linear algebra libraries:

`sudo apt-get install libtbb-dev libeigen3-dev`

####Python:

`sudo apt-get install python-dev python-tk python-numpy python3-dev python3-tk python3-numpy`

####Java:

`sudo apt-get install ant default-jdk`

####Documentation: (Optional)

`sudo apt-get install doxygen sphinx-common texlive-latex-extra`

####3. DOWNLOAD AND DECOMPRESS OPENCV
Enter the OpenCV (official website) and download the latest version for Linux. Then decompress the downloaded file.

######[Next]
######[Previous]



