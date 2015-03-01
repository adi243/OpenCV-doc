####4. COMPILE AND INSTALL OPENCV

In your terminal, make sure you are within the OpenCV directory and run the following commands:

`mkdir build`

`cd build`

`cmake -DWITH_QT=ON -DWITH_OPENGL=ON -DFORCE_VTK=ON -DWITH_TBB=ON -DWITH_GDAL=ON -DWITH_XINE=ON -DBUILD_EXAMPLES=ON ..`

`make -j4`

`sudo make install`

configure OpenCV

`sudo ldconfig`

Now, you have installed OpenCV.
