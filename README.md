# Semantic SLAM for Mobile Robots in Dynamic Environments

This repository contains the open-source code for the paper _"Semantic SLAM for mobile robots in dynamic environments based on visual camera sensors"_ by Qi Zhang and Changdi Li, published in the Measurement Science and Technology journal in 2023. You can access the original paper [here](https://dx.doi.org/10.1088/1361-6501/acd1a4).

## Abstract

Visual simultaneous localization and mapping (vSLAM) is inherently constrained by the static world assumption, which renders success in the presence of dynamic objects rather challenging. In our work, we propose a real-time semantic vSLAM system designed for both indoor and outdoor dynamic environments.

## Key Features
- Based on pretain-model of YOLOX
- Real-time semantic vSLAM system suitable for both indoor and outdoor environments.
- Object detection across 80 categories.
- Motion consistency checks for identifying outliers.
- Specialized handling of human and non-human objects.
- Algorithms for assessing human postures (seated or standing).
- Automatic threshold adjustments for non-human objects.
- Tested on TUM, Bonn RGB-D, and KITTI datasets.

## Dataset and Evaluation

Our system is evaluated on the indoor TUM and Bonn RGB-D datasets, with further testing conducted on the outdoor stereo KITTI dataset. The results reveal that our SLAM outperforms most SLAM systems in dynamic environments. We also tested our system in real-world environments with a monocular camera, demonstrating its robustness and universality across diverse settings.

## Citation

If you use this code in your research, please cite our paper:
> @article{Zhang_2023,  
  doi = {10.1088/1361-6501/acd1a4},  
  url = {https://dx.doi.org/10.1088/1361-6501/acd1a4},  
  year = {2023},  
  month = {may},  
  publisher = {IOP Publishing},  
  volume = {34},  
  number = {8},  
  pages = {085202},  
  author = {Qi Zhang and Changdi Li},  
  title = {Semantic SLAM for mobile robots in dynamic environments based on visual camera sensors},  
  journal = {Measurement Science and Technology},  
  }
