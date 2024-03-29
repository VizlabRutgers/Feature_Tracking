# Feature_Tracking
Vizlab Feature Tracking program

This program is generally used to detect features. See our [Hybrid eddy detection](https://github.com/VizlabRutgers/Hybrid-Eddy-detection) project for the eddy detection usage in oceanography dataset.

If you use our code, please refer to our paper:  

>Silver, Deborah, and Xin Wang. "Tracking scalar features in unstructured data sets." In Visualization'98. Proceedings, pp. 79-86. IEEE, 1998

Please contact Rutgers Vizlab if you has any problem
https://vizlab.rutgers.edu/

# Installation
This program is a C++ program developed in linux system. We strongly recommend you to compile the code in linux system to avoid some problems.

Validated environment:  
Ubuntu-18.04  
CMake-3.14  
gcc-7.5.0  
Hdf5-1.14.1  
NetCDF-4.3.1  
VTK-8.2.0  
QT-5.14.2  
OpenCV-3.4.13  

Installation Steps:
1. Install Cmake/CMake-gui.(not use the latest one as qt may not support that currently. Version 3.14 verified)
2. Install qt5.
3. Install Hdf5 and Netcdf first, which should not be a problem
4. Install VTK library, I use vtk 8.1/8,2 here
    a)You may meet some problem because of the incompatible version of cmake or VTK library.
    b)You need to change the library path in CMakeList file.
    b)You may need to use apt-file command to find necessary file (for QT)
5. Compile the source code by Cmake(or Do it in QT)

# Usage 
1. Modify the FeatureTrack.Conf to match the path of the dataset
2. Put the FeatureTrack.Conf to folder where you compile the code to.
3. Run the executable file


