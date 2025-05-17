# Multimodal Embedding Models Summary

This project collects and organizes detailed information about various multimodal embedding models, including model specifications, output dimensions, and usage instructions.

## Model Series

### General Embedding Models

#### Visual Embedding Models
1. [ViT Series](docs/en/general_embedding/visual_embedding/vit_series/README.md)
   - vit-base-patch16-224-in21k
   - vit-huge-patch14-224-in21k

2. [DINO Series](docs/en/general_embedding/visual_embedding/dino_series/README.md)
   - DINOv2 series (small, base, large, giant)
   - WebSSL-DINO series (various variants from 1b-7b)

### Special Embedding Models
1. [Street Scene Model Series](docs/en/special_embedding/street_clip_series/README.md)
   - StreetCLIP

#### Cross-modal Embedding Models
1. [SigLiP Series](docs/en/general_embedding/cross_modal_embedding/siglip_series/README.md)
   - siglip2-giant-opt-patch16-384

2. [InternViT Series](docs/en/general_embedding/cross_modal_embedding/internvit_series/README.md)
   - InternViT-300M-448px-V2_5

3. [Gme-Qwen Series](docs/en/general_embedding/cross_modal_embedding/gme_qwen_series/README.md)
   - gme-Qwen2-VL-7B-Instruct

## Usage Instructions

Please refer to the README.md file in each corresponding directory for specific information about each series.

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

Key metrics for evaluating multimodal embedding models include:

- Cross-modal Retrieval Accuracy
- Zero-shot Classification Accuracy
- Semantic Similarity Correlation
- Computational Efficiency
- Model Size

## Application Scenarios

Multimodal embedding models play important roles in the following scenarios:

1. Cross-modal Retrieval
   - Text-to-image search
   - Image-to-text search
   - Audio-to-text search

2. Zero-shot Classification
   - Image classification
   - Audio classification
   - Video classification

3. Multimodal Content Understanding
   - Image captioning
   - Video understanding
   - Multimodal Q&A

4. Recommendation Systems
   - Cross-modal content recommendation
   - Personalized search

## Contributing Guidelines

Contributions of new models, evaluation results, or improvement suggestions are welcome! Please follow these steps:

1. Fork this repository
2. Create a new branch
3. Submit your changes
4. Create a Pull Request

## License

MIT License

## Acknowledgments

Thanks to all researchers and developers in the open-source community whose work has made significant contributions to the field of multimodal AI. 