# Video-Captioning-Transformer
For transformer understanding

# Video Captioning Transformer Project

This project aims to generate captions for videos using a Transformer model. The project integrates multiple repositories, datasets, and pre-trained models to create a comprehensive video captioning solution. Below is a detailed guide on setting up and using the project.

## Table of Contents

1. [Repositories](#repositories)
2. [Datasets](#datasets)
3. [Pre-trained Models](#pre-trained-models)
4. [Dependencies](#dependencies)
5. [Setup Instructions](#setup-instructions)
6. [Usage](#usage)
7. [Notes](#notes)

## Repositories

### Main Repositories

- **Video-Captioning-Transformer**
  - Repository: [Video-Captioning-Transformer](https://github.com/Kamino666/Video-Captioning-Transformer/tree/master)
  - Description: Transformer model for video captioning.

- **Video-Features**
  - Repository: [Video-Features](https://github.com/Kamino666/video_features/tree/master)
  - Description: Repository for extracting video features.

## Datasets

- **Dataloader**
  - Repository: [MSVD Dataloader](https://github.com/albanie/collaborative-experts/blob/master/misc/datasets/msvd/README.md)
  - Description: Dataloader for MSVD dataset.

- **Baidu Dataset**
  - Link: [Baidu MSRVTT and MSVD Dataset](https://pan.baidu.com/s/1xG5F856VNEjNXD6JcG_4NA?pwd=aupi#list/path=%2Fsharelink3411495947-318895376070041%2FMSRVTT%20and%20MSVD&parentPath=%2Fsharelink3411495947-318895376070041)
  - Password: `aupi`
  - Description: MSRVTT and MSVD datasets available for download.

## Pre-trained Models

- **CLIP4Clip Model**
  - Model File: [clip4clip_msrvtt.pth](https://drive.google.com/file/d/1-aA6Zc-cK38TjC0JPfbttE009Bh3BtG_/view)
  - Paper: [CLIP4Clip Paper](https://arxiv.org/pdf/2104.08860)
  - Repository: [CLIP4Clip Repo](https://github.com/ArrowLuo/CLIP4Clip?tab=readme-ov-file)

- **I3D Model**
  - Repository: [ID3 Model](https://github.com/hassony2/kinetics_i3d_pytorch)
  - Description: Pre-trained I3D model for extracting video features.

## Dependencies

- **mmcv**
  - Installation Guide: [mmcv Installation](https://mmcv.readthedocs.io/en/latest/get_started/installation.html)
  - Note: Follow the instructions carefully to avoid errors.

## Setup Instructions

### 1. Create Conda Environment

```sh
conda create -n video_captioning python=3.8
conda activate video_captioning
