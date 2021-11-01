# Room_Capacity_Tracker
This repository is a code for an application used to detect and monitor a room capacity.

## Introduction
The core of the application is **JetPack 4.5**, which is a software package for Jetson that includes CUDA, cuDNN, TensorRT, DeepStream, OpenCV and many other libraries. Having all of these componants and libraries together helps building end-to-end accelerated AI solutions.

The algorithm is based on a CUDA (or Compute Unified Device Architecture) impelmentation, which is a parallel computing platform and application programming interface (API) that allows software to use certain types of graphics processing unit (GPU) for general purpose processing.
The tracking system is based heavily on ***SORT***, which is realtime tracking algorithm for 2D multiple object tracking in video sequences

## Hardware Requirements
1. NVIDIA® Jetson Nano™ Developer Kit 
2. Pi camera v2 (but any other camera compatible with the jetson Nano would also work fine)


## Downloading
1. Clone the following repository from github
 ```
 $ git clone https://github.com/JardinRyu/Room_Capacity_Tracker
 $ cd Room_Capacity_Tracker
 ```
2. Download Dependencies
```
$ ./Installation.sh
$ ./Dependencies_2.sh
$ ./Dependencies_3.sh

```
## Employment
```
$ python3 Pi_Camera.py
```

## Refrences 
- [Jetson_Nano_People_Counting](https://github.com/JardinRyu/Jetson_Nano_People_Counting)
- [SORT](https://github.com/abewley/sort)
- [tensorrt_demos](https://github.com/jkjung-avt/tensorrt_demos)

