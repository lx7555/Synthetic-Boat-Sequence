# Synthetic-Boat-Sequence


## Abstract

Change detection is an important vision task for water-landing of unmanned aerial vehicles. Inspired by the high-density 
photoreceptors and bilateral filter mechanism, a novel biologically computational method based on the eagle-eye visual
sensitivity and lateral inhibition is proposed for change detection. This method named STabCD, which ensures spatio-temporal
distribution consistency and achieves the goal of foreground acquisition, noise-reducing, background adaptability. Therefore,
the proposed method can respond strongly to object information and suppress noise and wave texture. Then, we present a cloning
method to simulate water-scene and collect a new synthetic dataset (called “Synthetic Boat Sequence”) for the UAVs’ vision
research. Besides, we utilize synthetic dataset and corresponding real dataset to conduct experiments for change detection. The
experimental results indicate that: 1) the STabCD model achieves the best result in complex real or synthetic water-scene; 2) change
detection models of UAVs can be quantitatively analyzed and tested under synthetic scenario challenges.

## Description
Considering that change detection models have to deal with some challenges of water-landing scenes, we generate various synthetic video
sequences, including Basic, Video Noise, Dynamic Background, Night, Shadows, and More Moving Objects. Note:
Each specific sequence is also affected by other challenges, but one challenge is dominant.

## Examples of the real and synthetic dataset
![image](https://github.com/lx7555/Synthetic-Boat-Sequence/blob/main/image/figure1.jpg)

## Download
Synthetic-Boat-Sequence is a water-scene dataset designed to design and evaluate a variety of computer vision models for change detection.
We provide one [.rar] archive per type of data as described below. Our indexes always start from 00001. In the following,

Synthetic-Boat-Sequence_rgb_2021: Each area is simply a folder in the format: The compressed file contains the original image.

[Synthetic-Boat-Sequence_rgb_2021.rar](https://drive.google.com/file/d/1MlkNlYiB2Xlo2ZrIo5OHdiXzw_a2MaCr/view?usp=sharing)

Synthetic-Boat-Sequence_gt_2021: The compressed file contains the ground truth of object detection. The per-pixel segmentation ground truth is encoded as per-frame .png files (standard 8-bit precision per channel).

[Synthetic-Boat-Sequence_gt_2021.rar](https://drive.google.com/file/d/1MlkNlYiB2Xlo2ZrIo5OHdiXzw_a2MaCr/view?usp=sharing)

## Sample images of synthetic dataset
![image](https://github.com/lx7555/Synthetic-Boat-Sequence/blob/main/image/figure2.jpg)

## Examples of change detection results on synthetic challenge sequences using different models
![image](https://github.com/lx7555/Synthetic-Boat-Sequence/blob/main/image/figure3.jpg)

## Citations
PLEASE READ THESE TERMS CAREFULLY BEFORE DOWNLOADING THE SYNTHETIC-BOAT-SEQUENCE DATASET. DOWNLOADING OR USING THE DATASET MEANS YOU ACCEPT THESE TERMS.
