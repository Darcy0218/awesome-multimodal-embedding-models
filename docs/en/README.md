[EN](README.md)|[ZH](../zh/README.md)
# Summary of Multimodal Embedding Models

This project collects and organizes detailed information on various multimodal embedding models, including model specifications, output dimensions, and usage instructions.

## Model Series

### General Embedding Models

#### Visual Embedding Models
1. [ViT Series](docs/general_embedding/visual_embedding/vit_series/README.md)
   - vit-base-patch16-224-in21k
   - vit-huge-patch14-224-in21k

2. [DINO Series](docs/general_embedding/visual_embedding/dino_series/README.md)
   - DINOv2 Series (small, base, large, giant)
   - WebSSL-DINO Series (various 1b-7b variants)

### Special Embedding Models
1. [Street Scene Model Series](docs/special_embedding/street_clip_series/README.md)
   - StreetCLIP

#### Cross-modal Embedding Models
1. [SigLiP Series](docs/general_embedding/cross_modal_embedding/siglip_series/README.md)
   - siglip2-giant-opt-patch16-384

2. [InternViT Series](docs/general_embedding/cross_modal_embedding/internvit_series/README.md)
   - InternViT-300M-448px-V2_5

3. [Gme-Qwen Series](docs/general_embedding/cross_modal_embedding/gme_qwen_series/README.md)
   - gme-Qwen2-VL-7B-Instruct

## Usage Instructions

For detailed information on each series, please refer to the README.md file in the corresponding directory.

## Directory Structure

```
.
├── docs/                     # Documentation directory
│   ├── general_embedding/    # General embedding models
│   │   ├── visual_embedding/ # Visual embedding models
│   │   │   ├── vit_series/   # ViT series
│   │   │   └── dino_series/  # DINO series
│   │   │
│   │   └── cross_modal_embedding/ # Cross-modal embedding models
│   │       ├── siglip_series/    # SigLiP series
│   │       ├── internvit_series/ # InternViT series
│   │       └── gme_qwen_series/  # Gme-Qwen series
│   │
│   └── special_embedding/    # Special embedding models
│       └── street_clip_series/   # Street scene model series
│
├── README.md
└── embedding_models_summary.md
```

## Evaluation Metrics

The main metrics for evaluating multimodal embedding models include:

- Cross-modal retrieval accuracy
- Zero-shot classification accuracy
- Semantic similarity correlation
- Computational efficiency
- Model size

## Application Scenarios

Multimodal embedding models play an important role in the following scenarios:

1. Cross-modal retrieval
   - Text-to-image search
   - Image-to-text search
   - Audio-to-text search

2. Zero-shot classification
   - Image classification
   - Audio classification
   - Video classification

3. Multimodal content understanding
   - Image captioning
   - Video understanding
   - Multimodal question answering

4. Recommendation systems
   - Cross-modal content recommendation
   - Personalized search

## Contribution Guide

Contributions of new models, evaluation results, or suggestions for improvement are welcome! Please follow these steps:

1. Fork this repository
2. Create a new branch
3. Submit your changes
4. Open a Pull Request

## License

MIT License

## Acknowledgements

Thanks to all researchers and developers in the open-source community whose work has made significant contributions to the field of multimodal AI. 