# seekthermal_ros
ROS node for Seek thermal imaging devices

## Depedencies
[libseekthermal](https://github.com/RO-BIT-Intelligence-Robot-Team/libseekthermal.git)
[ReMake](https://github.com/RO-BIT-Intelligence-Robot-Team/remake.git)
 -> original source from [ethz asl](https://github.com/ethz-asl)

## Installation 
### Installing build dependencies
```
sudo apt-get install debhelper cmake groff doxygen pkg-config libudev-dev
```
### Dependencies build
#### ReMake
```
git clone https://github.com/RO-BIT-Intelligence-Robot-Team/remake.git
cd remake
mkdir build
cd build 
cmake ..
sudo make install
```

#### libseekthermal
```
git clone https://github.com/RO-BIT-Intelligence-Robot-Team/libseekthermal.git
cd remake
mkdir build
cd build 
cmake ..
sudo make install
```

### ROS package build
```
cd ~/catkin_ws/src
git clone https://github.com/RO-BIT-Intelligence-Robot-Team/seekthermal_ros.git
cd ~/catkin_ws
catkin_make
```
