# CARLA-installation (for windows)
## Thanks for [Mr. Wu Sihao](https://github.com/WilliamWu96) and Mr. Li Renjue's contribution to this installation tutorial!  

Knowing that most people are not very familiar with the Linux system, but they want to try to get in touch with the field of autonomous driving, so I will share the method of installing carla under win here, hoping to help some people who want to learn how to get started with carla but don't know how to configure it.  

**I highly recommend you to use python=3.7 if you want to use CARLA 0.9.13 . I have used another version of CARLA 0.9.10 ， but it recommend us to use python=3.6**  

## Install CARLA 
### references:
```
https://github.com/WilliamWu96/Carla_Installation#desktop-version-installation
https://zhuanlan.zhihu.com/p/338927297
https://zhuanlan.zhihu.com/p/390143776
```
### 1.Install CARLA 0.9.13
* https://github.com/carla-simulator/carla/releases 
* chose [Windows] CARLA_0.9.13.zip and download it.
### 2.unzip the file  
### 3.Run CarlaUESTC4.exe
```
conda create -n carla python=3.7
conda activate carla
cd ~/PythonAPI/examples
python automatic_control.py
```
## Issure
* If your terminal show that ```no module named numpy```or```no module named shapely```or```no module named pygame``` , please install them using pip:
```
pip install numpy
pip install shapely
pip install pygame
```
* If your terminal show that  ```no module named carla``` , please:
```
cd ~/PythonAPI/carla/dist
pip install carla-0.9.13-cp37-cp37m-win_amd64.whl
```

## Test
```
conda create -n carla python=3.7
conda activate carla
cd ~/PythonAPI/examples
python automatic_control.py
```
* If you get a movie like this picture , you have fully installed carla environment！！ 
！[CARLA example](https://pic3.zhimg.com/v2-7e4f82bba4c5f6bcf3a96736dfac77c2_b.jpg)
