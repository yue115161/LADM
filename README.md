# LADM-LAFM A Locally Adaptive Semi-dense Matching Method for Multimodal Remote Sensing Images

**代码已发布在本仓库的 tag 中，请切换到对应 tag 查看和下载。https://github.com/yue115161/LADM/releases/tag/v1.0**


**The code has been released in the tag of this repository. Please switch to the corresponding tag to view and download it.https://github.com/yue115161/LADM/releases/tag/v1.0**

## 📖 Overview

This repository provides the implementation of the RMSS algorithm, as described in the paper:

**Multimodal Remote Sensing Image Matching Considering Structural Saliency**

Li Xue, Yehua Sheng, Shuwen Yang, Xiangqiang Min, and Xiu Lu

Experimental comparisons between RMSS and seven state-of-the-art algorithms, using six types of multimodal remote sensing images, demonstrate that RMSS is:

- ✅ Simple to implement
- ✅ Highly robust to rotation in multimodal images
- ✅ Able to substantially improve the number and localization accuracy of matching points
- ✅ Able to improve the correct matching rate

## ✨ Contributions

The main contributions of this work are outlined as follows:

1. **Structural Saliency Representation.** We propose a novel method for expressing structural saliency. Unlike phase congruency-based approaches, we represent structural information through the relative dispersion of neighborhood information and structural orientation, which enables stable and efficient representation of structural intensity and directional information in images. This provides resilience to NRD and directional reversal in multimodal remote sensing imagery to a certain extent.

2. **Structural Saliency Descriptor.** Feature points are extracted using a structural intensity map, and the GLOH framework is optimized to construct a structural saliency descriptor vector, which enhances the rotational invariance of the descriptor.

3. **Coarse-to-Fine Matching Strategy.** A coarse-to-fine matching strategy is designed to increase the number and accuracy of matched pairs, and the FSC algorithm is optimized to improve the stability of mismatch pruning.

4. **Two-Stage Subpixel Refinement.** A two-stage subpixel refinement strategy that combines Gaussian fitting and similarity metrics is designed to further improve the number of matched points and localization accuracy.

Experimental results demonstrate that the proposed method exhibits high robustness to NRD and image rotation, and can significantly increase the number of matching points and the matching accuracy.

## 🚀 Run

This code is written in **C#**.

### Option 1: Just run it (image matching only)

If you only use this code for image matching, simply run:


### Option 2: Modify the code

If you need to change the code, please use the **Visual Studio** platform.

Developed with **Visual Studio 2019**.

The code implements the RMSS algorithm (paper: *Multimodal Remote Sensing Image Matching Considering Structural Saliency*).

## 📊 Result

![](reslut-pair1.png)

（如果 `reslut-pair1` 是图片文件，请把上面的文件名改成实际路径；如果是文件夹，可以删掉这一行或改成文字说明。）

## 📌 Notes

⚠️ **Commercial use of this code is prohibited.**

I wish you all a happy life and successful scientific research! 🎉

## 📝 Cite

If you find this repository useful in your research, please consider giving a star ⭐ and a citation.
Xue, L., Sheng, Y., Yang, S., & Lu, X. (2026). A locally adaptive semi-dense matching method for multimodal remote sensing images. International Journal of Remote Sensing, 1–28. https://doi.org/10.1080/01431161.2026.2760580


## 📧 Contact
Email: 1151617653@qq.com
