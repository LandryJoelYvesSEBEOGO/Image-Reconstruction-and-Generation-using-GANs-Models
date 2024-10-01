# Generative Adversarial Networks Projects

This repository contains three advanced projects focusing on Generative Adversarial Networks (GANs) for various image processing tasks. Each project explores different GAN architectures to enhance or generate high-quality images. 

## Table of Contents

- [Projects Overview](#projects-overview)
- [Project 1: Progressive Growing GAN (ProGAN)](#project-1-progressive-growing-gan-progan)
- [Project 2: Super-Resolution GAN (SRGAN)](#project-2-super-resolution-gan-srgan)
- [Project 3: Enhanced Super-Resolution GAN (ESRGAN)](#project-3-enhanced-super-resolution-gan-esrgan)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [References](#references)

## Projects Overview

1. **Progressive Growing GAN (ProGAN)**: This project involves generating high-resolution images from low-dimensional noise vectors using progressive training.
2. **Super-Resolution GAN (SRGAN)**: SRGAN aims to enhance the resolution of images, converting low-resolution images into high-resolution counterparts.
3. **Enhanced Super-Resolution GAN (ESRGAN)**: An improvement over SRGAN, ESRGAN achieves superior performance in image super-resolution by incorporating advanced architectural enhancements.

---

## Project 1: Progressive Growing GAN (ProGAN)

### Overview
ProGAN employs a progressive training method to generate high-resolution images. The model starts training with small image resolutions and gradually increases the size, improving the stability and quality of generated images.

### Key Features
- Progressive training for stable high-resolution image generation.
- Utilizes adaptive learning rates for different image scales.
- Capable of generating diverse and realistic images.

### Files
- `ProGAN.ipynb`: Jupyter Notebook with the full implementation and training process.
  
---

## Project 2: Super-Resolution GAN (SRGAN)

### Overview
SRGAN is designed to upscale low-resolution images into high-resolution images using a GAN-based architecture. It combines a generator and discriminator network, with the generator attempting to create photo-realistic high-resolution images.

### Key Features
- Uses a perceptual loss function for better image quality.
- Incorporates residual blocks for efficient feature extraction.
- Capable of handling real-world low-resolution images.

### Files
- `SRGANN.ipynb`: Jupyter Notebook containing the SRGAN implementation and experiments.

---

## Project 3: Enhanced Super-Resolution GAN (ESRGAN)

### Overview
ESRGAN builds upon SRGAN to deliver even more realistic and high-quality super-resolution images. It replaces conventional residual blocks with Residual-in-Residual Dense Blocks (RRDB) and employs a Relativistic Average Discriminator (RaD) for improved adversarial training.

### Key Features
- Advanced residual blocks (RRDB) for enhanced image reconstruction.
- Relativistic Discriminator to generate sharper and more detailed images.
- Outperforms SRGAN in producing photo-realistic images.

### Files
- `ESRGANN.ipynb`: Jupyter Notebook with the ESRGAN implementation and enhancements.

---

## Installation

To set up the environment for these projects, follow these steps:

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/GAN-Projects.git
    cd GAN-Projects
    ```

*Note*: The `requirements.txt` file should contain dependencies such as `torch`, `tensorflow`, `numpy`, `matplotlib`, etc.

---

## Usage

You can run each project by opening the corresponding Jupyter Notebook:

1. **ProGAN**: 
   ```bash
   jupyter notebook ProGAN.ipynb
