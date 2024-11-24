# <p align='center'>`3DGS and Beyond Docs`</p>

This is a collection of documents and topics NeRF/3DGS & Beyond channel accumulated, as well as papers in literaure. Since there are lots of papers out there, so we split them into two seperate repositories: [NeRF and Beyond Docs](https://github.com/yangjiheng/nerf_and_beyond_docs) and [3DGS and Beyond Docs](https://github.com/yangjiheng/3DGS_and_Beyond_Docs). Please choose accordingly recarding to your preference.

Some papers we discussed in the group, will be added to the back of the paper with a **Notes** link. You can follow the link to check whether there is topic you are interested in. If not, welcome to join us and ask the question to the crowd. The mighty community might have your answers.

We are actively maintaining this page trying to stay up-to-date and gather important works in a daily basis. We would also like to put as many notes as possible to some works, trying to make it easier to catch up. 

Please feel free to join us on WeChat group or start a discussion topic here.

## NeRF/3DGS Book

I have recently published a book with PHEI(Publishing House of Electronics Industry) on NeRF/3DGS. This would not have been possible without the help of the whole 3D vision community. It is now available on jd.com ([Checkout here](https://item.jd.com/10110615626932.html)) and it should be suitable as a reference handbook for NeRF/3DGS beginners or engineers in related areas. I sincerely hope the book can be helpful in any perspective. 

For those of you who have already purchased the book, all references can be downloaded [HERE](./assets/book_references.pdf). If you experience any issue reading the book or have any suggestions to improve it, please contact me through my email address: `jiheng.yang@gmail.com`, or directly concact me on WeChat: `jiheng_yang`. I'm looking forward to talk to anyone reaching out to me, thanks in advance.

<div style="text-align: center;">
  <img src="./assets/book_cover.jpeg" width="400">
</div>

## How to join us

For now, you can join us in the following ways

* [Bilibili Channel](https://space.bilibili.com/455056488) where we post near daily updates (primarily) on NeRF.
* WeChat group, due to the limitation of WeChat group, you can add my personal account: `jiheng_yang`, and I will add you to the chat groups.
* If you want to view this from a timeline perspective, please refer to this [ProcessOn Diagram](https://www.processon.com/view/link/643f8907f1144c215788f3e2)
* If you think something is not correct or you think we could do better in some way, please write to us through all possible channels or drop an issue. All suggestions are appreciated!
* For other discussed techniques that's related to 3D reconstruction and NeRF, please refer to [link](./NeRF_Related_Tech.md), we are constantly trying to add more resource to this document.


## NeRF Progresses

For NeRF related progress, you can refer to [NeRF and Beyond Docs](https://github.com/yangjiheng/nerf_and_beyond_docs)

<summary>Table of Content</summary>

- [`3DGS and Beyond Docs`](#3dgs-and-beyond-docs)
  - [NeRF/3DGS Book](#nerf3dgs-book)
  - [How to join us](#how-to-join-us)
  - [NeRF Progresses](#nerf-progresses)
  - [3DGS Original Paper](#3dgs-original-paper)
  - [3DGS Surveys](#3dgs-surveys)
  - [3DGS Frameworks](#3dgs-frameworks)
  - [3DGS Profiling](#3dgs-profiling)
  - [3DGS Distributed Training](#3dgs-distributed-training)
  - [3DGS Quality Enhancement](#3dgs-quality-enhancement)
  - [3DGS with Ray Tracing](#3dgs-with-ray-tracing)
  - [3DGS Acceleration](#3dgs-acceleration)
  - [3DGS Geometry Reconstruction](#3dgs-geometry-reconstruction)
  - [3DGS+Mesh For Reconstruction](#3dgsmesh-for-reconstruction)
  - [3DGS Based Dynamic Scene](#3dgs-based-dynamic-scene)
  - [3DGS + Depth](#3dgs--depth)
  - [3DGS Based Depth Estimation](#3dgs-based-depth-estimation)
  - [3DGS Few-shot Reconstruction](#3dgs-few-shot-reconstruction)
  - [3DGS Weak Camera Pose](#3dgs-weak-camera-pose)
  - [3DGS Object Pose Estimation](#3dgs-object-pose-estimation)
  - [3DGS-NeRF Transfer](#3dgs-nerf-transfer)
  - [3DGS Generalization](#3dgs-generalization)
  - [3DGS Indoor Scene Reconstruction](#3dgs-indoor-scene-reconstruction)
  - [3DGS Based Wild Scene Reconstruction](#3dgs-based-wild-scene-reconstruction)
  - [3DGS Based Large Scene Reconstruction](#3dgs-based-large-scene-reconstruction)
  - [3DGS Autonomous Driving](#3dgs-autonomous-driving)
  - [3DGS Based Occupancy Prediction](#3dgs-based-occupancy-prediction)
  - [3DGS Based on Diffusion](#3dgs-based-on-diffusion)
  - [3DGS Based AIGC](#3dgs-based-aigc)
  - [3DGS Model Compactness Optimization](#3dgs-model-compactness-optimization)
    - [3DGS Model Compression Surveys](#3dgs-model-compression-surveys)
    - [3DGS Model Compression Progresses](#3dgs-model-compression-progresses)
  - [3DGS Streaming](#3dgs-streaming)
  - [3DGS Based Relighting](#3dgs-based-relighting)
  - [3DGS Robotics](#3dgs-robotics)
    - [3DGS Robotics Surveys](#3dgs-robotics-surveys)
    - [3DGS Robotics Progresses](#3dgs-robotics-progresses)
  - [3DGS Avatar Generation](#3dgs-avatar-generation)
    - [3DGS Avatar Generation Survey](#3dgs-avatar-generation-survey)
    - [3DGS Avatar Generation Progresses](#3dgs-avatar-generation-progresses)
  - [3DGS Clothes/Garment](#3dgs-clothesgarment)
  - [3DGS Scene Editing and Animation](#3dgs-scene-editing-and-animation)
  - [3DGS Stylization](#3dgs-stylization)
  - [3DGS Based Video Editing](#3dgs-based-video-editing)
  - [3DGS for Computer Graphics](#3dgs-for-computer-graphics)
  - [3DGS Based Scene Understanding](#3dgs-based-scene-understanding)
  - [3DGS based Segmentation](#3dgs-based-segmentation)
  - [3DGS + Specular](#3dgs--specular)
  - [3DGS Based SLAM](#3dgs-based-slam)
  - [3DGS Based 3D Point Tracking](#3dgs-based-3d-point-tracking)
  - [3DGS Based Inverse Rendering](#3dgs-based-inverse-rendering)
  - [3DGS Imaging Tasks](#3dgs-imaging-tasks)
  - [3DGS for Reflective and Transparent Objects](#3dgs-for-reflective-and-transparent-objects)
  - [3DGS Superresolution](#3dgs-superresolution)
  - [3DGS for Point Cloud](#3dgs-for-point-cloud)
  - [3DGS for CV Tasks](#3dgs-for-cv-tasks)
  - [3DGS with Hardware](#3dgs-with-hardware)
  - [3DGS Applications](#3dgs-applications)
    - [3DGS Application in Animal Reconstruction](#3dgs-application-in-animal-reconstruction)
    - [3DGS Application in Medical Imaging](#3dgs-application-in-medical-imaging)
    - [3DGS Application in Underwater Scenario](#3dgs-application-in-underwater-scenario)
    - [3DGS Application in Agriculture/Forestry Scenario](#3dgs-application-in-agricultureforestry-scenario)
  - [3DGS Artifact Detection](#3dgs-artifact-detection)
  - [3DGS Copyright/Safety](#3dgs-copyrightsafety)
  - [3DGS Applications in UAV/MAV](#3dgs-applications-in-uavmav)
  - [3DGS Applications in Satellite Images](#3dgs-applications-in-satellite-images)
  - [3DGS Network Applications](#3dgs-network-applications)
  - [3DGS for Acoustic](#3dgs-for-acoustic)
  - [3DGS with Panorama](#3dgs-with-panorama)
  - [3DGS with Thermal](#3dgs-with-thermal)
  - [3DGS with Fisheye Camera](#3dgs-with-fisheye-camera)
  - [3DGS with Compressive Sensing](#3dgs-with-compressive-sensing)
  - [Other NVS Methods](#other-nvs-methods)
  - [Other Surveys](#other-surveys)
  - [Contributors](#contributors)
  - [License](#license)


## 3DGS Original Paper

**3D Gaussian Splatting for Real-Time Radiance Field Rendering**<br>
*Bernhard Kerbl, Georgios Kopanas, Thomas Leimkühler, George Drettakis*<br>
ACM ToG 2023, 8 August, 2023<br>
[[arXiv](https://arxiv.org/abs/2308.04079)] [[Project](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/)] [[Github](https://github.com/graphdeco-inria/gaussian-splatting)]

## 3DGS Surveys

**A Survey on 3D Gaussian Splatting**<br>
*Guikun Chen, Wenguan Wang*<br>
arXiv preprint, 8 Jan 2024<br>
[[arXiv](https://arxiv.org/abs/2401.03890)]

**3D Gaussian as a New Vision Era: A Survey**<br>
*Ben Fei, Jingyi Xu, Rui Zhang, Qingyuan Zhou, Weidong Yang, Ying He*<br>
arXiv preprint, 11 Feb 2024<br>
[[arXiv](https://arxiv.org/abs/2402.07181)]

:fire:**Recent Advances in 3D Gaussian Splatting**<br>
*Tong Wu, Yu-Jie Yuan, Ling-Xiao Zhang, Jie Yang, Yan-Pei Cao, Ling-Qi Yan, Lin Gao*<br>
arXiv preprint, 17 Mar 2024<br>
<details span>
<summary><b>Abstract</b></summary>
The emergence of 3D Gaussian Splatting (3DGS) has greatly accelerated the rendering speed of novel view synthesis. Unlike neural implicit representations like Neural Radiance Fields (NeRF) that represent a 3D scene with position and viewpoint-conditioned neural networks, 3D Gaussian Splatting utilizes a set of Gaussian ellipsoids to model the scene so that efficient rendering can be accomplished by rasterizing Gaussian ellipsoids into images. Apart from the fast rendering speed, the explicit representation of 3D Gaussian Splatting facilitates editing tasks like dynamic reconstruction, geometry editing, and physical simulation. Considering the rapid change and growing number of works in this field, we present a literature review of recent 3D Gaussian Splatting methods, which can be roughly classified into 3D reconstruction, 3D editing, and other downstream applications by functionality. Traditional point-based rendering methods and the rendering formulation of 3D Gaussian Splatting are also illustrated for a better understanding of this technique. This survey aims to help beginners get into this field quickly and provide experienced researchers with a comprehensive overview, which can stimulate the future development of the 3D Gaussian Splatting representation.
</details>

[[arXiv](https://arxiv.org/abs/2403.11134)]<br>


**Gaussian Splatting: 3D Reconstruction and Novel View Synthesis, a Review**<br>
*Anurag Dalal, Daniel Hagen, Kjell G. Robbersmyr, Kristian Muri Knausgård*<br>
arXiv preprint, 6 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.03417)]

**Survey on Fundamental Deep Learning 3D Reconstruction Techniques**<br>
*Yonge Bai, LikHang Wong, TszYin Twan*<br>
arXiv preprint, 11 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.08137)]

**3D Gaussian Splatting: Survey, Technologies, Challenges, and Opportunities**<br>
*Yanqi Bao, Tianyu Ding, Jing Huo, Yaoli Liu, Yuxin Li, Wenbin Li, Yang Gao, Jiebo Luo*<br>
arXiv preprint, 24 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.17418)]

**3D Representation Methods: A Survey**<br>
*Zhengren Wang*<br>
arXiv preprint, 9 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.06475)]

## 3DGS Frameworks

:fire:**GauStudio: A Modular Framework for 3D Gaussian Splatting and Beyond**<br>
*Chongjie Ye, Yinyu Nie, Jiahao Chang, Yuantao Chen, Yihao Zhi, Xiaoguang Han*<br>
arXiv preprint, 28 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.19632)] [[Code](https://github.com/GAP-LAB-CUHK-SZ/gaustudio)]

**gsplat: An Open-Source Library for Gaussian Splatting**<br>
*Vickie Ye, Ruilong Li, Justin Kerr, Matias Turkulainen, Brent Yi, Zhuoyang Pan, Otto Seiskari, Jianbo Ye, Jeffrey Hu, Matthew Tancik, Angjoo Kanazawa*<br>
arXiv preprint, 10 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.06765)]

**SuperSplat - 3D Gaussian Splat Editor**<br>
PlayCanvas<br>
[[Code](https://github.com/playcanvas/supersplat)]

## 3DGS Profiling

**NerfBaselines: Consistent and Reproducible Evaluation of Novel View Synthesis Methods**<br>
*Jonas Kulhanek, Torsten Sattler*<br>
arXiv preprint, 25 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.17345)] [[Project](https://jkulhanek.com/nerfbaselines/)]

## 3DGS Distributed Training

**On Scaling Up 3D Gaussian Splatting Training**
*Hexu Zhao, Haoyang Weng, Daohan Lu, Ang Li, Jinyang Li, Aurojit Panda, Saining Xie*<br>
arXiv preprint, 26 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.18533)] [[Project](https://daohanlu.github.io/scaling-up-3dgs)] [[Code](https://github.com/nyu-systems/Grendel-GS)]

## 3DGS Quality Enhancement

:fire:**Mip-Splatting: Alias-free 3D Gaussian Splatting**<br>
*Zehao Yu, Anpei Chen, Binbin Huang, Torsten Sattler, Andreas Geiger*<br>
arXiv preprint, 27 Nov 2023<br>
[[arXiv](https://arxiv.org/abs/2311.16493)] [[Project](https://niujinshuchong.github.io/mip-splatting/)]

**Multi-Scale 3D Gaussian Splatting for Anti-Aliased Rendering**<br>
*Zhiwen Yan, Weng Fei Low, Yu Chen, Gim Hee Lee*<br>
arXiv preprint, 28 Nov 2023<br>
[[arXiv](https://arxiv.org/abs/2311.17089)] [[Project](https://jokeryan.github.io/projects/ms-gs/)] [[Code](https://github.com/JokerYan/MS-GS/tree/main)] [[Video](https://youtu.be/q77p5nKnpJw)]

:fire:**Scaffold-GS: Structured 3D Gaussians for View-Adaptive Rendering**<br>
*Tao Lu, Mulin Yu, Linning Xu, Yuanbo Xiangli, Limin Wang, Dahua Lin, Bo Dai*<br>
arXiv preprint, 30 Nov 2023<br>
[[arXiv](https://arxiv.org/abs/2312.00109)] [[Project](https://city-super.github.io/scaffold-gs/)]

**Gaussian Splitting Algorithm with Color and Opacity Depended on Viewing Direction**<br>
*Dawid Malarz, Weronika Smolak, Jacek Tabor, Sławomir Tadeja, Przemysław Spurek*<br>
arXiv preprint, 21 Dec 2023<br>
[[arXiv](https://arxiv.org/abs/2312.13729)]

**TRIPS: Trilinear Point Splatting for Real-Time Radiance Field Rendering**<br>
*Linus Franke, Darius Rückert, Laura Fink, Marc Stamminger*<br>
Eurographics 2024, 11 Jan 2024<br>
[[arXiv](https://arxiv.org/abs/2401.06003)] [[Project](https://lfranke.github.io/trips/)] [[Code](https://github.com/lfranke/trips)] [[Video](https://www.youtube.com/watch?v=Nw4A1tIcErQ&feature=youtu.be)]

**Optimal Projection for 3D Gaussian Splatting**<br>
*Letian Huang, Jiayang Bai, Jie Guo, Yanwen Guo*<br>
arXiv preprint, 1 Feb 2024<br>
[[arXiv](https://arxiv.org/abs/2402.00752)]

**FreGS: 3D Gaussian Splatting with Progressive Frequency Regularization**<br>
*Jiahui Zhang, Fangneng Zhan, Muyu Xu, Shijian Lu, Eric Xing*<br>
CVPR 2024, 11 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.06908)] [[Project](https://rogeraigc.github.io/FreGS-Page/)]

:fire:**Analytic-Splatting: Anti-Aliased 3D Gaussian Splatting via Analytic Integration**<br>
*Zhihao Liang, Qi Zhang, Wenbo Hu, Ying Feng, Lei Zhu, Kui Jia*<br>
arXiv preprint, 16 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.11056)] [[Project](https://lzhnb.github.io/project-pages/analytic-splatting/)] [[Code](https://github.com/lzhnb/Analytic-Splatting)]

**Pixel-GS: Density Control with Pixel-aware Gradient for 3D Gaussian Splatting**<br>
*Zheng Zhang, Wenbo Hu, Yixing Lao, Tong He, Hengshuang Zhao*<br>
arXiv preprint, 22 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.15530)]

:fire:**SA-GS: Scale-Adaptive Gaussian Splatting for Training-Free Anti-Aliasing**<br>
*Xiaowei Song, Jv Zheng, Shiran Yuan, Huan-ang Gao, Jingwei Zhao, Xiang He, Weihao Gu, Hao Zhao*<br>
arXiv preprint, 28 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.19615)] [[Project](https://kevinsong729.github.io/project-pages/SA-GS/)] [[Code](https://github.com/zsy1987/SA-GS/)]

**Robust Gaussian Splatting**<br>
*François Darmon, Lorenzo Porzi, Samuel Rota-Bulò, Peter Kontschieder*<br>
arXiv preprint, 5 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.04211)]

**Revising Densification in Gaussian Splatting**<br>
*Samuel Rota Bulò, Lorenzo Porzi, Peter Kontschieder*<br>
arXiv preprint, 9 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.06109)]

**EGGS: Edge Guided Gaussian Splatting for Radiance Fields**<br>
*Yuanhao Gong*<br>
arXiv preprint, 14 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.09105)]

**3D Gaussian Splatting as Markov Chain Monte Carlo**<br>
*Shakiba Kheradmand, Daniel Rebain, Gopal Sharma, Weiwei Sun, Jeff Tseng, Hossam Isack, Abhishek Kar, Andrea Tagliasacchi, Kwang Moo Yi*<br>
arXiv preprint, 15 Apr 2024<br>
[[arXiv](https://zhuanlan.zhihu.com/p/692938277)]

**LoopGaussian: Creating 3D Cinemagraph with Multi-view Images via Eulerian Motion Field**<br>
*Jiyang Li, Lechao Cheng, Zhangye Wang, Tingting Mu, Jingxuan He*<br>
arXiv preprint, 13 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.08966)]

**AbsGS: Recovering Fine Details for 3D Gaussian Splatting**<br>
*Zongxin Ye, Wenyu Li, Sidun Liu, Peng Qiao, Yong Dou*<br>
arXiv preprint, 16 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.10484)] [[Project](https://ty424.github.io/AbsGS.github.io/)] [[Code](https://github.com/TY424/AbsGS)]

**Gaussian Splatting Decoder for 3D-aware Generative Adversarial Networks**<br>
*Florian Barthel, Arian Beckmann, Wieland Morgenstern, Anna Hilsmann, Peter Eisert*<br>
CVPRW 2024, 16 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.10625)]

**Does Gaussian Splatting need SFM Initialization?**<br>
*Yalda Foroutan, Daniel Rebain, Kwang Moo Yi, Andrea Tagliasacchi*<br>
arXiv preprint, 18 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.12547)] [[Project](https://theialab.github.io/nerf-3dgs/)]

**FlowMap: High-Quality Camera Poses, Intrinsics, and Depth via Gradient Descent**<br>
*Cameron Smith, David Charatan, Ayush Tewari, Vincent Sitzmann*<br>
arXiv preprint, 23 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.15259)]

:fire:**Spectrally Pruned Gaussian Fields with Neural Compensation**<br>
*Runyi Yang, Zhenxin Zhu, Zhou Jiang, Baijun Ye, Xiaoxue Chen, Yifei Zhang, Yuantao Chen, Jian Zhao, Hao Zhao*<br>
arXiv preprint, 1 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.00676)] [[Project](https://runyiyang.github.io/projects/SUNDAE/)] [[Code](https://github.com/RunyiYang/SUNDAE)]

**Bootstrap 3D Reconstructed Scenes from 3D Gaussian Splatting**<br>
*Yifei Gao, Jie Ou, Lei Wang, Jun Cheng*<br>
arXiv preprint, 29 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.18669)]

**I3DGS: Improve 3D Gaussian Splatting from Multiple Dimensions**<br>
*Jinwei Lin*<br>
arXiv preprint, 10 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.06408)]

**Gaussian Time Machine: A Real-Time Rendering Methodology for Time-Variant Appearances**<br>
*Licheng Shen, Ho Ngai Chow, Lingyun Wang, Tong Zhang, Mengqiu Wang, Yuxing Han*<br>
arXiv preprint, 22 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.13694)]

**AtomGS: Atomizing Gaussian Splatting for High-Fidelity Radiance Field**<br>
*Rong Liu, Rui Xu, Yue Hu, Meida Chen, Andrew Feng*<br>
arXiv preprint, 20 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.12369)] [[Project](https://rongliu-leo.github.io/AtomGS/)] [[Code](https://github.com/RongLiu-Leo/AtomGS)] [[Video](https://www.youtube.com/watch?v=1B7oga_1BqE)]

**Feature Splatting for Better Novel View Synthesis with Low Overlap**<br>
*T. Berriel Martins, Javier Civera*<br>
arXiv preprint, 24 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.15518)] [[Code](https://github.com/tberriel/FeatSplat)]

**NegGS: Negative Gaussian Splatting**<br>
*Artur Kasymov, Bartosz Czekaj, Marcin Mazur, Przemysław Spurek*<br>
arXiv preprint, 28 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.18163)]

**3D-HGS: 3D Half-Gaussian Splatting**<br>
*Haolin Li, Jinyang Liu, Mario Sznaier, Octavia Camps*<br>
arXiv preprint, 4 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.02518)]

**Gaussian Splatting with Localized Points Management**<br>
*Haosen Yang, Chenhao Zhang, Wenqing Wang, Marco Volino, Adrian Hilton, Li Zhang, Xiatian Zhu*<br>
arXiv preprint, 6 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.04251)] [[Code](https://github.com/Surrey-UP-Lab/GS-LPM)]

**RetinaGS: Scalable Training for Dense Scene Rendering with Billion-Scale 3D Gaussians**<br>
*Bingling Li, Shengyi Chen, Luchao Wang, Kaimin He, Sijie Yan, Yuanjun Xiong*<br>
arXiv preprint, 17 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.11836)]

**Effective Rank Analysis and Regularization for Enhanced 3D Gaussian Splatting**<br>
*Junha Hyung, Susung Hong, Sungwon Hwang, Jaeseong Lee, Jaegul Choo, Jin-Hwa Kim*<br>
arXiv preprint, 17 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.11672)] [[Project](https://junhahyung.github.io/erankgs.github.io/)] 

**PUP 3D-GS: Principled Uncertainty Pruning for 3D Gaussian Splatting**<br>
*Alex Hanson, Allen Tu, Vasu Singla, Mayuka Jayawardhana, Matthias Zwicker, Tom Goldstein*<br>
arXiv preprint, 14 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.10219)]


**Taming 3DGS: High-Quality Radiance Fields with Limited Resources**<br>
*Saswat Subhajyoti Mallick, Rahul Goel, Bernhard Kerbl, Francisco Vicente Carrasco, Markus Steinberger, Fernando De La Torre*<br>
arXiv preprint, 21 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.15643)]

**SpotlessSplats: Ignoring Distractors in 3D Gaussian Splatting**<br>
*Sara Sabour, Lily Goli, George Kopanas, Mark Matthews, Dmitry Lagun, Leonidas Guibas, Alec Jacobson, David J. Fleet, Andrea Tagliasacchi*<br>
arXiv preprint, 28 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.20055)]

**GS-Octree: Octree-based 3D Gaussian Splatting for Robust Object-level 3D Reconstruction Under Strong Lighting**<br>
*Jiaze Li, Zhengyu Wen, Luo Zhang, Jiangbei Hu, Fei Hou, Zhebin Zhang, Ying He*<br>
arXiv preprint, 26 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.18199)]

**Textured-GS: Gaussian Splatting with Spatially Defined Color and Opacity**<br>
*Zhentao Huang, Minglun Gong*<br>
arXiv preprint, 13 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.09733)]

**Splatfacto-W: A Nerfstudio Implementation of Gaussian Splatting for Unconstrained Photo Collections**<br>
*Congrong Xu, Justin Kerr, Angjoo Kanazawa*<br>
arXiv preprint, 17 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.12306)] [[Code](https://github.com/KevinXu02/splatfacto-w)]

**MVG-Splatting: Multi-View Guided Gaussian Splatting with Adaptive Quantile-Based Geometric Consistency Densification**<br>
*Zhuoxiao Li, Shanliang Yao, Yijie Chu, Angel F. Garcia-Fernandez, Yong Yue, Eng Gee Lim, Xiaohui Zhu*<br>
arXiv preprint, 16 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.11840)] [[Project](https://mvgsplatting.github.io/)]

**3iGS: Factorised Tensorial Illumination for 3D Gaussian Splatting**<br>
*Zhe Jun Tang, Tat-Jen Cham*<br>
ECCV 2024, 7 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.03753)]


**Mipmap-GS: Let Gaussians Deform with Scale-specific Mipmap for Anti-aliasing Rendering**<br>
*Jiameng Li, Yue Shi, Jiezhang Cao, Bingbing Ni, Wenjun Zhang, Kai Zhang, Luc Van Gool*<br>
arXiv preprint, 12 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.06286)]

**FLoD: Integrating Flexible Level of Detail into 3D Gaussian Splatting for Customizable Rendering**<br>
*Yunji Seo, Young Sun Choi, Hyun Seung Son, Youngjung Uh*<br>
arXiv preprint, 23 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.12894)] [[Project](https://3dgs-flod.github.io/flod.github.io/)] [[Code](https://github.com/3DGS-FLoD/flod)]

**Robust 3D Gaussian Splatting for Novel View Synthesis in Presence of Distractors**<br>
*Paul Ungermann, Armin Ettenhofer, Matthias Nießner, Barbara Roessle*<br>
GCPR 2024, 21 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.11697)] [[Project](https://paulungermann.github.io/Robust3DGaussians/)] [[Video](https://www.youtube.com/watch?v=P9unyR7yK3E)] [[Code](https://github.com/paulungermann/Robust3DGaussians)]

**Implicit Gaussian Splatting with Efficient Multi-Level Tri-Plane Representation**<br>
*Minye Wu, Tinne Tuytelaars*<br>
arXiv preprint, 19 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.10041)]

**Correspondence-Guided SfM-Free 3D Gaussian Splatting for NVS**<br>
*Wei Sun, Xiaosong Zhang, Fang Wan, Yanzhao Zhou, Yuan Li, Qixiang Ye, Jianbin Jiao*<br>
arXiv preprint, 16 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.08723)]

**Sources of Uncertainty in 3D Scene Reconstruction**<br>
*Marcus Klasson, Riccardo Mereu, Juho Kannala, Arno Solin*<br>
ECCV 2024, 10 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.06407)] [[Project](https://aaltoml.github.io/uncertainty-nerf-gs/)] [[Code](https://github.com/AaltoML/uncertainty-nerf-gs)]

**3DGS-LM: Faster Gaussian-Splatting Optimization with Levenberg-Marquardt**<br>
*Lukas Höllein, Aljaž Božič, Michael Zollhöfer, Matthias Nießner*<br>
arXiv preprint, 19 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.12892)] [[Project](https://lukashoel.github.io/3DGS-LM/)] [[Video](https://www.youtube.com/watch?v=tDiGuGMssg8)] [[Code](https://github.com/lukasHoel/3DGS-LM)]

**Spectral-GS: Taming 3D Gaussian Splatting with Spectral Entropy**<br>
*Letian Huang, Jie Guo, Jialin Dan, Ruoyu Fu, Shujie Wang, Yuanqi Li, Yanwen Guo*<br>
arXiv preprint, 19 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.12771)]

**GStex: Per-Primitive Texturing of 2D Gaussian Splatting for Decoupled Appearance and Geometry Modeling**<br>
*Victor Rong, Jingxiang Chen, Sherwin Bahmani, Kiriakos N. Kutulakos, David B. Lindell*<br>
arXiv preprint, 19 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.12954)] [[Project](https://lessvrong.com/cs/gstex)]

**Frequency-based View Selection in Gaussian Splatting Reconstruction**<br>
*Monica M.Q. Li, Pierre-Yves Lajoie, Giovanni Beltrame*<br>
arXiv preprint, 24 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.16470)]

**MVGS: Multi-view-regulated Gaussian Splatting for Novel View Synthesis**<br>
*Xiaobiao Du, Yida Wang, Xin Yu*<br>
arXiv preprint, 2 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.02103)] [[Project](https://xiaobiaodu.github.io/mvgs-project/)] [[Code](https://github.com/xiaobiaodu/MVGS)]

**6DGS: Enhanced Direction-Aware Gaussian Splatting for Volumetric Rendering**<br>
*Zhongpai Gao, Benjamin Planche, Meng Zheng, Anwesa Choudhuri, Terrence Chen, Ziyan Wu*<br>
arXiv preprint, 7 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.04974)] [[Project](https://gaozhongpai.github.io/6dgs/)]

**PH-Dropout: Prctical Epistemic Uncertainty Quantification for View Synthesis**<br>
*Chuanhao Sun, Thanos Triantafyllou, Anthos Makris, Maja Drmač, Kai Xu, Luo Mai, Mahesh K. Marina*<br>
arXiv preprint, 7 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.05468)]

**PhotoReg: Photometrically Registering 3D Gaussian Splatting Models**<br>
*Ziwen Yuan, Tianyi Zhang, Matthew Johnson-Roberson, Weiming Zhi*<br>
arXiv preprint, 7 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.05044)] [[Project](https://ziweny11.github.io/photoreg/)] [[Video](https://www.youtube.com/watch?v=BmBtd8aFrV0&t=4s)]  [[Code](https://github.com/ziweny11/PhotoRegCodes)]

**Variational Bayes Gaussian Splatting**<br>
*Toon Van de Maele, Ozan Catal, Alexander Tschantz, Christopher L. Buckley, Tim Verbelen*<br>
arXiv preprint, 4 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.03592)]

**VR-Splatting: Foveated Radiance Field Rendering via 3D Gaussian Splatting and Neural Points**<br>
*Linus Franke, Laura Fink, Marc Stamminger*<br>
arXiv preprint, 23 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.17932)] [[Project](https://lfranke.github.io/vr_splatting/)]

**ODGS: 3D Scene Reconstruction from Omnidirectional Images with 3D Gaussian Splattings**<br>
*Suyoung Lee, Jaeyoung Chung, Jaeyoo Huh, Kyoung Mu Lee*<br>
arXiv preprint, 28 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.20686)] [[Code](https://github.com/esw0116/ODGS)]

**DyGASR: Dynamic Generalized Exponential Splatting with Surface Alignment for Accelerated 3D Mesh Reconstruction**<br>
*Shengchao Zhao, Yundong Li*<br>
arXiv preprint, 14 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.09156)]

**Projecting Gaussian Ellipsoids While Avoiding Affine Projection Approximation**<br>
*Han Qi, Tao Cai, Xiyue Han*<br>
arXiv preprint, 12 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.07579)]

**SplatFormer: Point Transformer for Robust 3D Gaussian Splatting**<br>
*Yutong Chen, Marko Mihajlovic, Xiyi Chen, Yiming Wang, Sergey Prokudin, Siyu Tang*<br>
arXiv preprint, 10 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.06390)] [[Code](https://github.com/ChenYutongTHU/SplatFormer)] [[Project](https://sergeyprokudin.github.io/splatformer/)]

**BillBoard Splatting (BBSplat): Learnable Textured Primitives for Novel View Synthesis**<br>
*David Svitov, Pietro Morerio, Lourdes Agapito, Alessio Del Bue*<br>
arXiv preprint, 13 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.08508)]

**Mini-Splatting2: Building 360 Scenes within Minutes via Aggressive Gaussian Densification**<br>
*Guangchi Fang, Bing Wang*<br>
19 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.12788)]

**Beyond Gaussians: Fast and High-Fidelity 3D Splatting with Linear Kernels**<br>
*Haodong Chen, Runnan Chen, Qiang Qu, Zhaoqing Wang, Tongliang Liu, Xiaoming Chen, Yuk Ying Chung*<br>
19 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.12440)]

## 3DGS with Ray Tracing

**Don't Splat your Gaussians: Volumetric Ray-Traced Primitives for Modeling and Rendering Scattering and Emissive Media**<br>
*Jorge Condor, Sebastien Speierer, Lukas Bode, Aljaz Bozic, Simon Green, Piotr Didyk, Adrian Jarabo*<br>
arXiv preprint, 24 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.15425)]

**Unified Gaussian Primitives for Scene Representation and Rendering**<br>
*Yang Zhou, Songyin Wu, Ling-Qi Yan*<br>
arXiv preprint, 14 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.09733)]

**3D Gaussian Ray Tracing: Fast Tracing of Particle Scenes**<br>
*Nicolas Moenne-Loccoz, Ashkan Mirzaei, Or Perel, Riccardo de Lutio, Janick Martinez Esturo, Gavriel State, Sanja Fidler, Nicholas Sharp, Zan Gojcic*<br>
arXiv preprint, 9 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.07090)]

**RayGauss: Volumetric Gaussian-Based Ray Casting for Photorealistic Novel View Synthesis**<br>
*Hugo Blanc, Jean-Emmanuel Deschaud, Alexis Paljic*<br>
arXiv preprint, 6 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.03356)] [[Project](https://raygauss.github.io/)]

**EVER: Exact Volumetric Ellipsoid Rendering for Real-time View Synthesis**<br>
*Alexander Mai, Peter Hedman, George Kopanas, Dor Verbin, David Futschik, Qiangeng Xu, Falko Kuester, Jon Barron, Yinda Zhang*<br>
arXiv preprint, 2 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.01804)] [[Project](https://half-potato.gitlab.io/posts/ever/)] [[Video](https://www.bilibili.com/video/BV1atxXeREWg/)]

## 3DGS Acceleration

**EAGLES: Efficient Accelerated 3D Gaussians with Lightweight EncodingS**<br>
*Sharath Girish, Kamal Gupta, Abhinav Shrivastava*<br>
arXiv preprint, 7 Dec, 2023<br>
[[arXiv](https://arxiv.org/abs/2312.04564)] [[Project](https://efficientgaussian.github.io/)] [[Code](https://github.com/Sharath-girish/efficientgaussian)]

:fire:**StopThePop: Sorted Gaussian Splatting for View-Consistent Real-time Rendering**<br>
*Lukas Radl, Michael Steiner, Mathias Parger, Alexander Weinrauch, Bernhard Kerbl, Markus Steinberger*<br>
SIGGRAPH 2024, 1 Feb 2024<br>
[[arXiv](https://arxiv.org/abs/2402.00525)] [[Project](https://r4dl.github.io/StopThePop/)] [[Code](https://github.com/r4dl/StopThePop)] [[Video](https://www.youtube.com/watch?v=EmcXtHYhigk)]


**GES: Generalized Exponential Splatting for Efficient Radiance Field Rendering**<br>
*Abdullah Hamdi, Luke Melas-Kyriazi, Guocheng Qian, Jinjie Mai, Ruoshi Liu, Carl Vondrick, Bernard Ghanem, Andrea Vedaldi*<br>
CVPR 2024, 15 Feb 2024<br>
[[arXiv](https://arxiv.org/abs/2402.10128)] [[Project](https://abdullahamdi.com/ges/)] [[Code](https://github.com/ajhamdi/ges-splatting)] [[Video](https://www.youtube.com/watch?v=edSvNy3roV8&feature=youtu.be)]

**OmniGS: Omnidirectional Gaussian Splatting for Fast Radiance Field Reconstruction using Omnidirectional Images**<br>
*Longwei Li, Huajian Huang, Sai-Kit Yeung, Hui Cheng*<br>
arXiv preprint, 4 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.03202)]

**Hash3D: Training-free Acceleration for 3D Generation**<br>
*Xingyi Yang, Xinchao Wang*<br>
arXiv preprint, 9 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.06091)] [[Project](https://adamdad.github.io/hash3D/)] [[Code](https://github.com/Adamdad/hash3D)]

**RTGS: Enabling Real-TimeGaussianSplatting on Mobile Devices Using Efficiency-Guided Pruning and Foveated Rendering**<br>
*Weikai Lin, Yu Feng, Yuhao Zhu*<br>
arXiv preprint, 29 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2407.00435)] [[Code](https://github.com/horizon-research/Fov-3DGS)]

**Low Latency Point Cloud Rendering with Learned Splatting**<br>
*Yueyu Hu, Ran Gong, Qi Sun, Yao Wang*<br>
CVPR 2024 Workshop on AIS, 24 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.16504)] [[Code](https://github.com/huzi96/gaussian-pcloud-render)]

**Sort-free Gaussian Splatting via Weighted Sum Rendering**<br>
*Qiqi Hou, Randall Rauwendaal, Zifeng Li, Hoang Le, Farzad Farhadzadeh, Fatih Porikli, Alexei Bourd, Amir Said*<br>
arXiv preprint, 24 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.18931)]

## 3DGS Geometry Reconstruction

**SuGaR: Surface-Aligned Gaussian Splatting for Efficient 3D Mesh Reconstruction and High-Quality Mesh Rendering**<br>
*Antoine Guédon, Vincent Lepetit*<br>
arXiv preprint, 21 Nov 2023<br>
[[arXiv](https://arxiv.org/abs/2311.12775)] [[Project](https://imagine.enpc.fr/~guedona/sugar/)]

**NeuSG: Neural Implicit Surface Reconstruction with 3D Gaussian Splatting Guidance**<br>
*Hanlin Chen, Chen Li, Gim Hee Lee*<br>
arXiv preprint, 1 Dec, 2023<br>
[[arXiv](https://arxiv.org/abs/2312.00846)]

:fire:**2D Gaussian Splatting for Geometrically Accurate Radiance Fields**<br>
*Binbin Huang, Zehao Yu, Anpei Chen, Andreas Geiger, Shenghua Gao*<br>
SIGGRAPH 2024, 26 Mar 2024<br>
[[arXiv](https://zhuanlan.zhihu.com/p/689046399)] [[Project](https://surfsplatting.github.io/)] [[Code](https://github.com/hbb1/2d-gaussian-splatting?tab=readme-ov-file)] [[Video](https://www.youtube.com/watch?v=oaHCtB6yiKU)]

**GSDF: 3DGS Meets SDF for Improved Rendering and Reconstruction**<br>
*Mulin Yu, Tao Lu, Linning Xu, Lihan Jiang, Yuanbo Xiangli, Bo Dai*<br>
arXiv preprint, 25 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.16964)] [[Project](https://city-super.github.io/GSDF/)] [[Code](https://github.com/city-super/GSDF)]

**Modeling uncertainty for Gaussian Splatting**<br>
*Luca Savant, Diego Valsesia, Enrico Magli*<br>
arXiv preprint, 27 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.18476)]

**Surface Reconstruction from Gaussian Splatting via Novel Stereo Views**<br>
*Yaniv Wolf, Amit Bracha, Ron Kimmel*<br>
arXiv preprint, 2 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.01810)] [[Project](https://gs2mesh.github.io/)]

**Gaussian Opacity Fields: Efficient and Compact Surface Reconstruction in Unbounded Scenes**<br>
*Zehao Yu, Torsten Sattler, Andreas Geiger*<br>
arXiv preprint, 16 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.10772)] [[Project](https://niujinshuchong.github.io/gaussian-opacity-fields/)] [[Code](https://github.com/autonomousvision/gaussian-opacity-fields)]

**Dynamic Gaussians Mesh: Consistent Mesh Reconstruction from Monocular Videos**<br>
*Isabella Liu, Hao Su, Xiaolong Wang*<br>
arXiv preprint, 18 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.12379)] [[Project](https://www.liuisabella.com/DG-Mesh/)]

**Direct Learning of Mesh and Appearance via 3D Gaussian Splatting**<br>
*Ancheng Lin, Jun Li*<br>
arXiv preprint, 11 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.06945)]

**TetSphere Splatting: Representing High-Quality Geometry with Lagrangian Volumetric Meshes**<br>
*Minghao Guo, Bohan Wang, Kaiming He, Wojciech Matusik*<br>
arXiv preprint, 30 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.20283)]

**Tetrahedron Splatting for 3D Generation**<br>
*Chun Gu, Zeyu Yang, Zijie Pan, Xiatian Zhu, Li Zhang*<br>
arXiv preprint, 3 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.01579)] [[Code](https://github.com/fudan-zvg/tet-splatting)]

**RaDe-GS: Rasterizing Depth in Gaussian Splatting**<br>
*Baowen Zhang, Chuan Fang, Rakesh Shrestha, Yixun Liang, Xiaoxiao Long, Ping Tan*<br>
arXiv preprint, 3 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.01467)]

**Trim 3D Gaussian Splatting for Accurate Geometry Representation**<br>
*Lue Fan, Yuxue Yang, Minxing Li, Hongsheng Li, Zhaoxiang Zhang*<br>
arXiv preprint, 11 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.07499)] [[Project](https://trimgs.github.io/)] [[Code](https://github.com/YuxueYang1204/TrimGS)]

:fire:**PGSR: Planar-based Gaussian Splatting for Efficient and High-Fidelity Surface Reconstruction**<br>
*Danpeng Chen, Hai Li, Weicai Ye, Yifan Wang, Weijian Xie, Shangjin Zhai, Nan Wang, Haomin Liu, Hujun Bao, Guofeng Zhang*<br>
arXiv prepreint, 10 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.06521)] [[Project](https://zju3dv.github.io/pgsr/)] [[Code](https://github.com/zju3dv/PGSR)]

**VCR-GauS: View Consistent Depth-Normal Regularizer for Gaussian Surface Reconstruction**<br>
*Hanlin Chen, Fangyin Wei, Chen Li, Tianxin Huang, Yunsong Wang, Gim Hee Lee*<br>
arXiv preprint, 9 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.05774)]

**Projecting Radiance Fields to Mesh Surfaces**<br>
*Adrian Xuan Wei Lim, Lynnette Hui Xian Ng, Nicholas Kyger, Tomo Michigami, Faraz Baghernezhad*<br>
SIGGRAPH Poster 2024, 17 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.11570)]

**2DGH: 2D Gaussian-Hermite Splatting for High-quality Rendering and Better Geometry Reconstruction**<br>
*Ruihan Yu, Tianyu Huang, Jingwang Ling, Feng Xu*<br>
arXiv preprint, 30 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.16982)]

**Spurfies: Sparse Surface Reconstruction using Local Geometry Priors**<br>
*Kevin Raj, Christopher Wewer, Raza Yunus, Eddy Ilg, Jan Eric Lenssen*<br>
arXiv preprint, 29 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.16544)] [[Project](https://geometric-rl.mpi-inf.mpg.de/spurfies/)]

**Spiking GS: Towards High-Accuracy and Low-Cost Surface Reconstruction via Spiking Neuron-based Gaussian Splatting**<br>
*Weixing Zhang, Zongrui Li, De Ma, Huajin Tang, Xudong Jiang, Qian Zheng, Gang Pan*<br>
arXiv preprint, 9 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.07266)] [[Code](https://github.com/zju-bmi-lab/SpikingGS)]

**Normal-GS: 3D Gaussian Splatting with Normal-Involved Rendering**<br>
*Meng Wei, Qianyi Wu, Jianmin Zheng, Hamid Rezatofighi, Jianfei Cai*<br>
NeurIPS 2024, 27 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.20593)]

"fire:**GVKF: Gaussian Voxel Kernel Functions for Highly Efficient Surface Reconstruction in Open Scenes**<br>
*Gaochao Song, Chong Cheng, Hao Wang*<br>
NeurIPS 2024, 4 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.01853)]

## 3DGS+Mesh For Reconstruction

**Integrating Meshes and 3D Gaussians for Indoor Scene Reconstruction with SAM Mask Guidance**<br>
*Jiyeop Kim, Jongwoo Lim*<br>
arXiv preprint, 23 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.16173)]

**Enhancement of 3D Gaussian Splatting using Raw Mesh for Photorealistic Recreation of Architectures**<br>
*Ruizhe Wang, Chunliang Hua, Tomakayev Shingys, Mengyuan Niu, Qingxin Yang, Lizhong Gao, Yi Zheng, Junyan Yang, Qiao Wang*<br>
arXiv preprint, 22 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.15435)]

## 3DGS Based Dynamic Scene

**Dynamic 3D Gaussians: Tracking by Persistent Dynamic View Synthesis**<br>
*Jonathon Luiten, Georgios Kopanas, Bastian Leibe, Deva Ramanan*<br>
arXiv preprint, 18 Aug 2023<br>
[[arXiv](https://arxiv.org/abs/2308.09713)] [[Project](https://dynamic3dgaussians.github.io/)] [[Github](https://github.com/JonathonLuiten/Dynamic3DGaussians)]

:fire:**Deformable 3D Gaussians for High-Fidelity Monocular Dynamic Scene Reconstruction**<br>
*Ziyi Yang, Xinyu Gao, Wen Zhou, Shaohui Jiao, Yuqing Zhang, Xiaogang Jin*<br>
arXiv preprint, 22 Sep 2023<br>
[[arXiv](https://arxiv.org/abs/2309.13101)]

**4D Gaussian Splatting for Real-Time Dynamic Scene Rendering**<br>
*Guanjun Wu, Taoran Yi, Jiemin Fang, Lingxi Xie, Xiaopeng Zhang, Wei Wei, Wenyu Liu, Qi Tian, Xinggang Wang*<br>
arXiv preprint, 12 Oct 2023<br>
[[arXiv](https://arxiv.org/abs/2310.08528)] [[Project](https://guanjunwu.github.io/4dgs/)] [[Github](https://github.com/hustvl/4DGaussians)]

**Real-time Photorealistic Dynamic Scene Representation and Rendering with 4D Gaussian Splatting**<br>
*Zeyu Yang, Hongye Yang, Zijie Pan, Xiatian Zhu, Li Zhang*<br>
arXiv preprint, 16 Oct 2023<br>
[[arXiv](https://arxiv.org/abs/2310.10642)]

**Neural Parametric Gaussians for Monocular Non-Rigid Object Reconstruction**<br>
*Devikalyan Das, Christopher Wewer, Raza Yunus, Eddy Ilg, Jan Eric Lenssen*<br>
arXiv preprint, 2 Dec 2023<br>
[[arXiv](https://arxiv.org/abs/2312.01196)]

**Gaussian-Flow: 4D Reconstruction with Dynamic 3D Gaussian Particle**<br>
*Youtian Lin, Zuozhuo Dai, Siyu Zhu, Yao Yao*<br>
arXiv preprint, 6 Dec 2023<br>
[[arXiv](https://arxiv.org/abs/2312.03431)]

**CoGS: Controllable Gaussian Splatting**<br>
*Heng Yu, Joel Julin, Zoltán Á. Milacski, Koichiro Niinuma, László A. Jeni*<br>
CVPR 2024, 9 Dec 2023<br>
[[arXiv](https://arxiv.org/abs/2312.05664)]

**GauFRe: Gaussian Deformation Fields for Real-time Dynamic Novel View Synthesis**<br>
*Yiqing Liang, Numair Khan, Zhengqin Li, Thu Nguyen-Phuoc, Douglas Lanman, James Tompkin, Lei Xiao*<br>
arXiv preprint, 18 Dec 2023<br>
[[arXiv](https://arxiv.org/abs/2312.11458)] [[Project](https://lynl7130.github.io/gaufre/index.html)]

:fire:**SC-GS: Sparse-Controlled Gaussian Splatting for Editable Dynamic Scenes**<br>
*Yi-Hua Huang, Yang-Tian Sun, Ziyi Yang, Xiaoyang Lyu, Yan-Pei Cao, Xiaojuan Qi*<br>
CVPR 2024, 4 Dec 2023<br>
[[arXiv](https://arxiv.org/abs/2312.14937)] [[Project](https://yihua7.github.io/SC-GS-web/)] [[Code](https://github.com/yihua7/SC-GS)] [[Video](https://www.youtube.com/watch?v=CYQYX_0xi5E&feature=youtu.be)]

**Spacetime Gaussian Feature Splatting for Real-Time Dynamic View Synthesis**<br>
*Zhan Li, Zhang Chen, Zhong Li, Yi Xu*<br>
CVPR 2024, 28 Dec 2023<br>
[[arXiv](https://arxiv.org/abs/2312.16812)] [[Project](https://oppo-us-research.github.io/SpacetimeGaussians-website/)] [[Code](https://github.com/oppo-us-research/SpacetimeGaussians)] [[Video](https://www.youtube.com/watch?v=YsPPmf-E6Lg)]

**4D Gaussian Splatting: Towards Efficient Novel View Synthesis for Dynamic Scenes**<br>
*Yuanxing Duan, Fangyin Wei, Qiyu Dai, Yuhang He, Wenzheng Chen, Baoquan Chen*<br>
arXiv preprint, 5 Feb 2024<br>
[[arXiv](https://arxiv.org/abs/2402.03307)] [[Code](https://github.com/weify627/4D-Rotor-Gaussians?tab=readme-ov-file)]

**Mesh-based Gaussian Splatting for Real-time Large-scale Deformation**<br>
*Lin Gao, Jie Yang, Bo-Tao Zhang, Jia-Mu Sun, Yu-Jie Yuan, Hongbo Fu, Yu-Kun Lai*<br>
arXiv preprint, 7 Feb 2024<br>
[[arXiv](https://arxiv.org/abs/2402.04796)]

**GaussianFlow: Splatting Gaussian Dynamics for 4D Content Creation**<br>
*Quankai Gao, Qiangeng Xu, Zhe Cao, Ben Mildenhall, Wenchao Ma, Le Chen, Danhang Tang, Ulrich Neumann*<br>
arXiv preprint, 19 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.12365)] [[Project](https://zerg-overmind.github.io/GaussianFlow.github.io/)] [[Code](https://github.com/Zerg-Overmind/GaussianFlow)] [[Video](https://www.youtube.com/watch?v=0qRcjTw7-YU&feature=youtu.be)]

**Per-Gaussian Embedding-Based Deformation for Deformable 3D Gaussian Splatting**<br>
*Jeongmin Bae, Seoha Kim, Youngsik Yun, Hahyun Lee, Gun Bang, Youngjung Uh*<br>
arXiv preprint, 4 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.03613)] [[Project](https://jeongminb.github.io/e-d3dgs/)] [[Code](https://github.com/JeongminB/E-D3DGS)]

**3D Geometry-aware Deformable Gaussian Splatting for Dynamic View Synthesis**<br>
*Zhicheng Lu, Xiang Guo, Le Hui, Tianrui Chen, Min Yang, Xiao Tang, Feng Zhu, Yuchao Dai*<br>
CVPR 2024, 9 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.06270)] [[Project](https://npucvr.github.io/GaGS/)]

**MoSca: Dynamic Gaussian Fusion from Casual Videos via 4D Motion Scaffolds**<br>
*Jiahui Lei, Yijia Weng, Adam Harley, Leonidas Guibas, Kostas Daniilidis*<br>
arXiv preprint, 27 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.17421)] [[Project](https://www.cis.upenn.edu/~leijh/projects/mosca/)] [[Video](https://www.youtube.com/watch?v=to869D5V7gQ)]

**GSDeformer: Direct Cage-based Deformation for 3D Gaussian Splatting**<br>
*Jiajun Huang, Hongchuan Yu*<br>
arXiv preprint, 24 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.15491)] [[Project](https://jhuangbu.github.io/gsdeformer/)] [[Video](https://jhuangbu.github.io/gsdeformer/static/videos/gsdeformer-final-video.mp4)]

**GFlow: Recovering 4D World from Monocular Video**<br>
*Shizun Wang, Xingyi Yang, Qiuhong Shen, Zhenxiang Jiang, Xinchao Wang*<br>
arXiv preprint, 28 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.18426)] [[Project](https://littlepure2333.github.io/GFlow/)]

**A Refined 3D Gaussian Representation for High-Quality Dynamic Scene Reconstruction**<br>
*Bin Zhang, Bi Zeng, Zexin Peng*<br>
arXiv preprint, 28 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.17891)]

**Object-centric Reconstruction and Tracking of Dynamic Unknown Objects using 3D Gaussian Splatting**<br>
*Kuldeep R Barad, Antoine Richard, Jan Dentler, Miguel Olivares-Mendez, Carol Martinez*<br>
IEEE Space Robotics 2024, 30 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.20104)]

**GaussianPrediction: Dynamic 3D Gaussian Prediction for Motion Extrapolation and Free View Synthesis**<br>
*Boming Zhao, Yuan Li, Ziyu Sun, Lin Zeng, Yujun Shen, Rui Ma, Yinda Zhang, Hujun Bao, Zhaopeng Cui*<br>
SIGGRAPH 2024, 30 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.19745)] [[Project](https://zju3dv.github.io/gaussian-prediction/)]

**Reconstructing and Simulating Dynamic 3D Objects with Mesh-adsorbed Gaussian Splatting**<br>
*Shaojie Ma, Yawei Luo, Yi Yang*<br>
arXiv preprint, 3 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.01593)] [[Project](https://wcwac.github.io/MaGS-page/)] [[Code](https://github.com/wcwac/MaGS)]

**Self-Calibrating 4D Novel View Synthesis from Monocular Videos Using Gaussian Splatting**<br>
*Fang Li, Hao Zhang, Narendra Ahuja*<br>
arXiv preprint, 3 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.01042)]  [[Code](https://github.com/fangli333/SC-4DGS)]

:fire:**Superpoint Gaussian Splatting for Real-Time High-Fidelity Dynamic Scene Reconstruction**<br>
*Diwen Wan, Ruijie Lu, Gang Zeng*<br>
ICML 2024, 6 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.03697)] [[Project](https://dnvtmf.github.io/SP_GS.github.io/)] [[Code](https://github.com/dnvtmf/SP_GS)]

**MoDGS: Dynamic Gaussian Splatting from Causually-captured Monocular Videos**<br>
*Qingming Liu, Yuan Liu, Jiepeng Wang, Xianqiang Lv, Peng Wang, Wenping Wang, Junhui Hou*<br>
arXiv preprint, 1 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.00434)]

**DGD: Dynamic 3D Gaussians Distillation**<br>
*Isaac Labe, Noam Issachar, Itai Lang, Sagie Benaim*<br>
arXiv preprint, 29 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.19321)] [[Project](https://isaaclabe.github.io/DGD-Website/)] [[Code](https://github.com/Isaaclabe/DGD-Dynamic-3D-Gaussians-Distillation)]

**Modeling Ambient Scene Dynamics for Free-view Synthesis**<br>
*Meng-Li Shih, Jia-Bin Huang, Changil Kim, Rajvi Shah, Johannes Kopf, Chen Gao*<br>
SIGGRAPH 2024, 13 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.09395)] [[Project](https://ambientgaussian.github.io/)]

**Dynamic Gaussian Marbles for Novel View Synthesis of Casual Monocular Videos**<br>
*Colton Stearns, Adam Harley, Mikaela Uy, Florian Dubost, Federico Tombari, Gordon Wetzstein, Leonidas Guibas*<br>
arXiv preprint, 26 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.18717)]

**Gaussian Splatting LK**<br>
*Liuyue Xie, Joel Julin, Koichiro Niinuma, Laszlo A. Jeni*<br>
arXiv preprint, 16 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.11309)]

**S4D: Streaming 4D Real-World Reconstruction with Gaussians and 3D Control Points**<br>
*Bing He, Yunuo Chen, Guo Lu, Li Song, Wenjun Zhang*<br>
arXiv preprint, 23 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.13036)]

**SplatFields: Neural Gaussian Splats for Sparse 3D and 4D Reconstruction**<br>
*Marko Mihajlovic, Sergey Prokudin, Siyu Tang, Robert Maier, Federica Bogo, Tony Tung, Edmond Boyer*<br>
ECCV 2024, 17 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.11211)]

**MotionGS: Exploring Explicit Motion Guidance for Deformable 3D Gaussian Splatting**<br>
*Ruijie Zhu, Yanzhe Liang, Hanzhi Chang, Jiacheng Deng, Jiahao Lu, Wenfei Yang, Tianzhu Zhang, Yongdong Zhang*<br>
NeurIPS 2024, 10 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.07707)] [[Project](https://ruijiezhu94.github.io/MotionGS_page/)]

**DN-4DGS: Denoised Deformable Network with Temporal-Spatial Aggregation for Dynamic Scene Rendering**<br>
*Jiahao Lu, Jiacheng Deng, Ruijie Zhu, Yanzhe Liang, Wenfei Yang, Tianzhu Zhang, Xu Zhou*<br>
NeurIPS 2024, 17 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.13607)]

**MEGA: Memory-Efficient 4D Gaussian Splatting for Dynamic Scenes**<br>
*Xinjie Zhang, Zhening Liu, Yifan Zhang, Xingtong Ge, Dailan He, Tongda Xu, Yan Wang, Zehong Lin, Shuicheng Yan, Jun Zhang*<br>
arXiv preprint, 17 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.13613)]

**Fully Explicit Dynamic Gaussian Splatting**<br>
*Junoh Lee, Chang-Yeon Won, Hyunjun Jung, Inhwan Bae, Hae-Gon Jeon*<br>
NeurIPS 2024, 21 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.15629)]

**FreeGaussian: Guidance-free Controllable 3D Gaussian Splats with Flow Derivatives**<br>
*Qizhi Chen, Delin Qu, Yiwen Tang, Haoming Song, Yiting Zhang, Dong Wang, Bin Zhao, Xuelong Li*<br>
arXiv preprint, 29 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.22070)] [[Project](https://freegaussian.github.io/)] [[Code](https://github.com/freegaussian/freegaussian.github.io)]

**Grid4D: 4D Decomposed Hash Encoding for High-fidelity Dynamic Gaussian Splatting**<br>
*Jiawei Xu, Zexin Fan, Jian Yang, Jin Xie*<br>
NeurIPS 2024, 28 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.20815)]

**HiCoM: Hierarchical Coherent Motion for Streamable Dynamic Scene with 3D Gaussian Splatting**<br>
*Qiankun Gao, Jiarui Meng, Chengxiang Wen, Jie Chen, Jian Zhang*<br>
NeurIPS 2024, 12 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.07541)] [[Code](https://github.com/gqk/HiCoM)]

**Adaptive and Temporally Consistent Gaussian Surfels for Multi-view Dynamic Reconstruction**<br>
*Decai Chen, Brianne Oberson, Ingo Feldmann, Oliver Schreer, Anna Hilsmann, Peter Eisert*<br>
arXiv preprint, 10 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.06602)] [[Project](https://fraunhoferhhi.github.io/AT-GS/)] 

**4D Gaussian Splatting in the Wild with Uncertainty-Aware Regularization**<br>
*Mijeong Kim, Jongwoo Lim, Bohyung Han*<br>
NeurIPS 2024, 13 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.08879)]

**Sketch-guided Cage-based 3D Gaussian Splatting Deformation**<br>
*Tianhao Xie, Noam Aigerman, Eugene Belilovsky, Tiberiu Popa*<br>
arXiv preprint, 19 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.12168)]

**TimeFormer: Capturing Temporal Relationships of Deformable 3D Gaussians for Robust Reconstruction**<br>
*DaDong Jiang, Zhihui Ke, Xiaobo Zhou, Zhi Hou, Xianghui Yang, Wenbo Hu, Tie Qiu, Chunchao Guo*<br>
18 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.11941)]  [[Project](https://patrickddj.github.io/TimeFormer/)]

## 3DGS + Depth

:fire:**DNGaussian: Optimizing Sparse-View 3D Gaussian Radiance Fields with Global-Local Depth Normalization**<br>
*Jiahe Li, Jiawei Zhang, Xiao Bai, Jin Zheng, Xin Ning, Jun Zhou, Lin Gu*<br>
CVPR 2024, 11 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.06912)] [[Project](https://fictionarry.github.io/DNGaussian/)] [[Code](https://github.com/Fictionarry/DNGaussian)] [[Video](https://www.youtube.com/watch?v=xmaRI9M3g_M)]

:fire:**DN-Splatter: Depth and Normal Priors for Gaussian Splatting and Meshing**<br>
*Matias Turkulainen, Xuqian Ren, Iaroslav Melekhov, Otto Seiskari, Esa Rahtu, Juho Kannala*<br>
arXiv preprint, 26 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.17822)] 

**HoloGS: Instant Depth-based 3D Gaussian Splatting with Microsoft HoloLens 2**<br>
*Miriam Jäger, Theodor Kapler, Michael Feßenbecker, Felix Birkelbach, Markus Hillemann, Boris Jutzi*<br>
arXiv preprint, 3 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.02005)]

**Self-Evolving Depth-Supervised 3D Gaussian Splatting from Rendered Stereo Pairs**<br>
*Sadra Safadoust, Fabio Tosi, Fatma Güney, Matteo Poggi*<br>
BMVC 2024, 11 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.07456)] [[Project](https://kuis-ai.github.io/StereoGS/)] [[Code](https://github.com/sadrasafa/StereoGS/)]

## 3DGS Based Depth Estimation

**Depth Estimation Based on 3D Gaussian Splatting Siamese Defocus**<br>
*Jinchang Zhang, Ningning Xu, Hao Zhang, Guoyu Lu*<br>
arXiv preprint, 18 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.12323)]

## 3DGS Few-shot Reconstruction

**Depth-Regularized Optimization for 3D Gaussian Splatting in Few-Shot Images**<br>
*Jaeyoung Chung, Jeongtaek Oh, Kyoung Mu Lee*<br>
arXiv preprint, 22 Nov 2023<br>
[[arXiv](https://arxiv.org/abs/2311.13398)]

**FSGS: Real-Time Few-shot View Synthesis using Gaussian Splatting**<br>
*Zehao Zhu, Zhiwen Fan, Yifan Jiang, Zhangyang Wang*<br>
arXiv preprint, 1 Dec 2023<br>
[[arXiv](https://arxiv.org/abs/2312.00451)] [[Project](https://zehaozhu.github.io/FSGS/)]

**Triplane Meets Gaussian Splatting: Fast and Generalizable Single-View 3D Reconstruction with Transformers**<br>
*Zi-Xin Zou, Zhipeng Yu, Yuan-Chen Guo, Yangguang Li, Ding Liang, Yan-Pei Cao, Song-Hai Zhang*<br>
arXiv preprint, 14 Dec 2023<br>
[[arXiv](https://arxiv.org/abs/2312.09147)] [[Project](https://zouzx.github.io/TriplaneGaussian/)] [[Code](https://github.com/VAST-AI-Research/TriplaneGaussian)]

**pixelSplat: 3D Gaussian Splats from Image Pairs for Scalable Generalizable 3D Reconstruction**<br>
*David Charatan, Sizhe Li, Andrea Tagliasacchi, Vincent Sitzmann*<br>
arXiv preprint, 19 Dec 2023<br>
[[arXiv](https://arxiv.org/abs/2312.12337)] [[Project](https://davidcharatan.com/pixelsplat/)] [[Code](https://github.com/dcharatan/pixelsplat)]

**AGG: Amortized Generative 3D Gaussians for Single Image to 3D**<br>
*Dejia Xu, Ye Yuan, Morteza Mardani, Sifei Liu, Jiaming Song, Zhangyang Wang, Arash Vahdat*<br>
arXiv preprint, 8 Jan 2024<br>
[[arXiv](https://arxiv.org/abs/2401.04099)] [[Project](https://ir1d.github.io/AGG/)]

**GaussianObject: Just Taking Four Images to Get A High-Quality 3D Object with Gaussian Splatting**<br>
*Chen Yang, Sikuang Li, Jiemin Fang, Ruofan Liang, Lingxi Xie, Xiaopeng Zhang, Wei Shen, Qi Tian*<br>
arXiv preprint, 15 Feb 2024<br>
[[arXiv](https://arxiv.org/abs/2402.10259)] [[Project](https://gaussianobject.github.io/)]

**FDGaussian: Fast Gaussian Splatting from Single Image via Geometric-aware Diffusion Model**<br>
*Qijun Feng, Zhen Xing, Zuxuan Wu, Yu-Gang Jiang*<br>
arXiv preprint, 15 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.10242)] [[Project](https://qjfeng.net/FDGaussian/)]

**Gamba: Marry Gaussian Splatting with Mamba for single view 3D reconstruction**<br>
*Qiuhong Shen, Xuanyu Yi, Zike Wu, Pan Zhou, Hanwang Zhang, Shuicheng Yan, Xinchao Wang*<br>
arXiv preprint, 27 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.18795)] [[Project](https://florinshen.github.io/gamba-project/)]

:fire:**InstantSplat: Unbounded Sparse-view Pose-free Gaussian Splatting in 40 Seconds**<br>
*Zhiwen Fan, Wenyan Cong, Kairun Wen, Kevin Wang, Jian Zhang, Xinghao Ding, Danfei Xu, Boris Ivanovic, Marco Pavone, Georgios Pavlakos, Zhangyang Wang, Yue Wang*<br>
arXiv preprint, 29 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.20309)] [[Project](https://instantsplat.github.io/)] [[Video](https://youtu.be/_9aQHLHHoEM)]

**CoherentGS: Sparse Novel View Synthesis with Coherent 3D Gaussians**<br>
*Avinash Paliwal, Wei Ye, Jinhui Xiong, Dmytro Kotovenko, Rakesh Ranjan, Vikas Chandra, Nima Khademi Kalantari*<br>
arXiv preprint, 28 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.19495)]  [[Project](https://people.engr.tamu.edu/nimak/Papers/CoherentGS/index.html)]

**Guess The Unseen: Dynamic 3D Scene Reconstruction from Partial 2D Glimpses**<br>
*Inhee Lee, Byungjun Kim, Hanbyul Joo*<br>
arXiv preprint, 22 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.14410)] [[Project](https://snuvclab.github.io/gtu/)]

**GDGS: Gradient Domain Gaussian Splatting for Sparse Representation of Radiance Fields**<br>
*Yuanhao Gong*<br>
arXiv preprint, 8 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.05446)]

**CoR-GS: Sparse-View 3D Gaussian Splatting via Co-Regularization**<br>
*Jiawei Zhang, Jiahe Li, Xiaohan Yu, Lei Huang, Lin Gu, Jin Zheng, Xiao Bai*<br>
arXiv preprint, 20 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.12110)] [[Project](https://jiaw-z.github.io/CoR-GS/)] [[Video](https://youtu.be/O83v9Wrn3c4)]

**Sp2360: Sparse-view 360 Scene Reconstruction using Cascaded 2D Diffusion Priors**<br>
*Soumava Paul, Christopher Wewer, Bernt Schiele, Jan Eric Lenssen*<br>
arXiv preprint, 26 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.16517)]

**A Pixel Is Worth More Than One 3D Gaussians in Single-View 3D Reconstruction**<br>
*Jianghao Shen, Tianfu Wu*<br>
arXiv preprint, 30 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.20310)]

**Flash3D: Feed-Forward Generalisable 3D Scene Reconstruction from a Single Image**<br>
*Stanislaw Szymanowicz, Eldar Insafutdinov, Chuanxia Zheng, Dylan Campbell, João F. Henriques, Christian Rupprecht, Andrea Vedaldi*<br>
arXiv preprint, 6 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.04343)] [[Project](https://www.robots.ox.ac.uk/~vgg/research/flash3d/)]

**GSD: View-Guided Gaussian Splatting Diffusion for 3D Reconstruction**<br>
*Yuxuan Mu, Xinxin Zuo, Chuan Guo, Yilin Wang, Juwei Lu, Xiaofeng Wu, Songcen Xu, Peng Dai, Youliang Yan, Li Cheng*<br>
ECCV 2024, 5 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.04237)]

**Self-augmented Gaussian Splatting with Structure-aware Masks for Sparse-view 3D Reconstruction**<br>
*Lingbei Meng, Bi'an Du, Wei Hu*<br>
arXiv preprint, 9 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.04831)]

:fire:**ReconX: Reconstruct Any Scene from Sparse Views with Video Diffusion Model**<br>
*Fangfu Liu, Wenqiang Sun, Hanyang Wang, Yikai Wang, Haowen Sun, Junliang Ye, Jun Zhang, Yueqi Duan*<br>
arXiv preprint, 29 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.16767)] [[Project](https://liuff19.github.io/ReconX/)] [[Video](https://www.youtube.com/watch?v=UuL2nP5rJcI)] [[Code](https://github.com/liuff19/ReconX)]

:fire:**ViewCrafter: Taming Video Diffusion Models for High-fidelity Novel View Synthesis**<br>
*Wangbo Yu, Jinbo Xing, Li Yuan, Wenbo Hu, Xiaoyu Li, Zhipeng Huang, Xiangjun Gao, Tien-Tsin Wong, Ying Shan, Yonghong Tian*<br>
arXiv preprint, 3 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.02048)] [[Project](https://drexubery.github.io/ViewCrafter/)] [[Video](https://www.youtube.com/watch?v=WGIEmu9eXmU)] [[Code](https://github.com/Drexubery/ViewCrafter)]

**LM-Gaussian: Boost Sparse-view 3D Gaussian Splatting with Large Model Priors**<br>
*Hanyang Yu, Xiaoxiao Long, Ping Tan*<br>
arXiv preprint, 5 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.03456)] [[Project](https://hanyangyu1021.github.io/lm-gaussian.github.io/)] [[Video](https://www.youtube.com/watch?v=ic4luAY_Hvk)] [[Code](https://github.com/hanyangyu1021/LMGaussian)]

**Optimizing 3D Gaussian Splatting for Sparse Viewpoint Scene Reconstruction**<br>
*Shen Chen, Jiale Zhou, Lei Li*<br>
arXiv preprint, 5 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.03213)]

**Object Gaussian for Monocular 6D Pose Estimation from Sparse Views**<br>
*Luqing Luo, Shichu Sun, Jiangang Yang, Linfang Zheng, Jinwei Du, Jian Liu*<br>
arXiv preprint, 4 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.02581)]

**Single-View 3D Reconstruction via SO(2)-Equivariant Gaussian Sculpting Networks**<br>
*Ruihan Xu, Anthony Opipari, Joshua Mah, Stanley Lewis, Haoran Zhang, Hanzhe Guo, Odest Chadwicke Jenkins*<br>
RSS 2024, 11 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.07245)]

**Vista3D: Unravel the 3D Darkside of a Single Image**<br>
*Qiuhong Shen, Xingyi Yang, Michael Bi Mi, Xinchao Wang*<br>
ECCV 2024, 18 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.12193)]  [[Code](https://github.com/florinshen/Vista3D)]

**MVPGS: Excavating Multi-view Priors for Gaussian Splatting from Sparse Input Views**<br>
*Wangze Xu, Huachen Gao, Shihe Shen, Rui Peng, Jianbo Jiao, Ronggang Wang*<br>
ECCV 2024, 22 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.14316)] [[Project](https://zezeaaa.github.io/projects/MVPGS/)] [[Code](https://github.com/zezeaaa/MVPGS)]

**HiSplat: Hierarchical 3D Gaussian Splatting for Generalizable Sparse-View Reconstruction**<br>
*Shengji Tang, Weicai Ye, Peng Ye, Weihao Lin, Yang Zhou, Tao Chen, Wanli Ouyang*<br>
arXiv preprint, 8 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.06245)] [[Project](https://open3dvlab.github.io/HiSplat/)] [[Code](https://github.com/Open3DVLab/HiSplat)]

**MCGS: Multiview Consistency Enhancement for Sparse-View 3D Gaussian Radiance Fields**<br>
*Yuru Xiao, Deming Zhai, Wenbo Zhao, Kui Jiang, Junjun Jiang, Xianming Liu*<br>
arXiv preprint, 15 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.11394)]

**Few-shot Novel View Synthesis using Depth Aware 3D Gaussian Splatting**<br>
*Raja Kumar, Vanshika Vats*<br>
ECCV 2024 Workshop S3DSGR, 14 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.11080)] [[Code](https://github.com/raja-kumar/depth-aware-3DGS)]

**3DGS-Enhancer: Enhancing Unbounded 3D Gaussian Splatting with View-consistent 2D Diffusion Priors**<br>
*Xi Liu, Chaoyi Zhou, Siyu Huang*<br>
NeurIPS 2024, 21 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.16266)] [[Project](https://xiliu8006.github.io/3DGS-Enhancer-project/)]

**Binocular-Guided 3D Gaussian Splatting with View Consistency for Sparse View Synthesis**<br>
*Liang Han, Junsheng Zhou, Yu-Shen Liu, Zhizhong Han*<br>
NeurIPS 2024, 24 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.18822)] [[Project](https://hanl2010.github.io/Binocular3DGS/)] [[Code](https://github.com/hanl2010/Binocular3DGS)]

**MVSplat360: Feed-Forward 360 Scene Synthesis from Sparse Views**<br>
*Yuedong Chen, Chuanxia Zheng, Haofei Xu, Bohan Zhuang, Andrea Vedaldi, Tat-Jen Cham, Jianfei Cai*<br>
NeurIPS 2024, 7 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.04924)] [[Project](https://donydchen.github.io/mvsplat360/)]  [[Code](https://github.com/donydchen/mvsplat360)]

**Structure Consistent Gaussian Splatting with Matching Prior for Few-shot Novel View Synthesis**<br>
*Rui Peng, Wangze Xu, Luyang Tang, Liwei Liao, Jianbo Jiao, Ronggang Wang*<br>
NeurIPS 2024, 6 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.03637)] [[Code](https://github.com/prstrive/SCGaussian)]

**FewViewGS: Gaussian Splatting with Few View Matching and Multi-stage Training**<br>
*Ruihong Yin, Vladimir Yugay, Yue Li, Sezer Karaoglu, Theo Gevers*<br>
NeurIPS 2024, 4 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.02229)]

## 3DGS Weak Camera Pose

**COLMAP-Free 3D Gaussian Splatting**<br>
*Yang Fu, Sifei Liu, Amey Kulkarni, Jan Kautz, Alexei A. Efros, Xiaolong Wang*<br>
CVPR 2024, 12 Dec 2023<br>
[[arXiv](https://arxiv.org/abs/2312.07504)] [[Project](https://oasisyang.github.io/colmap-free-3dgs/)] [[Video](https://www.youtube.com/watch?si=kqu3dbXopDdNg0wX&v=mGeVQS4ExK4&feature=youtu.be)]

**iComMa: Inverting 3D Gaussians Splatting for Camera Pose Estimation via Comparing and Matching**<br>
*Yuan Sun, Xuan Wang, Yunfan Zhang, Jie Zhang, Caigui Jiang, Yu Guo, Fei Wang*<br>
arXiv preprint, 14 Dec 2023<br>
[[arXiv](https://arxiv.org/abs/2312.09031)]

**A Construct-Optimize Approach to Sparse View Synthesis without Camera Pose**<br>
*Kaiwen Jiang, Yang Fu, Mukund Varma T, Yash Belhe, Xiaolong Wang, Hao Su, Ravi Ramamoorthi*<br>
arXiv preprint, 6 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.03659)]

:fire:**6DGS: 6D Pose Estimation from a Single Image and a 3D Gaussian Splatting Model**<br>
*Matteo Bortolon, Theodore Tsesmelis, Stuart James, Fabio Poiesi, Alessio Del Bue*<br>
ECCV 2024, 22 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.15484)] [[Project](https://mbortolon97.github.io/6dgs/)] [[Code](https://github.com/mbortolon97/6dgs)] [[Video](https://www.youtube.com/watch?v=SB4ToD93NFA)]

**GSLoc: Efficient Camera Pose Refinement via 3D Gaussian Splatting**<br>
*Changkun Liu, Shuai Chen, Yash Bhalgat, Siyan Hu, Zirui Wang, Ming Cheng, Victor Adrian Prisacariu, Tristan Braud*<br>
arXiv preprint, 20 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.11085)]

**Splatt3R: Zero-shot Gaussian Splatting from Uncalibrated Image Pairs**<br>
*Brandon Smart, Chuanxia Zheng, Iro Laina, Victor Adrian Prisacariu*<br>
arXiv preprint, 25 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.13912)] [[Project](https://splatt3r.active.vision/)] [[Code](https://github.com/btsmart/splatt3r)]

**HGSLoc: 3DGS-based Heuristic Camera Pose Refinement**<br>
*Zhongyan Niu, Zhen Tan*<br>
arXiv preprint, 17 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.10925)]

**GSplatLoc: Grounding Keypoint Descriptors into 3D Gaussian Splatting for Improved Visual Localization**<br>
*Gennady Sidorov, Malik Mohrat, Ksenia Lebedeva, Ruslan Rakhimov, Sergey Kolyubin*<br>
arXiv preprint, 24 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.16502)] [[Project](https://gsplatloc.github.io/)] [[Video](https://www.youtube.com/watch?v=3UKQQPLlqqg)] [[Code](https://github.com/haksorus/gsplatloc)]

**SplatLoc: 3D Gaussian Splatting-based Visual Localization for Augmented Reality**<br>
*Hongjia Zhai, Xiyu Zhang, Boming Zhao, Hai Li, Yijia He, Zhaopeng Cui, Hujun Bao, Guofeng Zhang*<br>
arXiv preprint, 21 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.14067)] [[Project](https://zju3dv.github.io/splatloc/)] [[Code](https://github.com/zhaihongjia/SplatLoc)]

**PF3plat: Pose-Free Feed-Forward 3D Gaussian Splatting**<br>
*Sunghwan Hong, Jaewoo Jung, Heeseong Shin, Jisang Han, Jiaolong Yang, Chong Luo, Seungryong Kim*<br>
arXiv preprint, 29 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.22128)] [[Project](https://cvlab-kaist.github.io/PF3plat/)] [[Code](https://github.com/cvlab-kaist/PF3plat)]

**Generating 3D-Consistent Videos from Unposed Internet Photos**<br>
*Gene Chou, Kai Zhang, Sai Bi, Hao Tan, Zexiang Xu, Fujun Luan, Bharath Hariharan, Noah Snavely*<br>
arXiv preprint, 20 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.13549)]

## 3DGS Object Pose Estimation

**Object Pose Estimation Using Implicit Representation For Transparent Objects**<br>
*Varun Burde, Artem Moroz, Vit Zeman, Pavel Burget*<br>
arXiv preprint, 17 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.13465)]

**GS2Pose: Tow-stage 6D Object Pose Estimation Guided by Gaussian Splatting**<br>
*Jilan Mei, Junbo Li, Cai Meng*<br>
arXiv preprint, 6 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.03807)]

## 3DGS-NeRF Transfer

**NeRFs to Gaussian Splats, and Back**<br>
*Siming He, Zach Osman, Pratik Chaudhari*<br>
arXiv preprint, 15 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.09717)] [[Code](https://github.com/grasp-lyrl/NeRFtoGSandBack)]

## 3DGS Generalization

**GGRt: Towards Generalizable 3D Gaussians without Pose Priors in Real-Time**<br>
*Hao Li, Yuanyuan Gao, Dingwen Zhang, Chenming Wu, Yalun Dai, Chen Zhao, Haocheng Feng, Errui Ding, Jingdong Wang, Junwei Han*<br>
arXiv preprint, 15 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.10147)] [[Project](https://3d-aigc.github.io/GGRt/)]

**latentSplat: Autoencoding Variational Gaussians for Fast Generalizable 3D Reconstruction**<br>
*Christopher Wewer, Kevin Raj, Eddy Ilg, Bernt Schiele, Jan Eric Lenssen*<br>
arXiv preprint, 24 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.16292)] [[Project](https://geometric-rl.mpi-inf.mpg.de/latentsplat/)]

**Fast Generalizable Gaussian Splatting Reconstruction from Multi-View Stereo**<br>
*Tianqi Liu, Guangcong Wang, Shoukang Hu, Liao Shen, Xinyi Ye, Yuhang Zang, Zhiguo Cao, Wei Li, Ziwei Liu*<br>
arXiv preprint, 20 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.12218)] [[Project](https://mvsgaussian.github.io/)] [[Code](https://github.com/TQTQliu/MVSGaussian)] [[Video](https://www.youtube.com/watch?v=4TxMQ9RnHMA)]

**GS-Net: Generalizable Plug-and-Play 3D Gaussian Splatting Module**<br>
*Yichen Zhang, Zihan Wang, Jiali Han, Peilin Li, Jiaxun Zhang, Jianqiang Wang, Lei He, Keqiang Li*<br>
arXiv preprint, 17 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.11307)]

**DepthSplat: Connecting Gaussian Splatting and Depth**<br>
*Haofei Xu, Songyou Peng, Fangjinhua Wang, Hermann Blum, Daniel Barath, Andreas Geiger, Marc Pollefeys*<br>
arXiv preprint, 17 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.13862)] [[Project](https://haofeixu.github.io/depthsplat/)] [[Code](https://github.com/cvg/depthsplat)]

:fire:**No Pose, No Problem: Surprisingly Simple 3D Gaussian Splats from Sparse Unposed Images**<br>
*Botao Ye, Sifei Liu, Haofei Xu, Xueting Li, Marc Pollefeys, Ming-Hsuan Yang, Songyou Peng*<br>
arXiv preprint, 31 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.24207)] [[Project](https://noposplat.github.io/)] [[Code](https://github.com/cvg/NoPoSplat)]

**Epipolar-Free 3D Gaussian Splatting for Generalizable Novel View Synthesis**<br>
*Zhiyuan Min, Yawei Luo, Jianwen Sun, Yi Yang*<br>
NeurIPS 2024, 30 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.22817)] [[Project](https://tatakai1.github.io/efreesplat/)]

**GPS-Gaussian+: Generalizable Pixel-wise 3D Gaussian Splatting for Real-Time Human-Scene Rendering from Sparse Views**<br>
*Boyao Zhou, Shunyuan Zheng, Hanzhang Tu, Ruizhi Shao, Boning Liu, Shengping Zhang, Liqiang Nie, Yebin Liu*<br>
CVPR 2024, 18 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.11363)] [[Project](https://yaourtb.github.io/GPS-Gaussian+/)]

## 3DGS Indoor Scene Reconstruction

**360-GS: Layout-guided Panoramic Gaussian Splatting For Indoor Roaming**<br>
*Jiayang Bai, Letian Huang, Jie Guo, Wen Gong, Yuanqi Li, Yanwen Guo*<br>
arXiv preprint, 1 Feb 2024<br>
[[arXiv]](https://arxiv.org/abs/2402.00763)

**MonoSelfRecon: Purely Self-Supervised Explicit Generalizable 3D Reconstruction of Indoor Scenes from Monocular RGB Views**<br>
*Runfa Li, Upal Mahbub, Vasudev Bhaskaran, Truong Nguyen*<br>
arXiv preprint, 10 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.06753)]

**FreeSplat: Generalizable 3D Gaussian Splatting Towards Free-View Synthesis of Indoor Scenes**<br>
*Yunsong Wang, Tianxin Huang, Hanlin Chen, Gim Hee Lee*<br>
arXiv preprint, 28 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.17958)]

**Scalable Indoor Novel-View Synthesis using Drone-Captured 360 Imagery with 3D Gaussian Splatting**<br>
*Yuanbo Chen, Chengyu Zhang, Jason Wang, Xuefan Gao, Avideh Zakhor*<br>
ECCV 2024 Workshop S3DSGR, 15 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.11285)]

## 3DGS Based Wild Scene Reconstruction

**SWAG: Splatting in the Wild images with Appearance-conditioned Gaussians**<br>
*Hiba Dahmani, Moussab Bennehar, Nathan Piasco, Luis Roldao, Dzmitry Tsishkou*<br>
arXiv preprint, 15 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.10427)]

**Gaussian in the Wild: 3D Gaussian Splatting for Unconstrained Image Collections**<br>
*Dongbin Zhang, Chuming Wang, Weitao Wang, Peihao Li, Minghan Qin, Haoqian Wang*<br>
arXiv preprint, 23 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.15704)]

**WE-GS: An In-the-wild Efficient 3D Gaussian Representation for Unconstrained Photo Collections**<br>
*Yuze Wang, Junyi Wang, Yue Qi*<br>
arXiv preprint, 4 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.02407)] [[Project](https://yuzewang1998.github.io/we-gs.github.io/)]

**Wild-GS: Real-Time Novel View Synthesis from Unconstrained Photo Collections**<br>
*Jiacong Xu, Yiqun Mei, Vishal M. Patel*<br>
arXiv preprint, 14 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.10373)]

:fire:**WildGaussians: 3D Gaussian Splatting in the Wild**<br>
*Jonas Kulhanek, Songyou Peng, Zuzana Kukelova, Marc Pollefeys, Torsten Sattler*<br>
NeurIPS 2024, 11 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.08447)] [[Project](https://wild-gaussians.github.io/)] [[Code](https://github.com/jkulhanek/wild-gaussians/)]

## 3DGS Based Large Scene Reconstruction
**Periodic Vibration Gaussian: Dynamic Urban Scene Reconstruction and Real-time Rendering**<br>
*Yurui Chen, Chun Gu, Junzhe Jiang, Xiatian Zhu, Li Zhang*<br>
arXiv preprint, 30 Nov 2023<br>
[[arXiv](https://arxiv.org/abs/2311.18561)] [[Project](https://fudan-zvg.github.io/PVG/)]

**GauU-Scene: A Scene Reconstruction Benchmark on Large Scale 3D Reconstruction Dataset Using Gaussian Splatting**<br>
*Butian Xiong, Zhuo Li, Zhen Li*<br>
arXiv preprint, 25 Jan 2024<br>
[[arXiv](https://arxiv.org/abs/2401.14032)]

**GaussianPro: 3D Gaussian Splatting with Progressive Propagation**<br>
*Kai Cheng, Xiaoxiao Long, Kaizhi Yang, Yao Yao, Wei Yin, Yuexin Ma, Wenping Wang, Xuejin Chen*<br>
arXiv preprint, 22 Feb 2024<br>
[[arXiv](https://arxiv.org/abs/2402.14650)] [[Project](https://kcheng1021.github.io/gaussianpro.github.io/)] [[Code](https://github.com/kcheng1021/GaussianPro)]

:fire:**VastGaussian: Vast 3D Gaussians for Large Scene**<br>
*Jiaqi Lin, Zhihao Li, Xiao Tang, Jianzhuang Liu, Shiyong Liu, Jiayue Liu, Yangdi Lu, Xiaofei Wu, Songcen Xu, Youliang Yan, Wenming Yang*<br>
CVPR 2024, 27 Feb, 2024<br>
[[arXiv](https://arxiv.org/abs/2402.17427)] [[Project](https://vastgaussian.github.io/)]


:fire:**Octree-GS: Towards Consistent Real-time Rendering with LOD-Structured 3D Gaussians**<br>
*Kerui Ren, Lihan Jiang, Tao Lu, Mulin Yu, Linning Xu, Zhangkai Ni, Bo Dai*<br>
arXiv preprint, 26 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.17898)] [[Project](https://city-super.github.io/octree-gs/)] [[Code](https://github.com/city-super/Octree-GS)]

**SGD: Street View Synthesis with Gaussian Splatting and Diffusion Prior**<br>
*Zhongrui Yu, Haoran Wang, Jinze Yang, Hanzhang Wang, Zeke Xie, Yunfeng Cai, Jiale Cao, Zhong Ji, Mingming Sun*<br>
arXiv preprint, 29 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.20079)]

**HO-Gaussian: Hybrid Optimization of 3D Gaussian Splatting for Urban Scenes**<br>
*Zhuopeng Li, Yilin Zhang, Chenming Wu, Jianke Zhu, Liangjun Zhang*<br>
arXiv preprint, 29 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.20032)]

:fire:**CityGaussian: Real-time High-quality Large-Scale Scene Rendering with Gaussians**<br>
*Yang Liu, He Guan, Chuanchen Luo, Lue Fan, Junran Peng, Zhaoxiang Zhang*<br>
ECCV 2024, 1 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.01133)] [[Project](https://dekuliutesla.github.io/citygs/)] [[Code](https://github.com/DekuLiuTesla/CityGaussian)]

**LetsGo: Large-Scale Garage Modeling and Rendering via LiDAR-Assisted Gaussian Primitives**<br>
*Jiadi Cui, Junming Cao, Yuhui Zhong, Liao Wang, Fuqiang Zhao, Penghao Wang, Yifan Chen, Zhipeng He, Lan Xu, Yujiao Shi, Yingliang Zhang, Jingyi Yu*<br>
arXiv preprint, 15 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.09748)] [[Project](https://zhaofuq.github.io/LetsGo/)]

**GS-LRM: Large Reconstruction Model for 3D Gaussian Splatting**<br>
*Kai Zhang, Sai Bi, Hao Tan, Yuanbo Xiangli, Nanxuan Zhao, Kalyan Sunkavalli, Zexiang Xu*<br>
arXiv preprint, 30 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.19702)] [[Project](https://sai-bi.github.io/project/gs-lrm/)]

**DoGaussian: Distributed-Oriented Gaussian Splatting for Large-Scale 3D Reconstruction Via Gaussian Consensus**<br>
*Yu Chen, Gim Hee Lee*<br>
arXiv preprint, 22 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.13943)] [[Project](https://aibluefisher.github.io/DoGaussian/)] [[Code](https://github.com/aibluefisher/DoGaussian)]

**PyGS: Large-scale Scene Representation with Pyramidal 3D Gaussian Splatting**<br>
*Zipeng Wang, Dan Xu*<br>
arXiv preprint, 27 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.16829)]

**GaussianFormer: Scene as Gaussians for Vision-Based 3D Semantic Occupancy Prediction**<br>
*Yuanhui Huang, Wenzhao Zheng, Yunpeng Zhang, Jie Zhou, Jiwen Lu*<br>
arXiv preprint, 27 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.17429)] [[Code](https://github.com/huang-yh/GaussianFormer)]

**3D StreetUnveiler with Semantic-Aware 2DGS**<br>
*Jingwei Xu, Yikai Wang, Yiqun Zhao, Yanwei Fu, Shenghua Gao*<br>
arXiv preprint, 28 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.18416)] [[Project](https://streetunveiler.github.io/)] [[Code](https://github.com/DavidXu-JJ/StreetUnveiler)]

**A Hierarchical 3D Gaussian Representation for Real-Time Rendering of Very Large Datasets**<br>
*Bernhard Kerbl, Andréas Meuleman, Georgios Kopanas, Michael Wimmer, Alexandre Lanvin, George Drettakis*<br>
arXiv preprint, 17 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.12080)] [[Project](https://repo-sam.inria.fr/fungraph/hierarchical-3d-gaussians/)]

**VEGS: View Extrapolation of Urban Scenes in 3D Gaussian Splatting using Learned Priors**<br>
*Sungwon Hwang, Min-Jung Kim, Taewoong Kang, Jayeon Kang, Jaegul Choo*<br>
arXiv preprint, 3 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.02945)] [[Project](https://vegs3d.github.io/)]

**FlashGS: Efficient 3D Gaussian Splatting for Large-scale and High-resolution Rendering**<br>
*Guofeng Feng, Siyan Chen, Rong Fu, Zimu Liao, Yi Wang, Tao Liu, Zhilin Pei, Hengjie Li, Xingcheng Zhang, Bo Dai*<br>
arXiv preprint, 15 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.07967)]

**GigaGS: Scaling up Planar-Based 3D Gaussians for Large Scene Surface Reconstruction**<br>
*Junyi Chen, Weicai Ye, Yifan Wang, Danpeng Chen, Di Huang, Wanli Ouyang, Guofeng Zhang, Yu Qiao, Tong He*<br>
arXiv preprint, 10 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.06685)]

**LI-GS: Gaussian Splatting with LiDAR Incorporated for Accurate Large-Scale Reconstruction**<br>
*Changjian Jiang, Ruilan Gao, Kele Shao, Yue Wang, Rong Xiong, Yu Zhang*<br>
arXiv preprint, 19 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.12899)]

**GaRField++: Reinforced Gaussian Radiance Fields for Large-Scale 3D Scene Reconstruction**<br>
*Hanyue Zhang, Zhiliu Yang, Xinhe Zuo, Yuxin Tong, Ying Long, Chen Liu*<br>
arXiv preprint, 19 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.12774)]

**DENSER: 3D Gaussians Splatting for Scene Reconstruction of Dynamic Urban Environments**<br>
*Mahmud A. Mohamad, Gamal Elghazaly, Arthur Hubert, Raphael Frank*<br>
arXiv preprint, 16 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.10041)] [[Code](https://github.com/sntubix/denser)]

**StreetSurfGS: Scalable Urban Street Surface Reconstruction with Planar-based Gaussian Splatting**<br>
*Xiao Cui, Weicai Ye, Yifan Wang, Guofeng Zhang, Wengang Zhou, Tong He, Houqiang Li*<br>
arXiv preprint, 6 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.04354)]

**Long-LRM: Long-sequence Large Reconstruction Model for Wide-coverage Gaussian Splats**<br>
*Chen Ziwen, Hao Tan, Kai Zhang, Sai Bi, Fujun Luan, Yicong Hong, Li Fuxin, Zexiang Xu*<br>
arXiv preprint, 16 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.12781)] [[Project](https://arthurhero.github.io/projects/llrm/)]

:fire:**SCube: Instant Large-Scale Scene Reconstruction using VoxSplats**
*Xuanchi Ren, Yifan Lu, Hanxue Liang, Zhangjie Wu, Huan Ling, Mike Chen, Sanja Fidler, Francis Williams, Jiahui Huang*<br>
NeurIPS 2024, 26 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.20030)] [[Project](https://research.nvidia.com/labs/toronto-ai/scube/)] [[Code](https://github.com/nv-tlabs/SCube)] [[Video](https://www.bilibili.com/video/BV1K1mBYCELD/)]

## 3DGS Autonomous Driving

**DrivingGaussian: Composite Gaussian Splatting for Surrounding Dynamic Autonomous Driving Scenes**<br>
*Xiaoyu Zhou, Zhiwei Lin, Xiaojun Shan, Yongtao Wang, Deqing Sun, Ming-Hsuan Yang*<br>
CVPR 2024, 13 Dec 2023<br>
[[arXiv](https://arxiv.org/abs/2312.07920)] [[Code](https://github.com/VDIGPKU/DrivingGaussian)]

**Street Gaussians for Modeling Dynamic Urban Scenes**<br>
*Yunzhi Yan, Haotong Lin, Chenxu Zhou, Weijie Wang, Haiyang Sun, Kun Zhan, Xianpeng Lang, Xiaowei Zhou, Sida Peng*<br>
arXiv preprint, 2 Jan 2024<br>
[[arXiv](https://arxiv.org/abs/2401.01339)] [[Project](https://zju3dv.github.io/street_gaussians/)] [[Code](https://github.com/zju3dv/street_gaussians)]

**TCLC-GS: Tightly Coupled LiDAR-Camera Gaussian Splatting for Surrounding Autonomous Driving Scenes**<br>
*Cheng Zhao, Su Sun, Ruoyu Wang, Yuliang Guo, Jun-Jun Wan, Zhou Huang, Xinyu Huang, Yingjie Victor Chen, Liu Ren*<br>
arXiv preprint, 3 Apr, 2024<br>
[[arXiv](https://arxiv.org/abs/2404.02410)]

**S^3 Gaussian: Self-Supervised Street Gaussians for Autonomous Driving**<br>
*Nan Huang, Xiaobao Wei, Wenzhao Zheng, Pengju An, Ming Lu, Wei Zhan, Masayoshi Tomizuka, Kurt Keutzer, Shanghang Zhang*<br>
arXiv preprint, 30 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.20323)] [[Code](https://github.com/nnanhuang/S3Gaussian/)]

**VDG: Vision-Only Dynamic Gaussian for Driving Simulation**<br>
*Hao Li, Jingfeng Li, Dingwen Zhang, Chenming Wu, Jieqi Shi, Chen Zhao, Haocheng Feng, Errui Ding, Jingdong Wang, Junwei Han*<br>
arXiv preprint, 26 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.18198)] [[Project](https://3d-aigc.github.io/VDG/)]

**AutoSplat: Constrained Gaussian Splatting for Autonomous Driving Scene Reconstruction**<br>
*Mustafa Khan, Hamidreza Fazlali, Dhruv Sharma, Tongtong Cao, Dongfeng Bai, Yuan Ren, Bingbing Liu*<br>
arXiv preprint, 2 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.02598)] [[Project](https://autosplat.github.io/)]

**DHGS: Decoupled Hybrid Gaussian Splatting for Driving Scene**<br>
*Xi Shi, Lingli Chen, Peng Wei, Xi Wu, Tian Jiang, Yonggang Luo, Lecheng Xie*<br>
arXiv preprint, 23 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.16600)] [[Project](https://ironbrotherstyle.github.io/dhgs_web/)]

**GaussianBeV: 3D Gaussian Representation meets Perception Models for BeV Segmentation**<br>
*Florian Chabot, Nicolas Granger, Guillaume Lapouge*<br>
arXiv preprint, 19 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.14108)]

:fire:**OmniRe: Omni Urban Scene Reconstruction**<br>
*Ziyu Chen, Jiawei Yang, Jiahui Huang, Riccardo de Lutio, Janick Martinez Esturo, Boris Ivanovic, Or Litany, Zan Gojcic, Sanja Fidler, Marco Pavone, Li Song, Yue Wang*<br>
arXiv preprint, 29 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.16760)] [[Project](https://ziyc.github.io/omnire/)]

**Drone-assisted Road Gaussian Splatting with Cross-view Uncertainty**<br>
*Saining Zhang, Baijun Ye, Xiaoxue Chen, Yuantao Chen, Zongzheng Zhang, Cheng Peng, Yongliang Shi, Hao Zhao*<br>
BMVC 2024, 27 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.15242)] [[Project](https://sainingzhang.github.io/project/uc-gs/)] [[Code](https://github.com/SainingZhang/uc-gs/)]

**GGS: Generalizable Gaussian Splatting for Lane Switching in Autonomous Driving**<br>
*Huasong Han, Kaixuan Zhou, Xiaoxiao Long, Yusen Wang, Chunxia Xiao*<br>
arXiv preprint, 4 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.02382)]

**DrivingForward: Feed-forward 3D Gaussian Splatting for Driving Scene Reconstruction from Flexible Surround-view Input**<br>
*Qijian Tian, Xin Tan, Yuan Xie, Lizhuang Ma*<br>
arXiv preprint, 19 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.12753)] [[Project](https://fangzhou2000.github.io/projects/drivingforward/)] [[Code](https://github.com/fangzhou2000/DrivingForward)]

**RenderWorld: World Model with Self-Supervised 3D Label**<br>
*Ziyang Yan, Wenzhen Dong, Yihua Shao, Yuhang Lu, Liu Haiyang, Jingwen Liu, Haozhe Wang, Zhe Wang, Yan Wang, Fabio Remondino, Yuexin Ma*<br>
arXiv preprint, 17 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.11356)]

**UniBEVFusion: Unified Radar-Vision BEVFusion for 3D Object Detection**<br>
*Haocheng Zhao, Runwei Guan, Taoyu Wu, Ka Lok Man, Limin Yu, Yutao Yue*<br>
arXiv preprint, 23 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.14751)]

**GSPR: Multimodal Place Recognition Using 3D Gaussian Splatting for Autonomous Driving**<br>
*Zhangshuo Qi, Junyi Ma, Jingyi Xu, Zijie Zhou, Luqi Cheng, Guangming Xiong*<br>
arXiv preprint, 1 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.00299)]

**LiDAR-GS:Real-time LiDAR Re-Simulation using Gaussian Splatting**<br>
*Qifeng Chen, Sheng Yang, Sicong Du, Tao Tang, Peng Chen, Yuchi Huo*<br>
arXiv preprint, 7 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.05111)]

**DriveDreamer4D: World Models Are Effective Data Machines for 4D Driving Scene Representation**<br>
*Guosheng Zhao, Chaojun Ni, Xiaofeng Wang, Zheng Zhu, Guan Huang, Xinze Chen, Boyuan Wang, Youyi Zhang, Wenjun Mei, Xingang Wang*<br>
arXiv preprint, 17 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.13571)] [[Project](https://drivedreamer4d.github.io/)] [[Code](https://github.com/GigaAI-research/DriveDreamer4D)]

**DeSiRe-GS: 4D Street Gaussians for Static-Dynamic Decomposition and Surface Reconstruction for Urban Driving Scenes**<br>
*Chensheng Peng, Chengwei Zhang, Yixiao Wang, Chenfeng Xu, Yichen Xie, Wenzhao Zheng, Kurt Keutzer, Masayoshi Tomizuka, Wei Zhan*<br>
18 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.11921)] [[Code](https://github.com/chengweialan/DeSiRe-GS)]

**GaussianPretrain: A Simple Unified 3D Gaussian Representation for Visual Pre-training in Autonomous Driving**<br>
*Shaoqing Xu, Fang Li, Shengyin Jiang, Ziying Song, Li Liu, Zhi-xin Yang*<br>
19 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.12452)] [[Code](https://github.com/Public-BOTs/GaussianPretrain)]

## 3DGS Based Occupancy Prediction

**GaussianOcc: Fully Self-supervised and Efficient 3D Occupancy Estimation with Gaussian Splatting**<br>
*Wanshui Gan, Fang Liu, Hongbin Xu, Ningkai Mo, Naoto Yokoya*<br>
arXiv preprint, 21 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.11447)] [[Code](https://github.com/GANWANSHUI/GaussianOcc)]

## 3DGS Based on Diffusion

**L3DG: Latent 3D Gaussian Diffusion**<br>
*Barbara Roessle, Norman Müller, Lorenzo Porzi, Samuel Rota Bulò, Peter Kontschieder, Angela Dai, Matthias Nießner*<br>
SIGGRAPH Asis 2024, 17 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.13530)] [[Project](https://barbararoessle.github.io/l3dg/)] [[Video](https://www.youtube.com/watch?v=UHEEiXCYeLU&feature=youtu.be)]

## 3DGS Based AIGC

**GaussianDiffusion: 3D Gaussian Splatting for Denoising Diffusion Probabilistic Models with Structured Noise**<br>
*Xinhai Li, Huaibin Wang, Kuo-Kun Tseng*<br>
arXiv preprint, 19 Nov 2023<br>
[[arXiv](https://arxiv.org/abs/2311.11221)]

**LucidDreamer: Towards High-Fidelity Text-to-3D Generation via Interval Score Matching**<br>
*Yixun Liang, Xin Yang, Jiantao Lin, Haodong Li, Xiaogang Xu, Yingcong Chen*<br>
arXiv preprint, 19 Nov 2023<br>
[[arXiv](https://arxiv.org/abs/2311.11284)] [[Github](https://github.com/EnVision-Research/LucidDreamer)]

**LucidDreamer: Domain-free Generation of 3D Gaussian Splatting Scenes**<br>
*Jaeyoung Chung, Suyoung Lee, Hyeongjin Nam, Jaerin Lee, Kyoung Mu Lee*<br>
arXiv preprint, 22 Nov 2023<br>
[[arXiv](https://arxiv.org/abs/2311.13384)] [[Project](https://luciddreamer-cvlab.github.io/)]

**DreamGaussian: Generative Gaussian Splatting for Efficient 3D Content Creation**<br>
*Jiaxiang Tang, Jiawei Ren, Hang Zhou, Ziwei Liu, Gang Zeng*<br>
arXiv preprint, 28 Sep 2023<br>
[[arXiv](https://arxiv.org/abs/2309.16653)] [[Project](https://dreamgaussian.github.io/)] [[Github](https://github.com/dreamgaussian/dreamgaussian)]

**Text-to-3D using Gaussian Splatting**<br>
*Zilong Chen, Feng Wang, Huaping Liu*<br>
arXiv preprint, 29 Sep 2023<br>
[[arXiv](https://arxiv.org/abs/2309.16585)] [[Project](https://gsgen3d.github.io/)] [[Github](https://github.com/gsgen3d/gsgen)]

**GaussianDreamer: Fast Generation from Text to 3D Gaussian Splatting with Point Cloud Priors**<br>
*Taoran Yi, Jiemin Fang, Guanjun Wu, Lingxi Xie, Xiaopeng Zhang, Wenyu Liu, Qi Tian, Xinggang Wang*<br>
arXiv preprint, 12 Oct 2023<br>
[[arXiv](https://arxiv.org/abs/2310.08529)] [[Project](https://taoranyi.com/gaussiandreamer/)] [[Github](https://github.com/hustvl/GaussianDreamer)]

**CG3D: Compositional Generation for Text-to-3D via Gaussian Splatting**<br>
*Alexander Vilesov, Pradyumna Chari, Achuta Kadambi*<br>
arXiv preprint, 29 Nov 2023<br>
[[arXiv](https://arxiv.org/abs/2311.17907)]

**Text2Immersion: Generative Immersive Scene with 3D Gaussians**<br>
*Hao Ouyang, Kathryn Heal, Stephen Lombardi, Tiancheng Sun*<br>
arXiv preprint, 14 Dec 2023<br>
[[arXiv](https://arxiv.org/abs/2312.09242)] [[Project](https://ken-ouyang.github.io/text2immersion/index.html)]

**Align Your Gaussians: Text-to-4D with Dynamic 3D Gaussians and Composed Diffusion Models**<br>
*Huan Ling, Seung Wook Kim, Antonio Torralba, Sanja Fidler, Karsten Kreis*<br>
CVPR 2024, 21 Dec 2023<br>
[[arXiv](https://arxiv.org/abs/2312.13763)] [[Project](https://research.nvidia.com/labs/toronto-ai/AlignYourGaussians/)]

:fire:**LangSplat: 3D Language Gaussian Splatting**<br>
*Minghan Qin, Wanhua Li, Jiawei Zhou, Haoqian Wang, Hanspeter Pfister*<br>
CVPR 2024, 26 Dec 2023<br>
[[arXiv](https://arxiv.org/abs/2312.16084)] [[Project](https://langsplat.github.io/)] [[Code](https://github.com/minghanqin/LangSplat)] [[Video](https://www.youtube.com/watch?v=XMlyjsei-Es)]

**4DGen: Grounded 4D Content Generation with Spatial-temporal Consistency**<br>
*Yuyang Yin, Dejia Xu, Zhangyang Wang, Yao Zhao, Yunchao Wei*<br>
arXiv preprint, 28 Dec 2023<br>
[[arXiv](https://arxiv.org/abs/2312.17225)] [[Project](https://vita-group.github.io/4DGen/)] [[Code](https://github.com/VITA-Group/4DGen)]


**DreamGaussian4D: Generative 4D Gaussian Splatting**<br>
*Jiawei Ren, Liang Pan, Jiaxiang Tang, Chi Zhang, Ang Cao, Gang Zeng, Ziwei Liu*<br>
arXiv preprint, 28 Dec 2023<br>
[[arXiv](https://arxiv.org/abs/2312.17142)] [[Project](https://jiawei-ren.github.io/projects/dreamgaussian4d/)] [[Code](https://github.com/jiawei-ren/dreamgaussian4d)]

**IM-3D: Iterative Multiview Diffusion and Reconstruction for High-Quality 3D Generation**<br>
*Luke Melas-Kyriazi, Iro Laina, Christian Rupprecht, Natalia Neverova, Andrea Vedaldi, Oran Gafni, Filippos Kokkinos*<br>
arXiv preprint, 13 Feb 2024<br>
[[arXiv](https://arxiv.org/abs/2402.08682)]

**GALA3D: Towards Text-to-3D Complex Scene Generation via Layout-guided Generative Gaussian Splatting**<br>
*Xiaoyu Zhou, Xingjian Ran, Yajiao Xiong, Jinlin He, Zhiwei Lin, Yongtao Wang, Deqing Sun, Ming-Hsuan Yang*<br>
arXiv preprint, 11 Feb 2024<br>
[[arXiv](https://arxiv.org/abs/2402.07207)]

**GVGEN: Text-to-3D Generation with Volumetric Representation**<br>
*Xianglong He, Junyi Chen, Sida Peng, Di Huang, Yangguang Li, Xiaoshui Huang, Chun Yuan, Wanli Ouyang, Tong He*<br>
arXiv preprint, 19 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.12957)] [[Project](https://gvgen.github.io/)]

**BrightDreamer: Generic 3D Gaussian Generative Framework for Fast Text-to-3D Synthesis**<br>
*Lutao Jiang, Lin Wang*<br>
arXiv preprint, 17 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.11273)] [[Project](https://vlislab22.github.io/BrightDreamer/)] [[Code](https://github.com/lutao2021/BrightDreamer)]

**DreamPolisher: Towards High-Quality Text-to-3D Generation via Geometric Diffusion**<br>
*Yuanze Lin, Ronald Clark, Philip Torr*<br>
arXiv preprint, 25 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.17237)] [[Project](https://yuanze-lin.me/DreamPolisher_page/)] [[Code](https://github.com/yuanze-lin/DreamPolisher)]


**GaussianCube: Structuring Gaussian Splatting using Optimal Transport for 3D Generative Modeling**<br>
*Bowen Zhang, Yiji Cheng, Jiaolong Yang, Chunyu Wang, Feng Zhao, Yansong Tang, Dong Chen, Baining Guo*<br>
arXiv preprint, 28 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.19655)] [[Prject](https://gaussiancube.github.io/)] [[Code](https://github.com/GaussianCube/GaussianCube)]

**RealmDreamer: Text-Driven 3D Scene Generation with Inpainting and Depth Diffusion**<br>
*Jaidev Shriram, Alex Trevithick, Lingjie Liu, Ravi Ramamoorthi*<br>
arXiv preprint, 10 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.07199)] [[Project](https://realmdreamer.github.io/)]

**DreamScene360: Unconstrained Text-to-3D Scene Generation with Panoramic Gaussian Splatting**<br>
*Shijie Zhou, Zhiwen Fan, Dejia Xu, Haoran Chang, Pradyumna Chari, Tejas Bharadwaj, Suya You, Zhangyang Wang, Achuta Kadambi*<br>
arXiv preprint, 10 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.06903)] [[Project](https://dreamscene360.github.io/)]

**DreamScape: 3D Scene Creation via Gaussian Splatting joint Correlation Modeling**<br>
*Xuening Yuan, Hongyu Yang, Yueming Zhao, Di Huang*<br>
arXiv preprint, 14 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.09227)]

**DreamScene: 3D Gaussian-based Text-to-3D Scene Generation via Formation Pattern Sampling**<br>
*Haoran Li, Haolin Shi, Wenli Zhang, Wenjun Wu, Yong Liao, Lin Wang, Lik-hang Lee, Pengyuan Zhou*<br>
arXiv preprint, 4 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.03575)]

**Interactive3D: Create What You Want by Interactive 3D Generation**<br>
*Shaocong Dong, Lihe Ding, Zhanpeng Huang, Zibin Wang, Tianfan Xue, Dan Xu*<br>
arXiv prepring, 25 Apr 2024<nr>
[[arXiv](https://arxiv.org/abs/2404.16510)] [[Project](https://interactive-3d.github.io/)] [[Code](https://github.com/interactive-3d/interactive3d)]

**FastScene: Text-Driven Fast 3D Indoor Scene Generation via Panoramic Gaussian Splatting**<br>
*Yikun Ma, Dandan Zhan, Zhi Jin*<br>
IJCAI 2024, 9 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.05768)]

**MagicDrive3D: Controllable 3D Generation for Any-View Rendering in Street Scenes**<br>
*Ruiyuan Gao, Kai Chen, Zhihao Li, Lanqing Hong, Zhenguo Li, Qiang Xu*<br>
arXiv preprint, 23 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.14475)]

**Dreamer XL: Towards High-Resolution Text-to-3D Generation via Trajectory Score Matching**<br>
*Xingyu Miao, Haoran Duan, Varun Ojha, Jun Song, Tejal Shah, Yang Long, Rajiv Ranjan*<br>
arXiv preprint, 18 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.11252)] [[Code](https://github.com/xingy038/Dreamer-XL)]

**EG4D: Explicit Generation of 4D Object without Score Distillation**<br>
*Qi Sun, Zhiyang Guo, Ziyu Wan, Jing Nathan Yan, Shengming Yin, Wengang Zhou, Jing Liao, Houqiang Li*<br>
arXiv preprint, 28 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.18132)] [[Code](https://github.com/jasongzy/EG4D)]

**PLA4D: Pixel-Level Alignments for Text-to-4D Gaussian Splatting**<br>
*Qiaowei Miao, Yawei Luo, Yi Yang*<br>
arXiv preprint, 30 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.19957)] [[Project](https://miaoqiaowei.github.io/PLA4D/)]

**Adversarial Generation of Hierarchical Gaussians for 3D Generative Model**<br>
*Sangeek Hyun, Jae-Pil Heo*<br>
arXiv preprint, 5 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.02968)] [[Project](https://hse1032.github.io/gsgan)]

**Physics3D: Learning Physical Properties of 3D Gaussians via Video Diffusion**<br>
*Fangfu Liu, Hanyang Wang, Shunyu Yao, Shengjun Zhang, Jie Zhou, Yueqi Duan*<br>
arXiv preprint, 6 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.04338)] [[Project](https://liuff19.github.io/Physics3D/)]

**GaussianCity: Generative Gaussian Splatting for Unbounded 3D City Generation**<br>
*Haozhe Xie, Zhaoxi Chen, Fangzhou Hong, Ziwei Liu*<br>
arXiv preprint, 10 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.06526)]

**MVGamba: Unify 3D Content Generation as State Space Sequence Modeling**<br>
*Xuanyu Yi, Zike Wu, Qiuhong Shen, Qingshan Xu, Pan Zhou, Joo-Hwee Lim, Shuicheng Yan, Xinchao Wang, Hanwang Zhang*<br>
arXiv preprint, 10 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.06367)]

**L4GM: Large 4D Gaussian Reconstruction Model**<br>
*Jiawei Ren, Kevin Xie, Ashkan Mirzaei, Hanxue Liang, Xiaohui Zeng, Karsten Kreis, Ziwei Liu, Antonio Torralba, Sanja Fidler, Seung Wook Kim, Huan Ling*<br>
arXiv preprint, 14 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.10324)] [[Project](https://research.nvidia.com/labs/toronto-ai/l4gm/)]

**GradeADreamer: Enhanced Text-to-3D Generation Using Gaussian Splatting and Multi-View Diffusion**<br>
*Trapoom Ukarapol, Kevin Pruvost*<br>
arXiv preprint,  14 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.09850)] [[Code](https://github.com/trapoom555/GradeADreamer)]

**ClotheDreamer: Text-Guided Garment Generation with 3D Gaussians**<br>
*Yufei Liu, Junshu Tang, Chu Zheng, Shijie Zhang, Jinkun Hao, Junwei Zhu, Dongjin Huang*<br>
arXiv preprint, 24 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.16815)] [[Project](https://ggxxii.github.io/clothedreamer/)]

**GaussianDreamerPro: Text to Manipulable 3D Gaussians with Highly Enhanced Quality**<br>
*Taoran Yi, Jiemin Fang, Zanwei Zhou, Junjie Wang, Guanjun Wu, Lingxi Xie, Xiaopeng Zhang, Wenyu Liu, Xinggang Wang, Qi Tian*<br>
arXiv preprint, 26 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.18462)] [[Project](https://taoranyi.com/gaussiandreamerpro/)] [[Code](https://github.com/hustvl/GaussianDreamerPro)]

**TrAME: Trajectory-Anchored Multi-View Editing for Text-Guided 3D Gaussian Splatting Manipulation**<br>
*Chaofan Luo, Donglin Di, Yongjia Ma, Zhou Xue, Chen Wei, Xun Yang, Yebin Liu*<br>
arXiv preprint, 2 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.02034)]

**HoloDreamer: Holistic 3D Panoramic World Generation from Text Descriptions**<br>
*Haiyang Zhou, Xinhua Cheng, Wangbo Yu, Yonghong Tian, Li Yuan*<br>
arXiv preprint, 21 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.15187)] [[Project](https://zhouhyocean.github.io/holodreamer/)]

**Connecting Consistency Distillation to Score Distillation for Text-to-3D Generation**<br>
*Zongrui Li, Minghui Hu, Qian Zheng, Xudong Jiang*<br>
ECCV 2024, 18 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.13584)] [[Code](https://github.com/LMozart/ECCV2024-GCS-BEG)]

**SV4D: Dynamic 3D Content Generation with Multi-Frame and Multi-View Consistency**<br>
*Yiming Xie, Chun-Han Yao, Vikram Voleti, Huaizu Jiang, Varun Jampani*<br>
arXiv preprint, 24 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.17470)] [[Project](https://sv4d.github.io/)] [[Code](https://github.com/Stability-AI/generative-models)]

**DreamCouple: Exploring High Quality Text-to-3D Generation Via Rectified Flow**<br>
*Hangyu Li, Xiangxiang Chu, Dingyuan Shi*<br>
arXiv preprint, 9 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.05008)]

**Hi3D: Pursuing High-Resolution Image-to-3D Generation with Video Diffusion Models**<br>
*Haibo Yang, Yang Chen, Yingwei Pan, Ting Yao, Zhineng Chen, Chong-Wah Ngo, Tao Mei*<br>
ACMMM 2024, 11 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.07452)] [[Code](https://github.com/yanghb22-fdu/Hi3D-Official)]

**DreamMapping: High-Fidelity Text-to-3D Generation via Variational Distribution Mapping**<br>
*Zeyu Cai, Duotun Wang, Yixun Liang, Zhijing Shao, Ying-Cong Chen, Xiaohang Zhan, Zeyu Wang*<br>
arXiv preprint, 8 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.05099)]

**DreamHOI: Subject-Driven Generation of 3D Human-Object Interactions with Diffusion Priors**<br>
*Thomas Hanwen Zhu, Ruining Li, Tomas Jakab*<br>
arXiv preprint, 12 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.08278)]

**DreamMesh: Jointly Manipulating and Texturing Triangle Meshes for Text-to-3D Generation**<br>
*Haibo Yang, Yang Chen, Yingwei Pan, Ting Yao, Zhineng Chen, Zuxuan Wu, Yu-Gang Jiang, Tao Mei*<br>
ECCV 2024, 11 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.07454)] [[Project](https://dreammesh.github.io/)]

**DreamMesh4D: Video-to-4D Generation with Sparse-Controlled Gaussian-Mesh Hybrid Representation**<br>
*Zhiqi Li, Yiming Chen, Peidong Liu*<br>
NeurIPS 2024, 9 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.06756)]

**RGM: Reconstructing High-fidelity 3D Car Assets with Relightable 3D-GS Generative Model from a Single Image**<br>
*Xiaoxue Chen, Jv Zheng, Hao Huang, Haoran Xu, Weihao Gu, Kangliang Chen, He xiang, Huan-ang Gao, Hao Zhao, Guyue Zhou, Yaqin Zhang*<br>
arXiv preprint, 10 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.08181)] 

**DreamSat: Towards a General 3D Model for Novel View Synthesis of Space Objects**<br>
*Nidhi Mathihalli, Audrey Wei, Giovanni Lavezzi, Peng Mun Siew, Victor Rodriguez-Fernandez, Hodei Urrutxua, Richard Linares*<br>
arXiv preprint, 7 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.05097)] [[Code](https://github.com/ARCLab-MIT/space-nvs)]

**Enhancing Single Image to 3D Generation using Gaussian Splatting and Hybrid Diffusion Priors**<br>
*Hritam Basak, Hadi Tabatabaee, Shreekant Gayaka, Ming-Feng Li, Xin Yang, Cheng-Hao Kuo, Arnie Sen, Min Sun, Zhaozheng Yin*<br>
arXiv preprint, 12 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.09467)]

**3D-Adapter: Geometry-Consistent Multi-View Diffusion for High-Quality 3D Generation**<br>
*Hansheng Chen, Bokui Shen, Yulin Liu, Ruoxi Shi, Linqi Zhou, Connor Z. Lin, Jiayuan Gu, Hao Su, Gordon Wetzstein, Leonidas Guibas*<br>
arXiv preprint, 24 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.18974)] [[Project](https://lakonik.github.io/3d-adapter/)] [[Code](https://github.com/Lakonik/MVEdit)]

**CompGS: Unleashing 2D Compositionality for Compositional Text-to-3D via Dynamically Optimizing 3D Gaussians**<br>
*Chongjian Ge, Chenfeng Xu, Yuanfeng Ji, Chensheng Peng, Masayoshi Tomizuka, Ping Luo, Mingyu Ding, Varun Jampani, Wei Zhan*<br>
arXiv preprint, 28 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.20723)]  [[Project](https://chongjiange.github.io/compgs.html)]]

**DiffGS: Functional Gaussian Splatting Diffusion**<br>
*Junsheng Zhou, Weiqi Zhang, Yu-Shen Liu*<br>
NeurIPS 2024, 25 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.19657)] [[Project](https://junshengzhou.github.io/DiffGS/)]  [[Code](https://github.com/weiqi-zhang/DiffGS)]

**Baking Gaussian Splatting into Diffusion Denoiser for Fast and Scalable Single-stage Image-to-3D Generation**<br>
*Yuanhao Cai, He Zhang, Kai Zhang, Yixun Liang, Mengwei Ren, Fujun Luan, Qing Liu, Soo Ye Kim, Jianming Zhang, Zhifei Zhang, Yuqian Zhou, Zhe Lin, Alan Yuille*<br>
arXiv preprint, 21 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.14384)] [[Project](https://caiyuanhao1998.github.io/project/DiffusionGS/)]

**Direct and Explicit 3D Generation from a Single Image**<br>
*Haoyu Wu, Meher Gitika Karumuri, Chuhang Zou, Seungbae Bang, Yuelong Li, Dimitris Samaras, Sunil Hadap*<br>
3DV 2025, 17 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.10947)] [[Project](https://hao-yu-wu.github.io/gen3d/)] [[Video](https://www.youtube.com/watch?v=SucVXcm_3sY)]

## 3DGS Model Compactness Optimization

### 3DGS Model Compression Surveys

**3DGS.zip: A survey on 3D Gaussian Splatting Compression Methods**<br>
*Milena T. Bagdasarian, Paul Knoll, Florian Barthel, Anna Hilsmann, Peter Eisert, Wieland Morgenstern*<br>
arXiv preprint, 17 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2407.09510)] [[Project](https://w-m.github.io/3dgs-compression-survey/)]

### 3DGS Model Compression Progresses

**LightGaussian: Unbounded 3D Gaussian Compression with 15x Reduction and 200+ FPS**<br>
*Zhiwen Fan, Kevin Wang, Kairun Wen, Zehao Zhu, Dejia Xu, Zhangyang Wang*<br>
arXiv preprint, 28 Nov 2023<br>
[[arXiv](https://arxiv.org/abs/2311.17245)] [[Project](https://lightgaussian.github.io/)] [[Video](https://www.bilibili.com/video/BV1QN4y127o9/)]

**Identifying Unnecessary 3D Gaussians using Clustering for Fast Rendering of 3D Gaussian Splatting**<br>
*Joongho Jo, Hyeongwon Kim, Jongsun Park*<br>
arXiv preprint, 21 Feb 2024<br>
[[arXiv](https://arxiv.org/abs/2402.13827)]

:fire:**HAC: Hash-grid Assisted Context for 3D Gaussian Splatting Compression**<br>
*Yihang Chen, Qianyi Wu, Weiyao Lin, Mehrtash Harandi, Jianfei Cai*<br>
ECCV 2024, 21 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.14530)] [[Project](https://yihangchen-ee.github.io/project_hac/)] [[Code](https://github.com/YihangChen-ee/HAC)]

**CompGS: Efficient 3D Scene Representation via Compressed Gaussian Splatting**<br>
*Xiangrui Liu, Xinju Wu, Pingping Zhang, Shiqi Wang, Zhu Li, Sam Kwong*<br>
arXiv preprint, 15 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.09458)]

**F-3DGS: Factorized Coordinates and Representations for 3D Gaussian Splatting**<br>
*Xiangyu Sun, Joo Chan Lee, Daniel Rho, Jong Hwan Ko, Usman Ali, Eunbyung Park*<br>
arXiv preprint, 27 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.17083)] [[Project](https://xiangyu1sun.github.io/Factorize-3DGS/)] [[Code](https://github.com/Xiangyu1Sun/Factorize-3DGS)]

**LP-3DGS: Learning to Prune 3D Gaussian Splatting**<br>
*Zhaoliang Zhang, Tianchen Song, Yongjae Lee, Li Yang, Cheng Peng, Rama Chellappa, Deliang Fan*<br>
arXiv preprint, 29 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.18784)]

**ContextGS: Compact 3D Gaussian Splatting with Anchor Level Context Model**<br>
*Yufei Wang, Zhihao Li, Lanqing Guo, Wenhan Yang, Alex C. Kot, Bihan Wen*<br>
arXiv preprint, 31 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.20721)]

**Gaussian-Forest: Hierarchical-Hybrid 3D Gaussian Splatting for Compressed Scene Modeling**<br>
*Fengyi Zhang, Tianjun Zhang, Lin Zhang, Helen Huang, Yadan Luo*<br>
arXiv preprint, 13 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.08759)]

:fire:**Reducing the Memory Footprint of 3D Gaussian Splatting**<br>
*Panagiotis Papantonakis, Georgios Kopanas, Bernhard Kerbl, Alexandre Lanvin, George Drettakis*<br>
arXiv preprint, 24 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.17074)] [[Project](https://repo-sam.inria.fr/fungraph/reduced_3dgs/)] 

**Lightweight Predictive 3D Gaussian Splats**<br>
*Junli Cao, Vidit Goel, Chaoyang Wang, Anil Kag, Ju Hu, Sergei Korolev, Chenfanfu Jiang, Sergey Tulyakov, Jian Ren*<br>
arXiv preprint, 27 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.19434)] [[Project](https://plumpuddings.github.io/LPGS/)]

**Trimming the Fat: Efficient Compression of 3D Gaussian Splats through Pruning**<br>
*Muhammad Salman Ali, Maryam Qamar, Sung-Ho Bae, Enzo Tartaglione*<br>
arXiv preprint, 26 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.18214)]

**A Benchmark for Gaussian Splatting Compression and Quality Assessment Study**<br>
*Qi Yang, Kaifa Yang, Yuke Xing, Yiling Xu, Zhu Li*<br>
arXiv preprint, 19 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.14197)] [[Code](https://github.com/Qi-Yangsjtu/GGSC)]

**Compact 3D Gaussian Splatting for Static and Dynamic Radiance Fields**<br>
*Joo Chan Lee, Daniel Rho, Xiangyu Sun, Jong Hwan Ko, Eunbyung Park*<br>
arXiv preprint, 7 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.03822)]

**MesonGS: Post-training Compression of 3D Gaussians via Efficient Attribute Transformation**<br>
*Shuzhao Xie, Weixiang Zhang, Chen Tang, Yunpeng Bai, Rongwei Lu, Shijia Ge, Zhi Wang*<br>
ECCV 2024, 15 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.09756)]

**Fast Feedforward 3D Gaussian Splatting Compression**<br>
*Yihang Chen, Qianyi Wu, Mengyao Li, Weiyao Lin, Mehrtash Harandi, Jianfei Cai*<br>
arXiv preprint, 10 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.08017)] [[Project](https://yihangchen-ee.github.io/project_fcgs/)] [[Code](https://github.com/YihangChen-ee/FCGS)]

**ELMGS: Enhancing memory and computation scaLability through coMpression for 3D Gaussian Splatting**<br>
*Muhammad Salman Ali, Sung-Ho Bae, Enzo Tartaglione*<br>
arXiv preprint, 30 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.23213)]

**A Hierarchical Compression Technique for 3D Gaussian Splatting Compression**<br>
*He Huang, Wenjie Huang, Qi Yang, Yiling Xu, Zhu li*<br>
arXiv preprint, 11 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.06976)]

## 3DGS Streaming

**3DGStream: On-the-Fly Training of 3D Gaussians for Efficient Streaming of Photo-Realistic Free-Viewpoint Videos**<br>
*Jiakai Sun, Han Jiao, Guangyuan Li, Zhanjie Zhang, Lei Zhao, Wei Xing*<br>
CVPR 2024, 3 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.01444)] [[Project](https://sjojok.top/3dgstream/)] [[Code](https://github.com/SJoJoK/3DGStream)]

**HAC: Hash-grid Assisted Context for 3D Gaussian Splatting Compression**<br>
*Yihang Chen, Qianyi Wu, Jianfei Cai, Mehrtash Harandi, Weiyao Lin*<br>
arXiv preprint, 12 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.14530)] [[Project](https://yihangchen-ee.github.io/project_hac/)] [[Code](https://yihangchen-ee.github.io/project_hac/)]

**LapisGS: Layered Progressive 3D Gaussian Splatting for Adaptive Streaming**<br>
*Yuang Shi, Simone Gasparini, Géraldine Morin, Wei Tsang Ooi*<br>
arXiv preprint, 27 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.14823)]

**PRoGS: Progressive Rendering of Gaussian Splats**<br>
*Brent Zoomers, Maarten Wijnants, Ivan Molenaers, Joni Vanherck, Jeroen Put, Lode Jorissen, Nick Michiels*<br>
arXiv preprint, 3 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.01761)]

**SwinGS: Sliding Window Gaussian Splatting for Volumetric Video Streaming with Arbitrary Length**<br>
*Bangya Liu, Suman Banerjee*<br>
[[arXiv](https://arxiv.org/abs/2409.07759)]

## 3DGS Based Relighting

**Subsurface Scattering for 3D Gaussian Splatting**<br>
*Jan-Niklas Dihlmann, Arjun Majumdar, Andreas Engelhardt, Raphael Braun, Hendrik P.A. Lensch*<br>
arXiv preprint, 22 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.12282)] [[Project](https://sss.jdihlmann.com/)] [[Code](https://github.com/cgtuebingen/SSS-GS)]

## 3DGS Robotics

### 3DGS Robotics Surveys

**3D Gaussian Splatting in Robotics: A Survey**<br>
*Siting Zhu, Guangming Wang, Dezhi Kong, Hesheng Wang*<br>
arXiv preprint, 16 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.12262)]

**Neural Fields in Robotics: A Survey**<br>
*Muhammad Zubair Irshad, Mauro Comi, Yen-Chen Lin, Nick Heppert, Abhinav Valada, Rares Ambrus, Zsolt Kira, Jonathan Tremblay*<br>
arXiv preprint, 26 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.20220)] [[Project](https://robonerf.github.io/survey/index.html)] 

### 3DGS Robotics Progresses 

**Splat-Nav: Safe Real-Time Robot Navigation in Gaussian Splatting Maps**<br>
*Timothy Chen, Ola Shorinwa, Weijia Zeng, Joseph Bruno, Philip Dames, Mac Schwager*<br>
arXiv preprint, 5 Mar 2023<br>
[[arXiv](https://arxiv.org/abs/2403.02751)]

**ManiGaussian: Dynamic Gaussian Splatting for Multi-task Robotic Manipulation**<br>
*Guanxing Lu, Shiyi Zhang, Ziwei Wang, Changliu Liu, Jiwen Lu, Yansong Tang*<br>
arXiv preprint, 13 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.08321)]

**Splat-MOVER: Multi-Stage, Open-Vocabulary Robotic Manipulation via Editable Gaussian Splatting**<br>
*Ola Shorinwa, Johnathan Tucker, Aliyah Smith, Aiden Swann, Timothy Chen, Roya Firoozi, Monroe Kennedy III, Mac Schwager*<br>
arXiv preprint, 7 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2405.04378)]

**Query-based Semantic Gaussian Field for Scene Representation in Reinforcement Learning**<br>
*Jiaxu Wang, Ziyi Zhang, Qiang Zhang, Jia Li, Jingkai Sun, Mingyuan Sun, Junhao He, Renjing Xu*<br>
arXiv preprint, 4 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.02370)]

**Gaussian Splatting to Real World Flight Navigation Transfer with Liquid Networks**<br>
*Alex Quach, Makram Chahine, Alexander Amini, Ramin Hasani, Daniela Rus*<br>
arXiv preprint, 21 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.15149)]

**Robo-GS: A Physics Consistent Spatial-Temporal Model for Robotic Arm with Hybrid Representation**<br>
*Haozhe Lou, Yurong Liu, Yike Pan, Yiran Geng, Jianteng Chen, Wenlong Ma, Chenglong Li, Lin Wang, Hengzhen Feng, Lu Shi, Liyi Luo, Yongliang Shi*<br>
arXiv preprint, 27 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.14873)] [[Project](https://robostudioapp.com/)] [[Video](https://youtu.be/Aq2-2EW6JBk)]

**GaussianPU: A Hybrid 2D-3D Upsampling Framework for Enhancing Color Point Clouds via 3D Gaussian Splatting**<br>
*Zixuan Guo, Yifan Xie, Weijing Xie, Peng Huang, Fei Ma, Fei Richard Yu*<br>
arXiv preprint, 3 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.01581)]

**GraspSplats: Efficient Manipulation with 3D Feature Splatting**<br>
*Mazeyu Ji, Ri-Zhao Qiu, Xueyan Zou, Xiaolong Wang*<br>
arXiv preprint, 3 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.02084)] [[Project](https://graspsplats.github.io/)] [[Video](https://www.youtube.com/watch?v=LkTe2jjsLDA)] [[Code](https://github.com/jimazeyu/GraspSplats)]

**SplatSim: Zero-Shot Sim2Real Transfer of RGB Manipulation Policies Using Gaussian Splatting**<br>
*Mohammad Nomaan Qureshi, Sparsh Garg, Francisco Yandun, David Held, George Kantor, Abhishesh Silwal*<br>
arXiv preprint, 16 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.10161)]

**BEINGS: Bayesian Embodied Image-goal Navigation with Gaussian Splatting**<br>
*Wugang Meng, Tianfu Wu, Huan Yin, Fumin Zhang*<br>
arXiv preprint, 16 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.10216)]

**SAFER-Splat: A Control Barrier Function for Safe Navigation with Online Gaussian Splatting Maps**<br>
*Timothy Chen, Aiden Swann, Javier Yu, Ola Shorinwa, Riku Murai, Monroe Kennedy III, Mac Schwager*<br>
arXiv preprint, 15 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.09868)] [[Project](https://chengine.github.io/safer-splat/)]

**RT-GuIDE: Real-Time Gaussian splatting for Information-Driven Exploration**<br>
*Yuezhan Tao, Dexter Ong, Varun Murali, Igor Spasojevic, Pratik Chaudhari, Vijay Kumar*<br>
arXiv preprint, 26 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.18122)] [[Project](https://tyuezhan.github.io/RT_GuIDE/)] [[Video](https://www.youtube.com/watch?v=SzzXLXxzc7s)]

**Language-Embedded Gaussian Splats (LEGS): Incrementally Building Room-Scale Representations with a Mobile Robot**<br>
*Justin Yu, Kush Hari, Kishore Srinivas, Karim El-Refai, Adam Rashid, Chung Min Kim, Justin Kerr, Richard Cheng, Muhammad Zubair Irshad, Ashwin Balakrishna, Thomas Kollar, Ken Goldberg*<br>
arXiv preprint, 26 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.18108)]

**HGS-Planner: Hierarchical Planning Framework for Active Scene Reconstruction Using 3D Gaussian Splatting**<br>
*Zijun Xu, Rui Jin, Ke Wu, Yi Zhao, Zhiwei Zhang, Jieru Zhao, Zhongxue Gan, Wenchao Ding*<br>
arXiv preprint, 26 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.17624)]

**Let's Make a Splan: Risk-Aware Trajectory Optimization in a Normalized Gaussian Splat**<br>
*Jonathan Michaux, Seth Isaacson, Challen Enninful Adu, Adam Li, Rahul Kashyap Swayampakula, Parker Ewen, Sean Rice, Katherine A. Skinner, Ram Vasudevan*<br>
arXiv preprint, 26 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.16915)]

**RL-GSBridge: 3D Gaussian Splatting Based Real2Sim2Real Method for Robotic Manipulation Learning**<br>
*Yuxuan Wu, Lei Pan, Wenhua Wu, Guangming Wang, Yanzi Miao, Hesheng Wang*<br>
arXiv preprint, 30 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.20291)]

**SplaTraj: Camera Trajectory Generation with Semantic Gaussian Splatting**<br>
*Xinyi Liu, Tianyi Zhang, Matthew Johnson-Roberson, Weiming Zhi*<br>
arXiv preprint, 8 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.06014)]

**Next Best Sense: Guiding Vision and Touch with FisherRF for 3D Gaussian Splatting**<br>
*Matthew Strong, Boshu Lei, Aiden Swann, Wen Jiang, Kostas Daniilidis, Monroe Kennedy III*<br>
arXiv preprint, 7 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.04680)] [[Project](https://arm.stanford.edu/next-best-sense/)] [[Video](https://www.youtube.com/watch?v=NHgb_16-Plg)] [[Code](https://github.com/armlabstanford/NextBestSense)]

**Mode-GS: Monocular Depth Guided Anchored 3D Gaussian Splatting for Robust Ground-View Scene Rendering**<br>
*Yonghan Lee, Jaehoon Choi, Dongki Jung, Jaeseong Yun, Soohyun Ryu, Dinesh Manocha, Suyong Yeon*<br>
arXiv preprint, 6 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.04646)]

**L-VITeX: Light-weight Visual Intuition for Terrain Exploration**<br>
*Antar Mazumder, Zarin Anjum Madhiha*<br>
arXiv preprint, 10 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.07872)]

**Gaussian Splatting Visual MPC for Granular Media Manipulation**<br>
*Wei-Cheng Tseng, Ellina Zhang, Krishna Murthy Jatavallabhula, Florian Shkurti*<br>
arXiv preprint, 13 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.09740)] [[Project](https://weichengtseng.github.io/gs-granular-mani/)]

**Differentiable Robot Rendering**<br>
*Ruoshi Liu, Alper Canberk, Shuran Song, Carl Vondrick*<br>
arXiv preprint, 17 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.13851)] [[Project](https://drrobot.cs.columbia.edu/)] [[Video](https://drrobot.cs.columbia.edu/assets/videos/video.mp4)] [[Code](https://github.com/cvlab-columbia/drrobot)]

**MSGField: A Unified Scene Representation Integrating Motion, Semantics, and Geometry for Robotic Manipulation**<br>
*Yu Sheng, Runfeng Lin, Lidian Wang, Quecheng Qiu, YanYong Zhang, Yu Zhang, Bei Hua, Jianmin Ji*<br>
arXiv preprint, 21 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.15730)] [[Project](https://shengyu724.github.io/MSGField.github.io/)] [[Code](https://github.com/ShengYu724/MSGField)]

**Dynamic 3D Gaussian Tracking for Graph-Based Neural Dynamics Modeling**<br>
*Mingtong Zhang, Kaifeng Zhang, Yunzhu Li*<br>
arXiv preprint, 24 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.18912)] [[Project](https://gs-dynamics.github.io/)] [[Code](https://github.com/robo-alex/gs-dynamics)]

**E-3DGS: Gaussian Splatting with Exposure and Motion Events**<br>
*Xiaoting Yin, Hao Shi, Yuhan Bao, Zhenshan Bing, Yiyi Liao, Kailun Yang, Kaiwei Wang*<br>
arXiv preprint, 22 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.16995)] [[Code](https://github.com/MasterHow/E-3DGS)]

**ActiveSplat: High-Fidelity Scene Reconstruction through Active Gaussian Splatting**<br>
*Yuetao Li, Zijia Kuang, Ting Li, Guyue Zhou, Shaohui Zhang, Zike Yan*<br>
arXiv preprint, 29 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.21955)] [[Project](https://li-yuetao.github.io/ActiveSplat/)] [[Video](https://youtu.be/444RW0t7FBs)]

**Get a Grip: Multi-Finger Grasp Evaluation at Scale Enables Robust Sim-to-Real Transfer**<br>
*Tyler Ga Wei Lum, Albert H. Li, Preston Culbertson, Krishnan Srinivasan, Aaron D. Ames, Mac Schwager, Jeannette Bohg*<br>
arXiv preprint, 31 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.23701)] [[Project](https://sites.google.com/view/get-a-grip-dataset/)] [[Video](https://www.youtube.com/watch?v=leN322X3g6E)]

**3DGS-CD: 3D Gaussian Splatting-based Change Detection for Physical Object Rearrangement**<br>
*Ziqi Lu, Jianbo Ye, John Leonard*<br>
arXiv preprint, 6 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.03706)]  [[Code](https://github.com/520xyxyzq/3DGS-CD)]

**Object and Contact Point Tracking in Demonstrations Using 3D Gaussian Splatting**<br>
*Michael Büttner, Jonathan Francis, Helge Rhodin, Andrew Melnik*<br>
CoRL 2024, 5 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.03555)]

**Modeling Uncertainty in 3D Gaussian Splatting through Continuous Semantic Splatting**<br>
*Joey Wilson, Marcelino Almeida, Min Sun, Sachit Mahajan, Maani Ghaffari, Parker Ewen, Omid Ghasemalizadeh, Cheng-Hao Kuo, Arnie Sen*<br>
arXiv preprint, 4 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.02547)]

**Through the Curved Cover: Synthesizing Cover Aberrated Scenes with Refractive Field**<br>
*Liuyue Xie, Jiancong Guo, Laszlo A. Jeni, Zhiheng Jia, Mingyang Li, Yunwen Zhou, Chao Guo*<br>
WACV 2025, 10 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.06365)]

**SplatR : Experience Goal Visual Rearrangement with 3D Gaussian Splatting and Dense Feature Matching**<br>
*Arjun P S, Andrew Melnik, Gora Chand Nandi*<br>
arXiv preprint, 21 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.14322)]

**RoboGSim: A Real2Sim2Real Robotic Gaussian Splatting Simulator**<br>
*Xinhai Li, Jialin Li, Ziheng Zhang, Rui Zhang, Fan Jia, Tiancai Wang, Haoqiang Fan, Kuo-Kun Tseng, Ruiping Wang*<br>
18 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.11839)] [[Project](https://robogsim.github.io/)]

## 3DGS Avatar Generation

### 3DGS Avatar Generation Survey

**A Survey on 3D Human Avatar Modeling -- From Reconstruction to Generation**<br>
*Ruihe Wang, Yukang Cao, Kai Han, Kwan-Yee K. Wong*<br>
arXiv preprint, 6 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.04253)]

### 3DGS Avatar Generation Progresses

**Animatable 3D Gaussian: Fast and High-Quality Reconstruction of Multiple Human Avatars**<br>
*Yang Liu, Xiang Huang, Minghan Qin, Qinwei Lin, Haoqian Wang*<br>
arXiv preprint, 27 Nov 2023<br>
[[arXiv](https://arxiv.org/abs/2311.16482)] [[Project](https://jimmyyliu.github.io/Animatable-3D-Gaussian/)]

**HumanGaussian: Text-Driven 3D Human Generation with Gaussian Splatting**<br>
*Xian Liu, Xiaohang Zhan, Jiaxiang Tang, Ying Shan, Gang Zeng, Dahua Lin, Xihui Liu, Ziwei Liu*<br>
arXiv preprint, 28 Nov 2023<br>
[[arXiv](https://arxiv.org/abs/2311.17061)] [[Project](https://alvinliu0.github.io/projects/HumanGaussian)]

**HUGS: Human Gaussian Splats**<br>
*Muhammed Kocabas, Jen-Hao Rick Chang, James Gabriel, Oncel Tuzel, Anurag Ranjan*<br>
arXiv preprint, 29 Nov 2023<br>
[[arXiv](https://arxiv.org/abs/2311.17910)]

**Gaussian Shell Maps for Efficient 3D Human Generation**<br>
*Rameen Abdal, Wang Yifan, Zifan Shi, Yinghao Xu, Ryan Po, Zhengfei Kuang, Qifeng Chen, Dit-Yan Yeung, Gordon Wetzstein*<br>
arXiv preprint, 29 Nov 2023<br>
[[arXiv](https://arxiv.org/abs/2311.17857)]

**GPS-Gaussian: Generalizable Pixel-wise 3D Gaussian Splatting for Real-time Human Novel View Synthesis**<br>
*Shunyuan Zheng, Boyao Zhou, Ruizhi Shao, Boning Liu, Shengping Zhang, Liqiang Nie, Yebin Liu*<br>
arXiv preprint, 4 Dec 2023<br>
[[arXiv](https://arxiv.org/abs/2312.02155)] [[Project](https://shunyuanzheng.github.io/)]

**GaussianAvatar: Towards Realistic Human Avatar Modeling from a Single Video via Animatable 3D Gaussians**<br>
*Liangxiao Hu, Hongwen Zhang, Yuxiang Zhang, Boyao Zhou, Boning Liu, Shengping Zhang, Liqiang Nie*<br>
arXiv preprint, 4 Dec 2023<br>
[[arXiv](https://arxiv.org/abs/2312.02134)] [[Project](https://huliangxiao.github.io/GaussianAvatar)]

**GaussianAvatars: Photorealistic Head Avatars with Rigged 3D Gaussians**<br>
*Shenhan Qian, Tobias Kirschstein, Liam Schoneveld, Davide Davoli, Simon Giebenhain, Matthias Nießner*<br>
arXiv preprint, 4 Dec 2023<br>
[[arXiv](https://arxiv.org/abs/2312.02069)] [[Project](https://shenhanqian.github.io/gaussian-avatars)]

**GaussianHead: Impressive 3D Gaussian-based Head Avatars with Dynamic Hybrid Neural Field**<br>
*Jie Wang, Xianyan Li, Jiucheng Xie, Feng Xu, Hao Gao*<br>
arXiv preprint, 4 Dec 2023<br>
[[arXiv](https://arxiv.org/abs/2312.01632)]

**GauHuman: Articulated Gaussian Splatting from Monocular Human Videos**<br>
*Shoukang Hu, Ziwei Liu*<br>
CVPR 2024, 5 Dec, 2023<br>
[[arXiv](https://arxiv.org/abs/2312.02973)] [[Project](https://skhu101.github.io/GauHuman/)] [[Code](https://github.com/skhu101/GauHuman)]

**HeadGaS: Real-Time Animatable Head Avatars via 3D Gaussian Splatting**<br>
*Helisa Dhamo, Yinyu Nie, Arthur Moreau, Jifei Song, Richard Shaw, Yiren Zhou, Eduardo Pérez-Pellitero*<br>
arXiv preprint, 5 Dec, 2023<br>
[[arXiv](https://arxiv.org/abs/2312.02902)]

**Relightable Gaussian Codec Avatars**<br>
*Shunsuke Saito, Gabriel Schwartz, Tomas Simon, Junxuan Li, Giljoo Nam*<br>
CVPR 2024, 5 Dec 2023<br>
[[arXiv](https://arxiv.org/abs/2312.03704)] [[Project](https://shunsukesaito.github.io/rgca/)]

**HiFi4G: High-Fidelity Human Performance Rendering via Compact Gaussian Splatting**<br>
*Yuheng Jiang, Zhehao Shen, Penghao Wang, Zhuo Su, Yu Hong, Yingliang Zhang, Jingyi Yu, Lan Xu*<br>
arXiv preprint, 6 Dec, 2023<br>
[[arXiv](https://arxiv.org/abs/2312.03461)]

**MonoGaussianAvatar: Monocular Gaussian Point-based Head Avatar**<br>
*Yufan Chen, Lizhen Wang, Qijing Li, Hongjiang Xiao, Shengping Zhang, Hongxun Yao, Yebin Liu*<br>
SIGGRAPH 2024, 7 Dec, 2023<br>
[[arXiv](https://arxiv.org/abs/2312.04558)] [[Project](https://yufan1012.github.io/MonoGaussianAvatar)] [[Code](https://github.com/yufan1012/MonoGaussianAvatar)] [[Video](https://www.youtube.com/embed/3UvBkyPc-oc)]

**ASH: Animatable Gaussian Splats for Efficient and Photoreal Human Rendering**<br>
*Haokai Pang, Heming Zhu, Adam Kortylewski, Christian Theobalt, Marc Habermann*<br>
arXiv preprint, 10 Dec 2023<br>
[[arXiv](https://arxiv.org/abs/2312.05941)] [[Project](https://vcai.mpi-inf.mpg.de/projects/ash/)] [[Code](https://github.com/kv2000/ASH)]

**3DGS-Avatar: Animatable Avatars via Deformable 3D Gaussian Splatting**<br>
*Zhiyin Qian, Shaofei Wang, Marko Mihajlovic, Andreas Geiger, Siyu Tang*<br>
CVPR 2024, 14 Dec 2023<br>
[[arXiv](https://arxiv.org/abs/2312.09228)] [[Project](https://neuralbodies.github.io/3DGS-Avatar/)] [[Code](https://github.com/mikeqzy/3dgs-avatar-release)]

**GAvatar: Animatable 3D Gaussian Avatars with Implicit Mesh Learning**<br>
*Ye Yuan, Xueting Li, Yangyi Huang, Shalini De Mello, Koki Nagano, Jan Kautz, Umar Iqbal*<br>
CVPR 2024, 18 Dec 2023<br>
[[arXiv](https://arxiv.org/abs/2312.11461)] [[Project](https://nvlabs.github.io/GAvatar/)] [[Video](https://www.youtube.com/watch?v=PbCF1HzrKrs&feature=youtu.be)]

**3D Points Splatting for Real-Time Dynamic Hand Reconstruction**<br>
*Zheheng Jiang, Hossein Rahmani, Sue Black, Bryan M. Williams*<br>
arXiv preprint, 21 Dec 2023<br>
[[arXiv](https://arxiv.org/abs/2312.13770)]

**Human101: Training 100+FPS Human Gaussians in 100s from 1 View**<br>
*Mingwei Li, Jiachen Tao, Zongxin Yang, Yi Yang*<br>
arXiv preprint, 23 Dec 2023<br>
[[arXiv](https://arxiv.org/abs/2312.15258)] [[Code](https://github.com/longxiang-ai/Human101)]

**Gaussian Shadow Casting for Neural Characters**<br>
*Luis Bolanos, Shih-Yang Su, Helge Rhodin*<br>
arXiv preprint, 11 Jan 2024<br>
[[arXiv](https://arxiv.org/abs/2401.06116)]

**GPAvatar: Generalizable and Precise Head Avatar from Image(s)**<br>
*Xuangeng Chu, Yu Li, Ailing Zeng, Tianyu Yang, Lijian Lin, Yunfei Liu, Tatsuya Harada*<br>
ICLR 2024, 18 Jan 2024<br>
[[arXiv](https://arxiv.org/abs/2401.10215)] [[Code](https://github.com/xg-chu/GPAvatar)]

**PSAvatar: A Point-based Morphable Shape Model for Real-Time Head Avatar Creation with 3D Gaussian Splatting**<br>
*Zhongyuan Zhao, Zhenyu Bao, Qing Li, Guoping Qiu, Kanglin Liu*<br>
arXiv preprint, 23 Jan 2024<br>
[[arXiv](https://arxiv.org/abs/2401.12900)]

**ImplicitDeepfake: Plausible Face-Swapping through Implicit Deepfake Generation using NeRF and Gaussian Splatting**<br>
*Georgii Stanishevskii, Jakub Steczkiewicz, Tomasz Szczepanik, Sławomir Tadeja, Jacek Tabor, Przemysław Spurek*<br>
arXiv preprint, 9 Feb 2024<br>
[[arXiv](https://arxiv.org/abs/2402.06390)]

**GaussianHair: Hair Modeling and Rendering with Light-aware Gaussians**<br>
*Haimin Luo, Min Ouyang, Zijun Zhao, Suyi Jiang, Longwen Zhang, Qixuan Zhang, Wei Yang, Lan Xu, Jingyi Yu*<br>
arXiv preprint, 16 Feb 2024<br>
[[arXiv](https://arxiv.org/abs/2402.10483)]

**HeadStudio: Text to Animatable Head Avatars with 3D Gaussian Splatting**<br>
*Zhenglin Zhou, Fan Ma, Hehe Fan, Yi Yang*<br>
arXiv preprint, 9 Feb 2024<br>
[[arXiv](https://arxiv.org/abs/2402.06149)]

**Rig3DGS: Creating Controllable Portraits from Casual Monocular Videos**<br>
*Alfredo Rivero, ShahRukh Athar, Zhixin Shu, Dimitris Samaras*<br>
arXiv preprint, 6 Feb 2024<br>
[[arXiv](https://arxiv.org/abs/2402.03723)] [[Project](https://shahrukhathar.github.io/2024/02/05/Rig3DGS.html)]

**SplatFace: Gaussian Splat Face Reconstruction Leveraging an Optimizable Surface**<br>
*Jiahao Luo, Jing Liu, James Davis*<br>
arXiv preprint, 27 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.18784)]

**HAHA: Highly Articulated Gaussian Human Avatars with Textured Mesh Prior**<br>
*David Svitov, Pietro Morerio, Lourdes Agapito, Alessio Del Bue*<br>
arXiv preprint, 1 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.01053)]

**GoMAvatar: Efficient Animatable Human Modeling from Monocular Video Using Gaussians-on-Mesh**<br>
*Jing Wen, Xiaoming Zhao, Zhongzheng Ren, Alexander G. Schwing, Shenlong Wang*<br>
CVPR 2024, 11 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.07991)] [[Project](https://wenj.github.io/GoMAvatar/)] [[Code](https://github.com/wenj/GoMAvatar)]

**OccGaussian: 3D Gaussian Splatting for Occluded Human Rendering**<br>
*Jingrui Ye, Zongkai Zhang, Yujiao Jiang, Qingmin Liao, Wenming Yang, Zongqing Lu*<br>
arXiv preprint, 12 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.08449)]

**GaussianTalker: Speaker-specific Talking Head Synthesis via 3D Gaussian Splatting**<br>
*Hongyun Yu, Zhan Qu, Qihang Yu, Jianchuan Chen, Zhonghua Jiang, Zhiwen Chen, Shengyu Zhang, Jimin Xu, Fei Wu, Chengfei Lv, Gang Yu*<br>
arXiv preprint, 22 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.14037)] [[Project](https://yuhongyun777.github.io/GaussianTalker/)] [[Video](https://youtu.be/TYS-WlAchvM)]

**3D Gaussian Blendshapes for Head Avatar Animation**<br>
*Shengjie Ma, Yanlin Weng, Tianjia Shao, Kun Zhou*<br>
SIGGRAPH 2024, 30 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.19398)]

**GaussianTalker: Real-Time High-Fidelity Talking Head Synthesis with Audio-Driven 3D Gaussian Splatting**<br>
*Kyusun Cho, Joungbin Lee, Heeji Yoon, Yeobin Hong, Jaehoon Ko, Sangjun Ahn, Seungryong Kim*<br>
arXiv preprint, 24 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.16012)] [[Code](https://github.com/KU-CVLAB/GaussianTalker/)]

**GSTalker: Real-time Audio-Driven Talking Face Generation via Deformable Gaussian Splatting**<br>
*Bo Chen, Shoukang Hu, Qi Chen, Chenpeng Du, Ran Yi, Yanmin Qian, Xie Chen*<br>
arXiv preprint, 29 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.19040)]

**MeGA: Hybrid Mesh-Gaussian Head Avatar for High-Fidelity Rendering and Head Editing**<br>
*Cong Wang, Di Kang, He-Yi Sun, Shen-Han Qian, Zi-Xuan Wang, Linchao Bao, Song-Hai Zhang*<br>
arXiv preprint, 29 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.19026)] [[Project](https://conallwang.github.io/MeGA_Pages/)]

**Tele-Aloha: A Low-budget and High-authenticity Telepresence System Using Sparse RGB Cameras**<br>
*Hanzhang Tu, Ruizhi Shao, Xue Dong, Shunyuan Zheng, Hao Zhang, Lili Chen, Meili Wang, Wenyu Li, Siyan Ma, Shengping Zhang, Boyao Zhou, Yebin Liu<br>
SIGGRAPH 2024, 23 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.14866)] [[Project](http://118.178.32.38/c/Tele-Aloha/)] [[Video](http://118.178.32.38/c/Tele-Aloha/#vid)]

**LAGA: Layered 3D Avatar Generation and Customization via Gaussian Splatting**<br>
*Jia Gong, Shenyu Ji, Lin Geng Foo, Kang Chen, Hossein Rahmani, Jun Liu*<br>
arXiv preprint, 21 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.12663)]

**Gaussian Control with Hierarchical Semantic Graphs in 3D Human Recovery**<br>
*Hongsheng Wang, Weiyue Zhang, Sihao Liu, Xinrui Zhou, Shengyu Zhang, Fei Wu, Feng Lin*<br>
arXiv preprint, 21 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.12477)] [[Project](https://wanghongsheng01.github.io/HUGS/)] [[Code](https://github.com/3DHumanRehab/SemanticGraph-Gaussian)]

**Gaussian Head & Shoulders: High Fidelity Neural Upper Body Avatars with Anchor Gaussian Guided Texture Warping**<br>
*Tianhao Wu, Jing Yang, Zhilin Guo, Jingyi Wan, Fangcheng Zhong, Cengiz Oztireli*<br>
arXiv preprint, 20 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.12069)] [[Project](https://gaussian-head-shoulders.netlify.app)]

**FAGhead: Fully Animate Gaussian Head from Monocular Videos**<br>
*Yixin Xuan, Xinyang Li, Gongxin Yao, Shiwei Zhou, Donghui Sun, Xiaoxin Chen, Yu Pan*<br>
arXiv preprint, 27 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.19070)]

**Expressive Gaussian Human Avatars from Monocular RGB Video**<br>
*Hezhen Hu, Zhiwen Fan, Tianhao Wu, Yihan Xi, Seoyoung Lee, Georgios Pavlakos, Zhangyang Wang*<br>
arXiv preprint, 3 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.03204)] [[Project](https://evahuman.github.io/)]

**MeshAvatar: Learning High-quality Triangular Human Avatars from Multi-view Videos**<br>
*Yushuo Chen, Zerong Zheng, Zhe Li, Chao Xu, Yebin Liu*<br>
arXiv preprint, 11 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.08414)] [[Project](https://shad0wta9.github.io/meshavatar-page/)] [[Code](https://github.com/shad0wta9/meshavatar)]

**Interactive Rendering of Relightable and Animatable Gaussian Avatars**<br>
*Youyi Zhan, Tianjia Shao, He Wang, Yin Yang, Kun Zhou*<br>
arXiv preprint, 15 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.10707)]

**Generalizable Human Gaussians for Sparse View Synthesis**<br>
*Youngjoong Kwon, Baole Fang, Yixing Lu, Haoye Dong, Cheng Zhang, Francisco Vicente Carrasco, Albert Mosella-Montoro, Jianjin Xu, Shingo Takagi, Daeil Kim, Aayush Prakash, Fernando De la Torre*<br>
arXiv preprint, 17 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.12777)]

**iHuman: Instant Animatable Digital Humans From Monocular Videos**<br>
*Pramish Paudel, Anubhav Khanal, Ajad Chhatkuli, Danda Pani Paudel, Jyoti Tandukar*<br>
ECCV 2024, 15 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.11174)]

**HeadGAP: Few-shot 3D Head Avatar via Generalizable Gaussian Priors**<br>
*Xiaozheng Zheng, Chao Wen, Zhaohu Li, Weiyi Zhang, Zhuo Su, Xu Chang, Yang Zhao, Zheng Lv, Xiaoyuan Zhang, Yongjie Zhang, Guidong Wang, Lan Xu*<br>
arXiv preprint, 12 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.06019)] [[Project](https://headgap.github.io/)]

**DEGAS: Detailed Expressions on Full-Body Gaussian Avatars**<br>
*Zhijing Shao, Duotun Wang, Qing-Yao Tian, Yao-Dong Yang, Hengyu Meng, Zeyu Cai, Bo Dong, Yu Zhang, Kang Zhang, Zeyu Wang*<br>
arXiv preprint, 20 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.10588)]

**SG-GS: Photo-realistic Animatable Human Avatars with Semantically-Guided Gaussian Splatting**<br>
*Haoyu Zhao, Chen Yang, Hao Wang, Xingyue Zhao, Wei Shen*<br>
arXiv preprint, 19 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.09665)]

**CHASE: 3D-Consistent Human Avatars with Sparse Inputs via Gaussian Splatting and Contrastive Learning**<br>
*Haoyu Zhao, Hao Wang, Chen Yang, Wei Shen*<br>
arXiv preprint, 19 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.09663)]

**Human-VDM: Learning Single-Image 3D Human Gaussian Splatting from Video Diffusion Models**<br>
*Zhibin Liu, Haoye Dong, Aviral Chharia, Hefeng Wu*<br>
arXiv preprint, 4 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.02851)] [[Project](https://human-vdm.github.io/Human-VDM/)] [[Code](https://github.com/Human-VDM/Human-VDM)]

**Instant Facial Gaussians Translator for Relightable and Interactable Facial Rendering**<br>
*Dafei Qin, Hongyang Lin, Qixuan Zhang, Kaichun Qiao, Longwen Zhang, Zijun Zhao, Jun Saito, Jingyi Yu, Lan Xu, Taku Komura*<br>
arXiv preprint, 11 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.07441)] [[Project](https://dafei-qin.github.io/TransGS.github.io/)] [[Video](https://www.youtube.com/watch?v=MQTm3WTQ3KI)]

**GST: Precise 3D Human Body from a Single Image with Gaussian Splatting Transformers**<br>
*Lorenza Prospero, Abdullah Hamdi, Joao F. Henriques, Christian Rupprecht*<br>
arXiv preprint, 6 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.04196)] [[Project](https://abdullahamdi.com/gst/)] [[Video](https://youtu.be/nlo6VN_WXrs)] [[Code](https://github.com/prosperolo/GST)]

**JEAN: Joint Expression and Audio-guided NeRF-based Talking Face Generation**<br>
*Sai Tanmay Reddy Chakkera, Aggelina Chatziagapi, Dimitris Samaras*<br>
BMVC 2024, 18 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.12156)] [[Project](https://starc52.github.io/publications/2024-07-19-JEAN/)] [[Video](https://www.youtube.com/watch?v=iTlW1HyxFDQ)]

**Disco4D: Disentangled 4D Human Generation and Animation from a Single Image**<br>
*Hui En Pang, Shuai Liu, Zhongang Cai, Lei Yang, Tianwei Zhang, Ziwei Liu*<br>
arXiv preprint, 25 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.17280)] [[Project](https://disco-4d.github.io/)]

**Gaussian Deja-vu: Creating Controllable 3D Gaussian Head-Avatars with Enhanced Generalization and Personalization Abilities**<br>
*Peizhi Yan, Rabab Ward, Qiang Tang, Shan Du*<br>
WACV 2024, 23 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.16147)]

**Human Hair Reconstruction with Strand-Aligned 3D Gaussians**<br>
*Egor Zakharov, Vanessa Sklyarova, Michael Black, Giljoo Nam, Justus Thies, Otmar Hilliges*<br>
arXiv preprint, 23 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.14778)]

**EVA-Gaussian: 3D Gaussian-based Real-time Human Novel View Synthesis under Diverse Camera Settings**<br>
*Yingdong Hu, Zhening Liu, Jiawei Shao, Zehong Lin, Jun Zhang*<br>
arXiv preprint, 2 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.01425)] [[Project](https://zhenliuzju.github.io/huyingdong/EVA-Gaussian)]


**DifFRelight: Diffusion-Based Facial Performance Relighting**<br>
*Mingming He, Pascal Clausen, Ahmet Levent Taşel, Li Ma, Oliver Pilarski, Wenqi Xian, Laszlo Rikker, Xueming Yu, Ryan Burgert, Ning Yu, Paul Debevec*<br>
SIGGRAPH Asia 2024, 10 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.08188)]  [[Project](https://www.eyelinestudios.com/research/diffrelight.html)]

**GS-VTON: Controllable 3D Virtual Try-on with Gaussian Splatting**<br>
*Yukang Cao, Masoud Hadi, Liang Pan, Ziwei Liu*<br>
arXiv preprint, 7 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.05259)]

**LoDAvatar: Hierarchical Embedding and Adaptive Levels of Detail with Gaussian Splatting for Enhanced Human Avatars**<br>
*Xiaonuo Dongye, Hanzhi Guo, Le Luo, Haiyan Jiang, Yihua Bao, Zeyu Tian, Dongdong Weng*<br>
arXiv preprint, 28 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.20789)]

**HFGaussian: Learning Generalizable Gaussian Human with Integrated Human Features**<br>
*Arnab Dey, Cheng-You Lu, Andrew I. Comport, Srinath Sridhar, Chin-Teng Lin, Jean Martinet*<br>
arXiv preprint, 5 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.03086)]

**GazeGaussian: High-Fidelity Gaze Redirection with 3D Gaussian Splatting**<br>
*Xiaobao Wei, Peng Chen, Guangyu Li, Ming Lu, Hui Chen, Feng Tian*<br>
20 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.12981)] [[Project](https://ucwxb.github.io/GazeGaussian/)]

## 3DGS Clothes/Garment

**GaussianVTON: 3D Human Virtual Try-ON via Multi-Stage Gaussian Splatting Editing with Image Prompting**<br>
*Haodong Chen, Yongle Huang, Haojian Huang, Xiangsheng Ge, Dian Shao*<br>
arXiv preprint, 13 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.07472)]

**MOSS: Motion-based 3D Clothed Human Synthesis from Monocular Video**<br>
*Hongsheng Wang, Xiang Cai, Xi Sun, Jinhong Yue, Shengyu Zhang, Feng Lin, Fei Wu*<br>
arXiv preprint, 21 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.12806)] [[Project](https://wanghongsheng01.github.io/MOSS/)] [[Code](https://github.com/3DHumanRehab/MOSS)]

**GarmentDreamer: 3DGS Guided Garment Synthesis with Diverse Geometry and Texture Details**<br>
*Boqian Li, Xuan Li, Ying Jiang, Tianyi Xie, Feng Gao, Huamin Wang, Yin Yang, Chenfanfu Jiang*<br>
arXiv preprint, 20 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.12420)] [[Project](https://xuan-li.github.io/GarmentDreamerDemo/)]

**NPGA: Neural Parametric Gaussian Avatars**<br>
*Simon Giebenhain, Tobias Kirschstein, Martin Rünz, Lourdes Agapito, Matthias Nießner*<br>
arXiv preprint, 29 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.19331)] [[Project](https://simongiebenhain.github.io/NPGA/)] [[Video](https://www.youtube.com/watch?v=NGRxAYbIkus)]

**GGHead: Fast and Generalizable 3D Gaussian Heads**<br>
*Tobias Kirschstein, Simon Giebenhain, Jiapeng Tang, Markos Georgopoulos, Matthias Nießner*<br>
arXiv preprint, 13 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.09377)] [[Projectt](https://tobias-kirschstein.github.io/gghead/)] [[Video](https://www.youtube.com/watch?v=1iyC74neQXc)]

**Human 3Diffusion: Realistic Avatar Creation via Explicit 3D Consistent Diffusion Models**<br>
*Yuxuan Xue, Xianghui Xie, Riccardo Marin, Gerard Pons-Moll*<br>
arXiv preprint, 12 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.08475)] [[Project](https://yuxuan-xue.com/human-3diffusion/)] [[Code](https://github.com/YuxuanSnow/Human3Diffusion/)]

**HumanSplat: Generalizable Single-Image HumanGaussianSplattingwith Structure Priors**<br>
*Panwang Pan, Zhuo Su, Chenguo Lin, Zhen Fan, Yongjie Zhang, Zeming Li, Tingting Shen, Yadong Mu, Yebin Liu*<br>
arXiv preprint, 18 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.12459)] [[Project](https://humansplat.github.io/)]

**PICA: Physics-Integrated Clothed Avatar**<br>
*Bo Peng, Yunfan Tao, Haoyu Zhan, Yudong Guo, Juyong Zhang*<br>
arXiv preprint, 7 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.05324)] [[Project](https://ustc3dv.github.io/PICA/)]

**Gaussian Eigen Models for Human Heads**<br>
*Wojciech Zielonka, Timo Bolkart, Thabo Beeler, Justus Thies*<br>
arXiv preprint, 5 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.04545)] [[Project](https://zielon.github.io/gem/)]

## 3DGS Scene Editing and Animation

**Animatable 3D Gaussians for High-fidelity Synthesis of Human Motions**<br>
*Keyang Ye, Tianjia Shao, Kun Zhou*<br>
arXiv preprint, 22 Nov 2023<br>
[[arXiv](https://arxiv.org/abs/2311.13404)]

**GaussianEditor: Swift and Controllable 3D Editing with Gaussian Splatting**<br>
*Yiwen Chen, Zilong Chen, Chi Zhang, Feng Wang, Xiaofeng Yang, Yikai Wang, Zhongang Cai, Lei Yang, Huaping Liu, Guosheng Lin*<br>
arXiv preprint, 24 Nov 2023<br>
[[arXiv](https://arxiv.org/abs/2311.14521)] [[Project](https://buaacyw.github.io/gaussian-editor/)]

**Relightable 3D Gaussian: Real-time Point Cloud Relighting with BRDF Decomposition and Ray Tracing**<br>
*Jian Gao, Chun Gu, Youtian Lin, Hao Zhu, Xun Cao, Li Zhang, Yao Yao*<br>
arXiv preprint, 27 Nov 2023<br>
[[arXiv](https://arxiv.org/abs/2311.16043)] [[Project](https://nju-3dv.github.io/projects/Relightable3DGaussian/)]

**GART: Gaussian Articulated Template Models**<br>
*Jiahui Lei, Yufu Wang, Georgios Pavlakos, Lingjie Liu, Kostas Daniilidis*<br>
arXiv preprint, 27 Nov 2023<br>
[[arXiv](https://arxiv.org/abs/2311.16099)] [[Project](https://www.cis.upenn.edu/~leijh/projects/gart/)]

**Animatable Gaussians: Learning Pose-dependent Gaussian Maps for High-fidelity Human Avatar Modeling**<br>
*Zhe Li, Zerong Zheng, Lizhen Wang, Yebin Liu*<br>
arXiv preprint, 27 Nov 2023<br>
[[arXiv](https://arxiv.org/abs/2311.16096)] [[Project](https://animatable-gaussians.github.io/)]

**Point'n Move: Interactive Scene Object Manipulation on Gaussian Splatting Radiance Fields**<br>
*Jiajun Huang, Hongchuan Yu*<br>
arXiv preprint, 28 Nov, 2023<br>
[[arXiv](https://arxiv.org/abs/2311.16737)]

**TIP-Editor: An Accurate 3D Editor Following Both Text-Prompts And Image-Prompts**<br>
*Jingyu Zhuang, Di Kang, Yan-Pei Cao, Guanbin Li, Liang Lin, Ying Shan*<br>
SIGGRAPH 2024, 26 Jan 2024<br>
[[arXiv](https://arxiv.org/abs/2401.14828)]

**GaMeS: Mesh-Based Adapting and Modification of Gaussian Splatting**<br>
*Joanna Waczyńska, Piotr Borycki, Sławomir Tadeja, Jacek Tabor, Przemysław Spurek*<br>
arXiv preprint, 2 Feb 2024<br>
[[arXiv](https://arxiv.org/abs/2402.01459)]

**GaussCtrl: Multi-View Consistent Text-Driven 3D Gaussian Splatting Editing**<br>
*Jing Wu, Jia-Wang Bian, Xinghui Li, Guangrun Wang, Ian Reid, Philip Torr, Victor Adrian Prisacariu*<br>
arXiv preprint, 13 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.08733)] [[Project](https://gaussctrl.active.vision/)]

**Texture-GS: Disentangling the Geometry and Texture for 3D Gaussian Splatting Editing**<br>
*Tian-Xing Xu, Wenbo Hu, Yu-Kun Lai, Ying Shan, Song-Hai Zhang*<br>
arXiv preprint, 15 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.10050)]

**View-Consistent 3D Editing with Gaussian Splatting**<br>
*Yuxuan Wang, Xuanyu Yi, Zike Wu, Na Zhao, Long Chen, Hanwang Zhang*<br>
arXiv preprint, 18 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.11868)] [[Project](https://yuxuanw.me/vcedit/)]

:fire:**Feature Splatting: Language-Driven Physics-Based Scene Synthesis and Editing**<br>
*Ri-Zhao Qiu, Ge Yang, Weijia Zeng, Xiaolong Wang*<br>
ECCV 2024, 1 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.01223)] [[Project](https://feature-splatting.github.io/)] [[Code](https://github.com/vuer-ai/feature_splatting)]

**GScream: Learning 3D Geometry and Feature Consistent Gaussian Splatting for Object Removal**<br>
*Yuxin Wang, Qianyi Wu, Guofeng Zhang, Dan Xu*<br>
arXiv preprint, 21 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.13679)] [[Project](https://w-ted.github.io/publications/gscream/)]

**DGE: Direct Gaussian 3D Editing by Consistent Multi-view Editing**<br>
*Minghao Chen, Iro Laina, Andrea Vedaldi*<br>
arXiv preprint, 29 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.18929)] [[Project](https://silent-chen.github.io/DGE/)] [[Code](https://github.com/silent-chen/DGE)]

**TIGER: Text-Instructed 3D Gaussian Retrieval and Coherent Editing**<br>
*Teng Xu, Jiamin Chen, Peng Chen, Youjia Zhang, Junqing Yu, Wei Yang*<br>
arXiv preprint, 23 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.14455)]

**D-MiSo: Editing Dynamic 3D Scenes using Multi-Gaussians Soup**<br>
*Joanna Waczyńska, Piotr Borycki, Joanna Kaleta, Sławomir Tadeja, Przemysław Spurek*<br>
arXiv preprint, 23 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.14276)]

**ICE-G: Image Conditional Editing of 3D Gaussian Splats**<br>
*Vishnu Jaganathan, Hannah Hanyun Huang, Muhammad Zubair Irshad, Varun Jampani, Amit Raj, Zsolt Kira*<br>
CVPR AI4CC Workshop 2024, 12 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.08488)] [[Project](https://ice-gaussian.github.io/)]

**3DEgo: 3D Editing on the Go!**<br>
*Umar Khalid, Hasan Iqbal, Azib Farooq, Jing Hua, Chen Chen*<br>
ECCV 2024, 14 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.10102)] [[Project](https://3dego.github.io/)]

**3D Gaussian Editing with A Single Image**<br>
*Guan Luo, Tian-Xing Xu, Ying-Tian Liu, Xiao-Xiong Fan, Fang-Lue Zhang, Song-Hai Zhang*<br>
arXiv preprint, 14 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.07540)]

**LumiGauss: High-Fidelity Outdoor Relighting with 2D Gaussian Splatting**<br>
*Joanna Kaleta, Kacper Kania, Tomasz Trzcinski, Marek Kowalski*<br>
arXiv preprint, 6 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.04474)]

**Generative Object Insertion in Gaussian Splatting with a Multi-View Diffusion Model**<br>
*Hongliang Zhong, Can Wang, Jingbo Zhang, Jing Liao*<br>
arXiv preprint, 25 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.16938)] [[Code](https://github.com/JiuTongBro/MultiView_Inpaint)]

**GaussianBlock: Building Part-Aware Compositional and Editable 3D Scene by Primitives and Gaussians**<br>
*Shuyi Jiang, Qihao Zhao, Hossein Rahmani, De Wen Soh, Jun Liu, Na Zhao*<br>
arXiv preprint, 2 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.01535)]

**MiraGe: Editable 2D Images using Gaussian Splatting**<br>
*Joanna Waczyńska, Tomasz Szczepanik, Piotr Borycki, Sławomir Tadeja, Thomas Bohné, Przemysław Spurek*<br>
arXiv preprint, 2 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.01521)]

**RNG: Relightable Neural Gaussians**<br>
*Jiahui Fan, Fujun Luan, Jian Yang, Miloš Hašan, Beibei Wang*<br>
arXiv preprint, 29 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.19702)]

**ProEdit: Simple Progression is All You Need for High-Quality 3D Scene Editing**<br>
*Jun-Kun Chen, Yu-Xiong Wang*<br>
NeurIPS 2024, 7 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.05006)] [[Project](https://immortalco.github.io/ProEdit/)]

## 3DGS Stylization

**Gaussian Splatting in Style**<br>
*Abhishek Saroha, Mariia Gladkova, Cecilia Curreli, Tarun Yenamandra, Daniel Cremers*<br>
arXiv preprint, 13 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.08498)]

**StyleGaussian: Instant 3D Style Transfer with Gaussian Splatting**<br>
*Kunhao Liu, Fangneng Zhan, Muyu Xu, Christian Theobalt, Ling Shao, Shijian Lu*<br>
arXiv preprint, 12 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.07807)] [[Project](https://kunhao-liu.github.io/StyleGaussian/)] [[Code](https://github.com/Kunhao-Liu/StyleGaussian)]

**StylizedGS: Controllable Stylization for 3D Gaussian Splatting**<br>
*Dingxi Zhang, Zhuoxun Chen, Yu-Jie Yuan, Fang-Lue Zhang, Zhenliang He, Shiguang Shan, Lin Gao*<br>
arXiv preprint, 8 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.05220)]

**InFusion: Inpainting 3D Gaussians via Learning Depth Completion from Diffusion Prior**<br>
*Zhiheng Liu, Hao Ouyang, Qiuyu Wang, Ka Leong Cheng, Jie Xiao, Kai Zhu, Nan Xue, Yu Liu, Yujun Shen, Yang Cao*<br>
arXiv preprint, 17 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.11613)] [[Project](https://johanan528.github.io/Infusion/)] [[Code](https://github.com/ali-vilab/infusion)]

**3DitScene: Editing Any Scene via Language-guided Disentangled Gaussian Splatting**<br>
*Qihang Zhang, Yinghao Xu, Chaoyang Wang, Hsin-Ying Lee, Gordon Wetzstein, Bolei Zhou, Ceyuan Yang*<br>
arXiv preprint, 28 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.18424)] [[Project](https://zqh0253.github.io/3DitScene/)] [[Code](https://github.com/zqh0253/3DitScene)]

**Enhancing Temporal Consistency in Video Editing by Reconstructing Videos with 3D Gaussian Splatting**<br>
*Inkyu Shin, Qihang Yu, Xiaohui Shen, In So Kweon, Kuk-Jin Yoon, Liang-Chieh Chen*<br>
arXiv preprint,  4 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.02541)] [[Project](https://video-3dgs-project.github.io/)]

**StyleSplat: 3D Object Style Transfer with Gaussian Splatting**<br>
*Sahil Jain, Avik Kuthiala, Prabhdeep Singh Sethi, Prakanshul Saxena*<br>
arXiv preprint, 12 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.09473)] [[Project](https://bernard0047.github.io/stylesplat/)]

**InstantStyleGaussian: Efficient Art Style Transfer with 3D Gaussian Splatting**<br>
*Xin-Yi Yu, Jun-Xin Yu, Li-Bo Zhou, Yan Wei, Lin-Lin Ou*<br>
arXiv preprint, 8 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.04249)]

**PRTGS: Precomputed Radiance Transfer of Gaussian Splats for Real-Time High-Quality Relighting**<br>
*Yijia Guo, Yuanxi Bai, Liwen Hu, Ziyi Guo, Mianzhi Liu, Yu Cai, Tiejun Huang, Lei Ma*<br>
arXiv preprint, 7 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.03538)]

**Towards Realistic Example-based Modeling via 3D Gaussian Stitching**<br>
*Xinyu Gao, Ziyi Yang, Bingchen Gong, Xiaoguang Han, Sipeng Yang, Xiaogang Jin*<br>
arXiv preprint, 28 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.15708)] [[Project](https://ingra14m.github.io/gs_stitching_website)]

**G-Style: Stylized Gaussian Splatting**<br>
*Áron Samuel Kovács, Pedro Hermosilla, Renata G. Raidou*<br>
arXiv preprint, 28 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.15695)]

**WaSt-3D: Wasserstein-2 Distance for Scene-to-Scene Stylization on 3D Gaussians**<br>
*Dmytro Kotovenko, Olga Grebenkova, Nikolaos Sarafianos, Avinash Paliwal, Pingchuan Ma, Omid Poursaeed, Sreyas Mohan, Yuchen Fan, Yilei Li, Rakesh Ranjan, Björn Ommer*<br>
arXiv preprint, 26 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.17917)] [[Project](https://compvis.github.io/wast3d/)] [[Code](https://github.com/facebookresearch/WaSt3D)]

**4DStyleGaussian: Zero-shot 4D Style Transfer with Gaussian Splatting**<br>
*Wanlin Liang, Hongbin Xu, Weitao Chen, Feng Xiao, Wenxiong Kang*<br>
arXiv preprint, 14 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.10412)]

## 3DGS Based Video Editing

**VeGaS: Video Gaussian Splatting**<br>
*Weronika Smolak-Dyżewska, Dawid Malarz, Kornel Howil, Jan Kaczmarczyk, Marcin Mazur, Przemysław Spurek*<br>
17 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.11024)] [[Code](https://github.com/gmum/VeGaS)]

## 3DGS for Computer Graphics

:fire:**PhysGaussian: Physics-Integrated 3D Gaussians for Generative Dynamics**<br>
*Tianyi Xie, Zeshun Zong, Yuxing Qiu, Xuan Li, Yutao Feng, Yin Yang, Chenfanfu Jiang*<br>
CVPR 2024, 20 Nov 2023<br>
[[arXiv](https://arxiv.org/abs/2311.12198)] [[Project](https://xpandora.github.io/PhysGaussian/)]

**Gaussian Splashing: Dynamic Fluid Synthesis with Gaussian Splatting**<br>
*Yutao Feng, Xiang Feng, Yintong Shang, Ying Jiang, Chang Yu, Zeshun Zong, Tianjia Shao, Hongzhi Wu, Kun Zhou, Chenfanfu Jiang, Yin Yang*<br>
arXiv preprint, 27 Jan 2024<br>
[[arXiv](https://arxiv.org/abs/2401.15318)] [[Project](https://amysteriouscat.github.io/GaussianSplashing/)] [[Video](https://www.youtube.com/watch?v=KgaR1ni-Egg&t=4s)]

**VR-GS: A Physical Dynamics-Aware Interactive Gaussian Splatting System in Virtual Reality**<br>
*Ying Jiang, Chang Yu, Tianyi Xie, Xuan Li, Yutao Feng, Huamin Wang, Minchen Li, Henry Lau, Feng Gao, Yin Yang, Chenfanfu Jiang*<br>
arXiv preprint, 30 Jan 2024<br>
[[arXiv](https://arxiv.org/abs/2401.16663)] [[Project](https://yingjiang96.github.io/VR-GS/)]

**A Grid-Free Fluid Solver based on Gaussian Spatial Representation**<br>
*Jingrui Xing, Bin Wang, Mengyu Chu, Baoquan Chen*<br>
arXiv preprint, 28 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.18133)]

**GS-Phong: Meta-Learned 3D Gaussians for Relightable Novel View Synthesis**<br>
*Yumeng He, Yunbo Wang, Xiaokang Yang*<br>
arXiv preprint, 31 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.20791)]

**DreamPhysics: Learning Physical Properties of Dynamic 3DGaussianswith Video Diffusion Priors**<br>
*Tianyu Huang, Yihan Zeng, Hui Li, Wangmeng Zuo, Rynson W. H. Lau*<br>
arXiv preprint, 3 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.01476)] [[Code](https://github.com/tyhuang0428/DreamPhysics)]

**GASP: Gaussian Splatting for Physic-Based Simulations**<br>
*Piotr Borycki, Weronika Smolak, Joanna Waczyńska, Marcin Mazur, Sławomir Tadeja, Przemysław Spurek*<br>
arXiv preprint, 9 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.05819)]

**Unleashing the Potential of Multi-modal Foundation Models and Video Diffusion for 4D Dynamic Physical Scene Simulation**<br>
*Zhuoman Liu, Weicai Ye, Yan Luximon, Pengfei Wan, Di Zhang*<br>
arXiv preprint, 21 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.14423)] [[Project](https://zhuomanliu.github.io/PhysFlow/)]

**Automated 3D Physical Simulation of Open-world Scene with Gaussian Splatting**<br>
*Haoyu Zhao, Hao Wang, Xingyue Zhao, Hongqiu Wang, Zhiyu Wu, Chengjiang Long, Hua Zou*<br>
arXiv preprint, 19 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.12789)]



## 3DGS Based Scene Understanding

**Language Embedded 3D Gaussians for Open-Vocabulary Scene Understanding**<br>
*Jin-Chuan Shi, Miao Wang, Hao-Bin Duan, Shao-Hua Guan*<br>
arXiv preprint, 30 Nov 2023<br>
[[arXiv](https://arxiv.org/abs/2311.18482)]

**Semantic Anything in 3D Gaussians**<br>
*Xu Hu, Yuxi Wang, Lue Fan, Junsong Fan, Junran Peng, Zhen Lei, Qing Li, Zhaoxiang Zhang*<br>
arXiv preprint, 31 Jan 2024<br>
[[arXiv](https://arxiv.org/abs/2401.17857)]

**Semantic Gaussians: Open-Vocabulary Scene Understanding with 3D Gaussian Splatting**<br>
*Jun Guo, Xiaojian Ma, Yue Fan, Huaping Liu, Qing Li*<br>
arXiv preprint, 22 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.15624)] [[Project](https://semantic-gaussians.github.io/)] [[Code](https://github.com/sharinka0715/semantic-gaussians)]

**CLIP-GS: CLIP-Informed Gaussian Splatting for Real-time and View-consistent 3D Semantic Understanding**<br>
*Guibiao Liao, Jiankun Li, Zhenyu Bao, Xiaoqing Ye, Jingdong Wang, Qing Li, Kanglin Liu*<br>
arXiv preprint, 22 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.14249)]  [[Code](https://github.com/gbliao/CLIP-GS)]

:fire:**HUGS: Holistic Urban 3D Scene Understanding via Gaussian Splatting**<br>
*Hongyu Zhou, Jiahao Shao, Lu Xu, Dongfeng Bai, Weichao Qiu, Bingbing Liu, Yue Wang, Andreas Geiger, Yiyi Liao*<br>
CVPR 2024, 19 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.12722)] [[Project](https://xdimlab.github.io/hugs_website/)]

**Memorize What Matters: Emergent Scene Decomposition from Multitraverse**<br>
*Yiming Li, Zehong Wang, Yue Wang, Zhiding Yu, Zan Gojcic, Marco Pavone, Chen Feng, Jose M. Alvarez*<br>
arXiv preprint, 27 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.17187)] [[Project](https://3d-gaussian-mapping.github.io/)] [[Code](https://github.com/NVlabs/3DGM)]

**FastLGS: Speeding up Language Embedded Gaussians with Feature Grid Mapping**<br>
*Yuzhou Ji, He Zhu, Junshu Tang, Wuyi Liu, Zhizhong Zhang, Yuan Xie, Lizhuang Ma, Xin Tan*<br>
arXiv preprint, 4 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.01916)]

**OpenGaussian: Towards Point-Level 3D Gaussian-based Open Vocabulary Understanding**<br>
*Yanmin Wu, Jiarui Meng, Haijie Li, Chenming Wu, Yahao Shi, Xinhua Cheng, Chen Zhao, Haocheng Feng, Errui Ding, Jingdong Wang, Jian Zhang*<br>
arXiv preprint, 4 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.02058)] [[Project](https://3d-aigc.github.io/OpenGaussian/)]

**EgoGaussian: Dynamic Scene Understanding from Egocentric Video with 3D Gaussian Splatting**<br>
*Daiwei Zhang, Gengyan Li, Jiajie Li, Mickaël Bressieux, Otmar Hilliges, Marc Pollefeys, Luc Van Gool, Xi Wang*<br>
arXiv preprint, 28 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.19811)]

**Scaling 3D Reasoning with LMMs to Large Robot Mission Environments Using Datagraphs**<br>
*W. J. Meijer, A.C. Kemmeren, E.H.J. Riemens, J.E. Fransman, M. van Bekkum, G.J. Burghouts, J.D. van Mil*<br>
RSS Workshop on Semantics for Robotics 2024, 15 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.10743)]

**SpectralGaussians: Semantic, spectral 3D Gaussian splatting for multi-spectral scene representation, visualization and analysis**<br>
*Saptarshi Neil Sinha, Holger Graf, Michael Weinmann*<br>
arXiv preprint, 13 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.06975)]

:fire:**ShapeSplat: A Large-scale Dataset of Gaussian Splats and Their Self-Supervised Pretraining**<br>
*Qi Ma, Yue Li, Bin Ren, Nicu Sebe, Ender Konukoglu, Theo Gevers, Luc Van Gool, Danda Pani Paudel*<br>
arXiv preprint, 20 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.10906)]

**GS-PT: Exploiting 3D Gaussian Splatting for Comprehensive Point Cloud Understanding via Self-supervised Learning**<br>
*Keyi Liu, Yeqi Luo, Weidong Yang, Jingyi Xu, Zhijun Li, Wen-Ming Chen, Ben Fei*<br>
arXiv preprint, 8 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.04963)]

**Gradient-Driven 3D Segmentation and Affordance Transfer in Gaussian Splatting Using 2D Masks**<br>
*Joji Joseph, Bharadwaj Amrutur, Shalabh Bhatnagar*<br>
arXiv preprint, 18 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.11681)] [[Project](https://jojijoseph.github.io/3dgs-segmentation/)] [[Code](https://github.com/JojiJoseph/3dgs-gradient-segmentation)]

**EdgeGaussians -- 3D Edge Mapping via Gaussian Splatting**<br>
*Kunal Chelani, Assia Benbihi, Torsten Sattler, Fredrik Kahl*<br>
arXiv preprint, 19 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.12886)] [[Code](https://github.com/kunalchelani/EdgeGaussians)]

**SRIF: Semantic Shape Registration Empowered by Diffusion-based Image Morphing and Flow Estimation**<br>
*Mingze Sun, Chen Guo, Puhua Jiang, Shiwei Mao, Yurun Chen, Ruqi Huang*<br>
arXiv preprint, 18 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.11682)]
 
**Semantics-Controlled Gaussian Splatting for Outdoor Scene Reconstruction and Rendering in Virtual Reality**<br>
*Hannah Schieber, Jacob Young, Tobias Langlotz, Stefanie Zollmann, Daniel Roth*<br>
arXiv preprint, 24 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.15959)]

**3DGS-DET: Empower 3D Gaussian Splatting with Boundary Guidance and Box-Focused Sampling for 3D Object Detection**<br>
*Yang Cao, Yuanliang Jv, Dan Xu*<br>
arXiv preprint, 2 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.01647)] [[Code](https://github.com/yangcaoai/3DGS-DET)]

**Gaussian-Det: Learning Closed-Surface Gaussians for 3D Object Detection**<br>
*Hongru Yan, Yu Zheng, Yueqi Duan*<br>
arXiv preprint, 2 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.01404)]

**3D Vision-Language Gaussian Splatting**<br>
*Qucheng Peng, Benjamin Planche, Zhongpai Gao, Meng Zheng, Anwesa Choudhuri, Terrence Chen, Chen Chen, Ziyan Wu*<br>
arXiv preprint, 10 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.07577)]

**4-LEGS: 4D Language Embedded Gaussian Splatting**<br>
*Gal Fiebelman, Tamir Cohen, Ayellet Morgenstern, Peter Hedman, Hadar Averbuch-Elor*<br>
arXiv preprint, 14 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.10719)] [[Project](https://tau-vailab.github.io/4-LEGS/)]

**3DArticCyclists: Generating Simulated Dynamic 3D Cyclists for Human-Object Interaction (HOI) and Autonomous Driving Applications**<br>
*Eduardo R. Corral-Soto, Yang Liu, Tongtong Cao, Yuan Ren, Liu Bingbing*<br>
arXiv preprint, 14 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.10782)]

**MVSDet: Multi-View Indoor 3D Object Detection via Efficient Plane Sweeps**<br>
*Yating Xu, Chen Li, Gim Hee Lee*<br>
NeurIPS 2024, 28 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.21566)] [[Code](https://github.com/Pixie8888/MVSDet)]

**Splat: FAST-Fast, Ambiguity-Free Semantics Transfer in Gaussian Splatting**<br>
*Ola Shorinwa, Jiankai Sun, Mac Schwager*<br>
arXiv preprint, 20 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.13753)]

## 3DGS based Segmentation

**2D-Guided 3D Gaussian Segmentation**<br>
*Kun Lan, Haoran Li, Haolin Shi, Wenjun Wu, Yong Liao, Lin Wang, Pengyuan Zhou*<br>
arXiv preprint, 26 Dec 2023<br>
[[arXiv](https://arxiv.org/abs/2312.16047)]

**CoSSegGaussians: Compact and Swift Scene Segmenting 3D Gaussians**<br>
*Bin Dou, Tianyu Zhang, Yongjia Ma, Zhaohui Wang, Zejian Yuan*<br>
arXiv preprint, 11 Jan 2024<br>
[[arXiv](https://arxiv.org/abs/2401.05925)] [[Project](https://david-dou.github.io/CoSSegGaussians/)]

**OMEGAS: Object Mesh Extraction from Large Scenes Guided by Gaussian Segmentation**<br>
*Lizhi Wang, Feng Zhou, Jianqin Yin*
arXiv preprint, 24 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.15891)] [[Code](https://github.com/CrystalWlz/OMEGAS)]

**RT-GS2: Real-Time Generalizable Semantic Segmentation for 3D Gaussian Representations of Radiance Fields**<br>
*Mihnea-Bogdan Jurca, Remco Royen, Ion Giosan, Adrian Munteanu*<br>
arXiv preprint, 28 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.18033)]

**Fast and Efficient: Mask Neural Fields for 3D Scene Segmentation**<br>
*Zihan Gao, Lingling Li, Licheng Jiao, Fang Liu, Xu Liu, Wenping Ma, Yuwei Guo, Shuyuan Yang*<br>
arXiv preprintm, 1 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.01220)]

**Segment Any 4D Gaussians**<br>
*Shengxiang Ji, Guanjun Wu, Jiemin Fang, Jiazhong Cen, Taoran Yi, Wenyu Liu, Qi Tian, Xinggang Wang*<br>
arXiv preprint, 5 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.04504)] [[Project](https://jsxzs.github.io/sa4d/)]

**Click-Gaussian: Interactive Segmentation to Any 3D Gaussians**<br>
*Seokhun Choi, Hyeonseop Song, Jaechul Kim, Taehyeong Kim, Hoseok Do*<br>
ECCV 2024, 16 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.11793)] [[Project](https://seokhunchoi.github.io/Click-Gaussian/)]

:fire:**FlashSplat: 2D to 3D Gaussian Splatting Segmentation Solved Optimally**<br>
*Qiuhong Shen, Xingyi Yang, Xinchao Wang*<br>
ECCV 2024, 12 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.08270)] [[Code](https://github.com/florinshen/FlashSplat)]

**PLGS: Robust Panoptic Lifting with 3D Gaussian Splatting**<br>
*Yu Wang, Xiaobao Wei, Ming Lu, Guoliang Kang*<br>
arXiv preprint, 23 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.17505)]

**GaussianCut: Interactive segmentation via graph cut for 3D Gaussian Splatting**<br>
*Umangi Jain, Ashkan Mirzaei, Igor Gilitschenski*<br>
arXiv preprint, 12 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.07555)]

## 3DGS + Specular

**Spec-Gaussian: Anisotropic View-Dependent Appearance for 3D Gaussian Splatting**<br>
*Ziyi Yang, Xinyu Gao, Yangtian Sun, Yihua Huang, Xiaoyang Lyu, Wen Zhou, Shaohui Jiao, Xiaojuan Qi, Xiaogang Jin*<br>
arXiv preprint, 24 Feb 2024<br>
[[arXiv](https://arxiv.org/abs/2402.15870)]


## 3DGS Based SLAM

:fire:**SplaTAM: Splat, Track & Map 3D Gaussians for Dense RGB-D SLAM**<br>
*Nikhil Keetha, Jay Karhade, Krishna Murthy Jatavallabhula, Gengshan Yang, Sebastian Scherer, Deva Ramanan, Jonathon Luiten*<br>
CVPR 2024, 4 Dec 2023<br>
[[arXiv](https://arxiv.org/abs/2312.02126)] [[Project](https://spla-tam.github.io/)] [[Code])(https://github.com/spla-tam/SplaTAM)] [[Video](https://youtu.be/jWLI-OFp3qU)]

**LIV-GaussMap: LiDAR-Inertial-Visual Fusion for Real-time 3D Radiance Field Map Rendering**<br>
*Sheng Hong, Junjie He, Xinhu Zheng, Hesheng Wang, Hao Fang, Kangcheng Liu, Chunran Zheng, Shaojie Shen*<br>
arXiv preprint, 26 Jan 2024<br>
[[arXiv](https://arxiv.org/abs/2401.14857)]

**SGS-SLAM: Semantic Gaussian Splatting For Neural Dense SLAM**<br>
*Mingrui Li, Shuhong Liu, Heng Zhou*<br>
arXiv preprint, 5 Feb 2024<br>
[[arXiv](https://arxiv.org/abs/2402.03246)]

**MoD-SLAM: Monocular Dense Mapping for Unbounded 3D Scene Reconstruction**<br>
*Heng Zhou, Zhetao Guo, Shuhong Liu, Lechen Zhang, Qihao Wang, Yuxiang Ren, Mingrui Li*<br>
arXiv preprint, 6 Feb 2024<br>
[[arXiv](https://arxiv.org/abs/2402.03762)]

**SemGauss-SLAM: Dense Semantic Gaussian Splatting SLAM**<br>
*Siting Zhu, Renjie Qin, Guangming Wang, Jiuming Liu, Hesheng Wang*<br>
arXiv preprint, 13 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.07494)]

**RGBD GS-ICP SLAM**<br>
*Seongbo Ha, Jiung Yeon, Hyeonwoo Yu*<br>
arXiv preprint, 19 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.12550)]

**NEDS-SLAM: A Novel Neural Explicit Dense Semantic SLAM Framework using 3D Gaussian Splatting**<br>
*Yiming Ji, Yang Liu, Guanghu Xie, Boyu Ma, Zongwu Xie*<br>
arXiv preprint, 18 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.11679)]

**CG-SLAM: Efficient Dense RGB-D SLAM in a Consistent Uncertainty-aware 3D Gaussian Field**<br>
*Jiarui Hu, Xianhao Chen, Boyin Feng, Guanglin Li, Liangjing Yang, Hujun Bao, Guofeng Zhang, Zhaopeng Cui*<br>
arXiv preprint, 24 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.16095)] [[Project](https://zju3dv.github.io/cg-slam/)] [[Code](https://github.com/hjr37/CG-SLAM)]

**RGBD GS-ICP SLAM**<br>
*Seongbo Ha, Jiung Yeon, Hyeonwoo Yu*<br>
arXiv preprint, 19 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.12550)]

**HGS-Mapping: Online Dense Mapping Using Hybrid Gaussian Representation in Urban Scenes**<br>
*Ke Wu, Kaizhao Zhang, Zhiwei Zhang, Shanshuai Yuan, Muer Tie, Julong Wei, Zijun Xu, Jieru Zhao, Zhongxue Gan, Wenchao Ding*<br>
arXiv preprint, 29 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.20159)]

**MM3DGS SLAM: Multi-modal 3D Gaussian Splatting for SLAM Using Vision, Depth, and Inertial Measurements**<br>
*Lisong C. Sun, Neel P. Bhatt, Jonathan C. Liu, Zhiwen Fan, Zhangyang Wang, Todd E. Humphreys, Ufuk Topcu*<br>
arXiv preprint, 1 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.00923)] [[Project](https://vita-group.github.io/MM3DGS-SLAM/)] [[Video](https://www.youtube.com/watch?v=drf6UxehChE&feature=youtu.be)]

**Gaussian-LIC: Photo-realistic LiDAR-Inertial-Camera SLAM with 3D Gaussian Splatting**<br>
*Xiaolei Lang, Laijian Li, Hang Zhang, Feng Xiong, Mu Xu, Yong Liu, Xingxing Zuo, Jiajun Lv*<br>
IROS 2024, 10 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.06926)]

**RTG-SLAM: Real-time 3D Reconstruction at Scale using Gaussian Splatting**<br>
*Zhexi Peng, Tianjia Shao, Yong Liu, Jingke Zhou, Yin Yang, Jingdong Wang, Kun Zhou*<br>
arXiv preprint, 30 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.19706)]

**MGS-SLAM: Monocular Sparse Tracking and Gaussian Mapping with Depth Smooth Regularization**<br>
*Pengcheng Zhu, Yaoming Zhuang, Baoquan Chen, Li Li, Chengdong Wu, Zhanlin Liu*<br>
arXiv preprint, 10 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.06241)]

**NGM-SLAM: Gaussian Splatting SLAM with Radiance Field Submap**<br>
*Mingrui Li, Jingwei Huang, Lei Sun, Aaron Xuxiang Tian, Tianchen Deng, Hongyu Wang*<br>
arXiv preprint, 9 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.05702)]

**GS-Planner: A Gaussian-Splatting-based Planning Framework for Active High-Fidelity Reconstruction**<br>
*Rui Jin, Yuman Gao, Haojian Lu, Fei Gao*<br>
arXiv preprint, 16 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.10142)]

**GaussNav: Gaussian Splatting for Visual Navigation**<br>
*Xiaohan Lei, Min Wang, Wengang Zhou, Houqiang Li*<br>
arXiv preprint, 18 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.11625)]

**Splat-SLAM: Globally Optimized RGB-only SLAM with 3D Gaussians**<br>
*Erik Sandström, Keisuke Tateno, Michael Oechsle, Michael Niemeyer, Luc Van Gool, Martin R. Oswald, Federico Tombari*<br>
arXiv preprint, 26 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.16544)] [[Code](https://github.com/eriksandstroem/Splat-SLAM)]

**Structure Gaussian SLAM with Manhattan World Hypothesis**<br>
*Shuhong Liu, Heng Zhou, Liuzhuozheng Li, Yun Liu, Tianchen Deng, Yiming Zhou, Mingrui Li*<br>
arXiv preprint, 30 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.20031)]

**From Perfect to Noisy World Simulation: Customizable Embodied Multi-modal Perturbations for SLAM Robustness Benchmarking**<br>
*Xiaohao Xu, Tianyi Zhang, Sibo Wang, Xiang Li, Yongqi Chen, Ye Li, Bhiksha Raj, Matthew Johnson-Roberson, Xiaonan Huang*<br>
arXiv preprint, 24 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.16850)]

**I^2-SLAM: Inverting Imaging Process for Robust Photorealistic Dense SLAM**<br>
*Gwangtak Bae, Changwoon Choi, Hyeongjun Heo, Sang Min Kim, Young Min Kim*<br>
ECCV 2024, 16 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.11347)]

**Evaluating Modern Approaches in 3D Scene Reconstruction: NeRF vs Gaussian-Based Methods**<br>
*Yiming Zhou, Zixuan Zeng, Andi Chen, Xiaofan Zhou, Haowei Ni, Shiyao Zhang, Panfeng Li, Liangxi Liu, Mengyao Zheng, Xupeng Chen*<br>
2024 6th International Conference on Data-driven Optimization of Complex Systems, 8 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.04268)]

**Visual SLAM with 3D Gaussian Primitives and Depth Priors Enabling Novel View Synthesis**<br>
*Zhongche Qu, Zhi Zhang, Cong Liu, Jianhua Yin*<br>
arXiv preprint, 10 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.05635)]

**Towards Real-Time Gaussian Splatting: Accelerating 3DGS through Photometric SLAM**<br>
*Yan Song Hu, Dayou Mao, Yuhao Chen, John Zelek*<br>
arXiv preprint, 7 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.03825)]

**IG-SLAM: Instant Gaussian SLAM**<br>
*F. Aykut Sarikamis, A. Aydin Alatan*<br>
arXiv preprint, 2 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.01126)]


**MotionGS : Compact Gaussian Splatting SLAM by Motion Filter**<br>
*Xinli Guo, Peng Han, Weidong Zhang, Hongtian Chen*<br>
arXiv preprint, 18 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.11129)]

**GSFusion: Online RGB-D Mapping Where Gaussian Splatting Meets TSDF Fusion**<br>
*Jiaxin Wei, Stefan Leutenegger*<br>
arXiv preprint, 22 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.12677)] [[Code](https://github.com/GS-Fusion/GSFusion)]

**LoopSplat: Loop Closure by Registering 3D Gaussian Splats**<br>
*Liyuan Zhu, Yue Li, Erik Sandström, Shengyu Huang, Konrad Schindler, Iro Armeni*<br>
3DV 2025, 19 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.10154)] [[Project](https://loopsplat.github.io/)] [[Code](https://github.com/GradientSpaces/LoopSplat)]

**OG-Mapping: Octree-based Structured 3DGaussians for Online Dense Mapping**<br>
*Meng Wang, Junyi Wang, Changqun Xia, Chen Wang, Yue Qi*<br>
arXiv preprint, 30 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.17223)]

**FAST-LIVO2: Fast, Direct LiDAR-Inertial-Visual Odometry**<br>
*Chunran Zheng, Wei Xu, Zuhao Zou, Tong Hua, Chongjian Yuan, Dongjiao He, Bingyang Zhou, Zheng Liu, Jiarong Lin, Fangcheng Zhu, Yunfan Ren, Rong Wang, Fanle Meng, Fu Zhang*<br>
arXiv preprint, 26 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.14035)]

**Hi-SLAM: Scaling-up Semantics in SLAM with a Hierarchically Categorical Gaussian Splatting**<br>
*Boying Li, Zhixi Cai, Yuan-Fang Li, Ian Reid, Hamid Rezatofighi*<br>
arXiv preprint, 19 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.12518)]

**GLC-SLAM: Gaussian Splatting SLAM with Efficient Loop Closure**<br>
*Ziheng Xu, Qingfeng Li, Chen Chen, Xuefeng Liu, Jianwei Niu*<br>
arXiv preprint, 17 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.10982)]

**Go-SLAM: Grounded Object Segmentation and Localization with Gaussian Splatting SLAM**<br>
*Phu Pham, Dipam Patel, Damon Conover, Aniket Bera*<br>
arXiv preprint, 26 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.16944)]

**CaRtGS: Computational Alignment for Real-Time Gaussian Splatting SLAM**<br>
*Dapeng Feng, Zhiqiang Chen, Yizhen Yin, Shipeng Zhong, Yuhua Qi, Hongbo Chen*<br>
arXiv preprint, 1 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.00486)]

**Robust Gaussian Splatting SLAM by Leveraging Loop Closure**<br>
*Zunjie Zhu, Youxu Fang, Xin Li, Chengang Yan, Feng Xu, Chau Yuen, Yanyan Li*<br>
arXiv preprint, 30 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.20111)]

**ES-Gaussian: Gaussian Splatting Mapping via Error Space-Based Gaussian Completion**<br>
*Lu Chen, Yingfu Zeng, Haoang Li, Zhitao Deng, Jiafu Yan, Zhenjun Zhao*<br>
arXiv preprint, 9 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.06613)] [[Project](https://chenlu-china.github.io/ES-Gaussian/)]

**GSLoc: Visual Localization with 3D Gaussian Splatting**<br>
*Kazii Botashev, Vladislav Pyatov, Gonzalo Ferrer, Stamatios Lefkimmiatis*<br>
arXiv preprint, 8 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.06165)]

**LoGS: Visual Localization via Gaussian Splatting with Fewer Training Images**<br>
*Yuzhou Cheng, Jianhao Jiao, Yue Wang, Dimitrios Kanoulas*<br>
arXiv preprint, 15 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.11505)]

**GSORB-SLAM: Gaussian Splatting SLAM benefits from ORB features and Transmittance information**<br>
*Wancai Zheng, Xinyi Yu, Jintao Rong, Linlin Ou, Yan Wei, Libo Zhou*<br>
arXiv preprint, 15 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.11356)]

**AG-SLAM: Active Gaussian Splatting SLAM**<br>
*Wen Jiang, Boshu Lei, Katrina Ashton, Kostas Daniilidis*<br>
arXiv preprint, 22 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.17422)]

**XRDSLAM: A Flexible and Modular Framework for Deep Learning based SLAM**<br>
*Xiaomeng Wang, Nan Wang, Guofeng Zhang*<br>
arXiv preprint, 31 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.23690)]

**LVI-GS: Tightly-coupled LiDAR-Visual-Inertial SLAM using 3D Gaussian Splatting**<br>
*Huibin Zhao, Weipeng Guan, Peng Lu*<br>
arXiv preprint, 5 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.02703)]

**DG-SLAM: Robust Dynamic Gaussian Splatting SLAM with Hybrid Pose Optimization**<br>
*Yueming Xu, Haochen Jiang, Zhongyang Xiao, Jianfeng Feng, Li Zhang*<br>
arXiv preprint, 13 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.08373)]

**MBA-SLAM: Motion Blur Aware Dense Visual SLAM with Radiance Fields Representation**<br>
*Peng Wang, Lingzhe Zhao, Yin Zhang, Shiyu Zhao, Peidong Liu*<br>
arXiv preprint, 13 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.08279)] [[Code](https://github.com/WU-CVGL/MBA-SLAM)]

**LiV-GS: LiDAR-Vision Integration for 3D Gaussian Splatting SLAM in Outdoor Environments**<br>
*Renxiang Xiao, Wei Liu, Yushuai Chen, Liang Hu*<br>
19 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.12185)]

**DGS-SLAM: Gaussian Splatting SLAM in Dynamic Environment**<br>
*Mangyu Kong, Jaewon Lee, Seongwon Lee, Euntai Kim*<br>
16 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.10722)]


## 3DGS Based 3D Point Tracking

**DynOMo: Online Point Tracking by Dynamic Online Monocular Gaussian Reconstruction**<br>
*Jenny Seidenschwarz, Qunjie Zhou, Bardienus Duisterhof, Deva Ramanan, Laura Leal-Taixé*<br>
arXiv preprint, 3 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.02104)]

## 3DGS Based Inverse Rendering

**GIR: 3D Gaussian Inverse Rendering for Relightable Scene Factorization**<br>
*Yahao Shi, Yanmin Wu, Chenming Wu, Xing Liu, Chen Zhao, Haocheng Feng, Jingtuo Liu, Liangjun Zhang, Jian Zhang, Bin Zhou, Errui Ding, Jingdong Wang*<br>
arXiv preprint, 8 Dec, 2023<br>
[[arXiv](https://arxiv.org/abs/2312.05133)] [[Project](https://3dgir.github.io/)]

**DeferredGS: Decoupled and Editable Gaussian Splatting with Deferred Shading**<br>
*Tong Wu, Jia-Mu Sun, Yu-Kun Lai, Yuewen Ma, Leif Kobbelt, Lin Gao*<br>
arXiv preprint, 15 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.09412)]

**Progressive Radiance Distillation for Inverse Rendering with Gaussian Splatting**<br>
*Keyang Ye, Qiming Hou, Kun Zhou*<br>
arXiv preprint, 14 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.07595)]

**GS-ID: Illumination Decomposition on Gaussian Splatting via Diffusion Prior and Parametric Light Source Optimization**<br>
*Kang Du, Zhihao Liang, Zeyu Wang*<br>
arXiv preprint, 16 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.08524)]

**Phys3DGS: Physically-based 3D Gaussian Splatting for Inverse Rendering**<br>
*Euntae Choi, Sungjoo Yoo*<br>
arXiv preprint, 16 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.10335)]

:fire: **Flash-Splat: 3D Reflection Removal with Flash Cues and Gaussian Splats**<br>
*Mingyang Xie, Haoming Cai, Sachin Shah, Yiran Xu, Brandon Y. Feng, Jia-Bin Huang, Christopher A. Metzler*<br>
arXiv preprint, 3 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.02764)] [[Project](https://flash-splat.github.io/)] [[Code](https://github.com/mingyangx/flash-splat)]

**GI-GS: Global Illumination Decomposition on Gaussian Splatting for Inverse Rendering**<br>
*Hongze Chen, Zehong Lin, Jun Zhang*<br>
arXiv preprint, 3 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.02619)]

**RelitLRM: Generative Relightable Radiance for Large Reconstruction Models**<br>
*Tianyuan Zhang, Zhengfei Kuang, Haian Jin, Zexiang Xu, Sai Bi, Hao Tan, He Zhang, Yiwei Hu, Milos Hasan, William T. Freeman, Kai Zhang, Fujun Luan*<br>
arXiv preprint, 8 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.06231)] [[Project](https://relit-lrm.github.io/)]

**GS^3: Efficient Relighting with Triple Gaussian Splatting**<br>
*Zoubin Bi, Yixin Zeng, Chong Zeng, Fan Pei, Xiang Feng, Kun Zhou, Hongzhi Wu*<br>
SIGGRAPH Asia 2024, 15 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.11419)] [[Project](https://gsrelight.github.io/)] [[Code](https://github.com/gsrelight/gs-relight)]

**Triplet: Triangle Patchlet for Mesh-Based Inverse Rendering and Scene Parameters Approximation**<br>
*Jiajie Yang*<br>
arXiv preprint, 16 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.12414)]

**GlossyGS: Inverse Rendering of Glossy Objects with 3D Gaussian Splatting**<br>
*Shuichang Lai, Letian Huang, Jie Guo, Kai Cheng, Bowen Pan, Xiaoxiao Long, Jiangjing Lyu, Chengfei Lv, Yanwen Guo*<br>
arXiv preprint, 17 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.13349)]

**SpectroMotion: Dynamic 3D Reconstruction of Specular Scenes**<br>
*Cheng-De Fan, Chen-Wei Chang, Yi-Ruei Liu, Jie-Ying Lee, Jiun-Long Huang, Yu-Chee Tseng, Yu-Lun Liu*<br>
arXiv preprint, 22 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.17249)] [[Project](https://cdfan0627.github.io/spectromotion/)]

**GeoSplatting: Towards Geometry Guided Gaussian Splatting for Physically-based Inverse Rendering**<br>
*Kai Ye, Chong Gao, Guanbin Li, Wenzheng Chen, Baoquan Chen*<br>
arXiv preprint, 31 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.24204)] [[Project](https://pku-vcl-geometry.github.io/GeoSplatting/)]

**Scaled Inverse Graphics: Efficiently Learning Large Sets of 3D Scenes**<br>
*Karim Kassab, Antoine Schnepf, Jean-Yves Franceschi, Laurent Caraffa, Flavian Vasile, Jeremie Mary, Andrew Comport, Valérie Gouet-Brunet*<br>
arXiv preprint, 31 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.23742)] [[Project](https://scaled-ig.github.io/)]

**GUS-IR: Gaussian Splatting with Unified Shading for Inverse Rendering**<br>
*Zhihao Liang, Hongdong Li, Kui Jia, Kailing Guo, Qi Zhang*<br>
arXiv preprint, 12 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.07478)]

## 3DGS Imaging Tasks

**Deblurring 3D Gaussian Splatting**<br>
*Byeonghyeon Lee, Howoong Lee, Xiangyu Sun, Usman Ali, Eunbyung Park*<br>
arXiv preprint, 1 Jan 2024<br>
[[arXiv](https://arxiv.org/abs/2401.00834)] [[Project](https://benhenryl.github.io/Deblurring-3D-Gaussian-Splatting/)] [[Code](https://github.com/benhenryL/Deblurring-3D-Gaussian-Splatting)]

**BAD-Gaussians: Bundle Adjusted Deblur Gaussian Splatting**<br>
*Lingzhe Zhao, Peng Wang, Peidong Liu*<br>
arXiv preprint, 18 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.11831)] [[Project](https://lingzhezhao.github.io/BAD-Gaussians/)] [[Code](https://github.com/WU-CVGL/BAD-Gaussians)]

**Gaussian Splatting on the Move: Blur and Rolling Shutter Compensation for Natural Camera Motion**<br>
*Otto Seiskari, Jerry Ylilammi, Valtteri Kaatrasalo, Pekka Rantalankila, Matias Turkulainen, Juho Kannala, Esa Rahtu, Arno Solin*<br>
arXiv preprint, 20 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.13327)] [[Code](https://github.com/SpectacularAI/3dgs-deblur)]

**BAGS: Blur Agnostic Gaussian Splatting through Multi-Scale Kernel Modeling**<br>
*Cheng Peng, Yutao Tang, Yifan Zhou, Nengyu Wang, Xijun Liu, Deming Li, Rama Chellappa*<br>
arXiv preprint, 7 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.04926)]

**From Chaos to Clarity: 3DGS in the Dark**<br>
*Zhihao Li, Yufei Wang, Alex Kot, Bihan Wen*<br>
arXiv preprint, 12 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.08300)]

**Cinematic Gaussians: Real-Time HDR Radiance Fields with Depth of Field**<br>
*Chao Wang, Krzysztof Wolski, Bernhard Kerbl, Ana Serrano, Mojtaba Bemana, Hans-Peter Seidel, Karol Myszkowski, Thomas Leimkühler*<br>
arXiv preprint, 11 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.07329)]

**Lighting Every Darkness with 3DGS: Fast Training and Real-Time Rendering for HDR View Synthesis**<br>
*Xin Jin, Pengyi Jiao, Zheng-Peng Duan, Xingchao Yang, Chun-Le Guo, Bo Ren, Chongyi Li*<br>
arXiv preprint, 10 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.06216)] [[Code](https://github.com/Srameo/LE3D)]

**CRiM-GS: Continuous Rigid Motion-Aware Gaussian Splatting from Motion Blur Images**<br>
*Junghe Lee, Donghyeong Kim, Dogyoon Lee, Suhwan Cho, Sangyoun Lee*<br>
arXiv preprint, 4 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.03923)] [[Project](https://jho-yonsei.github.io/CRiM-Gaussian/)]

**HDRSplat: Gaussian Splatting for High Dynamic Range 3D Scene Reconstruction from Raw Images**<br>
*Shreyas Singh, Aryan Garg, Kaushik Mitra*<br>
arXiv preprint, 23 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.16503)]

**EaDeblur-GS: Event assisted 3D Deblur Reconstruction with Gaussian Splatting**<br>
*Yuchen Weng, Zhengwen Shen, Ruofan Chen, Qi Wang, Jun Wang*<br>
arXiv preprint, 18 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.13520)]

**HDRGS: High Dynamic Range Gaussian Splatting**<br>
*Jiahao Wu, Lu Xiao, Chao Wang, Rui Peng, Kaiqiang Xiong, Ronggang Wang*<br>
arXiv preprint, 13 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.06543)]

**DeRainGS: Gaussian Splatting for Enhanced Scene Reconstruction in Rainy Environments**<br>
*Shuhong Liu, Xiang Chen, Hongming Chen, Quanfeng Xu, Mingrui Li*<br>
arXiv preprint, 21 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.11540)]

**Gaussian in the Dark: Real-Time View Synthesis From Inconsistent Dark Images Using Gaussian Splatting**<br>
*Sheng Ye, Zhen-Hui Dong, Yubin Hu, Yu-Hui Wen, Yong-Jin Liu*<br>
PG 2024, 17 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.09130)]

**GS-Blur: A 3D Scene-Based Dataset for Realistic Image Deblurring**<br>
*Dongwoo Lee, Joonkyu Park, Kyoung Mu Lee*<br>
NeurIPS 2024, 31 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.23658)]

## 3DGS for Reflective and Transparent Objects

**Snap-it, Tap-it, Splat-it: Tactile-Informed 3D Gaussian Splatting for Reconstructing Challenging Surfaces**<br>
*Mauro Comi, Alessio Tonioni, Max Yang, Jonathan Tremblay, Valts Blukis, Yijiong Lin, Nathan F. Lepora, Laurence Aitchison*<br>
arXiv preprint, 29 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.20275)]

**Mirror-3DGS: Incorporating Mirror Reflections into 3D Gaussian Splatting**<br>
*Jiarui Meng, Haijie Li, Yanmin Wu, Qiankun Gao, Shuzhou Yang, Jian Zhang, Siwei Ma*<br>
arXiv preprint, 1 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.01168)]

**RainyScape: Unsupervised Rainy Scene Reconstruction using Decoupled Neural Rendering**<br>
*Xianqiang Lyu, Hui Liu, Junhui Hou*<br>
arXiv preprint, 17 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.11401)]

**DeblurGS: Gaussian Splatting for Camera Motion Blur**<br>
*Jeongtaek Oh, Jaeyoung Chung, Dongwoo Lee, Kyoung Mu Lee*<br>
arXiv preprint, 17 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.11358)]

**3D Gaussian Splatting with Deferred Reflection**<br>
*Keyang Ye, Qiming Hou, Kun Zhou*<br>
arXiv preprint, 29 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.18454)]

**MirrorGaussian: Reflecting 3D Gaussians for Reconstructing Mirror Reflections**<br>
*Jiayue Liu, Xiao Tang, Freeman Cheng, Roy Yang, Zhihao Li, Jianzhuang Liu, Yi Huang, Jiaqi Lin, Shiyong Liu, Xiaofei Wu, Songcen Xu, Chun Yuan*<br>
arXiv preprint, 20 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.11921)] [[Project](https://mirror-gaussian.github.io/)]

**DC-Gaussian: Improving 3D Gaussian Splatting for Reflective Dash Cam Videos**<br>
*Linhan Wang, Kai Cheng, Shuo Lei, Shengkun Wang, Wei Yin, Chenyang Lei, Xiaoxiao Long, Chang-Tien Lu*<br>
arXiv preprint, 27 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.17705)] [[Project](https://linhanwang.github.io/dcgaussian/)] [[Code](https://github.com/linhanwang/DC-Gaussian)]

**RefGaussian: Disentangling Reflections from 3D Gaussian Splatting for Realistic Rendering**<br>
*Rui Zhang, Tianyue Luo, Weidong Yang, Ben Fei, Jingyi Xu, Qingyuan Zhou, Keyi Liu, Ying He*<br>
arXiv preprint, 9 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.05852)]

**Gaussian Splatting in Mirrors: Reflection-Aware Rendering via Virtual Camera Optimization**<br>
*Zihan Wang, Shuzhe Wang, Matias Turkulainen, Junyuan Fang, Juho Kannala*<br>
arXiv preprint, 2 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.01614)]

**Efficient Perspective-Correct 3D Gaussian Splatting Using Hybrid Transparency**<br>
*Florian Hahlbohm, Fabian Friederichs, Tim Weyrich, Linus Franke, Moritz Kappel, Susana Castillo, Marc Stamminger, Martin Eisemann, Marcus Magnor*<br>
arXiv preprint, 10 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.08129)] [[Project](https://fhahlbohm.github.io/htgs/)]

## 3DGS Superresolution

**SRGS: Super-Resolution 3D Gaussian Splatting**<br>
*Xiang Feng, Yongbo He, Yubo Wang, Yan Yang, Zhenzhong Kuang, Yu Jun, Jianping Fan, Jiajun ding*<br>
ACM MM 2024, 16 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.10318)]

**GaussianSR: 3D Gaussian Super-Resolution with 2D Diffusion Priors**<br>
*Xiqian Yu, Hanxin Zhu, Tianyu He, Zhibo Chen*<br>
arXiv preprint, 14 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.10111)] [[Project](https://chchnii.github.io/GaussianSR/)]

**GaussianSR: High Fidelity 2D Gaussian Splatting for Arbitrary-Scale Image Super-Resolution**<br>
*Jintong Hu, Bin Xia, Bin Chen, Wenming Yang, Lei Zhang*<br>
arXiv preprint, 25 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.18046)]

**SuperGS: Super-Resolution 3D Gaussian Splatting via Latent Feature Field and Gradient-guided Splitting**<br>
*Shiyun Xie, Zhiru Wang, Yinghao Zhu, Chengwei Pan*<br>
arXiv preprint, 3 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.02571)]

## 3DGS for Point Cloud

**Zero-shot Point Cloud Completion Via 2D Priors**<br>
*Tianxin Huang, Zhiwen Yan, Yuyang Zhao, Gim Hee Lee*<br>
arXiv preprint, 10 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.06814)]

**Photorealistic 3D Urban Scene Reconstruction and Point Cloud Extraction using Google Earth Imagery and Gaussian Splatting**<br>
*Kyle Gao, Dening Lu, Hongjie He, Linlin Xu, Jonathan Li*<br>
arXiv preprint, 17 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.11021)]

**PFGS: High Fidelity Point Cloud Rendering via Feature Splatting**<br>
*Jiaxu Wang, Ziyi Zhang, Junhao He, Renjing Xu*<br>
arXiv preprint, 4 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.03857)]

## 3DGS for CV Tasks

**3DGS-Calib: 3D Gaussian Splatting for Multimodal SpatioTemporal Calibration**<br>
*Quentin Herau, Moussab Bennehar, Arthur Moreau, Nathan Piasco, Luis Roldao, Dzmitry Tsishkou, Cyrille Migniot, Pascal Vasseur, Cédric Demonceaux*<br>
arXiv preprint, 18 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.11577)]

**GaussReg: Fast 3D Registration with Gaussian Splatting**<br>
*Jiahao Chang, Yinglin Xu, Yihao Li, Yuantao Chen, Xiaoguang Han*<br>
ECCV 2024, 7 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.05254)]

## 3DGS with Hardware

**Dual-Camera Smooth Zoom on Mobile Phones**<br>
*Renlong Wu, Zhilu Zhang, Yu Yang, Wangmeng Zuo*<br>
arXiv preprint, 7 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.04908)]

**Event3DGS: Event-based 3D Gaussian Splatting for Fast Egomotion**<br> 
*Tianyi Xiong, Jiayi Wu, Botao He, Cornelia Fermuller, Yiannis Aloimonos, Heng Huang, Christopher A. Metzler*<br>
arXiv preprint, 5 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.02972)]

**E2GS: Event Enhanced Gaussian Splatting**<br>
*Hiroyuki Deguchi, Mana Masuda, Takuya Nakabayashi, Hideo Saito*<br>
arXiv preprint, 21 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.14978)] 


**SpikeGS: Reconstruct 3D scene via fast-moving bio-inspired sensors**<br>
*Yijia Guo, Liwen Hu, Lei Ma, Tiejun Huang*<br>
arXiv preprint, 4 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.03771)]

**SpikeGS: 3D Gaussian Splatting from Spike Streams with High-Speed Camera Motion**<br>
*Jiyuan Zhang, Kang Chen, Shiyan Chen, Yajing Zheng, Tiejun Huang, Zhaofei Yu*<br>
arXiv preprint, 14 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.10062)]

**Ev-GS: Event-based Gaussian splatting for Efficient and Accurate Radiance Field Rendering**<br>
*Jingqian Wu, Shuo Zhu, Chutian Wang, Edmund Y. Lam*<br>
arXiv preprint, 16 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.11343)]

**IncEventGS: Pose-Free Gaussian Splatting from a Single Event Camera**<br>
*Jian Huang, Chengrui Dong, Peidong Liu*<br>
arXiv preprint, 10 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.08107)] [[Code](https://github.com/wu-cvgl/IncEventGS)]

**EF-3DGS: Event-Aided Free-Trajectory 3D Gaussian Splatting**<br>
*Bohao Liao, Wei Zhai, Zengyu Wan, Tianzhu Zhang, Yang Cao, Zheng-Jun Zha*<br>
arXiv preprint, 20 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.15392)] [[Project](https://lbh666.github.io/ef-3dgs/)]

## 3DGS Applications

### 3DGS Application in Animal Reconstruction

**Exploring the Feasibility of Generating Realistic 3D Models of Endangered Species Using DreamGaussian: An Analysis of Elevation Angle's Impact on Model Generation**<br>
*Selcuk Anil Karatopak, Deniz Sen*<br>
arXiv preprint, 15 Dec 2023<br>
[[arXiv](https://arxiv.org/abs/2312.09682)]


### 3DGS Application in Medical Imaging

**EndoGaussian: Gaussian Splatting for Deformable Surgical Scene Reconstruction**<br>
*Yifan Liu, Chenxin Li, Chen Yang, Yixuan Yuan*<br>
arXiv preprint, 23 Jan 2024<br>
[[arXiv](https://arxiv.org/abs/2401.12561/)] [[Project](https://yifliu3.github.io/EndoGaussian/)] [[Code](https://github.com/yifliu3/EndoGaussian)]

**Deformable Endoscopic Tissues Reconstruction with Gaussian Splatting**<br>
*Lingting Zhu, Zhao Wang, Zhenchao Jin, Guying Lin, Lequan Yu*<br>
arXiv preprint, 21 Jan 2024<br>
[[arXiv](https://arxiv.org/abs/2401.11535)] [[Code](https://github.com/HKU-MedAI/EndoGS)]

**Endo-4DGS: Distilling Depth Ranking for Endoscopic Monocular Scene Reconstruction with 4D Gaussian Splatting**<br>
*Yiming Huang, Beilei Cui, Long Bai, Ziqi Guo, Mengya Xu, Hongliang Ren*<br>
arXiv preprint, 29 Jan 2024<br>
[[arXiv](https://arxiv.org/abs/2401.16416)]

**Radiative Gaussian Splatting for Efficient X-ray Novel View Synthesis**<br>
*Yuanhao Cai, Yixun Liang, Jiahao Wang, Angtian Wang, Yulun Zhang, Xiaokang Yang, Zongwei Zhou, Alan Yuille*<br>
arXiv preprint, 7 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.04116)] [[Video](https://www.youtube.com/watch?v=gDVf_Ngeghg)]

**TOGS: Gaussian Splatting with Temporal Opacity Offset for Real-Time 4D DSA Rendering**<br>
*Shuai Zhang, Huangxuan Zhao, Zhenghong Zhou, Guanjun Wu, Chuansheng Zheng, Xinggang Wang, Wenyu Liu*<br>
arXiv preprint, 28 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.19586)]

**Gaussian Pancakes: Geometrically-Regularized 3D Gaussian Splatting for Realistic Endoscopic Reconstruction**<br>
*Sierra Bonilla, Shuai Zhang, Dimitrios Psychogyios, Danail Stoyanov, Francisco Vasconcelos, Sophia Bano*<br>
arXiv preprint, 9 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.06128)]

**Novel View Synthesis for Cinematic Anatomy on Mobile and Immersive Displays**<br>
*Simon Niedermayr, Christoph Neuhauser, Kaloian Petkov, Klaus Engel, Rüdiger Westermann*<br>
arXiv preprint, 17 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.11285)]

**HFGS: 4D Gaussian Splatting with Emphasis on Spatial and Temporal High-Frequency Components for Endoscopic Scene Reconstruction**<br>
*Haoyu Zhao, Xingyue Zhao, Lingting Zhu, Weixi Zheng, Yongchao Xu*<br>
arXiv preprint, 28 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.17872)]

**Deform3DGS: Flexible Deformation for Fast Surgical Scene Reconstruction with Gaussian Splatting**<br>
*Shuojue Yang, Qian Li, Daiyun Shen, Bingchen Gong, Qi Dou, Yueming Jin*<br>
arXiv preprint, 28 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.17835)] [[Code](https://github.com/jinlab-imvr/Deform3DGS)]

**R^2-Gaussian: Rectifying Radiative Gaussian Splatting for Tomographic Reconstruction**<br>
*Ruyi Zha, Tao Jun Lin, Yuanhao Cai, Jiwen Cao, Yanhao Zhang, Hongdong Li*<br>
arXiv preprint, 31 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.20693)]

**DDGS-CT: Direction-Disentangled Gaussian Splatting for Realistic Volume Rendering**<br>
*Zhongpai Gao, Benjamin Planche, Meng Zheng, Xiao Chen, Terrence Chen, Ziyan Wu*<br>
arXiv preprint, 4 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.02518)]

**Gaussian Representation for Deformable Image Registration**<br>
*Jihe Li, Fabian Zhang, Xia Li, Tianhao Zhang, Ye Zhang, Joachim Buhmann*<br>
arXiv preprint, 5 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.03394)]

**LGS: A Light-weight 4D Gaussian Splatting for Efficient Surgical Scene Reconstruction**<br>
*Hengyu Liu, Yifan Liu, Chenxin Li, Wuyang Li, Yixuan Yuan*<br>
MICCAI 2024, 23 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.16073)] [[Project](https://lgs-endo.github.io/)] [[Code](https://github.com/CUHK-AIM-Group/LGS)]


**Free-SurGS: SfM-Free 3D Gaussian Splatting for Surgical Scene Reconstruction**<br>
*Jiaxin Guo, Jiangliu Wang, Di Kang, Wenzhen Dong, Wenting Wang, Yun-hui Liu*<br>
MICCAI 2024, 3 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.02918)] [[Code](https://github.com/wrld/Free-SurGS)]

**EndoSparse: Real-Time Sparse View Synthesis of Endoscopic Scenes using Gaussian Splatting**<br>
*Chenxin Li, Brandon Y. Feng, Yifan Liu, Hengyu Liu, Cheng Wang, Weihao Yu, Yixuan Yuan*<br>
MICCAI 2024, 1 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.01029)] [[Project](https://endo-sparse.github.io/)]

**SurgicalGaussian: Deformable 3D Gaussians for High-Fidelity Surgical Scene Reconstruction**<br>
*Weixing Xie, Junfeng Yao, Xianpeng Cao, Qiqin Lin, Zerui Tang, Xiao Dong, Xiaohu Guo*<br>
arXiv preprint, 6 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.05023)] [[Project](https://surgicalgaussian.github.io/)] [[Video](https://youtu.be/oEfHfG6_Ous)] [[Code](https://github.com/SurgicalGaussian/SurgicalGaussian)]

**Realistic Surgical Image Dataset Generation Based On 3D Gaussian Splatting**<br>
*Tianle Zeng, Gerardo Loza Galindo, Junlei Hu, Pietro Valdastri, Dominic Jones*<br>
MICCAI 2024, 20 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.14846)]

**A Review of 3D Reconstruction Techniques for Deformable Tissues in Robotic Surgery**<br>
*Mengya Xu, Ziqi Guo, An Wang, Long Bai, Hongliang Ren*<br>
MICCAI 2024, 8 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.04426)] [[Code](https://github.com/Epsilon404/surgicalnerf)]

**Free-DyGS: Camera-Pose-Free Scene Reconstruction based on Gaussian Splatting for Dynamic Surgical Videos**<br>
*Qian Li, Shuojue Yang, Daiyun Shen, Yueming Jin*<br>
arXiv preprint, 2 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.01003)]

**Online 3D reconstruction and dense tracking in endoscopic videos**<br>
*Michel Hayoz, Christopher Hahne, Thomas Kurmann, Max Allan, Guido Beldi, Daniel Candinas, ablo Márquez-Neila, Raphael Sznitman*<br>
arXiv preprint, 9 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.06037)]

**Seamless Augmented Reality Integration in Arthroscopy: A Pipeline for Articular Reconstruction and Guidance**<br>
*Hongchao Shu, Mingxu Liu, Lalithkumar Seenivasan, Suxi Gu, Ping-Cheng Ku, Jonathan Knopf, Russell Taylor, Mathias Unberath*<br>
AE-CAI 2024, 1 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.00386)]

**Multi-Layer Gaussian Splatting for Immersive Anatomy Visualization**<br>
*Constantin Kleinbeck, Hannah Schieber, Klaus Engel, Ralf Gutjahr, Daniel Roth*<br>
arXiv preprint, 22 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.16978)]

**TomoGRAF: A Robust and Generalizable Reconstruction Network for Single-View Computed Tomography**<br>
*Di Xu, Yang Yang, Hengjie Liu, Qihui Lyu, Martina Descovich, Dan Ruan, Ke Sheng*<br>
arXiv preprint, 12 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.08158)]

**PR-ENDO: Physically Based Relightable Gaussian Splatting for Endoscopy**<br>
*Joanna Kaleta, Weronika Smolak-Dyżewska, Dawid Malarz, Diego Dall'Alba, Przemysław Korzeniowski, Przemysław Spurek*<br>
19 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.12510)]

### 3DGS Application in Underwater Scenario

**RecGS: Removing Water Caustic with Recurrent Gaussian Splatting**<br>
*Tianyi Zhang, Weiming Zhi, Kaining Huang, Joshua Mangelson, Corina Barbalata, Matthew Johnson-Roberson*<br>
arXiv preprint, 14 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.10318)]

**WaterSplatting: Fast Underwater 3D Scene Reconstruction Using Gaussian Splatting**<br>
*Huapeng Li, Wenxuan Song, Tianao Xu, Alexandre Elsig, Jonas Kulhanek*<br>
arXiv preprint, 15 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.08206)] [[Project](https://water-splatting.github.io/)] [[Code](https://github.com/water-splatting/water-splatting)]

**SeaSplat: Representing Underwater Scenes with 3D Gaussian Splatting and a Physically Grounded Image Formation Model**<br>
*Daniel Yang, John J. Leonard, Yogesh Girdhar*<br>
arXiv preprint, 25 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.17345)] [[Project](https://seasplat.github.io/)] [[Video](https://www.youtube.com/watch?v=iU9JWIhw5kg)]

**UW-GS: Distractor-Aware 3D Gaussian Splatting for Enhanced Underwater Scene Reconstruction**<br>
*Haoran Wang, Nantheera Anantrasirichai, Fan Zhang, David Bull*<br>
arXiv preprint, 2 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.01517)]

### 3DGS Application in Agriculture/Forestry Scenario

**Comparative Analysis of Novel View Synthesis and Photogrammetry for 3D Forest Stand Reconstruction and extraction of individual tree parameters**<br>
*Guoji Tian, Chongcheng Chen, Hongyu Huang*<br>
arXiv preprint, 8 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.05772)]

**Biomass phenotyping of oilseed rape through UAV multi-view oblique imaging with 3DGS and SAM model**<br>
*Yutao Shen, Hongyu Zhou, Xin Yang, Xuqi Lu, Ziyue Guo, Lixi Jiang, Yong He, Haiyan Cen*<br>
arXiv preprint, 13 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.08453)]

## 3DGS Artifact Detection

**SplatPose & Detect: Pose-Agnostic 3D Anomaly Detection**<br>
*Mathis Kruse, Marco Rudolph, Dominik Woiwode, Bodo Rosenhahn*<br>
CVPR 2024, 10 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.06832)]

**SplatPose+: Real-time Image-Based Pose-Agnostic 3D Anomaly Detection**<br>
*Yizhe Liu, Yan Song Hu, Yuhao Chen, John Zelek*<br>
arXiv preprint, 15 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.12080)]

**SplatOverflow: Asynchronous Hardware Troubleshooting**<br>
*Amritansh Kwatra, Tobias Wienberg, Ilan Mandel, Ritik Batra, Peter He, Francois Guimbretiere, Thijs Roumen*<br>
arXiv preprint, 4 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.02332)] [[Video](https://youtu.be/m4TKeBDuZkU)]

## 3DGS Copyright/Safety

**GaussianStego: A Generalizable Stenography Pipeline for Generative 3D Gaussians Splatting**<br>
*Chenxin Li, Hengyu Liu, Zhiwen Fan, Wuyang Li, Yifan Liu, Panwang Pan, Yixuan Yuan*<br>
arXiv preprint, 1 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.01301)] [[Project](https://gaussian-stego.github.io/)]


**Poison-splat: Computation Cost Attack on 3D Gaussian Splatting**<br>
*Jiahao Lu, Yifan Zhang, Qiuhong Shen, Xinchao Wang, Shuicheng Yan*<br>
arXiv preprint, 10 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.08190)]  [[Code](https://github.com/jiahaolu97/poison-splat)]

**GaussianMarker: Uncertainty-Aware Copyright Protection of 3D Gaussian Splatting**<br>
*Xiufeng Huang, Ruiqi Li, Yiu-ming Cheung, Ka Chun Cheung, Simon See, Renjie Wan*<br>
arXiv preprint, 31 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.23718)]

**Geometry Cloak: Preventing TGS-based 3D Reconstruction from Copyrighted Images**<br>
*Qi Song, Ziyuan Luo, Ka Chun Cheung, Simon See, Renjie Wan*<br>
NeurIPS 2024, 30 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.22705)]

**Towards More Accurate Fake Detection on Images Generated from Advanced Generative and Neural Rendering Models**<br>
*Chengdong Dong, Vijayakumar Bhagavatula, Zhenyu Zhou, Ajay Kumar*<br>
arXiv preprint, 13 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.08642)]

## 3DGS Applications in UAV/MAV

**DRAGON: Drone and Ground Gaussian Splatting for 3D Building Reconstruction**<br>
*Yujin Ham, Mateusz Michalkiewicz, Guha Balakrishnan*<br>
ICCP 2024, 1 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.01761)]

**Developing Smart MAVs for Autonomous Inspection in GPS-denied Constructions**<br>
*Paoqiang Pan, Kewei Hu, Xiao Huang, Wei Ying, Xiaoxuan Xie, Yue Ma, Naizhong Zhang, Hanwen Kang*<br>
arXiv preprint, 12 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.06030)]

**Video2BEV: Transforming Drone Videos to BEVs for Video-based Geo-localization**<br>
*Hao Ju, Zhedong Zheng*<br>
20 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.13610)]


## 3DGS Applications in Satellite Images

**Reconstructing Satellites in 3D from Amateur Telescope Images**<br>
*Zhiming Chang, Boyang Liu, Yifei Xia, Youming Guo, Boxin Shi, He Sun*<br>
arXiv preprint, 29 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.18394)]

**SatSplatYOLO: 3D Gaussian Splatting-based Virtual Object Detection Ensembles for Satellite Feature Recognition**<br>
*Van Minh Nguyen, Emma Sandidge, Trupti Mahendrakar, Ryan T. White*<br>
arXiv preprint, 4 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.02533)]

## 3DGS Network Applications

**Embracing Radiance Field Rendering in 6G: Over-the-Air Training and Inference with 3D Contents**<br>
*Guanlin Wu, Zhonghao Lyu, Juyong Zhang, Jie Xu*<br>
arXiv preprint, 20 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.12155)]

## 3DGS for Acoustic

**AV-GS: Learning Material and Geometry Aware Priors for Novel View Acoustic Synthesis**<br>
*Swapnil Bhosale, Haosen Yang, Diptesh Kanojia, Jiankang Deng, Xiatian Zhu*<br>
arXiv preprint, 13 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.08920)]

## 3DGS with Panorama

**LayerPano3D: Layered 3D Panorama for Hyper-Immersive Scene Generation**<br>
*Shuai Yang, Jing Tan, Mengchen Zhang, Tong Wu, Yixuan Li, Gordon Wetzstein, Ziwei Liu, Dahua Lin*<br>
arXiv preprint, 23 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.13252)] [[Project](https://ys-imtech.github.io/projects/LayerPano3D/)]

**Pano2Room: Novel View Synthesis from a Single Indoor Panorama**<br>
*Guo Pu, Yiming Zhao, Zhouhui Lian*<br>
Siggraph Asia 2024, 21 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.11413)] [[Code](https://github.com/TrickyGo/Pano2Room)]

## 3DGS with Thermal

:fire: **Thermal3D-GS: Physics-induced 3D Gaussians for Thermal Infrared Novel-view Synthesis**<br>
*Qian Chen, Shihao Shu, Xiangzhi Bai*<br>
ECCV 2024, 12 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.08042)] [[Code](https://github.com/mzzcdf/Thermal3DGS)]

**ThermalGaussian: Thermal 3D Gaussian Splatting**<br>
*Rongfeng Lu, Hangyu Chen, Zunjie Zhu, Yuhang Qin, Ming Lu, Le Zhang, Chenggang Yan, Anke Xue*<br>
arXiv preprint, 11 Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.07200)]

## 3DGS with Fisheye Camera

**Fisheye-GS: Lightweight and Extensible Gaussian Splatting Module for Fisheye Cameras**<br>
*Zimu Liao, Siyan Chen, Rong Fu, Yi Wang, Zhongling Su, Hao Luo, Li Ma, Linning Xu, Bo Dai, Hengjie Li, Zhilin Pei, Xingcheng Zhang*<br>
arXiv preprint, 7  Sep 2024<br>
[[arXiv](https://arxiv.org/abs/2409.04751)]

## 3DGS with Compressive Sensing

**SCIGS: 3D Gaussians Splatting from a Snapshot Compressive Image**<br>
*Zixu Wang, Hao Yang, Yu Guo, Fei Wang*<br>
19 Nov 2024<br>
[[arXiv](https://arxiv.org/abs/2411.12471)]

## Other NVS Methods

**LVSM: A Large View Synthesis Model with Minimal 3D Inductive Bias**<br>
*Haian Jin, Hanwen Jiang, Hao Tan, Kai Zhang, Sai Bi, Tianyuan Zhang, Fujun Luan, Noah Snavely, Zexiang Xu*<br>
arXiv preprint, 22 Oct 2024<br>
[[arXiv](https://arxiv.org/abs/2410.17242)] [[Project](https://haian-jin.github.io/projects/LVSM/)]

## Other Surveys

**Learning-based Multi-View Stereo: A Survey**<br>
*Fangjinhua Wang, Qingtian Zhu, Di Chang, Quankai Gao, Junlin Han, Tong Zhang, Richard Hartley, Marc Pollefeys*<br>
arXiv preprint, 27 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.15235)]

## Contributors

Thanks to the community and hoping more and more people are joining us and submit commits and PRs!<br>

<a href = "https://github.com/yangjiheng/3DGS_and_Beyond_Docs/graphs/contributors">
  <img src = "https://contrib.rocks/image?repo=yangjiheng/3DGS_and_Beyond_Docs"/>
</a>

Made with [contributors-img](https://contrib.rocks).

## License

CC-0
