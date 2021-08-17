# Comparison of Depth Cameras: Kinect V2 and Zed 2i

#### Body Tracking in SoSe 2021
@jana2308walter
@a-spork


## Goals

In this project the two depth cameras Microsoft Kinect V2 and Stereolabs Zed 2i are compared in terms of application areas and possible uses. 
The aim is to identify the advantages and disadvantages of the two systems and to be able to make recommendations for different areas of application. 
A special focus is on object tracking in space and the detection of persons and their movements or body posture. 
For this purpose we mainly use the depth cameras and the skeleton view.


## Kinect V2

### Installation requirements
- Supported Operating System
	- Embedded 8 Standard, Windows 8, Windows 8.1 or later
* Recommended Hardware Configuration
	- 64-bit (x64) processor
	- 4 GB Memory (or more)
	- Physical dual-core 3.1 GHz (2 logical cores per physical) or faster processor
	- USB 3.0 controller dedicated to the Kinect for Windows v2 sensor
	- DX11 capable graphics adapter
	- A Microsoft Kinect v2 sensor, which includes a power hub and USB cabling

- Software Requirements
	- Visual Studio 2012 or Visual Studio 2013

### Installation instructions
You can find the Kinect for Windows SDK 2.0 here: https://www.microsoft.com/en-us/download/details.aspx?id=44561

![BILD VISUAL STUDIO MIT PASSENDEM CODE](https://github.com/jana2308walter/Bodytracking_Spork_Walter/blob/main/Images/Code_Kinect.PNG?raw=true)

### Use instructions

In this pictures you can see the RGB, the skeleton view and the depth map with the Kinect V2:


![BILD RGB, SKELETT, TIEFENKAMERA](https://github.com/jana2308walter/Bodytracking_Spork_Walter/blob/main/Images/Image_KinectV2.PNG?raw=true)

In this picture you can see the the RGB view and the object detection on the map with the Kinect V2:


![BILD RGB, OBJECT DETECTION](https://github.com/jana2308walter/Bodytracking_Spork_Walter/blob/main/Images/Trajectory_Kinect.PNG?raw=true)



## ZED 2i

### Installation requirements

- Python (We used Python 3.8)
- Anaconda
- Microsoft Visual Studio Code (It has to be executable with Anaconda)
- Cuda
- Zed SDK
- Packages:
    - cython
    - numpy
    - opencv
    - py-opencv
    - pyopengl
    - pyzed
    - zlib


### Installation instructions

For the use of this camera it is helpful to use Visual Studio Code. The camera is compatible with C#, C++ and Python, so we decided to use Python for this course.
Also we suggest to use Anaconda to install all the needed packages and an individual development environment.
If you want to use our scripts you have to install the needed packages first (Described above). After you installed the packages correctly, the Scripts should run and
if your camera is connected to your computer, you can start to work.


![BILD VISUAL STUDIO MIT PASSENDEM CODE](https://github.com/jana2308walter/Bodytracking_Spork_Walter/blob/main/Images/VS_Code.JPG?raw=true)


### Use instructions

With the scripts from this repository you can activate the various views of the Zed 2i:
    - Make_interface: Here you can see the Depth Map and a RGB view
    - Body_tracking: Here you can see the Skeleton View and a RGB view with the similar skeletons on the persons
    - Birds eye viewer: Here you can see a function used for person detection in a room seen on a map, in a pointcloud and in RGB
    
In this pictures you can see the RGB, the skeleton view and the depth map with the Zed 2i:

![BILD RGB, SKELETT, TIEFENKAMERA](https://github.com/jana2308walter/Bodytracking_Spork_Walter/blob/main/Images/Trajectory_Kinect.PNG?raw=true)


In this picture you can see the pointcloud, the RGB view and the object detection on the map with the Zed 2i:

![BILD POINTCLOUD, RGB, OBJECT DETECTION](https://github.com/jana2308walter/Bodytracking_Spork_Walter/blob/main/Images/Trajectory_Zed2i.PNG?raw=true)
