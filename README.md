# awesome-UAV-vision

## 国内外从事相关工作的实验室
- 【同济大学】https://vision4robotics.github.io/ 【无人机单目标跟踪】
## detection

### 数据集
|      Source      |                            Paper                             | Code |    Note    |
| :--------------: | :----------------------------------------------------------: | :--: | :--------: |
|arXiv22|[HIT-UAV: A High-altitude Infrared Thermal Dataset for Unmanned Aerial Vehicles](https://arxiv.org/abs/2204.03245)|https://github.com/suojiashun/HIT-UAV-Infrared-Thermal-Dataset|8位红外数据|
### 论文
|      Source      |                            Paper                             | Code |    Note    |
| :--------------: | :----------------------------------------------------------: | :--: | :--------: |
|arXiv23|[Cascaded Zoom-in Detector for High Resolution Aerial Images](https://arxiv.org/pdf/2303.08747)|-|裁剪|
|      arXiv23       | [Confidence-driven Bounding Box Localization for Small Object Detection](https://arxiv.org/abs/2303.01803) |  -   | 小目标检测 |
| 中国图像图形学报23 | [无人机视角下的目标检测研究进展](http://www.cjig.cn/jig/ch/reader/view_abstract.aspx?flag=2&file_no=202208160000003&journal_id=jig) |  -   |    综述    |
|  ICIP22  | [Slicing Aided Hyper Inference and Fine-tuning for Small Object Detection](https://arxiv.org/abs/2202.06934) |            https://github.com/obss/sahi            | 高分辨率切图工具SAHI |
| TCSVT22  | [Pareto Refocusing for Drone-view Object Detection](https://ieeexplore.ieee.org/document/9905640) |                         -                          |         裁剪         |
|  CVPR22  | [QueryDet: Cascaded Sparse Query for Accelerating High-Resolution Small Object Detection](https://arxiv.org/abs/2103.09136) | https://github.com/ChenhongyiYang/QueryDet-PyTorch |                      |
|   PR22   | [mSODANet: A network for multi-scale object detection in aerial images using hierarchical dilated convolutions](https://www.sciencedirect.com/science/article/pii/S0031320322000292) |                         -                          |                      |
| arXiv22  | [Fewer is More: Efficient Object Detection in Large Aerial Images](https://arxiv.org/abs/2212.13136) |          https://github.com/Ranchosky/OAN          |         裁剪         |
|  CVPR21  | [Detection, Tracking, and Counting Meets Drones in Crowds: A Benchmark](https://arxiv.org/abs/2105.02440) |                    -                    |      |
| ICCVW21  | [VistrongerDet: Stronger Visual Information for Object Detection in VisDrone Images](https://ieeexplore.ieee.org/document/9607555) |                    -                    |      |
| ICCVW21  | [Coarse-grained Density Map Guided Object Detection in Aerial Images](https://ieeexplore.ieee.org/document/9607840) |                    -                    | 裁剪 |
| ICCVW21  | [TPH-YOLOv5: Improved YOLOv5 Based on Transformer Prediction Head for Object Detection on Drone-captured Scenarios](https://arxiv.org/abs/2108.11539) | https://github.com/cv516Buaa/tph-yolov5 |      |
| ICCVW21  | [ViT-YOLO:Transformer-Based YOLO for Object Detection](https://ieeexplore.ieee.org/document/9607536) |                                         |      |
|  WACV21  | [Towards Resolving the Challenge of Long-tail Distribution in UAV Images for Object Detection](https://ieeexplore.ieee.org/document/9423170) |   https://github.com/we1pingyu/DSHNet   |      |
|  ICME21  | [HRDNet: High-Resolution Detection Network for Small Objects](https://arxiv.org/abs/2006.07607) |                    -                    |      |
|  ECCV20  | [Object Detection Using Clustering Algorithm Adaptive Searching Regions in Aerial Images](https://link.springer.com/chapter/10.1007/978-3-030-66823-5_39)     |                 -                  |                                 |
|  TIP20   | [A Global-Local Self-Adaptive Network for Drone-View Object Detection](https://ieeexplore.ieee.org/document/9305976) | https://github.com/dengsutao/glsan | <font color=#ffb5b3>裁剪</font> |
| CVPRW20  | [Density Map Guided Object Detection in Aerial Images](https://arxiv.org/abs/2004.05520) |                 -                  |              裁剪               |
| ICCVW20  | [Spatial Attention for Multi-Scale Feature Refinement for Object Detection](https://openaccess.thecvf.com/content_ICCVW_2019/papers/VISDrone/Wang_Spatial_Attention_for_Multi-Scale_Feature_Refinement_for_Object_Detection_ICCVW_2019_paper.pdf) |                              -                               |      |
| ICCVW20  | [How to Fully Exploit The Abilities of Aerial Image Detectors](https://ieeexplore.ieee.org/document/9022557) |                              -                               | 裁剪 |
| CVPRW20  | [[The Power of Tiling for Small Object Detection](https://ieeexplore.ieee.org/document/9025422)](https://ieeexplore.ieee.org/document/9022557) |                              -                               | 裁剪 |
| TCSVT19  | [Small Object Detection in Unmanned Aerial Vehicle Images Using Feature Fusion and Scaling-Based Single Shot Detector With Spatial Context Analysis](https://ieeexplore.ieee.org/document/8672115) |                              -                               |      |
|  TIE19   | [Simultaneously Detecting and Counting Dense Vehicles From Drone Images](https://ieeexplore.ieee.org/document/8648370) |                              -                               |      |
|  ICCV19  | **[Clustered Object Detection in Aerial Images](https://arxiv.org/abs/1904.08008)** | https://github.com/fyangneil/Clustered-Object-Detection-in-Aerial-Image | 裁剪 |
|  TGRS19  | [R2-CNN: Fast Tiny Object Detection in Large-Scale Remote Sensing Images](https://arxiv.org/abs/1902.06042) |                              -                               | 遥感 |
|  TGRS19  | [Hierarchical and Robust Convolutional Neural Network for Very High-Resolution Remote Sensing Object Detection](https://ieeexplore.ieee.org/document/8676107) |                              -                               | 遥感 |
|  GRSL18  | [Multiscale Visual Attention Networks for Object Detection in VHR Remote Sensing Images](https://ieeexplore.ieee.org/document/8513990) |  -   | 遥感 |
|  TGRS17  | [Accurate Object Localization in Remote Sensing Images Based on Convolutional Neural Networks](https://ieeexplore.ieee.org/document/7827088) |  -   | 遥感 |
|  TIP17   | [Random Access Memories: A New Paradigm for Target Detection in High Resolution Aerial Remote Sensing Images](https://ieeexplore.ieee.org/document/8106808) |  -   | 遥感 |
|  ACCV16  | [R-CNN for Small Object Detection](https://link.springer.com/chapter/10.1007/978-3-319-54193-8_14) |  -   | 小目标检测 |  

### 其他可借鉴

| Source |                            Paper                             | Code | Note |
| :----: | :----------------------------------------------------------: | :--: | :--: |
| CVPR18 | [Dynamic Zoom-in Network for Fast Object Detection in Large Images](https://arxiv.org/abs/1711.05187) |  -   |      |
| CVPR16 | [Adaptive Object Detection Using Adjacency and Zoom Prediction](https://arxiv.org/abs/1512.07711) |  -   |      |

## segmentation

### 分割领域中与高分辨处理相关的文章

| Source |                            Paper                             |                   Code                   | Note |
| :----: | :----------------------------------------------------------: | :--------------------------------------: | :--: |
| CVPR22 | [ISDNet: Integrating Shallow and Deep Networks for Efficient Ultra-high Resolution Segmentation](https://arxiv.org/pdf/2211.11316) |   https://github.com/cedricgsh/ISDNet    |      |
| CVPR21 | [Progressive Semantic Segmentation](https://arxiv.org/abs/2104.03778) | https://github.com/VinAIResearch/MagNet  |      |
| ICCV21 | [From Contexts to Locality: Ultra-high Resolution Image Segmentation via Locality-aware Contextual Correlation](https://openaccess.thecvf.com/content/ICCV2021/papers/Li_From_Contexts_to_Locality_Ultra-High_Resolution_Image_Segmentation_via_Locality-Aware_ICCV_2021_paper.pdf) |     https://github.com/liqiokkk/FCtl     |      |
| CVPR20 | [CascadePSP: Toward Class-Agnostic and Very High-Resolution Segmentation via Global and Local Refinement](https://arxiv.org/abs/2005.02551) | https://github.com/hkchengrex/CascadePSP |      |
| AAAI20 | [Patch Proposal Network for Fast Semantic Segmentation of High-Resolution Images](https://ojs.aaai.org/index.php/AAAI/article/view/6926) |                    -                     |      |
| ICCV19 | [Collaborative Global-Local Networks for Memory-Efﬁcient Segmentation of Ultra-High Resolution Images](https://arxiv.org/abs/1905.06368) |   https://github.com/VITA-Group/GLNet    |      |


## MOT

### 数据集
| Source |                            Paper                             |                   Code                   | Note |
| :----: | :----------------------------------------------------------: | :--------------------------------------: | :--: |
|TMM23|[Robust Multi-Drone Multi-Target Tracking to Resolve Target Occlusion: A Benchmark](https://ieeexplore.ieee.org/document/10008047)|||

## SOT

## CrowdCouting

