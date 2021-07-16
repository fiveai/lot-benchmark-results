# LOT Benchmarks Results

This repository contains supplementary material for the paper _Smart Pointers and Shared Memory Synchronisation for 
Efficient Inter-process Communication in ROS on an Autonomous Vehicle_.

The full resolution pictures used throughout the paper can be found under the [figures](./figures) folder, whilst the 
underlying raw data is stored under the [data/core2](./data/core2) folder. The C++ source code is stored in [ros_comm](https://github.com/fiveai/ros_comm) repository on [lot branch](https://github.com/fiveai/ros_comm/tree/lot).

The configuration of each use case has been embedded into the name of the file, e.g. 
`sub1_shm_1p1s_same_docker_1024x1024_pool0_Hz30_count2000.txt` designates a test case where the SHM transport has been 
used to broadcast 2000 1MB images from one publisher to one subscriber at 30Hz without relying on memory pools.

Copyright(c) Five AI Limited 2021. 

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
