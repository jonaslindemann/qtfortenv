# Installing a Fortran IDE in Windows

This is an attempt in creating an efficient free development environment for Fortran on Windows. The key component of this environment i Qt Creator, which is an advanced development environment for C and C++. However, it can support other languages as Fortran through CMake.

## Creating a directory for the tools

Create a directory, **fortenv**, on the root of a harddrive:

    c:
    cd \
    mkdir fortdev

## Installing Fortran

To get a recent Fortran version on Windows we will use the compiler from the mingw64 project. The compiler is provided as a zip-file. Download the zip-file of the compiler [here](https://sourceforge.net/projects/mingw-w64/files/Toolchains%20targetting%20Win64/Personal%20Builds/mingw-builds/6.2.0/threads-win32/seh/x86_64-6.2.0-release-win32-seh-rt_v5-rev1.7z). Unpack the zip file under the **fortenv** directory **c:\fortdev\mingw64**. The path should preferable not include spaces

## Installing CMake

CMake will be used by Qt Creator as the build system. Download a zip-archive of a recent CMake [here](https://cmake.org/files/v3.7/cmake-3.7.1-win64-x64.zip). Extract the zip-file in the **fortenv** directory and rename the extracted folder to **cmake**.


 