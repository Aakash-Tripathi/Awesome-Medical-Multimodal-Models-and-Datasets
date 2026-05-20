# Task-Specific Medical Models

[← Back to main README](./README.md)

---

## 🎯 Medical Image Segmentation

| Model | Modality | Task | Year | Paper | Code |
|---|---|---|---|---|---|
| **MedSAM** | 10 modalities, 2D (1.57M image-mask pairs, 30+ cancer types) | Universal seg. | 2024 | [Nature Comms](https://www.nature.com/articles/s41467-024-44824-z) | [GitHub](https://github.com/bowang-lab/MedSAM) |
| **MedSAM2** | 3D + video (455K 3D pairs + 76K frames) | 3D / temporal seg | 2025 | [arXiv:2504.03600](https://arxiv.org/abs/2504.03600) | [GitHub](https://github.com/bowang-lab/MedSAM2) |
| **SAM-Med2D** | 2D (4.6M images, 19.7M masks) | Promptable seg | 2023 | [arXiv:2308.16184](https://arxiv.org/abs/2308.16184) | [GitHub](https://github.com/OpenGVLab/SAM-Med2D) |
| **SAM-Med3D** | 3D volumes | Volumetric seg | 2023 | [arXiv:2310.15161](https://arxiv.org/abs/2310.15161) | [GitHub](https://github.com/uni-medical/SAM-Med3D) |
| **MCP-MedSAM** | Lightweight med SAM | Efficient seg | 2025 | [MELBA](https://www.melba-journal.org/papers/2025:008.html) | — |
| **SAT** | 3D + text prompts | Text-driven seg | 2025 | [npj DM](https://www.nature.com/articles/s41746-025-01964-w) | [GitHub](https://github.com/zhaoziheng/SAT) |
| **nnU-Net / nnU-Net v2** | 2D / 3D | Self-configuring U-Net | 2021 | [Nat. Methods](https://www.nature.com/articles/s41592-020-01008-z) | [GitHub](https://github.com/MIC-DKFZ/nnUNet) |
| **TotalSegmentator** | CT, 104+ structures | Whole-body seg | 2023 | [Radiology AI](https://pubs.rsna.org/doi/10.1148/ryai.230024) | [GitHub](https://github.com/wasserth/TotalSegmentator) |
| **STU-Net** | Scalable med seg | 2D / 3D | 2023 | [arXiv:2304.06716](https://arxiv.org/abs/2304.06716) | [GitHub](https://github.com/Ziyan-Huang/STU-Net) |
| **UniverSeg** | Few-shot universal | Cross-task seg | 2023 | [ICCV 2023](https://arxiv.org/abs/2304.06131) | [GitHub](https://github.com/JJGO/UniverSeg) |
| **BiomedParse** | Image + text seg | Universal biomed seg | 2024 | [Nature Methods](https://www.nature.com/articles/s41592-024-02499-w) | [GitHub](https://github.com/microsoft/BiomedParse) |

---

## 📋 Medical Report Generation (RG)

| Model | Modality | Year | Paper | Code |
|---|---|---|---|---|
| **R2Gen / R2GenCMN** | CXR | 2020 / 21 | [EMNLP](https://arxiv.org/abs/2010.16056) · [ACL](https://arxiv.org/abs/2105.04578) | [GitHub](https://github.com/cuhksz-nlp/R2GenCMN) |
| **MAIRA-1 / 2** | CXR (grounded) | 2023 / 24 | [arXiv:2311.13668](https://arxiv.org/abs/2311.13668) · [arXiv:2406.04449](https://arxiv.org/abs/2406.04449) | [HF](https://huggingface.co/microsoft/maira-2) |
| **LLaVA-Rad** | CXR | 2024 | [arXiv:2403.08002](https://arxiv.org/abs/2403.08002) | [GitHub](https://github.com/microsoft/LLaVA-Rad) |
| **CheXagent** | CXR | 2024 | [arXiv:2401.12208](https://arxiv.org/abs/2401.12208) | [GitHub](https://github.com/Stanford-AIMI/CheXagent) |
| **CXR-LLaVA** | CXR | 2023 | [arXiv:2310.18341](https://arxiv.org/abs/2310.18341) | [GitHub](https://github.com/ECOFRI/CXR_LLAVA) |
| **RGRG** | CXR (region-guided) | 2023 | [CVPR 2023](https://arxiv.org/abs/2304.08295) | [GitHub](https://github.com/ttanida/rgrg) |
| **Flamingo-CXR** | CXR (DeepMind) | 2023 | [arXiv:2311.18260](https://arxiv.org/abs/2311.18260) | (closed) |
| **CT2Rep / RaDialog** | 3D CT / dialog | 2024 | (arXiv) | (various) |

---

## ❓ Medical VQA

| Model | Coverage | Year | Paper | Code |
|---|---|---|---|---|
| **LLaVA-Med** | General biomed | 2023 | [arXiv:2306.00890](https://arxiv.org/abs/2306.00890) | [GitHub](https://github.com/microsoft/LLaVA-Med) |
| **Med-Flamingo** | Few-shot MM | 2023 | [arXiv:2307.15189](https://arxiv.org/abs/2307.15189) | [GitHub](https://github.com/snap-stanford/med-flamingo) |
| **BiomedGPT** | Vision+lang+MM | 2023 | [arXiv:2305.17100](https://arxiv.org/abs/2305.17100) | [GitHub](https://github.com/taokz/BiomedGPT) |
| **MedVInT / PMC-VQA** | Biomed VQA | 2023 | [arXiv:2305.10415](https://arxiv.org/abs/2305.10415) | [GitHub](https://github.com/xiaoman-zhang/PMC-VQA) |
| **PMC-CLIP** | Biomed retrieval | 2023 | [MICCAI 2023](https://arxiv.org/abs/2303.07240) | [GitHub](https://github.com/WeixiongLin/PMC-CLIP) |
| **STLLaVA-Med** | Data-efficient (DPO) | 2024 | [arXiv:2406.19973](https://arxiv.org/abs/2406.19973) | — |

---

## 🧮 Classic Classification SOTA

| Model | Application | Year | Paper |
|---|---|---|---|
| **CheXNet** | Pneumonia (CXR) | 2017 | [arXiv:1711.05225](https://arxiv.org/abs/1711.05225) |
| **DeepDR / DeepDR-Plus** | Diabetic retinopathy | 2017–23 | (Nature Comms) |
| **Inception-v3 for skin (Esteva et al.)** | Dermatology | 2017 | [Nature](https://www.nature.com/articles/nature21056) |

---

## ⏳ Multimodal Survival Models

See **[README_MULTIMODAL_FUSION_MODELS.md](./README_MULTIMODAL_FUSION_MODELS.md)** for the dedicated survival section.

---

[← Back to main README](./README.md) · [→ Multimodal Fusion Models](./README_MULTIMODAL_FUSION_MODELS.md)
