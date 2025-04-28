# Multi-Scale Boundary Enhanced Pseudo Label Refinement For Semi-Supervised Medical Image Segmentation (ISBI 2025)
by Xingkuo Zhang, Hongjun Wu, Ren Chunxia, Yonggang Zhu, Le Feng, Li Xiao∗
## Installation
  
  This repository is based on PyTorch 1.13.0, CUDA 11.7 and Python 3.9.19. All experiments in our paper were conducted on NVIDIA GeForce RTX 4090 GPU with an identical experimental setting. 
 - `git clone https://github.com/rixyyy/MBPLR.git`  
 - ```conda create -n MBPLR python=3.9.19```  
 - `conda activate MBPLR`  
 - `pip install -r requirements.txt`

## Data
  Data could be got at [LA](https://github.com/yulequan/UA-MT/tree/master/data) and [ACDC](https://github.com/HiLab-git/SSL4MIS/tree/master/data/ACDC).

## Usage
  To train a model,
  - `python ./code/ACDC_BCP_train.py`   
  - `python ./code/LA_BCP_train.py`
    
  To test a model, 
 - `python ./code/test_ACDC.py`    
 - `python ./code/test_LA.py`

## Cite
Xingkuo Zhang, Hongjun Wu, Ren Chunxia, Yonggang Zhu, Le Feng, Li Xiao. Multi-Scale Boundary Enhanced Pseudo Label Refinement For Semi-Supervised Medical Image Segmentation, ISBI 2025.

## Acknowledgements
  Our code is largely based on [BCP](https://github.com/DeepMed-Lab-ECNU/BCP). Thanks for these authors for their valuable work, hope our work can also contribute to related research.
