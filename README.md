# Amazing Equivariance Learning

 Mathematically equivariance is defined as a form of symmetry for functions from one space with symmetry to another. When deep neural networks meet with equivariance, we either design or learn DNNs that are equivariant to transformation applied to the input like permutating, shifting, rotating, and etc. A broad range of CV/ML tasks are targeted at learning equivariant transformations, such as 2D flow estimation, 6D pose estimation, tracking, or to get robust estimations despite transformations to the input, like segmentation, classification, shape reconstruction. Equivariance learning brings new magic to the training process with less examples and faster convergence, and sometimes it even loose the requirement on creating GT labels, especially for current explorations on SSL.
## Contents
 - [Theories](#Theories)
 - [Backbones](#Backbones)
 - [Applications](#Applications)
 - [Resources](#Resources)
   - [Tutorials](#resources--tutorials)
   - [Videos](#resources-videos)

\* indicates equal contribution
## Theories
<!-- ##### • \[2021 ICCV\](https://arxiv.org/abs/2109.14744) The Object at Hand: Automated Editing for Mixed Reality Video Guidance from Hand-Object Interactions. [\[PDF\]](https://arxiv.org/pdf/2109.14744)
_Yao Lu, Walterio W. Mayol-Cuevas_ -->

## Backbones
##### • \[2019 NeuIPS\](https://arxiv.org/pdf/2104.12229.pdf) General E(2)-Equivariant Steerable CNNs. [\[PDF\]](https://arxiv.org/pdf/1911.08251.pdf)
_Maurice Weiler, Gabriele Cesa_

##### • \[2021 ICCV\](https://arxiv.org/pdf/2104.12229.pdf) Vector Neurons: A General Framework for SO(3)-Equivariant Networks. [\[PDF\]](https://arxiv.org/pdf/2109.14744)
_Yao Lu, Walterio W. Mayol-Cuevas_

##### • \[2021 ICCV\](https://arxiv.org/pdf/2104.12229.pdf) Vector Neurons: A General Framework for SO(3)-Equivariant Networks. [\[PDF\]](https://arxiv.org/pdf/2109.14744)
_Yao Lu, Walterio W. Mayol-Cuevas_


## Applications
##### • \[2020 AAAI\] Exploiting Spatial Invariance for Scalable Unsupervised Object Tracking. [\[PDF\]](https://arxiv.org/pdf/2109.14744)
_Eric Crawford, Joelle Pineau_

##### • \[2021 NeurIPS\] Sparse Steerable Convolutions: An Efficient Learning of SE(3)-Equivariant Features for Estimation and Tracking of Object Poses in 3D Space [\[PDF\]](https://papers.nips.cc/paper/2021/file/8c1b6fa97c4288a4514365198566c6fa-Paper.pdf) [\[Code\]](https://github.com/Gorilla-Lab-SCUT/SS-Conv)
_Jiehong Lin, Hongyang Li, Ke Chen, Jiangbo Lu, and Kui Jia_

##### • \[2021 NeurIPS\] Leveraging SE(3) Equivariance for Self-Supervised Category-Level Object Pose Estimation [\[PDF\]](http://arxiv.org/abs/2111.00190) [\[Code\]](https://github.com/dragonlong/equi-pose)
_Xiaolong Li, Yijia Weng, Li Yi, Leonidas Guibas, A. Lynn Abbott, Shuran Song, He Wang_
