# Handheld mmWave SAR Imaging with PSF Optimization

## Code repository for the paper: A High-resolution Handheld millimeter-wave Imaging System with Phase Error Estimation and Compensation, Comms. Eng., 2024.

Authors: [Yadong Li](https://yadongli.com), [Dongheng Zhang](http://staff.ustc.edu.cn/~dongheng/), Ruixu Geng, Zhi Lu, Zhi Wu, Yang Hu, [Qibin Sun](https://ustc-ip-lab.github.io/authors/qibinsun/), and [Yan Chen](https://ustc-ip-lab.github.io/authors/yanchen/)

Affiliation: [Intelligent Perception Lab](https://ustc-ip-lab.github.io/), University of Science and Technology of China. [Paper Link](https://www.nature.com/articles/s44172-023-00156-2)

![System Overview](https://github.com/leeyadong/PSF-Handheld-SAR-Imaging/blob/9652f1c63327bcb66d3d40a90ea3d6ed4ac8ea6d/figures/overview_ce.jpg)

## Introduction

- Here, we report a portable, affordable, and high-resolution 3D mmWave imaging system by overcoming the destructive motion error of
handheld SAR imaging. This is achieved by formulating the challenging phase error
estimation problem as a tractable point spread function (PSF) optimization problem. 

- This repository includes code for pre-processing, phase error estimation with PSF optimization, and Range Migration Algorithm (RMA).
  
- This repository provides sample data for generating the following result shown in the paper.
  
<div align=center>
    <img src="https://github.com/leeyadong/PSF-Handheld-SAR-Imaging/blob/7a2f7b644c0e54b31dc67504a8a1c4e20813dc94/figures/results_ce.jpg" alt="results" width="600" />
</div>


## How to Access the Code

The [USTC IP Lab](https://ustc-ip-lab.github.io/) has particular protocols for releasing the code and dataset. To access the code, please sign the [code agreement](IPLabCodeAgreementPSF.pdf), scan and send it to yadongli@mail.ustc.edu.cn or yadongli@uw.edu. A notification email that includes the code will be sent within three days.

## Run Demo
```
pip install matplotlib hdf5storage numpy scipy
```
set the file path in demo.py
```
python demo.py
```

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

