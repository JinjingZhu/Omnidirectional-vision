# Omnidirectional/360 Degree/Panoramic Vision [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT) 

Welcome to [VLIS LAB](https://addisonwang2013.github.io/vlislab/)

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
  - [Scene Understanding](#Scene-Understanding)
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
  - [Gaze Following](#Gaze-Following)
  - [Image Stitching](#Image-Stitching)
  - [Structure from Motion](#Structure-from-Motion)
  - [Quality Assessment](#Quality-Assessment)
  - [Planar Reconstruction](#Planar-Reconstruction)
- [Video-Based Computer Vision](#Video-Based-Computer-Vision)
  - [Saliency Detection](#Saliency-Detection)
  - [Audio-Visual Question Answering](#Audio-Visual-Question-Answering)
  - [Video-Synthesis](#Video-Synthesis)
  - [Video Summarization](Video-Summarization)
  - [Video Compression](#Video-Compression)
  - [Audio-Visual Scene Understanding](#Audio-Visual-Scene-Understanding)
- [Image-Based Vision with Deep Learning](#Image-Based-Vision-with-Deep-Learning)
  -[Domain Adaptation](#Domain-Adaptation)
  -[Knowledge Distillation](#Knowledge-Distillation)
  -[Zero-Shot Learning](#Zero-Shot-Learning)
  -[Self-Supervised Learning](#Self-Supervised-Learning)
- [Video-Based Vision with Deep Learning](#Video-Based-Vision-with-Deep-Learning)
- [Code](#Code)
- [Dataset](#Dataset)
- [Related Application](#Related-Application)
  -[Metaverse](#Metaverse)
  -[Augmented Reality](#Augmented-Reality)
  -[Virtual Reality](#Virtual-Reality)
  -[Extended Reality](#Extended-Reality)
- [Related Scholar](#Related-Scholar)
- [Forum](#Forum)


## Survey

***2022***
- Deep Learning for Omnidirectional Vision: A Survey and New Perspectives [[24 May 2022]](https://arxiv.org/abs/2205.10468)

## Theory
## Image-Based Computer Vision
### Semantic Segmentation

- Bending Reality: Distortion-Aware Transformers for Adapting to Panoramic Semantic Segmentation [[CVPR 2022]](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_Bending_Reality_Distortion-Aware_Transformers_for_Adapting_to_Panoramic_Semantic_Segmentation_CVPR_2022_paper.pdf)
- Capturing Omni-Range Context for Omnidirectional Segmentation [[CVPR 2021]](https://openaccess.thecvf.com/content/CVPR2021/papers/Yang_Capturing_Omni-Range_Context_for_Omnidirectional_Segmentation_CVPR_2021_paper.pdf)

### Depth Estimation

- PanoFormer: Panorama Transformer for Indoor 360° Depth Estimation [[ECCV 2022]](https://arxiv.org/abs/2203.09283)[[Pytorch]](https://github.com/zhijieshen-bjtu/PanoFormer)
- MODE: Multi-view Omnidirectional Depth Estimation with 360-degree Cameras [[ECCV 2022]]
- 360MonoDepth: High-Resolution 360deg Monocular Depth Estimation [[CVPR 2022]](https://openaccess.thecvf.com/content/CVPR2022/papers/Rey-Area_360MonoDepth_High-Resolution_360deg_Monocular_Depth_Estimation_CVPR_2022_paper.pdf)
- OmniFusion: 360 Monocular Depth Estimation via Geometry-Aware Fusion [[CVPR 2022]](https://openaccess.thecvf.com/content/CVPR2022/papers/Li_OmniFusion_360_Monocular_Depth_Estimation_via_Geometry-Aware_Fusion_CVPR_2022_paper.pdf) [[Pytorch]](https://github.com/yuyanli0831/OmniFusion)
- ACDNet: Adaptively Combined Dilated Convolution for Monocular Panorama Depth Estimation [[AAAI 2022]](https://www.aaai.org/AAAI22Papers/AAAI-2064.ZhuangC.pdf)
- Improving 360 Monocular Depth Estimation via Non-Local Dense Prediction Transformer and Joint Supervised and Self-Supervised Learning [[AAAI 2022]](https://www.aaai.org/AAAI22Papers/AAAI-7522.YunI.pdf)
- SliceNet: Deep Dense Depth Estimation From a Single Indoor Panorama Using a Slice-Based Representation [[CVPR 2021]](https://openaccess.thecvf.com/content/CVPR2021/papers/Pintore_SliceNet_Deep_Dense_Depth_Estimation_From_a_Single_Indoor_Panorama_CVPR_2021_paper.pdf)
- Geometric Structure Based and Regularized Depth Estimation From 360 Indoor Imagery [[CVPR 2020]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Jin_Geometric_Structure_Based_and_Regularized_Depth_Estimation_From_360_Indoor_CVPR_2020_paper.pdf)
- BiFuse: Monocular 360 Depth Estimation via Bi-Projection Fusion [[CVPR 2020]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Wang_BiFuse_Monocular_360_Depth_Estimation_via_Bi-Projection_Fusion_CVPR_2020_paper.pdf)

 
### Image Generation
- Weakly-Supervised Stitching Network for Real-World Panoramic Image Generation [[ECCV 2022]](https://arxiv.org/abs/2209.05968)
- 
### Depth Completion

- Multi-Modal Masked Pre-Training for Monocular Panoramic Depth Completion [[ECCV 2022]](https://arxiv.org/abs/2203.09855)


### Room Layout Estimation
- 3D Room Layout Estimation from a Cubemap of Panorama Image via Deep Manhattan Hough Transform [[ECCV 2022]](https://arxiv.org/abs/2207.09291)
- LGT-Net: Indoor Panoramic Room Layout Estimation With Geometry-Aware Transformer Network [[CVPR 2022]](https://openaccess.thecvf.com/content/CVPR2022/papers/Jiang_LGT-Net_Indoor_Panoramic_Room_Layout_Estimation_With_Geometry-Aware_Transformer_Network_CVPR_2022_paper.pdf)
- Zillow Indoor Dataset: Annotated Floor Plans With 360deg Panoramas and 3D Room Layouts [[CVPR 2021]](https://openaccess.thecvf.com/content/CVPR2021/papers/Cruz_Zillow_Indoor_Dataset_Annotated_Floor_Plans_With_360deg_Panoramas_and_CVPR_2021_paper.pdf)
- SSLayout360: Semi-Supervised Indoor Layout Estimation From 360deg Panorama [[CVPR 2021]](https://openaccess.thecvf.com/content/CVPR2021/papers/Tran_SSLayout360_Semi-Supervised_Indoor_Layout_Estimation_From_360deg_Panorama_CVPR_2021_paper.pdf)

### Scene Understanding
- DeepPanoContext: Panoramic 3D Scene Understanding with Holistic Scene Context Graph and Relation-based Optimization [[ICCV 2021]](https://openaccess.thecvf.com/content/ICCV2021/papers/Zhang_DeepPanoContext_Panoramic_3D_Scene_Understanding_With_Holistic_Scene_Context_Graph_ICCV_2021_paper.pdf)
- HoHoNet: 360 Indoor Holistic Understanding With Latent Horizontal Features [[CVPR 2021]](https://openaccess.thecvf.com/content/CVPR2021/papers/Sun_HoHoNet_360_Indoor_Holistic_Understanding_With_Latent_Horizontal_Features_CVPR_2021_paper.pdf)
- LED2-Net: Monocular 360deg Layout Estimation via Differentiable Depth Rendering [[CVPR 2021]](https://openaccess.thecvf.com/content/CVPR2021/papers/Wang_LED2-Net_Monocular_360deg_Layout_Estimation_via_Differentiable_Depth_Rendering_CVPR_2021_paper.pdf)




### Image Synthesis
- BIPS: Bi-modal Indoor Panorama Synthesis via Residual Depth-aided Adversarial Learning [[ECCV 2022]](https://arxiv.org/abs/2112.06179)
- Layout-Guided Novel View Synthesis from a Single Indoor Panorama [[CVPR 2021]](https://openaccess.thecvf.com/content/CVPR2021/papers/Xu_Layout-Guided_Novel_View_Synthesis_From_a_Single_Indoor_Panorama_CVPR_2021_paper.pdf)


### Optical Flow Estimation
- Deep 360∘ Optical Flow Estimation Based on Multi-Projection Fusion [[ECCV 2022]](https://arxiv.org/abs/2208.00776)
- Learning Omnidirectional Flow in 360-degree Video via Siamese Representation [[ECCV 2022]](https://arxiv.org/abs/2208.03620)

### Pose Estimation
- CoVisPose: Co-Visibility Pose Transformer for Wide-Baseline Relative Pose Estimation in 360 Indoor Panoramas [[ECCV 2022]]

### Reflection removal
- Zero-Shot Learning for Reflection Removal of Single 360-Degree Image [[ECCV 2022]]
- Panoramic Image Reflection Removal [[CVPR 2021]](https://openaccess.thecvf.com/content/CVPR2021/papers/Hong_Panoramic_Image_Reflection_Removal_CVPR_2021_paper.pdf)

### Lighting Estimation
- StyleLight: HDR Panorama Generation for Lighting Estimation and Editing [[ECCV 2022]](https://arxiv.org/abs/2207.14811)
- Lighting, Reflectance and Geometry Estimation From 360deg Panoramic Stereo [[CVPR 2021]](https://openaccess.thecvf.com/content/CVPR2021/papers/Li_Lighting_Reflectance_and_Geometry_Estimation_From_360deg_Panoramic_Stereo_CVPR_2021_paper.pdf )

### Visual Localization
- CPO: Change Robust Panorama to Point Cloud Localization [[ECCV 2022]](https://arxiv.org/abs/2207.05317)
- PICCOLO: Point Cloud-Centric Omnidirectional Localization[[ICCV 2021]](https://openaccess.thecvf.com/content/ICCV2021/papers/Kim_PICCOLO_Point_Cloud-Centric_Omnidirectional_Localization_ICCV_2021_paper.pdf)

### Image Outpainting
- Diverse Plausible 360-Degree Image Outpainting for Efficient 3DCG Background Creation [[CVPR 2022]](https://openaccess.thecvf.com/content/CVPR2022/papers/Akimoto_Diverse_Plausible_360-Degree_Image_Outpainting_for_Efficient_3DCG_Background_Creation_CVPR_2022_paper.pdf)
- 

### Super Resolution
- SphereSR: 360deg Image Super-Resolution With Arbitrary Projection via Continuous Spherical Image Representation[[CVPR 2022]](https://openaccess.thecvf.com/content/CVPR2022/papers/Yoon_SphereSR_360deg_Image_Super-Resolution_With_Arbitrary_Projection_via_Continuous_Spherical_CVPR_2022_paper.pdf)

- LAU-Net: Latitude Adaptive Upscaling Network for Omnidirectional Image Super-Resolution [[CVPR 2021]](https://openaccess.thecvf.com/content/CVPR2021/papers/Deng_LAU-Net_Latitude_Adaptive_Upscaling_Network_for_Omnidirectional_Image_Super-Resolution_CVPR_2021_paper.pdf)

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

### Quality Assessment 
- Perceptual Quality Assessment of Omnidirectional Images [[AAAI 2022]](https://www.aaai.org/AAAI22Papers/AAAI-4008.FangY.pdf)

### Planar Reconstruction
- Indoor Panorama Planar 3D Reconstruction via Divide and Conquer [[CVPR 2021]](https://openaccess.thecvf.com/content/CVPR2021/papers/Sun_Indoor_Panorama_Planar_3D_Reconstruction_via_Divide_and_Conquer_CVPR_2021_paper.pdf)


## Video-Based Computer Vision
### Saliency Detection
- Panoramic Vision Transformer for Saliency Detection in 360 Videos [[ECCV 2022]](https://arxiv.org/abs/2209.08956)
### Audio-Visual Question Answering
- Pano-AVQA: Grounded Audio-Visual Question Answering on 360◦ Videos [[ICCV 2021]](https://openaccess.thecvf.com/content/ICCV2021/papers/Yun_Pano-AVQA_Grounded_Audio-Visual_Question_Answering_on_360deg_Videos_ICCV_2021_paper.pdf)

### Video Synthesis
- Sat2Vid: Street-view Panoramic Video Synthesis from a Single Satellite Image [[ICCV 2021]](https://openaccess.thecvf.com/content/ICCV2021/papers/Li_Sat2Vid_Street-View_Panoramic_Video_Synthesis_From_a_Single_Satellite_Image_ICCV_2021_paper.pdf)

### Video Summarization

### Video Compression


## Image-Based Vision with Deep Learning


## Video-Based Vision with Deep Learning


## Code
## Dataset
### Semantic Segmentation
- Waymo Open Dataset: Panoramic Video Panoptic Segmentation [[ECCV 2022]](https://arxiv.org/abs/2206.07704)

### Layout Estimation
- Zillow Indoor Dataset: Annotated Floor Plans With 360deg Panoramas and 3D Room Layouts [[CVPR 2021]](https://openaccess.thecvf.com/content/CVPR2021/papers/Cruz_Zillow_Indoor_Dataset_Annotated_Floor_Plans_With_360deg_Panoramas_and_CVPR_2021_paper.pdf)


### Object Detection
- PANDORA: A Panoramic Detection Dataset for Object with Orientation [[ECCV 2022]]

### Audio-Visual Question Answering
- Pano-AVQA: Grounded Audio-Visual Question Answering on 360◦ Videos [[ICCV 2021]](https://openaccess.thecvf.com/content/ICCV2021/papers/Yun_Pano-AVQA_Grounded_Audio-Visual_Question_Answering_on_360deg_Videos_ICCV_2021_paper.pdf)


### Planar Reconstruction
- Indoor Panorama Planar 3D Reconstruction via Divide and Conquer [[CVPR 2021]](https://openaccess.thecvf.com/content/CVPR2021/papers/Sun_Indoor_Panorama_Planar_3D_Reconstruction_via_Divide_and_Conquer_CVPR_2021_paper.pdf)

## Related Application
### Metaverse
### Augmented Reality
### Virtual Reality
### Extended Reality
## Related Scholar
- [Addison Lin Wang](https://addisonwang2013.github.io/vlislab/linwang.html) is an Assistant Professor in the Artificial Intelligence (AI) Thrust of Information Hub and an Affiliate Assistant Professor in the Department of Computer Science and Engineering, the Hong Kong University of Science and Technology (HKUST). He is leadning Visual Learning and Intelligent Systems (VLIS) LAB @ HKUST, GZ Campus.
## Forum
