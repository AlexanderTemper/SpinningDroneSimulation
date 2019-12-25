
## Ros melodic
http://wiki.ros.org/melodic/Installation/Ubuntu
## MavRos
https://github.com/mavlink/mavros/tree/master/mavros#installation

## Px4
```
git submodule add https://github.com/PX4/Firmware.git 
cd px4-firmware
git checkout v1.9.2
git submodule update --init --recursive

no_sim=1 make px4_sitl_default gazebo
```





