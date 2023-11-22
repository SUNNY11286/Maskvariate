# Maskvariate: Optimizing Medical Diagnostic Image Segmentation

ALL UPDATES ARE COMING SOON......

## Introduction
The Maskvariate introduces a novel approach for contrastive loss along with it combines contrastive loss with the Dice loss to improve spatial accuracy and feature representation in medical image segmentation, particularly in scenarios with limited annotations, leading to increased precision in the analysis of medical images.

### The architecture of the UNet model integrated with our Maskvariate loss function
<img src="https://github.com/SUNNY11286/Maskvariate/blob/main/UnetD2.png" alt="Flowchart" />

## Getting Started

### Prerequisites
- Python 3.12.0
- TensorFlow 2.12.0

### Installation
Clone the repository and install the dependencies:

```bash
git clone https://github.com/SUNNY11286/Maskvariate.git
```
** install all compatible version of other libraries with given prereuisites

## Datasets

We utilized high-quality multi-modal MRI scans from the [BraTs 2016](https://www.smir.ch/BRATS/Start2016) and [BraTs 2017](https://www.med.upenn.edu/sbia/brats2017/data.html) datasets, including 274 and 285 patients, respectively. Emphasizing the FLAIR modality, our dataset encompasses diverse tumor shapes, sizes, and locations. Additionally, to assess the generalizability of our approach, we integrated the [AbdomenCT-1K](https://github.com/JunMa11/AbdomenCT-1K) dataset, comprising over a thousand abdominal CT scans, into our study.

