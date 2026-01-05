# 项目目录结构说明

## 目录结构

```
Vision-PaperLab/
├── paper/                    # 论文PDF文件目录
│   ├── *.pdf                 # 原版论文
│   ├── *-mono.pdf            # 中文翻译版
│   └── *-dual.pdf            # 中英对照版
│
├── notes/                    # 阅读笔记目录
│   ├── classification/       # 图像分类相关笔记
│   ├── detection/            # 目标检测相关笔记
│   ├── segmentation/        # 语义分割相关笔记
│   ├── transformer/          # Transformer架构相关笔记
│   ├── self-supervised/     # 自监督学习相关笔记
│   └── multimodal/          # 多模态学习相关笔记
│
├── docs/                     # 文档目录
│   └── STRUCTURE.md         # 本文件：目录结构说明
│
├── README.md                 # 项目主README
└── .gitignore               # Git忽略文件配置
```

## 目录说明

### paper/
存放所有论文的PDF文件，包括：
- 原版论文（英文）
- 中文翻译版（文件名以`-mono.pdf`结尾）
- 中英对照版（文件名以`-dual.pdf`结尾）

### notes/
存放论文阅读笔记，按研究方向分类：
- **classification/**: 图像分类相关论文笔记（AlexNet, VGG, ResNet, ResNetV2, GoogleNet）
- **detection/**: 目标检测相关论文笔记（R-CNN, Faster R-CNN, FPN, Mask R-CNN, DETR）
- **segmentation/**: 语义分割相关论文笔记（FCN, U-Net, DeepLab, SAM）
- **transformer/**: Transformer架构相关论文笔记（Transformer, BERT, ViT, Swin Transformer）
- **self-supervised/**: 自监督学习相关论文笔记（MAE, DINOv1）
- **multimodal/**: 多模态学习相关论文笔记（CLIP）

### docs/
存放项目相关文档和说明文件。

## 文件命名规范

### 论文文件
- 原版：`论文名称.pdf`
- 中文版：`论文名称-mono.pdf`
- 中英对照：`论文名称-dual.pdf`

### 笔记文件
建议使用Markdown格式，命名规范：
- `论文名称_notes.md` 或
- `论文缩写_notes.md`

例如：
- `AlexNet_notes.md`
- `ResNet_notes.md`
- `Faster_RCNN_notes.md`

## 使用建议

1. 阅读论文时，建议在对应的`notes/`子目录下创建笔记文件
2. 笔记文件使用Markdown格式，便于版本控制和阅读
3. 可以包含论文摘要、核心思想、关键公式、实验分析等内容
4. 建议在笔记中引用论文中的关键图表和公式

