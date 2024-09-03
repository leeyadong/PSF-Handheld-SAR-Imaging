# Handheld mmWave SAR Imaging with PSF Optiminization

## Code repository for the paper: A High-resolution Handheld millimeter-wave Imaging System with Phase Error Estimation and Compensation, Comms. Eng., 2024.

Authors: [Yadong Li](https://yadongli.com), [Dongheng Zhang](http://staff.ustc.edu.cn/~dongheng/), Ruixu Geng, Zhi Lu, Zhi Wu, Yang Hu, [Qibin Sun](https://ustc-ip-lab.github.io/authors/qibinsun/), and [Yan Chen](https://ustc-ip-lab.github.io/authors/yanchen/)

Affiliation: [Intelligent Perception Lab](https://ustc-ip-lab.github.io/), University of Science and Technology of China. [Paper Link](https://www.nature.com/articles/s44172-023-00156-2)

![System Overview](figures/overview_tmc.jpg)

## Introduction

- Here, we report a portable, affordable, and high-resolution 3D mmWave imaging system by overcoming the destructive motion error of
handheld SAR imaging. This is achieved by formulating the challenging phase error
estimation problem as a tractable point spread function optimization problem. 

- This code repository mainly includes two parts described in the paper:

  - **Signal Processing:** Pre-processing the raw FMCW signal to get the dynamic range angle image (DRAI).  

  - **Deep Learning:** A CNN-LSTM neural network that inputs DRAI and outputs gesture labels. 

- The code can be used to support other similar applications using wireless signals.

<div align=center>
    <img src="https://github.com/leeyadong/Radar-Gesture/blob/e26ca877818ab6af6e8c3ed8f643bcc988fb9d5b/figures/signal_processing.jpg" alt="Signal processing" width="500" />
</div>
<div align=center>
    <img src=https://github.com/leeyadong/Radar-Gesture/blob/e7d5a89eecf1d3567d40f1e1b7a145a49d02c746/figures/neural_network.jpg alt="Neural Network" width="500" />
</div>

## How to Access the Code

The [USTC IP Lab](https://ustc-ip-lab.github.io/) has particular protocols for releasing the code and dataset. To access the code, please sign the [agreement](datasetAgreement.pdf), scan and send it to yadongli@mail.ustc.edu.cn or yadongli@uw.edu. A notification email that includes the code will be sent within three days.

## Installation and Setup

## Run Demo

## Citing
If you find this code useful for your research, please consider citing the following paper:
```
@Article{Li2024,
author={Li, Yadong and Zhang, Dongheng and Geng, Ruixu and Lu, Zhi and Wu, Zhi and Hu, Yang and Sun, Qibin and Chen, Yan},
title={A high-resolution handheld millimeter-wave imaging system with phase error estimation and compensation},
journal={Communications Engineering},
year={2024},
month={Jan},
day={05},
volume={3},
number={1},
pages={4},
issn={2731-3395},
doi={10.1038/s44172-023-00156-2},
url={https://doi.org/10.1038/s44172-023-00156-2}
}
```

