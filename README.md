# 参考智源大会每日资讯
记录每天有用的ai技术
# 2021.1
## 2021.1.18
(1)给AI从业者的重要年终参考——**谷歌两万字博客总结自身2020人工智能进展**(https://mp.weixin.qq.com/s/gcR8_61A6gP1fkDDnUvr_Q)  
(2)谷歌最新发布数据集：Open Images V6 来了！新增局部叙事标注形式(https://storage.googleapis.com/openimages/web/index.html)  
(3)谷歌在**MediaPipe**中开源了新的感知推理功能和解决方案，例如设备上的面部、手和姿势预测，实时身体姿势跟踪，实时虹膜跟踪和深度估计以及实时3D对象检(https://github.com/google/mediapipe)     (4)AWS机器学习服务的概况与发展(https://mp.weixin.qq.com/s/NLKjAYuw-y_KhgXMyGs-Dw)    
(5)综述 | GAN逆映射(inversion)技术：全面调研（2016-2020） (https://hub.baai.ac.cn/view/5882)    
(6)第一个对**整个人体进行人工标注的基准**，包括133个密集的地标，其中68个在脸上，42个在手上，23个在身体和脚上（https://github.com/jin-s13/COCO-WholeBody）    
(7)**HRnet**目前比较好的模型，利用**多尺度**提高heatmap准确度(https://www.aiuai.cn/aifarm927.html)  
(8)一个值得深思的问题？**为什么验证集的loss会小于训练集的loss**（https://zhuanlan.zhihu.com/p/89623222）  
## 2021.1.20
(1)【机器学习】Cross-Validation（交叉验证）详解 https://zhuanlan.zhihu.com/p/24825503?refer=rdatamining  
(2)【思考】 mask标签数据如何训练？是全局部还是全局的数据参加训练?模型生成掩码可以提高其他任务的准确度(eg:分类，回归，maskrcnn)?
(3)【比赛方案流程】思路的构建（模型的选择），epoch的选择，数据集分布，数据增强（加噪，将噪），交叉验证，学习率的设置，多任务loss的均衡，模型训练结果的可视化（可视化可帮助分析）  
(4)【数据增强库】OpenCV，PIL，Skimage你pick谁（https://www.jianshu.com/p/bda23f8cfd84）  
Python下PIL, OpenCV, SKImage图像的相互转换（https://blog.csdn.net/u013832707/article/details/90293585）
## 2021.1.21
(1)2021/01/19 必读 |谷歌提出「元伪标签」半监督学习方法，将ImageNet的top-1提升到90.2% https://hub.baai.ac.cn/view/5947  
(2)UIUC韩家炜团队发文：文本分类只需标签名称，不需要任何标注数据 | EMNLP 2020 https://hub.baai.ac.cn/view/5972  
(3)共享单车站点规划 | 基于门控图神经网络对共享单车停放进行动态管理 https://hub.baai.ac.cn/view/5976  
(4)2021/01/20 必读 | CVPR 2021评审出炉，评审员奇葩意见遭热议 https://hub.baai.ac.cn/view/5968  
## 2021.1.24
(1)T-PAMI 2021 | **换个损失函数就能实现数据扩增**(语义层面的数据增强)？https://hub.baai.ac.cn/view/6013  
(2)trian img size必须和test img size**一致**  
(3)AI跳舞哪家强？**谷歌**3D舞者闻**歌**起**舞**，挑战**DanceNet**(多模态训练) https://mp.weixin.qq.com/s/duxL22Gohnj9SfSU3YmQfw  
论文地址：https://arxiv.org/pdf/2101.08779v1.pdf  
项目地址：https://google.github.io/aichoreographer/  
(4)AIST++数据集， AIST++ 是一个大规模 3D 舞蹈动作数据集，包含大量伴随音乐的3D舞蹈动作。其中每一帧都具备以下额外标注：  
9 种视角，包括摄像机的内外参数；  
17 种 COCO 格式的人类关节位置，包含 2D 和 3D 形式；  
24 个 SMPL 姿势参数，以及全局扩展和平移。  
数据集地址：https://google.github.io/aistplusplus_dataset/  
(5)**目标检测Anchor**是什么？怎么科学设置？人人都能彻底搞懂的Anchor深度解析 https://mp.weixin.qq.com/s/Qvjk7mz8d9lxeyIMND1mPA  
**anchor只有跟你要检测的物体的大小和长宽比更贴近**，才能让模型的效果更好。YOLOv2版本开始使用**kmeans方法聚类**得到**合适的anchor**  
## 2021.1.25
(1)动手学习深度学习 **mxnet** https://zh.d2l.ai/  
(2)了解mxnet的fine tune https://zhuanlan.zhihu.com/p/42441251,  
Fine-tuning a pre-trained model: 33 output nodes vs 17 https://github.com/MVIG-SJTU/AlphaPose/issues/187  
(3)创建新的HDF5数据集 https://github.com/MVIG-SJTU/AlphaPose/issues/193，https://github.com/MVIG-SJTU/AlphaPose/issues/238  
(4)alphapose的输出格式 https://github.com/MVIG-SJTU/AlphaPose/blob/pytorch/doc/output.md  
因为前17个输出是COCO关键点（COCO有17个关键点），而其他16个是MPII关键点（MPII有16个关键点），所以有33个输出  
