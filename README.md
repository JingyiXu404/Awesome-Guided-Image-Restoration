<p align="center"><img src="Figures/title.png" alt="Awesome Guided Image Restoration" width="100%"></p>

> A curated list of resources for **Guided Image Restoration (GISIR)** or **Multi-modal Image Restoration (MISR)**.
> 一个关于 **多模态图像修复** 精选资源的列表。
> 
> ⚡️ **Note:** This project is **continuously** being updated. Issues are welcome to help improve the list! 😊
---

## 📖 Table of Contents / 目录
- [💓 Introduction](#introduction)
- [📄 Papers](#papers)
  - [🛠️ All-In-One Guided Image Restoration](#All-papers)
  - [🛠️ Multi-task Image Restoration](#MT-papers)
  - [🛠️ Guided Image Super-Resolution](#SR-papers)
    - [🧪 RGB Guided Depth Image Super-Resolution](#RGBD-papers)
    - [🧪 RGB Guided Thermal Image Super-Resolution](#RGBT-papers)
    - [🧪 RGB Guided Hyperspectral Super-Resolution](#HSI-papers)
    - [🧪 Pansharpening](#Pan-papers)
    - [🧪 Multi-Contrast MRI](#MRI-papers)
  - [🛠️  Guided Image Denoising](#DN-papers)
  - [🛠️ Guided Low-Light Image Enhancement](#LL-papers)
  - [🛠️ Guided Image Deblurring](#DB-papers)
  - [🛠️ Guided Image Dehazing/Deraining](#DH-papers)
  - [🛠️ Guided Image Inpainting/ Completion](#IC-papers)
- [🌟 Datasets / 数据集](#datasets)
  - [🛠️ Guided Image Super-Resolution](#SR-data)
    - [🧪Super-Resolution Synthetic-Datasets](#SR-synthetic-datasets)
    - [🧪Super-Resolution Real-World-Datasets](#SR-real-world-datasets)
  - [🛠️ Guided Image Denoising](#DN-data)
    - [🧪Denoising Synthetic-Datasets](#DN-synthetic-datasets)
    - [🧪Denoising Real-World-Datasets](#DN-real-world-datasets)
  - [🛠️ Lowlight-Datasets](#LL-datasets)
  - [🛠️ Deblurring-Datasets](#DB-datasets)
  - [🛠️ Dehazing/Deraining-Datasets](#DH-datasets)
  - [🛠️ Guided Image Inpainting/ Completion](#IC-datasets)
---

<a id="introduction"></a>
## 🌟 Introduction / 简介
This repository focuses on collecting resources related to **Guided Image Super-Resolution (GISR)** or **Multi-modal Image Super-Resolution (MISR)**, including papers, open-source code and datasets. It serves as a one-stop reference for researchers and developers interested in this field.

本仓库专注于收集 **多模态图像修复** 相关资源，包括论文、开源代码、数据集，为对该领域感兴趣的研究者和开发者提供一站式参考资料。

---

<a id="papers"></a>
## 📄 Papers / 论文

<a id="All-papers"></a>
### 🛠️ All-In-One Guided Image Restoration

| 年份<br>Year | 标题<br>Title | 简称<br>Abbr. | 期刊/会议<br>Published | 代码<br>Code | 关键词<br>Keywords |
| ---- | ------------- | ------------- | ---------------------- | ------------ | ------------------ |
|2026|Task-aware all-in-one guided image super-resolution|MAG-Net | [PR](https://www.sciencedirect.com/science/article/pii/S0031320326004498) | |First all-in-one GISR framework, Text, **Pioneer‌**|

<a id="MT-papers"></a>
### 🛠️ Multi-task Image Restoration

| 年份<br>Year | 标题<br>Title | 简称<br>Abbr. | 期刊/会议<br>Published | 代码<br>Code | 关键词<br>Keywords |
| ---- | ------------- | ------------- | ---------------------- | ------------ | ------------------ |
| 2026 | Adaptive Cross-Modal Denoising: Enhancing LiDAR-Camera Fusion Perception in Adverse Circumstances | ACMD | [Sensors](https://doi.org/10.3390/s26020408) | - | LiDAR-camera denoising, Reliability-aware fusion |
| 2026 | M2Diff: Multi-Modality Multi-Task Enhanced Diffusion Model for MRI-Guided Low-Dose PET Enhancement|M2Diff|[TRPMS](https://doi.org/10.1109/TRPMS.2026.3672075)|/| MRI guided PET, Multi-task diffusion|
|2025|Hyperspectral Image Joint Denoising and Super-Resolution by Image Fusion with the Panchromatic Image|Hipandas|[ICCV](https://ieeexplore.ieee.org/document/11446024) |[Code](https://github.com/shuangxu96/Hipandas) | PAN guided HSI, Denoising+Super-Resolution|
| 2024 | DeepM2CDL: Deep multiscale multi-modal convolutional dictionary learning network | DeepM2CDL | [TPAMI](https://doi.org/10.1109/TPAMI.2023.3334624) | [Code](https://github.com/JingyiXu404/TPAMI-DeepM2CDL) | Multimodal restoration, Dictionary learning |
| 2022 | Designing CNNs for multimodal image restoration and fusion via unfolding the method of multipliers | MMCNN | [TCSVT](https://doi.org/10.1109/TCSVT.2022.3163649) | - | Multimodal restoration, Unfolding |
| 2021 | Deep convolutional neural network for multi-modal image restoration and fusion | CU-Net | [TPAMI](https://ieeexplore.ieee.org/document/9055063) | - | Multimodal restoration, Common/unique features |
| 2015 | Multispectral joint image restoration via optimizing a scale map | Scale Map | [TPAMI](https://doi.org/10.1109/TPAMI.2015.2417569) | - | Joint restoration, Scale map |

<a id="SR-papers"></a>
### 🛠️ Guided Image Super-Resolution

<a id="RGBD-papers"></a>
#### 🧪 RGB Guided Depth Image Super-Resolution

| 年份<br>Year | 标题<br>Title | 简称<br>Abbr. | 期刊/会议<br>Published | 代码<br>Code | 关键词<br>Keywords |
| ---- | ------------- | ------------- | ---------------------- | ------------ | ------------------ |
|2025|Deep Semi-Smooth Newton-Driven Unfolding Network for Multi-Modal Image Super-Resolution|SNUM-Net| [TIP](https://ieeexplore.ieee.org/abstract/document/11222911) | [Code]( https://github.com/pandazcx/SNUM-Net)|Unfolding|
|2025|Dual-Level Cross-Modality Neural Architecture Search for Guided Image Super-Resolution|DCNAS| [TPAMI](https://ieeexplore.ieee.org/abstract/document/11029618) | [Code](https://github.com/zhwzhong/DCNAS)|NAS |
|2025|C2PD: Continuity-Constrained Pixelwise Deformation for Guided Depth Super-Resolution|C2PD| [AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/32442) | [Code](https://github.com/amhamster/c2pd)||
|2025|DORNet: A Degradation Oriented and Regularized Network for Blind Depth Super-Resolution|DORNet| [CVPR](https://openaccess.thecvf.com/content/CVPR2025/papers/Wang_DORNet_A_Degradation_Oriented_and_Regularized_Network_for_Blind_Depth_CVPR_2025_paper.pdf) | [Code](https://github.com/yanzq95/dornet)|Transformer, Attention, Cross-modal Fusion|
|2024|A General Spatial-Frequency Learning Framework for Multimodal Image Fusion|SFINet| [TPAMI](https://ieeexplore.ieee.org/abstract/document/10443302) |||
|2024|Learning Hierarchical Color Guidance for Depth Map Super-Resolution|HCGNet| [TIM](https://ieeexplore.ieee.org/abstract/document/10478547) |[Code](https://github.com/rmcong/HCGNet_TIM2024)||
|2024|Learning Piecewise Planar Representation for RGB Guided Depth Super-Resolution|PGSR| [TCI](https://ieeexplore.ieee.org/abstract/document/10629189/) |[Code](https://github.com/XrKang/PGSR)||
|2024|TM-GAN: A Transformer-Based Multi-Modal Generative Adversarial Network for Guided Depth Image Super-Resolution|TM-GAN| [JETCAS](https://ieeexplore.ieee.org/abstract/document/10509697/) |||
|2024|SGNet: Structure Guided Network via Gradient-Frequency Awareness for Depth Map Super-resolution|SGNet| [AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/28395) |[Code](https://github.com/yanzq95/SGNet)||
|2024| Deep Attentional Guided Image Filtering | DAGF | [TNNLS](https://ieeexplore.ieee.org/document/10089494) | [Code](https://github.com/zhwzhong/DAGF) | Attentional kernel learning |
|2023|Recurrent Structure Attention Guidance for Depth Super-resolution|DSR-RSAG| [AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/25440) | [Code](https://github.com/Yuanjiayii/DSR_RSAG)||
|2023|Memory-augmented Deep Unfolding Network for Guided Image Super-resolution|MADUNet| [IJCV](https://link.springer.com/article/10.1007/s11263-022-01699-1) |||
|2023|Spherical Space Feature Decomposition for Guided Depth Map Super-Resolution|SSDNet| [ICCV](https://openaccess.thecvf.com/content/ICCV2023/papers/Zhao_Spherical_Space_Feature_Decomposition_for_Guided_Depth_Map_Super-Resolution_ICCV_2023_paper.pdf) |[Code](https://github.com/Zhaozixiang1228/GDSR-SSDNet)||
|2023| Learning Continuous Depth Representation via Geometric Spatial Aggregator | GeoDSR | [AAAI](https://arxiv.org/abs/2212.03499) | [Code](https://github.com/nana01219/GeoDSR) | Arbitrary-scale, continuous |
|2022| Discrete Cosine Transform Network for Guided Depth Map Super-Resolution | DCTNet | [CVPR](https://arxiv.org/abs/2104.06977) | [Code](https://github.com/Zhaozixiang1228/GDSR-DCTNet) | DCT, optimization unrolling |
|2022| High-resolution Depth Maps Imaging via Attention-based Hierarchical Multi-modal Fusion | AHMF | [TIP](https://arxiv.org/abs/2104.01530) | [Code](https://github.com/zhwzhong/AHMF) | Attention multi-modal fusion |
|2022| Symmetric Uncertainty-aware Feature Transmission for Depth Super-Resolution | SUFT | [ACM MM](https://dl.acm.org/doi/10.1145/3503161.3547873) | [Code](https://github.com/ShiWuxuan/SUFT) | Symmetric uncertainty, cross-modal |
|2021| Deformable Kernel Networks for Joint Image Filtering | DKN/FDKN | [IJCV](https://arxiv.org/abs/1910.08373) | [Code](https://github.com/cvlab-yonsei/dkn) | Sparse deformable kernels |
|2021| Towards Fast and Accurate Real-World Depth Super-Resolution: Benchmark Dataset and Baseline | FDSR | [CVPR](https://openaccess.thecvf.com/content/CVPR2021/papers/He_Towards_Fast_and_Accurate_Real-World_Depth_Super-Resolution_Benchmark_Dataset_and_CVPR_2021_paper.pdf) | [Code](https://github.com/lingzhi96/RGB-D-D-Dataset) | High-frequency guidance, RGB-D-D |
|2021| Joint Implicit Image Function for Guided Depth Super-Resolution | JIIF | [ACM MM](https://dl.acm.org/doi/10.1145/3474085.3475584) | [Code](https://github.com/ashawkey/jiif) | Implicit neural interpolation |
|2020| Deep Convolutional Neural Network for Multi-modal Image Restoration and Fusion | CU-Net | [TPAMI](https://arxiv.org/abs/1910.04066) | [Code](https://github.com/cindydeng1991/TPAMI-CU-Net) | Common/unique sparse coding |
|2019| Pixel-Adaptive Convolutional Neural Networks | PAC | [CVPR](https://openaccess.thecvf.com/content_CVPR_2019/papers/Su_Pixel-Adaptive_Convolutional_Neural_Networks_CVPR_2019_paper.pdf) | [Code](https://github.com/NVlabs/pacnet) | Content-adaptive convolution |
| 2016 | Deep joint image filtering | learning-based joint image filter | [ECCV](https://link.springer.com/chapter/10.1007/978-3-319-46493-0_10) | --- | CNN, Skip connection(**Pioneer‌ NN**) |
|2007| Joint Bilateral Upsampling | JBU | [TOG](https://johanneskopf.de/publications/jbu/) | - | Edge-aware upsampling (**Pioneer**) |

<a id="RGBT-papers"></a>
#### 🧪 RGB Guided Thermal Image Super-Resolution

| 年份<br>Year | 标题<br>Title | 简称<br>Abbr. | 期刊/会议<br>Published | 代码<br>Code | 关键词<br>Keywords |
| ---- | ------------- | ------------- | ---------------------- | ------------ | ------------------ |
| 2026 | DuaDiff: Dual-Conditional Diffusion Model for Guided Thermal Image Super-Resolution | DuaDiff | [TNNLS](https://doi.org/10.1109/TNNLS.2025.3640168) | [TBA](https://github.com/shilinrui/DuaDiff) | Diffusion-based, Dual-conditional, Cross-modal fusion |
| 2026 | Exploring Diffusion-generated Guidance for Thermal Image Super-resolution | --- | [WACV](https://openaccess.thecvf.com/content/WACV2026W/RWS/html/Ramos_Exploring_Diffusion-generated_Guidance_for_Thermal_Image_Super-resolution_WACVW_2026_paper.html) | --- | Diffusion-based, Pseudo-thermal guidance, Model-agnostic |
| 2026 | Diff-GTISR: Guided Thermal Image Super-Resolution via Diffusion Model and Refinement | Diff-GTISR | [Appl. Sci.](https://doi.org/10.3390/app16073435) | --- | Diffusion-based, Cross-modal guidance attention, Refinement |
| 2026 | Laplacian reconstructive network for guided thermal super-resolution | LapGSR | [Sci. Rep](https://www.nature.com/articles/s41598-026-36027-x) | [Code](https://github.com/uverma/LapGSR) | Multi-stage, Cross-modal fusion |
| 2026 | Visible-Light-Guided Infrared Image Super  Resolution With Dual Amplitude-Phase Optimization | vap-SR | [JSTARS](https://doi.org/10.1109/JSTARS.2026.3655485) | [Code](https://github.com/KustTeamWQW/vap-SR) | Diffusion-based|
| 2025 | A Swin Transformer-Based Framework for RGB-Guided Thermal Image Super-Resolution | SwinPaste | [CVPR](https://openaccess.thecvf.com/content/CVPR2025W/PBVS/html/Zhong_SwinPaste_A_Swin_Transformer-Based_Framework_for_RGB-Guided_Thermal_Image_Super-Resolution_CVPRW_2025_paper.html) | --- | Swin Transformer, Attention, Multi-stage |
| 2025 | Multi-Feature Guided Cross-Refinement Transformer for RGB-Guided Thermal Image Super-Resolution | MFG-CRT | [VCIP](https://ieeexplore.ieee.org/abstract/document/11396904) | [Code](https://github.com/DoGunKIM93/MFG-CRT) | Transformer, Attention, Cross-modal Fusion |
|2025|Deep Semi-Smooth Newton-Driven Unfolding Network for Multi-Modal Image Super-Resolution|SNUM-Net| [TIP](https://ieeexplore.ieee.org/abstract/document/11222911) | [Code]( https://github.com/pandazcx/SNUM-Net)|Unfolding|
|2025|Dual-Level Cross-Modality Neural Architecture Search for Guided Image Super-Resolution|DCNAS| [TPAMI](https://ieeexplore.ieee.org/abstract/document/11029618) | [Code](https://github.com/zhwzhong/DCNAS)| |
| 2024 | Multi-Scale Feature Fusion using Channel Transformers for Guided Thermal Image Super Resolution | MSFFCT | [CVPR](https://openaccess.thecvf.com/content/CVPR2024W/PBVS/html/Puttagunta_Multi-Scale_Feature_Fusion_using_Channel_Transformers_for_Guided_Thermal_Image_CVPRW_2024_paper.html) | --- | Transformer, Multi-scale fusion, Attention |
| 2024 | Enhancement of guided thermal image super-resolution approaches | --- | [Neurocomputing](https://www.sciencedirect.com/science/article/pii/S0925231223013206?via%3Dihub) | --- | Cycle GAN |
| 2024 | Modality Conversion Meets Superresolution: A Collaborative Framework for High- Resolution Thermal UAV Image Generation | CENet |[TGRS](https://ieeexplore.ieee.org/abstract/document/10401239) | --- | Cross-modal fusion, GAN, Swin Transformer |
| 2024 | An image fusion-inspired model for RGB-guided thermal image  super-resolution | SwinFuSR | [CVPR](https://openaccess.thecvf.com/content/CVPR2024W/PBVS/papers/Arnold_SwinFuSR_An_Image_Fusion-inspired_Model_for_RGB-guided_Thermal_Image_Super-resolution_CVPRW_2024_paper.pdf) | [Code](https://github.com/VisionICLab/SwinFuSR) | Intra-domain fusion, Skip connection |
| 2023 | CoReFusion: Contrastive Regularized Fusion for Guided Thermal Super-Resolution | CoReFusion | [CVPR](https://openaccess.thecvf.com/content/CVPR2023W/PBVS/html/Kasliwal_CoReFusion_Contrastive_Regularized_Fusion_for_Guided_Thermal_Super-Resolution_CVPRW_2023_paper.html) | [Code](https://github.com/Kasliwal17/CoReFusion) | Cross-modal fusion, Contrastive learning |
| 2023 | Thermal UAV Image Super-Resolution Guided by Multiple Visible Cues | MGNet | [TGRS](https://ieeexplore.ieee.org/abstract/document/10005291) | [Code](https://github.com/mmic-lcl/Datasets-and-benchmark-code) | Cross-modal fusion |
| 2018 | RGB Guided Thermal Super-Resolution  Enhancement | TIGAN | [Cloudtech 2018](https://www.researchgate.net/publication/333068416_RGB_Guided_Thermal_Super-Resolution_Enhancement) | --- | GAN, Residual-block(**Pioneer‌ NN**) |


<a id="HSI-papers"></a>
#### 🧪 RGB Guided Hyperspectral Super-Resolution

| 年份<br>Year | 标题<br>Title | 简称<br>Abbr. | 期刊/会议<br>Published | 代码<br>Code | 关键词<br>Keywords |
| ---- | ------------- | ------------- | ---------------------- | ------------ | ------------------ |
| 2026 | Multiscale RGB-Guided Fusion for Hyperspectral Image Super-Resolution | CGNet | [MDPI](https://www.mdpi.com/2313-433X/12/2/61) | --- | Cross-Model Fusion, Attention |
| 2025 | Deep RGB-guided generative network for unsupervised hyperspectral image super-resolution | DRGN | [APPL INTELL](https://link.springer.com/article/10.1007/s10489-025-06595-y) | --- | Cross-modal Fusion, Generative |
| 2025 | Unaligned RGB Guided Hyperspectral Image Super-Resolution with Spatial-Spectral Concordance | SSC-HSR | [IJCV](https://link.springer.com/article/10.1007/s11263-025-02466-8) | [Code](https://github.com/BITYKZhang/SSC-HSR) | Unaligned, Spatial-spectral concordance |
| 2024 | Unsupervised Multimodal Multilevel Feature Fusion Network for Hyperspectral Image Super-Resolution | UMMFF | [MDPI](https://www.mdpi.com/2072-4292/16/17/3282) | [Code](https://github.com/mengyao72/UMMFF) | Multi-Stage, Transformer |
| 2024 | Hyperspectral Image Super Resolution With  Real Unaligned RGB Guidance | HSIFN | [IEEE TNNLS](https://ieeexplore.ieee.org/abstract/document/10406185) | [Code](https://zeqiang-lai.github.io/HSI-RefSR/) | Multistage feature alignment |
| 2023 | RGB-Induced Feature Modulation Network for Hyperspectral Image Super-Resolution | IFMSR | [TGRS](https://ieeexplore.ieee.org/abstract/document/10129137) | [Code](https://github.com/qianngli/IFMSR) | Dynamic filtering |
| 2023 | Spectral Super-Resolution via Model-Guided Cross-Fusion Network | SSRNet | [TNNLS](https://ieeexplore.ieee.org/abstract/document/10028670) | [Code](https://github.com/renweidian/SSRnet-pytorch) | Unfolding, Multi-stage |
| 2022 | Robust RGB-Guided Super-Resolution of Hyperspectral Images via TV3 Minimization | TV3 Minimization | [IEEE Signal Process. Lett.](https://ieeexplore.ieee.org/abstract/document/9735396) | --- | Unfolding, Cross-modal guidance |

<a id="Pan-papers"></a>
#### 🧪 Pansharpening

| 年份<br>Year | 标题<br>Title | 简称<br>Abbr. | 期刊/会议<br>Published | 代码<br>Code | 关键词<br>Keywords |
| ---- | ------------- | ------------- | ---------------------- | ------------ | ------------------ |
|2025|Deep Semi-Smooth Newton-Driven Unfolding Network for Multi-Modal Image Super-Resolution|SNUM-Net| [TIP](https://ieeexplore.ieee.org/abstract/document/11222911) | [Code]( https://github.com/pandazcx/SNUM-Net)|Unfolding|
|2025|Dual-Level Cross-Modality Neural Architecture Search for Guided Image Super-Resolution|DCNAS| [TPAMI](https://ieeexplore.ieee.org/abstract/document/11029618) | [Code](https://github.com/zhwzhong/DCNAS)| NAS |
| 2025 | A Novel Split Deep Unfolding Transformer for Pan-Sharpening | DIUT | [ICASSP](https://ieeexplore.ieee.org/abstract/document/10887723) | --- | Unfolding, Transformer, Multi-stage |
| 2025 | Interpretable Region-Aware Transformer-Based Deep Unfolding Network for Pan-Sharpening | RTDU | [JSTARS](https://ieeexplore.ieee.org/abstract/document/11005626) | --- | Unfolding, Transformer, Attention |
| 2025 | Frequency-Analysis-Based Transformer  Focusing on Correlation and Specificity  for Pansharpening | FAFormer | [TGRS](https://ieeexplore.ieee.org/abstract/document/10994818) | [Code](https://github.com/Xidian-AIGroup190726/FAFormer) | Transformer, Attention, Cross-modal Fusion |
|2024|A General Spatial-Frequency Learning Framework for Multimodal Image Fusion|SFINet| [TPAMI](https://ieeexplore.ieee.org/abstract/document/10443302) || Attention|
|2023|Memory-augmented Deep Unfolding Network for Guided Image Super-resolution|MADUNet| [IJCV](https://link.springer.com/article/10.1007/s11263-022-01699-1) || Unfolding, Multi-Stage, Cross-modal Fusion |
| 2017 | Deep residual learning for remote sensed imagery pansharpening | DRPNN | [RSIP](https://ieeexplore.ieee.org/document/7958794) | --- | Residual learning |
| 2016 | Pansharpening by Convolutional Neural Networks | PNN | [MDPI](https://www.mdpi.com/2072-4292/8/7/594) | [Code](http://www.grip.unina.it) |**Pioneer‌**|

<a id="MRI-papers"></a>
#### 🛠️ Multi-Contrast MRI

| 年份<br>Year | 标题<br>Title | 简称<br>Abbr. | 期刊/会议<br>Published | 代码<br>Code | 关键词<br>Keywords |
| ---- | ------------- | ------------- | ---------------------- | ------------ | ------------------ |
| 2026 | Reference-guided MRI super-resolution with dual attention aggregation network | DAASR | [Front. Neurol.](https://www.frontiersin.org/journals/neurology/articles/10.3389/fneur.2026.1806780/full) | --- | Transformer, Reference-based |
| 2026 | Unfolding High-Order Correlations for Interpretable Multi-Contrast MRI Super-Resolution | HocMRI | [IEEE Trans. on Image Process.](https://pubmed.ncbi.nlm.nih.gov/41894209/) | --- | Unfolding, Multi-stage, Mamba |
| 2025 | A Spatial-Semantic Consistent Model for Multi-Contrast MRI Super-Resolution | SSAM | [CVPR](https://arxiv.org/abs/2509.18593) | --- | Attention |
| 2025 | Edge-guided conditional diffusion model for multi-contrast MRI super-resolution | Eg-Diff | [INFORM FUSION](https://www.sciencedirect.com/science/article/abs/pii/S156625352500586X) | --- | DM, LED |
| 2025 | CRFormer: Towards Accurate Multi-Contrast MRI Super-Resolution with Composited and Reconciled Transformer | CRFormer | [BIBM](https://ieeexplore.ieee.org/abstract/document/11356956) | --- | Attention, Cross-modal Fusion |
| 2025 | Multi-Contrast MRI Arbitrary-Scale Super-Resolution via Dynamic Implicit Network | DINet | [TCSVT](https://ieeexplore.ieee.org/abstract/document/10945918) | [Code](https://github.com/weijinbao1998/DINet) | DY-CNN, INR, Attention |
|2023|Memory-augmented Deep Unfolding Network for Guided Image Super-resolution|MADUNet| [IJCV](https://link.springer.com/article/10.1007/s11263-022-01699-1) | --- |Unfolding, Multi-Stage, Cross-modal Fusion|
| 2020 | Multi-Contrast Super-Resolution MRI Through a  Progressive Network | One/two-level progressive network | [IEEE TMI](https://ieeexplore.ieee.org/abstract/document/9001105) | --- | CNN, **Pioneer‌ GAN** |

<a id="DN-papers"></a>
### 🛠️ Guided Image Denoising

| 年份<br>Year | 标题<br>Title | 简称<br>Abbr. | 期刊/会议<br>Published | 代码<br>Code | 关键词<br>Keywords |
| ---- | ------------- | ------------- | ---------------------- | ------------ | ------------------ |
| 2025 | GCOANet: A gradient consistency constraints semi-supervised network for optical image-assisted SAR despeckling | GCOANet | [IJAEOG](https://www.sciencedirect.com/science/article/pii/S1569843225003243) | - | Optical guided SAR, Gradient consistency |
| 2025 | Multimodal feature-guided diffusion model for low-count PET image denoising | MFG-Diff | [Med. Phys](https://aapm.onlinelibrary.wiley.com/doi/abs/10.1002/mp.17764) | - | MRI guided PET, Diffusion |
| 2025 | Structure-guided denoising transformer for cross-spectral stereo image denoising | SGDFormer | [Information Fusion](https://doi.org/10.1016/j.inffus.2024.102603) | [Code](https://github.com/RM-Zhang/SGDFormer) | Cross-spectral stereo, Transformer |
| 2024 | Laplacian Gradient Consistency Prior for Flash Guided Non-Flash Image Denoising | LGCNet | [TIP](https://doi.org/10.1109/TIP.2024.3489275) | [Code](https://github.com/JingyiXu404/LGCNet) | Flash guided denoising, Gradient consistency |
| 2024 | Pan-Denoising: Guided Hyperspectral Image Denoising via Weighted Represent Coefficient Total Variation | PWRCTV | [TGRS](https://doi.org/10.1109/TGRS.2024.3450888) | [Code](https://github.com/shuangxu96/PWRCTV) | PAN guided HSI, Weighted TV |
| 2023 | Robust image denoising of no-flash images guided by consistent flash images | Robust Image Denoising Framework | [AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/25291) | [Code](https://github.com/CGLab-GIST/RIDFnF) | Flash guided denoising, Consistency selection |
| 2023 | Self-Supervised Learning for RGB-Guided Depth Enhancement by Exploiting the Dependency Between RGB and Depth | SRDE | [TIP](https://doi.org/10.1109/TIP.2022.3226419) | [Code](https://github.com/wjcyt/SRDE) | RGB guided depth, Self-supervised |
| 2023 | Structure Aggregation for Cross-Spectral Stereo Image Guided Denoising | SANet | [CVPR](https://openaccess.thecvf.com/content/CVPR2023/papers/Sheng_Structure_Aggregation_for_Cross-Spectral_Stereo_Image_Guided_Denoising_CVPR_2023_paper.pdf) | [Code](https://github.com/lustrouselixir/SANet) | Cross-spectral stereo, Structure aggregation |
| 2022 | A model-driven network for guided image denoising | MN | [Information Fusion](https://www.sciencedirect.com/science/article/pii/S1566253522000318) | [Code](https://github.com/shuangxu96/MN-A-model-driven-network-for-guided-image-denoising) | Guided denoising, Mixture modeling |
| 2022 | Frequency-domain deep guided image denoising | FGDNet | [TMM](https://doi.org/10.1109/TMM.2022.3214375) | [Code](https://github.com/lustrouselixir/FGDNet) | Guided denoising, Frequency-domain |
| 2022 | Frequency-relevant residual learning for multi-modal image denoising | FRL | [ICIP](https://doi.org/10.1109/ICIP46576.2022.9898074) | [Code](https://github.com/liuxw11/FRL) | Multi-modal denoising, Residual learning |
| 2022 | Joint image denoising with gradient direction and edge-preserving regularization | - | [Pattern Recognition](https://doi.org/10.1016/j.patcog.2021.108506) | - | Guided denoising, Edge-preserving regularization |
| 2022 | Spatial adaptive and transformer fusion network (STFNet) for low-count PET blind denoising with MRI | STFNet | [Med. Phys](https://pubmed.ncbi.nlm.nih.gov/34796526/) | - | MRI guided PET, Transformer fusion |
| 2021 | Deep denoising of flash and no-flash pairs for photography in low-light environments | DeepFnF | [CVPR](https://openaccess.thecvf.com/content/CVPR2021/papers/Xia_Deep_Denoising_of_Flash_and_No-Flash_Pairs_for_Photography_in_CVPR_2021_paper.pdf) | [Code](https://likesum.github.io/deepfnf/) | Flash guided denoising, Kernel prediction |
| 2020 | Color-guided depth image recovery with adaptive data fidelity and transferred graph Laplacian regularization | - | [TCSVT](https://doi.org/10.1109/TCSVT.2018.2890574) | - | RGB guided depth, Graph Laplacian |
| 2020 | Micro-Networks for Robust MR-Guided Low Count PET Imaging | Micro-net | [TRPMS](https://doi.org/10.1109/TRPMS.2020.2986414) | - | MRI guided PET, Small CNN |
| 2019 | Depth Restoration From RGB-D Data via Joint Adaptive Regularization and Thresholding on Manifolds | - | [TIP](https://doi.org/10.1109/TIP.2018.2872175) | - | RGB guided depth, Manifold regularization |
| 2019 | Fast color-guided depth denoising for RGB-D images by graph filtering | - | [Asilomar](https://doi.org/10.1109/IEEECONF44664.2019.9048703) | - | RGB guided depth, Graph filtering |
| 2019 | Optimized color-guided filter for depth image denoising | - | [ICASSP](https://doi.org/10.1109/ICASSP.2019.8683416) | - | RGB guided depth, Guided filtering |
| 2019 | Spatially Variant Linear Representation Models for Joint Filtering | SVLRM | [CVPR](https://openaccess.thecvf.com/content_CVPR_2019/papers/Pan_Spatially_Variant_Linear_Representation_Models_for_Joint_Filtering_CVPR_2019_paper.pdf) | - | Spatially-variant linear model |
| 2019 | Joint Image Filtering with Deep Convolutional Networks | DJFR | [TPAMI](https://doi.org/10.1109/TPAMI.2018.2890623) | [Code](https://github.com/Yijunmaverick/DeepJointFilter) | Residual joint filter (journal ext. of DJF) |
| 2018 | CT-guided PET Image Denoising using Deep Neural Network without Prior Training Data | - | [NSS/MIC](https://doi.org/10.1109/NSSMIC.2018.8824397) | - | CT guided PET, Untrained network |
| 2018 | DDRNet: Depth map denoising and refinement for consumer depth cameras using cascaded CNNs | DDRNet | [ECCV](https://link.springer.com/chapter/10.1007/978-3-030-01216-8_10) | [Code](https://github.com/neycyanshi/DDRNet) | RGB guided depth, Cascaded CNN |
| 2018 | MR-Guided Kernel EM Reconstruction for Reduced Dose PET Imaging | KEM | [TRPMS](https://pubmed.ncbi.nlm.nih.gov/29978142/) | - | MRI guided PET, Kernel EM |
| 2017 | Robust color guided depth map restoration | - | [TIP](https://doi.org/10.1109/TIP.2016.2612826) | [Code](https://github.com/wliusjtu/Robust-Color-Guided-Depth-Map-Restoration) | RGB guided depth, Robust guidance |
| 2015 | RGB-D depth-map restoration using smooth depth neighborhood supports | SDN-JBF | [JEI](https://doi.org/10.1117/1.JEI.24.3.033015) | - | RGB guided depth, Joint bilateral filtering |
| 2015 | Mutual-Structure for Joint Filtering | Mutual-Structure | [ICCV](https://doi.org/10.1109/ICCV.2015.389) | [Code](http://www.cse.cuhk.edu.hk/leojia/projects/mutualstructure/) | Mutual structure, joint filtering |
| 2014 | Color-guided depth recovery from RGB-D data using an adaptive autoregressive model | AR Model | [TIP](https://doi.org/10.1109/TIP.2014.2329776) | - | RGB guided depth, AR model |
| 2014 | SAR despeckling guided by an optical image | - | [IGARSS](https://www.iris.unina.it/handle/11588/587229) | - | Optical guided SAR, Cross-modal guidance |
| 2013 | Layer depth denoising and completion for structured-light RGB-D cameras | - | [CVPR](https://doi.org/10.1109/CVPR.2013.157) | - | RGB guided depth, Depth completion |
| 2013 | Cross-Field Joint Image Restoration via Scale Map | Cross-Field | [ICCV](https://doi.org/10.1109/ICCV.2013.194) | [Code](http://www.cse.cuhk.edu.hk/leojia/projects/crossfield) | Scale map, NIR/flash guided |
| 2010 | Guided Image Filtering | GF | [ECCV](https://doi.org/10.1007/978-3-642-15549-9_1) | [Code](https://kaiminghe.github.io/eccv10/) | Edge-preserving, local linear (**Pioneer**) |
| 2009 | Dark Flash Photography | Dark Flash | [TOG](https://doi.org/10.1145/1531326.1531402) | [Project](https://cs.nyu.edu/~fergus/research/dark_flash.html) | NIR/UV multispectral flash |
| 2004 | Digital photography with flash and no-flash image pairs | - | [TOG](https://doi.org/10.1145/1015706.1015777) | - | Flash/no-flash, Classical baseline |
| 2004 | Flash Photography Enhancement via Intrinsic Relighting | - | [TOG](https://doi.org/10.1145/1015706.1015778) | [Project](https://people.csail.mit.edu/fredo/PUBLI/flash/) | Cross/joint bilateral, flash/no-flash |

<a id="LL-papers"></a>
### 🛠️ Guided Low-Light Image Enhancement

| 年份<br>Year | 标题<br>Title | 简称<br>Abbr. | 期刊/会议<br>Published | 代码<br>Code | 关键词<br>Keywords |
| ---- | ------------- | ------------- | ---------------------- | ------------ | ------------------ |
|2026| M2Retinexformer: Multi-Modal Retinexformer for Low-Light Image Enhancement | M2Retinexformer | [arXiv](https://arxiv.org/abs/2605.12556) | - | RGB-depth, Retinex, multi-modal LLIE |
|2025| RT-X Net: RGB-Thermal Cross Attention Network for Low-Light Image Enhancement | RT-X Net | [arXiv](https://arxiv.org/abs/2505.24705) | - | RGB-thermal, cross-attention |
|2025| Low-Light Image Enhancement Using Event-Based Illumination Estimation | Event-based LLIE | [ICCV](https://openaccess.thecvf.com/content/ICCV2025/papers/Sun_Low-Light_Image_Enhancement_Using_Event-Based_Illumination_Estimation_ICCV_2025_paper.pdf) | - | event guidance, illumination estimation |
|2025| Multi-modal Fusion Guided Retinex-based Low-Light Image Enhancement | MFG-Retinex | [ESWA](https://www.sciencedirect.com/science/article/abs/pii/S0957417425022729) | - | infrared/depth guidance, Retinex |
|2025| Depth-Guided Dual-Domain Progressive Low-Light Enhancement for Light Field | DGDDP | [Electronics](https://www.mdpi.com/2079-9292/14/19/3784) | - | depth guidance, light field |
| 2025 | Wakeup-Darkness: When Multimodal Meets Unsupervised Low-Light Image Enhancement | Wakeup-Darkness | [ACM TOMM](https://dl.acm.org/doi/full/10.1145/3711929) | [Code](https://github.com/zhangbaijin/Wakeup-Dakness) | multi-modal, Fine-tuning / Frozen strategy |
|2024| Multimodal Low-light Image Enhancement with Depth Information | Depth-guided LLIE | [ACM MM](https://dl.acm.org/doi/10.1145/3664647.3680741) | - | RGB-depth, low-light enhancement |
|2024| RFFNet: Towards Robust and Flexible Fusion for Low-Light Image Denoising | RFFNet | [ACM MM](https://dl.acm.org/doi/10.1145/3664647.3680675) | - | RGB-NIR/flash guidance, low-light denoising |
|2024| Towards Robust Event-guided Low-Light Image Enhancement: A Large-Scale Real-World Event-Image Dataset and Novel Approach | Event-guided LLIE | [CVPR](https://openaccess.thecvf.com/content/CVPR2024/html/Liang_Towards_Robust_Event-guided_Low-Light_Image_Enhancement_A_Large-Scale_Real-World_Event-Image_CVPR_2024_paper.html) | | event guidance, multi-modal enhancement, real-world dataset |
|2022| Low-Light Imaging via RGB-NIR Fusion with Deep Inconsistency Prior | DarkVisionNet | [AAAI](https://arxiv.org/abs/2303.06834) | - | RGB-NIR fusion, inconsistency prior |
|2022| A deep thermal-guided approach for effective low-light visible image enhancement | Thermal-guided LLIE | [Neurocomputing](https://www.sciencedirect.com/science/article/abs/pii/S0925231222015077) | - | thermal guidance, visible enhancement |
|2020| Low Light Image Enhancement by Multispectral Fusion of RGB and NIR | RGB-NIR Fusion | [ICIP](https://www.semanticscholar.org/paper/ca728dfc78a242cefc2fa3c03789fd48b1caf60c) | - | RGB-NIR, multispectral fusion |


<a id="DB-papers"></a>
### 🛠️ Guided Image Deblurring

| 年份<br>Year | 标题<br>Title | 简称<br>Abbr. | 期刊/会议<br>Published | 代码<br>Code | 关键词<br>Keywords |
| ---- | ------------- | ------------- | ---------------------- | ------------ | ------------------ |
|2026| Gyro-based Deep Video Deblurring | GyroDVD | [CVPR](https://openaccess.thecvf.com/content/CVPR2026/papers/Rim_Gyro-based_Deep_Video_Deblurring_CVPR_2026_paper.pdf) | - | gyro-guided, video deblurring, dataset |
|2025| RED: Robust Event-Guided Motion Deblurring with Modality-Specific Disentangled Representation | RED | [arXiv](https://arxiv.org/abs/2509.05554) | | multi-modal, Event-guided, RPS |
|2025| EBAD-Gaussian: Event-driven Bundle Adjusted Deblur Gaussian Splatting | EBAD-Gaussian | [arXiv](https://arxiv.org/abs/2504.10012) | | multi-modal, Event-guided 3D Deblur, EDI |
|2025| A Novel Method and Dataset for Depth-Guided Image Deblurring from Smartphone LiDAR | ZSLDB | [arXiv](https://arxiv.org/abs/2509.09241) | [Code](https://github.com/diegovalsesia/ZSLDB) | LiDAR depth-guided, diffusion, zero-shot |
|2025| Depth-aware adapters for image deblurring with smartphone LiDAR | - | [Sensors](https://www.mdpi.com/1424-8220/25/21/6786) | - | depth-guided, adapter, continual learning |
|2025| Gyro-based Neural Single Image Deblurring | GyroDeblurNet | [CVPR](https://www.openaccess.thecvf.com/content/CVPR2025/papers/Yang_Gyro-based_Neural_Single_Image_Deblurring_CVPR_2025_paper.pdf) | - | gyro-guided, single image |
|2024| Frequency-aware Event-based Video Deblurring for Real-World Motion Blur | FCFE/ELTP/BTFF | [CVPR](https://openaccess.thecvf.com/content/CVPR2024/html/Kim_Frequency-aware_Event-based_Video_Deblurring_for_Real-World_Motion_Blur_CVPR_2024_paper.html) | [Code](https://sites.google.com/view/fevd-cvpr2024) | multi-modal, event guidance, frequency guidance, video deblurring |
|2024| Motion Aware Event Representation-Driven Image Deblurring | DA/RME/FAF | [ECCV](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/06299.pdf) | [Code](https://github.com/ZhijingS/DA_event_deblur) | multi-modal, recurrent, motion-aware guidance |
|2022| Learning to Deblur Using Light Field Generated and Real Defocus Images | DRBNet | [CVPR](https://openaccess.thecvf.com/content/CVPR2022/html/Ruan_Learning_to_Deblur_Using_Light_Field_Generated_and_Real_Defocus_CVPR_2022_paper.html) | [Code](http://lyruan.com/Projects/DRBNet) | light-field guidance, defocus deblurring, depth cue |
|2020| Learning Event-Driven Video Deblurring and Interpolation | LEDVDI | [ECCV](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/1534_ECCV_2020_paper.php) | | multi-modal, Video Deblurring, Interpolation |
|2019| Bringing a Blurry Frame Alive at High Frame-Rate with an Event Camera | EDI | [CVPR](https://ieeexplore.ieee.org/document/8953329/) | | multi-modal, Frame Interpolation, motion deblurring |

<a id="DH-papers"></a>
### 🛠️ Guided Image Dehazing/Deraining

| 年份<br>Year | 标题<br>Title | 简称<br>Abbr. | 期刊/会议<br>Published | 代码<br>Code | 关键词<br>Keywords |
| ---- | ------------- | ------------- | ---------------------- | ------------ | ------------------ |
|2026| Image dehazing via RGB-FIR multimodal fusion and collaborative learning | RGB-FIR Dehazing | [Pattern Recognition](https://www.sciencedirect.com/science/article/abs/pii/S0031320325008672) | - | RGB-FIR, multimodal dehazing |
|2026| Visible-infrared joint image deraining for harsh rain | VI Deraining | [Pattern Recognition](https://www.sciencedirect.com/science/article/abs/pii/S0031320326002669) | - | visible-infrared, deraining |
|2026| MMDehazeNet: Cross-modality attention with feature correction | MMDehazeNet | [Image and Vision Computing](https://www.sciencedirect.com/science/article/abs/pii/S0262885626000028) | - | visible-infrared, cross-modality attention |
|2026| VI-HAPFNet: Haze-aware prompt fusion for visible-infrared dehazing | VI-HAPFNet | [The Visual Computer](https://link.springer.com/article/10.1007/s00371-026-04512-z) | - | visible-infrared, prompt fusion |
|2025| HDCFN: Infrared-guided Dense Haze Removal in UAVs | HDCFN | [ACM MM](https://dl.acm.org/doi/10.1145/3746027.3754994) | - | infrared-guided dehazing, UAV |
|2025| Enhancing visibility in hazy conditions: multimodal multispectral RGB-NIR | RGB-NIR Dehazing | [JVCI](https://www.sciencedirect.com/science/article/abs/pii/S1047320325000215) | - | RGB-NIR, multispectral dehazing |
|2025| From Events to Clarity: Event-Guided Diffusion for Dehazing | Event-Guided Diffusion | [arXiv](https://arxiv.org/abs/2511.11944) | - | RGB-event, diffusion, dehazing |
|2025| Dehazing of four-channel remote sensing images fused with NIR | Four-channel RS Dehazing | [SPIE](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/13818/138181B/Dehazing-of-four-channel-remote-sensing-images-fused-with-near/10.1117/12.3083059.full) | - | RGB-NIR, remote sensing |
|2024| VIFNet: End-to-end Visible-Infrared Fusion for Dehazing | VIFNet | [Neurocomputing](https://www.sciencedirect.com/science/article/abs/pii/S0925231224008762) | - | visible-infrared fusion, dehazing |
|2024| InfDiff: Visible diffusion prior for infrared image restoration in rainy weather | InfDiff | [Computers & Electrical Engineering](https://www.sciencedirect.com/science/article/abs/pii/S0045790624007419) | - | visible-infrared, rainy-weather restoration |
|2024| Depth-Guided Dehazing Network for Long-Range Aerial Scenes | DGDNet | [Remote Sensing](https://www.mdpi.com/2072-4292/16/12/2081) | - | depth-guided dehazing |
|2023| Thermal Infrared Guided Color Image Dehazing | TIG-Dehazing | [ICIP](https://ieeexplore.ieee.org/document/10222916/) | - | RGB-thermal, dehazing |
|2023| Unsupervised Video Deraining with An Event Camera | Event Video Deraining | [ICCV](https://openaccess.thecvf.com/content/ICCV2023/papers/Wang_Unsupervised_Video_Deraining_with_An_Event_Camera_ICCV_2023_paper.pdf) | - | RGB-event, video deraining |
|2023| EGVD: Event-Guided Video Deraining | EGVD | [IEEE](https://ieeexplore.ieee.org/document/10943258/) | - | RGB-event, video deraining |
|2021| Learning to Dehaze with Polarization | - | [NeurIPS](https://proceedings.neurips.cc/paper/2021/hash/0bbb61d8d7a7f23ebe8c1f3df04a8be8-Abstract.html) | [Code](https://github.com/chuchu123451/polar_dehaze) | polarization-guided, dehazing |
|2017| Colour image dehazing using near-infrared fusion | NIR Fusion Dehazing | [IET IPR](https://ietresearch.onlinelibrary.wiley.com/doi/10.1049/iet-ipr.2017.0192) | - | RGB-NIR, dehazing |
|2013| Near-infrared guided color image dehazing | NIR-guided Dehazing | [ICIP](https://ieeexplore.ieee.org/document/6738487/) | - | RGB-NIR, guided dehazing |


<a id="IC-papers"></a>
### 🛠️ Guided Image Inpainting/ Completion

| **年份&#xA;Year** | **标题&#xA;Title**                                           | **简称&#xA;Abbr.**   | **期刊/会议&#xA;Published**                                  | **代码&#xA;Code**                                            | **关键词&#xA;Keywords**                                      |
| ----------------- | ------------------------------------------------------------ | -------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 2026              | Zero-Shot Depth Completion with Vision-Language Model        | -                    | [CVPR](https://openaccess.thecvf.com/content/CVPR2026/papers/Yan_Zero-Shot_Depth_Completion_with_Vision-Language_Model_CVPR_2026_paper.pdf) | -                                                            | Vision-language model, Sparse depth injection, Zero-shot     |
| 2026              | Dense Metric Depth Completion from Sparse Direct Time-of-Flight Sensors | -                    | [CVPR](https://openaccess.thecvf.com/content/CVPR2026/html/Kim_Dense_Metric_Depth_Completion_from_Sparse_Direct_Time-of-Flight_Sensors_CVPR_2026_paper.html) | [Project / TBA](https://vclab.kaist.ac.kr/cvpr2026p3/)       | Sparse dToF, Dual-branch ViT, Masked joint attention         |
| 2026              | DBFNM: Dual-Branch Fusion Network With Mamba Decoder for Indoor Depth Completion | DBFNM                | [TCSVT](https://doi.org/10.1109/TCSVT.2026.3657718)          | -                                                            | Indoor depth completion, Dual-branch fusion, Mamba           |
| 2026              | Depth Anything with Any Prior                                | Prior Depth Anything | [ICLR](https://proceedings.iclr.cc/paper_files/paper/2026/hash/990a88cb9b87b9d8e9922d6a24aa41f7-Abstract-Conference.html) | [Code](https://github.com/SpatialVision/Prior-Depth-Anything) | Foundation model, Zero-shot, Completion/Super-resolution/Inpainting |
| 2025              | OMNI-DC: Highly Robust Depth Completion with Multiresolution Depth Integration | OMNI-DC              | [ICCV](https://openaccess.thecvf.com/content/ICCV2025/papers/Zuo_OMNI-DC_Highly_Robust_Depth_Completion_with_Multiresolution_Depth_Integration_ICCV_2025_paper.pdf) | [Code](https://github.com/princeton-vl/OMNI-DC)              | Multiresolution integration, Robustness, Zero-shot           |
| 2025              | NLCMR: Indoor Depth Recovery Model With Non-Local Cross-Modality Prior | NLCMR                | [TCI](https://doi.org/10.1109/TCI.2025.3545358)              | [Code](https://github.com/Jackzhang13/NLCMR)                 | Unfolding, Non-local cross-modal prior, Data consistency     |
| 2025              | Deep Unrolled Weighted Graph Laplacian Regularization for Depth Completion | HUGNet               | [IJCV](https://doi.org/10.1007/s11263-024-02188-3)           | -                                                            | Unfolding, Weighted graph Laplacian, Input fidelity          |
| 2025              | HFD-Teacher: High-Frequency Depth Distillation from Depth Foundation Models for Enhanced Depth Completion | HFD-Teacher          | [ICCV](https://openaccess.thecvf.com/content/ICCV2025/papers/Yang_HFD-Teacher_High-Frequency_Depth_Distillation_from_Depth_Foundation_Models_for_Enhanced_ICCV_2025_paper.pdf) | -                                                            | Foundation model distillation, High-frequency details, Wavelets |
| 2025              | Completion as Enhancement: A Degradation-Aware Selective Image Guided Network for Depth Completion | SigNet               | [CVPR](https://openaccess.thecvf.com/content/CVPR2025/papers/Yan_Completion_as_Enhancement_A_Degradation-Aware_Selective_Image_Guided_Network_for_CVPR_2025_paper.pdf) | -                                                            | Degradation-aware enhancement, Selective RGB guidance, Mamba |
| 2025              | Tri-Perspective View Decomposition for Geometry Aware Depth Completion and Super-Resolution | TPVD                 | [TPAMI](https://doi.org/10.1109/TPAMI.2025.3596391)          | -                                                            | 3D geometry, Tri-perspective decomposition, Completion/Super-resolution |
| 2025              | RigNet++: Semantic Assisted Repetitive Image Guided Network for Depth Completion | RigNet++             | [IJCV; manuscript](https://arxiv.org/abs/2309.00655)         | -                                                            | SAM semantic prior, Repetitive guidance, Region-aware propagation |
| 2025              | Learning Inverse Laplacian Pyramid for Progressive Depth Completion | LP-Net               | [arXiv](https://arxiv.org/abs/2502.07289)                    | -                                                            | Laplacian pyramid, Progressive refinement, Selective filtering |
| 2025              | Marigold-DC: Zero-Shot Monocular Depth Completion with Guided Diffusion | Marigold-DC          | [ICCV](https://openaccess.thecvf.com/content/ICCV2025/papers/Viola_Marigold-DC_Zero-Shot_Monocular_Depth_Completion_with_Guided_Diffusion_ICCV_2025_paper.pdf) | [Code](https://github.com/prs-eth/Marigold-DC)               | Guided diffusion, Test-time optimization, Zero-shot          |
| 2025              | Prompting Depth Anything for 4K Resolution Accurate Metric Depth Estimation | PromptDA             | [CVPR](https://openaccess.thecvf.com/content/CVPR2025/papers/Lin_Prompting_Depth_Anything_for_4K_Resolution_Accurate_Metric_Depth_Estimation_CVPR_2025_paper.pdf) | [Code](https://github.com/DepthAnything/PromptDA)            | LiDAR prompting, Foundation model, 4K metric depth           |
| 2025              | Distilling Monocular Foundation Model for Fine-grained Depth Completion | DMD³C                | [CVPR](https://openaccess.thecvf.com/content/CVPR2025/html/Liang_Distilling_Monocular_Foundation_Model_for_Fine-grained_Depth_Completion_CVPR_2025_paper.html) | [Code](https://github.com/Sharpiless/DMD3C)                  | Knowledge distillation, Synthetic LiDAR, Scale/shift-invariant loss |
| 2025              | Efficient Indoor Depth Completion Network Using Mask-adaptive Gated Convolution | MagaConv             | [AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/32390) | [Code](https://github.com/htx0601/MagaConv)                  | Mask-adaptive gated convolution, Bidirectional fusion, Indoor |
| 2025              | DepthFM: Fast Generative Monocular Depth Estimation with Flow Matching | DepthFM              | [AAAI](https://doi.org/10.1609/aaai.v39i3.32330)             | [Code](https://github.com/CompVis/depth-fm)                  | Flow matching, Monocular depth estimation, Depth inpainting  |
| 2024              | DepthLab: From Partial to Complete                           | DepthLab             | [arXiv](https://arxiv.org/abs/2412.18153)                    | [Code](https://github.com/robbyant-research/DepthLab)        | Diffusion prior, Depth inpainting, Scale consistency; revised 2026 |
| 2024              | Learnable differencing center for nighttime depth perception | LDCNet               | [Visual Intelligence](https://doi.org/10.1007/s44267-024-00048-9) | -                                                            | Nighttime depth completion, Illumination, Learnable differencing |
| 2024              | RDFC-GAN: RGB-Depth Fusion CycleGAN for Indoor Depth Completion | RDFC-GAN             | [TPAMI](https://doi.org/10.1109/TPAMI.2024.3388004)          | [Code](https://github.com/midea-ai/RDFC-GAN)                 | RGB-depth fusion, CycleGAN, Normal guidance                  |
| 2024              | Bilateral Propagation Network for Depth Completion           | BP-Net               | [CVPR](https://openaccess.thecvf.com/content/CVPR2024/papers/Tang_Bilateral_Propagation_Network_for_Depth_Completion_CVPR_2024_paper.pdf) | [Code](https://github.com/kakaxi314/BP-Net)                  | Bilateral propagation, Sparse-to-dense, Multiscale refinement |
| 2024              | DySPN: Learning Dynamic Affinity for Image-Guided Depth Completion | DySPN                | [TCSVT](https://doi.org/10.1109/TCSVT.2023.3321668)          | [Code](https://github.com/Kyakaka/DySPN)                     | Dynamic affinity, Adaptive propagation, Diffusion suppression |
| 2024              | A transformer-CNN parallel network for image guided depth completion | TCPNet               | [PR](https://doi.org/10.1016/j.patcog.2024.110305)           | -                                                            | CNN–Transformer, Token correlation, Multiscale CRF           |
| 2023              | CompletionFormer: Depth Completion With Convolutions and Vision Transformers | CompletionFormer     | [CVPR; manuscript](https://arxiv.org/abs/2304.13030)         | [Code](https://github.com/youmi-zym/CompletionFormer)        | CNN–Transformer, Local/global features, Spatial propagation  |
| 2023              | DeepSmooth: Efficient and Smooth Depth Completion            | DeepSmooth           | [CVPR Workshops (VOCVALC)](https://openaccess.thecvf.com/content/CVPR2023W/VOCVALC/html/Krishna_DeepSmooth_Efficient_and_Smooth_Depth_Completion_CVPRW_2023_paper.html) | -                                                            | RGB-D video, Temporal consistency, EfficientNet              |
| 2023              | A Two-stage hybrid CNN-Transformer Network for RGB Guided Indoor Depth Completion | -                    | [ICME](https://doi.org/10.1109/ICME55011.2023.00197)         | [Code](https://github.com/eecoder-dyf/ICME-2023-depth-completion) | Two-stage, Cross-modal Transformer, Indoor                   |
| 2023              | Indoor Depth Recovery Based on Deep Unfolding with Non-Local Prior | DC-NLAR              | [ICCV](https://openaccess.thecvf.com/content/ICCV2023/html/Dai_Indoor_Depth_Recovery_Based_on_Deep_Unfolding_with_Non-Local_Prior_ICCV_2023_paper.html) | -                                                            | Unfolding, Non-local autoregression, Deep image prior        |
| 2023              | PointDC: Unsupervised Semantic Segmentation of 3D Point Clouds via Cross-Modal Distillation and Super-Voxel Clustering | PointDC              | [ICCV; manuscript](https://arxiv.org/abs/2304.08965)         | [Code](https://github.com/SCUT-BIP-Lab/PointDC)              | Related: point-cloud semantic segmentation, Cross-modal distillation, Clustering |
| 2023              | AGG-Net: Attention Guided Gated-Convolutional Network for Depth Image Completion | AGG-Net              | [ICCV](https://openaccess.thecvf.com/content/ICCV2023/papers/Chen_AGG-Net_Attention_Guided_Gated-Convolutional_Network_for_Depth_Image_Completion_ICCV_2023_paper.pdf) | [Code](https://github.com/htx0601/AGG-Net)                   | Attention-guided gated convolution, Skip connection, Indoor  |
| 2022              | RigNet: Repetitive Image Guided Network for Depth Completion | RigNet               | [ECCV; manuscript](https://arxiv.org/abs/2107.13802)         | -                                                            | Repetitive guidance, Dynamic convolution, Hourglass network  |
| 2022              | RGB-Depth Fusion GAN for Indoor Depth Completion             | RDF-GAN              | [CVPR](https://openaccess.thecvf.com/content/CVPR2022/html/Wang_RGB-Depth_Fusion_GAN_for_Indoor_Depth_Completion_CVPR_2022_paper.html) | [Code](https://github.com/midea-ai/RDFC-GAN)                 | RGB-depth fusion, GAN, Indoor depth completion               |
| 2022              | GraphCSPN: Geometry-Aware Depth Completion via Dynamic GCNs  | GraphCSPN            | [ECCV](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136930087.pdf) | [Code](https://github.com/xinliu20/GraphCSPN_ECCV2022)       | Dynamic GCN, 3D geometric constraints, Spatial propagation   |
| 2021              | Adaptive Context-Aware Multi-Modal Network for Depth Completion | ACMNet               | [TIP; manuscript](https://arxiv.org/abs/2008.10833)          | [Code](https://github.com/sshan-zhao/ACMNet)                 | Graph propagation, Context attention, Gated fusion           |
| 2021              | Learning Guided Convolutional Network for Depth Completion   | GuideNet             | [TIP](https://doi.org/10.1109/TIP.2020.3040528)              | [Code](https://github.com/kakaxi314/GuideNet)                | Guided convolution, Dynamic kernels, RGB guidance            |
| 2021              | Decoder Modulation for Indoor Depth Completion               | -                    | [IROS; manuscript](https://arxiv.org/abs/2005.08607)         | [Code](https://github.com/dsenushkin/saic_depth_completion)  | Decoder modulation, SPADE, Semi-dense depth                  |
| 2021              | Algorithm Unrolling: Interpretable, Efficient Deep Learning for Signal and Image Processing | -                    | [IEEE Signal Processing Magazine](https://doi.org/10.1109/MSP.2020.3016905) | -                                                            | Related: survey/tutorial, Algorithm unrolling, Interpretability |
| 2021              | FCFR-Net: Feature Fusion based Coarse-to-Fine Residual Learning for Depth Completion | FCFR-Net             | [AAAI](https://cdn.aaai.org/ojs/16311/16311-13-19805-1-2-20210518.pdf) | -                                                            | Coarse-to-fine, Feature fusion, Residual learning            |
| 2020              | Non-local Spatial Propagation Network for Depth Completion   | NLSPN                | [ECCV; manuscript](https://arxiv.org/abs/2007.10042)         | [Code](https://github.com/zzangjinsun/NLSPN_ECCV20)          | Non-local propagation, Confidence, Learnable affinity        |
| 2020              | A Multi-Scale Guided Cascade Hourglass Network for Depth Completion | MSG-CHN              | [WACV](https://openaccess.thecvf.com/content_WACV_2020/papers/Li_A_Multi-Scale_Guided_Cascade_Hourglass_Network_for_Depth_Completion_WACV_2020_paper.pdf) | [Code](https://github.com/anglixjtu/msg_chn_wacv20)          | Multiscale guidance, Cascade hourglass, Coarse-to-fine       |
| 2020              | Learning Depth with Convolutional Spatial Propagation Network | CSPN                 | [TPAMI](https://doi.org/10.1109/TPAMI.2019.2947374)          | [Code](https://github.com/XinJCheng/CSPN)                    | Convolutional propagation, Learned affinity, Depth completion/Stereo |
| 2019              | Dense Depth Posterior (DDP) From Single Image and Sparse Range | DDP                  | [CVPR](https://openaccess.thecvf.com/content_CVPR_2019/papers/Yang_Dense_Depth_Posterior_DDP_From_Single_Image_and_Sparse_Range_CVPR_2019_paper.pdf) | [TBA](https://github.com/YanchaoYang/Dense-Depth-Posterior)  | Bayesian posterior, Sparse range, Image-conditioned prior    |
| 2019              | Indoor Depth Completion with Boundary Consistency and Self-Attention | -                    | [ICCV Workshops (RLQ)](https://openaccess.thecvf.com/content_ICCVW_2019/papers/RLQ/Huang_Indoor_Depth_Completion_with_Boundary_Consistency_and_Self-Attention_ICCVW_2019_paper.pdf) | [Code](https://github.com/tsunghan-wu/Depth-Completion)      | Boundary consistency, Self-attention, Indoor                 |
| 2018              | Deep Depth Completion of a Single RGB-D Image                | DeepCompletion       | [CVPR; manuscript](https://arxiv.org/abs/1803.09326)         | [Code](https://github.com/yindaz/DeepCompletionRelease)      | Surface normals, Occlusion boundaries, Global optimization   |
| 2018              | Sparse-to-Dense: Depth Prediction from Sparse Depth Samples and a Single Image | Sparse-to-Dense      | [ICRA; manuscript](https://arxiv.org/abs/1709.07492)         | [Code](https://github.com/fangchangma/sparse-to-dense)       | RGB + sparse depth, CNN regression, SLAM densification       |
| 2018              | In Defense of Classical Image Processing: Fast Depth Completion on the CPU | IP-Basic             | [CRV; manuscript](https://arxiv.org/abs/1802.00036)          | [Code](https://github.com/kujason/ip_basic)                  | Classical baseline, Unguided depth completion, Morphology, CPU |



<a id="datasets"></a>
## 🌟 Datasets / 数据集

### 🛠️ Guided Image Super-Resolution
<a id="SR-data"></a>

#### 🧪 Super-Resolution Synthetic
<a id="SR-synthetic-datasets"></a>
| 年份<br>Year | 数据集简称<br>Dataset | 数据集论文<br>Paper | 下载链接<br>Download | 训练集个数<br>Training Samples | 验证集个数<br>Validation Samples | 测试集个数<br>Testing Samples | 关键词<br>Keywords |
| ---- | -------------------- | ------------------ | -------------------- | ------------------------------ | -------------------------------- | ----------------------------- | ------------------ |
| 2024 | Flower | [Hyperspectral Image Super Resolution With Real Unaligned RGB Guidance](https://ieeexplore.ieee.org/abstract/document/10406185) | [download](https://zeqiang-lai.github.io/HSI-RefSR/) | 3243 | / | 100 | HSI-SR |
| 2022 | ARAD1K | [NTIRE 2022 Spectral Recovery Challenge and Data Set](https://openaccess.thecvf.com/content/CVPR2022W/NTIRE/html/Arad_NTIRE_2022_Spectral_Recovery_Challenge_and_Data_Set_CVPRW_2022_paper.html) | [download](https://github.com/boazarad/ARAD_1K) | 850 | 50 | 50 | HSI-SR |
| 2018 | StereoMSI | [PIRM2018 Challenge on Spectral Image Super-Resolution: Dataset and Study](https://openaccess.thecvf.com/content_ECCVW_2018/html/Shoeiby_PIRM2018_Challenge_on_Spectral_Image_Super-Resolution_Dataset_and_Study_ECCVW_2018_paper.html) | [download](https://data.csiro.au/collection/csiro:40743) | 272 | / | 50 | HSI-SR |
| 2024 | VGTSR | [Thermal uav image super-resolution guided by multiple visible cues](https://ieeexplore.ieee.org/abstract/document/10005291) | [download](https://drive.google.com/drive/folders/19WLeBytRQ8IkE0Cf-s6Ejzcg9WJGBltE) | 1025 pairs (exact split unspecified) | / | / | RGBT |
| 2019 | ULB17-VT | [Multimodal sensor fusion in single thermal image super-resolution](https://link.springer.com/chapter/10.1007/978-3-030-21074-8_34) | [download](https://zenodo.org/records/2557535) | 280 | 78 | 46 | RGBT |
| 2012 | NYU v2 |[Indoor segmentation and support inference from RGBD images](https://link.springer.com/chapter/10.1007/978-3-642-33715-4_54) | [download](https://cs.nyu.edu/~fergus/datasets/nyu_depth_v2.html) | 1000 | / | 449 | RGBD |
| 2006 | Middlebury 2006 | [Evaluation of cost functions for stereo matching](https://ieeexplore.ieee.org/abstract/document/4270273) | [download](https://vision.middlebury.edu/stereo/data/scenes2006/ThirdSize/zip-2views/ALL-2views.zip) | / | / | 21 | RGBD |

#### 🧪 Super-Resolution Real-World
<a id="SR-real-world-datasets"></a>

| 年份<br>Year | 数据集简称<br>Dataset | 数据集论文<br>Paper | 下载链接<br>Download | 训练集个数<br>Training Samples | 验证集个数<br>Validation Samples | 测试集个数<br>Testing Samples | 关键词<br>Keywords |
| ---- | -------------------- | ------------------ | -------------------- | ------------------------------ | -------------------------------- | ----------------------------- | ------------------ |
| 2024 | Real-HSI-Fusion | [Hyperspectral Image Super Resolution With Real Unaligned RGB Guidance](https://ieeexplore.ieee.org/abstract/document/10406185) | [download](https://zeqiang-lai.github.io/HSI-RefSR/) | 50 | / | 10 | HSI-SR |
| 2016 | Chikusei | [Airborne hyperspectral data over Chikusei](https://www.researchgate.net/profile/Naoto-Yokoya/publication/304013716_Airborne_hyperspectral_data_over_Chikusei/links/5762f36808ae570d6e15c026/Airborne-hyperspectral-data-over-Chikusei.pdf) | [download](https://www.sal.t.u-tokyo.ac.jp/hyperdata/) | 12 | / | 4 | HSI-SR |
| 2024 | TOFDSR | [Tri-perspective view decomposition for geometry-aware depth completion](https://openaccess.thecvf.com/content/CVPR2024/html/Yan_Tri-Perspective_View_Decomposition_for_Geometry-Aware_Depth_Completion_CVPR_2024_paper.html) | [download](https://yanzq95.github.io/projectpage/TOFDC/index.html) | / | / | 560 | RGBD |
| 2021 | RGB-D-D | [Towards fast and accurate real-world depth superresolution: Benchmark dataset and baseline](https://openaccess.thecvf.com/content/CVPR2021/html/He_Towards_Fast_and_Accurate_Real-World_Depth_Super-Resolution_Benchmark_Dataset_and_CVPR_2021_paper.html?ref=https://githubhelp.com) | [download](https://github.com/lingzhi96/RGB-D-D-Dataset) | 2215 | / | 405 | RGBD |
| 2019 | DIODE | [DIODE: A Dense Indoor and Outdoor DEpth Dataset](https://arxiv.org/abs/1908.00463) | [download](https://diode-dataset.org/) | 8574 indoor + 16884 outdoor | 325 indoor + 446 outdoor | / | RGBD |
| 2023 | M4Raw | [M4Raw: A multi-contrast, multi-repetition, multi-channel MRI k-space dataset for low-field MRI research](https://www.nature.com/articles/s41597-023-02181-4) | [download](https://github.com/mylyu/M4Raw) | 6912 | 1620 | / | MC-MRI |
| 2018 | BraTS 2018 | N/A | [download](https://www.kaggle.com/datasets/sanglequang/brats2018) | 285 | 66 | 191 | MC-MRI |
| 2018 | FastMRI | [fastMRI: An Open Dataset and Benchmarks for Accelerated MRI](https://arxiv.org/abs/1811.08839) | [download](https://cai2r.net/resources/fastmri-dataset/) | 227 | / | 24 | MC-MRI |
| 2008 (approx.) | IXI | N/A | [download](https://brain-development.org/ixi-dataset/) | 600 | / | 50 | MC-MRI |
| 2022 | QB | [Machine Learning in Pansharpening: A Benchmark, from Shallow to Deep Networks](https://ieeexplore.ieee.org/search/searchresult.jsp?action=search&newsearch=true&queryText=%22DOI%22:10.1109%2Fmgrs.2022.3187652&SID=EBSCO:edseee) | [download](https://github.com/liangjiandeng/PanCollection) | 9000 | 1000 | 8 | Pansharpening(4-band satellite data) |
| 2022 | WV4 | [Machine Learning in Pansharpening: A Benchmark, from Shallow to Deep Networks](https://ieeexplore.ieee.org/search/searchresult.jsp?action=search&newsearch=true&queryText=%22DOI%22:10.1109%2Fmgrs.2022.3187652&SID=EBSCO:edseee) | [download](https://github.com/liangjiandeng/PanCollection) | 9000 | 1000 | 9 | Pansharpening(4-band satellite data) |
| 2022 | WV3 | [Machine Learning in Pansharpening: A Benchmark, from Shallow to Deep Networks](https://ieeexplore.ieee.org/search/searchresult.jsp?action=search&newsearch=true&queryText=%22DOI%22:10.1109%2Fmgrs.2022.3187652&SID=EBSCO:edseee) | [download](https://github.com/liangjiandeng/PanCollection) | 9000 | 1000 | 5 | Pansharpening(8-band satellite data) |
| 2022 | WV2 | [Machine Learning in Pansharpening: A Benchmark, from Shallow to Deep Networks](https://ieeexplore.ieee.org/search/searchresult.jsp?action=search&newsearch=true&queryText=%22DOI%22:10.1109%2Fmgrs.2022.3187652&SID=EBSCO:edseee) | [download](https://github.com/liangjiandeng/PanCollection) | 14496 | 1611 | 13 | Pansharpening(8-band satellite data) |
| 2017 | GF-2 | [Dataset of GF-2 satellite images (2017)](https://data.tpdc.ac.cn/zh-hans/data/1b2ebe66-8389-4c9f-9756-1b29d83f851f/) | [download](https://data.scsio.ac.cn/metaData-detail/1455780551812595713) | 19809 | / | 20 | Pansharpening(4-band satellite data) |

### 🛠️ Guided Image Denoising
<a id="DN-data"></a>

#### 🧪 Denoising Synthetic
<a id="DN-synthetic-datasets"></a>

| 年份<br>Year | 数据集简称<br>Dataset | 数据集论文<br>Paper | 下载链接<br>Download | 样本个数<br>Sample Count | 关键词<br>Keywords |
| ---- | -------------------- | ------------------ | -------------------- | ----------------------- | ------------------ |
| 2026 | DaCRA | [M2Diff: Multi-Modality Multi-Task Enhanced Diffusion Model for MRI-Guided Low-Dose PET Enhancement](https://doi.org/10.1109/TRPMS.2026.3672075) | [download](https://doi.org/10.18112/openneuro.ds003397.v1.1.1) | 15 adult subjects | MRI-guided PET |
| 2026 | ADNI | [M2Diff: Multi-Modality Multi-Task Enhanced Diffusion Model for MRI-Guided Low-Dose PET Enhancement](https://doi.org/10.1109/TRPMS.2026.3672075) | [download](https://adni.loni.usc.edu/data-samples/adni-data/) | longitudinal PET/MRI cohort; official portal does not expose a fixed sample count | MRI-guided PET |
| 2026 | WeatherKITTI | [Adaptive Cross-Modal Denoising: Enhancing LiDAR-Camera Fusion Perception in Adverse Circumstances](https://doi.org/10.3390/s26020408) | [download](https://wangjiyuan9.github.io/project/weatherkitti/) | 697 test images; full Eigen train/val/test release available | LiDAR-camera |
| 2026 | UDPET | [MGTP: Multi-Granularity Textual Prompts for Low-Dose Brain PET Image Denoising via Adversarial Diffusion Model](https://doi.org/10.1109/JBHI.2025.3625572) | [download](https://udpet-challenge.github.io/) | 156 subjects: 120 for training, 8 for validation, 28 for testing | Text-guided PET |
| 2025 | SYSUCC PET/MR | [Multimodal feature-guided diffusion model for low-count PET image denoising](https://aapm.onlinelibrary.wiley.com/doi/abs/10.1002/mp.17764) | / | 71 patients: 65 for training, 6 for testing | MRI-guided PET |
| 2025 | UCMerced | [GCOANet: A gradient consistency constraints semi-supervised network for optical image-assisted SAR despeckling](https://www.sciencedirect.com/science/article/pii/S1569843225003243) | [download](https://vision.ucmerced.edu/datasets/) | 2100 optical images across 21 classes | Optical-guided SAR |
| 2024 | Florence | [Pan-Denoising: Guided Hyperspectral Image Denoising via Weighted Represent Coefficient Total Variation](https://doi.org/10.1109/TGRS.2024.3450888) | [download](https://www.researchgate.net/publication/383825518_data_PWRCTVzip) | 1 hyperspectral scene | PAN-guided HSI |
| 2024 | Milan | [Pan-Denoising: Guided Hyperspectral Image Denoising via Weighted Represent Coefficient Total Variation](https://doi.org/10.1109/TGRS.2024.3450888) | [download](https://www.researchgate.net/publication/383825518_data_PWRCTVzip) | 1 hyperspectral scene | PAN-guided HSI |
| 2022 | ToF-FT3D | [Self-Supervised Learning for RGB-Guided Depth Enhancement by Exploiting the Dependency Between RGB and Depth](https://doi.org/10.1109/TIP.2022.3226419) | [download](https://github.com/denyingmxd/selftof) | synthetic ToF/RGB training set; official releases do not report a fixed split size | RGB-guided depth |
| 2022 | Neck PET/MRI | [Spatial adaptive and transformer fusion network (STFNet) for low-count PET blind denoising with MRI](https://pubmed.ncbi.nlm.nih.gov/34796526/) | [request: Zhanli Hu](mailto:zl.hu@siat.ac.cn)<br>[request: Xu Zhang](mailto:zhangx2@sysucc.org.cn) | 70 patients total; 50/10/10 train/val/test per fold | MRI-guided PET |
| 2020 | BrainWeb 20 | [Micro-Networks for Robust MR-Guided Low Count PET Imaging](https://doi.org/10.1109/TRPMS.2020.2986414) | [download](https://brainweb.bic.mni.mcgill.ca/brainweb/anatomic_normal_20.html) | 20 normal-brain subjects | MRI-guided PET |
| 2020 | BrainWeb multimodal 20 | [Micro-Networks for Robust MR-Guided Low Count PET Imaging](https://doi.org/10.1109/TRPMS.2020.2986414) | [download](https://doi.org/10.5281/zenodo.3269888) | 20 derived multimodal brain models | MRI-guided PET |
| 2020 | FDG PET/MPRAGE | [Micro-Networks for Robust MR-Guided Low Count PET Imaging](https://doi.org/10.1109/TRPMS.2020.2986414) | / | 10 clinical PET/MR scans | MRI-guided PET |
| 2019 | Flickr1024 | [Flickr1024: A Large-Scale Dataset for Stereo Image Super-Resolution](https://openaccess.thecvf.com/content_ICCVW_2019/html/LCI/Wang_Flickr1024_A_Large-Scale_Dataset_for_Stereo_Image_Super-Resolution_ICCVW_2019_paper.html) | [download](https://yingqianwang.github.io/Flickr1024/) | 1024 stereo pairs: 800/112/112 train/val/test | Cross-spectral stereo |
| 2018 | BrainWeb PET-MR | [MR-Guided Kernel EM Reconstruction for Reduced Dose PET Imaging](https://pubmed.ncbi.nlm.nih.gov/29978142/) | [download](https://brainweb.bic.mni.mcgill.ca/brainweb/) | 1 simulated 3D phantom + 1 simulated 2D phantom | MRI-guided PET |
| 2018 | FDG PET-MR | [MR-Guided Kernel EM Reconstruction for Reduced Dose PET Imaging](https://pubmed.ncbi.nlm.nih.gov/29978142/) | [download](https://doi.org/10.5281/zenodo.1041423) | 1 simultaneous PET/MR scan | MRI-guided PET |
| 2018 | PittsStereo-RGBNIR | [Deep Material-aware Cross-spectral Stereo Matching](https://www.cs.cmu.edu/~ILIM/projects/AA/RGBNIRStereo/index.html) | [download](https://platformpgh.cs.cmu.edu/tzhi/RGBNIRStereoRelease/rgbnir_stereo/) | 42000 stereo pairs: 40000 for training, 2000 for testing | Cross-spectral stereo |
| 2015 | KITTI Stereo 2015 | [Object Scene Flow for Autonomous Vehicles](https://www.cvlibs.net/publications/Geiger2015CVPR.pdf) | [download](https://www.cvlibs.net/datasets/kitti/eval_scene_flow.php?benchmark=stereo) | 200 training scenes + 200 test scenes | Cross-spectral stereo |
| 2013 | ToFMark | [ToFMark benchmark](https://www.tugraz.at/institute/icg/research/team-bischof/robot-vision/research/time-of-flight-imaging/) | [download](https://www.tugraz.at/institute/icg/research/team-bischof/robot-vision/research/time-of-flight-imaging/) | 3 benchmark scenes | RGB-guided depth |
| 2012 | NYU v2 | [Indoor segmentation and support inference from RGBD images](https://link.springer.com/chapter/10.1007/978-3-642-33715-4_54) | [download](https://cs.nyu.edu/~fergus/datasets/nyu_depth_v2.html) | 1449 RGB-D frames: 1000 for training, 449 for testing | RGB-guided depth |
| 2011 | RNS | [RGB-NIR Scene Dataset](https://www.epfl.ch/labs/ivrl/research/downloads/rgb-nir-scene-dataset/) | [download](https://www.epfl.ch/labs/ivrl/research/downloads/rgb-nir-scene-dataset/) | 477 aligned RGB-NIR pairs | RGB/NIR |
| 2005-2014 | Middlebury | [Middlebury Stereo Benchmark](https://vision.middlebury.edu/stereo/) | [download](https://vision.middlebury.edu/stereo/) | benchmark subsets; e.g. 26 stereo scenes in some denoising papers | RGB-guided depth |

#### 🧪 Denoising Real-World
<a id="DN-real-world-datasets"></a>

| 年份<br>Year | 数据集简称<br>Dataset | 数据集论文<br>Paper | 下载链接<br>Download | 样本个数<br>Sample Count | 关键词<br>Keywords |
| ---- | -------------------- | ------------------ | -------------------- | ----------------------- | ------------------ |
| 2025 | GF3-GE / S1-S2 patches | [GCOANet: A gradient consistency constraints semi-supervised network for optical image-assisted SAR despeckling](https://www.sciencedirect.com/science/article/pii/S1569843225003243) | [GF-3](https://data.cresda.cn/)<br>[Sentinel-1](https://dataspace.copernicus.eu/data-collections/sentinel-data/sentinel-1)<br>[Sentinel-2](https://dataspace.copernicus.eu/explore-data/data-collections/sentinel-data/sentinel-2)<br>[Google Earth](https://www.google.com/earth/)<br>| 30000 paired optical/SAR patches | Optical-guided SAR |
| 2024 | LGCNet flash/no-flash | [Laplacian Gradient Consistency Prior for Flash Guided Non-Flash Image Denoising](https://doi.org/10.1109/TIP.2024.3489275) | [download](https://drive.google.com/drive/folders/10NQONsMlIeA72LK70mUoE1roRfOvbvbJ?usp=sharing) | testing-only real flash/no-flash split; public release does not state the exact pair count | Flash-guided RGB |
| 2024 | Beijing | [Pan-Denoising: Guided Hyperspectral Image Denoising via Weighted Represent Coefficient Total Variation](https://doi.org/10.1109/TGRS.2024.3450888) | [download](https://www.researchgate.net/publication/383825518_data_PWRCTVzip) | 1 hyperspectral scene | PAN-guided HSI |
| 2024 | Yulin | [Pan-Denoising: Guided Hyperspectral Image Denoising via Weighted Represent Coefficient Total Variation](https://doi.org/10.1109/TGRS.2024.3450888) | [download](https://www.researchgate.net/publication/383825518_data_PWRCTVzip) | 1 hyperspectral scene | PAN-guided HSI |
| 2023 | FAID | [Robust image denoising of no-flash images guided by consistent flash images](https://ojs.aaai.org/index.php/AAAI/article/view/25291) | [download](https://yaksoy.github.io/faid/) | 256 FAID pairs for testing | Flash-guided RGB |
| 2019 | DPD | [DeepFlash: Turning a flash selfie into a studio portrait](https://www.sciencedirect.com/science/article/pii/S0923596519301498) | [download](https://yaksoy.github.io/efaid/) | 429 portrait pairs: 409 for training, 20 for testing | Flash-guided RGB |
| 2019 | MID | [A dataset of multi-illumination images in the wild](https://openaccess.thecvf.com/content_ICCV_2019/html/Murmann_A_Dataset_of_Multi-Illumination_Images_in_the_Wild_ICCV_2019_paper.html) | [download](https://projects.csail.mit.edu/illumination/) | 1014 multi-illumination scenes: 984 for training, 30 for testing | Flash-guided RGB |
| 2019 | Dark Flash Stereo | [Stereoscopic Dark Flash for Low-light Photography](https://research.snap.com/publications/stereoscopic-dark-flash-for-low-light-photography.html) | [download](https://research.snap.com/publications/stereoscopic-dark-flash-for-low-light-photography.html) | project examples only; no fixed public benchmark size reported | Cross-spectral stereo |
| 2018 | FAID | [A dataset of flash and ambient illumination pairs from the crowd](https://openaccess.thecvf.com/content_ECCV_2018/html/Yagiz_Aksoy_A_Dataset_of_ECCV_2018_paper.html) | [download](https://yaksoy.github.io/faid/) | 2775 aligned flash/ambient pairs | Flash-guided RGB |
| 2018 | 68Ga-PRGD2 PET/CT | [CT-guided PET Image Denoising using Deep Neural Network without Prior Training Data](https://doi.org/10.1109/NSSMIC.2018.8824397) | / | 10 patient PET/CT studies | CT-guided PET |
| 2018 | DDRNet RGB-D subset | [DDRNet: Depth map denoising and refinement for consumer depth cameras using cascaded CNNs](https://link.springer.com/chapter/10.1007/978-3-030-01216-8_10) | [download](https://github.com/neycyanshi/DDRNet/tree/master/dataset) | 22 public RGB-D frames in the repo subset | RGB-guided depth |
| 2014 | COSMO-SkyMed / Maxar | [SAR despeckling guided by an optical image](https://www.iris.unina.it/handle/11588/587229) | [COSMO-SkyMed](https://portal.cosmo-skymed.it)<br>[ASI](https://www.asi.it/bandi_e_concorsi/open-call-for-science-data-utilization-of-the-cosmo-skymed-mission-first-and-second-generation-english-version/)<br>[e-GEOS](https://www.e-geos.it/)<br>[WorldView](https://vantor.com/product/worldview/access-programs/)<br>[USGS GeoEye-1](https://www.usgs.gov/centers/eros/science/usgs-eros-archive-commercial-satellites-cdp-imagery-geoeye-1) | 1 registered optical/SAR pair + 11 SAR scenes | Optical-guided SAR |
| 2004 | Flash/no-flash pairs | [Digital photography with flash and no-flash image pairs](https://doi.org/10.1145/1015706.1015777) | [official access](https://hhoppe.com/proj/flash/) | project examples + full-resolution TIFF package; exact pair count not reported | Flash-guided RGB |


### 🛠️ Lowlight
<a id="LL-datasets"></a>

| 年份<br>Year | 数据集简称<br>Dataset | 数据集论文<br>Paper | 下载链接<br>Download | 训练集个数<br>Training Samples | 验证集个数<br>Validation Samples | 测试集个数<br>Testing Samples | 关键词<br>Keywords |
| ---- | -------------------- | ------------------ | ------------------------- | ----------------------------------- | --------------------------------------- | --------------------------------- | ------------------ |
| 2024 | LED | [Multimodal Low-light Image Enhancement with Depth Information](https://dl.acm.org/doi/10.1145/3664647.3680741) | / | / | / | / | RGB-depth lowlight |
| 2022 | M3FD | [Target-aware Dual Adversarial Learning and a Multi-scenario Multi-modality Benchmark to Fuse Infrared and Visible for Object Detection](https://openaccess.thecvf.com/content/CVPR2022/html/Liu_Target-Aware_Dual_Adversarial_Learning_and_a_Multi-Scenario_Multi-Modality_Benchmark_To_CVPR_2022_paper.html) | [download](https://github.com/JinyuanLiu-CV/TarDAL) | / | / | 4200 pairs | Lowlight |
| 2022 | Dark Vision Dataset | [Low-Light Imaging via RGB-NIR Fusion with Deep Inconsistency Prior](https://arxiv.org/abs/2303.06834) | / | / | / | / | RGB-NIR lowlight |
| 2021 | LLVIP | [LLVIP: A Visible-infrared Paired Dataset for Low-light Vision](https://openaccess.thecvf.com/content/ICCV2021W/LLVIP/html/Jia_LLVIP_A_Visible-Infrared_Paired_Dataset_for_Low-Light_Vision_ICCVW_2021_paper.html) | [download](https://github.com/bupt-ai-cz/LLVIP) | 12025 pairs | / | 3463 pairs | Lowlight |
| / | ARRI RGB/NIR | RGB/NIR paired evaluation data | / | / | / | / | RGB-NIR lowlight |

### 🛠️ Deblurring
<a id="DB-datasets"></a>

| 年份<br>Year | 数据集简称<br>Dataset | 数据集论文<br>Paper | 下载链接<br>Download | 训练集个数<br>Training Samples | 验证集个数<br>Validation Samples | 测试集个数<br>Testing Samples | 关键词<br>Keywords |
| ---- | -------------------- | ------------------ | ------------------------- | ----------------------------------- | --------------------------------------- | --------------------------------- | ------------------ |
| 2024 | REVD | [Frequency-aware Event-based Video Deblurring for Real-World Motion Blur](https://openaccess.thecvf.com/content/CVPR2024/papers/Kim_Frequency-aware_Event-based_Video_Deblurring_for_Real-World_Motion_Blur_CVPR_2024_paper.pdf) | - | 13 sequences | / | 8 sequences | Deblurring |
| 2020 | RealBlur-J | [Real-World Blind Motion Deblurring](https://openaccess.thecvf.com/content_CVPR_2020/html/Rim_Real-World_Blind_Motion_Deblurring_CVPR_2020_paper.html) | [download](https://github.com/rimchang/RealBlur) | 3758 | / | 980 | Deblurring |
| 2020 | RealBlur-R | [Real-World Blind Motion Deblurring](https://openaccess.thecvf.com/content_CVPR_2020/html/Rim_Real-World_Blind_Motion_Deblurring_CVPR_2020_paper.html) | [download](https://github.com/rimchang/RealBlur) | 3758 | / | 980 | Deblurring |
| 2019 | REDS | [NTIRE 2019 Challenge on Video Deblurring and Super-Resolution: Dataset and Study](https://openaccess.thecvf.com/content_CVPRW_2019/html/NTIRE/Nah_NTIRE_2019_Challenge_on_Video_Deblurring_and_Super-Resolution_Dataset_and_CVPRW_2019_paper.html) | [download](https://seungjunnah.github.io/Datasets/reds) | 240 clips | 30 clips | 30 clips | Deblurring(video) |
| 2019 | HIDE | [Human-Aware Motion Deblurring](https://openaccess.thecvf.com/content_ICCV_2019/html/Shen_Human-Aware_Motion_Deblurring_ICCV_2019_paper.html) | [download](https://github.com/joansj/DeepDeblur_release) | / | / | 2025 | Deblurring |
| 2019 | DPDD | [Defocus Deblurring Using Dual-Pixel Data](https://openaccess.thecvf.com/content_ICCV_2019/html/Abuolaim_Defocus_Deblurring_Using_Dual-Pixel_Data_ICCV_2019_paper.html) | [download](https://github.com/Abdullah-Abuolaim/defocus-deblurring-dual-pixel) | 350 pairs | 76 pairs | 74 pairs | Deblurring |
| 2017 | GoPro Dataset | [Deep  multi-scale convolutional neural network for dynamic scene deblurring](https://openaccess.thecvf.com/content_cvpr_2017/html/Nah_Deep_Multi-Scale_Convolutional_CVPR_2017_paper.html) | [download](https://drive.google.com/file/d/1y4wvPdOG3mojpFCHTqLgriexhbjoWVkK/view?pli=1) | 2103 | / | 1111 | Deblurring |
| 2017 | DVD | [Deep Video Deblurring for Hand-held Cameras](https://openaccess.thecvf.com/content_cvpr_2017/html/Su_Deep_Video_Deblurring_CVPR_2017_paper.html) | [download](https://github.com/shuochsu/DeepVideoDeblurring) | 5708 frames | / | 1000 frames | Deblurring |
| 2016 | Lai et al. Blur Dataset | [A Comparative Study for Single Image Blind Deblurring](https://openaccess.thecvf.com/content_cvpr_2016/html/Lai_A_Comparative_Study_CVPR_2016_paper.html) | [download](https://github.com/phoenix104104/blur_dataset) | / | / | 100 | Deblurring |

### 🛠️ Dehazing/Deraining
<a id="DH-datasets"></a>

| 年份<br>Year | 数据集简称<br>Dataset | 数据集论文<br>Paper | 下载链接<br>Download | 训练集个数<br>Training Samples | 验证集个数<br>Validation Samples | 测试集个数<br>Testing Samples | 关键词<br>Keywords |
| ---- | -------------------- | ------------------ | -------------------- | ------------------------------ | -------------------------------- | ----------------------------- | ------------------ |
| 2021 | Rain13K | [Multi-Stage Progressive Image Restoration](https://openaccess.thecvf.com/content/CVPR2021/html/Zamir_Multi-Stage_Progressive_Image_Restoration_CVPR_2021_paper.html) | [download](https://github.com/swz30/MPRNet) | 13712 | / | multiple test sets | Dehazing/Deraining |
| 2020 | NH-HAZE | [NTIRE 2020 NonHomogeneous Dehazing Challenge Dataset](https://data.vision.ee.ethz.ch/cvl/ntire20/nh-haze/) | [download](https://data.vision.ee.ethz.ch/cvl/ntire20/nh-haze/) | 45 | 5 | 5 | Dehazing/Deraining |
| 2019 | RESIDE | [RESIDE: A Benchmark for Single Image Dehazing](https://ieeexplore.ieee.org/document/8451944) | [download](https://sites.google.com/view/reside-dehaze-datasets) | 13990 ITS + 313950 OTS | / | 500 indoor SOTS + 500 outdoor SOTS + 4322 RTTS | Dehazing/Deraining |
| 2019 | Dense-Haze | [Dense-Haze: A Benchmark for Image Dehazing with Dense-Haze and Haze-Free Images](https://data.vision.ee.ethz.ch/cvl/ntire19/dense-haze/) | [download](https://data.vision.ee.ethz.ch/cvl/ntire19/dense-haze/) | 45 | 5 | 5 | Dehazing/Deraining |
| 2019 | SPA-Data | [Spatial Attentive Single-Image Deraining with a High Quality Real Rain Dataset](https://openaccess.thecvf.com/content_CVPR_2019/html/Wang_Spatial_Attentive_Single-Image_Deraining_With_a_High_Quality_Real_Rain_Dataset_CVPR_2019_paper.html) | [download](https://github.com/stevewongv/SPANet) | 638492 | / | 1000 | Dehazing/Deraining |
| 2018 | I-HAZE | [I-HAZE: A Dehazing Benchmark with Real Hazy and Haze-Free Indoor Images](https://data.vision.ee.ethz.ch/cvl/ntire18/i-haze/) | [download](https://data.vision.ee.ethz.ch/cvl/ntire18/i-haze/) | 25 | 5 | 5 | Dehazing/Deraining |
| 2018 | O-HAZE | [O-HAZE: A Dehazing Benchmark with Real Hazy and Haze-Free Outdoor Images](https://data.vision.ee.ethz.ch/cvl/ntire18/o-haze/) | [download](https://data.vision.ee.ethz.ch/cvl/ntire18/o-haze/) | 35 | 5 | 5 | Dehazing/Deraining |
| 2018 | HazeRD | [HazeRD: An Outdoor Scene Dataset and Benchmark for Single Image Dehazing](https://labsites.rochester.edu/gsharma/research/computer-vision/hazerd/) | [download](https://labsites.rochester.edu/gsharma/research/computer-vision/hazerd/) | / | / | 75 scenes | Dehazing/Deraining |
| 2017 | Rain100L | [Removing Rain from Single Images via a Deep Detail Network](https://openaccess.thecvf.com/content_cvpr_2017/html/Fu_Removing_Rain_From_CVPR_2017_paper.html) | [download](https://xueyangfu.github.io/projects/cvpr2017.html) | 200 | / | 100 | Dehazing/Deraining |
| 2017 | Rain100H | [Removing Rain from Single Images via a Deep Detail Network](https://openaccess.thecvf.com/content_cvpr_2017/html/Fu_Removing_Rain_From_CVPR_2017_paper.html) | [download](https://xueyangfu.github.io/projects/cvpr2017.html) | 1800 | / | 100 | Dehazing/Deraining |
| 2017 | Rain800 | [Image De-raining Using a Conditional Generative Adversarial Network](https://arxiv.org/abs/1701.05957) | [download](https://github.com/hezhangsprinter/ID-CGAN) | 700 | / | 100 | Dehazing/Deraining |
| 2017 | Rain1400 | [Clearing the Skies: A Deep Network Architecture for Single-Image Rain Removal](https://ieeexplore.ieee.org/document/8067575) | [download](https://xueyangfu.github.io/projects/tip2017.html) | 12600 | / | 1400 | Dehazing/Deraining |
| 2016 | D-HAZY | [D-HAZY: A Dataset to Evaluate Quantitatively Dehazing Algorithms](https://ieeexplore.ieee.org/document/7532754) | [download](https://ancuti.meo.etc.upt.ro/D_Hazzy_ICIP2016/) | / | / | 1449 | Dehazing/Deraining |


### 🛠️ Guided Image Inpainting/ Completion

<a id="IC-datasets"></a>


#### 🧪 Depth Completion Benchmarks / 深度补全常用基准

| 年份<br>Year | 数据集简称<br>Dataset  | 数据集论文<br>Paper                                          | 下载链接<br>Download                                         | 样本个数<br>Sample Count                                     | 关键词<br>Keywords                                           |
| ------------ | ---------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 2024         | TOFDC                  | [Tri-Perspective View Decomposition for Geometry-Aware Depth Completion](https://openaccess.thecvf.com/content/CVPR2024/papers/Yan_Tri-Perspective_View_Decomposition_for_Geometry-Aware_Depth_Completion_CVPR_2024_paper.pdf) (CVPR) | [download](https://yanzq95.github.io/projectpage/TOFDC/index.html) | 10000 training + 560 test pairs; 512 × 384                   | Real-world ToF completion, Smartphone RGB, Helios ground truth |
| 2021         | DIML                   | [A Large RGB-D Dataset for Semi-supervised Monocular Depth Estimation](https://arxiv.org/abs/1904.10230)<br>Journal version: [Deep monocular depth estimation leveraging a large-scale outdoor stereo dataset](https://doi.org/10.1016/j.eswa.2021.114877) (ESWA; preprint 2019) | [download](https://dimlrgbd.github.io/)                      | 200+ indoor/outdoor scenes; official sample subsets: 1500 training + 500 test images for indoor, and 1500 + 500 for outdoor; completion papers may use different filtered subsets | RGB-D, Indoor completion subsets, Stereo depth               |
| 2020         | VOID                   | [Unsupervised Depth Completion from Visual Inertial Odometry](https://arxiv.org/abs/1905.08616) (RA-L / ICRA) | [download](https://github.com/alexklwong/void-dataset)       | 56 sequences: 48 training (~47K frames), 8 testing (800 selected test frames); 150 / 500 / 1500 sparse points per frame | Visual-inertial depth, Sparse-to-dense, Indoor/outdoor       |
| 2017         | KITTI Depth Completion | [Sparsity Invariant CNNs](https://www.cvlibs.net/publications/Uhrig2017THREEDV.pdf) (3DV) | [download / benchmark](https://www.cvlibs.net/datasets/kitti/eval_depth.php?benchmark=depth_completion) | 85898 training; 6852 validation (1000 selected validation); 1000 test frames ([protocol](https://github.com/wvangansbeke/Sparse-Depth-Completion)) | Outdoor driving, RGB + LiDAR, Semi-dense ground truth        |
| 2017         | Matterport3D           | [Matterport3D: Learning from RGB-D Data in Indoor Environments](https://niessner.github.io/Matterport/) (3DV) | [request / download](https://github.com/niessner/Matterport) | 90 building-scale scenes; 10800 panoramas / 194400 RGB-D images; completion subsets depend on rendering and filtering protocol | Indoor RGB-D, Large holes, Mesh-derived supervision          |
| 2017         | ScanNet                | [ScanNet: Richly-annotated 3D Reconstructions of Indoor Scenes](https://arxiv.org/abs/1702.04405) (CVPR) | [request / download](https://github.com/ScanNet/ScanNet)     | Original paper: 2.5M views in 1513 scans; frame sampling and completion splits depend on protocol | Indoor RGB-D video, Reconstruction, Missing depth            |
| 2015         | SUN RGB-D              | [SUN RGB-D: A RGB-D Scene Understanding Benchmark Suite](https://openaccess.thecvf.com/content_cvpr_2015/html/Song_SUN_RGB-D_A_2015_CVPR_paper.html) (CVPR) | [download](https://rgbd.cs.princeton.edu/)                   | 10335 RGB-D images; original split: 5285 training / 5050 evaluation; depth completion often uses filtered subsets | Indoor completion, Multiple RGB-D sensors, Scene understanding |
| 2012         | NYU Depth V2 / NYUv2   | [Indoor Segmentation and Support Inference from RGBD Images](https://link.springer.com/chapter/10.1007/978-3-642-33715-4_54) (ECCV) | [download](https://cs.nyu.edu/~fergus/datasets/nyu_depth_v2.html) | 464 scenes; 1449 labeled pairs (795 training / 654 test), plus 407024 raw frames; completion commonly samples training frames from raw sequences and evaluates on 654 images | Indoor RGB-D, Kinect, Random sparse-depth sampling           |

#### 🧪 Additional Real-World / Synthetic Data / 辅助真实与合成数据

| 年份<br>Year | 数据集简称<br>Dataset | 数据集论文<br>Paper                                          | 下载链接<br>Download                                         | 样本个数<br>Sample Count                                     | 关键词<br>Keywords                                           |
| ------------ | --------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 2023         | ScanNet++             | [ScanNet++: A High-Fidelity Dataset of 3D Indoor Scenes](https://arxiv.org/abs/2308.11417) (ICCV) | [request / download](https://scannetpp.mlsg.cit.tum.de/scannetpp/) | v2 (2024 release): 1000+ scenes; use version-specific official splits | Indoor RGB-D, iPhone LiDAR, Laser-scan reference, Generalization |
| 2021         | ARKitScenes           | [ARKitScenes: A Diverse Real-World Dataset for 3D Indoor Scene Understanding Using Mobile RGB-D Data](https://github.com/apple-aiml-research/ARKitScenes) | [download](https://github.com/apple-aiml-research/ARKitScenes/blob/main/DATA.md) | Full collection: 5047 captures; depth-upsampling subset has separate Training / Validation lists | Mobile RGB-D, Low-resolution LiDAR, Faro ground truth, Depth enhancement |
| 2021         | Hypersim              | [Hypersim: A Photorealistic Synthetic Dataset for Holistic Indoor Scene Understanding](https://github.com/apple-aiml-research/ml-hypersim) (ICCV) | [download](https://github.com/apple-aiml-research/ml-hypersim) | 77400 images / 461 indoor scenes; official split metadata available | Synthetic indoor RGB-D, Dense ground truth, Pretraining      |
| 2020         | Virtual KITTI 2       | [Virtual KITTI 2](https://arxiv.org/abs/2001.10773)          | [download](https://europe.naverlabs.com/proxy-virtual-worlds-vkitti-2/) | 5 base sequences with weather, lighting and viewpoint variants; no universal depth-completion split | Synthetic outdoor, Dense depth, Sparse-input simulation      |
| 2019         | DIODE                 | [DIODE: A Dense Indoor and Outdoor DEpth Dataset](https://arxiv.org/abs/1908.00463) | [download](https://diode-dataset.org/)                       | 25458 training / 771 validation images publicly released; website also lists 1629 test images | Indoor/outdoor RGB-D, Laser scanner, Cross-domain evaluation |
| 2017         | ETH3D                 | [A Multi-View Stereo Benchmark with High-Resolution Images and Multi-Camera Videos](https://eth3d.ethz.ch/overview) (CVPR) | [download](https://eth3d.ethz.ch/overview)                   | High-resolution multi-view benchmark: 13 training / 12 test scenes; completion evaluation uses protocol-specific views | Multi-view stereo source data, Laser ground truth, Generalization |
| 2017         | SceneNet RGB-D        | [SceneNet RGB-D: 5M Photorealistic Images of Synthetic Indoor Trajectories with Ground Truth](https://arxiv.org/abs/1612.05079) (ICCV) | [download](https://robotvault.bitbucket.io/scenenet-rgbd.html) | 5M rendered RGB-D images; trajectory-based data organization | Synthetic indoor, Dense depth, Video, Pretraining            |



---

## ⭐ Star History / Cite US

⭐ If this work is helpful to you, please help star this repo. Thanks! 🤗

![visitors](https://visitor-badge.laobi.icu/badge?page_id=JingyiXu404.Awesome-Guided-Image-Restoration)
