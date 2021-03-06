# Point-Cloud-Research
[[paper]()] [[Code]()]

# Fundamental Challenges

## Irregularity
* A mixture of dense point clouds and sparse point clouds

## Unstructured 
* Different distance between two adjacent point clouds
* (for image: ) Same distance between two adjacent pixels

## Unordered
* Order does not matter (e.g., [1,2,3] = [3,2,1])
* (for image: ) order does matter (e.g., [1,2,3] != [3,2,1])


# Recent Papers

## CVPR 2022 (For Point Cloud Registration)
* Multi-Instance Point Cloud Registration by Efficient Correspondence Clustering

* Deterministic Point Cloud Registration via Novel Transformation Decomposition

* SC2-PCR: A Second Order Spatial Compatibility for Efficient and Robust Point Cloud Registration

* Geometric Transformer for Fast and Robust Point Cloud Registration

## CVPR 2022 (For Point Cloud Segmentation)
* Contrastive Boundary Learning for Point Cloud Segmentation

* An MIL-Derived Transformer for Weakly Supervised Point Cloud Segmentation

* Pyramid Architecture for Multi-Scale Processing in Point Cloud Segmentation

* SemAffiNet: Semantic-Affine Transformation for Point Cloud Segmentation

* Stratified Transformer for 3D Point Cloud Segmentation

* HybridCR: Weakly-Supervised 3D Point Cloud Semantic Segmentation via Hybrid Contrastive Regularization

## CVPR 2022 (For Point Cloud Completion)
* AutoSDF: Shape Priors for 3D Completion, Reconstruction and Generation [[paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Mittal_AutoSDF_Shape_Priors_for_3D_Completion_Reconstruction_and_Generation_CVPR_2022_paper.pdf)] [[Code](https://github.com/yccyenchicheng/AutoSDF/)]

* ShapeFormer: Transformer-Based Shape Completion via Sparse Representation [[paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Yan_ShapeFormer_Transformer-Based_Shape_Completion_via_Sparse_Representation_CVPR_2022_paper.pdf)] [[Code](https://github.com/qheldiv/shapeformer)] 

* Learning Local Displacements for Point Cloud Completion [[paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_Learning_Local_Displacements_for_Point_Cloud_Completion_CVPR_2022_paper.pdf)] [[Code](https://github.com/wangyida/disp3d)]

* LAKe-Net: Topology-Aware Point Cloud Completion by Localizing Aligned Keypoints [[paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Tang_LAKe-Net_Topology-Aware_Point_Cloud_Completion_by_Localizing_Aligned_Keypoints_CVPR_2022_paper.pdf)]

* Learning a Structured Latent Space for Unsupervised Point Cloud Completion [[paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Cai_Learning_a_Structured_Latent_Space_for_Unsupervised_Point_Cloud_Completion_CVPR_2022_paper.pdf)]

## Arxiv 2022
* **PointAttN: You Only Need Attention for Point Cloud Completion** [[paper](https://arxiv.org/abs/2203.08485)][[Pytorch](https://github.com/ohhhyeahhh/PointAttN)] 

* PMP-Net++: Point cloud completion by transformer-enhanced multi-step point moving paths [[paper](https://arxiv.org/pdf/2202.09507v3.pdf)]

## ICLR 2022
* **A Conditional Point Diffusion-Refinement Paradigm for 3D Point Cloud Completion** [[paper](https://openreview.net/forum?id=wqD6TfbYkrn)] [[Code](https://github.com/ZhaoyangLyu/Point_Diffusion_Refinement)]

* Deep Point Cloud Reconstruction [[paper](https://openreview.net/forum?id=mKDtUtxIGJ)]

* **Rethinking Network Design and Local Geometry in Point Cloud: A Simple Residual MLP Framework** [[paper](https://openreview.net/forum?id=3Pbra-_u76D)] [[Pytorch](https://github.com/ma-xu/pointmlp-pytorch)]

## ICCV 2021
* **SnowflakeNet: Point Cloud Completion by Snowflake Point Deconvolution With Skip-Transformer** [[Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Xiang_SnowflakeNet_Point_Cloud_Completion_by_Snowflake_Point_Deconvolution_With_Skip-Transformer_ICCV_2021_paper.pdf)] [[Pytorch](https://github.com/AllenXiangX/SnowflakeNet)]
 
* RFNet: Recurrent Forward Network for Dense Point Cloud Completion [[paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Huang_RFNet_Recurrent_Forward_Network_for_Dense_Point_Cloud_Completion_ICCV_2021_paper.pdf)]

* PoinTr: Diverse Point Cloud Completion With Geometry-Aware Transformers [[paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Yu_PoinTr_Diverse_Point_Cloud_Completion_With_Geometry-Aware_Transformers_ICCV_2021_paper.pdf)]

* Voxel-based Network for Shape Completion by Leveraging Edge Generation [[paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Wang_Voxel-Based_Network_for_Shape_Completion_by_Leveraging_Edge_Generation_ICCV_2021_paper.pdf)]

* ME-PCN: Point Completion Conditioned on Mask Emptiness [[paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Gong_ME-PCN_Point_Completion_Conditioned_on_Mask_Emptiness_ICCV_2021_paper.pdf)]

* 3D Shape Generation and Completion through Point-Voxel Diffusion [[paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Zhou_3D_Shape_Generation_and_Completion_Through_Point-Voxel_Diffusion_ICCV_2021_paper.pdf)]

## CVPR 2021
* Style-Based Point Generator With Adversarial Rendering for Point Cloud Completion [[paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Xie_Style-Based_Point_Generator_With_Adversarial_Rendering_for_Point_Cloud_Completion_CVPR_2021_paper.pdf)]

* Cycle4Completion: Unpaired Point Cloud Completion Using Cycle Transformation With Missing Region Coding [[paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Wen_Cycle4Completion_Unpaired_Point_Cloud_Completion_Using_Cycle_Transformation_With_Missing_CVPR_2021_paper.pdf)]

* **PMP-Net: Point Cloud Completion by Learning Multi-Step Point Moving Paths** [[paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Wen_PMP-Net_Point_Cloud_Completion_by_Learning_Multi-Step_Point_Moving_Paths_CVPR_2021_paper.pdf)] [[Pytorch](https://github.com/diviswen/PMP-Net)]

* View-Guided Point Cloud Completion [[paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_View-Guided_Point_Cloud_Completion_CVPR_2021_paper.pdf)]

* Variational Relational Point Completion Network [[paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Pan_Variational_Relational_Point_Completion_Network_CVPR_2021_paper.pdf)]

* Denoise and Contrast for Category Agnostic Shape Completion [[paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Alliegro_Denoise_and_Contrast_for_Category_Agnostic_Shape_Completion_CVPR_2021_paper.pdf)]

* Unsupervised 3D Shape Completion through GAN Inversion [[paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_Unsupervised_3D_Shape_Completion_Through_GAN_Inversion_CVPR_2021_paper.pdf)]


# Previous Papers
* FoldingNet (CVPR 2018) [[paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Yang_FoldingNet_Point_Cloud_CVPR_2018_paper.pdf)] [[Caffe](https://www.merl.com/research/license/FoldingNet#download)]
* TopNet (CVPR 2019) [[paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Tchapmi_TopNet_Structural_Point_Cloud_Decoder_CVPR_2019_paper.pdf)] [[Pytorch](https://github.com/lynetcha/completion3d)]
* AtlasNet (CVPR 2018) [[paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Groueix_A_Papier-Mache_Approach_CVPR_2018_paper.pdf)] [[Pytorch](https://github.com/ThibaultGROUEIX/AtlasNet)]
* PCN (3DV 2018) [[paper](https://arxiv.org/pdf/1808.00671.pdf)] [[TensorFlow](https://github.com/wentaoyuan/pcn)]
* **GRNet (ECCV 2020)** [[paper](https://arxiv.org/pdf/2006.03761.pdf?ref=https://githubhelp.com)] [[Pytorch](https://github.com/hzxie/GRNet)]
* CRN (CVPR 2020) [[paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Wang_Cascaded_Refinement_Network_for_Point_Cloud_Completion_CVPR_2020_paper.pdf)] [[TensorFlow](https://github.com/xiaogangw-zz/cascaded-point-completion)]
* NSFA (ECCV 2020) [[paper](https://arxiv.org/pdf/2007.02374.pdf)] [[TensorFlow](https://github.com/XLechter/Detail-Preserved-Point-Cloud-Completion-via-SFA)]
* SoftPoolNet (ECCV 2020) [[paper](https://arxiv.org/pdf/2008.07358.pdf)] [[TensorFlow](https://github.com/wangyida/softpool)]
* SA-Net (CVPR 2020) [[paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Wen_Point_Cloud_Completion_by_Skip-Attention_Network_With_Hierarchical_Folding_CVPR_2020_paper.pdf)] [[TensorFlow](https://github.com/diviswen/sanet)]


# Categories
* Point-based methods
* Convolution-based methods
* Graph-based method
* Folding-based methods
* GAN-based methods
* Transformer-based methods
* VAE-based methods
* Other methods

# Survey
Comprehensive Review of Deep Learning-Based 3D Point Clouds Completion Processing and Analysis (arxiv 2022) [[paper](https://arxiv.org/pdf/2203.03311.pdf)]
  * Point-based methods
    * overlook geometrical neighbor information
      * lose local features
    * coarse-to-fine manner
      * coarse outputs lose high-freq. information
      * point up-sampling cannot synthesize complex topoligies
    * directly with points
      * extensive computation with large-scale data
  * Convolution-based Methods
    * ineffetive voxel or grid representation 
      * huge computation and memory requirements
    * difficult vovel or grid size selection
      * poor spatial relationship between points
  * Graph-based Methods
    * hard to define an operator for dynamic neighbors
    * hard to maintain the weight sharing of CNNs
    * spatial and geometric relationships among neighbors
  * Folding-based Methods
    * overlook the local shape charateristics within parent points
  * GAN-based Methods
    * uneven distribution for shape surface
      * unwanted holes
    * different pos. for partial input and predicted output
      * poor reconstruction
    * complicated point distribution & hard GAN training
      * small size of points
  * Transformer-based Methods
    * Huge model parameters
    * Poor model interpretablilty
* Overall future works
  * New real-world dataset
  * Dedicated architecture for feature learning
  * Corresponding loss function
  * Transformer-based methods
  * Unsupervised learning methods
  * Fast training and real-time completion

Deep Learning for 3D Point Clouds: A Survey (PAMI 2020) [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9127813)]
* 3D Shape Classification
  * Graph Convolution
* 3D Object Detection
  * Regional Proposal-based methods
  * Long-range & texture information
  * Multi-task learning
* 3D Semantic Segmentation
  * Sparse Convolution to reduce information loss and computational & memory cost
  * Point-voxel joint representation to exploit neb. information
  * Learning from imbalanced dataset
  * Segmentation of large-scale point clouds
  * Spatio-temporal information for dynamic point clouds

Review: Deep Learning on 3D Point Clouds [[paper](https://www.mdpi.com/2072-4292/12/11/1729)]

# Ideas
* Geometric Module 
* Skip-connection between encoding & decoding transformers (maybe with edge)
* Light-weight convolution layer

# Dataset
* **ShapeNet**
* ShapeNet55
* ShapeNet34
* KITTI
* ModelNet
* **Completion3D**
* MVP
* SVP

# Metrics
* L1/L2 Distance
* Chamfer Distance (CD)
* Earth Mover???s Distance (EMD)
* Fidelity Error (FD)
* Maxinum Mean Discrepancy (MMD)
* Density-aware Chamfer Distance (DCD)

# Related Resources
