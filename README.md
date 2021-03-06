Automatically generate multi-challenge synthetic video sequences for change detection, named “Synthetic Boat Sequence (SBS)”


# Synthetic-Boat-Sequence


## Abstract

Change detection (CD) is an important vision task for landing unmanned aerial vehicles on water. 
High-density photoreceptors and lateral inhibition mechanisms have inspired a novel biologic computational 
method based on structure and properties in eagle eyes as proposed for change detection. 
We call this method “STabCD,” which ensures spatiotemporal distribution consistency to achieve 
foreground acquisition, noise reduction, and background adaptability. Therefore, our proposed model 
responds strongly to object information and suppresses noise and wave textures. Then, we present a
cloning method to simulate water scenes and collect a new synthetic dataset (called “Synthetic Boat Sequence”) 
for UAV vision research. Besides, we utilize synthetic datasets and corresponding real datasets to conduct 
change detection experiments. The experimental results indicate that: 1) the STabCD model achieves the 
best results inreal or synthetic water landing scenes; and 2) change detection models for UAVs can
be quantitatively analyzed and tested under challenging synthetic scenarios.

## Description
Considering that change detection models have to deal with some challenges of water-landing scenes, we generate various synthetic video
sequences, including Basic, Video Noise, Dynamic Background, Night, Shadows, and More Moving Objects. Note:
Each specific sequence is also affected by other challenges, but one challenge is dominant.

## Examples of the real and synthetic dataset
![image](https://github.com/lx7555/Synthetic-Boat-Sequence/blob/main/image/figure1.jpg)

## Download
Synthetic-Boat-Sequence is a water-scene dataset designed to design and evaluate a variety of computer vision models for change detection.
We provide one [.rar] archive per type of data as described below. Our indexes always start from 000001. In the following,

Synthetic-Boat-Sequence_rgb_2021: Each area is simply a folder in the format: The compressed file contains the original image.

[Synthetic-Boat-Sequence_rgb_2021.rar](https://drive.google.com/file/d/1MlkNlYiB2Xlo2ZrIo5OHdiXzw_a2MaCr/view?usp=sharing)

Synthetic-Boat-Sequence_gt_2021: The compressed file contains the ground truth of object detection. The per-pixel segmentation ground truth is encoded as per-frame .png files (standard 8-bit precision per channel).

[Synthetic-Boat-Sequence_gt_2021.rar](https://drive.google.com/file/d/1MlkNlYiB2Xlo2ZrIo5OHdiXzw_a2MaCr/view?usp=sharing)

## Sample images of synthetic dataset
![image](https://github.com/lx7555/Synthetic-Boat-Sequence/blob/main/image/figure2.jpg)

## Examples of change detection results on synthetic challenge sequences using different models
![image](https://github.com/lx7555/Synthetic-Boat-Sequence/blob/main/image/figure3.jpg)

## Citations
All rights of the Synthetic-Boat-Sequence Dataset are reversed by the Peng Cheng Laboratory. It is free for academic research, and your cooperation with us is appreciated. Feel free to contact us if you have any questions.

If the Synthetic-Boat-Sequence Dataset is used in your research, please cite the following papers:

1. Xuan Li, Kunfeng Wang, Yonglin Tian, Lan Yan, Fang Deng, Fei-Yue Wang, "The ParallelEye Dataset: A Large Collection of Virtual Images for Traffic Vision Research," 
IEEE Transactions on Intelligent Transportation Systems, 2018, 20(6): 2072-2084. [Link](https://ieeexplore.ieee.org/document/8451919/)

2. Xuan Li, Yutong Wang, Lan Yan, Kunfeng Wang, Fang Deng, Fei-Yue Wang, "ParallelEye-CS: A New Dataset of Synthetic Images for Testing the Visual Intelligence of Intelligent Vehicles," IEEE Transactions on Vehicular Technology, 2019, 68(10): 9619-9631. [Link](https://ieeexplore.ieee.org/abstract/document/8807212)

3. Xuan Li, Kunfeng Wang, Xianfeng Gu, Fang Deng, Fei-Yue Wang, "ParallelEye Pipeline: An Effective Method to Synthesize Images for Improving the Visual
Intelligence of Intelligent Vehicles," IEEE Transactions on Systems Man Cybernetics-Systems.(accepted) 


