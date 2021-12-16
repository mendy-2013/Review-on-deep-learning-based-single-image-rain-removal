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
  
  Reference
  -----------
  * Single image rain streak decomposition using layer priors (TIP2017), Li et al[https://ieeexplore.ieee.org/document/7934436]
  * Joint bi-layer optimization for single-image rain streak removal (ICCV2017), Zhu et al.[https://openaccess.thecvf.com/content_iccv_2017/html/Zhu_Joint_Bi-Layer_Optimization_ICCV_2017_paper.html]
  * Joint convolutional analysis and synthesis sparse representation for single image layer separation (CVPR2017), Gu et al [https://openaccess.thecvf.com/content_iccv_2017/html/Gu_Joint_Convolutional_Analysis_ICCV_2017_paper.html]
  * Clearing the skies: A deep network architecture for single-image rain streaks removal (TIP2017), Fu et al. [https://ieeexplore.ieee.org/abstract/document/7893758]
  * Removing rain from single images via a deep detail network (CVPR2017), Fu et al. [https://openaccess.thecvf.com/content_cvpr_2017/papers/Fu_Removing_Rain_From_CVPR_2017_paper.pdf]
  * Deep joint rain detection and removal from a single image (CVPR2017), Yang et al.[https://openaccess.thecvf.com/content_cvpr_2017/papers/Yang_Deep_Joint_Rain_CVPR_2017_paper.pdf]
  * Residual guide feature fusion network for single image deraining (ACMMM2018), Fan et al.[http://export.arxiv.org/pdf/1804.07493]
  * Density-aware single image de-raining using a multi-stream dense network (CVPR2018), Zhang et al.[https://arxiv.org/abs/1802.07412]
  * Recurrent squeeze-and-excitation context aggregation net for single image deraining (ECCV2018), Li et al. [https://export.arxiv.org/pdf/1807.05698]
  * Physics-based generative adversarial models for image restoration and beyond (Arxiv2018), Pan et al.[https://arxiv.org/pdf/1808.00605.pdf]
  * Learning dual convolutional neural networks for low-level vision (CVPR2018), Pan et al.[https://arxiv.org/pdf/1805.05020.pdf]
  * Non-locally enhanced encoder-decoder network for single image de-raining (ACMMM2018), Li et al.[https://arxiv.org/pdf/1808.01491.pdf]
  * Deep Layer Prior Optimization for Single Image Rain Streaks Removal (ICASSP2018), Liu et al.[https://ieeexplore.ieee.org/document/8461892]
  * Single image rain removal via a deep decomposition-composition network (CVIU2019), Li et al.
  * Unsupervised single image deraining with self-supervised constraints (ICIP2019), Jin et al.[https://arxiv.org/pdf/1811.08575.pdf]
  * Uncertainty guided multi-scale residual learning-using a cycle spinning cnn for single image de-raining (CVPR2019), Rajeev Yasarla et al.
  * Heavy rain image restoration: Integrating physics model and conditional adversarial learning (CVPR2019), Li et al.
  * Progressive image deraining networks: A better and simpler baseline (CVPR2019), Ren et al.[https://csdwren.github.io/papers/PReNet_cvpr_camera.pdf]
  * Spatial attentive single-image deraining with a high quality real rain dataset (CVPR2019), Wang et al.[https://arxiv.org/abs/1904.01538]
  * Lightweight pyramid networks for image deraining (TNNLS2019), Fu et al.[https://arxiv.org/pdf/1805.06173.pdf]
  * Single image deraining: A comprehensive benchmark analysis(CVPR2019), Li et al.[https://arxiv.org/abs/1903.08558]
  * A Survey on Rain Removal from Video and Single Image (Arxiv2019), Wang et al.[https://arxiv.org/abs/1909.08326]
  * Semi-supervised transfer learning for image rain removal (CVPR2019), Wei et al.[http://gr.xjtu.edu.cn/c/document_library/get_file?folderId=2618027&name=DLFE-118007.pdf]
  * Joint rain detection and removal from a single image with contextualized deep networks (TPAMI2019), Yang et al.[https://ieeexplore.ieee.org/document/8627954]
  * Structural Residual Learning for Single Image Rain Removal(Arxiv2020), Wang et al.[https://arxiv.org/abs/2005.09228]
  * All in One Bad Weather Removal Using Architectural Search (CVPR2020), Li et al.[https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_All_in_One_Bad_Weather_Removal_Using_Architectural_Search_CVPR_2020_paper.pdf]
  * Syn2Real Transfer Learning for Image Deraining Using Gaussian Processes(CVPR2020), Rajeev Yasarla et al. 
  * Multi-Scale Progressive Fusion Network for Single Image Deraining(CVPR2020), Jiang et al.
  * Detail-recovery Image Deraining via Context Aggregation Networks(CVPR2020), Deng et al.
  * Variational image deraining(WACV2020), Du et al.[https://openaccess.thecvf.com/content_WACV_2020/papers/Du_Variational_Image_Deraining_WACV_2020_paper.pdf]
  * A Model-driven Deep Neural Network for Single Image Rain Removal (CVPR2020), Wang et al.[https://openaccess.thecvf.com/content_CVPR_2020/papers/Wang_A_Model-Driven_Deep_Neural_Network_for_Single_Image_Rain_Removal_CVPR_2020_paper.pdf]
  * Single image deraining: From model-based to data-driven and beyond(TPAMI2020), Yang et al.
