# Omnidirectional/360 Degree/Panoramic Vision [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT) 

Welcome to [VLIS Lab](https://addisonwang2013.github.io/vlislab/)

This repo is a collection of AWESOME things about omnidirectional vision, including paper, code, dataset, etc. Feel free to star and fork.

# Contents

- [Survey](#Survey)
- [Theory](#Theory)
- [Image-Based Computer Vision](#Image-Based-Computer-Vision)
  - [Semantic Segmentation](#Semantic-Segmentation)
  - [Depth Estimation](#Depth-Estimation)
  - [Image Generation](#Image-Generation)
  - [Depth Completion](#Depth-Completion)
  - [Room Layout Estimation](#Room-Layout-Estimation)
  - [Image Synthesis](#Image-Synthesis)
  - [Optical Flow Estimation](#Optical-Flow-Estimation)
  - [Pose Estimation](#Pose-Estimation)
  - [Reflection Removal](#Reflection-Removal)
  - [Lighting Estimation](#Lighting-Estimation)
  - [Visual Localization](#Visual-Localization)
  - [Image Outpainting](#Image-Outpainting)
  - [Super Resolution](#Super-Resolution)
  - [Spherical Stereo Matching](#Spherical-Stereo-Matching)
  - [Inverse Rendering](#Inverse-Rendering)
- [Video-Based Computer Vision](#Video-Based-Computer-Vision)
- [Image-Based Vision with Deep Learning](#Image-Based-Vision-with-Deep-Learning)
- [Video-Based Vision with Deep Learning](#Video-Based-Vision-with-Deep-Learning)
- [Code](#Code)
- [Dataset](#Dataset)
- [Related Application](#Related-Application)
- [Forum](#Forum)


## Survey

***2022***
- Deep Learning for Omnidirectional Vision: A Survey and New Perspectives [[24 May 2022]](https://arxiv.org/abs/2205.10468)

## Theory
## Image-Based Computer Vision
### Semantic Segmentation

-Bending Reality: Distortion-Aware Transformers for Adapting to Panoramic Semantic Segmentation [[CVPR 2022]](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_Bending_Reality_Distortion-Aware_Transformers_for_Adapting_to_Panoramic_Semantic_Segmentation_CVPR_2022_paper.pdf)

### Depth Estimation

- PanoFormer: Panorama Transformer for Indoor 360° Depth Estimation [[ECCV 2022]](https://arxiv.org/abs/2203.09283)
- MODE: Multi-view Omnidirectional Depth Estimation with 360-degree Cameras [[ECCV 2022]]
- 360MonoDepth: High-Resolution 360deg Monocular Depth Estimation [[CVPR 2022]](https://openaccess.thecvf.com/content/CVPR2022/papers/Rey-Area_360MonoDepth_High-Resolution_360deg_Monocular_Depth_Estimation_CVPR_2022_paper.pdf)
- OmniFusion: 360 Monocular Depth Estimation via Geometry-Aware Fusion [[CVPR 2022]](https://openaccess.thecvf.com/content/CVPR2022/papers/Li_OmniFusion_360_Monocular_Depth_Estimation_via_Geometry-Aware_Fusion_CVPR_2022_paper.pdf)
- 
### Image Generation
- Weakly-Supervised Stitching Network for Real-World Panoramic Image Generation [[ECCV 2022]](https://arxiv.org/abs/2209.05968)
- 
### Depth Completion

- Multi-Modal Masked Pre-Training for Monocular Panoramic Depth Completion [[ECCV 2022]](https://arxiv.org/abs/2203.09855)


### Room Layout Estimation
- 3D Room Layout Estimation from a Cubemap of Panorama Image via Deep Manhattan Hough Transform [[ECCV 2022]](https://arxiv.org/abs/2207.09291)
- LGT-Net: Indoor Panoramic Room Layout Estimation With Geometry-Aware Transformer Network [[CVPR 2022]](https://openaccess.thecvf.com/content/CVPR2022/papers/Jiang_LGT-Net_Indoor_Panoramic_Room_Layout_Estimation_With_Geometry-Aware_Transformer_Network_CVPR_2022_paper.pdf)

### Scene Understanding
- DeepPanoContext: Panoramic 3D Scene Understanding with Holistic Scene Context Graph and Relation-based Optimization [[ICCV 2021]](https://openaccess.thecvf.com/content/ICCV2021/papers/Zhang_DeepPanoContext_Panoramic_3D_Scene_Understanding_With_Holistic_Scene_Context_Graph_ICCV_2021_paper.pdf)
- 


### Image Synthesis
- BIPS: Bi-modal Indoor Panorama Synthesis via Residual Depth-aided Adversarial Learning [[ECCV 2022]](https://arxiv.org/abs/2112.06179)


### Optical Flow Estimation
- Deep 360∘ Optical Flow Estimation Based on Multi-Projection Fusion [[ECCV 2022]](https://arxiv.org/abs/2208.00776)
- Learning Omnidirectional Flow in 360-degree Video via Siamese Representation [[ECCV 2022]](https://arxiv.org/abs/2208.03620)

### Pose Estimation
- CoVisPose: Co-Visibility Pose Transformer for Wide-Baseline Relative Pose Estimation in 360 Indoor Panoramas [[ECCV 2022]]

### Reflection removal
- Zero-Shot Learning for Reflection Removal of Single 360-Degree Image [[ECCV 2022]]

### Lighting Estimation
- StyleLight: HDR Panorama Generation for Lighting Estimation and Editing [[ECCV 2022]](https://arxiv.org/abs/2207.14811)

### Visual Localization
- CPO: Change Robust Panorama to Point Cloud Localization [[ECCV 2022]](https://arxiv.org/abs/2207.05317)
- PICCOLO: Point Cloud-Centric Omnidirectional Localization[[ICCV 2021]](https://openaccess.thecvf.com/content/ICCV2021/papers/Kim_PICCOLO_Point_Cloud-Centric_Omnidirectional_Localization_ICCV_2021_paper.pdf)

### Image Outpainting
- Diverse Plausible 360-Degree Image Outpainting for Efficient 3DCG Background Creation [[CVPR 2022]](https://openaccess.thecvf.com/content/CVPR2022/papers/Akimoto_Diverse_Plausible_360-Degree_Image_Outpainting_for_Efficient_3DCG_Background_Creation_CVPR_2022_paper.pdf)
- 

### Super Resolution
- SphereSR: 360deg Image Super-Resolution With Arbitrary Projection via Continuous Spherical Image Representation[[CVPR 2022]](https://openaccess.thecvf.com/content/CVPR2022/papers/Yoon_SphereSR_360deg_Image_Super-Resolution_With_Arbitrary_Projection_via_Continuous_Spherical_CVPR_2022_paper.pdf)

### Spherical Stereo Matching
- Uniform Subdivision of Omnidirectional Camera Space for Efficient Spherical Stereo Matching [[CVPR 2022]](https://openaccess.thecvf.com/content/CVPR2022/papers/Kang_Uniform_Subdivision_of_Omnidirectional_Camera_Space_for_Efficient_Spherical_Stereo_CVPR_2022_paper.pdf)


### Inverse Rendering
- PhyIR: Physics-based Inverse Rendering for Panoramic Indoor Images [[CVPR 2022]](https://openaccess.thecvf.com/content/CVPR2022/papers/Li_PhyIR_Physics-Based_Inverse_Rendering_for_Panoramic_Indoor_Images_CVPR_2022_paper.pdf)

### Gaze Following
- Looking here or there? Gaze Following in 360-Degree Images [[ICCV 2021]](https://openaccess.thecvf.com/content/ICCV2021/papers/Li_Looking_Here_or_There_Gaze_Following_in_360-Degree_Images_ICCV_2021_paper.pdf)

### Image Stitching
- Minimal Solutions for Panoramic Stitching Given Gravity Prior [[ICCV 2021]](https://openaccess.thecvf.com/content/ICCV2021/papers/Ding_Minimal_Solutions_for_Panoramic_Stitching_Given_Gravity_Prior_ICCV_2021_paper.pdf)

### Structure from Motion
- Extreme Structure from Motion for Indoor Panoramas without Visual Overlaps [[ICCV 2021]](https://openaccess.thecvf.com/content/ICCV2021/papers/Shabani_Extreme_Structure_From_Motion_for_Indoor_Panoramas_Without_Visual_Overlaps_ICCV_2021_paper.pdf)



## Video-Based Computer Vision
### Saliency Detection
- Panoramic Vision Transformer for Saliency Detection in 360 Videos [[ECCV 2022]](https://arxiv.org/abs/2209.08956)
### Audio-Visual Question Answering
- Pano-AVQA: Grounded Audio-Visual Question Answering on 360◦ Videos [[ICCV 2021]](https://openaccess.thecvf.com/content/ICCV2021/papers/Yun_Pano-AVQA_Grounded_Audio-Visual_Question_Answering_on_360deg_Videos_ICCV_2021_paper.pdf)

### Video synthesis
- Sat2Vid: Street-view Panoramic Video Synthesis from a Single Satellite Image [[ICCV 2021]](https://openaccess.thecvf.com/content/ICCV2021/papers/Li_Sat2Vid_Street-View_Panoramic_Video_Synthesis_From_a_Single_Satellite_Image_ICCV_2021_paper.pdf)

## Image-Based Vision with Deep Learning


## Video-Based Vision with Deep Learning


## Code
## Dataset
### Semantic Segmentation
- Waymo Open Dataset: Panoramic Video Panoptic Segmentation [[ECCV 2022]](https://arxiv.org/abs/2206.07704)

### Object Detection
- PANDORA: A Panoramic Detection Dataset for Object with Orientation [[ECCV 2022]]

### Audio-Visual Question Answering
- Pano-AVQA: Grounded Audio-Visual Question Answering on 360◦ Videos [[ICCV 2021]](https://openaccess.thecvf.com/content/ICCV2021/papers/Yun_Pano-AVQA_Grounded_Audio-Visual_Question_Answering_on_360deg_Videos_ICCV_2021_paper.pdf)

## Related Application
### Metaverse
### Augmented Reality
## Forum
