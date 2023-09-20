# Cellular-Segmentation-of-Cultured-Neurons-in-Calcium-Imaging-Experiments
## Overview

This repository contains the code and resources for a research project aimed at analyzing neuronal activity in calcium imaging experiments conducted on cultured neurons outside the brain. The primary objective of this study is to develop and compare different models for cellular segmentation, denoising data, and predicting activity. We employ the U-Net, W-Net, and LinkNet models for training the dataset, along with exploring the impact of denoising techniques on image quality. Additionally, various loss functions will be investigated to assess their impact on the accuracy of cellular segmentation. The overarching hypothesis is that denoising images will enhance the accuracy of cellular segmentation. Furthermore, the use of the W-Net model, an improved version of the U-Net, is expected to further enhance the segmentation process. We also explore the potential of other models such as LinkNet.

## Project Structure

The repository is organized as follows:

- **`data/`**: This directory contains the dataset used for training and evaluation. We have used the "Autosegmentation of cultured neurons" dataset, which can be accessed [here](http://www.cellimagelibrary.org/images/CCDB_6843). Please download the dataset from the provided link and follow any usage guidelines or licenses associated with it.
