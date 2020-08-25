# VINS-Windows
**Authors**: Bruce Guohua Chen

Migration the VINS-Mono to windows system, the original code base are

# Vins Course
**Authors**: He Yijia, Gao Xiang, Cui huakun, Zhao Song
This project is used for an online course about visual inertial odometry on [shenlanxueyuan](http://www.shenlanxueyuan.com). She is based on the VINS-Mono framework but does not rely on ROS, Ceres, G2o. This code is very basic and aims to demonstrate Eigen-based back-end LM algorithms, sliding window algorithms, robust kernel functions, etc. This code supports for Ubuntu or Mac OS.

I had modified some of the original source code to make it get rid of the dependence on ros and Linux.
I had made a Visual C++ 2013 solution file. you can build the source code with VC2010~2019 easily.

## Prerequisites：
1. pangolin: <https://github.com/stevenlovegrove/Pangolin>
2. opencv
3. Eigen
4. Ceres.  

### Build
Open VinsCourse.sln with Visual Studio 2013~2019 and Build.

### Run
#### . VINs-Mono on Euroc Dataset
```c++
cd bin
VinCourse.bat
```
The EuroC dataset can be found here :https://projects.asl.ethz.ch/datasets/doku.php?id=kmavvisualinertialdatasets#downloads

## Acknowledgements

# Vins Course use [VINS-Mono](https://github.com/HKUST-Aerial-Robotics/VINS-Mono) 
as our base line code. Thanks Dr. Qin Tong, Prof. Shen etc very much.

I used the # Vins Course as bases. thanks to He Yijia, Gao Xiang, Cui huakun, Zhao Song
