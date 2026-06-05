# <p align="center">`Awesome Lung Cancer Segmentation in Medical Imaging`</p>

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Our Paper](https://img.shields.io/badge/Our_Paper-ACM%20Computing%20Surveys-blue)](https://doi.org/10.1145/3797901)

This repository accompanies the survey paper **[From Pixels to Prognosis: A Comprehensive Review of Classical and Modern Approaches of Lung Nodule Segmentation for Improved Lung Cancer Diagnosis](https://doi.org/10.1145/3797901)** 

authored by
> [**Arup Sau**](https://scholar.google.co.in/citations?user=z_4j5sYAAAAJ&hl)¹, [**Nandita Gautam**](https://scholar.google.co.in/citations?user=bboVe7gAAAAJ&hl)¹, [**Abhishek Basu**](https://abasu.ai)², [**Ram Sarkar**](https://scholar.google.co.in/citations?user=bDj0BUEAAAAJ)¹.

¹ Department of Computer Science and Engineering, Jadavpur University, India.

² Computer Vision Department, Mohamed Bin Zayed University of Artificial Intelligence, UAE.

## 📢 **Status:**
- **[18th April 2026]** ✅ Accepted in **ACM Computing Surveys** and published as *ACM Computing Surveys*, Volume 58, Issue 10, Article 266, April 2026. DOI: [10.1145/3797901](https://doi.org/10.1145/3797901).

- **[27th July 2023]** Submitted to ACM Computing Surveys.

If you find this repository useful, please consider giving it a star :star: and citing the survey:

```bibtex
@article{10.1145/3797901,
author = {Sau, Arup and Gautam, Nandita and Basu, Abhishek and Sarkar, Ram},
title = {From Pixels to Prognosis: A Comprehensive Review of Classical and Modern Approaches of Lung Nodule Segmentation for Improved Lung Cancer Diagnosis},
year = {2026},
issue_date = {July 2026},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
volume = {58},
number = {10},
issn = {0360-0300},
url = {https://doi.org/10.1145/3797901},
doi = {10.1145/3797901},
journal = {ACM Comput. Surv.},
month = apr,
articleno = {266},
numpages = {34},
keywords = {Lung cancer, deep learning, image segmentation, medical image analysis, machine learning}
}
```

## Recent top-conference papers to track (2024-2026)


| Year | Venue | Paper | Paper link | Code | Why it is relevant |
|---|---|---|---|---|---|
| 2026 | CVPR | Instruction-Guided Lesion Segmentation for Chest X-rays with Automatically Generated Large-Scale Dataset | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Choi_Instruction-Guided_Lesion_Segmentation_for_Chest_X-rays_with_Automatically_Generated_Large-Scale_CVPR_2026_paper.html) | [Code](https://github.com/checkoneee/ROSALIA) | Chest X-ray lesion segmentation; introduces MIMIC-ILS and ROSALIA. |
| 2026 | CVPR | VesMamba: 3D Pulmonary Vessel Segmentation from CT Images via Mamba with Structural Perception and Scale-aware Filtering | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Liu_VesMamba_3D_Pulmonary_Vessel_Segmentation_from_CT_images_via_Mamba_CVPR_2026_paper.html) | [Code](https://github.com/Lzpbright/VesMamba) | 3D pulmonary vessel segmentation from CT; CVF record lists the official VesMamba code repository. |
| 2025 | CVPR | Cross-Modal Interactive Perception Network with Mamba for Lung Tumor Segmentation in PET-CT Images | [Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Mei_Cross-Modal_Interactive_Perception_Network_with_Mamba_for_Lung_Tumor_Segmentation_CVPR_2025_paper.html) | [Code](https://github.com/mj129/CIPA) | Lung tumor segmentation in PET-CT images; includes the PCLT20K dataset/code release. |
| 2025 | CVPR Workshops | LNTransformer: Lung Nodule Transformer for Sparse CT Segmentation | [Paper](https://openaccess.thecvf.com/content/CVPR2025W/CVDD/html/Ramezani_LNTransformer_Lung_Nodule_Transformer_for_Sparse_CT_Segmentation_CVPRW_2025_paper.html) | N/A | Lung nodule segmentation from sparsely annotated CT. |
| 2025 | MICCAI | MG-UNet: A Memory-Guided UNet for Lesion Segmentation in Chest Images | [Paper](https://papers.miccai.org/miccai-2025/0563-Paper1062.html) | N/A | Chest lesion segmentation with memory-guided multimodal learning. |
| 2025 | MICCAI | Location-Aware Parameter Fine-Tuning for Multimodal Image Segmentation | [Paper](https://papers.miccai.org/miccai-2025/0507-Paper2608.html) | N/A | Lung infection region segmentation with parameter-efficient multimodal fine-tuning. |
| 2025 | MICCAI | Self-adaptive Vision-Language Model for 3D Segmentation of Pulmonary Artery and Vein | [Paper](https://papers.miccai.org/miccai-2025/0812-Paper2333.html) | [Code](https://github.com/zhuji423/LA-CAF-MICCAI2025) | 3D pulmonary artery-vein segmentation on CT; adjacent to lung CT analysis. |
| 2025 | MICCAI | MoDiff: A Morphology-Emphasized Diffusion Model for Ambiguous Medical Image Segmentation | [Paper](https://papers.miccai.org/miccai-2025/0576-Paper3281.html) | N/A | Ambiguous segmentation evaluated on LIDC-IDRI and MS-MRI. |
| 2025 | MICCAI | Ambiguous Medical Image Segmentation Using Diffusion Schrodinger Bridge | [Paper](https://papers.miccai.org/miccai-2025/0060-Paper4859.html) | N/A | Ambiguous medical image segmentation evaluated on LIDC-IDRI, COCA, and RACER. |
| 2025 | MICCAI | Variational Visible Layers: A Practical Framework for Uncertainty Estimation | [Paper](https://papers.miccai.org/miccai-2025/0996-Paper0787.html) | [Code](https://github.com/zabboud/Variational-Visible-Layers) | Uncertainty estimation evaluated on LIDC-IDRI segmentation. |
| 2024 | CVPR | Diversified and Personalized Multi-rater Medical Image Segmentation | [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Wu_Diversified_and_Personalized_Multi-rater_Medical_Image_Segmentation_CVPR_2024_paper.html) | [Code](https://github.com/ycwu1997/D-Persona) | Multi-rater medical segmentation evaluated on LIDC-IDRI lung nodules. |
| 2024 | MICCAI | Cross-graph Interaction and Diffusion Probability Models for Lung Nodule Segmentation | [Paper](https://papers.miccai.org/miccai-2024/173-Paper1228.html) | N/A | Lung nodule segmentation in CT with cross-graph interaction and diffusion probability modeling. |
| 2024 | MICCAI | Visual-Textual Matching Attention for Lesion Segmentation in Chest Images | [Paper](https://papers.miccai.org/miccai-2024/835-Paper2773.html) | [Code](https://github.com/nguyenpbui/MMI-UNet) | Chest-image lesion segmentation with visual-textual matching. |
| 2024 | MICCAI | Fuzzy Attention-based Border Rendering Network for Lung Organ Segmentation | [Paper](https://papers.miccai.org/miccai-2024/347-Paper2376.html) | N/A | Lung organ, airway, and artery segmentation in CT; useful for lung-region preprocessing. |
| 2026 | CVPR | VoxTell: Free-Text Promptable Universal 3D Medical Image Segmentation | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Rokuss_VoxTell_Free-Text_Promptable_Universal_3D_Medical_Image_Segmentation_CVPR_2026_paper.html) | [Code](https://github.com/MIC-DKFZ/VoxTell) | Text-prompted 3D segmentation across CT, MRI, and PET. |
| 2026 | CVPR | MedCLIPSeg: Probabilistic Vision-Language Adaptation for Data-Efficient and Generalizable Medical Image Segmentation | [Paper](https://arxiv.org/abs/2602.20423) | [Code](https://github.com/HealthX-Lab/MedCLIPSeg) | General text-guided medical image segmentation. |
| 2026 | CVPR | Simple-ViLMedSAM: Simple Text Prompts Meet Vision-Language Models for Medical Image Segmentation | [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Qian_Simple-ViLMedSAM_Simple_Text_Prompts_Meet_Vision-Language_Models_for_Medical_Image_CVPR_2026_paper.html) | N/A | Vision-language medical segmentation; useful baseline for simple text prompts. |
| 2025 | MICCAI | Sparsely Annotated Medical Image Segmentation via Cross-SAM of 3D and 2D Networks | [Paper](https://papers.miccai.org/miccai-2025/0846-Paper3529.html) | [Code](https://github.com/CTSegPilot/SA-Net) | Sparse annotation medical segmentation with SAM and 2D/3D cross-supervision. |
| 2025 | MICCAI | TGSAM-2: Text-Guided Medical Image Segmentation using Segment Anything Model 2 | [Paper](https://papers.miccai.org/miccai-2025/0921-Paper0846.html) | N/A | Text-guided SAM-2 adaptation for medical image segmentation. |
| 2024 | MICCAI | Mask-Enhanced Segment Anything Model for Tumor Lesion Semantic Segmentation | [Paper](https://papers.miccai.org/miccai-2024/491-Paper0762.html) | [Code](https://github.com/nanase1025/M-SAM) | 3D tumor lesion segmentation across CT/MRI tumor datasets. |
| 2024 | MICCAI | FastSAM3D: An Efficient Segment Anything Model for 3D Volumetric Medical Images | [Paper](https://papers.miccai.org/miccai-2024/312-Paper2456.html) | [Code](https://github.com/arcadelab/FastSAM3D) | General 3D medical segmentation foundation model. |
| 2024 | ECCV | ScribblePrompt: Fast and Flexible Interactive Segmentation for Any Biomedical Image | [Paper](https://doi.org/10.1007/978-3-031-73661-2_12) | [Code](https://github.com/halleewong/ScribblePrompt) | Interactive biomedical segmentation with scribbles, clicks, and boxes. |
| 2024 | ECCV | I-MedSAM: Implicit Medical Image Segmentation with Segment Anything | [Paper](https://doi.org/10.1007/978-3-031-72684-2_6) | [Code](https://github.com/ucwxb/I-MedSAM) | SAM-based medical segmentation with implicit representations. |
| 2024 | ECCV | CAT-SAM: Conditional Tuning for Few-Shot Adaptation of Segment Anything Model | [Paper](https://doi.org/10.1007/978-3-031-73661-2_11) | [Code](https://github.com/weihao1115/CAT-SAM) | Few-shot SAM adaptation for medical and other non-natural-image domains. |
| 2024 | CVPR | EMCAD: Efficient Multi-scale Convolutional Attention Decoding for Medical Image Segmentation | [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Rahman_EMCAD_Efficient_Multi-scale_Convolutional_Attention_Decoding_for_Medical_Image_Segmentation_CVPR_2024_paper.html) | [Code](https://github.com/SLDGroup/EMCAD) | Efficient decoder for medical image segmentation. |
| 2024 | CVPR | One-Prompt to Segment All Medical Images | [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Wu_One-Prompt_to_Segment_All_Medical_Images_CVPR_2024_paper.html) | [Code](https://github.com/KidsWithTokens/one-prompt) | Universal medical segmentation from a single prompted sample. |
| 2024 | CVPR | Tyche: Stochastic In-Context Learning for Medical Image Segmentation | [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Rakic_Tyche_Stochastic_In-Context_Learning_for_Medical_Image_Segmentation_CVPR_2024_paper.html) | [Code](https://github.com/mariannerakic/tyche) | In-context stochastic medical segmentation for ambiguous tasks. |

## Complete paper index from the ACM survey

This table preserves the original ACM bibliography reference numbers (`[1]`-`[183]`) so entries can be cross-checked against the survey PDF.

| Year | ACM ref | Paper | Paper/source link | Code |
|---|---:|---|---|---|
| 2024 | [3] | Transformer-based semantic segmentation and CNN network for detection of histopathological lung cancer | [Paper](https://doi.org/10.1016/j.bspc.2024.106106) | N/A |
| 2024 | [4] | Segmentation and classification of lungs CT-scan for detecting COVID-19 abnormalities by deep learning technique: U-Net model | [Paper](https://doi.org/10.4103/jfmpc.jfmpc_695_23) | N/A |
| 2024 | [180] | Towards segment anything model (SAM) for medical image segmentation: A survey | [Paper](https://doi.org/10.1016/j.compbiomed.2024.108238) | N/A |
| 2024 | [181] | Automatic lung segmentation in chest X-ray images using SAM with prompts from YOLO | [Paper](https://doi.org/10.1109/ACCESS.2024.3454188) | N/A |
| 2024 | [183] | SAM3D: Segment anything model in volumetric medical images | [Paper](https://doi.org/10.1109/ISBI56570.2024.10635844) | [Code](https://github.com/UARK-AICV/SAM3D) |
| 2023 | [74] | Group theoretic particle swarm optimization for multi-level threshold lung cancer image segmentation | [Paper](https://doi.org/10.21037/qims-22-295) | N/A |
| 2023 | [96] | MSA-Net: Multiscale spatial attention network for medical image segmentation | [Paper](https://doi.org/10.1016/j.aej.2023.02.039) | N/A |
| 2023 | [98] | OAU-net: Outlined attention U-net for biomedical image segmentation | [Paper](https://doi.org/10.1016/j.bspc.2022.104038) | [Code](https://github.com/YF-W/OAU-net/tree/main) |
| 2023 | [104] | An ensemble of UNet frameworks for lung nodule segmentation | [Paper](https://doi.org/10.1007/978-3-031-34127-4_44) | [Code](https://github.com/iabh1shekbasu/LungNoduleSegmentationUnetEnsemble) |
| 2023 | [105] | A medical image segmentation method based on improved UNet 3+ network | [Paper](https://doi.org/10.3390/diagnostics13030576) | N/A |
| 2023 | [106] | RAD-UNet: Research on an improved lung nodule semantic segmentation algorithm based on deep learning | [Paper](https://doi.org/10.3389/fonc.2023.1084096) | N/A |
| 2023 | [107] | CA-UNet: Convolution and attention fusion for lung nodule segmentation | [Paper](https://doi.org/10.1002/ima.22878) | N/A |
| 2023 | [132] | A deep learning based dual encoder–decoder framework for anatomical structure segmentation in chest X-ray images | [Paper](https://doi.org/10.1038/s41598-023-27815-w) | N/A |
| 2023 | [136] | Atrous convolution aided integrated framework for lung nodule segmentation and classification | [Paper](https://doi.org/10.1016/j.bspc.2022.104527) | N/A |
| 2023 | [167] | A semi-supervised multi-task learning framework for cancer classification with weak annotation in whole-slide images | [Paper](https://doi.org/10.1016/j.media.2022.102652) | N/A |
| 2023 | [168] | Semi-supervised adversarial learning for improving the diagnosis of pulmonary nodules | [Paper](https://doi.org/10.1109/JBHI.2022.3216446) | N/A |
| 2023 | [174] | DRU-Net: Pulmonary artery segmentation via dense residual U-network with hybrid loss function | [Paper](https://doi.org/10.3390/s23125427) | N/A |
| 2023 | [182] | Segment anything model for medical image analysis: An experimental study | [Paper](https://doi.org/10.1016/j.media.2023.102918) | [Code](https://github.com/mazurowski-lab/segment-anything-medical-evaluation) |
| 2022 | [2] | Automated feature extraction and selection for data-driven models of rapid battery capacity fade and end of life | [Paper](https://doi.org/10.1109/TII.2021.3106593) | N/A |
| 2022 | [11] | Recent advancements in deep learning based lung cancer detection: A systematic review | [Paper](https://www.sciencedirect.com/science/article/pii/S0952197622004808) | N/A |
| 2022 | [25] | Histopathological tissue segmentation of lung cancer with bilinear CNN and soft attention | [Paper](https://doi.org/10.1155/2022/7966553) | N/A |
| 2022 | [27] | H-SegNet: Hybrid segmentation network for lung segmentation in chest radiographs using mask region-based convolutional neural network and adaptive closed polyline searching method | [Paper](https://doi.org/10.1088/1361-6560/ac5d74) | N/A |
| 2022 | [41] | A novel threshold-based segmentation method for quantification of COVID-19 lung abnormalities | [Paper](https://doi.org/10.1007/s11760-022-02183-6) | N/A |
| 2022 | [42] | A semi-automatic threshold-based segmentation algorithm for lung cancer delineation | [Paper](https://doi.org/10.1117/12.2611501) | N/A |
| 2022 | [50] | Detection of lung cancer stages on computed tomography image using Laplacian filter and marker controlled watershed segmentation technique | [Paper](https://doi.org/10.3311/PPee.19755) | N/A |
| 2022 | [52] | The algorithm of watershed color image segmentation based on morphological gradient | [Paper](https://doi.org/10.3390/s22218202) | N/A |
| 2022 | [54] | Efficient tumor volume measurement and segmentation approach for CT image based on twin support vector machines | [Paper](https://doi.org/10.1007/s00521-021-06769-y) | N/A |
| 2022 | [56] | Automated segmentation of lungs and lung tumors in mouse micro-CT scans | [Paper](https://doi.org/10.1016/j.isci.2022.105712) | N/A |
| 2022 | [58] | Deep belief network and closed polygonal line for lung segmentation in chest radiographs | [Paper](https://doi.org/10.1093/comjnl/bxaa148) | N/A |
| 2022 | [59] | A hybrid deep learning model for effective segmentation and classification of lung nodules from CT images | [Paper](https://doi.org/10.3233/JIFS-212189) | N/A |
| 2022 | [71] | Texture appearance model, a new model-based segmentation paradigm, application on the segmentation of lung nodule in the CT scan of the chest | [Paper](https://doi.org/10.1016/j.compbiomed.2021.105086) | N/A |
| 2022 | [75] | A novel lung extraction approach for LDCT images using discrete wavelet transform with adaptive thresholding and Fuzzy C-means clustering enhanced by genetic algorithm | [Paper](https://doi.org/10.1007/s42600-022-00210-6) | N/A |
| 2022 | [86] | Lung nodule detection based on YOLOv3 deep learning with limited datasets | [Paper](https://doi.org/10.32604/mcb.2022.018318) | N/A |
| 2022 | [90] | DPBET: A dual-path lung nodules segmentation model based on boundary enhancement and hybrid transformer | [Paper](https://doi.org/10.1016/j.compbiomed.2022.106330) | N/A |
| 2022 | [91] | Application of TransUNet for segmenting lung mass from chest X-ray image | [Paper](https://doi.org/10.1109/ICCE-Taiwan55306.2022.9869180) | N/A |
| 2022 | [97] | SegChaNet: A novel model for lung cancer segmentation in CT scans | [Paper](https://doi.org/10.1155/2022/1139587) | N/A |
| 2022 | [99] | APU-Net: An attention mechanism parallel U-net for lung tumor segmentation | [Paper](https://doi.org/10.1155/2022/5303651) | N/A |
| 2022 | [108] | Multi-scale segmentation squeeze-and-excitation UNet with conditional random field for segmenting lung tumor from CT images | [Paper](https://doi.org/10.1016/j.cmpb.2022.106946) | N/A |
| 2022 | [109] | Automatic lung tumor segmentation from CT images using improved 3D densely connected UNet | [Paper](https://doi.org/10.1007/s11517-022-02667-0) | N/A |
| 2022 | [110] | A shape-guided deep residual network for automated CT lung segmentation | [Paper](https://www.sciencedirect.com/science/article/pii/S0950705122004750) | N/A |
| 2022 | [123] | Imaging-based deep graph neural networks for survival analysis in early stage lung cancer using CT: A multicenter study | [Paper](https://doi.org/10.3389/fonc.2022.868186) | N/A |
| 2022 | [133] | DASNet: A lung nodule segmentation method based on adaptive dual-branch attention and shadow mapping | [Paper](https://doi.org/10.1007/s10489-021-03038-2) | N/A |
| 2022 | [135] | Lung segmentation using resunet++ powered by variational auto encoder-based enhancement in chest X-ray images | [Paper](https://doi.org/10.1007/978-3-031-12053-4_26) | N/A |
| 2022 | [150] | Two-stage lung nodule detection framework using enhanced UNet and convolutional LSTM networks in CT images | [Paper](https://www.sciencedirect.com/science/article/pii/S0010482522007727) | N/A |
| 2022 | [151] | Convolutional bi-directional learning and spatial enhanced attentions for lung tumor segmentation | [Paper](https://www.sciencedirect.com/science/article/pii/S0169260722005284) | N/A |
| 2022 | [154] | Detection of lung cancer in CT scans using grey wolf optimization algorithm and recurrent neural network | [Paper](https://doi.org/10.1007/s12553-022-00700-8) | N/A |
| 2022 | [155] | An improved capuchin search algorithm optimized hybrid CNN-LSTM architecture for malignant lung nodule detection | [Paper](https://doi.org/10.1016/j.bspc.2022.103973) | N/A |
| 2022 | [163] | CSE-GAN: A 3D conditional generative adversarial network with concurrent squeeze-and-excitation blocks for lung nodule segmentation | [Paper](https://doi.org/10.1016/j.compbiomed.2022.105781) | N/A |
| 2022 | [169] | Teacher-student approach for lung tumor segmentation from mixed-supervised datasets | [Paper](https://doi.org/10.1371/journal.pone.0266147) | N/A |
| 2022 | [170] | Semi-supervised deep transfer learning for benign-malignant diagnosis of pulmonary nodules in chest CT images | [Paper](https://doi.org/10.1109/TMI.2021.3123572) | N/A |
| 2021 | [6] | A survey of computer-aided diagnosis of lung nodules from CT scans using deep learning | [Paper](https://doi.org/10.1016/j.compbiomed.2021.104806) | N/A |
| 2021 | [37] | Hessian-MRLoG: Hessian information and multi-scale reverse LoG filter for pulmonary nodule detection | [Paper](https://doi.org/10.1016/j.compbiomed.2021.104272) | N/A |
| 2021 | [72] | Segmentation of lungs in thoracic CTs using K-means clustering and morphological operations | [Paper](https://doi.org/10.1007/978-981-15-6329-4_28) | N/A |
| 2021 | [73] | Impact of interobserver variability in manual segmentation of non-small cell lung cancer (NSCLC) applying low-rank radiomic representation on computed tomography | [Paper](https://doi.org/10.3390/cancers13235985) | N/A |
| 2021 | [76] | Lung nodule segmentation using Salp Shuffled Shepherd Optimization Algorithm-based Generative Adversarial Network | [Paper](https://doi.org/10.1016/j.compbiomed.2021.104811) | N/A |
| 2021 | [92] | Densely connected recurrent residual (dense R2UNet) convolutional neural network for segmentation of lung CT images | [Paper](https://arxiv.org/abs/2102.00663) | N/A |
| 2021 | [93] | LNCDS: A 2D-3D cascaded CNN approach for lung nodule classification, detection and segmentation | [Paper](https://doi.org/10.1016/j.bspc.2021.102527) | N/A |
| 2021 | [111] | Lung CT image segmentation: A generalized framework based on U-net architecture and preprocessing models | [Paper](https://www.researchgate.net/profile/Moustafa-Aly-3/publication/365111875_Lung_CT_Image_Segmentation_A_Generalized_Framework_Based_on_U-Net_Architecture_and_Preprocessing_Models/links/636be58b54eb5f547cb98738/Lung-CT-Image-Segmentation-A-Generalized-Framework-Based-on-U-Net-Architecture-and-Preprocessing-Models.pdf) | N/A |
| 2021 | [112] | Lung nodule segmentation using UNet | [Paper](https://doi.org/10.1109/ICACCS51430.2021.9441977) | N/A |
| 2021 | [113] | MAU-Net: Multiple attention 3D U-Net for lung cancer segmentation on CT images | [Paper](https://doi.org/10.1016/j.procs.2021.08.056) | N/A |
| 2021 | [114] | Lung computed tomography image segmentation based on U-Net network fused with dilated convolution | [Paper](https://doi.org/10.1016/j.cmpb.2021.106170) | N/A |
| 2021 | [116] | ResBCDUNet: A deep learning framework for lung CT image segmentation | [Paper](https://doi.org/10.3390/s21010268) | N/A |
| 2021 | [120] | SGNet: Structure-aware graph-based network for airway semantic segmentation | [Paper](https://doi.org/10.1007/978-3-030-87193-2_15) | N/A |
| 2021 | [121] | Hybrid graph convolutional neural networks for landmark-based anatomical segmentation | [Paper](https://link.springer.com/chapter/10.1007/978-3-030-87193-2_57) | [Code](https://github.com/ngaggion/HybridGNet) |
| 2021 | [124] | PSGR: Pixel-wise sparse graph reasoning for COVID-19 pneumonia segmentation in CT images | [Paper](https://arxiv.org/abs/2108.03809) | N/A |
| 2021 | [134] | PMED-Net: Pyramid based multi-scale encoder-decoder network for medical image segmentation | [Paper](https://doi.org/10.1109/ACCESS.2021.3071754) | N/A |
| 2021 | [142] | PyDiNet: Pyramid dilated network for medical image segmentation | [Paper](https://doi.org/10.1016/j.neunet.2021.03.023) | N/A |
| 2021 | [145] | Deep LF-Net: Semantic lung segmentation from Indian chest radiographs including severely unhealthy images | [Paper](https://www.sciencedirect.com/science/article/pii/S1746809421002639) | N/A |
| 2021 | [148] | D2A U-Net: Automatic segmentation of COVID-19 CT slices based on dual attention and hybrid dilated convolution | [Paper](https://doi.org/10.1016/j.compbiomed.2021.104526) | N/A |
| 2021 | [149] | Multi-view convolutional recurrent neural networks for lung cancer nodule identification | [Paper](https://doi.org/10.1016/j.neucom.2020.06.144) | N/A |
| 2021 | [152] | ResBCDUNet: A deep learning framework for lung CT image segmentation | [Paper](https://doi.org/10.3390/s21010268) | N/A |
| 2021 | [160] | LGAN: Lung segmentation in CT scans using generative adversarial network | [Paper](https://doi.org/10.1016/j.compmedimag.2020.101817) | N/A |
| 2021 | [162] | LungSeg-Net: Lung field segmentation using generative adversarial network | [Paper](https://doi.org/10.1016/j.bspc.2020.102296) | N/A |
| 2021 | [164] | Lung cancer segmentation with transfer learning: Usefulness of a pretrained model constructed from an artificial dataset generated using a generative adversarial network | [Paper](https://doi.org/10.3389/frai.2021.694815) | N/A |
| 2021 | [165] | Lung nodule segmentation using salp shuffled shepherd optimization algorithm-based generative adversarial network | [Paper](https://doi.org/10.1016/j.compbiomed.2021.104811) | N/A |
| 2021 | [175] | CoLe-CNN: Context-learning convolutional neural network with adaptive loss function for lung nodule segmentation | [Paper](https://doi.org/10.1016/j.cmpb.2020.105792) | N/A |
| 2021 | [178] | Deep feature learning for medical image analysis with convolutional autoencoder neural network | [Paper](https://doi.org/10.1109/TBDATA.2017.2717439) | N/A |
| 2020 | [1] | World Health Organisation | [Paper](https://www.who.int/news-room/factsheets/detail/cancer) | N/A |
| 2020 | [10] | A survey of deep learning for lung disease detection on medical images: State-of-the-art, taxonomy, issues and future directions | [Paper](https://doi.org/10.3390/jimaging6120131) | N/A |
| 2020 | [24] | Deep learning methods for lung cancer segmentation in whole-slide histopathology images—the acdc@ lunghp challenge 2019 | [Paper](https://doi.org/10.1109/JBHI.2020.3039741) | N/A |
| 2020 | [26] | An effective approach for CT lung segmentation using mask region-based convolutional neural networks | [Paper](https://doi.org/10.1016/j.artmed.2020.101792) | N/A |
| 2020 | [48] | Demarcation of lung lobes in CT scan images for lung cancer detection using watershed segmentation | [Paper](https://ir.uitm.edu.my/id/eprint/69746/1/69746.pdf) | N/A |
| 2020 | [51] | An effective and robust cancer detection in the lungs with BPNN and watershed segmentation | [Paper](https://doi.org/10.1109/INCET49848.2020.9154186) | N/A |
| 2020 | [57] | An automated CAD system of CT chest images for COVID-19 based on genetic algorithm and K-nearest neighbor classifier | [Paper](https://doi.org/10.18280/isi.250505) | N/A |
| 2020 | [60] | Hybrid model for lung nodule segmentation based on support vector machine and k-nearest neighbor | [Paper](https://www.researchgate.net/profile/Srishti-Sharma-4/publication/340888849_Hybrid_Model_for_Lung_Nodule_Segmentation_based_on_Support_Vector_Machine_and_k-Nearest_Neighbor/links/5fd4fae745851553a0b14f2c/Hybrid-Model-for-Lung-Nodule-Segmentation-based-on-Support-Vector-Machine-and-k-Nearest-Neighbor.pdf) | N/A |
| 2020 | [63] | Deep learning-based decision-tree classifier for COVID-19 diagnosis from chest X-ray imaging | [Paper](https://doi.org/10.3389/fmed.2020.00427) | N/A |
| 2020 | [67] | A fully automatic segmentation algorithm for CT lung images based on random forest | [Paper](https://doi.org/10.1002/mp.13939) | N/A |
| 2020 | [68] | Automatic detection of pulmonary nodules using three-dimensional chain coding and optimized random forest | [Paper](https://doi.org/10.3390/app10072346) | N/A |
| 2020 | [69] | PRF-RW: A progressive random forest-based random walk approach for interactive semi-automated pulmonary lobes segmentation | [Paper](https://doi.org/10.1007/s13042-020-01111-9) | N/A |
| 2020 | [82] | A lung dense deep convolution neural network for robust lung parenchyma segmentation | [Paper](https://doi.org/10.1109/ACCESS.2020.2993953) | N/A |
| 2020 | [83] | Dual-branch residual network for lung nodule segmentation | [Paper](https://www.sciencedirect.com/science/article/pii/S156849461930715X) | N/A |
| 2020 | [100] | CA-Net: Comprehensive attention convolutional neural networks for explainable medical image segmentation | [Paper](https://arxiv.org/abs/2009.10549) | [Code](https://github.com/HiLab-git/CA-Net) |
| 2020 | [101] | Residual attention U-Net for automated multi-class segmentation of COVID-19 chest CT images | [Paper](https://arxiv.org/abs/2004.05645) | N/A |
| 2020 | [102] | UNet++: A nested U-Net architecture for medical image segmentation | [Paper](https://doi.org/10.1007/978-3-030-00889-5_1) | [Code](https://github.com/MrGiovanni/UNetPlusPlus) |
| 2020 | [115] | Segmentation of lung nodules using improved 3D-UNet neural network | [Paper](https://doi.org/10.3390/sym12111787) | N/A |
| 2020 | [117] | Conventional filtering versus U-net based models for pulmonary nodule segmentation in CT images | [Paper](https://doi.org/10.1007/s10916-020-1541-9) | N/A |
| 2020 | [118] | Volumetric lung nodule segmentation using adaptive ROI with multi-view residual learning | [Paper](https://doi.org/10.1038/s41598-020-69817-y) | N/A |
| 2020 | [139] | Md-net: Multi-scale dilated convolution network for CT images segmentation | [Paper](https://doi.org/10.1007/s11063-020-10230-x) | N/A |
| 2020 | [146] | Semantic lung segmentation using convolutional neural networks | [Paper](https://doi.org/10.1007/978-3-658-29267-6_17) | N/A |
| 2020 | [147] | Automatic semantic segmentation with DeepLab dilated learning network for change detection in remote sensing images | [Paper](https://doi.org/10.1007/s11063-019-10174-x) | N/A |
| 2020 | [153] | Multi-level context gating of embedded collective knowledge for medical image segmentation | [Paper](https://arxiv.org/abs/2003.05056) | N/A |
| 2020 | [156] | Automated detection of multiple lesions on chest x-ray images: Classification using a neural network technique with association-specific contexts | [Paper](https://doi.org/10.3390/app10051742) | N/A |
| 2020 | [157] | Time-distanced gates in long short-term memory networks | [Paper](https://doi.org/10.1016/j.media.2020.101785) | N/A |
| 2020 | [158] | Generative adversarial networks | [Paper](https://doi.org/10.1145/3422622) | N/A |
| 2020 | [161] | Segmentation of lungs in chest X-ray image using generative adversarial networks | [Paper](https://doi.org/10.1109/ACCESS.2020.3017915) | N/A |
| 2020 | [176] | 3D segmentation of pulmonary nodules based on multiview and semi-supervised | [Paper](https://doi.org/10.1109/ACCESS.2020.2971542) | N/A |
| 2019 | [9] | Application of CAD systems for the automatic detection of lung nodules | [Paper](https://doi.org/10.1016/j.imu.2019.100173) | N/A |
| 2019 | [23] | An automatic method for lung segmentation and reconstruction in chest X-ray using deep neural networks | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0169260719303517) | N/A |
| 2019 | [29] | Segmentation of chest radiographs for tuberculosis screening using kernel mapping and graph cuts | [Paper](https://doi.org/10.1007/978-3-319-96139-2_3) | N/A |
| 2019 | [31] | Ensemble deep learning for tuberculosis detection using chest X-Ray and canny edge detected images | [Paper](https://doi.org/10.11591/ijai.v8.i4.pp429-435) | N/A |
| 2019 | [39] | A multiscale Laplacian of Gaussian (LoG) filtering approach to pulmonary nodule detection from whole-lung CT scans | [Paper](https://arxiv.org/abs/1907.08328) | N/A |
| 2019 | [53] | A new fast morphological geodesic active contour method for lung CT image segmentation | [Paper](https://doi.org/10.1016/j.measurement.2019.05.078) | N/A |
| 2019 | [66] | Lung segmentation based on random forest and multi-scale edge detection | [Paper](https://doi.org/10.1049/iet-ipr.2019.0130) | N/A |
| 2019 | [77] | Segmentation-assisted diagnosis of pulmonary nodule recognition based on adaptive particle swarm image algorithm | [Paper](https://doi.org/10.1007/978-981-15-1925-3_36) | N/A |
| 2019 | [85] | Fast and fully-automated detection and segmentation of pulmonary nodules in thoracic CT scans using deep convolutional neural networks | [Paper](https://doi.org/10.1016/j.compmedimag.2019.02.003) | N/A |
| 2019 | [87] | Nodulenet: Decoupled false positive reduction for pulmonary nodule detection and segmentation | [Paper](https://arxiv.org/abs/1907.11320) | [Code](https://github.com/uci-cbcl/NoduleNet) |
| 2019 | [122] | Linking convolutional neural networks with graph convolutional networks: Application in pulmonary artery-vein separation | [Paper](https://doi.org/10.1007/978-3-030-35817-4_5) | [Code](https://github.com/Zhiwei-Zhai/Linking-CNN-GCN) |
| 2019 | [138] | A pipeline for lung tumor detection and segmentation from CT scans using dilated convolutional neural networks | [Paper](https://www.researchgate.net/profile/Shahruk-Hossain/publication/332790518_A_Pipeline_for_Lung_Tumor_Detection_and_Segmentation_from_CT_Scans_Using_Dilated_Convolutional_Neural_Networks/links/614dec1ff8c9c51a8aeecf5a/A-Pipeline-for-Lung-Tumor-Detection-and-Segmentation-from-CT-Scans-Using-Dilated-Convolutional-Neural-Networks.pdf) | [Code](https://github.com/suhailnajeeb/lungseg-vip2018) |
| 2019 | [140] | Lung segmentation method with dilated convolution based on VGG-16 network | [Paper](https://doi.org/10.1080/24699322.2019.1649071) | N/A |
| 2019 | [141] | Historical document text binarization using atrous convolution and multi-scale feature decoder | [Paper](https://www.researchgate.net/profile/Salman-Khan-62/publication/335714619_Historical_Document_Text_Binarization_using_Atrous_Convolution_and_Multi-Scale_Feature_Decoder/links/5d7883594585151ee4ae0368/Historical-Document-Text-Binarization-using-Atrous-Convolution-and-Multi-Scale-Feature-Decoder.pdf) | N/A |
| 2019 | [159] | Lung image segmentation by generative adversarial networks | [Paper](https://doi.org/10.1117/12.2548153) | N/A |
| 2019 | [177] | Semi-supervised adversarial model for benign–malignant lung nodule classification on chest CT | [Paper](https://doi.org/10.1016/j.media.2019.07.004) | N/A |
| 2019 | [179] | A review: Deep learning for medical image segmentation using multi-modality fusion | [Paper](https://doi.org/10.1016/j.array.2019.100004) | N/A |
| 2018 | [8] | Automatic nodule detection for lung cancer in CT images: A review | [Paper](https://doi.org/10.1016/j.compbiomed.2018.10.033) | N/A |
| 2018 | [21] | Lung CT image segmentation using deep neural networks | [Paper](https://www.sciencedirect.com/science/article/pii/S1877050918301157) | N/A |
| 2018 | [45] | Segmentation on chest radiographs using Otsu’s and K-means clustering methods | [Paper](https://doi.org/10.1109/ISRITI.2018.8864444) | N/A |
| 2018 | [47] | Image segmentation of overlapping leaves based on Chan–Vese model and Sobel operator | [Paper](https://www.sciencedirect.com/science/article/pii/S2214317317301270) | N/A |
| 2018 | [81] | Lung segmentation in CT images using a fully convolutional neural network with multi-instance and conditional adversary loss | [Paper](https://doi.org/10.1109/ISBI.2018.8363626) | N/A |
| 2018 | [95] | Recurrent residual convolutional neural network based on u-net (r2u-net) for medical image segmentation | [Paper](https://arxiv.org/abs/1802.06955) | N/A |
| 2018 | [103] | Encoder-decoder with atrous separable convolution for semantic image segmentation | [Paper](https://arxiv.org/abs/1802.02611) | N/A |
| 2018 | [119] | Improved U-NET network for pulmonary nodules segmentation | [Paper](https://doi.org/10.1016/j.ijleo.2018.08.086) | N/A |
| 2018 | [137] | Smoothed dilated convolutions for improved dense prediction | [Paper](https://doi.org/10.1145/3219819.3219944) | [Code](https://github.com/divelab/dilated) |
| 2018 | [166] | Semi-supervised deep linear discriminant analysis for histopathology image classification | [Paper](https://doi.org/10.1109/BIBM.2018.8621451) | N/A |
| 2018 | [171] | Semi-supervised multi-task learning for lung cancer diagnosis | [Paper](https://doi.org/10.1109/EMBC.2018.8512294) | N/A |
| 2017 | [7] | Lung field segmentation in chest radiographs: A historical review, current status, and expectations from deep learning | [Paper](https://doi.org/10.1049/iet-ipr.2016.0526) | N/A |
| 2017 | [12] | Validation, comparison, and combination of algorithms for automatic detection of pulmonary nodules in computed tomography images: The LUNA16 challenge | [Paper](https://doi.org/10.1016/j.media.2017.06.015) | N/A |
| 2017 | [15] | Chestx-ray8: Hospital-scale chest x-ray database and benchmarks on weakly-supervised classification and localization of common thorax diseases | [Paper](https://openaccess.thecvf.com/content_cvpr_2017/html/Wang_ChestX-Ray8_Hospital-Scale_Chest_CVPR_2017_paper.html) | N/A |
| 2017 | [46] | An assisted diagnosis system for detection of early pulmonary nodule in computed tomography images | [Paper](https://doi.org/10.1007/s10916-016-0669-0) | N/A |
| 2017 | [84] | Accurate lung segmentation via network-wise training of convolutional networks | [Paper](https://doi.org/10.1007/978-3-319-67558-9_11) | N/A |
| 2017 | [88] | Central focused convolutional neural networks: Developing a data-driven model for lung nodule segmentation | [Paper](https://www.sciencedirect.com/science/article/pii/S1361841517301019) | N/A |
| 2017 | [89] | A multi-view deep convolutional neural networks for lung nodule segmentation | [Paper](https://doi.org/10.1109/EMBC.2017.8037182) | N/A |
| 2017 | [94] | Fully convolutional networks for semantic segmentation | [Paper](https://doi.org/10.1109/TPAMI.2016.2572683) | N/A |
| 2017 | [143] | Rethinking atrous convolution for semantic image segmentation | [Paper](https://arxiv.org/abs/1706.05587) | N/A |
| 2017 | [144] | Deeplab: Semantic image segmentation with deep convolutional nets, atrous convolution, and fully connected crfs | [Paper](https://doi.org/10.1109/TPAMI.2017.2699184) | N/A |
| 2017 | [172] | Fully convolutional networks for semantic segmentation | [Paper](https://doi.org/10.1109/TPAMI.2016.2572683) | N/A |
| 2017 | [173] | Tversky loss function for image segmentation using 3D fully convolutional deep networks | [Paper](https://doi.org/10.1007/978-3-319-67389-9_44) | N/A |
| 2016 | [34] | Comparison of various edge detection technique | [Paper](https://doi.org/10.14257/ijsip.2016.9.2.13) | N/A |
| 2016 | [36] | A parameterized logarithmic image processing method with Laplacian of Gaussian filtering for lung nodule enhancement in chest radiographs | [Paper](https://doi.org/10.1007/s11517-016-1469-x) | N/A |
| 2016 | [44] | Computer-aided detection of pulmonary nodules using dynamic self-adaptive template matching and a FLDA classifier | [Paper](https://www.sciencedirect.com/science/article/pii/S1120179716309772) | N/A |
| 2016 | [49] | An improved image processing analysis for the detection of lung cancer using Gabor filters and watershed segmentation technique | [Paper](https://doi.org/10.1109/INVENTIVE.2016.7830084) | N/A |
| 2016 | [64] | ATLAAS: An automatic decision tree-based learning algorithm for advanced image segmentation in positron emission tomography | [Paper](https://doi.org/10.1088/0031-9155/61/13/4855) | N/A |
| 2016 | [70] | Dynamically balanced online random forests for interactive scribble-based segmentation | [Paper](https://doi.org/10.1007/978-3-319-46723-8_41) | N/A |
| 2015 | [5] | A survey on fuzzy clustering techniques for lung CT image segmentation | [Paper](https://www.researchgate.net/profile/Tharcis-Paulraj/publication/333339810_A_Survey_on_Fuzzy_Clustering_Techniques_for_Lung_CT_Image_Segmentation/links/5ce8dc8492851c4eabbc5359/A-Survey-on-Fuzzy-Clustering-Techniques-for-Lung-CT-Image-Segmentation.pdf) | N/A |
| 2015 | [28] | A novel approach of lung segmentation on chest CT images using graph cuts | [Paper](https://www.sciencedirect.com/science/article/pii/S0925231215007201) | N/A |
| 2015 | [30] | Random walk and graph cut for co-segmentation of lung tumor on PET-CT images | [Paper](https://doi.org/10.1109/TIP.2015.2488902) | N/A |
| 2015 | [32] | An approach toward fast gradient-based image segmentation | [Paper](https://pubmed.ncbi.nlm.nih.gov/25838522/) | N/A |
| 2015 | [35] | An improved edge detection using morphological Laplacian of Gaussian operator | [Paper](https://doi.org/10.1109/SPIN.2015.7095391) | N/A |
| 2015 | [43] | A robust approach for automated lung segmentation in thoracic CT | [Paper](https://dblp.org/rec/conf/smc/ZhouGHWLCGHN15) | N/A |
| 2015 | [55] | An automated lung segmentation approach using bidirectional chain codes to improve nodule detection accuracy | [Paper](https://doi.org/10.1016/j.compbiomed.2014.12.008) | N/A |
| 2015 | [78] | Segmentation of CT lung nodules using FCM with firefly search algorithm | [Paper](https://doi.org/10.1109/ICIIECS.2015.7193181) | N/A |
| 2015 | [79] | Cavitary nodule segmentation in computed tomography images based on self–generating neural networks and particle swarm optimisation | [Paper](https://doi.org/10.1504/IJBIC.2015.067999) | N/A |
| 2015 | [130] | Unsupervised learning of video representations using lstms | [Paper](https://proceedings.mlr.press/v37/srivastava15.html) | [Code](https://github.com/mansimov/unsupervised-videos) |
| 2015 | [131] | Adversarial autoencoders | [Paper](https://arxiv.org/abs/1511.05644) | N/A |
| 2014 | [13] | Decoding tumour phenotype by noninvasive imaging using a quantitative radiomics approach | [Paper](https://doi.org/10.1038/ncomms5006) | N/A |
| 2014 | [14] | National lung screening trial research team | [Paper](https://doi.org/10.1056/NEJMoa1208962) | N/A |
| 2014 | [38] | Refinement of lung nodule candidates based on local geometric shape analysis and Laplacian of Gaussian kernels | [Paper](https://www.sciencedirect.com/science/article/pii/S0010482514002613) | N/A |
| 2014 | [40] | A survey on threshold based segmentation technique in image processing | [Paper](https://www.researchgate.net/profile/Singaraju-Jyothi/publication/309209325_A_Survey_on_Threshold_Based_Segmentation_Technique_in_Image_Processing/links/5805bb6f08aee314f68e2879/A-Survey-on-Threshold-Based-Segmentation-Technique-in-Image-Processing.pdf) | N/A |
| 2014 | [80] | Soft computing approach to 3D lung nodule segmentation in CT | [Paper](https://doi.org/10.1016/j.compbiomed.2014.08.005) | N/A |
| 2013 | [16] | Lung segmentation in chest radiographs using anatomical atlases with nonrigid registration | [Paper](https://doi.org/10.1109/TMI.2013.2290491) | N/A |
| 2013 | [61] | Decision trees: A recent overview | [Paper](https://doi.org/10.1007/s10462-011-9272-4) | N/A |
| 2013 | [62] | Illumination invariant segmentation of vegetation for time series wheat images based on decision tree model | [Paper](https://doi.org/10.1016/j.compag.2013.04.010) | N/A |
| 2013 | [65] | Automatic segmentation of lung carcinoma using 3D texture features in 18-FDG PET/CT | [Paper](https://doi.org/10.1155/2013/980769) | N/A |
| 2013 | [129] | Auto-encoding variational bayes | [Paper](https://arxiv.org/abs/1312.6114) | N/A |
| 2012 | [20] | Lungs segmentation using multi-level thresholding in CT images | [Paper]() | N/A |
| 2012 | [33] | A comparison of various edge detection techniques used in image processing | [Paper](https://ijcsi.org/papers/IJCSI-9-5-1-269-276.pdf) | N/A |
| 2011 | [17] | The lung image database consortium (LIDC) and image database resource initiative (IDRI): A completed reference database of lung nodules on CT scans | [Paper](https://doi.org/10.1118/1.3528204) | N/A |
| 2011 | [127] | Contractive auto-encoders: Explicit invariance during feature extraction | [Paper](https://www.icml-2011.org/papers/455_icmlpaper.pdf) | N/A |
| 2011 | [128] | Stacked convolutional auto-encoders for hierarchical feature extraction | [Paper](https://doi.org/10.1007/978-3-642-21735-7_7) | N/A |
| 2009 | [18] | Evaluating variability in tumor measurements from same-day repeat CT scans of patients with non–small cell lung cancer | [Paper](https://doi.org/10.1148/radiol.2522081593) | N/A |
| 2008 | [126] | Extracting and composing robust features with denoising autoencoders | [Paper](https://doi.org/10.1145/1390156.1390294) | N/A |
| 2007 | [22] | Accurate lung segmentation for X-ray CT images | [Paper](https://doi.org/10.1109/ICNC.2007.157) | N/A |
| 2006 | [125] | Efficient learning of sparse representations with an energy-based model | [Paper](https://proceedings.neurips.cc/paper/2006/file/87f4d79e36d68c3031ccf6c55e9bbd39-Paper.pdf) | N/A |
| 2000 | [19] | Development of a digital image database for chest radiographs with and without a lung nodule: Receiver operating characteristic analysis of radiologists’ detection of pulmonary nodules | [Paper](https://db.jsrt.or.jp/eng.php) | N/A |
