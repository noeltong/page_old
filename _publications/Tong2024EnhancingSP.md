---
title: "Enhancing Sparse Photoacoustic Tomography Reconstruction with Score-Based Generative Models"
collection: publications
category: conference
permalink: /publication/Tong2024EnhancingSP
date: 2024-05-27
venue: 'IEEE International Symposium on Biomedical Imaging'
paperurl: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10635125'
citation: "Tong, Shangqing, Hengrong Lan, Daohuai Jiang, Liming Nie, Jianwen Luo and Fei Gao. &quot;Enhancing Sparse Photoacoustic Tomography Reconstruction with Score-Based Generative Models.&quot; <i>2024 IEEE International Symposium on Biomedical Imaging (ISBI)</i> (2024): 1-4."
---


* Trained with only ground truth images, our method achieved competitive performance against supervised U-Net, while ours could generalize to different numbers of projections;
* A constraint is designed following the rotation equivariance between photoacoustic tomography measurements and images, which is used to guide the vanilla diffusion sampler.
* Our method achieved 35.06 PSNR, 0.913 SSIM in uniform sampling with 32 measurements; and 29.69 PSNR (128 in total).

If you find our article useful for your research, please consider citing
```
@inproceedings{Tong2024EnhancingSP,
  title={Enhancing Sparse Photoacoustic Tomography Reconstruction with Score-Based Generative Models},
  author={Shangqing Tong and Hengrong Lan and Daohuai Jiang and Liming Nie and Jianwen Luo and Fei Gao},
  journal={2024 IEEE International Symposium on Biomedical Imaging (ISBI)},
  year={2024},
  pages={1-4},
}
```