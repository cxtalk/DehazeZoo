# DehazeZoo (Single Image vs. Video Based)
[Xiang Chen](https://cxtalk.github.io/), Yufeng Li, Yufeng Huang

## 1 Description
   * DehazeZoo: A survey on haze removal from video and single image. Papers, codes and datasets are maintained.

   * Thanks for the sharing of [DerainZoo](https://github.com/nnUyi/DerainZoo) by [Youzhao Yang](https://github.com/nnuyi).
   
   * More details about image dehazing and deraining are available [here](https://zhuanlan.zhihu.com/dehaze-derain).

## 2 Image Quality Metrics
* PSNR (Peak Signal-to-Noise Ratio) [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4550695) [[matlab code]](https://www.mathworks.com/help/images/ref/psnr.html) [[python code]](https://github.com/aizvorski/video-quality)
* SSIM (Structural Similarity) [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1284395) [[matlab code]](http://www.cns.nyu.edu/~lcv/ssim/ssim_index.m) [[python code]](https://github.com/aizvorski/video-quality/blob/master/ssim.py)
* VIF (Visual Quality) [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1576816) [[matlab code]](http://sse.tongji.edu.cn/linzhang/IQA/Evalution_VIF/eva-VIF.htm)
* FSIM (Feature Similarity) [[paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=5705575) [[matlab code]](http://sse.tongji.edu.cn/linzhang/IQA/FSIM/FSIM.htm)
* NIQE (Naturalness Image Quality Evaluator) [[paper]](http://live.ece.utexas.edu/research/Quality/niqe_spl.pdf)[[matlab code]](http://live.ece.utexas.edu/research/Quality/index_algorithms.htm)[[python code]](https://github.com/aizvorski/video-quality/blob/master/niqe.py)

## 3 Dehazing Research
### 3.1 Datasets
------------
* KITTI [paper][[dataset](http://www.cvlibs.net/datasets/kitti/eval_depth_all.php)]
* RESIDE [[paper](https://arxiv.org/pdf/1712.04143.pdf)][[dataset](https://sites.google.com/view/reside-dehaze-datasets)]
* SceneNet [paper][[dataset](https://robotvault.bitbucket.io/scenenet-rgbd.html)]
* I-HAZE [[paper](https://data.vision.ee.ethz.ch/cvl/ntire18//o-haze/O-HAZE.pdf)][[dataset](http://www.vision.ee.ethz.ch/ntire18/i-haze/)]
* O-HAZE [[paper](https://data.vision.ee.ethz.ch/cvl/ntire18//o-haze/O-HAZE.pdf)][[dataset](http://www.vision.ee.ethz.ch/ntire18/o-haze/)]
* D-HAZY [[paper](http://www.meo.etc.upt.ro/AncutiProjectPages/D_Hazzy_ICIP2016/D_HAZY_ICIP2016.pdf)][[dataset](https://www.researchgate.net/publication/307516141_D-HAZY_A_dataset_to_evaluate_quantitatively_dehazing_algorithms)]
* Middlebury [[paper](http://www.cs.middlebury.edu/~schar/papers/datasets-gcpr2014.pdf)][[dataset](http://vision.middlebury.edu/stereo/data/scenes2014/)]
* NYU Depth Dataset V2 [[paper](https://cs.nyu.edu/~silberman/papers/indoor_seg_support.pdf)][[dataset](https://cs.nyu.edu/~silberman/datasets/nyu_depth_v2.html)]

### 3.2 Papers
--------------
### 2020
* Shen et al, Implicit Euler ODE Networks for Single-Image Dehazing. [[paper](https://arxiv.org/abs/2007.06443)][code]
* Liu et al, Efficient Unpaired Image Dehazing with Cyclic Perceptual-Depth Supervision. [[paper](https://arxiv.org/abs/2007.05220)][code]
* Li et al, You Only Look Yourself: Unsupervised and Untrained Single Image Dehazing Neural Network. [[paper](https://arxiv.org/abs/2006.16829)][code]
* Pang et al, BidNet: Binocular Image Dehazing without Explicit Disparity Estimation. (CVPR) [[paper](http://openaccess.thecvf.com/content_CVPR_2020/papers/Pang_BidNet_Binocular_Image_Dehazing_Without_Explicit_Disparity_Estimation_CVPR_2020_paper.pdf)][code]
* Sourya et al, Fast Deep Multi-patch Hierarchical Network for Nonhomogeneous Image Dehazing. [[paper](https://arxiv.org/abs/2005.05999)][code]
* Dong et al, Multi-Scale Boosted Dehazing Network with Dense Feature Fusion. (CVPR) [[paper](https://arxiv.org/abs/2004.13388)][[code](https://github.com/BookerDeWitt/MSBDN-DFF)]
* Li et al, Learning to Dehaze From Realistic Scene with A Fast Physics Based Dehazing Network. [[paper](https://arxiv.org/abs/2004.08554)][[code](https://github.com/liruoteng/3DRealisticSceneDehaze)]
* Shao et al, Domain Adaptation for Image Dehazing. (CVPR) [[paper](https://arxiv.org/abs/2005.04668)][[code](https://github.com/HUSTSYJ/DA_dahazing)][[web](https://sites.google.com/site/renwenqi888)]
* Wu et al, Accurate Transmission Estimation for Removing Haze and Noise from a Single Image. (TIP) [[paper](https://ieeexplore.ieee.org/document/8891906)][code]
* Ren et al, Single Image Dehazing via Multi-Scale Convolutional Neural Networks with Holistic Edges. (IJCV) [[paper](https://link.springer.com/article/10.1007%2Fs11263-019-01235-8)][code]
* Dong et al, FD-GAN: Generative Adversarial Networks with Fusion-discriminator for Single Image Dehazing. [[paper](https://arxiv.org/abs/2001.06968)][[code](https://github.com/WeilanAnnn/FD-GAN)]
* Qin et al, FFA-Net: Feature Fusion Attention Network for Single Image Dehazing. (AAAI) [[paper](https://arxiv.org/abs/1911.07559)][[code](https://github.com/zhilin007/FFA-Net)]

### 2019
* Wu et al, Learning Interleaved Cascade of Shrinkage Fields for Joint Image Dehazing and Denoising. (TIP) [[paper](https://ieeexplore.ieee.org/document/8852852)][code]
* Li et al, Semi-Supervised Image Dehazing. (TIP) [[paper](https://ieeexplore.ieee.org/abstract/document/8902220/)][code]
* Li et al, Benchmarking Single Image Dehazing and Beyond. (TIP) [[paper](https://arxiv.org/abs/1712.04143)][code][[web](https://sites.google.com/site/boyilics/website-builder/reside)]
* Pei et al, Classification-driven Single Image Dehazing. [[paper](https://arxiv.org/abs/1911.09389)][code]
* Liu et al, GridDehazeNet: Attention-Based Multi-Scale Network for Image Dehazing. (ICCV) [[paper](https://arxiv.org/abs/1908.03245)][[code](https://github.com/proteus1991/GridDehazeNet)]
* Li et al, Joint haze image synthesis and dehazing with mmd-vae losses. [[paper](https://arxiv.org/abs/1905.05947)][code]
* Peter et al, Feature Forwarding for Efficient Single Image Dehazing. [[paper](https://arxiv.org/abs/1904.09059)][code]
* Shu et al, Variational Regularized Transmission Refinement for Image Dehazing. [[paper](https://arxiv.org/abs/1902.07069)][code]
* Liu et al, End-to-End Single Image Fog Removal using Enhanced Cycle Consistent Adversarial Networks. [[paper](https://arxiv.org/abs/1902.01374)][code]
* Chen et al, Gated Context Aggregation Network for Image Dehazing and Deraining. (WACV) [[paper](https://arxiv.org/abs/1811.08747)][[code](https://github.com/cddlyf/GCANet)]
* Ren et al, Deep Video Dehazing with Semantic Segmentation. (TIP) [[paper](https://ieeexplore.ieee.org/document/8492451)][code]
* Jing Zhang, Dacheng Tao, FAMED-Net: A Fast and Accurate Multi-scale End-to-end Dehazing Network. (TIP) [[paper](https://arxiv.org/abs/1906.04334)][[code](https://github.com/chaimi2013/FAMED-Net)]

### 2018
* Ren et al, Gated Fusion Network for Single Image Dehazing. (CVPR) [[paper](https://arxiv.org/abs/1804.00213)][[code](https://github.com/rwenqi/GFN-dehazing)][[web](https://sites.google.com/site/renwenqi888/research/dehazing/gfn)]
* Zhang et al, FEED-Net: Fully End-To-End Dehazing. (ICME) [paper][code]
* Zhang et al, Densely Connected Pyramid Dehazing Network. (CVPR) [[paper](https://arxiv.org/abs/1803.08396)][[code](https://github.com/hezhangsprinter/DCPDN)]
* Yang et al, Towards Perceptual Image Dehazing by Physics-based Disentanglement and Adversarial Training. (AAAI) [paper][code]
* Deniz et al, Cycle-Dehaze: Enhanced CycleGAN for Single Image Dehazing. (CVPRW) [[paper](https://arxiv.org/abs/1805.05308v1)][code]

### Before
* Ren et al, An All-in-One Network for Dehazing and Beyond. (ICCV) [[paper](https://arxiv.org/pdf/1707.06543.pdf)][[code](https://github.com/MayankSingal/PyTorch-Image-Dehazing)][[web](https://sites.google.com/site/boyilics/website-builder/project-page)]
* Zhu et al, Single Image Dehazing via Multi-Scale Convolutional Neural Networks. (ECCV) [[paper](https://drive.google.com/open?id=0B7PPbXPJRQp3TUJ0VjFaU1pIa28)][[code](https://sites.google.com/site/renwenqi888/research/dehazing/mscnndehazing/MSCNN_dehazing.zip?attredirects=0&d=1)][[web](https://sites.google.com/site/renwenqi888/research/dehazing/mscnndehazing)]
* Cai et al, DehazeNet: An end-to-end system for single image haze removal. (TIP) [[paper](http://caibolun.github.io/papers/DehazeNet.pdf)][[code](https://github.com/caibolun/DehazeNet)][[web](http://caibolun.github.io/DehazeNet/)]
* Ren et al, A fast single image haze removal algorithm using color attenuation prior. (TIP) [[paper](https://ieeexplore.ieee.org/document/7128396)][code]
* He et al, Single Image Haze Removal Using Dark Channel Prior. (CVPR) [[paper](http://www.jiansun.org/papers/Dehaze_CVPR2009.pdf)][code]

## 4 Note
* The above content is constantly updated, welcome continuous attention!

## 5 Acknowledgement
* Thanks for the sharing of codes of image quality metrics by [Wang, Hong](https://github.com/hongwang01/Video-and-Single-Image-Deraining).

## 6 Contact
* If you have any question, please feel free to contact Xiang Chen (Email: cx@cvgpu.com).
