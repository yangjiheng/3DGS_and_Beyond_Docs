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
  - [3DGS Acceleration](#3dgs-acceleration)
  - [3DGS Geometry Reconstruction](#3dgs-geometry-reconstruction)
  - [3DGS+Mesh For Reconstruction](#3dgsmesh-for-reconstruction)
  - [3DGS Based Dynamic Scene](#3dgs-based-dynamic-scene)
  - [3DGS + Depth](#3dgs--depth)
  - [3DGS Few-shot Reconstruction](#3dgs-few-shot-reconstruction)
  - [3DGS Weak Camera Pose](#3dgs-weak-camera-pose)
  - [3DGS-NeRF Transfer](#3dgs-nerf-transfer)
  - [3DGS Generalization](#3dgs-generalization)
  - [3DGS Indoor Scene Reconstruction](#3dgs-indoor-scene-reconstruction)
  - [3DGS Based Wild Scene Reconstruction](#3dgs-based-wild-scene-reconstruction)
  - [3DGS Based Large Scene Reconstruction](#3dgs-based-large-scene-reconstruction)
  - [3DGS Autonomous Driving](#3dgs-autonomous-driving)
  - [3DGS Based AIGC](#3dgs-based-aigc)
  - [3DGS Model Compactness Optimization](#3dgs-model-compactness-optimization)
  - [3DGS Streaming](#3dgs-streaming)
  - [3DGS Robotics](#3dgs-robotics)
  - [3DGS Avatar Generation](#3dgs-avatar-generation)
    - [3DGS Avatar Generation Survey](#3dgs-avatar-generation-survey)
    - [3DGS Avatar Generation Progresses](#3dgs-avatar-generation-progresses)
  - [3DGS Clothes/Garment](#3dgs-clothesgarment)
  - [3DGS Scene Editing and Animation](#3dgs-scene-editing-and-animation)
  - [3DGS Stylization](#3dgs-stylization)
  - [3DGS for Computer Graphics](#3dgs-for-computer-graphics)
  - [3DGS Based Scene Understanding](#3dgs-based-scene-understanding)
  - [3DGS + Specular](#3dgs--specular)
  - [3DGS Based SLAM](#3dgs-based-slam)
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
  - [3DGS Artifact Detection](#3dgs-artifact-detection)
  - [3DGS Copyright/Safety](#3dgs-copyrightsafety)
  - [3DGS Applications in UAV/MAV](#3dgs-applications-in-uavmav)
  - [3DGS Applications in Satellite Images](#3dgs-applications-in-satellite-images)
  - [3DGS Network Applications](#3dgs-network-applications)
  - [3DGS for Acoustic](#3dgs-for-acoustic)
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
[[arXiv](https://arxiv.org/abs/2403.11134)]

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

## 3DGS Frameworks

:fire:**GauStudio: A Modular Framework for 3D Gaussian Splatting and Beyond**<br>
*Chongjie Ye, Yinyu Nie, Jiahao Chang, Yuantao Chen, Yihao Zhi, Xiaoguang Han*<br>
arXiv preprint, 28 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.19632)] [[Code](https://github.com/GAP-LAB-CUHK-SZ/gaustudio)]

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

**Mip-Splatting: Alias-free 3D Gaussian Splatting**<br>
*Zehao Yu, Anpei Chen, Binbin Huang, Torsten Sattler, Andreas Geiger*<br>
arXiv preprint, 27 Nov 2023<br>
[[arXiv](https://arxiv.org/abs/2311.16493)] [[Project](https://niujinshuchong.github.io/mip-splatting/)]

**Multi-Scale 3D Gaussian Splatting for Anti-Aliased Rendering**<br>
*Zhiwen Yan, Weng Fei Low, Yu Chen, Gim Hee Lee*<br>
arXiv preprint, 28 Nov 2023<br>
[[arXiv](https://arxiv.org/abs/2311.17089)]

**Scaffold-GS: Structured 3D Gaussians for View-Adaptive Rendering**<br>
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
[[arXiv](https://browse.arxiv.org/abs/2402.00752)]

**GaMeS: Mesh-Based Adapting and Modification of Gaussian Splatting**<br>
*Joanna Waczyńska, Piotr Borycki, Sławomir Tadeja, Jacek Tabor, Przemysław Spurek*<br>
arXiv preprint, 2 Feb 2024<br>
[[arXiv](https://browse.arxiv.org/abs/2402.01459)]

**FreGS: 3D Gaussian Splatting with Progressive Frequency Regularization**<br>
*Jiahui Zhang, Fangneng Zhan, Muyu Xu, Shijian Lu, Eric Xing*<br>
CVPR 2024, 11 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.06908)] [[Project](https://rogeraigc.github.io/FreGS-Page/)]

**Analytic-Splatting: Anti-Aliased 3D Gaussian Splatting via Analytic Integration**<br>
*Zhihao Liang, Qi Zhang, Wenbo Hu, Ying Feng, Lei Zhu, Kui Jia*<br>
arXiv preprint, 16 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.11056)]

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

**Hash3D: Training-free Acceleration for 3D Generation**<br>
*Xingyi Yang, Xinchao Wang*<br>
arXiv preprint, 9 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.06091)] [[Project](https://adamdad.github.io/hash3D/)] [[Code](https://github.com/Adamdad/hash3D)]

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
[[arXiv](https://arxiv.org/abs/2405.15518)]

**LP-3DGS: Learning to Prune 3D Gaussian Splatting**<br>
*Zhaoliang Zhang, Tianchen Song, Yongjae Lee, Li Yang, Cheng Peng, Rama Chellappa, Deliang Fan*<br>
arXiv preprint, 29 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.18784)]

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

**Unified Gaussian Primitives for Scene Representation and Rendering**<br>
*Yang Zhou, Songyin Wu, Ling-Qi Yan*<br>
arXiv preprint, 14 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.09733)]

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

**RayGauss: Volumetric Gaussian-Based Ray Casting for Photorealistic Novel View Synthesis**<br>
*Hugo Blanc, Jean-Emmanuel Deschaud, Alexis Paljic*<br>
arXiv preprint, 6 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.03356)] [[Project](https://raygauss.github.io/)]

**Mipmap-GS: Let Gaussians Deform with Scale-specific Mipmap for Anti-aliasing Rendering**<br>
*Jiameng Li, Yue Shi, Jiezhang Cao, Bingbing Ni, Wenjun Zhang, Kai Zhang, Luc Van Gool*<br>
arXiv preprint, 12 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.06286)]

## 3DGS Acceleration

**EAGLES: Efficient Accelerated 3D Gaussians with Lightweight EncodingS**<br>
*Sharath Girish, Kamal Gupta, Abhinav Shrivastava*<br>
arXiv preprint, 7 Dec, 2023<br>
[[arXiv](https://arxiv.org/abs/2312.04564)] [[Project](https://efficientgaussian.github.io/)] [[Code](https://github.com/Sharath-girish/efficientgaussian)]

**StopThePop: Sorted Gaussian Splatting for View-Consistent Real-time Rendering**<br>
*Lukas Radl, Michael Steiner, Mathias Parger, Alexander Weinrauch, Bernhard Kerbl, Markus Steinberger*<br>
SIGGRAPH 2024, 1 Feb 2024<br>
[[arXiv](https://browse.arxiv.org/abs/2402.00525)] [[Project](https://r4dl.github.io/StopThePop/)] [[Code](https://github.com/r4dl/StopThePop)] [[Video](https://www.youtube.com/watch?v=EmcXtHYhigk)]

**GES: Generalized Exponential Splatting for Efficient Radiance Field Rendering**<br>
*Abdullah Hamdi, Luke Melas-Kyriazi, Guocheng Qian, Jinjie Mai, Ruoshi Liu, Carl Vondrick, Bernard Ghanem, Andrea Vedaldi*<br>
CVPR 2024, 15 Feb 2024<br>
[[arXiv](https://arxiv.org/abs/2402.10128)] [[Project](https://abdullahamdi.com/ges/)] [[Code](https://github.com/ajhamdi/ges-splatting)] [[Video](https://www.youtube.com/watch?v=edSvNy3roV8&feature=youtu.be)]

**OmniGS: Omnidirectional Gaussian Splatting for Fast Radiance Field Reconstruction using Omnidirectional Images**<br>
*Longwei Li, Huajian Huang, Sai-Kit Yeung, Hui Cheng*<br>
arXiv preprint, 4 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.03202)]

**RTGS: Enabling Real-TimeGaussianSplatting on Mobile Devices Using Efficiency-Guided Pruning and Foveated Rendering**<br>
*Weikai Lin, Yu Feng, Yuhao Zhu*<br>
arXiv preprint, 29 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2407.00435)] [[Code](https://github.com/horizon-research/Fov-3DGS)]

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

**PGSR: Planar-based Gaussian Splatting for Efficient and High-Fidelity Surface Reconstruction**<br>
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

**Superpoint Gaussian Splatting for Real-Time High-Fidelity Dynamic Scene Reconstruction**<br>
*Diwen Wan, Ruijie Lu, Gang Zeng*<br>
ICML 2024, 6 Jun 2024<br>
[[arXiv](https://arxiv.org/abs/2406.03697)] [[Project](https://dnvtmf.github.io/SP_GS.github.io/)] [[Code]()https://github.com/dnvtmf/SP_GS]

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

## 3DGS + Depth

**DNGaussian: Optimizing Sparse-View 3D Gaussian Radiance Fields with Global-Local Depth Normalization**<br>
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

## 3DGS Weak Camera Pose

**COLMAP-Free 3D Gaussian Splatting**<br>
*Yang Fu, Sifei Liu, Amey Kulkarni, Jan Kautz, Alexei A. Efros, Xiaolong Wang*<br>
CVPR 2024, 12 Dec 2023<br>
[[arXiv](https://arxiv.org/abs/2312.07504)] [[Project](https://oasisyang.github.io/colmap-free-3dgs/)] [[Video](https://www.youtube.com/watch?si=kqu3dbXopDdNg0wX&v=mGeVQS4ExK4&feature=youtu.be)]

**iComMa: Inverting 3D Gaussians Splatting for Camera Pose Estimation via Comparing and Matching**<br>
*Yuan Sun, Xuan Wang, Yunfan Zhang, Jie Zhang, Caigui Jiang, Yu Guo, Fei Wang*<br>
arXiv preprint, 14 Dec 2023<br>
[[arXiv]https://arxiv.org/abs/2312.09031]

**A Construct-Optimize Approach to Sparse View Synthesis without Camera Pose**<br>
*Kaiwen Jiang, Yang Fu, Mukund Varma T, Yash Belhe, Xiaolong Wang, Hao Su, Ravi Ramamoorthi*<br>
arXiv preprint, 6 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.03659)]

**6DGS: 6D Pose Estimation from a Single Image and a 3D Gaussian Splatting Model**<br>
*Matteo Bortolon, Theodore Tsesmelis, Stuart James, Fabio Poiesi, Alessio Del Bue*<br>
ECCV 2024, 22 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.15484)] [[Project](https://mbortolon97.github.io/6dgs/)] [[Code](https://github.com/mbortolon97/6dgs)] [[Video](https://www.youtube.com/watch?v=SB4ToD93NFA)]


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

## 3DGS Indoor Scene Reconstruction

**360-GS: Layout-guided Panoramic Gaussian Splatting For Indoor Roaming**<br>
*Jiayang Bai, Letian Huang, Jie Guo, Wen Gong, Yuanqi Li, Yanwen Guo*<br>
arXiv preprint, 1 Feb 2024<br>
[[arXiv]](https://browse.arxiv.org/abs/2402.00763)

**MonoSelfRecon: Purely Self-Supervised Explicit Generalizable 3D Reconstruction of Indoor Scenes from Monocular RGB Views**<br>
*Runfa Li, Upal Mahbub, Vasudev Bhaskaran, Truong Nguyen*<br>
arXiv preprint, 10 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.06753)]

**FreeSplat: Generalizable 3D Gaussian Splatting Towards Free-View Synthesis of Indoor Scenes**<br>
*Yunsong Wang, Tianxin Huang, Hanlin Chen, Gim Hee Lee*<br>
arXiv preprint, 28 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.17958)]

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

**WildGaussians: 3D Gaussian Splatting in the Wild**<br>
*Jonas Kulhanek, Songyou Peng, Zuzana Kukelova, Marc Pollefeys, Torsten Sattler*<br>
arXiv preprint, 11 Jul 2024<br>
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

**CityGaussian: Real-time High-quality Large-Scale Scene Rendering with Gaussians**<br>
*Yang Liu, He Guan, Chuanchen Luo, Lue Fan, Junran Peng, Zhaoxiang Zhang*<br>
arXiv preprint, 1 Apr 2024<br>
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

## 3DGS Model Compactness Optimization

**LightGaussian: Unbounded 3D Gaussian Compression with 15x Reduction and 200+ FPS**<br>
*Zhiwen Fan, Kevin Wang, Kairun Wen, Zehao Zhu, Dejia Xu, Zhangyang Wang*<br>
arXiv preprint, 28 Nov 2023<br>
[[arXiv](https://arxiv.org/abs/2311.17245)] [[Project](https://lightgaussian.github.io/)] [[Video](https://www.bilibili.com/video/BV1QN4y127o9/)]

**Identifying Unnecessary 3D Gaussians using Clustering for Fast Rendering of 3D Gaussian Splatting**<br>
*Joongho Jo, Hyeongwon Kim, Jongsun Park*<br>
arXiv preprint, 21 Feb 2024<br>
[[arXiv](https://arxiv.org/abs/2402.13827)]

**CompGS: Efficient 3D Scene Representation via Compressed Gaussian Splatting**<br>
*Xiangrui Liu, Xinju Wu, Pingping Zhang, Shiqi Wang, Zhu Li, Sam Kwong*<br>
arXiv preprint, 15 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.09458)]

**F-3DGS: Factorized Coordinates and Representations for 3D Gaussian Splatting**<br>
*Xiangyu Sun, Joo Chan Lee, Daniel Rho, Jong Hwan Ko, Usman Ali, Eunbyung Park*<br>
arXiv preprint, 27 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.17083)] [[Project](https://xiangyu1sun.github.io/Factorize-3DGS/)] [[Code](https://github.com/Xiangyu1Sun/Factorize-3DGS)]

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

## 3DGS Streaming

**3DGStream: On-the-Fly Training of 3D Gaussians for Efficient Streaming of Photo-Realistic Free-Viewpoint Videos**<br>
*Jiakai Sun, Han Jiao, Guangyuan Li, Zhanjie Zhang, Lei Zhao, Wei Xing*<br>
CVPR 2024, 3 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.01444)] [[Project](https://sjojok.top/3dgstream/)] [[Code](https://github.com/SJoJoK/3DGStream)]

**HAC: Hash-grid Assisted Context for 3D Gaussian Splatting Compression**<br>
*Yihang Chen, Qianyi Wu, Jianfei Cai, Mehrtash Harandi, Weiyao Lin*<br>
arXiv preprint, 12 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.14530)] [[Project](https://yihangchen-ee.github.io/project_hac/)] [[Code](https://yihangchen-ee.github.io/project_hac/)]

## 3DGS Robotics

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
[[arXiv]()https://arxiv.org/abs/2404.19026] [[Project](https://conallwang.github.io/MeGA_Pages/)]

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

**Feature Splatting: Language-Driven Physics-Based Scene Synthesis and Editing**<br>
*Ri-Zhao Qiu, Ge Yang, Weijia Zeng, Xiaolong Wang*<br>
arXiv preprint, 1 Apr 2024<br>
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


## 3DGS for Computer Graphics

**PhysGaussian: Physics-Integrated 3D Gaussians for Generative Dynamics**<br>
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

**3D Gaussian Ray Tracing: Fast Tracing of Particle Scenes**<br>
*Nicolas Moenne-Loccoz, Ashkan Mirzaei, Or Perel, Riccardo de Lutio, Janick Martinez Esturo, Gavriel State, Sanja Fidler, Nicholas Sharp, Zan Gojcic*<br>
arXiv preprint, 9 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.07090)]


## 3DGS Based Scene Understanding

**Language Embedded 3D Gaussians for Open-Vocabulary Scene Understanding**<br>
*Jin-Chuan Shi, Miao Wang, Hao-Bin Duan, Shao-Hua Guan*<br>
arXiv preprint, 30 Nov 2023<br>
[[arXiv](https://arxiv.org/abs/2311.18482)]

**Semantic Anything in 3D Gaussians**<br>
*Xu Hu, Yuxi Wang, Lue Fan, Junsong Fan, Junran Peng, Zhen Lei, Qing Li, Zhaoxiang Zhang*<br>
arXiv preprint, 31 Jan 2024<br>
[[arXiv](https://arxiv.org/abs/2401.17857)]

**2D-Guided 3D Gaussian Segmentation**<br>
*Kun Lan, Haoran Li, Haolin Shi, Wenjun Wu, Yong Liao, Lin Wang, Pengyuan Zhou*<br>
arXiv preprint, 26 Dec 2023<br>
[[arXiv](https://arxiv.org/abs/2312.16047)]

**CoSSegGaussians: Compact and Swift Scene Segmenting 3D Gaussians**<br>
*Bin Dou, Tianyu Zhang, Yongjia Ma, Zhaohui Wang, Zejian Yuan*<br>
arXiv preprint, 11 Jan 2024<br>
[[arXiv](https://arxiv.org/abs/2401.05925)] [[Project](https://david-dou.github.io/CoSSegGaussians/)]

**Semantic Gaussians: Open-Vocabulary Scene Understanding with 3D Gaussian Splatting**<br>
*Jun Guo, Xiaojian Ma, Yue Fan, Huaping Liu, Qing Li*<br>
arXiv preprint, 22 Mar 2024<br>
[[arXiv](https://arxiv.org/abs/2403.15624)] [[Project](https://semantic-gaussians.github.io/)] [[Code](https://github.com/sharinka0715/semantic-gaussians)]

**CLIP-GS: CLIP-Informed Gaussian Splatting for Real-time and View-consistent 3D Semantic Understanding**<br>
*Guibiao Liao, Jiankun Li, Zhenyu Bao, Xiaoqing Ye, Jingdong Wang, Qing Li, Kanglin Liu*<br>
arXiv preprint, 22 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.14249)]  [[Code](https://github.com/gbliao/CLIP-GS)]

**OMEGAS: Object Mesh Extraction from Large Scenes Guided by Gaussian Segmentation**<br>
*Lizhi Wang, Feng Zhou, Jianqin Yin*
arXiv preprint, 24 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.15891)] [[Code](https://github.com/CrystalWlz/OMEGAS)]

**Memorize What Matters: Emergent Scene Decomposition from Multitraverse**<br>
*Yiming Li, Zehong Wang, Yue Wang, Zhiding Yu, Zan Gojcic, Marco Pavone, Chen Feng, Jose M. Alvarez*<br>
arXiv preprint, 27 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.17187)] [[Project](https://3d-gaussian-mapping.github.io/)] [[Code](https://github.com/NVlabs/3DGM)]

**RT-GS2: Real-Time Generalizable Semantic Segmentation for 3D Gaussian Representations of Radiance Fields**<br>
*Mihnea-Bogdan Jurca, Remco Royen, Ion Giosan, Adrian Munteanu*<br>
arXiv preprint, 28 May 2024<br>
[[arXiv](https://arxiv.org/abs/2405.18033)]

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


**Fast and Efficient: Mask Neural Fields for 3D Scene Segmentation**<br>
*Zihan Gao, Lingling Li, Licheng Jiao, Fang Liu, Xu Liu, Wenping Ma, Yuwei Guo, Shuyuan Yang*<br>
arXiv preprintm, 1 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.01220)]

**Segment Any 4D Gaussians**<br>
*Shengxiang Ji, Guanjun Wu, Jiemin Fang, Jiazhong Cen, Taoran Yi, Wenyu Liu, Qi Tian, Xinggang Wang*<br>
arXiv preprint, 5 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.04504)] [[Project](https://jsxzs.github.io/sa4d/)]

**Scaling 3D Reasoning with LMMs to Large Robot Mission Environments Using Datagraphs**<br>
*W. J. Meijer, A.C. Kemmeren, E.H.J. Riemens, J.E. Fransman, M. van Bekkum, G.J. Burghouts, J.D. van Mil*<br>
RSS Workshop on Semantics for Robotics 2024, 15 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.10743)]

**Click-Gaussian: Interactive Segmentation to Any 3D Gaussians**<br>
*Seokhun Choi, Hyeonseop Song, Jaechul Kim, Taehyeong Kim, Hoseok Do*<br>
ECCV 2024, 16 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.11793)] [[Project](https://seokhunchoi.github.io/Click-Gaussian/)]

**SpectralGaussians: Semantic, spectral 3D Gaussian splatting for multi-spectral scene representation, visualization and analysis**<br>
*Saptarshi Neil Sinha, Holger Graf, Michael Weinmann*<br>
arXiv preprint, 13 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.06975)]

## 3DGS + Specular

**Spec-Gaussian: Anisotropic View-Dependent Appearance for 3D Gaussian Splatting**<br>
*Ziyi Yang, Xinyu Gao, Yangtian Sun, Yihua Huang, Xiaoyang Lyu, Wen Zhou, Shaohui Jiao, Xiaojuan Qi, Xiaogang Jin*<br>
arXiv preprint, 24 Feb 2024<br>
[[arXiv](https://arxiv.org/abs/2402.15870)]


## 3DGS Based SLAM

**SplaTAM: Splat, Track & Map 3D Gaussians for Dense RGB-D SLAM**<br>
*Nikhil Keetha, Jay Karhade, Krishna Murthy Jatavallabhula, Gengshan Yang, Sebastian Scherer, Deva Ramanan, Jonathon Luiten*<br>
arXiv preprint, 4 Dec 2023<br>
[[arXiv](https://arxiv.org/abs/2312.02126)]

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

### 3DGS Application in Underwater Scenario

**RecGS: Removing Water Caustic with Recurrent Gaussian Splatting**<br>
*Tianyi Zhang, Weiming Zhi, Kaining Huang, Joshua Mangelson, Corina Barbalata, Matthew Johnson-Roberson*<br>
arXiv preprint, 14 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.10318)]

## 3DGS Artifact Detection

**SplatPose & Detect: Pose-Agnostic 3D Anomaly Detection**<br>
*Mathis Kruse, Marco Rudolph, Dominik Woiwode, Bodo Rosenhahn*<br>
CVPR 2024, 10 Apr 2024<br>
[[arXiv](https://arxiv.org/abs/2404.06832)]

## 3DGS Copyright/Safety

**GaussianStego: A Generalizable Stenography Pipeline for Generative 3D Gaussians Splatting**<br>
*Chenxin Li, Hengyu Liu, Zhiwen Fan, Wuyang Li, Yifan Liu, Panwang Pan, Yixuan Yuan*<br>
arXiv preprint, 1 Jul 2024<br>
[[arXiv](https://arxiv.org/abs/2407.01301)] [[Project](https://gaussian-stego.github.io/)]

## 3DGS Applications in UAV/MAV

**Developing Smart MAVs for Autonomous Inspection in GPS-denied Constructions**<br>
*Paoqiang Pan, Kewei Hu, Xiao Huang, Wei Ying, Xiaoxuan Xie, Yue Ma, Naizhong Zhang, Hanwen Kang*<br>
arXiv preprint, 12 Aug 2024<br>
[[arXiv](https://arxiv.org/abs/2408.06030)]

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


## Contributors

Thanks to the community and hoping more and more people are joining us and submit commits and PRs!<br>

<a href = "https://github.com/yangjiheng/3DGS_and_Beyond_Docs/graphs/contributors">
  <img src = "https://contrib.rocks/image?repo=yangjiheng/3DGS_and_Beyond_Docs"/>
</a>

Made with [contributors-img](https://contrib.rocks).

## License

CC-0
