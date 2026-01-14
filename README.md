# Adaptive Weight-Modified Riesz Mean Filter (AWMRmF)

**Official implementation of the paper: "Adaptive weight-modified Riesz mean filter for high-density salt-and-pepper noise removal"**

[![Journal](https://img.shields.io/badge/Journal-J.%20Electr.%20Syst.%20Inf.%20Technol.-blue)](https://doi.org/10.1186/s43067-025-00266-1)
[![DOI](https://img.shields.io/badge/DOI-10.1186%2Fs43067--025--00266--1-green)](https://doi.org/10.1186/s43067-025-00266-1)

## 📄 Abstract
This paper introduces a novel filter, the adaptive weight-modified Riesz mean filter
(AWMRmF), designed for the effective removal of high-density salt-and-pepper
noise. AWMRmF integrates a pixel weight function and adaptivity condition inspired
by the different adaptive modified Riesz mean filter. In this study, the performance
of AWMRmF was evaluated against established filters such as adaptive frequency
median filter, adaptive weighted mean filter, adaptive Ces´aro mean filter, adaptive
Riesz mean filter, and improved adaptive weighted mean filter. The assessment
was conducted on 26 typical test images, varying noise levels from 60 to 95%. The findings
indicate that, in terms of both peak signal-to-noise ratio and structural similarity
metrics, AWMRmF outperformed other state-of-the-art filters. Furthermore, AWMRmF
demonstrated superior performance in mean PSNR and SSIM results as well.
In our simulations, we evaluated the performance of AWMRmF against established filters such as:
*AFMF: Adaptive Frequency Median Filter 
*AWMF: Adaptive Weighted Mean Filter 
*ACmF: Adaptive Cesáro Mean Filter 
*ARmF: Adaptive Riesz Mean Filter 
*IAWMF: Improved Adaptive Weighted Mean Filter 
*DAMRmF: Different Adaptive Modified Riesz Mean Filter (This was a key basis for your proposed method)

The assessment was conducted on **26 typical test images**, with noise levels varying from **60% to 95%**. The findings indicate that, in terms of both **Peak Signal-to-Noise Ratio (PSNR)** and **Structural Similarity (SSIM)** metrics, AWMRmF outperformed other state-of-the-art filters.

## 🔗 Publication Details
This article is published in the **Journal of Electrical Systems and Information Technology** (Springer Open).

* **Title:** Adaptive weight-modified Riesz mean filter for high-density salt-and-pepper noise removal
* **Author:** Md Jahidul Islam
* **Journal:** Journal of Electrical Systems and Information Technology
* **Volume:** 12, Article number: 76 (2025)
* **DOI:** [10.1186/s43067-025-00266-1](https://doi.org/10.1186/s43067-025-00266-1)

## 📝 Citation
If you use this code or findings in your research, please cite the published journal version:

```bibtex
@article{islam2025adaptive,
  title={Adaptive weight-modified Riesz mean filter for high-density salt-and-pepper noise removal},
  author={Islam, Md Jahidul},
  journal={Journal of Electrical Systems and Information Technology},
  volume={12},
  number={1},
  pages={76},
  year={2025},
  publisher={Springer},
  doi={10.1186/s43067-025-00266-1}
}
