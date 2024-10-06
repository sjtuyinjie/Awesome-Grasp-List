# Awesome-Grasp-List

💎 Author: [**Jie Yin 殷杰**](https://github.com/sjtuyinjie)

## 📝 Introduction

**Dexterous grasping** is crucial for enabling robots to handle complex tasks that involve manipulating objects of varying shapes, sizes, and textures. The key challenge lies in achieving precise control over force and finger movements to adapt to dynamic environments, similar to how human hands work. This requires solving issues related to real-time adaptability, complex object interactions, and maintaining a stable grip without causing damage, making it one of the most technically challenging areas in robotics.

**Gripper grasping** is essential for industrial automation and repetitive tasks, where efficiency, robustness, and reliability are prioritized. While simpler in design compared to dexterous hands, gripper systems must still contend with challenges like grasping irregular or deformable objects, achieving precision with limited degrees of freedom, and maintaining adaptability in cluttered or unstructured environments. The balance between simplicity and functionality remains a significant hurdle in advancing gripper grasping technology.

Inspired by [Robotic-grasping-papers](https://github.com/rhett-chen/Robotic-grasping-papers) and [awesome-grasping](https://github.com/Po-Jen/awesome-grasping), this project aims to provide a comprehensive list of research efforts, datasets, and tools in the field of grasping, highlighting both classical approaches and the latest advancements. By making this list open-source, we encourage collaboration, community-driven improvements, and knowledge sharing to accelerate progress in this critical area of robotics. An open repository of resources ensures that cutting-edge innovations and best practices are accessible to researchers, engineers, and developers worldwide, fostering an ecosystem of transparency and continual advancement.

If you know more open-source grasp-related work, please propose an issue to remind me of updating, thanks!


## 🚩 Papers

### 🔥 Dexterous Grasping (Updating!)
- [3DV2024] ArtiGrasp: Physically Plausible Synthesis of Bi-Manual Dexterous Grasping and Articulation [[paper](https://arxiv.org/pdf/2309.03891)[[code](https://github.com/zdchan/artigrasp)]

- [AAAI2024] DexFuncGrasp: A Robotic Dexterous Functional Grasp Dataset Constructed from a Cost-Effective Real-Simulation Annotation System [[paper](https://ojs.aaai.org/index.php/AAAI/article/download/28897/29706)[[code](https://github.com/hjlllll/DexFuncGrasp)]

- [Arxiv2024] Realdex: Towards human-like grasping for robotic dexterous hand [[paper](https://arxiv.org/pdf/2402.13853)


- [Arxiv2024] Grasping Diverse Objects with Simulated Humanoids [[paper](https://arxiv.org/pdf/2407.11385)][[code](https://www.zhengyiluo.com/Omnigrasp-Site/)]
  
- [Arxiv2024] GraspXL: Generating Grasping Motions for Diverse Objects at Scale [[paper](https://arxiv.org/pdf/2403.19649)][[code](https://github.com/zdchan/GraspXL)]
  
- [ECCV2024] UGG: Unified Generative Grasping [[paper](https://arxiv.org/abs/2311.16917)][[code](https://github.com/Jiaxin-Lu/ugg)]

- [ICRA2024] Grasp-Anything: Large-scale Grasp Dataset from Foundation Models [[paper](https://arxiv.org/pdf/2309.09818)][[code](https://github.com/andvg3/Grasp-Anything)]

- [ICRA2024] ASGrasp: Generalizable Transparent Object Reconstruction and 6-DoF Grasp Detection from RGB-D Active Stereo Camera [[paper](https://arxiv.org/pdf/2405.05648)][[code](https://github.com/jun7-shi/ASGrasp)]
  
- [RAL2024] A LiDAR-inertial-visual odometry and mapping system based on the sweep reconstruction method [[paper](https://xplorestaging.ieee.org/document/10501952)][[code](https://github.com/ZikangYuan/sr_livo)]

- [TRO2023] Deep Learning Approaches to Grasp Synthesis: A Review [[paper](https://arxiv.org/pdf/2207.02556)][[website](https://rhys-newbury.github.io/projects/6dof/)]


- [IROS2023] Continuous Grasping Function [[paper](https://arxiv.org/abs/2207.05053)][[code](https://github.com/jianglongye/cgf)]

- [ICRA2023] exGraspNet: A Large-Scale Robotic Dexterous Grasp Dataset for General Objects Based on Simulation [[paper](https://ieeexplore.ieee.org/abstract/document/10404014)][[code](https://github.com/PKU-EPIC/DexGraspNet)]

- [ICRA2023] GraspNeRF: Multiview-based 6-DoF Grasp Detection for Transparent and Specular Objects Using Generalizable NeRF [[paper](https://arxiv.org/abs/2210.06575)][[code](https://github.com/PKU-EPIC/GraspNeRF)]

- [ICRA2023] Keypoint-GraspNet: Keypoint-based 6-DoF Grasp Generation from the Monocular RGB-D input [[paper](https://arxiv.org/abs/2209.08752)][[code](https://github.com/ivalab/KGN)]

- [IROS2023]  KGNv2: Separating Scale and Pose Prediction for Keypoint-based 6-DoF Grasp Synthesis on RGB-D input [[paper](https://arxiv.org/abs/2303.05617)][[code](https://github.com/ivalab/KGN)]
  
- [ICCV2023] UniDexGrasp++: Improving Dexterous Grasping Policy Learning via Geometry-aware Curriculum and Iterative Generalist-Specialist Learning [[paper](https://arxiv.org/abs/2304.00464)][[code](https://github.com/PKU-EPIC/UniDexGrasp2)]

- [CVPR2023] UniDexGrasp: Universal Robotic Dexterous Grasping via Learning Diverse Proposal Generation and Goal-Conditioned Policy [[paper](https://arxiv.org/abs/2303.00938)][[code](https://github.com/PKU-EPIC/UniDexGrasp)]

- [CORL2023] Sequential Dexterity: Chaining Dexterous Policies for Long-Horizon Manipulation [[paper](https://arxiv.org/pdf/2309.00987)][[code](https://github.com/sequential-dexterity/SeqDex)]
  
- [NeurIPS2023] Learning Score-based Grasping Primitive for Human-assisting Dexterous Grasping [[paper](https://arxiv.org/abs/2309.06038)][[code](https://github.com/tianhaowuhz/human-assisting-dex-grasp)]

- [RAL2023] Efficient Heatmap-Guided 6-Dof Grasp Detection in Cluttered Scenes [[paper](https://ieeexplore.ieee.org/document/10168242)][[code](https://github.com/THU-VCLab/HGGD)]

- [CORL2023] Geometry Matching for Multi-Embodiment Grasping [[paper](https://proceedings.mlr.press/v229/attarian23a/attarian23a.pdf)][[code](https://github.com/google-deepmind/geomatch)]

- [ECCV2022] Domain Randomization-Enhanced Depth Simulation and Restoration for Perceiving and Grasping Specular and Transparent Object [[paper](https://arxiv.org/abs/2208.03792)][[code](https://github.com/PKU-EPIC/DREDS)]

- [CORL2022] Towards Scale Balanced 6-DoF Grasp Detection in Cluttered Scenes [[paper](https://arxiv.org/pdf/2212.05275)][[code](https://github.com/mahaoxiang822/Scale-Balanced-Grasp)]

- [CORL2022] Volumetric-based Contact Point Detection for 7-DoF Grasping [[paper](https://openreview.net/pdf?id=SrSCqW4dq9)][[code](https://github.com/caijunhao/vcpd)]

- [RAL2022] DA2 Dataset: Toward Dexterity-Aware Dual-Arm Grasping [[paper](https://arxiv.org/pdf/2208.00408)][[code](https://github.com/ymxlzgy/DA2)]
  
- [ECCV2022] Domain Randomization-Enhanced Depth Simulation and Restoration for Perceiving and Grasping Specular and Transparent Object [[paper](https://arxiv.org/abs/2208.03792)][[code](https://github.com/PKU-EPIC/DREDS)]

- [RAL2021] Diverse and Physically Stable Grasps with Arbitrary Hand Structures using Differentiable Force Closure Estimation[[paper](https://arxiv.org/pdf/2104.09194)][[code](https://github.com/tengyu-liu/diverse-and-stable-grasp)]

### Gripper Grasping
- [RAL2023] Efficient Heatmap-Guided 6-Dof Grasp Detection in Cluttered Scenes [[paper](https://ieeexplore.ieee.org/document/10168242)][[code](https://github.com/THU-VCLab/HGGD)]
  
- [ICRA2023] GraspNeRF: Multiview-based 6-DoF Grasp Detection for Transparent and Specular Objects Using Generalizable NeRF [[paper](https://arxiv.org/pdf/2210.06575.pdf)][[code](https://github.com/PKU-EPIC/GraspNeRF)]

- [RAL2023] GPDAN: Grasp Pose Domain Adaptation Network for Sim-to-Real 6-DoF Object Grasping [[paper](https://ieeexplore.ieee.org/abstract/document/10153686)][[code](https://github.com/Wenxuan-1119/GPDAN)]

- [arXiv2023] Grasp-Anything: Large-scale Grasp Dataset from Foundation Models [[paper](https://arxiv.org/pdf/2309.09818.pdf)][[code](https://github.com/andvg3/Grasp-Anything)]

- [ECCV2022] Domain Randomization-Enhanced Depth Simulation and Restoration for Perceiving and Grasping Specular and Transparent Objects [[paper](https://arxiv.org/pdf/2208.03792.pdf)][[code](https://github.com/PKU-EPIC/DREDS)]

- [ECCV2022] TransGrasp: Grasp Pose Estimation of a Category of Objects by Transferring Grasps from Only One Labeled Instance [[paper](https://arxiv.org/pdf/2207.07861.pdf)][[code](https://github.com/yanjh97/TransGrasp)]

- [ICRA2022] Hybrid Physical Metric For 6-DoF Grasp Pose Detection [[paper](https://arxiv.org/pdf/2206.11141.pdf)][[code](https://github.com/luyh20/FGC-GraspNet)]

- [ICRA2022] Volumetric-based Contact Point Detection for 7-DoF Grasping [[paper](https://openreview.net/pdf?id=SrSCqW4dq9)][[code](https://github.com/caijunhao/vcpd)]

- [RA-L2022] Real-Time Collision-Free Grasp Pose Detection With Geometry-Aware Refinement Using High-Resolution Volume [[paper](https://ieeexplore.ieee.org/abstract/document/9681231)][[code](https://github.com/caijunhao/VPNet)]

- [RA-L2022] DA2 Dataset: Toward Dexterity-Aware Dual-Arm Grasping [[paper](https://arxiv.org/pdf/2208.00408.pdf)][[code](https://github.com/ymxlzgy/DA2)]

- [RA-L2022] End-to-End Learning to Grasp via Sampling From Object Point Clouds [[paper](https://arxiv.org/pdf/2203.05585.pdf)][[code](https://github.com/antoalli/L2G)]

- [RA-L2022] EfficientGrasp: A Unified Data-Efficient Learning to Grasp Method for Multi-Fingered Robot Hands [[paper](https://arxiv.org/pdf/2206.15159.pdf)][[code](https://github.com/kelinos/efficient_grasp)]

- [RA-L2022] From one hand to multiple hands: Imitation learning for dexterous manipulation from single-camera teleoperation [[paper](https://arxiv.org/pdf/2204.12490)][[code](https://github.com/yzqin/dex-hand-teleop)]


- [ICRA2021] Contact-GraspNet: Efficient 6-DoF Grasp Generation in Cluttered Scenes [[paper](https://arxiv.org/pdf/2103.14127.pdf)][[code](https://github.com/NVlabs/contact_graspnet)]

- [ICRA2021] REGNet: REgion-based Grasp Network for End-to-end Grasp Detection in Point Clouds [[paper](https://arxiv.org/pdf/2002.12647v1.pdf)][[code](https://github.com/lu-kuang/REGNet)]

- [ICRA2021] Acronym: A large-scale grasp dataset based on simulation [[paper](https://arxiv.org/pdf/2011.09584.pdf)][[code](https://github.com/NVlabs/acronym)]

- [CVPR2020] GraspNet-1Billion: A Large-Scale Benchmark for General Object Grasping [[paper](http://openaccess.thecvf.com/content_CVPR_2020/papers/Fang_GraspNet-1Billion_A_Large-Scale_Benchmark_for_General_Object_Grasping_CVPR_2020_paper.pdf)][[code](https://github.com/graspnet)]

- [CoRL2020] Volumetric Grasping Network: Real-time 6 DOF Grasp Detection in Clutter [[paper](https://arxiv.org/pdf/2101.01132.pdf)][[code](https://github.com/ethz-asl/vgn)]

- [CoRL2020] S4G: Amodal Single-view Single-Shot SE(3) Grasp Detection in Cluttered Scenes [[paper](https://arxiv.org/pdf/1910.14218.pdf)][[code](https://github.com/yzqin/s4g-release)]

- [ICRA2019] PointNetGPD: Detecting Grasp Configurations from Point Set [[paper](https://web.cs.ucla.edu/~xm/file/pointnetgpd_icra19.pdf)][[code](https://github.com/lianghongzhuo/PointNetGPD)]

- [RSS2018] Closing the Loop for Robotic Grasping: A Real-time, Generative Grasp Synthesis Approach [[paper](https://arxiv.org/pdf/1804.05172.pdf)][[code](https://github.com/dougsm/ggcnn)] 

- [ICRA2017] Dex-Net 2.0: Deep Learning to Plan Robust Grasps with Synthetic Point Clouds and Analytic Grasp Metrics [[paper](https://arxiv.org/pdf/1703.09312.pdf)][[code](https://github.com/BerkeleyAutomation/dex-net)]
  
## ⭐️ Related awesome lists

- [awesome-wheel-slam](https://github.com/sjtuyinjie/awesome-wheel-slam)
- [awesome-isaac-sim](https://github.com/sjtuyinjie/awesome-isaac-sim)
- [awesome-LiDAR-Camera-Calibration](https://github.com/Deephome/Awesome-LiDAR-Camera-Calibration)
- [awesome-SLAM](https://github.com/SilenceOverflow/Awesome-SLAM)
- [awesome-SLAM-datasets](https://github.com/youngguncho/awesome-slam-datasets)
- [Awesome-Implicit-NeRF-Robotics](https://github.com/zubair-irshad/Awesome-Implicit-NeRF-Robotics)
- [awesome-humanoid-learning](https://github.com/jonyzhang2023/awesome-humanoid-learning)
- [awesome-isaac-gym](https://github.com/wangcongrobot/awesome-isaac-gym)
- [Awesome-Quadrupedal-Robots](https://github.com/curieuxjy/Awesome_Quadrupedal_Robots)
- [Awesome-Robot-Descriptions](https://github.com/robot-descriptions/awesome-robot-descriptions)
- [awesome-legged-locomotion-learning](https://github.com/gaiyi7788/awesome-legged-locomotion-learning)

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=sjtuyinjie/Awesome-Grasp-List&type=Timeline)](https://star-history.com/#Ashutosh00710/github-readme-activity-graph&Timeline)
