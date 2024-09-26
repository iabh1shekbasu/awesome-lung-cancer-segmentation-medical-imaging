# <p align=center>`Awesome Lung Cancer Segmentation in Medical Imaging`</p>


[![Last Updated](https://img.shields.io/github/last-commit/iabh1shekbasu/awesome-lung-cancer-segmentation-medical-imaging?color=blue&label=Last%20Updated)](https://github.com/iabh1shekbasu/awesome-lung-cancer-segmentation-medical-imaging/commits/main) 
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Our Paper](https://img.shields.io/badge/Our_Paper-blue)]()

This repository originates from our survey paper "**[From Pixels to Prognosis: A Comprehensive Review of Classical and Modern Approaches of Lung Nodule Segmentation for Improved Lung Cancer Diagnosis]()**" and authors (**[Arup Sau](https://scholar.google.co.in/citations?user=z_4j5sYAAAAJ&hl)**, **[Nandita Gautam](https://scholar.google.co.in/citations?user=bboVe7gAAAAJ&hl)**, **[Abhishek Basu](https://scholar.google.co.in/citations?user=SG3BWMoAAAAJ)**, **[Ram Sarkar](https://scholar.google.co.in/citations?user=bDj0BUEAAAAJ)**) will continue to update this over time.


> **Abstract:** *Lung cancer is a pervasive and life-threatening disease that requires timely detection and treatment for improved patient outcomes. Recent advancements in image processing and deep learning techniques have opened new avenues for identifying cancer in medical images. We examine these studies across various dimensions, encompassing input data (such as data modality, preprocessing techniques, and synthetic data generation), model design (including architecture, modules, and loss functions), and evaluation aspects (covering data annotation requirements and segmentation performance). Our analysis considers mostly the recently proposed methods and adopts a systematic viewpoint to understand the impact of these choices on current trends, and identifies areas (i.e., research gaps), where future researchers can work. To facilitate easy reference and comparison, we have comprehensively summarized the key findings of the existing methodologies.*

<div align="center">
    <img src="./media/Survey_Roadmap.drawio.png" alt="alt text" width="800" height="500">
    <p>Overview of the methods discussed in our paper. </p>
</div>

This repository contains a collection of state-of-the-art segmentation methods for lung cancer segmentation. 

If you find our work useful. Please consider giving a star :star: and a citation.
```bibtex
@article{,
  title={From Pixels to Prognosis: A Comprehensive Review of Classical and Modern Approaches of Lung Nodule Segmentation for Improved Lung Cancer Diagnosis},
  author={Sau, Arup and Gautam, Nandita and Basu, Abhishek and Sarkar, Ram},
  year={2024},
  publisher={}
}
```

In this repository, we have gathered some of the most promising lung cancer segmentation approaches for medical imaging and organized them based on their publication year. Whether you are new to lung cancer segmentation in medical imaging or an experienced researcher in the field, we hope that this repository will serve as a valuable resource for exploring the latest advances in this exciting area of research.


**Let's collaborate and enrich this list together! Reach out to [me](http://iabh1shekbasu.github.io/) or submit a [pull request](https://github.com/iabh1shekbasu/awesome-lung-cancer-segmentation-medical-imaging/pulls). Your contributions are highly appreciated.**

### *2024*
- **SAM3D: Segment Anything Model in Volumetric Medical Images**  
  Authors: Bui, Nhat-Tan and Hoang, Dinh-Hieu and Tran, Minh-Triet and Doretto, Gianfranco and Adjeroh, Donald and Patel, Brijesh and Choudhary, Arabinda and Le, Ngan
  [[Paper]](https://arxiv.org/abs/2309.03493)
- **Automatic lung segmentation in chest X-ray images using SAM with prompts from YOLO**  
  Authors: Khalili, Ebrahim and Priego-Torres, Blanca and Leon-Jimenez, Antonio and Sanchez-Morillo, Daniel
  [[Paper]](https://www.techrxiv.org/users/749622/articles/720884-automatic-lung-segmentation-in-chest-x-ray-images-using-sam-with-prompts-from-yolo)
- **Towards Segment Anything Model (SAM) for Medical Image Segmentation: A Survey**  
  Authors: Zhang, Yichi and Jiao, Rushi  
  [[Paper]](https://arxiv.org/abs/2305.03678)
- **Segmentation and classification of lungs CT-scan for detecting COVID-19 abnormalities by deep learning technique: U-Net model**  
  Authors: Amir S. Moosavi and Ali Mahboobi and Farshid Arabzadeh and Nasrin Ramezani and Hossein S. Moosavi and Gholamreza Mehrpoor         
  [[Paper]](https://pubmed.ncbi.nlm.nih.gov/38605799/)
- **Transformer-based semantic segmentation and CNN network for detection of histopathological lung cancer**  
  Authors: Lareib Fatima Talib and Javaria Amin and Muhammad Sharif and Mudassar Raza    
  [[Paper]](https://www.sciencedirect.com/science/article/pii/S1746809424001642)
  

### *2023*
- **Segment anything model for medical image analysis: An experimental study**  
  Authors: Maciej A. Mazurowski and Haoyu Dong and Hanxue Gu and Jichen Yang and Nicholas Konz and Yixin Zhang
  [[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S1361841523001780)
- **Atrous convolution aided integrated framework for lung nodule segmentation and classification**  
  Authors: Halder, Amitava and Dey, Debangshu  
  [[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S1746809422009818)
- **Semi-Supervised Adversarial Learning for Improving the Diagnosis of Pulmonary Nodules**  
  Authors: Fu, Yu and Xue, Peng and Xiao, Taohui and Zhang, Zhili and Zhang, Youren and Dong, Enqing  
  [[Paper]](https://pubmed.ncbi.nlm.nih.gov/36269913/)
- **A deep learning based dual encoder--decoder framework for anatomical structure segmentation in chest X-ray images**  
  Authors: Ullah, Ihsan and Ali, Farman and Shah, Babar and El-Sappagh, Shaker and Abuhmed, Tamer and Park, Sang Hyun  
  [[Paper]](https://www.nature.com/articles/s41598-023-27815-w)
- **Eres-UNet++: Liver CT image segmentation based on high-efficiency channel attention and Res-UNet++**  
  Authors: Li, Jian and Liu, Kongyu and Hu, Yating and Zhang, Hongchen and Heidari, Ali Asghar and Chen, Huiling and Zhang, Weijiang and Algarni, Abeer D and Elmannai, Hela  
  [[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S0010482522012094)
- **PET-CT image Co-segmentation of lung tumor using joint level set model**  
  Authors: Chen, Zhe and Qiu, Nan and Feng, Hui and Dai, Dongfang  
  [[Paper]](https://dl.acm.org/doi/abs/10.1016/j.compeleceng.2022.108545)
- **A Hybrid Approach for 3D Lung Segmentation in CT Images Using Active Contour and Morphological Operation**  
  Authors: Sahu, Satya Praksh and Kamble, Bhawna  
  [[Paper]](https://www.igi-global.com/chapter/a-hybrid-approach-for-3d-lung-segmentation-in-ct-images-using-active-contour-and-morphological-operation/315072)
- **OAU-net: Outlined Attention U-net for biomedical image segmentation**  
  Authors: Song, Haojie and Wang, Yuefei and Zeng, Shijie and Guo, Xiaoyan and Li, Zheheng  
  [[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S1746809422005158)
- **A Medical Image Segmentation Method Based on Improved UNet 3+ Network**  
  Authors: Xu, Yang and Hou, Shike and Wang, Xiangyu and Li, Duo and Lu, Lu  
  [[Paper]](https://pubmed.ncbi.nlm.nih.gov/36766681/)
- **RAD-UNet: Research on an improved lung nodule semantic segmentation algorithm based on deep learning**  
  Authors: Wu, Zezhi and Li, Xiaoshu and Zuo, Jianhui  
  [[Paper]](https://pubmed.ncbi.nlm.nih.gov/37035155/)
- **MSA-Net: Multiscale spatial attention network for medical image segmentation**  
  Authors: Fu, Zhaojin and Li, Jinjiang and Hua, Zhen  
  [[Paper]](https://www.sciencedirect.com/science/article/pii/S1110016823001448)

### *2022*
- **Automated Feature Extraction and Selection for Data-Driven Models of Rapid Battery Capacity Fade and End of Life**  
  Authors: Greenbank, Samuel and Howey, David  
  [[Paper]]()
- **Imaging-Based Deep Graph Neural Networks for Survival Analysis in Early Stage Lung Cancer Using CT: A Multicenter Study**  
  Authors: Lian, Jie and Long, Yonghao and Huang, Fan and Ng, Kei Shing and Lee, Faith MY and Lam, David CL and Fang, Benjamin XL and Dou, Qi and Vardhanabhuti, Varut  
  [[Paper]]()
- **Semi-Supervised Deep Transfer Learning for Benign-Malignant Diagnosis of Pulmonary Nodules in Chest CT Images**  
  Authors: Shi, Feng and Chen, Bojiang and Cao, Qiqi and Wei, Ying and Zhou, Qing and Zhang, Rui and Zhou, Yaojie and Yang, Wenjie and Wang, Xiang and Fan, Rongrong and Yang, Fan and Chen, Yanbo and Li, Weimin and Gao, Yaozong and Shen, Dinggang  
  [[Paper]]()
- **DAS-Net: A lung nodule segmentation method based on adaptive dual-branch attention and shadow mapping**  
  Authors: Luo, Shichao and Zhang, Jina and Xiao, Ning and Qiang, Yan and Li, Keqin and Zhao, Juanjuan and Meng, Liang and Song, Ping  
  [[Paper]]()
- **An Auto-Encoder Multi-Task LSTM Model for Boundary Localization**  
  Authors: Liu, Yu-Ting and Chen, Jen-Jee and Tseng, Yu-Chee and Li, Frank Y  
  [[Paper]]()
- **Multi-tier block truncation coding model using genetic auto encoders for gray scale images**  
  Authors: Rajasoundaran, S and Kumar SVN, Santhosh and Selvi, M and Ganapathy, Sannasi and Kannan, A  
  [[Paper]]()
- **Cross-modality synthesis aiding lung tumor segmentation on multi-modal MRI images**  
  Authors: Li, Jiaxin and Chen, Houjin and Li, Yanfeng and Peng, Yahui and Sun, Jia and Pan, Pan  
  [[Paper]]()
- **Microscopic segmentation and classification of COVID-19 infection with ensemble convolutional neural network**  
  Authors: Amin, Javeria and Anjum, Muhammad Almas and Sharif, Muhammad and Rehman, Amjad and Saba, Tanzila and Zahra, Rida  
  [[Paper]]()
- **APU-Net: An Attention Mechanism Parallel U-Net for Lung Tumor Segmentation**  
  Authors: Zhou, Tao and Dong, YaLi and Lu, HuiLing and Zheng, XiaoMin and Qiu, Shi and Hou, SenBao  
  [[Paper]]()
- **Nested block self-attention multiple resolution residual network for multiorgan segmentation from CT**  
  Authors: Jiang, Jue and Elguindi, Sharif and Berry, Sean L and Onochie, Ifeanyirochukwu and Cervino, Laura and Deasy, Joseph O and Veeraraghavan, Harini  
  [[Paper]]()
- **DI-Unet: Dimensional interaction self-attention for medical image segmentation**  
  Authors: Wu, Yanlin and Wang, Guanglei and Wang, Zhongyang and Wang, Hongrui and Li, Yan  
  [[Paper]]()
- **COVID-19 lesion segmentation using convolutional LSTM for self-attention**  
  Authors: Killekar, Aditya and Grodecki, Kajetan and Lin, Andrew and Cadet, Sebastien and McElhinney, Priscilla and Razipour, Aryabod and Chan, Cato and Pressman, Barry and Julien, Peter and Chen, Peter and others  
  [[Paper]]()
- **SD-UNet: A Novel Segmentation Framework for CT Images of Lung Infections**  
  Authors: Yin, Shuangcai and Deng, Hongmin and Xu, Zelin and Zhu, Qilin and Cheng, Junfeng  
  [[Paper]]()
- **SSA-Net: Spatial self-attention network for COVID-19 pneumonia infection segmentation with semi-supervised few-shot learning**  
  Authors: Wang, Xiaoyan and Yuan, Yiwen and Guo, Dongyan and Huang, Xiaojie and Cui, Ying and Xia, Ming and Wang, Zhenhua and Bai, Cong and Chen, Shengyong  
  [[Paper]]()
- **Lung image segmentation based on DRD U-Net and combined WGAN with Deep Neural Network**  
  Authors: Lian, Luoyu and Luo, Xin and Pan, Canyu and Huang, Jinlong and Hong, Wenshan and Xu, Zhendong  
  [[Paper]]()
- **Wasserstein GAN based Chest X-ray Dataset Augmentation for Deep Learning Models: COVID-19 Detection Use-Case**  
  Authors: Hussain, B Zahid and Andleeb, Ifrah and Ansari, Mohammad Samar and Joshi, Amit Mahesh and Kanwal, Nadia  
  [[Paper]]()
- **A hybrid active contour model based on pre-fitting energy and adaptive functions for fast image segmentation**  
  Authors: Ge, Pengqiang and Chen, Yiyang and Wang, Guina and Weng, Guirong  
  [[Paper]]()
- **PET/CT Co-Segmentation Based on Hybrid Active Contour Model**  
  Authors: Jiang, Chuangbo and Zheng, Shenhai and Li, Laquan  
  [[Paper]]()
- **Improved Active Contour Snake Model for Hollow Filter Bar Roundness Inspection**  
  Authors: Zhao, Kun and Zhang, Jianguo and Li, Jiangbo and Li, Guili and others  
  [[Paper]]()
- **Deep Active Contour-Based Capsule Network for Medical Image Segmentation**  
  Authors: Reddy Soora, Narasimha and Rahman Mohammed, Ehsan Ur and Waseem Mohammed, Sharfuddin and Santosh Kumar, NC  
  [[Paper]]()
- **A novel level set model initialized with guided filter for automated PET-CT image segmentation**  
  Authors: Bai, Shuhua and Qiu, Xiaojian and Hu, Rongqun and Wu, Yunqiang  
  [[Paper]]()
- **Image segmentation application combining moving grid method and level set method**  
  Authors: Shi, Hongjian and Lee, Wan-lung  
  [[Paper]]()
- **Hybrid active contour model driven by optimized local pre-fitting image energy for fast image segmentation**  
  Authors: Yan, Xin and Weng, Guirong  
  [[Paper]]()
- **Computer-aided detection of COVID-19 from CT images based on Gaussian mixture model and kernel support vector machines classifier**  
  Authors: Sayg{\i  
  [[Paper]]()
- **Effective hybrid deep learning model for COVID-19 patterns identification using CT images**  
  Authors: Ibrahim, Dheyaa Ahmed and Zebari, Dilovan Asaad and Mohammed, Hussam J and Mohammed, Mazin Abed  
  [[Paper]]()
- **Hybrid Deep Learning Model and Fuzzy C Means Clustering Method for Pulmonary Nodule Detection in CT Images**  
  Authors: Amsaveni, D and Malleswaran, M  
  [[Paper]]()
- **A novel threshold-based segmentation method for quantification of COVID-19 lung abnormalities**  
  Authors: Khan, Azrin and Garner, Rachael and Rocca, Marianna La and Salehi, Sana and Duncan, Dominique  
  [[Paper]]()
- **Detection of Lung Cancer Stages on Computed Tomography Image Using Laplacian Filter and Marker Controlled Watershed Segmentation Technique**  
  Authors: Tajrin, Tamanna and Ahmed, Mamun and Zaman, Sabina  
  [[Paper]]()
- **LUNG SCANS SEGMENTATION USING MARKER-CONTROLLED WATERSHED TRANSFORMATION**  
  Authors: Rajeshwari, D  
  [[Paper]]()
- **A Robust Approach for Segmentation and Classification of Lung Cancer using Marker Controlled Watershed Method and Deep Hybrid Learning**  
  Authors: Mothkur, Rashmi and Veerappa, BN  
  [[Paper]]()
- **The Algorithm of Watershed Color Image Segmentation Based on Morphological Gradient**  
  Authors: Wu, Yanyan and Li, Qian  
  [[Paper]]()
- **Detection of lung cancer in CT scans using grey wolf optimization algorithm and recurrent neural network**  
  Authors: Gunjan, Vinit Kumar and Singh, Ninni and Shaik, Fahimudin and Roy, Sudipta  
  [[Paper]]()
- **R2U++: a multiscale recurrent residual U-Net with dense skip connections for medical image segmentation**  
  Authors: Mubashar, Mehreen and Ali, Hazrat and Gr{\"o  
  [[Paper]]()
- **CSE-GAN: A 3D conditional generative adversarial network with concurrent squeeze-and-excitation blocks for lung nodule segmentation**  
  Authors: Tyagi, Shweta and Talbar, Sanjay N  
  [[Paper]]()
- **Early detection of COPD based on graph convolutional network and small and weakly labeled data**  
  Authors: Li, Zongli and Huang, Kewu and Liu, Ligong and Zhang, Zuoqing  
  [[Paper]]()
- **A semi-automatic threshold-based segmentation algorithm for lung cancer delineation**  
  Authors: Christie, Jaryd R and Daher, Omar and van Dongen, Hannah and Gilliland, Rory and Abdelrazek, Mohamed and Mattonen, Sarah A  
  [[Paper]]()
- **Semi-Supervised Segmentation of Radiation-Induced Pulmonary Fibrosis From Lung CT Scans With Multi-Scale Guided Dense Attention**  
  Authors: Wang, Guotai and Zhai, Shuwei and Lasio, Giovanni and Zhang, Baoshe and Yi, Byong and Chen, Shifeng and Macvittie, Thomas J. and Metaxas, Dimitris and Zhou, Jinghao and Zhang, Shaoting  
  [[Paper]]()
- **Deep belief network and closed polygonal line for lung segmentation in chest radiographs**  
  Authors: Peng, Tao and Xu, Thomas Canhao and Wang, Yihuai and Li, Fanzhang  
  [[Paper]]()
- **A hybrid deep learning model for effective segmentation and classification of lung nodules from CT images**  
  Authors: Murugesan, Malathi and Kaliannan, Kalaiselvi and Balraj, Shankarlal and Singaram, Kokila and Kaliannan, Thenmalar and Albert, Johny Renoald  
  [[Paper]]()
- **Comparison of Histogram Features and Co-occurrence Matrix in Identification of Lung Cancer X-Ray Images with Naive-Bayes Method**  
  Authors: Bustomi, MA and Rusnandar, AM  
  [[Paper]]()
- **A hierarchical GAN method with ensemble CNN for accurate nodule detection**  
  Authors: Rezaei, Seyed Reza and Ahmadi, Abbas  
  [[Paper]]()
- **Two-stage lung nodule detection framework using enhanced UNet and convolutional LSTM networks in CT images**  
  Authors: Agnes, S Akila and Anitha, J and Solomon, A Arun  
  [[Paper]]()
- **An improved capuchin search algorithm optimized hybrid CNN-LSTM architecture for malignant lung nodule detection**  
  Authors: Kanipriya, M and Hemalatha, C and Sridevi, N and SriVidhya, SR and Shabu, SL Jany  
  [[Paper]]()
- **Long Short-Term Memory Based Framework for Longitudinal Assessment of COVID-19 Using CT Imaging and Laboratory Data**  
  Authors: Chen, Chong and Li, Rui and Shen, Hong and Xia, Liming  
  [[Paper]]()
- **Convolutional bi-directional learning and spatial enhanced attentions for lung tumor segmentation**  
  Authors: Xuan, Ping and Jiang, Bin and Cui, Hui and Jin, Qiangguo and Cheng, Peng and Nakaguchi, Toshiya and Zhang, Tiangang and Li, Changyang and Ning, Zhiyu and Guo, Menghan and others  
  [[Paper]]()
- **Efficient tumor volume measurement and segmentation approach for CT image based on twin support vector machines**  
  Authors: Sathish, K and Narayana, YV and Mekala, Mahammad Shareef and Rizwan, Patan and Kallam, Suresh  
  [[Paper]]()
- **Recent advancements in deep learning based lung cancer detection: A systematic review**  
  Authors: Dodia, Shubham and Annappa, B and Mahesh, Padukudru A  
  [[Paper]]()
- **Histopathological Tissue Segmentation of Lung Cancer with Bilinear CNN and Soft Attention**  
  Authors: Xu, Rui and Wang, Zhizhen and Liu, Zhenbing and Han, Chu and Yan, Lixu and Lin, Huan and Xu, Zeyan and Feng, Zhengyun and Liang, Changhong and Chen, Xin and others  
  [[Paper]]()
- **A bi-directional deep learning architecture for lung nodule semantic segmentation**  
  Authors: Bhattacharyya, Debnath and Thirupathi Rao, N and Joshua, Eali Stephen Neal and Hu, Yu-Chen  
  [[Paper]]()
- **Automated segmentation of lungs and lung tumors in mouse micro-CT scans**  
  Authors: Ferl, Gregory Z and Barck, Kai H and Patil, Jasmine and Jemaa, Skander and Malamut, Evelyn J and Lima, Anthony and Long, Jason E and Cheng, Jason H and Junttila, Melissa R and Carano, Richard AD  
  [[Paper]]()
- **DPBET: A dual-path lung nodules segmentation model based on boundary enhancement and hybrid transformer**  
  Authors: Wang, Sihui and Jiang, Ailian and Li, Xiaotian and Qiu, Yanfang and Li, Mengyang and Li, Feixiang  
  [[Paper]]()
- **Application of TransUNet for Segmenting Lung Mass from Chest X-ray Image**  
  Authors: Chang, Chuan--Yu and Lin, Tin--Kwang and Lin, Chih--Wen and Cheng, Hsin--Tien  
  [[Paper]]()
- **H-SegNet: hybrid segmentation network for lung segmentation in chest radiographs using mask region-based convolutional neural network and adaptive closed polyline searching method**  
  Authors: Peng, Tao and Wang, Caishan and Zhang, You and Wang, Jing  
  [[Paper]]()
- **Texture appearance model, a new model-based segmentation paradigm, application on the segmentation of lung nodule in the CT scan of the chest**  
  Authors: Shariaty, Faridoddin and Orooji, Mahdi and Velichko, Elena N and Zavjalov, Sergey V  
  [[Paper]]()
- **Teacher-student approach for lung tumor segmentation from mixed-supervised datasets**  
  Authors: Fredriksen, Vemund and Sevle, Svein Ole M and Pedersen, Andr{\'e  
  [[Paper]]()
- **SegChaNet: A Novel Model for Lung Cancer Segmentation in CT Scans**  
  Authors: Cifci, Mehmet Akif and others  
  [[Paper]]()
- **Lung nodule detection based on YOLOv3 deep learning with limited datasets**  
  Authors: Bu, Zhaohui and Zhang, Xuejun and Lu, Jianxiang and Lao, Huan and Liang, Chan and Xu, Xianfu and Wei, Yini and Zeng, Hongjie  
  [[Paper]]()
- **A shape-guided deep residual network for automated CT lung segmentation**  
  Authors: Yang, Lei and Gu, Yuge and Huo, Benyan and Liu, Yanhong and Bian, Guibin  
  [[Paper]]()
- **Lung Segmentation Using ResUnet++ Powered by Variational Auto Encoder-Based Enhancement in Chest X-ray Images**  
  Authors: Ibrahim, Samar and Elgohary, Kareem and Higazy, Mahmoud and Mohannad, Thanaa and Selim, Sahar and Elattar, Mustafa  
  [[Paper]]()
- **Arseg: an attention regseg architecture for cxr lung segmentation**  
  Authors: Ghali, Rafik and Akhloufi, Moulay A  
  [[Paper]]()

### *2021*
- **Hybrid graph convolutional neural networks for landmark-based anatomical segmentation**  
  Authors: Gaggion, Nicol{\'a  
  [[Paper]]()
- **SGNet: Structure-Aware Graph-Based Network for Airway Semantic Segmentation**  
  Authors: Tan, Zimeng and Feng, Jianjiang and Zhou, Jie  
  [[Paper]]()
- **PSGR: Pixel-wise Sparse Graph Reasoning for COVID-19 Pneumonia Segmentation in CT Images**  
  Authors: Jia, Haozhe and Tang, Haoteng and Ma, Guixiang and Cai, Weidong and Huang, Heng and Zhan, Liang and Xia, Yong  
  [[Paper]]()
- **Automatic lung segmentation algorithm on chest x-ray images based on fusion variational auto-encoder and three-terminal attention mechanism**  
  Authors: Cao, Feidao and Zhao, Huaici  
  [[Paper]]()
- **Deep lung auscultation using acoustic biomarkers for abnormal respiratory sound event detection**  
  Authors: Tiwari, Upasana and Bhosale, Swapnil and Chakraborty, Rupayan and Kopparapu, Sunil Kumar  
  [[Paper]]()
- **An Uncertainty-aware Hierarchical Probabilistic Network for Early Prediction, Quantification and Segmentation of Pulmonary Tumour Growth**  
  Authors: Rafael-Palou, Xavier and Aubanell, Anton and Ceresa, Mario and Ribas, Vicent and Piella, Gemma and Ballester, Miguel A Gonz{\'a  
  [[Paper]]()
- **Decoding regulatory structures and features from epigenomics profiles: a Roadmap-ENCODE Variational Auto-Encoder (RE-VAE) model**  
  Authors: Hu, Ruifeng and Pei, Guangsheng and Jia, Peilin and Zhao, Zhongming  
  [[Paper]]()
- **PrepNet: A Convolutional Auto-Encoder to Homogenize CT Scans for Cross-Dataset Medical Image Analysis**  
  Authors: Amirian, Mohammadreza and Montoya-Zegarra, Javier A and Gruss, Jonathan and Stebler, Yves D and Bozkir, Ahmet Selman and Calandri, Marco and Schwenker, Friedhelm and Stadelmann, Thilo  
  [[Paper]]()
- **Automatic lung segmentation on chest X-rays using self-attention deep neural network**  
  Authors: Kim, Minki and Lee, Byoung-Dai  
  [[Paper]]()
- **Medical image segmentation algorithm based on multilayer boundary perception-self attention deep learning model**  
  Authors: An, Feng-Ping and Liu, Jun-e  
  [[Paper]]()
- **Domain adaptation based self-correction model for COVID-19 infection segmentation in CT images**  
  Authors: Jin, Qiangguo and Cui, Hui and Sun, Changming and Meng, Zhaopeng and Wei, Leyi and Su, Ran  
  [[Paper]]()
- **R2AU-Net: attention recurrent residual convolutional neural network for multimodal medical image segmentation**  
  Authors: Zuo, Qiang and Chen, Songyu and Wang, Zhifang  
  [[Paper]]()
- **Deep recurrent neural networks with attention mechanisms for respiratory anomaly classification**  
  Authors: Wall, Conor and Zhang, Li and Yu, Yonghong and Mistry, Kamlesh  
  [[Paper]]()
- **Hybrid dilation and attention residual U-Net for medical image segmentation**  
  Authors: Wang, Zekun and Zou, Yanni and Liu, Peter X  
  [[Paper]]()
- **Automatic COVID-19 CT segmentation using U-Net integrated spatial and channel attention mechanism**  
  Authors: Zhou, Tongxue and Canu, St{\'e  
  [[Paper]]()
- **Semi-supervised learning segmentation method of liver CT images based on 3D scSE-UNet**  
  Authors: LIU, Qing-qing and ZHOU, Zhi-yong and FAN, Guo-hua and QIAN, Xu-sheng and HU, Ji-su and CHEN, Guang-qiang and DAI, Ya-kang  
  [[Paper]]()
- **AWEU-Net: An attention-aware weight excitation u-net for lung nodule segmentation**  
  Authors: Banu, Syeda Furruka and Sarker, Md and Kamal, Mostafa and Abdel-Nasser, Mohamed and Puig, Domenec and Raswan, Hatem A  
  [[Paper]]()
- **Quadratic polynomial guided fuzzy C-means and dual attention mechanism for medical image segmentation**  
  Authors: Cai, Weiwei and Zhai, Bo and Liu, Yun and Liu, Runmin and Ning, Xin  
  [[Paper]]()
- **COVID-19 detection from X-ray images using multi-kernel-size spatial-channel attention network**  
  Authors: Fan, Yuqi and Liu, Jiahao and Yao, Ruixuan and Yuan, Xiaohui  
  [[Paper]]()
- **Multimodal spatial attention module for targeting multimodal PET-CT lung tumor segmentation**  
  Authors: Fu, Xiaohang and Bi, Lei and Kumar, Ashnil and Fulham, Michael and Kim, Jinman  
  [[Paper]]()
- **Esophagus segmentation in CT images via spatial attention network and STAPLE algorithm**  
  Authors: Tran, Minh-Trieu and Kim, Soo-Hyung and Yang, Hyung-Jeong and Lee, Guee-Sang and Oh, In-Jae and Kang, Sae-Ryung  
  [[Paper]]()
- **D2A U-Net: Automatic segmentation of COVID-19 CT slices based on dual attention and hybrid dilated convolution**  
  Authors: Zhao, Xiangyu and Zhang, Peng and Song, Fan and Fan, Guangda and Sun, Yangyang and Wang, Yujia and Tian, Zheyuan and Zhang, Luqi and Zhang, Guanglei  
  [[Paper]]()
- **Super resolution generative adversarial network (Srgans) for wheat stripe rust classification**  
  Authors: Maqsood, Muhammad Hassan and Mumtaz, Rafia and Haq, Ihsan Ul and Shafi, Uferah and Zaidi, Syed Mohammad Hassan and Hafeez, Maryam  
  [[Paper]]()
- **Dense GAN and multi-layer attention based lesion segmentation method for COVID-19 CT images**  
  Authors: Zhang, Ju and Yu, Lunduan and Chen, Decheng and Pan, Weidong and Shi, Chao and Niu, Yan and Yao, Xinwei and Xu, Xiaobin and Cheng, Yun  
  [[Paper]]()
- **An Automatic Lung Field Segmentation Algorithm Based on Improved Snake Model in X-ray Chest Radiograph**  
  Authors: Hu, Jun and Li, Ping  
  [[Paper]]()
- **A characteristic function-based algorithm for geodesic active contours**  
  Authors: Ma, Jun and Wang, Dong and Wang, Xiao-Ping and Yang, Xiaoping  
  [[Paper]]()
- **Combining cnn and hybrid active contours for head and neck tumor segmentation in ct and pet images**  
  Authors: Ma, Jun and Yang, Xiaoping  
  [[Paper]]()
- **Segmentation of lungs in thoracic CTs using K-means clustering and morphological operations**  
  Authors: Sahu, Satya Prakash and Kumar, Rahul and Londhe, Narendra D and Verma, Shrish  
  [[Paper]]()
- **An optimized approach for prostate image segmentation using K-means clustering algorithm with elbow method**  
  Authors: Sammouda, Rachid and El-Zaart, Ali and others  
  [[Paper]]()
- **CT image segmentation for inflamed and fibrotic lungs using a multi-resolution convolutional neural network**  
  Authors: Gerard, Sarah E and Herrmann, Jacob and Xin, Yi and Martin, Kevin T and Rezoagli, Emanuele and Ippolito, Davide and Bellani, Giacomo and Cereda, Maurizio and Guo, Junfeng and Hoffman, Eric A and others  
  [[Paper]]()
- **Lung nodule segmentation with a region-based fast marching method**  
  Authors: Savic, Marko and Ma, Yanhe and Ramponi, Giovanni and Du, Weiwei and Peng, Yahui  
  [[Paper]]()
- **Hessian-MRLoG: Hessian information and multi-scale reverse LoG filter for pulmonary nodule detection**  
  Authors: Mao, Qi and Zhao, Shuguang and Tong, Dongbing and Su, Shengchao and Li, Zhiwei and Cheng, Xiang  
  [[Paper]]()
- **Lung tumor segmentation using marker-controlled watershed and support vector machine**  
  Authors: Vijh, Surbhi and Sarma, Rituparna and Kumar, Sumit  
  [[Paper]]()
- **A survey of computer-aided diagnosis of lung nodules from CT scans using deep learning**  
  Authors: Gu, Yu and Chi, Jingqian and Liu, Jiaqi and Yang, Lidong and Zhang, Baohua and Yu, Dahua and Zhao, Ying and Lu, Xiaoqi  
  [[Paper]]()
- **LGAN: Lung segmentation in CT scans using generative adversarial network**  
  Authors: Tan, Jiaxing and Jing, Longlong and Huo, Yumei and Li, Lihong and Akin, Oguz and Tian, Yingli  
  [[Paper]]()
- **LungSeg-Net: Lung field segmentation using generative adversarial network**  
  Authors: Pawar, Swati P and Talbar, Sanjay N  
  [[Paper]]()
- **Lung cancer segmentation with transfer learning: usefulness of a pretrained model constructed from an artificial dataset generated using a generative adversarial network**  
  Authors: Nishio, Mizuho and Fujimoto, Koji and Matsuo, Hidetoshi and Muramatsu, Chisako and Sakamoto, Ryo and Fujita, Hiroshi  
  [[Paper]]()
- **Lung nodule segmentation using salp shuffled shepherd optimization algorithm-based generative adversarial network**  
  Authors: Jain, Supiksha and Indora, Sanjeev and Atal, Dinesh Kumar  
  [[Paper]]()
- **PyDiNet: Pyramid dilated network for medical image segmentation**  
  Authors: Gridach, Mourad  
  [[Paper]]()
- **A semantic contour based segmentation of lungs from chest x-rays for the classification of tuberculosis using Na{\"\i**  
  Authors: Geetha Pavani, P and Biswal, Birendra and Sairam, Metta Venkata Satya and Bala Subrahmanyam, N  
  [[Paper]]()
- **ResBCDU-Net: a deep learning framework for lung CT image segmentation**  
  Authors: Jalali, Yeganeh and Fateh, Mansoor and Rezvani, Mohsen and Abolghasemi, Vahid and Anisi, Mohammad Hossein  
  [[Paper]]()
- **Densely connected recurrent residual (dense r2unet) convolutional neural network for segmentation of lung ct images**  
  Authors: Dutta, Kaushik  
  [[Paper]]()
- **LNCDS: A 2D-3D cascaded CNN approach for lung nodule classification, detection and segmentation**  
  Authors: Dutande, Prasad and Baid, Ujjwal and Talbar, Sanjay  
  [[Paper]]()
- **SA-Net: A scale-attention network for medical image segmentation**  
  Authors: Hu, Jingfei and Wang, Hua and Wang, Jie and Wang, Yunqi and He, Fang and Zhang, Jicong  
  [[Paper]]()
- **Semi-supervised segmentation of radiation-induced pulmonary fibrosis from lung CT scans with multi-scale guided dense attention**  
  Authors: Wang, Guotai and Zhai, Shuwei and Lasio, Giovanni and Zhang, Baoshe and Yi, Byong and Chen, Shifeng and Macvittie, Thomas J and Metaxas, Dimitris and Zhou, Jinghao and Zhang, Shaoting  
  [[Paper]]()
- **CNN-based transfer learning--BiLSTM network: A novel approach for COVID-19 infection detection**  
  Authors: Aslan, Muhammet Fatih and Unlersen, Muhammed Fahri and Sabanci, Kadir and Durdu, Akif  
  [[Paper]]()
- **PMED-Net: Pyramid Based Multi-Scale Encoder-Decoder Network for Medical Image Segmentation**  
  Authors: Khan, Abbas and Kim, Hyongsuk and Chua, Leon  
  [[Paper]]()
- **Deep LF-Net: Semantic lung segmentation from Indian chest radiographs including severely unhealthy images**  
  Authors: Singh, Anushikha and Lall, Brejesh and Panigrahi, Bijaya K and Agrawal, Anjali and Agrawal, Anurag and Thangakunam, Balamugesh and Christopher, DJ  
  [[Paper]]()
- **Glacier Calving Front Segmentation Using Attention U-Net**  
  Authors: Holzmann, Michael and Davari, Amirabbas and Seehaus, Thorsten and Braun, Matthias and Maier, Andreas and Christlein, Vincent  
  [[Paper]]()
- **Lung Nodule Segmentation Using UNet**  
  Authors: Niranjan Kumar, S and Bruntha, P. Malin and Isaac Daniel, S and Kirubakar, J. Ajay and Elaine Kiruba, R and Sam, Siril and Immanuel Alex Pandian, S.  
  [[Paper]]()
- **Deep Feature Learning for Medical Image Analysis with Convolutional Autoencoder Neural Network**  
  Authors: Chen, Min and Shi, Xiaobo and Zhang, Yin and Wu, Di and Guizani, Mohsen  
  [[Paper]]()
- **Impact of interobserver variability in manual segmentation of non-small cell lung cancer (NSCLC) applying low-rank radiomic representation on computed tomography**  
  Authors: Hershman, Michelle and Yousefi, Bardia and Serletti, Lacey and Galperin-Aizenberg, Maya and Roshkovan, Leonid and Luna, Jos{\'e  
  [[Paper]]()
- **Lung CT Image Segmentation: A Generalized Framework Based on U-Net Architecture and Preprocessing Models**  
  Authors: Salama, Wessam M and Aly, Moustafa H  
  [[Paper]]()

### *2020*
- **A Co-Melting Reduction Auto-Encoder**  
  Authors: Sun, Yu and Cong, Jinyu and Liu, Chuan and Wei, Benzheng  
  [[Paper]]()
- **Unsupervised domain adaptation to classify medical images using zero-bias convolutional auto-encoders and context-based feature augmentation**  
  Authors: Ahn, Euijoon and Kumar, Ashnil and Fulham, Michael and Feng, Dagan and Kim, Jinman  
  [[Paper]]()
- **Lung segmentation from chest X-rays using variational data imputation**  
  Authors: Selvan, Raghavendra and Dam, Erik B and Detlefsen, Nicki S and Rischel, Sofus and Sheng, Kaining and Nielsen, Mads and Pai, Akshay  
  [[Paper]]()
- **CA-Net: Comprehensive attention convolutional neural networks for explainable medical image segmentation**  
  Authors: Gu, Ran and Wang, Guotai and Song, Tao and Huang, Rui and Aertsen, Michael and Deprest, Jan and Ourselin, S{\'e  
  [[Paper]]()
- **Self-channel-and-spatial-attention neural network for automated multi-organ segmentation on head and neck CT images**  
  Authors: Gou, Shuiping and Tong, Nuo and Qi, Sharon and Yang, Shuyuan and Chin, Robert and Sheng, Ke  
  [[Paper]]()
- **Two-staged self-attention based neural model for lung cancer recognition**  
  Authors: Samarin, Aleksei and Savelev, Alexander and Malykh, Valentin  
  [[Paper]]()
- **Recurrent attention network for false positive reduction in the detection of pulmonary nodules in thoracic CT scans**  
  Authors: Farhangi, M Mehdi and Petrick, Nicholas and Sahiner, Berkman and Frigui, Hichem and Amini, Amir A and Pezeshk, Aria  
  [[Paper]]()
- **Spatial and channel attention modulated network for medical image segmentation**  
  Authors: Fang, Wenhao and Han, Xian-hua  
  [[Paper]]()
- **Residual attention u-net for automated multi-class segmentation of covid-19 chest ct images**  
  Authors: Chen, Xiaocong and Yao, Lina and Zhang, Yu  
  [[Paper]]()
- **Md-net: multi-scale dilated convolution network for CT images segmentation**  
  Authors: Xia, Haiying and Sun, Weifan and Song, Shuxiang and Mou, Xiangwei  
  [[Paper]]()
- **Automatic semantic segmentation with DeepLab dilated learning network for change detection in remote sensing images**  
  Authors: Venugopal, N  
  [[Paper]]()
- **RDA-UNET-WGAN: an accurate breast ultrasound lesion segmentation using wasserstein generative adversarial networks**  
  Authors: Negi, Anuja and Raj, Alex Noel Joseph and Nersisson, Ruban and Zhuang, Zhemin and Murugappan, M  
  [[Paper]]()
- **Active contour image segmentation method for training talents of computer graphics and image processing technology**  
  Authors: Ye, Xinghuo and Wang, Qianyi  
  [[Paper]]()
- **Automatic segmentation model combining U-Net and level set method for medical images**  
  Authors: Yang, Yunyun and Feng, Chong and Wang, Ruofan  
  [[Paper]]()
- **New Adaptive Morphological Geodesic Active Contour Method for Segmentation of Hemorrhagic Stroke in Computed Tomography Image**  
  Authors: Medeiros, Ald{\'\i  
  [[Paper]]()
- **Unsupervised color image segmentation: A case of RGB histogram based K-means clustering initialization**  
  Authors: Basar, Sadia and Ali, Mushtaq and Ochoa-Ruiz, Gilberto and Zareei, Mahdi and Waheed, Abdul and Adnan, Awais  
  [[Paper]]()
- **Morphological Filter Aided GMM Technique for Lung Nodule Detection**  
  Authors: Halder, Amitava and Chatterjee, Saptarshi and Dey, Debangshu  
  [[Paper]]()
- **Automatic detection of pulmonary nodules using three-dimensional chain coding and optimized random forest**  
  Authors: Paing, May Phu and Hamamoto, Kazuhiko and Tungjitkusolmun, Supan and Visitsattapongse, Sarinporn and Pintavirooj, Chuchart  
  [[Paper]]()
- **PRF-RW: a progressive random forest-based random walk approach for interactive semi-automated pulmonary lobes segmentation**  
  Authors: Li, Qiang and Chen, Lei and Li, Xiangju and Lv, Xiaofeng and Xia, Shuyue and Kang, Yan  
  [[Paper]]()
- **Demarcation of Lung Lobes in CT scan Images for lung cancer Detection using Watershed Segmentation**  
  Authors: Marzuki, Nur Najihah Sofia Mohd and Isa, Iza Sazanita and Karim, Noor Khairiah A and Shuaib, Ibrahim Lutfi and Soh, Zainal Hisham Che and Sulaiman, Siti Noraini  
  [[Paper]]()
- **An effective and robust cancer detection in the lungs with BPNN and watershed segmentation**  
  Authors: Basha, CMAK Zeelan and Pravallika, B Lakshmi and Vineela, D and Prathyusha, S Lakshmi  
  [[Paper]]()
- **A survey of deep learning for lung disease detection on medical images: state-of-the-art, taxonomy, issues and future directions**  
  Authors: Kieu, Stefanus Tao Hwa and Bade, Abdullah and Hijazi, Mohd Hanafi Ahmad and Kolivand, Hoshang  
  [[Paper]]()
- **Segmentation of lungs in chest X-ray image using generative adversarial networks**  
  Authors: Munawar, Faizan and Azmat, Shoaib and Iqbal, Talha and Gr{\"o  
  [[Paper]]()
- **Effective and reliable lung segmentation of chest images with medical image processing and machine learning approaches**  
  Authors: Chanda, Pramit Brata and Sarkar, Subir Kumar  
  [[Paper]]()
- **An Automated CAD System of CT Chest Images for COVID-19 Based on Genetic Algorithm and K-Nearest Neighbor Classifier.**  
  Authors: Afify, Heba M and Darwish, Ashraf and Mohammed, Kamel K and Hassanien, Aboul Ella  
  [[Paper]]()
- **Hybrid model for lung nodule segmentation based on support vector machine and k-nearest neighbor**  
  Authors: Sharma, Srishti and Fulzele, Prasenjeet and Sreedevi, Indu  
  [[Paper]]()
- **A novel selective na{\"\i**  
  Authors: Chen, Shenglei and Webb, Geoffrey I and Liu, Linyuan and Ma, Xin  
  [[Paper]]()
- **Deep learning-based decision-tree classifier for COVID-19 diagnosis from chest X-ray imaging**  
  Authors: Yoo, Seung Hoon and Geng, Hui and Chiu, Tin Lok and Yu, Siu Ki and Cho, Dae Chul and Heo, Jin and Choi, Min Sung and Choi, Il Hyun and Cung Van, Cong and Nhung, Nguen Viet and others  
  [[Paper]]()
- **Optical flow methods for lung nodule segmentation on LIDC-IDRI images**  
  Authors: Suji, R Jenkin and Bhadouria, Sarita Singh and Dhar, Joydip and Godfrey, W Wilfred  
  [[Paper]]()
- **A lung dense deep convolution neural network for robust lung parenchyma segmentation**  
  Authors: Chen, Ying and Wang, Yerong and Hu, Fei and Wang, Ding  
  [[Paper]]()
- **A deep Residual U-Net convolutional neural network for automated lung segmentation in computed tomography images**  
  Authors: Khanna, Anita and Londhe, Narendra D and Gupta, S and Semwal, Ashish  
  [[Paper]]()
- **Dual-branch residual network for lung nodule segmentation**  
  Authors: Cao, Haichao and Liu, Hong and Song, Enmin and Hung, Chih-Cheng and Ma, Guangzhi and Xu, Xiangyang and Jin, Renchao and Lu, Jianguo  
  [[Paper]]()
- **Parallel deep learning algorithms with hybrid attention mechanism for image segmentation of lung tumors**  
  Authors: Hu, Hexuan and Li, Qingqiu and Zhao, Yunfeng and Zhang, Ye  
  [[Paper]]()
- **Attention u-net based adversarial architectures for chest x-ray lung segmentation**  
  Authors: Ga{\'a  
  [[Paper]]()
- **Time-distanced gates in long short-term memory networks**  
  Authors: Gao, Riqiang and Tang, Yucheng and Xu, Kaiwen and Huo, Yuankai and Bao, Shunxing and Antic, Sanja L and Epstein, Emily S and Deppen, Steve and Paulson, Alexis B and Sandler, Kim L and others  
  [[Paper]]()
- **Lung nodule malignancy classification based on NLSTx Data**  
  Authors: Veasey, Benjamin and Farhangi, M Mehdi and Frigui, Hichem and Broadhead, Justin and Dahle, Michael and Pezeshk, Aria and Seow, Albert and Amini, Amir A  
  [[Paper]]()
- **Automated detection of multiple lesions on chest x-ray images: classification using a neural network technique with association-specific contexts**  
  Authors: Xu, Shuaijing and Guo, Junqi and Zhang, Guangzhi and Bie, Rongfang  
  [[Paper]]()
- **Deep-pneumonia framework using deep learning models based on chest X-ray images**  
  Authors: Elshennawy, Nada M and Ibrahim, Dina M  
  [[Paper]]()
- **A fully automatic segmentation algorithm for CT lung images based on random forest**  
  Authors: Liu, Caixia and Zhao, Ruibin and Pang, Mingyong  
  [[Paper]]()
- **Segmentation of pulmonary nodules using a GMM fuzzy C-means algorithm**  
  Authors: Li, Xiangxia and Li, Bin and Liu, Fang and Yin, Hua and Zhou, Feng  
  [[Paper]]()
- **Deep learning methods for lung cancer segmentation in whole-slide histopathology images—the acdc@ lunghp challenge 2019**  
  Authors: Li, Zhang and Zhang, Jiehua and Tan, Tao and Teng, Xichao and Sun, Xiaoliang and Zhao, Hong and Liu, Lihong and Xiao, Yang and Lee, Byungjae and Li, Yilong and others  
  [[Paper]]()
- **UNet++: A Nested U-Net Architecture for Medical Image Segmentation**  
  Authors: Zhou, Zongwei and Siddiquee, Md Mahfuzur Rahman and Tajbakhsh, Nima and Liang, Jianming  
  [[Paper]]()
- **Semantic lung segmentation using convolutional neural networks**  
  Authors: Chang, Ching-Sheng and Lin, Jin-Fa and Lee, Ming-Ching and Palm, Christoph  
  [[Paper]]()
- **An effective approach for CT lung segmentation using mask region-based convolutional neural networks**  
  Authors: Hu, Qinhua and Souza, Luis Fabricio de F and Holanda, Gabriel Bandeira and Alves, Shara SA and Silva, Francisco Hercules dos S and Han, Tao and Reboucas Filho, Pedro P  
  [[Paper]]()
- **3D Segmentation of Pulmonary Nodules Based on Multi-View and Semi-Supervised**  
  Authors: Sun, Yurou and Tang, Jinglei and Lei, Weijie and He, Dongjian  
  [[Paper]]()
- **An unsupervised semi-automated pulmonary nodule segmentation method based on enhanced region growing**  
  Authors: Ren, Hongliang and Zhou, Liang and Liu, Guopeng and Peng, Xiaohui and Shi, Weifang and Xu, Haiming and Shan, Fei and Liu, Lin  
  [[Paper]]()
- **Volumetric lung nodule segmentation using adaptive ROI with multi-view residual learning**  
  Authors: Usman, Muhammad and Lee, Byoung-Dai and Byon, Shi-Sub and Kim, Sung-Hyun and Lee, Byung-il and Shin, Yeong-Gil  
  [[Paper]]()
- **Multi-level context gating of embedded collective knowledge for medical image segmentation**  
  Authors: Asadi-Aghbolaghi, Maryam and Azad, Reza and Fathy, Mahmood and Escalera, Sergio  
  [[Paper]]()

### *2019*
- **Linking convolutional neural networks with graph convolutional networks: application in pulmonary artery-vein separation**  
  Authors: Zhai, Zhiwei and Staring, Marius and Zhou, Xuhui and Xie, Qiuxia and Xiao, Xiaojuan and Els Bakker, M and Kroft, Lucia J and Lelieveldt, Boudewijn PF and Boon, Gudula JAM and Klok, Frederikus A and others  
  [[Paper]]()
- **Deep stacked sparse auto-encoders for prediction of postoperative survival expectancy in thoracic lung cancer surgery.**  
  Authors: Iraji, Mohammad Saber  
  [[Paper]]()
- **Interactive user interface based on Convolutional Auto-encoders for annotating CT-scans**  
  Authors: L{\"a  
  [[Paper]]()
- **Self-attention generative adversarial networks**  
  Authors: Zhang, Han and Goodfellow, Ian and Metaxas, Dimitris and Odena, Augustus  
  [[Paper]]()
- **Xlsor: A robust and accurate lung segmentor on chest x-rays using criss-cross attention and customized radiorealistic abnormalities generation**  
  Authors: Tang, You-Bao and Tang, Yu-Xing and Xiao, Jing and Summers, Ronald M  
  [[Paper]]()
- **A pipeline for lung tumor detection and segmentation from CT scans using dilated convolutional neural networks**  
  Authors: Hossain, Shahruk and Najeeb, Suhail and Shahriyar, Asif and Abdullah, Zaowad R and Haque, M Ariful  
  [[Paper]]()
- **Lung segmentation method with dilated convolution based on VGG-16 network**  
  Authors: Geng, Lei and Zhang, Siqi and Tong, Jun and Xiao, Zhitao  
  [[Paper]]()
- **A style-based generator architecture for generative adversarial networks**  
  Authors: Karras, Tero and Laine, Samuli and Aila, Timo  
  [[Paper]]()
- **WGAN-based synthetic minority over-sampling technique: improving semantic fine-grained classification for lung nodules in CT images**  
  Authors: Wang, Qingfeng and Zhou, Xuehai and Wang, Chao and Liu, Zhiqin and Huang, Jun and Zhou, Ying and Li, Changlong and Zhuang, Hang and Cheng, Jie-Zhi  
  [[Paper]]()
- **Learning active contour models for medical image segmentation**  
  Authors: Chen, Xu and Williams, Bryan M and Vallabhaneni, Srinivasa R and Czanner, Gabriela and Williams, Rachel and Zheng, Yalin  
  [[Paper]]()
- **Level set image segmentation with velocity term learned from data with applications to lung nodule segmentation**  
  Authors: Hancock, Matthew C and Magnan, Jerry F  
  [[Paper]]()
- **A new fast morphological geodesic active contour method for lung CT image segmentation**  
  Authors: Medeiros, Ald{\'\i  
  [[Paper]]()
- **Segmentation of lung images for tumor detection using color based k-means clustering algorithm**  
  Authors: Mathews, AB and Jeyakumar, MK  
  [[Paper]]()
- **Automated segmentation of lung parenchyma using colour based fuzzy C-means clustering**  
  Authors: Khan, Z Faizal  
  [[Paper]]()
- **Segmentation of lungs from chest X rays using firefly optimized fuzzy C-means and level set algorithm**  
  Authors: Jangam, Ebenezer and Rao, ACS  
  [[Paper]]()
- **Lung segmentation based on random forest and multi-scale edge detection**  
  Authors: Liu, Caixia and Zhao, Ruibin and Pang, Mingyong  
  [[Paper]]()
- **Instance segmentation of anatomical structures in chest radiographs**  
  Authors: Wang, Jie and Li, Zhigang and Jiang, Rui and Xie, Zhen  
  [[Paper]]()
- **Nodule-plus R-CNN and deep self-paced active learning for 3D instance segmentation of pulmonary nodules**  
  Authors: Wang, Wenzhe and Feng, Ruiwei and Chen, Jintai and Lu, Yifei and Chen, Tingting and Yu, Hongyun and Chen, Danny Z and Wu, Jian  
  [[Paper]]()
- **Adaptis: Adaptive instance selection network**  
  Authors: Sofiiuk, Konstantin and Barinova, Olga and Konushin, Anton  
  [[Paper]]()
- **A multiscale Laplacian of Gaussian (LoG) filtering approach to pulmonary nodule detection from whole-lung CT scans**  
  Authors: Fotin, Sergei V and Yankelevitz, David F and Henschke, Claudia I and Reeves, Anthony P  
  [[Paper]]()
- **Automatic pulmonary nodule detection applying deep learning or machine learning algorithms to the LIDC-IDRI database: a systematic review**  
  Authors: Pehrson, Lea Marie and Nielsen, Michael Bachmann and Ammitzb{\o  
  [[Paper]]()
- **Lung image segmentation by generative adversarial networks**  
  Authors: Cai, Jiaxin and Zhu, Hongfeng  
  [[Paper]]()
- **Panoptic segmentation**  
  Authors: Kirillov, Alexander and He, Kaiming and Girshick, Ross and Rother, Carsten and Doll{\'a  
  [[Paper]]()
- **Historical document text binarization using atrous convolution and multi-scale feature decoder**  
  Authors: Rasyidi, Hanif and Khan, Salman  
  [[Paper]]()
- **Fast and fully-automated detection and segmentation of pulmonary nodules in thoracic CT scans using deep convolutional neural networks**  
  Authors: Huang, Xia and Sun, Wenqing and Tseng, Tzu-Liang Bill and Li, Chunqiang and Qian, Wei  
  [[Paper]]()
- **Automated pulmonary nodule detection in CT images using 3D deep squeeze-and-excitation networks**  
  Authors: Gong, Li and Jiang, Shan and Yang, Zhiyong and Zhang, Guobin and Wang, Lu  
  [[Paper]]()
- **Nodulenet: Decoupled false positive reduction for pulmonary nodule detection and segmentation**  
  Authors: Tang, Hao and Zhang, Chupeng and Xie, Xiaohui  
  [[Paper]]()
- **iW-Net: an automatic and minimalistic interactive lung nodule segmentation deep network**  
  Authors: Aresta, Guilherme and Jacobs, Colin and Ara{\'u  
  [[Paper]]()
- **Pulmonary nodule segmentation with CT sample synthesis using adversarial networks**  
  Authors: Qin, Yulei and Zheng, Hao and Huang, Xiaolin and Yang, Jie and Zhu, Yue-Min  
  [[Paper]]()
- **Accurate colorectal tumor segmentation for CT scans based on the label assignment generative adversarial network**  
  Authors: Liu, Xiaoming and Guo, Shuxu and Zhang, Huimao and He, Kan and Mu, Shengnan and Guo, Yu and Li, Xueyan  
  [[Paper]]()
- **Et-net: A generic edge-attention guidance network for medical image segmentation**  
  Authors: Zhang, Zhijie and Fu, Huazhu and Dai, Hang and Shen, Jianbing and Pang, Yanwei and Shao, Ling  
  [[Paper]]()
- **Gated Recurrent Neural Networks for Accelerated Ventilation MRI**  
  Authors: Sandk{\"u  
  [[Paper]]()
- **Deep learning predicts lung cancer treatment response from serial medical imaginglongitudinal deep learning to track treatment response**  
  Authors: Xu, Yiwen and Hosny, Ahmed and Zeleznik, Roman and Parmar, Chintan and Coroller, Thibaud and Franco, Idalid and Mak, Raymond H and Aerts, Hugo JWL  
  [[Paper]]()
- **Lungs nodule detection framework from computed tomography images using support vector machine**  
  Authors: Khan, Sajid A and Nazir, Muhammad and Khan, Muhammad A and Saba, Tanzila and Javed, Kashif and Rehman, Amjad and Akram, Tallha and Awais, Muhammad  
  [[Paper]]()
- **Segmentation of Chest Radiographs for Tuberculosis Screening Using Kernel Mapping and Graph Cuts**  
  Authors: Fatima, Ayesha and Tariq, Anam and Akhtar, Mahmood and Zahid, Hira  
  [[Paper]]()
- **Application of CAD systems for the automatic detection of lung nodules**  
  Authors: Shariaty, Faridoddin and Mousavi, Mojtaba  
  [[Paper]]()
- **An automatic method for lung segmentation and reconstruction in chest X-ray using deep neural networks**  
  Authors: Souza, Johnatan Carvalho and Diniz, Jo{\~a  
  [[Paper]]()
- **Ensemble deep learning for tuberculosis detection using chest X-Ray and canny edge detected images**  
  Authors: Hijazi, Mohd Hanafi Ahmad and Hwa, Stefanus Kieu Tao and Bade, Abdullah and Yaakob, Razali and Jeffree, Mohammad Saffree  
  [[Paper]]()

### *2018*
- **Lung segmentation in CT images using a fully convolutional neural network with multi-instance and conditional adversary loss**  
  Authors: Zhao, Tianyi and Gao, Dashan and Wang, Jiao and Yin, Zhaozheng  
  [[Paper]]()
- **Recurrent residual convolutional neural network based on u-net (r2u-net) for medical image segmentation**  
  Authors: Alom, Md Zahangir and Hasan, Mahmudul and Yakopcic, Chris and Taha, Tarek M and Asari, Vijayan K  
  [[Paper]]()
- **Semi-Supervised Multi-Task Learning for Lung Cancer Diagnosis**  
  Authors: Khosravan, Naji and Bagci, Ulas  
  [[Paper]]()
- **Semi-supervised Deep Linear Discriminant Analysis for Histopathology Image Classification**  
  Authors: Cui, Lei and Feng, Jun and Yang, Lin  
  [[Paper]]()
- **A probabilistic u-net for segmentation of ambiguous images**  
  Authors: Kohl, Simon and Romera-Paredes, Bernardino and Meyer, Clemens and De Fauw, Jeffrey and Ledsam, Joseph R and Maier-Hein, Klaus and Eslami, SM and Jimenez Rezende, Danilo and Ronneberger, Olaf  
  [[Paper]]()
- **Appearance based pedestrians’ gender recognition by employing stacked auto encoders in deep learning**  
  Authors: Raza, Mudassar and Sharif, Muhammad and Yasmin, Mussarat and Khan, Muhammad Attique and Saba, Tanzila and Fernandes, Steven Lawrence  
  [[Paper]]()
- **Smoothed dilated convolutions for improved dense prediction**  
  Authors: Wang, Zhengyang and Ji, Shuiwang  
  [[Paper]]()
- **A novel region-based active contour model via local patch similarity measure for image segmentation**  
  Authors: Yu, Haiping and He, Fazhi and Pan, Yiteng  
  [[Paper]]()
- **Automatic lung segmentation with juxta-pleural nodule identification using active contour model and bayesian approach**  
  Authors: Chung, Heewon and Ko, Hoon and Jeon, Se Jeong and Yoon, Kwon-Ha and Lee, Jinseok  
  [[Paper]]()
- **A level-set approach to joint image segmentation and registration with application to CT lung imaging**  
  Authors: Swierczynski, P., Papież, B.W., Schnabel, J.A. and Macdonald, C  
  [[Paper]](https://www.sciencedirect.com/science/article/pii/S0895611117300526)
- **A novel bayesian model incorporating deep neural network and statistical shape model for pancreas segmentation**  
  Authors: Ma, Jingting and Lin, Feng and Wesarg, Stefan and Erdt, Marius  
  [[Paper]]()
- **A hybrid lung segmentation algorithm based on histogram-based fuzzy C-means clustering**  
  Authors: E Doğanay, S Kara, HK Özçelik, and L Kart
  [[Paper]](https://www.tandfonline.com/doi/abs/10.1080/21681163.2017.1332531)
- **A fast weak-supervised pulmonary nodule segmentation method based on modified self-adaptive FCM algorithm**  
  Authors: Liu, Hui and Geng, Fenghuan and Guo, Qiang and Zhang, Caiqing and Zhang, Caiming  
  [[Paper]]()
- **Hybrid intelligent approach for diagnosis of the lung nodule from CT images using spatial kernelized fuzzy c-means and ensemble learning**  
  Authors: Farahani, Farzad Vasheghani and Ahmadi, Abbas and Zarandi, Mohammad Hossein Fazel  
  [[Paper]]()
- **An effective hybrid windowed Fourier filtering and fuzzy c-mean for pulmonary nodule segmentation**  
  Authors: Mao, Qi and Zhao, Shuguang and Gong, Tao and Zheng, Qianqian  
  [[Paper]]()
- **Understanding convolution for semantic segmentation**  
  Authors: Wang, Panqu and Chen, Pengfei and Yuan, Ye and Liu, Ding and Huang, Zehua and Hou, Xiaodi and Cottrell, Garrison  
  [[Paper]]()
- **Panoptic segmentation with an end-to-end cell R-CNN for pathology image analysis**  
  Authors: Zhang, Donghao and Song, Yang and Liu, Dongnan and Jia, Haozhe and Liu, Siqi and Xia, Yong and Huang, Heng and Cai, Weidong  
  [[Paper]]()
- **Contrast enhanced medical MRI evaluation using Tsallis entropy and region growing segmentation**  
  Authors: Raja, N Sri Madhava and Fernandes, SL and Dey, Nilanjan and Satapathy, Suresh Chandra and Rajinikanth, V  
  [[Paper]]()
- **Automatic nodule detection for lung cancer in CT images: A review**  
  Authors: Zhang, Guobin and Jiang, Shan and Yang, Zhiyong and Gong, Li and Ma, Xiaodong and Zhou, Zeyang and Bao, Chao and Liu, Qi  
  [[Paper]]()
- **EMG-based estimation of limb movement using deep learning with recurrent convolutional neural networks**  
  Authors: Xia, Peng and Hu, Jie and Peng, Yinghong  
  [[Paper]]()
- **Image segmentation of overlapping leaves based on Chan--Vese model and Sobel operator**  
  Authors: Wang, Zhibin and Wang, Kaiyi and Yang, Feng and Pan, Shouhui and Han, Yanyun  
  [[Paper]]()
- **Bayes’ theorem and naive Bayes classifier**  
  Authors: Berrar, Daniel  
  [[Paper]]()
- **A new approach for prediction of lung carcinoma using back propogation neural network with decision tree classifiers**  
  Authors: Varadharajan, R and Priyan, MK and Panchatcharam, Parthasarathy and Vivekanandan, S and Gunasekaran, M  
  [[Paper]]()
- **Joint learning for pulmonary nodule segmentation, attributes and malignancy prediction**  
  Authors: Wu, Botong and Zhou, Zhen and Wang, Jianwei and Wang, Yizhou  
  [[Paper]]()
- **Deepem: Deep 3d convnets with em for weakly supervised pulmonary nodule detection**  
  Authors: Zhu, Wentao and Vang, Yeeleng S and Huang, Yufang and Xie, Xiaohui  
  [[Paper]]()
- **CT-realistic lung nodule simulation from 3D conditional generative adversarial networks for robust lung segmentation**  
  Authors: Jin, Dakai and Xu, Ziyue and Tang, Youbao and Harrison, Adam P and Mollura, Daniel J  
  [[Paper]]()
- **Joint registration and segmentation of xray images using generative adversarial networks**  
  Authors: Mahapatra, Dwarikanath and Ge, Zongyuan and Sedai, Suman and Chakravorty, Rajib  
  [[Paper]]()
- **Semantic-aware generative adversarial nets for unsupervised domain adaptation in chest x-ray segmentation**  
  Authors: Chen, Cheng and Dou, Qi and Chen, Hao and Heng, Pheng-Ann  
  [[Paper]]()
- **Multistage segmentation model and SVM-ensemble for precise lung nodule detection**  
  Authors: Naqi, Syed Muhammad and Sharif, Muhammad and Yasmin, Mussarat  
  [[Paper]]()
- **Segmentation on Chest Radiographs Using Otsu's and K-Means Clustering Methods**  
  Authors: Kasu, Narsimha Raj and Saravanan, Chandran  
  [[Paper]]()
- **Lung CT image segmentation using deep neural networks**  
  Authors: Skourt, Brahim Ait and El Hassani, Abdelhamid and Majda, Aicha  
  [[Paper]](https://www.sciencedirect.com/science/article/pii/S1877050918301157)
- **Encoder-decoder with atrous separable convolution for semantic image segmentation**  
  Authors: Chen, Liang-Chieh and Papandreou, George and Kokkinos, Iasonas and Murphy, Kevin and Yuille, Alan L.  
  [[Paper]](https://arxiv.org/abs/1802.02611)
- **Added value of computer-aided CT image features for early lung cancer diagnosis with small pulmonary nodules: a matched case-control study**  
  Authors: Huang, Peng and Park, Seyoun and Yan, Rongkai and Lee, Junghoon and Chu, Linda C and Lin, Cheng T and Hussien, Amira and Rathmell, Joshua and Thomas, Brett and Chen, Chen and others  
  [[Paper]](https://pubmed.ncbi.nlm.nih.gov/28872442/)

### *2017*
- **Convolutional auto-encoder for image denoising of ultra-low-dose CT**  
  Authors: Nishio, Mizuho and Nagashima, Chihiro and Hirabayashi, Saori and Ohnishi, Akinori and Sasaki, Kaori and Sagawa, Tomoyuki and Hamada, Masayuki and Yamashita, Tatsuo
  [[Paper]](https://www.sciencedirect.com/science/article/pii/S2405844016321600)  
- **Pulmonary parenchyma segmentation in thin CT image sequences with spectral clustering and geodesic active contour model based on similarity**  
  Authors: He, Nana and Zhang, Xiaolong and Zhao, Juanjuan and Zhao, Huilan and Qiang, Yan  
  [[Paper]](https://ui.adsabs.harvard.edu/abs/2017SPIE10420E..2GH/abstract)
- **Stacom-slawt challenge: left atrial wall segmentation and thickness measurement using region growing and marker-controlled geodesic active contour**  
  Authors: Shuman Jia, Loïc Cadour, Hubert Cochet & Maxime Sermesant 
  [[Paper]](https://link.springer.com/chapter/10.1007/978-3-319-52718-5_23)
- **Global optimal hybrid geometric active contour for automated lung segmentation on CT images**  
  Authors: Zhang, Weihang and Wang, Xue and Zhang, Pengbo and Chen, Junfeng  
  [[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S0010482517303256)
- **Segmentation and classification of lung tumor from 3D CT image using K-means clustering algorithm**  
  Authors: Sarker, Prionjit and Shuvo, Md Maruf Hossain and Hossain, Zakir and Hasan, Sabbir  
  [[Paper]](https://ieeexplore.ieee.org/document/8255451?denied=)
- **Myocardium segmentation from DE MRI using multicomponent Gaussian mixture model and coupled level set**  
  Authors: Liu, Jie and Zhuang, Xiahai and Wu, Lianming and An, Dongaolei and Xu, Jianrong and Peters, Terry and Gu, Lixu  
  [[Paper]](https://pubmed.ncbi.nlm.nih.gov/28129147/)
- **Central focused convolutional neural networks: Developing a data-driven model for lung nodule segmentation**  
  Authors: Wang, Shuo and Zhou, Mu and Liu, Zaiyi and Liu, Zhenyu and Gu, Dongsheng and Zang, Yali and Dong, Di and Gevaert, Olivier and Tian, Jie  
  [[Paper]](https://www.sciencedirect.com/science/article/pii/S1361841517301019)
- **A multi-view deep convolutional neural networks for lung nodule segmentation**  
  Authors: Wang, Shuo and Zhou, Mu and Gevaert, Olivier and Tang, Zhenchao and Dong, Di and Liu, Zhenyu and Jie, Tian  
  [[Paper]](https://ieeexplore.ieee.org/document/8037182)
- **Lung nodule classification using artificial crawlers, directional texture and support vector machine**  
  Authors: Froz, Bruno Rodrigues and de Carvalho Filho, Antonio Oseas and Silva, Arist{\'o  
  [[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S0957417416305796)
- **Validation, comparison, and combination of algorithms for automatic detection of pulmonary nodules in computed tomography images: the LUNA16 challenge**  
  Authors: Setio, Arnaud Arindra Adiyoso and Traverso, Alberto and De Bel, Thomas and Berens, Moira SN and Van Den Bogaard, Cas and Cerello, Piergiorgio and Chen, Hao and Dou, Qi and Fantacci, Maria Evelina and Geurts, Bram and others  
  [[Paper]](https://pubmed.ncbi.nlm.nih.gov/28732268/)
- **Chestx-ray8: Hospital-scale chest x-ray database and benchmarks on weakly-supervised classification and localization of common thorax diseases**  
  Authors: Wang, Xiaosong and Peng, Yifan and Lu, Le and Lu, Zhiyong and Bagheri, Mohammadhadi and Summers, Ronald M  
  [[Paper]](https://arxiv.org/abs/1705.02315)
- **A comparison study on the effect of false positive reduction in deep learning based detection for juxtapleural lung nodules: CNN VS DNN**  
  Authors: Tan, Jiaxing and Huo, Yumei and Liang, Zhengrong and Li, Lihong  
  [[Paper]](https://dl.acm.org/doi/10.5555/3108760.3108768)
- **Accurate lung segmentation via network-wise training of convolutional networks**  
  Authors: Hwang, Sangheum and Park, Sunggyun  
  [[Paper]](https://arxiv.org/abs/1708.00710)
- **Deep CNN-based method for segmenting lung fields in digital chest radiographs**  
  Authors: Kaur, Simranpreet and Hooda, Rahul and Mittal, Ajay and Sofat, Sanjeev  
  [[Paper]](https://link.springer.com/chapter/10.1007/978-981-10-5780-9_17)
- **Synthesis of positron emission tomography (PET) images via multi-channel generative adversarial networks (GANs)**  
  Authors: Bi, Lei and Kim, Jinman and Kumar, Ashnil and Feng, Dagan and Fulham, Michael  
  [[Paper]](https://arxiv.org/abs/1707.09747)
- **Deep reinforcement learning for automated radiation adaptation in lung cancer**  
  Authors: Tseng, Huan-Hsin and Luo, Yi and Cui, Sunan and Chien, Jen-Tzung and Ten Haken, Randall K and Naqa, Issam El  
  [[Paper]](https://pubmed.ncbi.nlm.nih.gov/29034482/)
- **An assisted diagnosis system for detection of early pulmonary nodule in computed tomography images**  
  Authors: Liu, Ji-kui and Jiang, Hong-yang and Gao, Meng-di and He, Chen-guang and Wang, Yu and Wang, Pu and Ma, He and Li, Ye  
  [[Paper]](https://pubmed.ncbi.nlm.nih.gov/28032305/)
- **Detection of juxta-pleural lung nodules in computed tomography images**  
  Authors: Aresta, Guilherme, António Cunha, and Aurélio Campilho
  [[Paper]](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/10134/101343N/Detection-of-juxta-pleural-lung-nodules-in-computed-tomography-images/10.1117/12.2252022.short)
- **Lung field segmentation in chest radiographs: a historical review, current status, and expectations from deep learning**  
  Authors: Mittal, Ajay and Hooda, Rahul and Sofat, Sanjeev  
  [[Paper]](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/iet-ipr.2016.0526)
- **Tversky loss function for image segmentation using 3D fully convolutional deep networks**  
  Authors: Salehi, Seyed Sadegh Mohseni and Erdogmus, Deniz and Gholipour, Ali  
  [[Paper]](https://arxiv.org/abs/1706.05721)




