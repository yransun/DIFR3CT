# DIFR3CT: Latent Diffusion for Probabilistic 3D CT Reconstruction from Few Planar X-Rays

This is the official pytorch implementation of the deep leraning model DIFR3CT for 3D CT reconstruction from few planar X-rays using latent diffusion model. 


## Code release
The code will be ready before Nov. 30, 2024.


## Abstract
Computed Tomography (CT) scans are the standard-of-care for the visualization and diagnosis of many clinical ailments, and are needed for the treatment planning of external beam radiotherapy. Unfortunately, the availability of CT scanners in low- and mid-resource settings is highly variable. Planar x-ray radiography units, in comparison, are far more prevalent, but can only provide limited 2D observations of the 3D anatomy. In this work we propose DIFR3CT, a 3D latent diffusion model, that can generate a distribution of plausible CT volumes from one or few ($<$ 10)  planar x-ray observations. DIFR3CT works by fusing 2D features from each x-ray into a joint 3D space, and performing diffusion conditioned on these fused features in a low-dimensional latent space. We conduct extensive experiments demonstrating that DIFR3CT is better than recent sparse CT reconstruction baselines in terms of standard pixel-level (PSNR, SSIM) on both the public LIDC and in-house post-mastectomy CT datasets. We also show that DIFR3CT supports uncertainty quantification via Monte Carlo sampling, which provides an opportunity to measure reconstruction reliability. Finally, we perform a preliminary pilot study evaluating DIFR3CT for automated breast radiotherapy contouring and planning -- and demonstrate promising feasibility.


## Baselines
We choose the following previous work as our baselines in the paper:

1. INRR3CT: CT Reconstruction from Few Planar X-Rays with Application Towards Low-Resource Radiotherapy: https://github.com/LexieSunn/INRR3CT

2. X2CT-GAN: Reconstructing CT from Biplanar X-Rays with Generative Adversarial Networks: https://github.com/kylekma/X2CT

3. Video Diffusion Models: https://github.com/lucidrains/video-diffusion-pytorch

4. NAF: Neural Attenuation Fields for Sparse-View CBCT Reconstruction: https://github.com/Ruyi-Zha/naf_cbct


## References

1. Long Video Generation with Time-Agnostic VQGAN and Time-Sensitive Transformer: https://github.com/songweige/TATS

2. Video Diffusion Models: https://github.com/lucidrains/video-diffusion-pytorch



