---
layout: post
title: "Self-Supervised Learning"
date: 2023-01-09T14:13:42+01:00
author: "ABDALLAH YOUBI IDRISSI"
description: "A type of machine learning in which an algorithm learns to perform a task without being explicitly given labels or examples of the task."
tags: ["Self-Supervised Learning"]
---

## Courses

- [CSCI 601.771: Self-supervised Statistical Models](https://self-supervised.cs.jhu.edu/fa2022/index.html) - [Spring 2023](https://self-supervised.cs.jhu.edu/sp2023/)
- CIS 620 - Learning in Few-Labels Settings - [Website](https://www.seas.upenn.edu/~cis6200/)
- COMP 152 Machine Learning with Limited Annotation - [Website](https://berthuang.com/courses/limited21/)
- [Self-Supervised Learning by Anuj shah](https://www.youtube.com/playlist?list=PLd9i_xMMzZF7QiPZNF7zblpTksTt0DDy6)
- [Joint Embedding Methods - NYU Deep Learning SP22](https://www.youtube.com/playlist?list=PLLHTzKZzVU9f3kmEta5dlkMXgtD1LxHzT) and [Lecture Notes](https://atcold.github.io/NYU-DLSP21/en/week15/15/)

## Energy Based Models and Energy-Based Self-Supervised Learning

- Theory and Application of Energy-Based Generative Models, CVPR 2021 Tutorial - [Website](https://energy-based-models.github.io/#Topics) and [Lectures](https://www.youtube.com/playlist?list=PLR5rf_74feHp-VUvA83j9h0muFR7Wnz4r)
- Collection of research materials on EBM/EBL (Energy Based Models, Energy Based Learning) - [GitHub repo](https://github.com/yataobian/awesome-ebm)
- Chunpai Wang notes:
  - [Energy and Probability](https://chunpai.github.io/assets/note/Energy_and_Probability.pdf)
  - [Boltzmann Machines](https://chunpai.github.io/assets/note/Boltzmann_Machines.pdf)
  - [Training and Inference](https://chunpai.github.io/assets/note/EBM_3__Non_probabilistic_Energy_Based_Learning.pdf)
- [The Physics of Energy-Based Models](https://physicsofebm.github.io/)
- [A Tutorial on Energy-Based Learning](http://yann.lecun.com/exdb/publis/pdf/lecun-06.pdf)
- [How to Train Your Energy-Based Models by Yang Song, Diederik P. Kingma](https://arxiv.org/abs/2101.03288)
- [Boltzmann machines and energy-based models by Takayuki Osogami](https://arxiv.org/abs/1708.06008)
- [Concept Learning with Energy-Based Models](https://arxiv.org/pdf/1811.02486.pdf) and [OpenAI Blog Post](https://openai.com/blog/learning-concepts-with-energy-functions/) and [Yannic's Explanation](https://www.youtube.com/watch?v=Cs_j-oNwGgg)
- [Flow Contrastive Estimation of Energy-Based Models](https://arxiv.org/abs/1912.00589)
- [Learning Latent Space Energy-Based Prior Model](https://arxiv.org/pdf/2006.08205.pdf)
- [Divergence Triangle for Joint Training of Generator Model, Energy-based Model, and Inference Model](https://arxiv.org/pdf/1812.10907.pdf)
- [Joint Training of Variational Auto-Encoder and Latent Energy-Based Model](https://arxiv.org/pdf/2006.06059.pdf)
- [Conjugate Energy-Based Models](https://arxiv.org/abs/2106.13798)
- [Guiding Energy-based Models via Contrastive Latent Variables](https://sslneurips22.github.io/paper_pdfs/paper_49.pdf)

- Alfredo Canziani Lectures:
  - Energy-Based Self-Supervised Learning - [Lecture](https://www.youtube.com/watch?v=bDvpuaPq8Vc)
  - [Joint Embedding Methods (JEMs) NYU Deep Learning SP22](https://www.youtube.com/playlist?list=PLLHTzKZzVU9f3kmEta5dlkMXgtD1LxHzT)
  - [NYU Deep Learning FL22](https://www.youtube.com/playlist?list=PLLHTzKZzVU9d_3TcHbyiAjl5qCbpJR-o0)
  - NYU Deep Learning SP21 - [Website](https://atcold.github.io/NYU-DLSP21/) and [Lectures](https://www.youtube.com/playlist?list=PLLHTzKZzVU9e6xUfG10TkTWApKSZCzuBI)

- Yann LeCun Talks:
  - [ICLR 2020: Energy-Based Models](https://www.youtube.com/watch?v=piaPIKO1MFY)
  - [The future is self-supervised](https://iclr.cc/virtual_2020/speaker_7.html)
  - [Energy-Based Models for Self-Supervised Learning](https://www.youtube.com/watch?v=BqgnnrojVBI)
  - [The Energy-Based Learning Model](https://www.youtube.com/watch?v=4lthJd3DNTM)
  - [Summer school on Statistical Physics & Machine learning: From machine learning to autonomous intelligence](https://leshouches2022.github.io/) and [Youtube Playlist](https://www.youtube.com/playlist?list=PLEIq5bchE3R3Yl5taXdYA04a9kH9yvyGm)

## Visual Representation Learning and Joint Embedding Methods

Visual Representation Learning trains a system to produce the representations required for feature detection or classification from raw data. Visual Representation Learning is about the representations of images or videos in particular. Self-supervised Visual Representation Learning, can be classified into Generative models, Pretext Tasks and Joint Embedding methods. In generative models, you train the model to reconstruct the original image from the noisy image. In pretext tasks, you train the model to figure out a smart way to generate pseudo labels. Joint Embedding Methods try to make their backbone network robust to certain distortions and are invariant to data augmentation.
The pretext task is a self-supervised learning task solved to learn visual representations, with the aim of using the learned representations or model weights obtained in the process, for other downstream tasks. The pretext task is usually performed on a property that is inherent in the dataset itself.

Energy Based Models can be classified into Generative or Joint Embedding based on architectures, and into Contrastive or "Architectural & Regularised" based on training methods. The contrastive methods differ in the way they pick the points to push up. While the architectural methods differ in the way they limit the volume of low energy.

Joint Embedding Methods (JEMs) training methods can be classified into four types: Contrastive Methods, Non-contrastive Methods, Clustering Methods and Other Methods.

Contrastive Methods push positive pairs closer and negative pairs away. Contrastive methods include MoCo, PIRL, and SimCLR. There are other Contrastive Methods such as Contrastive Divergence (or Persistent Contrastive Divergence), Ratio Matching, Noise Contrastive Estimation, and Minimum Probability Flow. Contrastive Methods can be further classified in this way:

- Push Up Everywhere (Maximum Likelihood) - This category includes methods that aim to push the representations of all data points as far apart as possible.
- Push Up at Locations (ML with MCMC Methods, Siamese Neural Networks (MoCo, PIRL, SimCLR), GAN) - This category includes methods that push the representations of certain data points further apart than others. An example of this is the Siamese network, where two versions of the same network are used to process two different data points, and the distance between their representations is minimized for similar data points and maximized for dissimilar data points.
- Off-manifold to on-manifold (Denoising and Masked AE (BERT)) - This category includes methods that learn to denoise or recover the original data from a corrupted or masked version.

Architectural & Regularised (Non-contrastive) Methods can classified into:

- Upper-bound low energy volume (PCA, K-means, GMM) - This category includes methods that aim to find a low-dimensional representation of the data by looking for a subspace that captures the most variation in the data, while keeping the energy of the representation low.
- Regularization term (Sparse & Contractive AE, LISTA, BYOL, VicReg) - This category includes methods that add a regularization term to the objective function of the model, which encourage certain properties of the learned representation, such as sparsity or contractiveness.
- Minimise gradient, Maximise curvature (Score Matching)

Non-contrastive methods are based on Information Theory and don’t require special architectures or engineering techniques, for example Barlow Twins and VicReg.

Clustering Methods prevent trivial solution by quantizing the embedding space. Clustering Methods include ClusterFit, SwAV, DeepCluster, ProPos, CC and PCL. Other Methods are local and don’t create problem with distributed training unlike previous methods. Examples are Dino, BYOL, SimSiam and Data2Vec.

Another classification is the following:

- Instance Discrimination (MoCo, SimCLR, BYOL)
- Clustering and Classification (SwAV, DeepCluster)
- Others (Solving Jigsaw, Rotation, ReSort, LocationPrediction,GAN)

Sparse Coding is a Regularized Latent Variable Energy Based Model (FISTA, LISTA are algorithms that optimizes the sparse coding energy function.).

## Blog Posts

- [Self-supervised learning: The dark matter of intelligence](https://ai.facebook.com/blog/self-supervised-learning-the-dark-matter-of-intelligence/) and [Yannic Kilcher Explanation](https://www.youtube.com/watch?v=Ag1bw8MfHGQ)
- [Self-Supervised Representation Learning](https://lilianweng.github.io/posts/2019-11-10-self-supervised/)
- [A curated list of awesome self-supervised methods](https://github.com/jason718/awesome-self-supervised-learning)
- [The Illustrated Self-Supervised Learning](https://amitness.com/2020/02/illustrated-self-supervised-learning/)
- [Contrastive Representation Learning](https://lilianweng.github.io/posts/2021-05-31-contrastive/)
- [Contrastive Self-Supervised Learning](https://ankeshanand.com/blog/2020/01/26/contrative-self-supervised-learning.html)
- [Self-Supervised Learning (SSL) Overview](https://towardsdatascience.com/self-supervised-learning-ssl-overview-8a7f24740e40)

## Papers

- [A Path Towards Autonomous Machine Intelligence](https://openreview.net/pdf?id=BZ5a1r-kVsf), [Talk](https://www.youtube.com/watch?v=VRzvpV9DZ8Y&t=16s), [Blog Post](https://ai.facebook.com/blog/yann-lecun-advances-in-ai-research/) and [Yannic Kilcher Explanation](https://www.youtube.com/watch?v=jSdHmImyUjk)

- Self-Supervised Learning Theory:
  - [What Do We Maximize in Self-Supervised Learning?](https://arxiv.org/abs/2207.10081)
  - [Energy-Based Contrastive Learning of Visual Representations](https://arxiv.org/abs/2202.04933)
  - [On the duality between contrastive and non-contrastive self-supervised learning](https://arxiv.org/abs/2206.02574)
  - [Contrastive Representation Learning: A Framework and Review](https://arxiv.org/abs/2010.05113)
  - [Contrastive and Non-Contrastive Self-Supervised Learning Recover Global and Local Spectral Embedding Methods](https://arxiv.org/abs/2205.11508) and [Appendix](https://openreview.net/attachment?id=jQgsZDspz5h&name=supplementary_material)
  - [Joint Embedding Self-Supervised Learning in the Kernel Regime](https://arxiv.org/abs/2209.14884)
  - [Demystifying Self-Supervised Learning: An Information-Theoretical Framework](https://arxiv.org/abs/2006.05576)
  - [Self-supervised Learning: Generative or Contrastive](https://arxiv.org/abs/2006.08218)
  - [Towards the Generalization of Contrastive Self-Supervised Learning](https://arxiv.org/abs/2111.00743)

- Self-Supervised Learning Methods:
  - [JEPA: Joint Embedding Predictive Architectures Focus on Slow Features](https://arxiv.org/abs/2211.10831)
  - [IFM: Can contrastive learning avoid shortcut solutions?](https://arxiv.org/abs/2106.11230)
  - [SimCLR: A Simple Framework for Contrastive Learning of Visual Representations](https://arxiv.org/abs/2002.05709)
  - [VICREG: VARIANCE-INVARIANCE-COVARIANCE RE- GULARIZATION FOR SELF-SUPERVISED LEARNING](https://arxiv.org/abs/2105.04906)
  - [SwAV: Unsupervised Learning of Visual Features by Contrasting Cluster Assignments](https://arxiv.org/abs/2006.09882)
  - [DeepCluster: Deep Clustering for Unsupervised Learning of Visual Features](https://arxiv.org/abs/1807.05520)
  - [Moco: Momentum Contrast for Unsupervised Visual Representation Learning](https://arxiv.org/abs/1911.05722)
  - [PIRL: Self-Supervised Learning of Pretext-Invariant Representations](https://arxiv.org/abs/1912.01991)
  - [ClusterFit: Improving Generalization of Visual Representations](https://arxiv.org/abs/1912.03330)
  - [Barlow Twins: Self-Supervised Learning via Redundancy Reduction](https://arxiv.org/abs/2103.03230)
  - [W-MSE: Whitening for Self-Supervised Representation Learning](https://arxiv.org/abs/2007.06346)
  - [TiCo: Transformation Invariance and Covariance Contrast for Self-Supervised Visual Representation Learning](https://arxiv.org/abs/2206.10698)
  - [SimSiam: Exploring Simple Siamese Representation Learning](https://arxiv.org/abs/2011.10566)
  - [ProPos: Learning Representation for Clustering via Prototype Scattering and Positive Sampling](https://arxiv.org/abs/2111.11821)
  - [CC: Contrastive Clustering](https://arxiv.org/abs/2009.09687)
  - [BYOL: Bootstrap your own latent: A new approach to self-supervised Learning](https://arxiv.org/abs/2006.07733)
  - [PCL: Prototypical Contrastive Learning of Unsupervised Representations](https://arxiv.org/abs/2005.04966)
  - [Dino: Emerging Properties in Self-Supervised Vision Transformers](https://arxiv.org/abs/2104.14294)
  - [Data2vec: A General Framework for Self-supervised Learning in Speech, Vision and Language](https://arxiv.org/abs/2202.03555)
  - [RankMe: Assessing the downstream performance of pretrained self-supervised representations by their rank](https://arxiv.org/abs/2210.02885)
  - [VICRegL: Self-Supervised Learning of Local Visual Features](https://arxiv.org/abs/2210.01571)
  - [RPC: Self-supervised Representation Learning with Relative Predictive Coding](https://arxiv.org/abs/2103.11275)
  - [CPC: Representation Learning with Contrastive Predictive Coding](https://arxiv.org/abs/1807.03748)
  - [VCReg: Variance Covariance Regularization Enforces Pairwise Independence in Self-Supervised Representations](https://arxiv.org/abs/2209.14905)
  - [DCL: Decoupled Contrastive Learning](https://arxiv.org/abs/2110.06848)
  - [DirectCLR: Understanding Dimensional Collapse in Contrastive Self-supervised Learning](https://arxiv.org/abs/2110.09348)

## Libraries

- [A library for state-of-the-art self-supervised learning from images](https://vissl.ai/)
