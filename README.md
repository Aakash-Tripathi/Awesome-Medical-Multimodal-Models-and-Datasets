# Awesome Medical Multimodal Models & Datasets [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![GitHub stars](https://img.shields.io/github/stars/Aakash-Tripathi/Awesome-Medical-Multimodal-Models-and-Datasets.svg?style=social)](https://github.com/Aakash-Tripathi/Awesome-Medical-Multimodal-Models-and-Datasets/stargazers)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-May%202026-blue)](#)

> A comprehensive, curated catalog of **medical multimodal AI models** and **medical datasets** across radiology, pathology (WSI), ophthalmology, dermatology, EHR, omics (genomics / transcriptomics / proteomics), and combined multimodal benchmarks.
>
> Tables follow the format: *Name · Modalities · Task · Year · Paper · Code*.

---

## 📚 Table of Contents

| Section | File |
|---|---|
| 🏛️ **Foundation Models** — pathology, radiology, EHR, omics, generalist medical LLMs | [→ Foundation Models](./README_FOUNDATION_MODELS.md) |
| 🎯 **Task-Specific Models** — segmentation, report generation, VQA, classification | [→ Task-Specific Models](./README_TASK_SPECIFIC_MODELS.md) |
| 🔀 **Multimodal Fusion Models** — WSI+omics, image+EHR, EHR+omics | [→ Multimodal Fusion](./README_MULTIMODAL_FUSION_MODELS.md) |
| 🩻 **Imaging Datasets** — CXR, CT/MRI, WSI, fundus, dermoscopy, ECG, US | [→ Imaging Datasets](./README_DATASETS_IMAGING.md) |
| 🧬 **Omics Datasets** — TCGA, CPTAC, ICGC, HCA, GTEx, UKB, spatial transcriptomics | [→ Omics Datasets](./README_DATASETS_OMICS.md) |
| 🏥 **EHR Datasets** — MIMIC-III/IV, eICU, HiRID, UK Biobank, All of Us | [→ EHR Datasets](./README_DATASETS_EHR.md) |
| 🔗 **Multimodal Datasets** — image+text, WSI+omics, EHR+imaging | [→ Multimodal Datasets](./README_DATASETS_MULTIMODAL.md) |
| ❓ **VQA & Reasoning Benchmarks** — VQA-RAD, SLAKE, OmniMedVQA, GMAI-MMBench, MedXpertQA | [→ VQA Benchmarks](./README_DATASETS_VQA_BENCHMARKS.md) |
| 📜 **Foundational Research** — seminal papers (CLIP, ConVIRT, Pathomic Fusion, U-Net, Med-PaLM, scGPT, ...) | [→ Foundational Research](./README_FOUNDATIONAL_RESEARCH.md) |

---

## 🚀 Quick Highlights — Most-impactful models in 2026

| Model | Why it matters | Year |
|---|---|---|
| **UNI / CONCH** (Mahmood Lab, *Nature Medicine*) | UNI: vision-only DINOv2 on >100M patches; CONCH: vision-language on 1.17M image-text pairs. | 2024 |
| **Prov-GigaPath** (Microsoft/Providence, *Nature*) | First WSI FM with LongNet slide-level pretraining on 1.3B tiles from 171,189 WSIs. | 2024 |
| **Virchow / Virchow2** (Paige.AI, *Nat. Medicine*) | 632M-param ViT trained on 1.5M WSIs (Virchow); Virchow2 scales to 3.1M slides / 1.7–1.9B tiles. | 2024 |
| **MedSAM / MedSAM2** | Universal medical segmentation FM: 1.57M image-mask pairs (10 modalities, 30+ cancer types); MedSAM2 adds 455K 3D pairs + 76K video frames. | 2024–25 |
| **RadFM** (Wu et al., *Nat. Comms* 2025) | Generalist 2D+3D radiology FM trained on MedMD (16M scans, 5,000+ diseases). | 2025 |
| **LLaVA-Med · Med-Flamingo · BiomedGPT** | Open generalist biomedical VLMs. | 2023–24 |
| **Med-PaLM M · Med-Gemini** (Google) | Closed SOTA generalist medical multimodal models; Med-Gemini reaches 91.1 % on MedQA (USMLE). | 2023–24 |
| **scGPT · Geneformer · Nucleotide Transformer** | Single-cell and DNA foundation models. scGPT pretrained on 33M scRNA-seq cells (CELLxGENE, 51 organs/tissues, 441 studies). | 2023–25 |
| **CLMBR · MOTOR · ETHOS** | EHR foundation models on structured patient timelines. MOTOR: +4.6 % C-statistic over SOTA across 19 tasks on 3 databases. | 2022–24 |

### Most-used datasets

| Dataset | What | Size |
|---|---|---|
| **MIMIC-CXR / MIMIC-IV** | CXR + reports / ICU EHR | 377K CXRs · 300K+ admissions |
| **TCGA** | Pan-cancer multi-omics + WSI + clinical | 33 cancers, ~11K patients |
| **CheXpert / NIH ChestX-ray14 / PadChest** | CXR with labels | 224K · 112K · 160K |
| **Quilt-1M / OpenPath / PMC-OA** | Pathology / biomed image-text pairs | 1M · 208K · 1.6M |
| **HAM10000 / ISIC** | Dermoscopy | 10K · 33K+ |
| **CAMELYON16/17 · PANDA** | Pathology WSI challenges | ~1K · 10,616 WSIs |
| **OmniMedVQA / GMAI-MMBench / MedXpertQA-MM** | VQA benchmarks | 128K · 26K · 2K |

---

## 🧭 How to Use

1. **Looking for a foundation model?** → [README_FOUNDATION_MODELS.md](./README_FOUNDATION_MODELS.md)
2. **Need a benchmark dataset?** → the `README_DATASETS_*.md` files
3. **Building a multimodal fusion system?** → [README_MULTIMODAL_FUSION_MODELS.md](./README_MULTIMODAL_FUSION_MODELS.md) + [README_DATASETS_MULTIMODAL.md](./README_DATASETS_MULTIMODAL.md)
4. **Want historical context?** → [README_FOUNDATIONAL_RESEARCH.md](./README_FOUNDATIONAL_RESEARCH.md)

---

## 🤝 Contributing

PRs welcome! Use the existing table format and include:
- a working paper link (arXiv / journal DOI),
- a working code link (GitHub / Hugging Face) where available,
- a one-line description.

---

## 📖 Citation

```bibtex
@misc{awesome_medical_mm_2026,
  title  = {Awesome Medical Multimodal Models and Datasets},
  author = {Tripathi, Aakash and Contributors},
  year   = {2026},
  howpublished = {\url{https://github.com/Aakash-Tripathi/Awesome-Medical-Multimodal-Models-and-Datasets}}
}
```

---

## 📄 License

MIT. Individual papers, code, and datasets retain their original licenses.
