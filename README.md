# Awesome 3D Reconstruction Papers
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A collection of 3D reconstruction papers in the deep learning era. Feel free to contribute :)

Table of Contents
=================

  * [Object-level](#object-level)
     * [Single-view](#single-view)
     * [Multi-view](#multi-view)
  * [Scene-level](#scene-level)
     * [Single-view](#single-view-1)
     * [Multi-view](#multi-view-1)
  * [Survey](#survey)

## Object-level

### Single-view

| Paper | Representation| Publisher | Project/Code |
| :----------------------------------------------------------: | :-------: | :-------: | :-----------------------------------------------------: |
| [Perspective Transformer Nets: Learning Single-View 3D Object Reconstruction without 3D Supervision](https://proceedings.neurips.cc/paper/2016/hash/e820a45f1dfc7b95282d10b6087e11c0-Abstract.html) | Voxel | NIPS 2016 |      [[Code]](https://github.com/xcyan/nips16_PTN)      |
| [A Point Set Generation Network for 3D Object Reconstruction from a Single Image](https://openaccess.thecvf.com/content_cvpr_2017/html/Fan_A_Point_Set_CVPR_2017_paper.html) | Point Cloud | CVPR 2017 | [[Code]](https://github.com/fanhqme/PointSetGeneration) |
| [SurfNet: Generating 3D Shape Surfaces Using Deep Residual Networks](https://openaccess.thecvf.com/content_cvpr_2017/html/Sinha_SurfNet_Generating_3D_CVPR_2017_paper.html) | Mesh | CVPR 2017 | [[Code]](https://github.com/sinhayan/surfnet) |
| [Multi-View Supervision for Single-View Reconstruction via Differentiable Ray Consistency](https://openaccess.thecvf.com/content_cvpr_2017/html/Tulsiani_Multi-View_Supervision_for_CVPR_2017_paper.html) | Voxel | CVPR 2017 | [[Project]](https://shubhtuls.github.io/drc/) |
| [OctNet: Learning Deep 3D Representations at High Resolutions](https://openaccess.thecvf.com/content_cvpr_2017/html/Riegler_OctNet_Learning_Deep_CVPR_2017_paper.html) | Voxel | CVPR 2017 | [[Code]](https://github.com/griegler/octnet) |
| [Rethinking Reprojection: Closing the Loop for Pose-Aware Shape Reconstruction From a Single Image](https://openaccess.thecvf.com/content_iccv_2017/html/Zhu_Rethinking_Reprojection_Closing_ICCV_2017_paper.html) | Voxel | ICCV 2017 | / |
| [MarrNet: 3D Shape Reconstruction via 2.5D Sketches](https://proceedings.neurips.cc/paper/2017/hash/ad972f10e0800b49d76fed33a21f6698-Abstract.html) | Voxel | NIPS 2017 | [[Project]](http://marrnet.csail.mit.edu/) |
| [Hierarchical Surface Prediction for 3D Object Reconstruction](https://arxiv.org/abs/1704.00710) | Voxel | 3DV 2017 | / |
| [Image2Mesh: A Learning Framework for Single Image 3D Reconstruction](https://arxiv.org/abs/1711.10669) | Mesh | ACCV 2018 | [[Code]](https://github.com/jhonykaesemodel/image2mesh) |
| [Learning Efficient Point CloudGeneration for Dense 3D Object Reconstruction](https://aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16530) | Point Cloud | AAAI 2018 | [[Project]](https://chenhsuanlin.bitbucket.io/3D-point-cloud-generation/) |
| [A Papier-Mâché Approach to Learning 3D Surface Generation](https://openaccess.thecvf.com/content_cvpr_2018/html/Groueix_A_Papier-Mache_Approach_CVPR_2018_paper.html) | Mesh | CVPR 2018 | [[Project]](http://imagine.enpc.fr/~groueixt/atlasnet/) |
| [Im2Struct: Recovering 3D Shape Structure From a Single RGB Image](https://openaccess.thecvf.com/content_cvpr_2018/html/Niu_Im2Struct_Recovering_3D_CVPR_2018_paper.html) | Parts | CVPR 2018 | [[Code]](https://github.com/chengjieniu/Im2Struct) |
| [Matryoshka Networks: Predicting 3D Geometry via Nested Shape Layers](https://openaccess.thecvf.com/content_cvpr_2018/html/Richter_Matryoshka_Networks_Predicting_CVPR_2018_paper.html) | Voxel | CVPR 2018 | [[Code]](https://bitbucket.org/visinf/projects-2018-matryoshka/src/master/) |
| [Multi-View Consistency as Supervisory Signal for Learning Shape and Pose Prediction](https://openaccess.thecvf.com/content_cvpr_2018/html/Tulsiani_Multi-View_Consistency_as_CVPR_2018_paper.html) | Voxel | CVPR 2018 | [[Project]](https://shubhtuls.github.io/mvcSnP/) |
| [Efficient Dense Point Cloud Object Reconstruction using Deformation Vector Fields](https://openaccess.thecvf.com/content_ECCV_2018/html/Kejie_Li_Efficient_Dense_Point_ECCV_2018_paper.html) | Point Cloud | ECCV 2018 | / |
| [GAL: Geometric Adversarial Loss for Single-View 3D-Object Reconstruction](https://openaccess.thecvf.com/content_ECCV_2018/html/Li_Jiang_GAL_Geometric_Adversarial_ECCV_2018_paper.html) | Point Cloud | ECCV 2018 | / |
| [Learning Category-Specific Mesh Reconstruction from Image Collections](https://openaccess.thecvf.com/content_ECCV_2018/html/Angjoo_Kanazawa_Learning_Category-Specific_Mesh_ECCV_2018_paper.html) | Mesh | ECCV 2018 | [[Project]](https://akanazawa.github.io/cmr/) |
| [Learning Shape Priors for Single-View 3D Completion and Reconstruction](https://openaccess.thecvf.com/content_ECCV_2018/html/Jiajun_Wu_Learning_3D_Shape_ECCV_2018_paper.html) | Voxel | ECCV 2018 | / |
| [Learning Single-View 3D Reconstruction with Limited Pose Supervision](https://openaccess.thecvf.com/content_ECCV_2018/html/Guandao_Yang_A_Unified_Framework_ECCV_2018_paper.html) | Voxel | ECCV 2018 | [[Code]](https://github.com/stevenygd/3d-recon) |
| [Pixel2Mesh: Generating 3D Mesh Models from Single RGB Images](https://openaccess.thecvf.com/content_ECCV_2018/html/Nanyang_Wang_Pixel2Mesh_Generating_3D_ECCV_2018_paper.html) | Mesh | ECCV 2018 | [[Code]](https://github.com/nywang16/Pixel2Mesh) |
| [Residual MeshNet: Learning to Deform Meshes for Single-View 3D Reconstruction](https://ieeexplore.ieee.org/abstract/document/8491025) | Mesh | 3DV 2018 | / |
| [Learning to Reconstruct Shapes from Unseen Classes](https://proceedings.neurips.cc/paper/2018/hash/208e43f0e45c4c78cafadb83d2888cb6-Abstract.html) | Generic | NIPS 2018 | / |
| [Multi-View Silhouette and Depth Decomposition for High Resolution 3D Object Representation](https://proceedings.neurips.cc/paper/2018/hash/39ae2ed11b14a4ccb41d35e9d1ba5d11-Abstract.html) | Voxel | NIPS 2018 | [[Code]](https://github.com/EdwardSmith1884/Multi-View-Silhouette-and-Depth-Decomposition-for-High-Resolution-3D-Object-Representation) |
| [MVPNet: Multi-View Point Regression Networks for 3D Object Reconstruction from A Single Image](https://ojs.aaai.org/index.php/AAAI/article/view/4923) | Point Cloud | AAAI 2019 | / |
| [Deep Single-View 3D Object Reconstruction with Visual Hull Embedding](https://ojs.aaai.org//index.php/AAAI/article/view/4922) | Voxel | AAAI 2019 | [[Code]](https://github.com/HanqingWangAI/PSVH-3d-reconstruction) |
| [Occupancy Networks: Learning 3D Reconstruction in Function Space](https://openaccess.thecvf.com/content_CVPR_2019/html/Mescheder_Occupancy_Networks_Learning_3D_Reconstruction_in_Function_Space_CVPR_2019_paper.html) | Implicit | CVPR 2019 | [[Code]](https://github.com/autonomousvision/occupancy_networks) |
| [Learning Implicit Fields for Generative Shape Modeling](https://openaccess.thecvf.com/content_CVPR_2019/html/Chen_Learning_Implicit_Fields_for_Generative_Shape_Modeling_CVPR_2019_paper.html) | Implicit | CVPR 2019 | [[Project]](https://www.sfu.ca/~zhiqinc/imgan/Readme.html) |
| [A Skeleton-Bridged Deep Learning Approach for Generating Meshes of Complex Topologies From Single RGB Images](https://openaccess.thecvf.com/content_CVPR_2019/html/Tang_A_Skeleton-Bridged_Deep_Learning_Approach_for_Generating_Meshes_of_Complex_CVPR_2019_paper.html) | Mesh | CVPR 2019 | [[Code]](https://github.com/tangjiapeng/SkeletonBridgeRecon) |
| [What Do Single-view 3D Reconstruction Networks Learn?](https://openaccess.thecvf.com/content_CVPR_2019/html/Tatarchenko_What_Do_Single-View_3D_Reconstruction_Networks_Learn_CVPR_2019_paper.html) | Generic | CVPR 2019 | [[Code]](https://github.com/lmb-freiburg/what3d) |
| [DeepSDF: Learning Continuous Signed Distance Functions for Shape Representation](https://openaccess.thecvf.com/content_CVPR_2019/html/Park_DeepSDF_Learning_Continuous_Signed_Distance_Functions_for_Shape_Representation_CVPR_2019_paper.html) | Implicit | CVPR 2019 | [[Code]](https://github.com/alexeybokhovkin/DeepSDF) |
| [Deep Level Sets: Implicit Surface Representations for 3D Shape Inference](https://arxiv.org/abs/1901.06802) | Implicit | Arxiv 2019 | / |
| [Deep Mesh Reconstruction From Single RGB Images via Topology Modification Networks](https://openaccess.thecvf.com/content_ICCV_2019/html/Pan_Deep_Mesh_Reconstruction_From_Single_RGB_Images_via_Topology_Modification_ICCV_2019_paper.html) | Mesh | ICCV 2019 | [[Code]](https://github.com/jnypan/TMNet) |
| [GraphX-Convolution for Point Cloud Deformation in 2D-to-3D Conversion](https://openaccess.thecvf.com/content_ICCV_2019/html/Nguyen_GraphX-Convolution_for_Point_Cloud_Deformation_in_2D-to-3D_Conversion_ICCV_2019_paper.html) | Point Cloud | ICCV 2019 | [[Code]](https://github.com/ywcmaike/pcdnet) |
| [Learning Shape Templates With Structured Implicit Functions](https://openaccess.thecvf.com/content_ICCV_2019/html/Genova_Learning_Shape_Templates_With_Structured_Implicit_Functions_ICCV_2019_paper.html) | Implicit | ICCV 2019 | [[Code]](https://github.com/google/ldif) |
| [Pix2Vox: Context-Aware 3D Reconstruction From Single and Multi-View Images](https://openaccess.thecvf.com/content_ICCV_2019/html/Xie_Pix2Vox_Context-Aware_3D_Reconstruction_From_Single_and_Multi-View_Images_ICCV_2019_paper.html) | Voxel | ICCV 2019 | [[Code]](https://github.com/hzxie/Pix2Vox) |
| [Domain-Adaptive Single-View 3D Reconstruction](https://openaccess.thecvf.com/content_ICCV_2019/html/Pinheiro_Domain-Adaptive_Single-View_3D_Reconstruction_ICCV_2019_paper.html) | Voxel | ICCV 2019 | [[Code]](https://github.com/Gitikameher/Domain-Adaptive-Single-View-3D-Reconstruction) |
| [DISN: Deep Implicit Surface Network for High-quality Single-view 3D Reconstruction](https://proceedings.neurips.cc/paper/2019/hash/39059724f73a9969845dfe4146c5660e-Abstract.html) | Implicit | NIPS 2019 | [[Code]](https://github.com/laughtervv/DISN) |
| [Front2Back: Single View 3D Shape Reconstruction via Front to Back Prediction](https://openaccess.thecvf.com/content_CVPR_2020/html/Yao_Front2Back_Single_View_3D_Shape_Reconstruction_via_Front_to_Back_CVPR_2020_paper.html) | Mesh | CVPR 2020 | [[Code]](https://github.com/rozentill/Front2Back) |
| [Local Deep Implicit Functions for 3D Shape](https://openaccess.thecvf.com/content_CVPR_2020/html/Genova_Local_Deep_Implicit_Functions_for_3D_Shape_CVPR_2020_paper.html) | Implicit | CVPR 2020 | [[Code]](https://github.com/google/ldif) |
| [Differentiable Volumetric Rendering: Learning Implicit 3D Representations Without 3D Supervision](https://openaccess.thecvf.com/content_CVPR_2020/html/Niemeyer_Differentiable_Volumetric_Rendering_Learning_Implicit_3D_Representations_Without_3D_Supervision_CVPR_2020_paper.html) | Implicit | CVPR 2020 | [[Project]](https://avg.is.tuebingen.mpg.de/publications/niemeyer2020cvpr) |
| [BSP-Net: Generating Compact Meshes via Binary Space Partitioning](https://openaccess.thecvf.com/content_CVPR_2020/html/Chen_BSP-Net_Generating_Compact_Meshes_via_Binary_Space_Partitioning_CVPR_2020_paper.html) | Mesh | CVPR 2020 | [[Project]](https://bsp-net.github.io/) |
| [Height and Uprightness Invariance for 3D Prediction From a Single View](https://openaccess.thecvf.com/content_CVPR_2020/html/Baradad_Height_and_Uprightness_Invariance_for_3D_Prediction_From_a_Single_CVPR_2020_paper.html) | Point Cloud | CVPR 2020 | [[Code]](https://github.com/mbaradad/im2pcl) |
| [Implicit Functions in Feature Space for 3D Shape Reconstruction and Completion](https://openaccess.thecvf.com/content_CVPR_2020/html/Chibane_Implicit_Functions_in_Feature_Space_for_3D_Shape_Reconstruction_and_CVPR_2020_paper.html) | Implicit | CVPR 2020 | [[Project]](https://virtualhumans.mpi-inf.mpg.de/ifnets/) |
| [Unsupervised Learning of Probably Symmetric Deformable 3D Objects From Images in the Wild](https://openaccess.thecvf.com/content_CVPR_2020/html/Wu_Unsupervised_Learning_of_Probably_Symmetric_Deformable_3D_Objects_From_Images_CVPR_2020_paper.html) | Mesh | CVPR 2020 | [[Project]](https://www.robots.ox.ac.uk/~vgg/blog/unsupervised-learning-of-probably-symmetric-deformable-3d-objects-from-images-in-the-wild.html?image=004_face&type=human) |
| [Deep Local Shapes: Learning Local SDF Priors for Detailed 3D Reconstruction](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/6873_ECCV_2020_paper.php) | Implicit | ECCV 2020 | / |
| [Few-Shot Single-View 3-D Object Reconstruction with Compositional Priors](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123700613.pdf) | Voxel | ECCV 2020 | [[Code]](https://github.com/JeremyFisher/few_shot_3dr) |
| [GSIR: Generalizable 3D Shape Interpretation and Reconstruction](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/1955_ECCV_2020_paper.php) | Voxel | ECCV 2020 | / |
| [DR-KFS: A Differentiable Visual Similarity Metric for 3D Shape Reconstruction](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660290.pdf) | Mesh | ECCV 2020 | / |
| [Self-supervised Single-view 3D Reconstruction via Semantic Consistency](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123590664.pdf) | Mesh | ECCV 2020 | [[Project]](https://sites.google.com/nvidia.com/unsup-mesh-2020) |
| [Shape and Viewpoint without Keypoints](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123600086.pdf) | Mesh | ECCV 2020 | [[Project]](https://shubham-goel.github.io/ucmr/) |
| [Ladybird: Quasi-Monte Carlo Sampling for Deep Implicit Field Based 3D Reconstruction with Symmetry](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123460239.pdf) | Mesh | ECCV 2020 | [[Code]](https://github.com/FuxiCV/Ladybird) |
| [Learning to Detect 3D Reflection Symmetry for Single-View Reconstruction](https://arxiv.org/abs/2006.10042) | / | Arxiv 2020 | [[Code]](https://github.com/zhou13/symmetrynet) |
| [3D Reconstruction of Novel Object Shapes from Single Images](https://arxiv.org/abs/2006.07752) | Implicit | Arxiv 2020 | [[Project]](https://devlearning-gt.github.io/3DShapeGen/) |
| [3D Shape Reconstruction from Free-Hand Sketches](https://arxiv.org/abs/2006.09694) | Point Cloud | Arxiv 2020 | [[Code]](https://github.com/samaonline/3D-Shape-Reconstruction-from-Free-Hand-Sketches) |
| [Implicit Mesh Reconstruction from Unannotated Image Collections](https://arxiv.org/abs/2007.08504) | Mesh | Arxiv 2020 | [[Project]](https://shubhtuls.github.io/imr/) |
| [SkeletonNet: A Topology-Preserving Solution for Learning Mesh Reconstruction of Object Surfaces from RGB Images](https://arxiv.org/abs/2008.05742) | Mesh | Arxiv 2020 | [[Code]](https://github.com/tangjiapeng/SkeletonNet) |
| [MeshSDF: Differentiable Iso-Surface Extraction](https://papers.nips.cc/paper/2020/hash/fe40fb944ee700392ed51bfe84dd4e3d-Abstract.html) | Implicit | NIPS 2020 | [[Code]](https://github.com/cvlab-epfl/MeshSDF) |
| [Learning Deformable Tetrahedral Meshes for 3D Reconstruction](https://proceedings.neurips.cc//paper/2020/file/7137debd45ae4d0ab9aa953017286b20-Paper.pdf) | Mesh | NIPS 2020 | [[Project]](https://nv-tlabs.github.io/DefTet/) |
| [MetaSDF: Meta-learning Signed Distance Functions](https://proceedings.neurips.cc//paper/2020/file/731c83db8d2ff01bdc000083fd3c3740-Paper.pdf) | Implicit | NIPS 2020 | [[Project]](https://vsitzmann.github.io/metasdf/) |
| [SDF-SRN: Learning Signed Distance 3D Object Reconstruction from Static Images](https://papers.nips.cc/paper/2020/file/83fa5a432ae55c253d0e60dbfa716723-Paper.pdf) | Implicit | NIPS 2020 | [[Project]](https://chenhsuanlin.bitbucket.io/signed-distance-SRN/) |
| [UCLID-Net: Single View Reconstruction in Object Space](https://papers.nips.cc/paper/2020/hash/21327ba33b3689e713cdff1641128004-Abstract.html) | Mesh | NIPS 2020 | [[Code]](https://github.com/cvlab-epfl/UCLID-Net) |
| [Pix2Vox++: Multi-scale Context-aware 3D Object Reconstruction from Single and Multiple Images](https://arxiv.org/abs/2006.12250) | Voxel | IJCV 2020 | [[Code]](https://gitlab.com/hzxie/Pix2Vox) |
| [Silhouette Guided Point Cloud Reconstruction beyond Occlusion](https://openaccess.thecvf.com/content_WACV_2020/html/Zou_Silhouette_Guided_Point_Cloud_Reconstruction_beyond_Occlusion_WACV_2020_paper.html) | Point Cloud | WACV 2020 | [[Code]](https://github.com/zouchuhang/Silhouette-Guided-3D) |
| [Look, Cast and Mold: Learning 3D Shape Manifold from Single-view Synthetic Data](https://arxiv.org/abs/2103.04789) | Voxel | Arxiv 2021 | / |

### Multi-view

|                            Paper                             | Representation | Publisher |                         Project/Code                         |
| :----------------------------------------------------------: | :------------: | :-------: | :----------------------------------------------------------: |
| [3D-R2N2: A Unified Approach for Single and Multi-view 3D Object Reconstruction](https://arxiv.org/abs/1604.00449) |     Voxel      | ECCV 2016 |        [[Code]](https://github.com/chrischoy/3D-R2N2)        |
| [3D Shape Induction from 2D Views of Multiple Objects](https://arxiv.org/abs/1612.05872) |     Voxel      | 3DV 2017  |      [[Code]](https://github.com/matheusgadelha/PrGAN)       |
| [Learning Efficient Point Cloud Generation for Dense 3D Object Reconstruction](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/download/16530/16302) |  Point Cloud   | AAAI 2018 | [[Project]](https://chenhsuanlin.bitbucket.io/3D-point-cloud-generation/) |
| [Conditional Single-view Shape Generation for Multi-view Stereo Reconstruction](https://openaccess.thecvf.com/content_CVPR_2019/html/Wei_Conditional_Single-View_Shape_Generation_for_Multi-View_Stereo_Reconstruction_CVPR_2019_paper.html) |  Point Cloud   | CVPR 2019 |      [[Code]](https://github.com/weiyithu/OptimizeMVS)       |
| [Pixel2Mesh++: Multi-View 3D Mesh Generation via Deformation](https://openaccess.thecvf.com/content_ICCV_2019/html/Wen_Pixel2Mesh_Multi-View_3D_Mesh_Generation_via_Deformation_ICCV_2019_paper.html) |      Mesh      | ICCV 2019 |  [[Project]](https://walsvid.github.io/Pixel2MeshPlusPlus/)  |
| [Multiview Aggregation for Learning Category-Specific Shape Reconstruction](https://papers.nips.cc/paper/8506-multiview-aggregation-for-learning-category-specific-shape-reconstruction.pdf) |  Point Cloud   | NIPS 2019 |     [[Code]](https://github.com/drsrinathsridhar/xnocs)      |
| [Multiview Neural Surface Reconstruction by Disentangling Geometry and Appearance](https://papers.nips.cc/paper/2020/hash/1a77befc3b608d6ed363567685f70e1e-Abstract.html) |      Mesh      | NIPS 2020 |        [[Project]](https://lioryariv.github.io/idr/)         |

## Scene-level

### Single-view
|                            Paper                             | Representation | Publisher |                         Project/Code                         |
| :----------------------------------------------------------: | :------------: | :-------: | :----------------------------------------------------------: |
| [IM2CAD](https://openaccess.thecvf.com/content_cvpr_2017/html/Izadinia_IM2CAD_CVPR_2017_paper.html) |      CAD       | CVPR 2017 |         [[Code]](https://github.com/yyong119/IM2CAD)         |
| [3D-RCNN: Instance-level 3D Object Reconstruction via Render-and-Compare](https://openaccess.thecvf.com/content_cvpr_2018/html/Kundu_3D-RCNN_Instance-Level_3D_CVPR_2018_paper.html) |     Priors     | CVPR 2018 |   [[Project]](https://abhijitkundu.info/projects/3D-RCNN/)   |
| [Factoring Shape, Pose, and Layout from the 2D Image of a 3D Scene](https://openaccess.thecvf.com/content_cvpr_2018/html/Tulsiani_Factoring_Shape_Pose_CVPR_2018_paper.html) |     Voxel      | CVPR 2018 |     [[Project]](https://shubhtuls.github.io/factored3d/)     |
| [Holistic 3D Scene Parsing and Reconstruction from a Single RGB Image](https://openaccess.thecvf.com/content_ECCV_2018/html/Siyuan_Huang_Monocular_Scene_Parsing_ECCV_2018_paper.html) |      CAD       | ECCV 2018 | [[Project]](https://siyuanhuang.com/holistic_parsing/main.html) |
| [Mesh R-CNN](https://openaccess.thecvf.com/content_ICCV_2019/html/Gkioxari_Mesh_R-CNN_ICCV_2019_paper.html) |      Mesh      | ICCV 2019 |    [[Code]](https://github.com/facebookresearch/meshrcnn)    |
| [3D Scene Reconstruction With Multi-Layer Depth and Epipolar Transformers](https://openaccess.thecvf.com/content_ICCV_2019/html/Shin_3D_Scene_Reconstruction_With_Multi-Layer_Depth_and_Epipolar_Transformers_ICCV_2019_paper.html) |      Mesh      | ICCV 2019 | [[Project]](https://research.dshin.org/iccv19/multi-layer-depth) |
| [3D-RelNet: Joint Object and Relational Network for 3D Prediction](https://openaccess.thecvf.com/content_ICCV_2019/html/Kulkarni_3D-RelNet_Joint_Object_and_Relational_Network_for_3D_Prediction_ICCV_2019_paper.html) |     Voxel      | ICCV 2019 |  [[Project]](https://nileshkulkarni.github.io/relative3d/)   |
| [Total3DUnderstanding: Joint Layout, Object Pose and Mesh Reconstruction for Indoor Scenes from a Single Image](https://openaccess.thecvf.com/content_CVPR_2020/html/Nie_Total3DUnderstanding_Joint_Layout_Object_Pose_and_Mesh_Reconstruction_for_Indoor_CVPR_2020_paper.html) |      Mesh      | CVPR 2020 |       [[Project]](https://yinyunie.github.io/Total3D/)       |
| [3D Scene Reconstruction from a Single Viewport](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123670052.pdf) |     Voxel      | ECCV 2020 | [[Code]](https://github.com/DLR-RM/SingleViewReconstruction) |
| [CoReNet: Coherent 3D scene reconstruction from a single RGB image](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123470358.pdf) | Voxel+Implicit | ECCV 2020 |     [[Code]](https://github.com/google-research/corenet)     |
| [Image-to-Voxel Model Translation for 3D Scene Reconstruction and Segmentation](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123520103.pdf) |     Voxel      | ECCV 2020 |           [[Code]](https://github.com/vlkniaz/SSZ)           |
| [Holistic 3D Scene Understanding from a Single Image with Implicit Representation](https://arxiv.org/abs/2103.06422) |    Implicit    | CVPR 2021 |  [[Project]](https://chengzhag.github.io/publication/im3d/)  |

### Multi-view

|                            Paper                             | Representation | Publisher |                         Project/Code                         |
| :----------------------------------------------------------: | :------------: | :-------: | :----------------------------------------------------------: |
| [MARMVS: Matching Ambiguity Reduced Multiple View Stereo for Efficient Large Scale Scene Reconstruction](https://openaccess.thecvf.com/content_CVPR_2020/html/Xu_MARMVS_Matching_Ambiguity_Reduced_Multiple_View_Stereo_for_Efficient_Large_CVPR_2020_paper.html) | Point Cloud    | CVPR 2020 | /                                                      |
| [Associative3D: Volumetric Reconstruction from Sparse Views](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123600137.pdf) | Voxel          | ECCV 2020 | [[Project]](https://jasonqsy.github.io/Associative3D/) |
| [Atlas: End-to-End 3D Scene Reconstruction from Posed Images](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123520409.pdf) | Mesh           | ECCV 2020 | [[Project]](http://zak.murez.com/atlas/)               |
| [NeuralRecon: Real-Time Coherent 3D Reconstruction from Monocular Video](https://arxiv.org/abs/2104.00681) | Mesh           | CVPR 2021 | [[Project]](https://zju3dv.github.io/neuralrecon/)     |

## Survey

|                            Paper                             | Publisher  |
| :--------------------------------------------------------------------: | :--------: |
| [Image-based 3D Object Reconstruction: State-of-the-Art and Trends in the Deep Learning Era](https://arxiv.org/abs/1906.06543) | TPAMI 2019 |
