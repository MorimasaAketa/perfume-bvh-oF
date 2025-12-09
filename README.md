perfume-bvh-oF
======================

This is a Perfume-dev #001's fork.

I updated project settings and modified some code for 0.12.1 in XCode 14.3 and macOS 13.4, or in Windows 11 and Visual Studio 2022.	

As all projects contains VS2022 project setting files, you can build and run on windows immediately.

Each project contains data files in bin/data.

# Basic setup steps for macOS

1. Install XCode.
2. Download openFrameworks 0.12.0 or later from [official site](http://openframeworks.cc/download/) .
3. Clone or "download zip" and extract this repository to folder `of_0.12.1_osx_release/apps/`. There should be the folder  `of_0.12.1_osx_release/apps/perfume-bvh-oF`.
4. Copy ofx* folders ( ofxBvh, ofxMarchingCubes, ofxSTL ) from `of_0.12.1_osx_release/apps/perfume-bvh-oF` to `of_0.12.1_osx_release/addons/` .
5. Open `example-bvh/example-bvh.xcodeproj` and build to run.

# Basic setup steps for Windows/Visual Studio 2022

1. Install Visual Studio Community 2022 with C++ component.
2. Download openFrameworks 0.12.0 or later for Visual Studio 2019 from [official site](http://openframeworks.cc/download/) .
3. Clone or "download zip" and extract this repository to folder `of_0.12.1_vs_64_release/apps/`. There should be the folder  `of_0.12.1_vs_64_release/apps/perfume-bvh-oF`.
4. Copy ofx* folders ( ofxBvh, ofxMarchingCubes, ofxSTL ) from `of_0.12.1_vs_64_release/apps/perfume-bvh-oF/` to `of_0.12.1_vs_64_release/addons/` .
5. Open `example-bvh/example-bvh.sln` . and push 'Local Windows Debugger' button.


