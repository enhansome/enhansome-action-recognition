# Awesome Action Recognition: with stars

A curated list of action recognition and related area (e.g. object recognition, pose estimation) resources, inspired by [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision) ⭐ 23,503 | 🐛 91 | 📅 2024-05-17.

## Contents

* [Action Recognition and Video Understanding](#action-recognition-and-video-understanding)
* [Object Recognition](#object-recognition)
* [Pose Estimation](#pose-estimation)
* [Competitions](#competitions)

## Action Recognition and Video Understanding

### Summary posts

* [Deep Learning for Videos: A 2018 Guide to Action Recognition](http://blog.qure.ai/notes/deep-learning-for-videos-action-recognition-review) - Summary of major landmark action recognition research papers till 2018
* [Literature Survey: Human Action Recognition](https://towardsdatascience.com/literature-survey-human-action-recognition-cc7c3818a99a) - Brief human action recognition literature survey of work published between 2014 and 2019.

### Video Representation

* [SlowFast Networks for Video Recognition](https://arxiv.org/abs/1812.03982) - C. Feichtenhofer et al., ICCV2019. [\[code\]](https://github.com/facebookresearch/SlowFast) ⭐ 7,408 | 🐛 444 | 🌐 Python | 📅 2026-03-16
* [Can Spatiotemporal 3D CNNs Retrace the History of 2D CNNs and ImageNet?](http://openaccess.thecvf.com/content_cvpr_2018/papers/Hara_Can_Spatiotemporal_3D_CVPR_2018_paper.pdf) - K. Hara et al., CVPR2019. [\[code\]](https://github.com/kenshohara/3D-ResNets-PyTorch) ⭐ 4,037 | 🐛 154 | 🌐 Python | 📅 2021-01-20
* [Non-Local Neural Networks](https://arxiv.org/abs/1711.07971) - X. Wang et al., CVPR2018. [\[code\]](https://github.com/facebookresearch/video-nonlocal-net) ⚠️ Archived
* [Quo Vadis, Action Recognition? A New Model and the Kinetics Dataset](https://arxiv.org/pdf/1705.07750.pdf) - J. Carreira et al, CVPR2017. [\[code\]](https://github.com/deepmind/kinetics-i3d) ⭐ 1,839 | 🐛 95 | 🌐 Python | 📅 2019-09-12[\[PyTorch code\]](https://github.com/hassony2/kinetics_i3d_pytorch) ⭐ 547 | 🐛 12 | 🌐 Python | 📅 2024-05-23, [\[another PyTorch code\]](https://github.com/piergiaj/pytorch-i3d) ⭐ 1,054 | 🐛 60 | 🌐 Python | 📅 2020-06-28
* [Temporal Segment Networks: Towards Good Practices for Deep Action Recognition](https://arxiv.org/pdf/1608.00859.pdf) - L. Wang et al, arXiv 2016. [\[code\]](https://github.com/yjxiong/temporal-segment-networks) ⭐ 1,577 | 🐛 39 | 🌐 Python | 📅 2020-10-27
* [ConvNet Architecture Search for Spatiotemporal Feature Learning](https://arxiv.org/abs/1708.05038) - D. Tran et al, arXiv2017. Note: Aka Res3D. [\[code\]](https://github.com/facebook/C3D) ⚠️ Archived: In the repository, C3D-v1.1 is the Res3D implementation.
* [Learning Spatiotemporal Features with 3D Convolutional Networks](http://vlg.cs.dartmouth.edu/c3d/c3d_video.pdf) - D. Tran et al, ICCV2015. [\[the official Caffe code\]](https://github.com/facebook/C3D) ⚠️ Archived [\[project web\]](http://vlg.cs.dartmouth.edu/c3d/) Note: Aka C3D. [\[Python Wrapper\]](https://github.com/chuckcho/C3D/tree/python-wrapper) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2016-10-10 Note that the official caffe does not support python wrapper. [\[TensorFlow\]](https://github.com/hx173149/C3D-tensorflow) ⭐ 580 | 🐛 81 | 🌐 Python | 📅 2019-07-11, [\[TensorFlow + Keras\]](https://github.com/axon-research/c3d-keras), [\[Another TensorFlow Implemetation\]](https://github.com/frankgu/C3D-tensorflow.git) ⭐ 15 | 🐛 2 | 🌐 Python | 📅 2018-06-30, [\[Keras C3D Project web\]](https://imatge.upc.edu/web/resources/c3d-model-keras-trained-over-sports-1m): [\[Keras code\]](https://gist.github.com/albertomontesg/d8b21a179c1e6cca0480ebdf292c34d2), [\[Pretrained weights\]](https://www.dropbox.com/s/ypiwalgtlrtnw8b/c3d-sports1M_weights.h5?dl=0).
* [A Closer Look at Spatiotemporal Convolutions for Action Recognition](https://arxiv.org/pdf/1711.11248.pdf) - D. Tran et al., CVPR2018. [\[code\]](https://github.com/facebookresearch/R2Plus1D) ⚠️ Archived [\[PyTorch\]](https://github.com/irhumshafkat/R2Plus1D-PyTorch) ⚠️ Archived
* [Temporal Relational Reasoning in Videos](https://arxiv.org/pdf/1711.08496.pdf) - B. Zhou et al., ECCV2018. [\[code\]](https://github.com/metalbubble/TRN-pytorch) ⭐ 789 | 🐛 63 | 🌐 Python | 📅 2021-05-06 [\[project web\]](http://relation.csail.mit.edu/)
* [Learning Correspondence from the Cycle-consistency of Time](https://arxiv.org/pdf/1903.07593.pdf) - X. Wang et al., CVPR2019. [\[code\]](https://github.com/xiaolonw/TimeCycle) ⭐ 723 | 🐛 10 | 🌐 Python | 📅 2019-06-26 [\[project web\]](https://ajabri.github.io/timecycle/)
* [Convolutional Two-Stream Network Fusion for Video Action Recognition](https://arxiv.org/pdf/1604.06573.pdf) - C. Feichtenhofer et al, CVPR2016. [\[code\]](https://github.com/feichtenhofer/twostreamfusion) ⭐ 715 | 🐛 38 | 🌐 Cuda | 📅 2016-09-27
* [Long-Term Feature Banks for Detailed Video Understanding](https://arxiv.org/pdf/1812.05038.pdf) - C.-Y. Wu. et al., CVPR2019. [\[code\]](https://github.com/facebookresearch/video-long-term-feature-banks/) ⚠️ Archived
* [Learning Spatio-Temporal Representation with Pseudo-3D Residual Networks](http://openaccess.thecvf.com/content_ICCV_2017/papers/Qiu_Learning_Spatio-Temporal_Representation_ICCV_2017_paper.pdf) - Z. Qui et al, ICCV2017. [\[code\]](https://github.com/ZhaofanQiu/pseudo-3d-residual-networks) ⭐ 347 | 🐛 23 | 🌐 C++ | 📅 2018-10-10
* [Temporal Convolutional Networks: A Unified Approach to Action Segmentation and Detection](https://arxiv.org/pdf/1611.05267.pdf) - C. Lea et al, CVPR 2017. [\[code\]](https://github.com/colincsl/TemporalConvolutionalNetworks) ⭐ 298 | 🐛 6 | 🌐 Python | 📅 2017-08-08
* [Action Recognition Zoo](https://github.com/coderSkyChen/Action_Recognition_Zoo) ⭐ 246 | 🐛 4 | 🌐 Python | 📅 2019-04-08 -
  Codes for popular action recognition models, written based on pytorch, verified on the something-something dataset.
* [Long Short-Term Transformer for Online Action Detection](https://arxiv.org/pdf/2107.03377.pdf) - M. Xu et al, Neurips2021. [\[code\]](https://github.com/amazon-research/long-short-term-transformer) ⭐ 140 | 🐛 13 | 🌐 Python | 📅 2024-07-25
* [Why Can't I Dance in the Mall? Learning to Mitigate Scene Bias in Action Recognition](https://papers.nips.cc/paper/8372-why-cant-i-dance-in-the-mall-learning-to-mitigate-scene-bias-in-action-recognition.pdf) - J. Choi et al., NeurIPS2019. [\[project web\]](http://chengao.vision/SDN/) [\[code\]](https://github.com/vt-vl-lab/SDN) ⭐ 86 | 🐛 2 | 🌐 Python | 📅 2024-03-20 [\[arXiv\]](https://arxiv.org/abs/1912.05534)
* [Temporal Recurrent Networks for Online Action Detection](https://arxiv.org/pdf/1811.07391.pdf) - M. Xu et al, ICCV2019. [\[code\]](https://github.com/xumingze0308/TRN.pytorch) ⭐ 85 | 🐛 8 | 🌐 Python | 📅 2022-07-21
* [Long-term Temporal Convolutions](https://arxiv.org/pdf/1604.04494v1.pdf) - G. Varol et al, TPAMI2017. [\[project web\]](http://www.di.ens.fr/willow/research/ltc/) [\[code\]](https://github.com/gulvarol/ltc) ⭐ 84 | 🐛 8 | 🌐 Lua | 📅 2018-08-09
* [Large-scale weakly-supervised pre-training for video action recognition](https://research.fb.com/wp-content/uploads/2019/05/Large-scale-weakly-supervised-pre-training-for-video-action-recognition.pdf?) - D. Ghadiyaram et al., arXiv2019.
* [Video Classification with Channel-Separated Convolutional Networks](https://arxiv.org/pdf/1904.02811.pdf) - D. Tran et al., arXiv2019.
* [DistInit: Learning Video Representations without a Single Labeled Video](https://arxiv.org/pdf/1901.09244.pdf) - R. Girdhar et al., arXiv2019.
* [SCSampler: Sampling Salient Clips from Video for Efficient Action Recognition](https://arxiv.org/pdf/1904.04289.pdf) - B. Korbar et al., arXiv2019.
* [Video Action Transformer Network](https://arxiv.org/pdf/1812.02707.pdf) - R. Girdhar et al., CVPR2019. [\[project web\]](https://rohitgirdhar.github.io/ActionTransformer/)
* [Representation Flow for Action Recognition](https://arxiv.org/pdf/1810.01455.pdf) - AJ. Piergiovanni and M. S. Ryoo et al., CVPR2019.
* [Collaborative Spatiotemporal Feature Learning for Video Action Recognition](https://arxiv.org/pdf/1903.01197.pdf) - C. Li et al., CVPR2019.
* [Learning Video Representations from Correspondence Proposals](https://arxiv.org/pdf/1905.07853.pdf) - X. Liu et al., CVPR2019.
* [Timeception for Complex Action Recognition](https://arxiv.org/pdf/1812.01289.pdf) - N. Hussein et al., CVPR2019.
* [The Visual Centrifuge: Model-Free Layered Video Representations](https://arxiv.org/pdf/1812.01461.pdf) - J.-B. Alayrac et al., CVPR2019.
* [Videos as Space-Time Region Graphs](https://arxiv.org/pdf/1806.01810.pdf) - X. Wang and A. Gupta, ECCV2018.
* [Attend and Interact: Higher-Order Object Interactions for Video Understanding](https://arxiv.org/abs/1711.06330) - CY. Ma et al., CVPR 2018.
* [Rethinking Spatiotemporal Feature Learning For Video Understanding](https://arxiv.org/pdf/1712.04851.pdf) - S. Xie et al., arXiv2017.
* [Deep Temporal Linear Encoding Networks](https://arxiv.org/abs/1611.06678) - A. Diba et al, CVPR2017.
* [Two-Stream Convolutional Networks for Action Recognition in Videos](http://www.robots.ox.ac.uk/~vgg/publications/2014/Simonyan14b/simonyan14b.pdf.pdf) - K. Simonyan and A. Zisserman, NIPS2014.

#### Useful Code Repos on Video Representation Learning

* [\[PySlowFast\]](https://github.com/facebookresearch/slowfast) ⭐ 7,408 | 🐛 444 | 🌐 Python | 📅 2026-03-16
* [\[MMAction2\]](https://github.com/open-mmlab/mmaction2) ⭐ 5,140 | 🐛 319 | 🌐 Python | 📅 2026-03-18
* [\[3D ResNet PyTorch\]](https://github.com/kenshohara/3D-ResNets-PyTorch) ⭐ 4,037 | 🐛 154 | 🌐 Python | 📅 2021-01-20
* [\[Decord\]](https://github.com/dmlc/decord) ⭐ 2,512 | 🐛 220 | 🌐 C++ | 📅 2024-07-17 Efficient video reader for python
* [\[MMAction\]](https://github.com/open-mmlab/mmaction) ⭐ 1,875 | 🐛 57 | 🌐 Python | 📅 2022-04-08
* [\[I3D models transfered from Tensorflow to PyTorch\]](https://github.com/hassony2/kinetics_i3d_pytorch) ⭐ 547 | 🐛 12 | 🌐 Python | 📅 2024-05-23
* [\[PyTorch Video Research\]](https://github.com/gsig/PyVideoResearch) ⭐ 536 | 🐛 11 | 🌐 Python | 📅 2019-06-17
* [\[Extract frame and optical-flow from videos, #docker\]](https://github.com/epic-kitchens/epic-kitchens-100-annotations/blob/master/README.md#erratum) ⭐ 172 | 🐛 2 | 🌐 Python | 📅 2022-08-01
* [\[Inflated models on PyTorch\]](https://github.com/hassony2/inflated_convnets_pytorch) ⭐ 154 | 🐛 5 | 🌐 Python | 📅 2021-04-28
* [\[M-PACT: Michigan Platform for Activity Classification in Tensorflow\]](https://github.com/MichiganCOG/M-PACT) ⭐ 108 | 🐛 2 | 🌐 Python | 📅 2019-05-24
* [\[A Two Stream Baseline on Kinectics dataset\]](https://github.com/gurkirt/2D-kinectics) ⭐ 42 | 🐛 1 | 🌐 Python | 📅 2019-02-23
* [\[I3D models converted from Tensorflow to Core ML\]](https://github.com/lukereichold/VisualActionKit) ⭐ 26 | 🐛 0 | 🌐 Swift | 📅 2020-08-05
* [\[NVIDIA-DALI, video loading pipelines\]](https://docs.nvidia.com/deeplearning/dali/user-guide/docs/examples/sequence_processing/video/video_reader_label_example.html)
* [\[NVIDIA optical-flow SDK\]](https://developer.nvidia.com/opticalflow-sdk)

### Action Classification

* [Attentional Pooling for Action Recognition](https://arxiv.org/abs/1711.01467) - R. Girdhar and D. Ramanan, NIPS2017. [\[code\]](https://github.com/rohitgirdhar/AttentionalPoolingAction) ⭐ 259 | 🐛 6 | 🌐 Python | 📅 2018-05-20
* [Describing Videos by Exploiting Temporal Structure](http://arxiv.org/pdf/1502.08029v4.pdf) - L. Yao et al, ICCV2015. [\[code\]](https://github.com/yaoli/arctic-capgen-vid) ⭐ 256 | 🐛 15 | 🌐 Python | 📅 2020-01-12 note: from the same group of RCN paper “Delving Deeper into Convolutional Networks for Learning Video Representations"
* [Long-term Recurrent Convolutional Networks for Visual Recognition and Description](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Donahue_Long-Term_Recurrent_Convolutional_2015_CVPR_paper.pdf) - J. Donahue et al, CVPR2015. [\[code\]](https://github.com/LisaAnne/lisa-caffe-public/tree/lstm_video_deploy) ⭐ 218 | 🐛 7 | 🌐 C++ | 📅 2017-09-05 [\[project web\]](http://jeffdonahue.com/lrcn/)
* [Hidden Two-Stream Convolutional Networks for Action Recognition](https://arxiv.org/pdf/1704.00389.pdf) - Y. Zhu et al, arXiv2017. [\[code\]](https://github.com/bryanyzhu/Hidden-Two-Stream) ⭐ 190 | 🐛 3 | 🌐 C++ | 📅 2017-12-20
* [Dynamic Image Networks for Action Recognition](https://www.robots.ox.ac.uk/~vgg/publications/2016/Bilen16a/bilen16a.pdf) - H. Bilen et al, CVPR2016. [\[code\]](https://github.com/hbilen/dynamic-image-nets) ⭐ 186 | 🐛 5 | 🌐 Matlab | 📅 2018-01-10 [\[project web\]](http://www.robots.ox.ac.uk/~vgg/publications/2016/Bilen16a/)
* [Real-time Action Recognition with Enhanced Motion Vector CNNs](http://arxiv.org/abs/1604.07669) - B. Zhang et al, CVPR2016. [\[code\]](https://github.com/zbwglory/MV-release) ⭐ 107 | 🐛 7 | 🌐 Matlab | 📅 2018-03-20
* [Action Recognition with Trajectory-Pooled Deep-Convolutional Descriptors](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Wang_Action_Recognition_With_2015_CVPR_paper.pdf) - L. Wang et al, CVPR2015. [\[code\]](https://github.com/wanglimin/TDD) ⭐ 104 | 🐛 1 | 🌐 Matlab | 📅 2017-08-24
* [Guided Weak Supervision for Action Recognition with Scarce Data to Assess Skills of Children with Autism](https://arxiv.org/pdf/1911.04140.pdf) - P. Pandey et al, AAAI 2020. [\[code\]](https://github.com/prinshul/GWSDR) ⭐ 15 | 🐛 1 | 🌐 Python | 📅 2020-07-26
* [Neural Graph Matching Networks for Fewshot 3D Action Recognition](http://openaccess.thecvf.com/content_ECCV_2018/papers/Michelle_Guo_Neural_Graph_Matching_ECCV_2018_paper.pdf) - M. Guo et al., ECCV2018.
* [Temporal 3D ConvNets using Temporal Transition Layer](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w19/Diba_Temporal_3D_ConvNets_CVPR_2018_paper.pdf) - A. Diba et al., CVPRW2018.
* [Temporal 3D ConvNets: New Architecture and Transfer Learning for Video Classification](https://arxiv.org/abs/1711.08200) - A. Diba et al., arXiv2017.
* [Fully Context-Aware Video Prediction](https://arxiv.org/pdf/1710.08518v1.pdf) - Byeon et al, arXiv2017.
* [Two-Stream SR-CNNs for Action Recognition in Videos](http://wanglimin.github.io/papers/ZhangWWQW_CVPR16.pdf) - L. Wang et al, BMVC2016.

### Skeleton-Based Action Classification

* [Actional-Structural Graph Convolutional Networks for Skeleton-Based Action Recognition](http://openaccess.thecvf.com/content_CVPR_2019/html/Li_Actional-Structural_Graph_Convolutional_Networks_for_Skeleton-Based_Action_Recognition_CVPR_2019_paper.html) - M. Li et al., CVPR2019.
* [An Attention Enhanced Graph Convolutional LSTM Network for Skeleton-Based Action Recognition](https://arxiv.org/abs/1902.09130) - C. Si et al., CVPR2019.
* [View Adaptive Neural Networks for High Performance Skeleton-Based Human Action Recognition](https://ieeexplore.ieee.org/abstract/document/8630687) - P. Zhang et al., TPAMI2019.
* [Spatial Temporal Graph Convolutional Networks for Skeleton-Based Action Recognition](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewPaper/17135) - S. Yan et al., AAAI2018. [\[code\]](https://github.com/yysijie/st-gcn) ⭐ 1,752 | 🐛 0 | 🌐 Python | 📅 2023-03-08
* [Deep Progressive Reinforcement Learning for Skeleton-Based Action Recognition](http://openaccess.thecvf.com/content_cvpr_2018/html/Tang_Deep_Progressive_Reinforcement_CVPR_2018_paper.html) - Y. Tang et al., CVPR2018.
* [Co-occurrence Feature Learning from Skeleton Data for Action Recognition and Detection with Hierarchical Aggregation](https://dl.acm.org/citation.cfm?id=3304527) - C. Li et al., IJCAI2018.
* [Part-based Graph Convolutional Network for Action Recognition](http://bmvc2018.org/contents/papers/1003.pdf) - K. Thakkar et al., BMVC2018.

### Temporal Action Detection

* [Temporal Action Detection with Structured Segment Networks](http://cn.arxiv.org/pdf/1704.06228v2) - Y. Zhao et al., ICCV2017. [\[code\]](https://github.com/yjxiong/action-detection) ⭐ 646 | 🐛 18 | 🌐 Python | 📅 2019-06-21 [\[project web\]](http://yjxiong.me/others/ssn/)
* [R-C3D: Region Convolutional 3D Network for Temporal Activity Detection](https://arxiv.org/abs/1703.07814) - H. Xu et al, arXiv2017. [\[code\]](https://github.com/VisionLearningGroup/R-C3D) ⭐ 255 | 🐛 47 | 🌐 Jupyter Notebook | 📅 2019-12-22 [\[project web\]](http://ai.bu.edu/r-c3d/) [\[PyTorch\]](https://github.com/sunnyxiaohu/R-C3D.pytorch) ⭐ 245 | 🐛 26 | 🌐 Python | 📅 2019-12-16
* [Temporal Action Localization in Untrimmed Videos via Multi-stage CNNs](http://dvmmweb.cs.columbia.edu/files/dvmm_scnn_paper.pdf) - Z. Shou et al, CVPR2016. [\[code\]](https://github.com/zhengshou/scnn) ⭐ 233 | 🐛 15 | 🌐 Jupyter Notebook | 📅 2019-03-02 Note: Aka S-CNN.
* [End-to-End, Single-Stream Temporal Action Detection in Untrimmed Videos](http://vision.stanford.edu/pdf/buch2017bmvc.pdf) - Shayamal Buch et al., BMVC 2017 [\[code\]](https://github.com/shyamal-b/ss-tad) ⭐ 108 | 🐛 6 | 🌐 Python | 📅 2017-10-12
* [SST: Single-Stream Temporal Action Proposals](http://vision.stanford.edu/pdf/buch2017cvpr.pdf) - S. Buch et al, CVPR2017. [\[code\]](https://github.com/shyamal-b/sst) ⭐ 100 | 🐛 17 | 🌐 Jupyter Notebook | 📅 2022-12-08
* [End-to-end Learning of Action Detection from Frame Glimpses in Videos](http://vision.stanford.edu/pdf/yeung2016cvpr.pdf) - S. Yeung et al, CVPR2016. [\[code\]](https://github.com/syyeung/frameglimpses) ⭐ 94 | 🐛 3 | 🌐 Lua | 📅 2016-09-12 [\[project web\]](http://ai.stanford.edu/~syyeung/frameglimpses.html) Note: This method uses reinforcement learning
* [DAPs: Deep Action Proposals for Action Understanding](https://ivul.kaust.edu.sa/Documents/Publications/2016/DAPs%20Deep%20Action%20Proposals%20for%20Action%20Understanding.pdf) - V. Escorcia et al, ECCV2016. [\[code\]](https://github.com/escorciav/daps) ⭐ 77 | 🐛 0 | 🌐 Python | 📅 2018-09-22 [\[raw data\]](https://github.com/escorciav/daps) ⭐ 77 | 🐛 0 | 🌐 Python | 📅 2018-09-22
* [Temporal Tessellation: A Unified Approach for Video Analysis](http://openaccess.thecvf.com/content_ICCV_2017/papers/Kaufman_Temporal_Tessellation_A_ICCV_2017_paper.pdf) - Kaufman et al., ICCV2017. [\[code\]](https://github.com/dot27/temporal-tessellation) ⭐ 59 | 🐛 1 | 🌐 Python | 📅 2017-12-13
* [Cascaded Boundary Regression for Temporal Action Detection](https://arxiv.org/abs/1705.01180) - Jiyang Gao et al., BMVC 2017 \[[code](https://github.com/jiyanggao/CBR) ⭐ 52 | 🐛 3 | 🌐 Python | 📅 2018-03-20]
* [Fast Temporal Activity Proposals for Efficient Detection of Human Actions in Untrimmed Videos](http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Heilbron_Fast_Temporal_Activity_CVPR_2016_paper.pdf) - F. Heilbron et al, CVPR2016. [\[code\]](https://github.com/cabaf/sparseprop) ⭐ 47 | 🐛 2 | 🌐 Python | 📅 2019-05-22 Note: Depends on [C3D](http://vlg.cs.dartmouth.edu/c3d/), aka SparseProp.
* [Actionness Estimation Using Hybrid Fully Convolutional Networks](https://arxiv.org/abs/1604.07279) - L. Wang et al, CVPR2016. [\[code\]](https://github.com/wanglimin/actionness-estimation/) ⭐ 30 | 🐛 0 | 🌐 Matlab | 📅 2016-07-30 Note: The code is not a complete verision. It only contains a demo, not training. [\[project web\]](http://wanglimin.github.io/actionness_hfcn/index.html)
* [Rethinking the Faster R-CNN Architecture for Temporal Action Localization](https://arxiv.org/pdf/1804.07667v1.pdf) - Yu-Wei Chao et al., CVPR2018
* [Weakly Supervised Action Localization by Sparse Temporal Pooling Network](https://arxiv.org/pdf/1712.05080) - Phuc Nguyen et al., CVPR 2018
* [Temporal Deformable Residual Networks for Action Segmentation in Videos](http://web.engr.oregonstate.edu/~sinisa/research/publications/cvpr18_TDRN.pdf) - P. Lei and S. Todrovic., CVPR2018.
* [Temporal Context Network for Activity Localization in Videos](https://arxiv.org/pdf/1708.02349.pdf) - X. Dai et al., ICCV2017.
* [Detecting the Moment of Completion: Temporal Models for Localising Action Completion](https://arxiv.org/abs/1710.02310) - F. Heidarivincheh et al., arXiv2017.
* [CDC: Convolutional-De-Convolutional Networks for Precise Temporal Action Localization in Untrimmed Videos](https://arxiv.org/abs/1703.01515/) - Z. Shou et al, CVPR2017. [\[code\]](https://bitbucket.org/columbiadvmm/cdc)
* [Online Action Detection using Joint Classification-Regression Recurrent Neural Networks](https://arxiv.org/abs/1604.05633) - Y. Li et al, ECCV2016. Noe: RGB-D Action Detection
* [Learning Activity Progression in LSTMs for Activity Detection and Early Detection](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Ma_Learning_Activity_Progression_CVPR_2016_paper.pdf) - S. Ma et al, CVPR2016.
* [Fast Action Proposals for Human Action Detection and Search](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Yu_Fast_Action_Proposals_2015_CVPR_paper.pdf) - G. Yu and J. Yuan, CVPR2015. Note: code for FAP is NOT available online. Note: Aka FAP.
* [Bag-of-fragments: Selecting and encoding video fragments for event detection and recounting](https://staff.fnwi.uva.nl/t.e.j.mensink/publications/mettes15icmr.pdf) - P. Mettes et al, ICMR2015.
* [Action localization in videos through context walk](http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Soomro_Action_Localization_in_ICCV_2015_paper.pdf) - K. Soomro et al, ICCV2015.

### Spatio-Temporal Action Detection

* [Online Real time Multiple Spatiotemporal Action Localisation and Prediction](https://arxiv.org/pdf/1611.08563v3.pdf) - [G. Singh](http://gurkirt.github.io/) et al, ICCV2017. [\[code\]](https://github.com/gurkirt/realtime-action-detection) ⭐ 320 | 🐛 0 | 🌐 MATLAB | 📅 2021-02-23
* [Action Tubelet Detector for Spatio-Temporal Action Localization](https://arxiv.org/abs/1705.01861) - V. Kalogeiton et al, ICCV2017. [\[code\]](https://github.com/vkalogeiton/caffe/tree/act-detector) ⭐ 106 | 🐛 0 | 🌐 C++ | 📅 2018-02-27 [\[project web\]](http://thoth.inrialpes.fr/src/ACTdetector/)
* [Finding Action Tubes](https://people.eecs.berkeley.edu/~gkioxari/ActionTubes/action_tubes.pdf) - G. Gkioxari and J. Malik CVPR2015. [\[code\]](https://github.com/gkioxari/ActionTubes) ⭐ 64 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2016-06-22 [\[project web\]](https://people.eecs.berkeley.edu/~gkioxari/ActionTubes/)
* [Multi-region two-stream R-CNN for action detection](https://www.robots.ox.ac.uk/~vgg/rg/papers/peng16eccv.pdf) - [X. Peng](http://xjpeng.weebly.com/) and C. Schmid. ECCV2016. [\[code\]](https://github.com/pengxj/action-faster-rcnn) ⭐ 58 | 🐛 7 | 🌐 Jupyter Notebook | 📅 2017-11-23
* [APT: Action localization proposals from dense trajectories](http://jvgemert.github.io/pub/gemertBMVC15APTactionProposals.pdf) - J. Gemert et al, BMVC2015. [\[code\]](https://github.com/jvgemert/apt) ⭐ 21 | 🐛 3 | 🌐 Python | 📅 2016-01-14
* [A Better Baseline for AVA](https://arxiv.org/pdf/1807.10066.pdf) - R. Girdhar et al., ActivityNet Workshop, CVPR2018.
* [Real-Time End-to-End Action Detection with Two-Stream Networks](https://arxiv.org/abs/1802.08362) - A. El-Nouby and G. Taylor, arXiv2018.
* [Human Action Localization with Sparse Spatial Supervision](https://arxiv.org/pdf/1605.05197.pdf) - P. Weinzaepfel et al., arXiv2017.
* [Unsupervised Action Discovery and Localization in Videos](http://openaccess.thecvf.com/content_ICCV_2017/papers/Soomro_Unsupervised_Action_Discovery_ICCV_2017_paper.pdf) - K. Soomro and M. Shah, ICCV2017.
* [Spatial-Aware Object Embeddings for Zero-Shot Localization and Classification of Actions](https://arxiv.org/pdf/1707.09145.pdf) - P. Mettes and C. G. M. Snoek, ICCV2017.
* [Tube Convolutional Neural Network (T-CNN) for Action Detection in Videos](https://arxiv.org/pdf/1703.10664.pdf) - [R. Hou](http://www.cs.ucf.edu/~rhou/) et al, ICCV2017. [\[project web\]](http://crcv.ucf.edu/projects/TCNN/)
* [Chained Multi-stream Networks Exploiting Pose, Motion, and Appearance for Action Classification and Detection](https://arxiv.org/abs/1704.00616) - M. Zolfaghari et al, ICCV2017. [\[project web\]](https://lmb.informatik.uni-freiburg.de/projects/action_chain/)
* [TORNADO: A Spatio-Temporal Convolutional Regression Network for Video Action Proposal](http://openaccess.thecvf.com/content_ICCV_2017/papers/Zhu_TORNADO_A_Spatio-Temporal_ICCV_2017_paper.pdf) - H. Zhu et al., ICCV2017.
* [AMTnet: Action-Micro-Tube regression by end-to-end trainable deep architecture](https://arxiv.org/pdf/1704.04952.pdf) - S. Saha et al, ICCV2017.
* [Am I Done? Predicting Action Progress in Videos](https://arxiv.org/abs/1705.01781) - F. Becattini et al, BMVC2017.
* [Generic Tubelet Proposals for Action Localization](https://arxiv.org/abs/1705.10861) - J. He et al, arXiv2017.
* [Incremental Tube Construction for Human Action Detection](https://arxiv.org/pdf/1704.01358.pdf) - H. S. Behl et al, arXiv2017.
* [Spot On: Action Localization from Pointly-Supervised Proposals](http://jvgemert.github.io/pub/spotOnECCV16.pdf) - P. Mettes et al, ECCV2016.
* [Deep Learning for Detecting Multiple Space-Time Action Tubes in Videos](https://arxiv.org/abs/1608.01529) - S. Saha et al, BMVC2016. [\[code\]](https://bitbucket.org/sahasuman/bmvc2016_code) [\[project web\]](http://sahasuman.bitbucket.org/bmvc2016/)
* [Learning to track for spatio-temporal action localization](http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Weinzaepfel_Learning_to_Track_ICCV_2015_paper.pdf) - P. Weinzaepfel et al. ICCV2015.
* [Action detection by implicit intentional motion clustering](http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Chen_Action_Detection_by_ICCV_2015_paper.pdf) - W. Chen and J. Corso, ICCV2015.
* [Spatio-Temporal Object Detection Proposals](https://hal.inria.fr/hal-01021902/PDF/proof.pdf) - D. Oneata et al, ECCV2014. [\[code\]](https://bitbucket.org/doneata/proposals) [\[project web\]](http://lear.inrialpes.fr/~oneata/3Dproposals/)
* [Action localization with tubelets from motion](http://isis-data.science.uva.nl/cgmsnoek/pub/jain-tubelets-cvpr2014.pdf) - M. Jain et al, CVPR2014.
* [Spatiotemporal deformable part models for action detection](http://crcv.ucf.edu/papers/cvpr2013/cvpr2013-sdpm.pdf) - [Y. Tian](http://www.cs.ucf.edu/~ytian/index.html) et al, CVPR2013. [\[code\]](http://www.cs.ucf.edu/~ytian/sdpm.html)
* [Action localization in videos through context walk](http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Soomro_Action_Localization_in_ICCV_2015_paper.pdf) - K. Soomro et al, ICCV2015.
* [Fast Action Proposals for Human Action Detection and Search](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Yu_Fast_Action_Proposals_2015_CVPR_paper.pdf) - G. Yu and J. Yuan, CVPR2015. Note: code for FAP is NOT available online. Note: Aka FAP.

### Ego-Centric Action Recognition

* [Actor and Observer: Joint Modeling of First and Third-Person Videos](https://arxiv.org/pdf/1804.09627.pdf) - G. Sigurdsson et al., CVPR2018. [\[code\]](https://github.com/gsig/actor-observer) ⭐ 84 | 🐛 10 | 🌐 Python | 📅 2019-03-08

### Miscellaneous

* [CortexNet: a Generic Network Family for Robust Visual Temporal Representations](https://arxiv.org/pdf/1706.02735.pdf) A. Canziani and E. Culurciello - arXiv2017. [\[code\]](https://github.com/atcold/pytorch-CortexNet) ⭐ 365 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2018-11-28 [\[project web\]](https://engineering.purdue.edu/elab/CortexNet/)
* [Slicing Convolutional Neural Network for Crowd Video Understanding](http://www.ee.cuhk.edu.hk/~jshao/papers_jshao/jshao_cvpr16_scnn.pdf) - J. Shao et al, CVPR2016. [\[code\]](https://github.com/amandajshao/Slicing-CNN) ⭐ 45 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2016-08-10
* [Two-Stream (RGB and Flow) pretrained model weights](https://github.com/craftGBD/caffe-GBD/tree/master/models/action_recognition) ⭐ 27 | 🐛 1 | 🌐 C++ | 📅 2016-10-07
* [What and How Well You Performed? A Multitask Learning Approach to Action Quality Assessment](https://arxiv.org/pdf/1904.04346.pdf) - P. Parma and B. T. Morris. CVPR2019.
* [PathTrack: Fast Trajectory Annotation with Path Supervision](http://openaccess.thecvf.com/content_ICCV_2017/papers/Manen_PathTrack_Fast_Trajectory_ICCV_2017_paper.pdf) - S. Manen et al., ICCV2017.

### Action Recognition Datasets

* [UCF-101](http://crcv.ucf.edu/data/UCF101.php), [annotation provided by THUMOS-14](http://crcv.ucf.edu/ICCV13-Action-Workshop/index.files/UCF101_24Action_Detection_Annotations.zip), and [corrupted annotation list](https://github.com/jinwchoi/Jinwoo-Computer-Vision-and-Machine-Learing-papers-to-read/blob/master/UCF101_Spatial_Annotation_Corrupted_file_list) ⭐ 4,012 | 🐛 1 | 📅 2023-05-13,  [UCF-101 corrected annotations](https://github.com/gurkirt/corrected-UCF101-Annots) ⭐ 82 | 🐛 0 | 🌐 MATLAB | 📅 2021-02-20 and [different version annotaions](https://github.com/jvgemert/apt) ⭐ 21 | 🐛 3 | 🌐 Python | 📅 2016-01-14. And there are also some pre-computed spatiotemporal action detection [results](https://drive.google.com/drive/folders/0B-LzM05qEdk0aG5pTE94VFI1SUk)
* [Kinetics](https://deepmind.com/research/open-source/open-source-datasets/kinetics/), [paper](https://arxiv.org/pdf/1705.07750.pdf), [download toolkit](https://github.com/activitynet/ActivityNet/tree/master/Crawler/Kinetics) ⭐ 976 | 🐛 22 | 🌐 Jupyter Notebook | 📅 2024-03-21
* [NTU RGB+D](https://github.com/shahroudy/NTURGB-D) ⭐ 879 | 🐛 23 | 🌐 MATLAB | 📅 2022-02-18
* [Video Dataset Overview from Antoine Miech](https://www.di.ens.fr/~miech/datasetviz/)
* [HACS](http://hacs.csail.mit.edu/)
* [Moments in Time](http://moments.csail.mit.edu/), [paper](http://moments.csail.mit.edu/data/moments_paper.pdf)
* [AVA](https://research.google.com/ava/), [paper](https://arxiv.org/abs/1705.08421), [\[INRIA web\]](http://thoth.inrialpes.fr/ava/getava.php) for missing videos
* [OOPS](https://oops.cs.columbia.edu/data/) - A dataset of unintentional action, [paper](https://arxiv.org/abs/1911.11206)
* [COIN](https://coin-dataset.github.io/) - a large-scale dataset for comprehensive instructional video analysis, [paper](https://arxiv.org/abs/1903.02874)
* [YouTube-8M](https://research.google.com/youtube8m/), [technical report](https://arxiv.org/abs/1609.08675)
* [YouTube-BB](https://research.google.com/youtube-bb/), [technical report](https://arxiv.org/pdf/1702.00824.pdf)
* [DALY](http://thoth.inrialpes.fr/daly/) Daily Action Localization in Youtube videos. Note: Weakly supervised action detection dataset. Annotations consist of start and end time of each action, one bounding box per each action per video.
* [20BN-JESTER](https://www.twentybn.com/datasets/jester), [20BN-SOMETHING-SOMETHING](https://www.twentybn.com/datasets/something-something)
* [ActivityNet](http://activity-net.org/) Note: They provide a download script and evaluation code [here](https://github.com/activitynet) .
* [Charades](http://allenai.org/plato/charades/)
* [Charades-Ego](https://prior.allenai.org/projects/charades-ego), [paper](https://arxiv.org/pdf/1804.09626.pdf) - First person and third person video aligned dataset
* [EPIC-Kitchens](https://epic-kitchens.github.io/), [paper](https://arxiv.org/abs/1804.02748) - First person videos recorded in kitchens. Note they provide download scripts and a python library [here](https://github.com/epic-kitchens)
* [Sports-1M](http://cs.stanford.edu/people/karpathy/deepvideo/classes.html) - Large scale action recognition dataset.
* [THUMOS14](http://crcv.ucf.edu/THUMOS14/) Note: It overlaps with [UCF-101](http://crcv.ucf.edu/data/UCF101.php) dataset.
* [THUMOS15](http://www.thumos.info/home.html) Note: It overlaps with [UCF-101](http://crcv.ucf.edu/data/UCF101.php) dataset.
* [HOLLYWOOD2](http://www.di.ens.fr/~laptev/actions/hollywood2/): [Spatio-Temporal annotations](https://staff.fnwi.uva.nl/p.s.m.mettes/index.html#data)
* [UCF-50](http://crcv.ucf.edu/data/UCF50.php).
* [UCF-Sports](http://crcv.ucf.edu/data/UCF_Sports_Action.php), note: the train/test split link in the official website is broken. Instead, you can download it from [here](http://pascal.inrialpes.fr/data2/oneata/data/ucf_sports/videos.txt).
* [HMDB](http://serre-lab.clps.brown.edu/resource/hmdb-a-large-human-motion-database/)
* [J-HMDB](http://jhmdb.is.tue.mpg.de/)
* [LIRIS-HARL](http://liris.cnrs.fr/voir/activities-dataset/)
* [KTH](http://www.nada.kth.se/cvap/actions/)
* [MSR Action](https://www.microsoft.com/en-us/download/details.aspx?id=52315) Note: It overlaps with [KTH](http://www.nada.kth.se/cvap/actions/) datset.
* [Sports Videos in the Wild](http://cvlab.cse.msu.edu/project-svw.html)
* [Mixamo Mocap Dataset](http://mocap.cs.cmu.edu/)
* [UWA3D Multiview Activity II Dataset](http://staffhome.ecm.uwa.edu.au/~00053650/databases.html)
* [Northwestern-UCLA Dataset](https://users.eecs.northwestern.edu/~jwa368/my_data.html)
* [SYSU 3D Human-Object Interaction Dataset](http://www.isee-ai.cn/~hujianfang/ProjectJOULE.html)
* [MEVA (Multiview Extended Video with Activities) Dataset](http://mevadata.org)

### Video Annotation

* [VTT: Visual Object Tagging Tool](https://github.com/microsoft/VoTT) ⚠️ Archived. Modern app to annotate objects in videos and images. It facilitates the development of an end-to-end machine learning pipeline encompassing the annotation/export/import of assets. Moreover, it could run as a native app or via web.
* [Efficiently scaling up crowdsourced video annotation](http://cvrr.ucsd.edu/ece285/Spring2014/papers/Vondrick_IJCV2013.pdf) - C. Vondrick et. al, IJCV2013. [\[code\]](https://github.com/cvondrick/vatic) ⭐ 614 | 🐛 91 | 🌐 HTML | 📅 2020-07-15
* [The Design and Implementation of ViPER](https://www.cs.umd.edu/grad/scholarlypapers/papers/davidm-viper.pdf) - D. Mihalcik and D. Doermann, Technical report.
* [VIA: VGG Image Annotator](http://www.robots.ox.ac.uk/~vgg/software/via/). Simple and standalone manual annotation web-app for image, audio and video. It runs in the web browser and does not require any installation or setup.

## Object Recognition

### Object Detection

* [YOLO](https://pjreddie.com/media/files/papers/yolo.pdf) - J. Redmon et al, CVPR2016. [\[official code\]](https://github.com/pjreddie/darknet.git) ⭐ 26,491 | 🐛 1,975 | 🌐 C | 📅 2024-05-03, [\[TensorFLow\]](https://github.com/gliese581gg/YOLO_tensorflow) ⭐ 1,708 | 🐛 38 | 🌐 Python | 📅 2019-01-05 - Fast object detector.
* [Detectron](https://github.com/facebookresearch/Detectron) ⚠️ Archived - Open Source Object Detection Framework from Facebook AI Research. Includes Mask R-CNN, FPN, and etc. Caffe2 implementation.
* [Mask R-CNN](https://arxiv.org/abs/1703.06870) - K. He et al, [\[Detectron\]](https://github.com/facebookresearch/Detectron) ⚠️ Archived, [\[TensorFlow + Keras\]](https://github.com/matterport/Mask_RCNN) ⭐ 25,565 | 🐛 2,022 | 🌐 Python | 📅 2024-06-07, [\[MXNet\]](https://github.com/TuSimple/mx-maskrcnn) ⭐ 1,753 | 🐛 54 | 🌐 Python | 📅 2018-02-28, [\[TensorFlow\]](https://github.com/CharlesShang/FastMaskRCNN) ⭐ 3,082 | 🐛 142 | 🌐 Python | 📅 2021-01-05, [\[PyTorch\]](https://github.com/felixgwu/mask_rcnn_pytorch) - State-of-the-art object detection/instance segmentation algorithm.
* [SSD](https://arxiv.org/abs/1512.02325) - W. Liu et al, ECCV2016. [\[official PyCaffe code\]](https://github.com/weiliu89/caffe/tree/ssd) ⭐ 4,808 | 🐛 676 | 🌐 C++ | 📅 2023-04-21, [\[TensorFlow\]](https://github.com/balancap/SSD-Tensorflow) ⭐ 4,101 | 🐛 295 | 🌐 Jupyter Notebook | 📅 2021-08-12, [\[Keras\]](https://github.com/rykov8/ssd_keras) ⚠️ Archived - State-of-the-art object detector with realtime processing speed.
* [RetinaNet](https://arxiv.org/abs/1708.02002) - Tsung-Yi Lin, Priya Goyal, Ross Girshick, Kaiming He and Piotr Dollár, Facebook AI Research FAIR & ICCV 2017.[\[Keras\]](https://github.com/fizyr/keras-retinanet) ⭐ 4,383 | 🐛 29 | 🌐 Python | 📅 2023-03-16 - State-of-the-art object detector with realtime processing speed.
* [Deformable Convolutional Networks](http://openaccess.thecvf.com/content_ICCV_2017/papers/Dai_Deformable_Convolutional_Networks_ICCV_2017_paper.pdf) - J. Dai et al., ICCV2017. [\[official code\]](https://github.com/msracver/Deformable-ConvNets) ⭐ 4,120 | 🐛 159 | 🌐 Python | 📅 2021-09-27
* [Faster R-CNN](https://arxiv.org/abs/1506.01497) - S. Ren et al, NIPS2015. [\[official MatCaffe code\]](https://github.com/ShaoqingRen/faster_rcnn) ⭐ 2,835 | 🐛 141 | 🌐 Matlab | 📅 2018-07-26, [\[PyCaffe\]](https://github.com/rbgirshick/py-faster-rcnn) ⭐ 8,289 | 🐛 667 | 🌐 Python | 📅 2019-11-07, [\[TensorFlow\]](https://github.com/smallcorgi/Faster-RCNN_TF) ⭐ 2,342 | 🐛 271 | 🌐 Python | 📅 2021-10-28, [\[Another TF implementation\]](https://github.com/CharlesShang/TFFRCNN) ⭐ 871 | 🐛 102 | 🌐 Python | 📅 2018-06-07 [\[Keras\]](https://github.com/yhenon/keras-frcnn) - State-of-the-art object detector.
* [YOLO9000](https://arxiv.org/abs/1612.08242) - J. Redmon and A. Farhadi, CVPR2017. [\[official code\]](https://pjreddie.com/darknet/yolo/) - State-of-the-art object detector which can detect 9000 objects in realtime.

### Video Object Detection

* \[Flow-Guided Feature Aggregation for Video Object Detection] - X. Zhu et al., ICCV2017. [\[code\]](https://github.com/msracver/Flow-Guided-Feature-Aggregation) ⭐ 732 | 🐛 67 | 🌐 Python | 📅 2021-09-27, aka FGFA
* \[Detect to Track and Track to Detect] - C. Feichtenhofer et al., ICCV2017. [\[code\]](https://github.com/feichtenhofer/detect-track) ⭐ 552 | 🐛 20 | 🌐 Matlab | 📅 2018-07-03, [\[project web\]](http://www.robots.ox.ac.uk/~vgg/research/detect-track/)

### Video Object Detection Datasets

* [ImageNet VID](http://image-net.org/challenges/LSVRC/2017/download-images-1p39.php)
* [YouTube-8M](https://research.google.com/youtube8m/), [technical report](https://arxiv.org/abs/1609.08675)
* [YouTube-BB](https://research.google.com/youtube-bb/), [technical report](https://arxiv.org/pdf/1702.00824.pdf)

## Pose Estimation

### Pose Estimation

* [OpenPose Library](https://github.com/CMU-Perceptual-Computing-Lab/openpose) ⭐ 34,371 | 🐛 359 | 🌐 C++ | 📅 2024-08-03 - Caffe based realtime pose estimation library from CMU.
* [AlphaPose](https://github.com/MVIG-SJTU/AlphaPose) ⭐ 8,594 | 🐛 304 | 🌐 Python | 📅 2024-05-13 - PyTorch based realtime and accurate pose estimation and tracking tool from SJTU.
* [DensePose](https://arxiv.org/abs/1802.00434v1) [\[code\]](https://github.com/facebookresearch/DensePose) ⚠️ Archived - Dense pose human estimation in the wild implemented in the Detectron framework.
* [DeepLabCut: markerless pose estimation of user-defined body parts with deep learning](https://www.nature.com/articles/s41593-018-0209-y) - A. Mathis et al, Nature Neuroscience 2018. [\[code\]](https://github.com/DeepLabCut/DeepLabCut) ⭐ 5,736 | 🐛 48 | 🌐 Python | 📅 2026-08-18
* [Realtime Multi-Person 2D Pose Estimation using Part Affinity Fields](https://arxiv.org/abs/1611.08050) - Z. Cao et al, CVPR2017. [\[code\]](https://github.com/ZheC/Realtime_Multi-Person_Pose_Estimation) ⭐ 5,123 | 🐛 107 | 🌐 Jupyter Notebook | 📅 2020-03-21 depends on the [\[caffe RT pose\]](https://github.com/CMU-Perceptual-Computing-Lab/caffe_rtpose.git) ⭐ 356 | 🐛 4 | 🌐 C++ | 📅 2017-07-18 - Earlier version of OpenPose from CMU.
* [MultiPoseNet: Fast Multi-Person Pose Estimation using Pose Residual Network](https://arxiv.org/abs/1807.04067) - M. Kocabas et al, ECCV2018. [\[code\]](https://github.com/salihkaragoz/pose-residual-network-pytorch) ⭐ 285 | 🐛 8 | 🌐 Python | 📅 2021-08-06
* [Detect-and-Track: Efficient Pose Estimation in Videos](https://arxiv.org/abs/1712.09184) - R. Girdhar et al., arXiv2017.

## Competitions

### Competitions

* [ActEV (Activities in Extended Video](https://actev.nist.gov/sdl) - Activity detection in security camera videos. Runs through 2021. Hosted by NIST.

## Licenses

License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Jinwoo Choi](https://sites.google.com/site/jchoivision/) has waived all copyright and related or neighboring rights to this work.

## Contributing

Please read the [contribution guidelines](contributing.md). Then please feel free to send me [pull requests](https://github.com/jinwchoi/Action-Recognition/pulls) ⭐ 4,012 | 🐛 1 | 📅 2023-05-13 or email (<jinchoi@vt.edu>) to add links.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-18._
