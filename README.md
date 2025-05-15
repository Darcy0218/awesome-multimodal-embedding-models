# 多模态嵌入模型总结

本项目收集和整理了各种多模态嵌入模型的详细信息，包括模型规格、输出维度和使用说明等。

## 模型系列

1. [ViT系列](vit_series/README.md)
   - vit-base-patch16-224-in21k
   - vit-huge-patch14-224-in21k

2. [街景专用模型系列](street_clip_series/README.md)
   - StreetCLIP

3. [DINO系列](dino_series/README.md)
   - DINOv2系列 (small, base, large, giant)
   - WebSSL-DINO系列 (1b-7b各种变体)

4. [SigLiP系列](siglip_series/README.md)
   - siglip2-giant-opt-patch16-384

5. [InternViT系列](internvit_series/README.md)
   - InternViT-300M-448px-V2_5

6. [Gme-Qwen系列](gme_qwen_series/README.md)
   - gme-Qwen2-VL-7B-Instruct

## 使用说明

每个系列的具体信息请查看对应目录下的README.md文件。

## 目录

- [模型列表](#模型列表)
- [评估指标](#评估指标)
- [应用场景](#应用场景)
- [贡献指南](#贡献指南)

## 模型列表

### 文本-图像模型
- CLIP (Contrastive Language-Image Pre-training)
- OpenCLIP
- CoCa (Contrastive Captioner)
- BLIP-2
- Flamingo

### 文本-音频模型
- CLAP (Contrastive Language-Audio Pre-training)
- AudioCLIP

### 多模态模型
- ImageBind
- CoDi
- Unified-IO

## 评估指标

评估多模态嵌入模型的主要指标包括：

- 跨模态检索准确率（Cross-modal Retrieval Accuracy）
- 零样本分类准确率（Zero-shot Classification Accuracy）
- 语义相似度相关性（Semantic Similarity Correlation）
- 计算效率（Computational Efficiency）
- 模型大小（Model Size）

## 应用场景

多模态嵌入模型在以下场景中发挥着重要作用：

1. 跨模态检索
   - 文本到图像搜索
   - 图像到文本搜索
   - 音频到文本搜索

2. 零样本分类
   - 图像分类
   - 音频分类
   - 视频分类

3. 多模态内容理解
   - 图像描述生成
   - 视频理解
   - 多模态问答

4. 推荐系统
   - 跨模态内容推荐
   - 个性化搜索

## 贡献指南

欢迎贡献新的模型、评估结果或改进建议！请遵循以下步骤：

1. Fork 本仓库
2. 创建新的分支
3. 提交你的更改
4. 发起 Pull Request

## 许可证

MIT License

## 致谢

感谢所有开源社区的研究者和开发者，他们的工作为多模态AI领域做出了重要贡献。 