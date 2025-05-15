# 多模态嵌入模型总结

## 目录
1. [ViT系列](#vit系列)
2. [街景专用模型系列](#街景专用模型系列)
3. [DINO系列](#dino系列)
4. [SigLiP系列](#siglip系列)
5. [InternViT系列](#internvit系列)
6. [Gme-Qwen系列](#gme-qwen系列)

## ViT系列

### vit-base-patch16-224-in21k
- 模型型号: google/vit-base-patch16-224-in21k
- 输出embedding维度: 768
- 灌库时间: 25.4.27

### vit-huge-patch14-224-in21k
- 模型型号: google/vit-huge-patch14-224-in21k
- 输出embedding维度: 1280
- 灌库时间: 25.4.27

## 街景专用模型系列

### StreetCLIP
- 模型型号: geolocal/StreetCLIP
- 输出embedding维度: 768
- 灌库时间: 25.4.27

## DINO系列

### dinov2-small
- 模型型号: facebook/dinov2-small
- 输出embedding维度: 
  - CLS feature: 384
  - Patch feature: (256,384)
- 灌库时间: 25.5.13

### dinov2-base
- 模型型号: facebook/dinov2-base
- 输出embedding维度:
  - CLS feature: 768
  - Patch feature: (256,768)
- 灌库时间: 25.5.13

### dinov2-large
- 模型型号: facebook/dinov2-large
- 输出embedding维度:
  - CLS feature: 1024
  - Patch feature: (256,1024)
- 灌库时间: 25.5.13

### dinov2-giant
- 模型型号: facebook/dinov2-giant
- 输出embedding维度:
  - CLS feature: 1536
  - Patch feature: (256,1536)
- 灌库时间: 25.5.13

### webssl-dino系列

#### webssl-dino1b-full2b-224
- 模型型号: facebook/webssl-dino1b-full2b-224
- 输出embedding维度:
  - CLS feature: 1536
  - Patch feature: (256,1536)

#### webssl-dino2b-full2b-224
- 模型型号: facebook/webssl-dino2b-full2b-224
- 输出embedding维度:
  - CLS feature: 2688
  - Patch feature: (256,2688)

#### webssl-dino2b-light2b-224
- 模型型号: facebook/webssl-dino2b-light2b-224
- 输出embedding维度:
  - CLS feature: 2688
  - Patch feature: (256,2688)

#### webssl-dino2b-heavy2b-224
- 模型型号: facebook/webssl-dino2b-heavy2b-224
- 输出embedding维度:
  - CLS feature: 2688
  - Patch feature: (256,2688)

#### webssl-dino3b-light2b-224
- 模型型号: facebook/webssl-dino3b-light2b-224
- 输出embedding维度:
  - CLS feature: 3072
  - Patch feature: (256,3072)

#### webssl-dino3b-heavy2b-224
- 模型型号: facebook/webssl-dino3b-heavy2b-224
- 输出embedding维度:
  - CLS feature: 3072
  - Patch feature: (256,3072)

#### webssl-dino7b-full8b-224
- 模型型号: facebook/webssl-dino7b-full8b-224
- 输出embedding维度:
  - CLS feature: 4096
  - Patch feature: (256,4096)

#### webssl-dino7b-full8b-378
- 模型型号: facebook/webssl-dino7b-full8b-378
- 输出embedding维度:
  - CLS feature: 4096
  - Patch feature: (729,4096)

#### webssl-dino7b-full8b-518
- 模型型号: facebook/webssl-dino7b-full8b-518
- 输出embedding维度:
  - CLS feature: 4096
  - Patch feature: (1369,4096)

## SigLiP系列

### siglip2-giant-opt-patch16-384
- 模型型号: google/siglip2-giant-opt-patch16-384
- 输出embedding维度: 1536

## InternViT系列

### InternViT-300M-448px-V2_5
- 模型型号: OpenGVLab/InternViT-300M-448px-V2_5
- 输出embedding维度: 1024

## Gme-Qwen系列

### gme-Qwen2-VL-7B-Instruct
- 模型型号: Alibaba-NLP/gme-Qwen2-VL-7B-Instruct 