# Custom Diffusers library for STDiff

This is a custom modified Diffusers for the AAAI24 paper: [STDiff: Spatio-temporal Diffusion for Continuous Stochastic Video Prediction](https://arxiv.org/abs/2312.06486)

## Description

Compared with the official Diffusers library, the following modifications are made:

- Enable [SPADE](https://github.com/NVlabs/SPADE)-manner motion conditioning for the ResNetBlock of unet_2d_blocks.
- Implement a custom UNet2D model with motion conditioning. see src/diffusers/models/unet_2d_motion_cond.py

## Installation
Clone the library
```bash
git clone https://github.com/XiYe20/CustomDiffusers.git
```
Installation
```bash
cd CustomDiffusers
pip install -e .