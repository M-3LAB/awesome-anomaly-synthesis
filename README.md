# awesome-anomaly-synthesis

We discuss anomaly synthesis methods in detail. Welcome to read our paper and make comments.

A Survey on Industrial Anomalies Synthesis [[paper]](https://arxiv.org/abs/2502.16412)

🔥🔥🔥 Contributions to our repository are welcome. Feel free to categorize the papers.

## Taxonomy of Industrial Image Anomaly Synthesis
![Taxonomy](https://github.com/M-3LAB/awesome-anomaly-synthesis/blob/main/paper_tree.png)

## Hand-Crafted Model
### Self-Contained
+ Cutpaste: Self-supervised learning for anomaly detection and localization [[CVPR 2021]](http://arxiv.org/pdf/2104.04015)[[unofficial code]](https://github.com/Runinho/pytorch-cutpaste)
+ Self-supervised learning for anomaly detection with dynamic local augmentation [[IEEE Access 2021]](https://ieeexplore.ieee.org/ielx7/6287639/6514899/09597511.pdf)
+ A Study on Data Augmentation Techniques for Visual Defect Detection in Manufacturing [[BUAV 2021]](https://library.oapen.org/bitstream/handle/20.500.12657/62433/1/978-3-662-66769-9.pdf#page=80)
+ Anomaly Detection of GAN Industrial Image Based on Attention Feature Fusion [[Sensors 2022]](https://www.mdpi.com/1424-8220/23/1/355)
+ Self-Supervised Learning for Industrial Image Anomaly Detection by Simulating Anomalous Samples [[IJCIS 2023]](https://link.springer.com/article/10.1007/s44196-023-00328-0)
+ REB: Reducing Biases in Representation for Industrial Anomaly Detection [[KBS 2023]](https://arxiv.org/abs/2308.12577)[[code]](https://github.com/ShuaiLYU/REB)
+ Natural Synthetic Anomalies for Self-supervised Anomaly Detection and Localization (NSA) [[ECCV 2022]](https://arxiv.org/pdf/2109.15222.pdf)[[code]](https://github.com/hmsch/natural-synthetic-anomalies)


### External-Dependent
+ Draem-a discriminatively trained reconstruction embedding for surface anomaly detection [[ICCV 2021]](http://arxiv.org/pdf/2108.07610)[[code]](https://github.com/vitjanz/draem)
+ MemSeg: A semi-supervised method for image surface defect detection using differences and commonalities [[EAAI 2023]](https://arxiv.org/pdf/2205.00908.pdf)[[unofficial code]](https://github.com/TooTouch/MemSeg)
+ DeSTSeg: Segmentation Guided Denoising Student-Teacher for Anomaly Detection [[CVPR 2023]](https://arxiv.org/abs/2211.11317)[[code]](https://github.com/apple/ml-destseg)

### Inpainting-Based
+ Superpixel masking and inpainting for self-supervised anomaly detection (SMAI) [[BMVC 2020]](https://www.bmvc2020-conference.com/assets/papers/0275.pdf)
+ Reconstruction by inpainting for visual anomaly detection (RIAD) [[PR 2021]](https://www.sciencedirect.com/science/article/pii/S0031320320305094/pdfft?md5=9bbe942017de1acd3a97034bc2d4a8fb&pid=1-s2.0-S0031320320305094-main.pdf)
+ Iterative image inpainting with structural similarity mask for anomaly detection (I3AD) [[2021]](https://openreview.net/pdf?id=b4ach0lGuYO)
+ Inpainting transformer for anomaly detection (InTra) [[ICIAP 2022]](https://arxiv.org/pdf/2104.13897.pdf)
+ Cutout as augmentation in contrastive learning for detecting burn marks in plastic granules [[JSSS 2024]](https://jsss.copernicus.org/articles/13/63/2024/)
+ AMI-Net: Adaptive Mask Inpainting Network for Industrial Anomaly Detection and Localization [[TASE 2024]](https://ieeexplore.ieee.org/abstract/document/10445116)

## Distribution Hypothesis-Based Models
### Prior-Dependent
+ Manifolds for unsupervised visual anomaly detection [[2020]](https://arxiv.org/abs/2006.11364)
+ Anomaly Detection using Score-based Perturbation Resilience [[ICCV 2023]](https://openaccess.thecvf.com/content/ICCV2023/papers/Shin_Anomaly_Detection_using_Score-based_Perturbation_Resilience_ICCV_2023_paper.pdf)
+ Progressive Boundary Guided Anomaly Synthesis for Industrial Anomaly Detection [[TCSVT 2024]](https://ieeexplore.ieee.org/document/10716437)[[code]](https://github.com/cqylunlun/PBAS)
+ A Unified Anomaly Synthesis Strategy with Gradient Ascent for Industrial Anomaly Detection and Localization (GLASS) [[ECCV 2024]](https://arxiv.org/abs/2407.09359)[[code]](https://github.com/cqylunlun/GLASS)

### Data-Driven
+ DSR: A dual subspace re-projection network for surface anomaly detection [[ECCV 2022]](https://arxiv.org/pdf/2208.01521.pdf)[[code]](https://github.com/VitjanZ/DSR_anomaly_detection)
+ A Unified Model for Multi-class Anomaly Detection (UniAD) [[NeurIPS 2022]](https://arxiv.org/pdf/2206.03687.pdf) [[code]](https://github.com/zhiyuanyou/UniAD)
+ SimpleNet: A Simple Network for Image Anomaly Detection and Localization [[CVPR 2023]](https://github.com/DonaldRR/SimpleNet)[[code]](https://github.com/DonaldRR/SimpleNet)
+ GLAD: Towards Better Reconstruction with Global and Local Adaptive Diffusion Models for Unsupervised Anomaly Detection [[ECCV 2024]](https://arxiv.org/abs/2406.07487)[[code]](https://github.com/hyao1/GLAD)
+ SuperSimpleNet: Unifying Unsupervised and Supervised Learning for Fast and Reliable Surface Defect Detection [[ICPR 2024]](https://arxiv.org/abs/2408.03143)[[code]](https://github.com/blaz-r/SuperSimpleNet/tree/main)


## GM-Based Models
### Full-Image Synthesis
+ Multistage GAN for fabric defect detection [[TIP 2019]](https://pubmed.ncbi.nlm.nih.gov/31870985/)
+ A new contrastive GAN with data augmentation for surface defect recognition under limited data (Con-GAN) [[TIM 2022]](https://ieeexplore.ieee.org/abstract/document/9999697/)
+ Few-shot defect image generation via defect-aware feature manipulation (DFMGAN) [[AAAI 2023]](https://arxiv.org/abs/2303.02389)[[code]](https://github.com/Ldhlwh/DFMGAN)
+ FEGAN: A Feature Extraction Based Approach For GAN Anomaly Detection And Localization (FEGAN) [[IEEE Access 2024]](https://ieeexplore.ieee.org/abstract/document/10540177/)
+ Defect Spectrum: A Granular Look of Large-Scale Defect Datasets with Rich Semantics [[ECCV 2024]](https://openreview.net/forum?id=RLhS1TrjK3)[[data]](https://github.com/EnVision-Research/Defect_Spectrum)

### Full-Image Translation
+ Defect image sample generation with GAN for improving defect recognition [[TASE 2020]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9000806)
+ Defect-GAN: High-fidelity defect synthesis for automated defect inspection [[WACV 2021]](https://dr.ntu.edu.sg/bitstream/10356/146285/2/WACV_2021_Defect_GAN__Camera_Ready_.pdf)
+ A new cycle-consistent adversarial networks with attention mechanism for surface defect classification with small samples (AttenCGAN) [[TII 2022]](https://ieeexplore.ieee.org/abstract/document/9760037/)

### Local Anomaly Synthesis
+ Mask-guided generation method for industrial defect images with non-uniform structures [[Machines 2022]](https://www.mdpi.com/2075-1702/10/12/1239)
+ Diversified and Multi-Class Controllable Industrial Defect Synthesis for Data Augmentation and Transfer [[CVPRW 2023]](https://openaccess.thecvf.com/content/CVPR2023W/VISION/html/Wei_Diversified_and_Multi-Class_Controllable_Industrial_Defect_Synthesis_for_Data_Augmentation_CVPRW_2023_paper.html)
+ RealNet: A Feature Selection Network with Realistic Synthetic Anomaly for Anomaly Detection [[CVPR 2024]](https://arxiv.org/abs/2403.05897)[[code]](https://github.com/cnulab/RealNet)

## Vison Language Models-Based
### One-Stage Generation
+ CAGEN: Controllable Anomaly Generator using Diffusion Model [[ICASSP 2024]](https://ieeexplore.ieee.org/document/10447663)
+ Anomaly Anything: Promptable Unseen Visual Anomaly Generation [[CVPR 2025]](https://arxiv.org/abs/2406.01078)[[code]](https://github.com/EPFL-IMOS/AnomalyAny)
+ AnomalyXFusion: Multi-modal Anomaly Synthesis with Diffusion [[2024]](https://arxiv.org/abs/2404.19444)[[code]](https://github.com/hujiecpp/MVTec-Caption)
+ AnomalyControl: Learning Cross-modal Semantic Features for Controllable Anomaly Synthesis [[2024]](https://arxiv.org/abs/2412.06510)
+ SeaS: Few-shot Industrial Anomaly Image Generation with Separation and Sharing Fine-tuning [[2024]](https://arxiv.org/abs/2410.14987)

### Multi-Stage Generation
+ AnomalyDiffusion: Few-Shot Anomaly Image Generation with Diffusion Model [[AAAI 2024]](https://ojs.aaai.org/index.php/AAAI/article/view/28696)[[code]](https://github.com/sjtuplayer/anomalydiffusion)
+ Few-shot defect image generation based on consistency modeling [[ECCV 2024]](https://link.springer.com/chapter/10.1007/978-3-031-73116-7_21)
+ DualAnoDiff: Dual-Interrelated Diffusion Model for Few-Shot Anomaly Image Generation [[2024]](https://arxiv.org/abs/2408.13509)[[code]](https://github.com/yinyjin/DualAnoDiff)
+ A Novel Approach to Industrial Defect Generation through Blended Latent Diffusion Model with Online Adaptation [[2024]](https://arxiv.org/abs/2402.19330)[[code]](https://github.com/GrandpaXun242/AdaBLDM)
