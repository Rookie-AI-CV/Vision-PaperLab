# 计算机视觉经典论文收录

本仓库系统性地收录了计算机视觉领域的经典深度学习论文，涵盖图像分类、目标检测、语义分割、自监督学习等多个研究方向。每篇论文均提供原版、中文翻译版及中英对照版，并附有相应的代码实现链接，旨在为研究者和学习者提供全面的学习资源。

## 项目结构

```
Vision-PaperLab/
├── paper/                    # 论文PDF文件目录
│   ├── *.pdf                 # 原版论文
│   ├── *-mono.pdf            # 中文翻译版
│   └── *-dual.pdf            # 中英对照版
│
├── notes/                    # 阅读笔记目录（按研究方向分类）
│   ├── classification/       # 图像分类相关笔记
│   ├── detection/            # 目标检测相关笔记
│   ├── segmentation/        # 语义分割相关笔记
│   ├── transformer/          # Transformer架构相关笔记
│   ├── self-supervised/     # 自监督学习相关笔记
│   └── multimodal/          # 多模态学习相关笔记
│
├── docs/                     # 文档目录
│   └── STRUCTURE.md         # 目录结构详细说明
│
├── README.md                 # 项目主README
└── .gitignore               # Git忽略文件配置
```

详细的目录结构说明请参考 [docs/STRUCTURE.md](docs/STRUCTURE.md)。

## 📑 快速导航

- [图像分类](#图像分类) (5篇) | [目标检测](#目标检测) (5篇) | [语义分割](#语义分割) (4篇) | [Transformer架构](#transformer架构) (4篇) | [自监督学习](#自监督学习) (2篇) | [多模态学习](#多模态学习) (1篇)

## 📚 论文列表

### 图像分类

| 论文名称 | 原版论文 | 中文版 | 中英对照 | Code | Note |
|---------|---------|--------|---------|------|------|
| **AlexNet** | [PDF](paper/AlexNet%20-%20ImageNet%20Classification%20with%20Deep%20Convolutional%20Neural%20Networks.pdf) | [中文版](paper/AlexNet%20-%20ImageNet%20Classification%20with%20Deep%20Convolutional%20Neural%20Networks-mono.pdf) | [中英对照](paper/AlexNet%20-%20ImageNet%20Classification%20with%20Deep%20Convolutional%20Neural%20Networks-dual.pdf) | [GitHub](https://github.com/BVLC/caffe) | [笔记](notes/classification/) |
| **VGG** | [PDF](paper/VGG%20-%20Very%20Deep%20Convolutional%20Networks%20for%20Large-Scale%20Image%20Recognition.pdf) | [中文版](paper/VGG%20-%20Very%20Deep%20Convolutional%20Networks%20for%20Large-Scale%20Image%20Recognition-mono.pdf) | [中英对照](paper/VGG%20-%20Very%20Deep%20Convolutional%20Networks%20for%20Large-Scale%20Image%20Recognition-dual.pdf) | [GitHub](https://github.com/pytorch/vision/blob/main/torchvision/models/vgg.py) | [笔记](notes/classification/) |
| **ResNet** | [PDF](paper/ResNet%20-%20Deep%20Residual%20Learning%20for%20Image%20Recognition.pdf) | [中文版](paper/ResNet%20-%20Deep%20Residual%20Learning%20for%20Image%20Recognition-mono.pdf) | [中英对照](paper/ResNet%20-%20Deep%20Residual%20Learning%20for%20Image%20Recognition-dual.pdf) | [GitHub](https://github.com/KaimingHe/deep-residual-networks) | [笔记](notes/classification/) |
| **ResNetV2** | [PDF](paper/ResNetV2%20-%20Identity%20Mappings%20in%20Deep%20Residual%20Networks.pdf) | [中文版](paper/ResNetV2%20-%20Identity%20Mappings%20in%20Deep%20Residual%20Networks-mono.pdf) | [中英对照](paper/ResNetV2%20-%20Identity%20Mappings%20in%20Deep%20Residual%20Networks-dual.pdf) | [GitHub](https://github.com/KaimingHe/deep-residual-networks) | [笔记](notes/classification/) |
| **GoogleNet** | [PDF](paper/GoogleNet%20-%20Going%20Deeper%20with%20Convolutions.pdf) | [中文版](paper/GoogleNet%20-%20Going%20Deeper%20with%20Convolutions-mono.pdf) | [中英对照](paper/GoogleNet%20-%20Going%20Deeper%20with%20Convolutions-dual.pdf) | [GitHub](https://github.com/tensorflow/models/tree/master/research/slim) | [笔记](notes/classification/) |

### 目标检测

| 论文名称 | 原版论文 | 中文版 | 中英对照 | Code | Note |
|---------|---------|--------|---------|------|------|
| **R-CNN** | [PDF](paper/R-CNN%20-%20Rich%20feature%20hierarchies%20for%20accurate%20object%20detection%20and%20semantic%20segmentation.pdf) | - | - | [GitHub](https://github.com/rbgirshick/rcnn) | [笔记](notes/detection/) |
| **Faster R-CNN** | [PDF](paper/Faster%20R-CNN%20-%20Towards%20Real-Time%20Object.pdf) | [中文版](paper/Faster%20R-CNN%20-%20Towards%20Real-Time%20Object-mono.pdf) | [中英对照](paper/Faster%20R-CNN%20-%20Towards%20Real-Time%20Object-dual.pdf) | [GitHub](https://github.com/rbgirshick/py-faster-rcnn) | [笔记](notes/detection/) |
| **FPN** | [PDF](paper/FPN%20-%20Feature%20Pyramid%20Networks%20for%20Object%20Detection.pdf) | [中文版](paper/FPN%20-%20Feature%20Pyramid%20Networks%20for%20Object%20Detection-mono.pdf) | [中英对照](paper/FPN%20-%20Feature%20Pyramid%20Networks%20for%20Object%20Detection-dual.pdf) | [GitHub](https://github.com/facebookresearch/Detectron) | [笔记](notes/detection/) |
| **Mask R-CNN** | [PDF](paper/Mask%20R-CNN.pdf) | [中文版](paper/Mask%20R-CNN-mono.pdf) | [中英对照](paper/Mask%20R-CNN-dual.pdf) | [GitHub](https://github.com/matterport/Mask_RCNN) | [笔记](notes/detection/) |
| **DETR** | [PDF](paper/DETR%20-%20End-to-End%20Object%20Detection%20with%20Transformers.pdf) | [中文版](paper/DETR%20-%20End-to-End%20Object%20Detection%20with%20Transformers-mono.pdf) | [中英对照](paper/DETR%20-%20End-to-End%20Object%20Detection%20with%20Transformers-dual.pdf) | [GitHub](https://github.com/facebookresearch/detr) | [笔记](notes/detection/) |

### 语义分割

| 论文名称 | 原版论文 | 中文版 | 中英对照 | Code | Note |
|---------|---------|--------|---------|------|------|
| **FCN** | [PDF](paper/FCN%20-%20Fully%20Convolutional%20Networks%20for%20Semantic%20Segmentation.pdf) | - | - | [GitHub](https://github.com/shelhamer/fcn.berkeleyvision.org) | [笔记](notes/segmentation/) |
| **U-Net** | [PDF](paper/U-Net%20-%20Convolutional%20Networks%20for%20Biomedical.pdf) | [中文版](paper/U-Net%20-%20Convolutional%20Networks%20for%20Biomedical-mono.pdf) | [中英对照](paper/U-Net%20-%20Convolutional%20Networks%20for%20Biomedical-dual.pdf) | [GitHub](https://github.com/milesial/Pytorch-UNet) | [笔记](notes/segmentation/) |
| **DeepLab** | [PDF](paper/DeepLab%20-%20Semantic%20Image%20Segmentation%20with%20Deep%20Convolutional%20Nets%2C%20Atrous%20Convolution%2C%20and%20Fully%20Connected%20CRFs.pdf) | - | - | [GitHub](https://github.com/tensorflow/models/tree/master/research/deeplab) | [笔记](notes/segmentation/) |
| **SAM** | [PDF](paper/SAM%20-%20Segment%20Anything.pdf) | - | - | [GitHub](https://github.com/facebookresearch/segment-anything) | [笔记](notes/segmentation/) |

### Transformer架构

| 论文名称 | 原版论文 | 中文版 | 中英对照 | Code | Note |
|---------|---------|--------|---------|------|------|
| **Transformer** | [PDF](paper/Attention%20Is%20All%20You%20Need.pdf) | [中文版](paper/Attention%20Is%20All%20You%20Need-mono.pdf) | [中英对照](paper/Attention%20Is%20All%20You%20Need-dual.pdf) | [GitHub](https://github.com/tensorflow/tensor2tensor) | [笔记](notes/transformer/) |
| **BERT** | [PDF](paper/BERT%20--%20%20Pre-training%20of%20Deep%20Bidirectional%20Transformers%20for%20Language%20Understanding.pdf) | [中文版](paper/BERT%20--%20%20Pre-training%20of%20Deep%20Bidirectional%20Transformers%20for%20Language%20Understanding-mono.pdf) | [中英对照](paper/BERT%20--%20%20Pre-training%20of%20Deep%20Bidirectional%20Transformers%20for%20Language%20Understanding-dual.pdf) | [GitHub](https://github.com/google-research/bert) | [笔记](notes/transformer/) |
| **ViT** | [PDF](paper/ViT%20-%20Learning%20Transferable%20Visual%20Models%20From%20Natural%20Language%20Supervision.pdf) | [中文版](paper/ViT%20-%20Learning%20Transferable%20Visual%20Models%20From%20Natural%20Language%20Supervision-mono.pdf) | [中英对照](paper/ViT%20-%20Learning%20Transferable%20Visual%20Models%20From%20Natural%20Language%20Supervision-dual.pdf) | [GitHub](https://github.com/google-research/vision_transformer) | [笔记](notes/transformer/) |
| **Swin Transformer** | [PDF](paper/Swin%20Transformer%20-%20Hierarchical%20Vision%20Transformer%20using%20Shifted%20Windows.pdf) | [中文版](paper/Swin%20Transformer%20-%20Hierarchical%20Vision%20Transformer%20using%20Shifted%20Windows-mono.pdf) | [中英对照](paper/Swin%20Transformer%20-%20Hierarchical%20Vision%20Transformer%20using%20Shifted%20Windows-dual.pdf) | [GitHub](https://github.com/microsoft/Swin-Transformer) | [笔记](notes/transformer/) |

### 自监督学习

| 论文名称 | 原版论文 | 中文版 | 中英对照 | Code | Note |
|---------|---------|--------|---------|------|------|
| **MAE** | [PDF](paper/MAE%20--%20Masked%20Autoencoders%20Are%20Scalable%20Vision%20Learners.pdf) | [中文版](paper/MAE%20--%20Masked%20Autoencoders%20Are%20Scalable%20Vision%20Learners-mono.pdf) | [中英对照](paper/MAE%20--%20Masked%20Autoencoders%20Are%20Scalable%20Vision%20Learners-dual.pdf) | [GitHub](https://github.com/facebookresearch/mae) | [笔记](notes/self-supervised/) |
| **DINOv1** | [PDF](paper/DINOv1%20-%20Emerging%20Properties%20in%20Self-Supervised%20Vision%20Transformers.pdf) | [中文版](paper/DINOv1%20-%20Emerging%20Properties%20in%20Self-Supervised%20Vision%20Transformers-mono.pdf) | [中英对照](paper/DINOv1%20-%20Emerging%20Properties%20in%20Self-Supervised%20Vision%20Transformers-dual.pdf) | [GitHub](https://github.com/facebookresearch/dino) | [笔记](notes/self-supervised/) |

### 多模态学习

| 论文名称 | 原版论文 | 中文版 | 中英对照 | Code | Note |
|---------|---------|--------|---------|------|------|
| **CLIP** | [PDF](paper/CLIP%20-%20Learning%20Transferable%20Visual%20Models%20From%20Natural%20Language%20Supervision.pdf) | - | - | [GitHub](https://github.com/openai/CLIP) | [笔记](notes/multimodal/) |

## 📖 资源说明

每篇论文均提供以下资源：

- **原版论文**：链接至原始英文版本PDF
- **中文版（mono）**：纯中文翻译版本，便于中文读者理解
- **中英对照版（dual）**：中英对照版本，适合双语学习
- **Code**：对应的GitHub代码仓库链接，包含官方实现或高质量第三方实现
- **Note**：个人阅读笔记目录链接，可在对应分类目录下创建笔记

> 💡 **提示**：部分论文可能暂未提供中文翻译版，我们会持续更新。

## 🚀 使用建议

### 学习路径

1. **按时间顺序学习**：从AlexNet开始，按照发表时间顺序阅读，理解深度学习在CV领域的发展脉络
2. **按研究方向学习**：选择感兴趣的研究方向（如目标检测），系统性地学习该领域的经典工作
3. **对比学习**：阅读同一研究方向的不同论文，对比方法差异和改进点

### 阅读建议

- 📄 **先读原版**：对于重要论文，建议先阅读原版英文论文，确保准确理解
- 📝 **做笔记**：在`notes/`目录下创建阅读笔记，记录核心思想、关键公式和实验分析
- 💻 **看代码**：结合代码实现深入理解论文中的技术细节
- 🔗 **关注关联**：注意论文之间的引用关系，理解技术演进过程

### 笔记模板

创建笔记时，建议参考各分类目录下的README模板，包含：
- 论文基本信息（作者、会议/期刊、年份）
- 核心贡献和创新点
- 方法概述和关键技术
- 实验结果分析
- 个人思考和启发

## 🤝 贡献指南

本仓库持续更新中，欢迎贡献：

- ✨ 补充新的经典论文
- 📝 添加或完善阅读笔记
- 🔗 更新代码仓库链接
- 🌐 提供论文翻译版本
- 🐛 修正错误或改进文档

## 📄 许可证

本仓库仅用于学术研究和学习目的。论文版权归原作者所有，代码仓库遵循各自的许可证。

## 📮 联系方式

如有问题或建议，欢迎通过Issue或Pull Request参与讨论。

