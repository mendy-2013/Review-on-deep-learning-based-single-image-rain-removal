 Review on deep learning based single image rain removal
 =======================================================
 Datasets experiments
 --------------------
    Select the follow six methods(code links have been attached), train on Rain100H, Rain100L, Rain800, Rain1400, and test on the real rain image dataset SPA-Data.
    
  *    Clearing the skies: A deep network architecture for single-image rain streaks removal (TIP2017), Fu et al.[https://xueyangfu.github.io/]  
  *  Removing rain from single images via a deep detail network (CVPR2017), Fu et al.[https://xueyangfu.github.io/]
   * Residual-Guide Network for Single Image Deraining(ACMMM2018)，Fan et al.[https://xmu-smartdsp.github.io/]  
   * Recurrent squeeze-and-excitation context aggregation net for single image deraining (ECCV2018), Li et al. [https://github.com/XiaLiPKU/RESCAN]  
   * Semi-supervised transfer learning for image rain removal(CVPR2019),Wei et al.[https://github.com/wwzjer/Semi- supervised- IRR] 
   *   From rain removal to rain generation(CVPR2020),Wang et al.[https://github.com/hongwang01/VRGNet]  


  Algorithm experiments
  ---------------------
      Choose the following methods (code links have been attached), train and test on Rain100H, Rain100L, Raindrop, Rain800, and use the trained model to test on the real rain image, and compare the average PSNR and SSIM values.
  *  Deep joint rain detection and removal from a single image. (CVPR2017)，Yang, Wenhan et al.[https://github.com/flyywh/]
  * Attentive generative adversarial network for raindrop removal from a single image (CVPR2018), Qian et al.[https://github.com/MaybeShewill-CV/attentive-gan-derainnet]
  *  Density-aware Single Image De-raining using a Multi-stream Dense Network. (CVPR2018),Zhang et al.[https://github.com/hezhangsprinter/]
  *   Lightweight Pyramid Networks for Image Deraining. (TNNLS2019),Fu et al.[https://xueyangfu.github.io/projects/LPNet.html]
  *   Progressive Image Deraining Networks: A Better and Simpler Baseline.Ren et al.(CVPR2019),[https://github.com/csdwren/PReNet]
  *  Semi-supervised Transfer Learning for Image Rain Removal. (CVPR2019),Wei et al.[https://github.com/wwzjer/Semi-supervised-IRR]
  *  Dual Residual Networks Leveraging the Potential of Paired Operations for Image Restoration.(CVPR2019),Liu et al.[https://github.com/liu-vis/DualResidualNetworks]  
  *   Multi-Scale Progressive Fusion Network for Single Image Deraining.(CVPR2020),Jiang et al.[https://github.com/kuijiang0802/MSPFN]
  *   DCSFN: Deep Cross-scale Fusion Network for Single Image Rain Removal. (ACMMM2020),Wang et al.[https://github.com/Ohraincu/DCSFN]
  *    A Model-driven Deep Neural Network for Single Image Rain Removal. (CVPR2020),Wang et al.[https://github.com/hongwang01/RCDNet]
  *   Rain Streak Removal via Dual Graph Convolutional Network. (AAAI2021), Fu et al.[https://fuxueyang.github.io] 
  *   From Rain Generation to Rain Removal. (CVPR2021),Wang et al. [https://github.com/hongwang01/VRGNet]
  *  Successive Graph Convolutional Network for Image De-raining.(ICCV2021),Fu et al.[https://fuxueyang.github.io] 
 
 Datasets
 --------
 * Rain100H[https://github.com/hongwang01/Video-and-Single-Image-Deraining]
  * Rain100L[https://github.com/hongwang01/RCDNet]
  * Rain800[https://github.com/hezhangsprinter/ID-CGAN],
  * Rain1400[https://xueyangfu.github.io/]
  * SPA-Data[https://stevewongv.github.io/derainproject.html]
  * Internet-Data[https://github.com/wwzjer/Semi-supervised-IRR/tree/master/data/rainy_image_dataset/real_input]
  
  Image Quality Metrics
  ---------
  * PSNR (Peak Signal-to-Noise Ratio)[https://github.com/aizvorski/video-quality]
  * SSIM (Structural Similarity)[https://github.com/aizvorski/video-quality/blob/master/ssim.py]
    
