# CARLA-installation-windows
## Thanks for [Mr. Wu Sihao](https://github.com/WilliamWu96) and Mr. Li Renjue's contribution to this installation tutorial!  

Knowing that most people are not very familiar with the Linux system, but they want to try to get in touch with the field of autonomous driving, so I will share the method of installing carla under win here, hoping to help some people who want to learn how to get started with carla but don't know how to configure it.  

**I highly recommend you to use python = 3.7 if you want to use CARLA 0.9.13 . I have used another version of CARLA 0.9.10 ， but it recommend us to use python = 3.6**  

## Install CARLA 
### 1.Install CARLA 0.9.13
* https://github.com/carla-simulator/carla/releases 
* chose [Windows] CARLA_0.9.13.zip
### 2.unzip the file  
### 3.Run CarlaUESTC4.exe
```
conda create -n carla python=3.7
conda activate carla
cd ~/PythonAPI/examples
python automatic_control.py
```
