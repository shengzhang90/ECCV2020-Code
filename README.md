# ECCV2020-Code
ECCV 2020 论文开源项目合集，同时欢迎各位大佬提交issue，分享ECCV 2020开源项目

关于往年CV顶会论文（如CVPR 2020、ICCV 2019、ECCV 2018）以及其他优质CV论文和大盘点，详见： https://github.com/amusi/daily-paper-computer-vision 

- [CNN](#CNN)
- [图像分类](#Image-Classification)
- [2D目标检测](#Object-Detection)
- [3D目标检测](#3D-Object-Detection)
- [视频目标检测](#Video-Object-Detection)
- [语义分割](#Semantic-Segmentation)
- [实例分割](#Instance-Segmentation)
- [视频目标分割](#VOS)
- [单/多目标跟踪](#Object-Tracking)
- [GAN](#GAN)
- [NAS](#NAS)
- [3D点云（分类/分割/配准/补全等）](#3D-PointCloud)
- [人脸（检测/识别/解析等）](#Face)
- [Re-ID](#Re-ID)
- [显著性检测（SOD）](#Saliency)
- [模型压缩（剪枝/知识蒸馏等）](#Model-Compression)
- [视频理解/行为识别/行为检测](#Action-Recognition)
- [场景文本检测](#Scene-Text-Detection)
- [场景文本识别](#Scene-Text-Recognition)
- [特征点检测/描述符](#Feature)
- [姿态估计](#Pose-Estimation)
- [深度估计](#Depth-Estimation)
- [深度补全](#Depth-Completion)
- [域泛化](#Domain-Generalization)
- [超分辨率](#Super-Resolution)
- [去模糊](#Deblurring)
- [去雨](#Deraining)
- [图像/视频修复(补全)](#Image-Video-Inpainting)
- [图像检索](#Image-Retrieval)
- [光流估计](#Optical-Flow-Estimation)
- [视频插帧](#Video-Interpolation)
- [车道线检测](#Lane-Detection)
- [轨迹预测](#TP)
- [线段检测](#Line-Detection)
- [眼动追踪](#Eye-Tracking)
- [数据集](#Datasets)
- [其他](#Others)
- [不确定中没中](#Not-Sure)

<a name="CNN"></a>

# CNN

 **WeightNet: Revisiting the Design Space of Weight Networks**

- 论文：https://arxiv.org/abs/2007.11823
- 代码：https://github.com/megvii-model/WeightNet

**Feature Pyramid Transformer**

- 论文：https://arxiv.org/abs/2007.09451

- 代码：https://github.com/ZHANGDONG-NJUST/FPT

**Dynamic Group Convolution for Accelerating Convolutional Neural Networks**

- 论文：https://arxiv.org/abs/2007.04242
- 代码：https://github.com/zhuogege1943/dgc

**Learning to Learn Parameterized Classification Networks for Scalable Input Images**

- 论文：https://arxiv.org/abs/2007.06181

- 代码：https://github.com/d-li14/SAN

**Rethinking Bottleneck Structure for Efficient Mobile Network Design**

- 论文：https://arxiv.org/abs/2007.02269
- 代码：https://github.com/zhoudaquan/rethinking_bottleneck_design

**MutualNet: Adaptive ConvNet via Mutual Learning from Network Width and Resolution**

- 论文：Oral
- 论文：https://arxiv.org/abs/1909.12978
- 代码：https://github.com/taoyang1122/MutualNet

**PSConv: Squeezing Feature Pyramid into One Compact Poly-Scale Convolutional Layer**

- 论文：https://arxiv.org/abs/2007.06191
- 代码：https://github.com/d-li14/PSConv

<a name="Image-Classification"></a>

# 图像分类

**Learning to Learn Parameterized Classification Networks for Scalable Input Images**

- 论文：暂无

- 代码：https://github.com/d-li14/SAN

**Learning To Classify Images Without Labels**

- 论文：https://arxiv.org/abs/2005.12320
- 代码：https://github.com/wvangansbeke/Unsupervised-Classification

<a name="Object-Detection"></a>

# 2D目标检测

**Dense RepPoints: Representing Visual Objects with Dense Point Sets**

- 论文：https://arxiv.org/abs/1912.11473
- 代码：https://github.com/justimyhxu/Dense-RepPoints

**Corner Proposal Network for Anchor-free, Two-stage Object Detection**

- 论文：https://arxiv.org/abs/2007.13816

- 代码：https://github.com/Duankaiwen/CPNDet

**BorderDet: Border Feature for Dense Object Detection**

- 论文：https://arxiv.org/abs/2007.11056

- 代码：https://github.com/Megvii-BaseDetection/BorderDet
- 中文解读：https://zhuanlan.zhihu.com/p/163044323

**Multi-Scale Positive Sample Refinement for Few-Shot Object Detection**

- 论文：https://arxiv.org/abs/2007.09384

- 代码：https://github.com/jiaxi-wu/MPSR

**PIoU Loss: Towards Accurate Oriented Object Detection in Complex Environments**

- 论文：https://arxiv.org/abs/2007.09584

- 代码：https://github.com/clobotics/piou

- 数据集：https://github.com/clobotics/piou

**Boosting Weakly Supervised Object Detection with Progressive Knowledge Transfer**

- 论文：https://arxiv.org/abs/2007.07986
- 代码：https://github.com/mikuhatsune/wsod_transfer

**Probabilistic Anchor Assignment with IoU Prediction for Object Detection**

- 论文：https://arxiv.org/abs/2007.08103
- 代码：https://github.com/kkhoot/PAA

**HoughNet: Integrating near and long-range evidence for bottom-up object detection**

- 论文：https://arxiv.org/abs/2007.02355
- 代码：https://github.com/nerminsamet/houghnet

**OS2D: One-Stage One-Shot Object Detection by Matching Anchor Features**

- 论文：https://arxiv.org/abs/2003.06800

- 代码：https://github.com/aosokin/os2d

**End-to-End Object Detection with Transformers**

- Oral

- 论文：https://ai.facebook.com/research/publications/end-to-end-object-detection-with-transformers
- 代码：https://github.com/facebookresearch/detr

**Dynamic R-CNN: Towards High Quality Object Detection via Dynamic Training**

- 论文：https://arxiv.org/abs/2004.06002

- 代码：https://github.com/hkzhang95/DynamicRCNN 

## 遥感旋转目标检测

**Arbitrary-Oriented Object Detection with Circular Smooth Label**

- 论文：https://arxiv.org/abs/2003.05597
- 代码：https://github.com/Thinklab-SJTU/CSL_RetinaNet_Tensorflow

<a name="3D-Object-Detection"></a>

# 3D目标检测

**Pillar-based Object Detection for Autonomous Driving**

- 论文：https://arxiv.org/abs/2007.10323
- 代码：https://github.com/WangYueFt/pillar-od

**EPNet: Enhancing Point Features with Image Semantics for 3D Object Detection**

- 论文：https://arxiv.org/abs/2007.08856
- 代码：https://github.com/happinesslz/EPNet

<a name="Video-Object-Detection"></a>

# 视频目标检测

**Learning Where to Focus for Efficient Video Object Detection**

- 主页：https://jiangzhengkai.github.io/LSTS/
- 论文：暂无
- 代码：https://github.com/jiangzhengkai/LSTS

<a name="Semantic-Segmentation"></a>

# 语义分割

**Tensor Low-Rank Reconstruction for Semantic Segmentation**

- 论文：https://arxiv.org/abs/2008.00490

- 代码：https://github.com/CWanli/RecoNet

**Bi-directional Cross-Modality Feature Propagation with Separation-and-Aggregation Gate for RGB-D Semantic Segmentation**

- 论文：https://arxiv.org/abs/2007.09183

- 代码：https://github.com/charlesCXK/RGBD_Semantic_Segmentation_PyTorch

**GMNet: Graph Matching Network for Large Scale Part Semantic Segmentation in the Wild**

- 主页：https://lttm.dei.unipd.it/paper_data/GMNet/
- 论文：https://arxiv.org/abs/2007.09073
- 代码：https://github.com/LTTM/GMNet

**SegFix: Model-Agnostic Boundary Refinement for Segmentation**

- 论文：https://arxiv.org/abs/2007.04269

- 代码：https://github.com/openseg-group/openseg.pytorch

**Mining Cross-Image Semantics for Weakly Supervised Semantic Segmentation**

- Oral
- 论文：https://arxiv.org/abs/2007.01947
- 代码：https://github.com/GuoleiSun/MCIS_wsss

 **Improving Semantic Segmentation via Decoupled Body and Edge Supervision**

- 论文：https://arxiv.org/abs/2007.10035

- 代码：https://github.com/lxtGH/DecoupleSegNets

<a name="Instance-Segmentation"></a>

# 实例分割

**SipMask: Spatial Information Preservation for Fast Image and Video Instance Segmentation**

- 论文：https://arxiv.org/abs/2007.14772

- 代码：https://github.com/JialeCao001/SipMask

**Commonality-Parsing Network across Shape and Appearance for Partially Supervised Instance Segmentation**

- 论文：https://arxiv.org/abs/2007.12387

- 代码：https://github.com/fanq15/CPMask

 **Boundary-preserving Mask R-CNN**

- 论文：https://arxiv.org/abs/2007.08921

- 代码：https://github.com/hustvl/BMaskR-CNN

**Conditional Convolutions for Instance Segmentation**

- Oral
- 论文：https://arxiv.org/abs/2003.05664
- 代码：https://github.com/aim-uofa/AdelaiDet/blob/master/configs/CondInst/README.md

**SOLO: Segmenting Objects by Locations**

- 论文：https://arxiv.org/abs/1912.04488
- 代码：https://github.com/WXinlong/SOLO

- 知乎话题：https://www.zhihu.com/question/360594484

<a name="VOS"></a>

# 视频目标分割

**Collaborative Video Object Segmentation by Foreground-Background Integration**

- 论文：https://arxiv.org/abs/2003.08333
- 代码：https://github.com/z-x-yang/CFBI

**Video Object Segmentation with Episodic Graph Memory Networks**

- 论文：https://arxiv.org/abs/2007.07020

- 代码：https://github.com/carrierlxk/GraphMemVOS

<a name="Object-Tracking"></a>

# 单/多目标跟踪

**Ocean: Object-aware Anchor-Free Tracking**

- 论文：https://arxiv.org/abs/2006.10721

- 代码：https://github.com/researchmm/TracKit

## 多目标跟踪

**Chained-Tracker: Chaining Paired Attentive Regression Results for End-to-End Joint Multiple-Object Detection and Tracking**

- 论文：https://arxiv.org/abs/2007.14557

- 代码：https://github.com/pjl1995/CTracker

**Ocean: Object-aware Anchor-Free Tracking**

- 论文：https://arxiv.org/abs/2006.10721

- 代码：https://github.com/researchmm/TracKit

**TAO: A Large-Scale Benchmark for Tracking Any Object**

- 主页：http://taodataset.org/
- 论文：https://arxiv.org/abs/2005.10356
- 代码：https://github.com/TAO-Dataset/tao

**Segment as Points for Efficient Online Multi-Object Tracking and Segmentation**

- Oral
- 论文：https://arxiv.org/abs/2007.01550
- 代码：https://github.com/detectRecog/PointTrack
- 数据集：https://github.com/detectRecog/PointTrack

<a name="GAN"></a>

# GAN

**Rewriting a Deep Generative Model**

- 论文：https://arxiv.org/abs/2007.15646

- 代码：https://github.com/davidbau/rewriting

**Contrastive Learning for Unpaired Image-to-Image Translation**

- 论文：https://arxiv.org/abs/2007.15651
- 代码：https://github.com/taesungp/contrastive-unpaired-translation

**XingGAN for Person Image Generation**

- 论文：暂无
- 代码：https://github.com/Ha0Tang/XingGAN

<a name="NAS"></a>

# NAS

**Rethinking Bottleneck Structure for Efficient Mobile Network Design**

- 论文：https://arxiv.org/abs/2007.02269
- 代码：https://github.com/zhoudaquan/rethinking_bottleneck_design

**Fair DARTS: Eliminating Unfair Advantages in Differentiable Architecture Search**

- 论文：https://arxiv.org/abs/1911.12126
- 代码：https://github.com/xiaomi-automl/fairdarts

<a name="3D-PointCloud"></a>

# 3D点云（分类/分割/配准/补全等）

**A Closer Look at Local Aggregation Operators in Point Cloud Analysis**

- 论文：https://arxiv.org/abs/2007.01294
- 代码：https://github.com/zeliu98/CloserLook3D

## 3D点云补全

**Multimodal Shape Completion via Conditional Generative Adversarial Networks**

- 论文：https://arxiv.org/abs/2003.07717
- 代码：https://github.com/ChrisWu1997/Multimodal-Shape-Completion

**GRNet: Gridding Residual Network for Dense Point Cloud Completion**

- 论文：https://arxiv.org/abs/2006.03761
- 代码：https://github.com/hzxie/GRNet

## 3D点云生成

**Progressive Point Cloud Deconvolution Generation Network**

- 论文：https://arxiv.org/abs/2007.05361

- 代码：https://github.com/fpthink/PDGN

<a name="Face"></a>

# 人脸（检测/识别/解析等）

## 3D人脸重建

**Self-Supervised Monocular 3D Face Reconstruction by Occlusion-Aware Multi-view Geometry Consistency**

- 论文：https://arxiv.org/abs/2007.12494
- 代码：https://github.com/jiaxiangshang/MGCNet

## 人脸活体检测

**CelebA-Spoof: Large-Scale Face Anti-Spoofing Dataset with Rich Annotations**

- 论文：https://arxiv.org/abs/2007.12342

- 数据集：https://github.com/Davidzhangyuanhan/CelebA-Spoof

## 人脸解析

**Edge-aware Graph Representation Learning and Reasoning for Face Parsing**

- 论文：https://arxiv.org/abs/2007.11240

- 代码：https://github.com/tegusi/EAGRNet

<a name="Re-ID"></a>

# Re-ID

**Temporal Complementary Learning for Video Person Re-Identification**

论文下载链接：https://arxiv.org/abs/2007.09357

代码：https://github.com/blue-blue272/VideoReID-TCLNet

**Joint Disentangling and Adaptation for Cross-Domain Person Re-Identification**

- 论文：https://arxiv.org/abs/2007.10315
- 代码：https://github.com/NVlabs/DG-Net-PP

**Robust Re-Identification by Multiple Views Knowledge Distillation**

- 论文：https://arxiv.org/abs/2007.04174
- 代码：https://github.com/aimagelab/VKD

**Multiple Expert Brainstorming for Domain Adaptive Person Re-identification**

- 论文：https://arxiv.org/abs/2007.01546

- 代码：https://github.com/YunpengZhai/MEB-Net

<a name="Saliency"></a>

# 显著性检测（SOD）

**Suppress and Balance: A Simple Gated Network for Salient Object Detection**

- Oral

- 论文：https://arxiv.org/abs/2007.08074
- 代码：https://github.com/Xiaoqi-Zhao-DLUT/GateNet-RGB-Saliency

**Hierarchical Dynamic Filtering Network for RGB-D Salient Object Detection**

- 论文：https://arxiv.org/abs/2007.06227

- 代码：https://github.com/lartpang/HDFNet

**A Single Stream Network for Robust and Real-time RGB-D Salient Object Detection**

- 论文：https://arxiv.org/abs/2007.06811
- 代码：https://github.com/Xiaoqi-Zhao-DLUT/DANet-RGBD-Saliency

**Cross-Modal Weighting Network for RGB-D Salient Object Detection**

- 论文：暂无

- 代码：https://github.com/MathLee/CMWNet

**BBS-Net: RGB-D Salient Object Detection with a Bifurcated Backbone Strategy Network**

- 论文：暂无
- 代码：https://github.com/DengPingFan/BBS-Net

**Highly Efficient Salient Object Detection with 100K Parameters**

- 论文：https://arxiv.org/abs/2003.05643
- 代码：https://github.com/MCG-NKU/Sal100K

<a name="Model-Compression"></a>

# 模型压缩（剪枝/知识蒸馏等）

**EagleEye: Fast Sub-net Evaluation for Efficient Neural Network Pruning**

- 论文：https://arxiv.org/abs/2007.02491
- 代码：https://github.com/anonymous47823493/EagleEye

<a name="Action-Recognition"></a>

# 视频理解/行为识别/行为检测

**Context-Aware RCNN: A Baseline for Action Detection in Videos**

- 论文：https://arxiv.org/abs/2007.09861

- 代码：https://github.com/MCG-NJU/CRCNN-Action

**Actions as Moving Points**

- 论文：https://arxiv.org/abs/2001.04608
- 代码：https://github.com/MCG-NJU/MOC-Detector 

**SF-Net: Single-Frame Supervision for Temporal Action Localization**

- 论文：https://arxiv.org/abs/2003.06845
- 代码：https://github.com/Flowerfan/SF-Net

**Asynchronous Interaction Aggregation for Action Detection**

- 论文：https://arxiv.org/abs/2004.07485

- 代码：https://github.com/MVIG-SJTU/AlphAction 

<a name="Scene-Text-Detection"></a>

# 场景文本检测

**Mask TextSpotter v3: Segmentation Proposal Network for Robust Scene Text Spotting**

- 论文：https://arxiv.org/abs/2007.09482

- 代码：https://github.com/MhLiao/MaskTextSpotterV3

<a name="Scene-Text-Recognition"></a>

# 场景文本识别

**Mask TextSpotter v3: Segmentation Proposal Network for Robust Scene Text Spotting**

- 论文：https://arxiv.org/abs/2007.09482

- 代码：https://github.com/MhLiao/MaskTextSpotterV3

<a name="Feature"></a>

# 特征点检测/描述符

**Learning and aggregating deep local descriptors for instance-level recognition**

- 论文：https://arxiv.org/abs/2007.13172

- 代码：https://github.com/gtolias/how

**Online Invariance Selection for Local Feature Descriptors**

- Oral

- 论文：https://arxiv.org/abs/2007.08988

- 代码：https://github.com/rpautrat/LISRD

<a name="Pose-Estimation"></a>

# 姿态估计

**Key Frame Proposal Network for Efficient Pose Estimation in Videos**

- 论文：https://arxiv.org/abs/2007.15217

- 代码：https://github.com/Yuexiaoxi10/Key-Frame-Proposal-Network-for-Efficient-Pose-Estimation-in-Videos

<a name="Depth-Estimation"></a>

# 深度估计

## 单目深度估计

**P2Net: Patch-match and Plane-regularization for Unsupervised Indoor Depth Estimation**

- 论文：https://arxiv.org/abs/2007.07696
- 代码：https://github.com/svip-lab/Indoor-SfMLearner

**Self-Supervised Monocular Depth Estimation: Solving the Dynamic Object Problem by Semantic Guidance**

- 论文：https://arxiv.org/abs/2007.06936

- 代码：https://github.com/ifnspaml/SGDepth

<a name="Depth-Completion"></a>

# 深度补全

**Non-Local Spatial Propagation Network for Depth Completion**

- 论文：https://arxiv.org/abs/2007.10042
- 代码：https://github.com/zzangjinsun/NLSPN_ECCV20

<a name="Domain-Generalization"></a>

# 域泛化

**Learning from Extrinsic and Intrinsic Supervisions for Domain Generalization**

- 论文：https://arxiv.org/abs/2007.09316
- 代码：https://github.com/EmmaW8/EISNet 

<a name="Super-Resolution"></a>

# 超分辨率

## 图像超分辨率

**Component Divide-and-Conquer for Real-World Image Super-Resolution**

- 论文：https://arxiv.org/abs/2008.01928

- 代码和数据集：https://github.com/xiezw5/Component-Divide-and-Conquer-for-Real-World-Image-Super-Resolution

**Learning with Privileged Information for Efficient Image Super-Resolution**

- 主页：https://cvlab.yonsei.ac.kr/projects/PISR/
- 论文：https://arxiv.org/abs/2007.07524
- 代码：https://github.com/cvlab-yonsei/PISR

**Spatial-Angular Interaction for Light Field Image Super-Resolution**

- 论文：https://arxiv.org/abs/1912.07849
- 代码：https://github.com/YingqianWang/LF-InterNet 

**Invertible Image Rescaling**

- 论文：https://arxiv.org/abs/2005.05650
- 代码：https://github.com/pkuxmq/Invertible-Image-Rescaling

## 视频超分辨率

**Video Super-Resolution with Recurrent Structure-Detail Network**

- 论文：https://arxiv.org/abs/2008.00455

- 代码：https://github.com/junpan19/RSDN

<a name="Deblurring"></a>

# 去模糊

**End-to-end Interpretable Learning of Non-blind Image Deblurring**

- 论文：https://arxiv.org/abs/2007.01769
- 代码：暂无（即将出来）

<a name="Deraining"></a>

# 去雨

**Rethinking Image Deraining via Rain Streaks and Vapors**

- 论文：https://arxiv.org/abs/2008.00823

- 代码：https://github.com/yluestc/derain

<a name="Image-Video-Inpainting"></a>

# 图像/视频修复(补全)

**Learning Joint Spatial-Temporal Transformations for Video Inpainting**

- 论文：https://arxiv.org/abs/2007.10247

- 代码：https://github.com/researchmm/STTN

**Rethinking Image Inpainting via a Mutual Encoder-Decoder with Feature Equalizations**

- Oral
- 论文：暂无
- 代码：https://github.com/KumapowerLIU/ECCV2020oralRethinking-Image-Inpainting-via-a-Mutual-Encoder-Decoder-with-Feature-Equalizations

 <a name="Image-Retrieval"></a>

# 图像检索

**Self-supervising Fine-grained Region Similarities for Large-scale Image Localization**

- 主页：https://yxgeee.github.io/projects/sfrs
- 论文：https://arxiv.org/abs/2006.03926

- 代码：https://github.com/yxgeee/SFRS

 <a name="Optical-Flow-Estimation"></a>

# 光流估计

**LiteFlowNet3: Resolving Correspondence Ambiguity for More Accurate Optical Flow Estimation**

- 论文：https://arxiv.org/abs/2007.09319
- 代码：https://github.com/twhui/LiteFlowNet3

<a name="Video-Interpolation"></a>

# 视频插帧

**BMBC: Bilateral Motion Estimation with Bilateral Cost Volume for Video Interpolation**

- 论文：https://arxiv.org/abs/2007.12622

- 代码：https://github.com/JunHeum/BMBC

<a name="Lane-Detection"></a>

# 车道线检测

**Ultra Fast Structure-aware Deep Lane Detection**

- 论文：https://arxiv.org/abs/2004.11757

- 代码：https://github.com/cfzd/Ultra-Fast-Lane-Detection
- 论文解读：https://mp.weixin.qq.com/s/TYzDx8R1oUbVr0FxGnFspQ

 **Gen-LaneNet: a generalized and scalable approach for 3D lane detection** 

- 论文：https://arxiv.org/abs/2003.10656
- 代码：https://github.com/yuliangguo/Pytorch_Generalized_3D_Lane_Detection
- 数据集：https://github.com/yuliangguo/3D_Lane_Synthetic_Dataset

<a name="TP"></a>

# 轨迹预测

**SimAug: Learning Robust Representations from 3D Simulation for Pedestrian Trajectory Prediction in Unseen Cameras**

- 论文：https://arxiv.org/abs/2004.02022
- 代码：https://github.com/JunweiLiang/Multiverse

<a name="Line-Detection"></a>

# 线段检测

**Deep Hough-Transform Line Priors**

- 论文：https://arxiv.org/abs/2007.09493

- 代码：https://github.com/yanconglin/Deep-Hough-Transform-Line-Priors

<a name="Eye-Tracking"></a>

# 眼动追踪

**Towards End-to-end Video-based Eye-Tracking**

- 主页：https://ait.ethz.ch/projects/2020/EVE/
- 论文：https://arxiv.org/abs/2007.13120

<a name="Datasets"></a>

# 数据集

**Component Divide-and-Conquer for Real-World Image Super-Resolution**

- 论文：https://arxiv.org/abs/2008.01928

- 代码和数据集：https://github.com/xiezw5/Component-Divide-and-Conquer-for-Real-World-Image-Super-Resolution

**Towards End-to-end Video-based Eye-Tracking**

- 主页：https://ait.ethz.ch/projects/2020/EVE/
- 论文：https://arxiv.org/abs/2007.13120

**Reconstructing NBA Players**

- 主页：http://grail.cs.washington.edu/projects/nba_players/

- 论文：https://arxiv.org/abs/2007.13303

**CelebA-Spoof: Large-Scale Face Anti-Spoofing Dataset with Rich Annotations**

- 论文：https://arxiv.org/abs/2007.12342

- 数据集：https://github.com/Davidzhangyuanhan/CelebA-Spoof

**PIoU Loss: Towards Accurate Oriented Object Detection in Complex Environments**

- 论文：https://arxiv.org/abs/2007.09584

- 代码：https://github.com/clobotics/piou

- 数据集：https://github.com/clobotics/piou

**DanbooRegion: An Illustration Region Dataset**

- 主页：https://lllyasviel.github.io/DanbooRegion/

- 论文：https://lllyasviel.github.io/DanbooRegion/paper/paper.pdf

- 数据集：https://github.com/lllyasviel/DanbooRegion

**Segment as Points for Efficient Online Multi-Object Tracking and Segmentation**

- Oral
- 论文：https://arxiv.org/abs/2007.01550
- 代码：https://github.com/detectRecog/PointTrack
- 数据集：https://github.com/detectRecog/PointTrack

 **Gen-LaneNet: a generalized and scalable approach for 3D lane detection** 

- 论文：https://arxiv.org/abs/2003.10656
- 代码：https://github.com/yuliangguo/Pytorch_Generalized_3D_Lane_Detection
- 数据集：https://github.com/yuliangguo/3D_Lane_Synthetic_Dataset

**TAO: A Large-Scale Benchmark for Tracking Any Object**

- 主页：http://taodataset.org/
- 论文：https://arxiv.org/abs/2005.10356
- 代码：https://github.com/TAO-Dataset/tao

**Structured3D: A Large Photo-realistic Dataset for Structured 3D Modeling**

- 主页：[http://structured3d-dataset.org](http://structured3d-dataset.org/)
- 论文：https://arxiv.org/abs/1908.00222
- 代码：https://github.com/bertjiazheng/Structured3D 

**AiR: Attention with Reasoning Capability**

- 论文：暂无

- 代码：https://github.com/szzexpoi/AiR
- 数据集：https://github.com/szzexpoi/AiR

<a name="Others"></a>

# 其他

**Open-Edit: Open-Domain Image Manipulation with Open-Vocabulary Instructions**

- 论文：暂无
- 代码：https://github.com/xh-liu/Open-Edit
- Video：https://youtu.be/8E3bwvjCHYE

**Consensus-Aware Visual-Semantic Embedding for Image-Text Matching**

- 论文：https://arxiv.org/abs/2007.08883
- 代码：https://github.com/BruceW91/CVSE 

**Perceiving 3D Human-Object Spatial Arrangements from a Single Image in the Wild**

- 主页：https://jasonyzhang.com/phosa/
- 论文下载：https://arxiv.org/abs/2007.15649
- 代码：https://github.com/jasonyzhang/phosa

**AiR: Attention with Reasoning Capability**

- Oral

- 论文：https://arxiv.org/abs/2007.14419

- 代码：https://github.com/szzexpoi/AiR

**Distribution-Balanced Loss for Multi-Label Classification in Long-Tailed Datasets**

- 论文：https://arxiv.org/abs/2007.09654
- 代码：https://github.com/wutong16/DistributionBalancedLoss

**A Generic Visualization Approach for Convolutional Neural Networks**

- 论文：https://arxiv.org/abs/2007.09748

- 代码：https://github.com/ahmdtaha/constrained_attention_filter

**Deep Plastic Surgery: Robust and Controllable Image Editing with Human-Drawn Sketches**

- 主页：https://williamyang1991.github.io/projects/ECCV2020
- 论文：https://arxiv.org/abs/2001.02890
- 代码：https://github.com/TAMU-VITA/DeepPS

**GIQA: Generated Image Quality Assessment**

- 论文：https://arxiv.org/abs/2003.08932
- 代码：https://github.com/cientgu/GIQA

**Structured3D: A Large Photo-realistic Dataset for Structured 3D Modeling**

- 主页：[http://structured3d-dataset.org](http://structured3d-dataset.org/)
- 论文：https://arxiv.org/abs/1908.00222
- 代码：https://github.com/bertjiazheng/Structured3D 

**AiR: Attention with Reasoning Capability**

- 论文：暂无

- 代码：https://github.com/szzexpoi/AiR
- 数据集：https://github.com/szzexpoi/AiR

**Square Attack: a query-efficient black-box adversarial attack via random search**

- 论文：https://arxiv.org/abs/1912.00049
- 代码：https://github.com/max-andr/square-attack

<a name="Not-Sure"></a>

# 不确定中没中

**Relation Aware Panoptic Segmentation**

- 论文：暂无
- 代码：https://github.com/RAPNet/RAP

**Spatial-Angular Interaction for Light Field Image Super-Resolution**

- 论文：暂无
- 代码：https://github.com/YingqianWang/LF-InterNet

**TVR: A Large-Scale Dataset for Video-Subtitle Moment Retrieval**

- 论文：https://arxiv.org/abs/2001.09099
- 代码：https://github.com/jayleicn/TVRetrieval
- 代码：https://github.com/jayleicn/TVCaption

**Self-supervising Fine-grained Region Similarities for IBL**

- 论文：暂无
- 代码： https://github.com/ID2191/ECCV2020 

https://github.com/lelechen63/eccv2020

