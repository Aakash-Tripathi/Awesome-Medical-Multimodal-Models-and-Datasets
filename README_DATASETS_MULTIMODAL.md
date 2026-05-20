# Multimodal Datasets

[← Back to main README](./README.md)

---

## 🖼️ Image + Text (biomedical / radiology / pathology)

| Dataset | Modality | Pairs | Year | Paper | Link |
|---|---|---|---|---|---|
| **MIMIC-CXR** | CXR + reports | 377K img / 227K studies | 2019 | [Sci. Data](https://www.nature.com/articles/s41597-019-0322-0) | [PhysioNet](https://physionet.org/content/mimic-cxr/) |
| **IU X-ray (Open-i)** | CXR + reports | 7,470 / 3,955 | 2016 | [JAMIA](https://doi.org/10.1093/jamia/ocv080) | [Open-i](https://openi.nlm.nih.gov/) |
| **ROCO / ROCOv2** | Radiology figures + captions (PMC) | 81K / 80K+ | 2018 / 24 | [LABELS@MICCAI](https://doi.org/10.1007/978-3-030-01364-6_20) · [arXiv:2405.10004](https://arxiv.org/abs/2405.10004) | [GitHub](https://github.com/razorx89/roco-dataset) |
| **MedICaT** | Biomed figures + captions + refs | 217K | 2020 | [EMNLP 2020 Findings](https://arxiv.org/abs/2010.06000) | [GitHub](https://github.com/allenai/medicat) |
| **PMC-OA** | Biomed image-caption (subfig aligned) | 1.6M | 2023 | [MICCAI 2023 (PMC-CLIP)](https://arxiv.org/abs/2303.07240) | [HF](https://huggingface.co/datasets/axiong/pmc_oa) |
| **PMC-15M** | Biomed image-text (BiomedCLIP corpus) | 15M | 2023 | [arXiv:2303.00915](https://arxiv.org/abs/2303.00915) | (not redistributed) |
| **OpenPath** | Pathology image + tweet text | 208,414 | 2023 | [Nature Medicine](https://doi.org/10.1038/s41591-023-02504-3) | (PLIP repo) |
| **Quilt-1M** | Pathology image-text (YouTube + other; Quilt core = 768,826 pairs from 1,087 hr of expert videos) | 1M | 2023 | [NeurIPS 2023](https://arxiv.org/abs/2306.11207) | [GitHub](https://github.com/wisdomikezogwo/quilt1m) |
| **PathGen-1.6M** | LMM-refined pathology pairs | 1.6M | 2024 | [arXiv:2407.00203](https://arxiv.org/abs/2407.00203) | — |
| **PathCap** | Pathology captions | 200K | 2023 | (arXiv) | — |
| **ARCH** | Pathology image-text from papers | ~8K | 2021 | [CVPR 2021](https://arxiv.org/abs/2106.13435) | — |
| **PubMedVision** | Vision-aware refined PMC QA | 1.3M | 2024 | [arXiv:2406.19280](https://arxiv.org/abs/2406.19280) | [GitHub](https://github.com/FreedomIntelligence/HuatuoGPT-Vision) |
| **CT-RATE** | 3D chest CT + reports | 25K | 2024 | [arXiv:2403.17834](https://arxiv.org/abs/2403.17834) | [HF](https://huggingface.co/datasets/ibrahimhamamci/CT-RATE) |
| **MedTrinity-25M** | 25M biomedical image-text triplets | 25M | 2024 | [arXiv:2408.02900](https://arxiv.org/abs/2408.02900) | [GitHub](https://github.com/UCSC-VLAA/MedTrinity-25M) |

---

## 🧬 WSI + Omics + Clinical (oncology)

| Resource | Modalities | Reference |
|---|---|---|
| **TCGA pan-cancer** | WSI + RNA-seq + CNV + mut + methylation + clinical | NIH / NCI GDC |
| **CPTAC** | WSI + proteomics + genomics + clinical | proteomics.cancer.gov |
| **MSK-IMPACT (cBioPortal)** | Targeted seq + clinical | MSKCC |
| **Honeybee** | Multimodal oncology embedding framework | [arXiv:2405.07460](https://arxiv.org/abs/2405.07460) |
| **HEST-1k** | H&E + spatial transcriptomics | [GitHub](https://github.com/mahmoodlab/hest) |

---

## 🧠 EHR + Imaging Linked

| Resource | Modalities | Year | Link |
|---|---|---|---|
| **MIMIC-CXR ↔ MIMIC-IV** | CXR + ICU EHR + notes | 2019 / 2023 | (PhysioNet linkable IDs) |
| **UK Biobank imaging** | Brain / cardiac MRI / DXA / retinal + EHR + genomics | 2014+ | [ukbiobank.ac.uk](https://www.ukbiobank.ac.uk/) |
| **EMBED** | Mammography + EHR | 2023 | [Radiology AI](https://pubs.rsna.org/doi/10.1148/ryai.220047) |

---

[← Back to main README](./README.md) · [→ VQA Benchmarks](./README_DATASETS_VQA_BENCHMARKS.md)
