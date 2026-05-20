# Multimodal Fusion Models (2+ modalities)

[← Back to main README](./README.md)

---

## 🧪 WSI + Omics (± Clinical) — Cancer Survival

| Model | Modalities | Fusion | Cohort | Year | Paper | Code |
|---|---|---|---|---|---|---|
| **Pathomic Fusion** | WSI + genomics + cell graph | Kronecker tensor + gated attn | TCGA glioma | 2020 | [IEEE TMI / arXiv:1912.08937](https://arxiv.org/abs/1912.08937) | [GitHub](https://github.com/mahmoodlab/PathomicFusion) |
| **MCAT** | WSI + genomics | Co-attention transformer | TCGA pan-cancer | 2021 | [ICCV 2021](https://openaccess.thecvf.com/content/ICCV2021/html/Chen_Multimodal_Co-Attention_Transformer_for_Survival_Prediction_in_Gigapixel_Whole_Slide_ICCV_2021_paper.html) | [GitHub](https://github.com/mahmoodlab/MCAT) |
| **PORPOISE** | WSI + molecular + clinical | AMIL + SNN + Kronecker | 14 TCGA cancers | 2022 | [Cancer Cell](https://doi.org/10.1016/j.ccell.2022.07.004) | [GitHub](https://github.com/mahmoodlab/PORPOISE) |
| **MOTCat** | WSI + genomics | OT co-attention | TCGA | 2023 | [ICCV 2023 / arXiv:2306.08330](https://arxiv.org/abs/2306.08330) | [GitHub](https://github.com/Innse/MOTCat) |
| **CMTA** | WSI + genomics | Cross-modal translation | TCGA | 2023 | (ICCV 2023) | — |
| **SurvPath** | WSI + pathway transcriptomics | Bidirectional transformer | 5 TCGA cohorts | 2024 | [CVPR 2024 / arXiv:2304.06819](https://arxiv.org/abs/2304.06819) | [GitHub](https://github.com/mahmoodlab/SurvPath) |
| **MMP** | WSI prototypes + transcriptomics | Gaussian-mixture prototypes | TCGA | 2024 | [arXiv:2407.00224](https://arxiv.org/abs/2407.00224) | — |
| **MultiSurv** | Multi-omic + clinical + WSI | MT multimodal | TCGA | 2021 | [Sci. Rep.](https://www.nature.com/articles/s41598-021-92799-4) | [GitHub](https://github.com/luisvalesilva/multisurv) |
| **MADSurv** | WSI + genomics | Mixture-of-attention | TCGA | 2025 | (arXiv) | — |
| **PIBD** | WSI + genomics | Prototype-IB disentanglement | TCGA | 2024 | (CVPR 2024) | — |
| **HiMT** | Hierarchical WSI + genomics | Low-mem co-attention | TCGA | 2022 | [arXiv:2211.16632](https://arxiv.org/abs/2211.16632) | — |
| **SurvPGC** | WSI + genomics + clinical (prompts) | LLM prompts | TCGA | 2025 | [npj Digital Medicine](https://www.nature.com/articles/s41746-025-02257-y) | — |
| **CLAM** | WSI weakly-supervised | Attention MIL | — | 2021 | [Nat. BME](https://www.nature.com/articles/s41551-020-00682-w) | [GitHub](https://github.com/mahmoodlab/CLAM) |

> **Systematic review (Jennings et al., 2025, [arXiv:2507.16876](https://arxiv.org/abs/2507.16876), PROSPERO CRD42024594745):** 48 studies, 19 cancer types, all using TCGA. c-index range **0.550–0.857**; all studies showed unclear / high risk of bias with limited external validation and little clinical-utility evaluation.

---

## 🩻 Image + EHR / Clinical Data

| Model | Modalities | Year | Paper | Code |
|---|---|---|---|---|
| **MedFuse** | CXR + ICU EHR time series | 2022 | [MLHC 2022](https://arxiv.org/abs/2207.07027) | [GitHub](https://github.com/nyuad-cai/MedFuse) |
| **HAIM (Holistic AI in Medicine)** | EHR + images + notes + WSIs | 2022 | [npj DM](https://www.nature.com/articles/s41746-022-00689-4) | [GitHub](https://github.com/lrsoenksen/HAIM) |
| **MMTM** | Image + tabular | 2020 | [CVPR 2020](https://openaccess.thecvf.com/content_CVPR_2020/html/Joze_MMTM_Multimodal_Transfer_Module_for_CNN_Fusion_CVPR_2020_paper.html) | – |
| **DAFT** | Image + tabular conditioning | 2021 | [MICCAI 2021](https://link.springer.com/chapter/10.1007/978-3-030-87240-3_66) | [GitHub](https://github.com/ai-med/DAFT) |

---

## 🧬 EHR + Omics

| Model | Modalities | Year | Paper |
|---|---|---|---|
| **EHR FM + PRS (Verily)** | EHR + polygenic risk scores | 2025 | [bioRxiv](https://www.biorxiv.org/content/10.1101/2025.10.26.684668v1) |
| **Med-Gemini-Polygenic** | Genetic + clinical | 2024 | (see Med-Gemini) |

---

## 🧫 Spatial Transcriptomics + Histology

| Model / Dataset | Modalities | Year | Paper | Code |
|---|---|---|---|---|
| **STimage-1K4M** | Pathology + spatial transcriptomics | 2024 | [arXiv:2406.06393](https://arxiv.org/abs/2406.06393) | — |
| **HEST-1k** | H&E + spatial gene expression | 2024 | [NeurIPS 2024 / arXiv:2406.16192](https://arxiv.org/abs/2406.16192) | [GitHub](https://github.com/mahmoodlab/hest) |

---

[← Back to main README](./README.md) · [→ Imaging Datasets](./README_DATASETS_IMAGING.md)
