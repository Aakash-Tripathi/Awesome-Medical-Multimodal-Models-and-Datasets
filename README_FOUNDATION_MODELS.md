# Foundation Models for Medical AI

[← Back to main README](./README.md)

---

## 🔬 Pathology Foundation Models

| Model | Modalities | Pretraining Data | Backbone | Year | Paper | Code |
|---|---|---|---|---|---|---|
| **UNI** | H&E WSI | >100M patches / 100K+ slides (MGB) | ViT-L (DINOv2) | 2024 | [Nature Medicine](https://www.nature.com/articles/s41591-024-02857-3) | [GitHub](https://github.com/mahmoodlab/UNI) |
| **UNI 2** | H&E + IHC | >200M patches / 350K slides | ViT-H (DINOv2) | 2025 | (model card) | [GitHub](https://github.com/mahmoodlab/UNI) |
| **CONCH** | H&E + text | 1.17M image-text pairs | ViT-B + text enc. (CoCa-like) | 2024 | [Nature Medicine](https://www.nature.com/articles/s41591-024-02856-4) | [GitHub](https://github.com/mahmoodlab/CONCH) |
| **TITAN** | WSI + reports + 423K captions | 335K WSIs | Slide-level FM | 2024 | [arXiv:2411.19666](https://arxiv.org/abs/2411.19666) | [GitHub](https://github.com/mahmoodlab/TITAN) |
| **PathChat** | WSI + text chat | 456K visual-language instructions | UNI/CONCH + LLM | 2024 | [Nature](https://doi.org/10.1038/s41586-024-07618-3) | (gated, Modella AI) |
| **Prov-GigaPath** | H&E + IHC WSI | 1.3B tiles / 171K WSIs (Providence) | DINOv2 + LongNet | 2024 | [Nature](https://doi.org/10.1038/s41586-024-07441-w) | [GitHub](https://github.com/prov-gigapath/prov-gigapath) |
| **Virchow** | H&E WSI | 1.5M WSIs (MSKCC) | ViT-H (632M, DINOv2) | 2024 | [Nature Medicine](https://doi.org/10.1038/s41591-024-03141-0) | [HF](https://huggingface.co/paige-ai/Virchow) |
| **Virchow2 / Virchow2G** | H&E multi-magnification | 3.1M WSIs / 1.7–1.9B tiles | ViT-H / ViT-G | 2024 | [arXiv:2408.00738](https://arxiv.org/abs/2408.00738) | [HF](https://huggingface.co/paige-ai/Virchow2) |
| **H-Optimus-0** | H&E WSI | 500K+ WSIs | ViT (1.1B) | 2024 | (Bioptimus report) | [HF](https://huggingface.co/bioptimus/H-optimus-0) |
| **Phikon (v1)** | H&E WSI | 40M tiles / 6K WSIs | ViT-B (iBOT) | 2023 | [medRxiv](https://doi.org/10.1101/2023.07.21.23292757) | [HF](https://huggingface.co/owkin/phikon) |
| **Phikon-v2** | H&E WSI (PANCAN-XL) | 450M tiles / ~60K WSIs | ViT-L (DINOv2) | 2024 | [arXiv:2409.09173](https://arxiv.org/abs/2409.09173) | [HF](https://huggingface.co/owkin/phikon-v2) |
| **PLIP** | Pathology + Twitter text | OpenPath 208K pairs | CLIP-based | 2023 | [Nature Medicine](https://doi.org/10.1038/s41591-023-02504-3) | [GitHub](https://github.com/PathologyFoundation/plip) |
| **QuiltNet** | Pathology + YouTube text | Quilt-1M (1M pairs) | CLIP | 2023 | [NeurIPS 2023](https://arxiv.org/abs/2306.11207) | [GitHub](https://github.com/wisdomikezogwo/quilt1m) |
| **CTransPath** | H&E WSI | TCGA + PAIP | Swin (SSL) | 2022 | [MedIA](https://doi.org/10.1016/j.media.2022.102559) | [GitHub](https://github.com/Xiyue-Wang/TransPath) |
| **KEEP** | Pathology + knowledge graph | OpenPath/Quilt + onco-KG | Knowledge-enhanced CLIP | 2024 | [arXiv:2404.09942](https://arxiv.org/abs/2404.09942) | [GitHub](https://github.com/MAGIC-AI4Med/KEP) |
| **Quilt-LLaVA** | Pathology vision + chat | YouTube-grounded data | LLaVA-style | 2024 | [arXiv:2312.04746](https://arxiv.org/abs/2312.04746) | (Quilt-1M repo) |
| **HIPT** | Hierarchical WSI | TCGA | Hierarchical ViT | 2022 | [CVPR 2022](https://arxiv.org/abs/2206.02647) | [GitHub](https://github.com/mahmoodlab/HIPT) |
| **DinoSSLPath / Hibou / Panakeia** | H&E WSI | Various | DINOv2-based | 2024 | (various) | (various) |

> **Benchmark note (Neidlinger et al., *Nat. Biomed. Eng.* 2025, [doi:10.1038/s41551-025-01516-3](https://doi.org/10.1038/s41551-025-01516-3))** — averaged across 31 pathology tasks on 13 cohorts: **CONCH and Virchow2 are co-leaders at AUROC 0.71**; Prov-GigaPath and DinoSSLPath at 0.69; H-Optimus-0, UNI, Panakeia at 0.68; Virchow, Hibou-L, CTransPath at 0.67.

---

## 🩻 Radiology Foundation Models

| Model | Modalities | Backbone | Year | Paper | Code |
|---|---|---|---|---|---|
| **RadFM** | 2D/3D + text (interleaved) | LLM + visual enc. | 2025 | [Nat. Comms](https://www.nature.com/articles/s41467-025-62385-7) | [GitHub](https://github.com/chaoyi-wu/RadFM) |
| **CheXzero** | CXR + reports (zero-shot) | CLIP (impressions) | 2022 | [Nat. Biomed. Eng.](https://www.nature.com/articles/s41551-022-00936-9) | [GitHub](https://github.com/rajpurkarlab/CheXzero) |
| **BiomedCLIP** | Biomed image+text | PMC-15M, ViT-B + PubMedBERT | 2023 | [arXiv:2303.00915](https://arxiv.org/abs/2303.00915) | [HF](https://huggingface.co/microsoft/BiomedCLIP-PubMedBERT_256-vit_base_patch16_224) |
| **PubMedCLIP** | Biomed image+text | CLIP+ROCO | 2021 | [arXiv:2112.13906](https://arxiv.org/abs/2112.13906) | [GitHub](https://github.com/sarahESL/PubMedCLIP) |
| **MedCLIP** | Image+text (unpaired) | Semantic-matching CLIP | 2022 | [EMNLP 2022](https://arxiv.org/abs/2210.10163) | [GitHub](https://github.com/RyanWangZf/MedCLIP) |
| **ConVIRT** | CXR + reports | ResNet + Bio-ClinicalBERT | 2020 (MLHC 2022) | [arXiv:2010.00747](https://arxiv.org/abs/2010.00747) | [GitHub](https://github.com/yuhaozhang/convirt) |
| **GLoRIA** | CXR + reports (local+global) | CNN + word/patch attn | 2021 | [ICCV 2021](https://openaccess.thecvf.com/content/ICCV2021/html/Huang_GLoRIA_A_Multimodal_Global-Local_Representation_Learning_Framework_for_Label-Efficient_Medical_ICCV_2021_paper.html) | [GitHub](https://github.com/marshuang80/gloria) |
| **BioViL / BioViL-T** | CXR + temporal text | Multimodal SSL | 2022-23 | (MSR) | [GitHub](https://github.com/microsoft/hi-ml) |
| **MAIRA-1** | CXR + RG | RAD-DINO + Vicuna-7B | 2023 | [arXiv:2311.13668](https://arxiv.org/abs/2311.13668) | [HF (gated)](https://huggingface.co/microsoft/maira-1) |
| **MAIRA-2** | CXR + grounded RG | MM-LLM + bbox | 2024 | [arXiv:2406.04449](https://arxiv.org/abs/2406.04449) | [HF](https://huggingface.co/microsoft/maira-2) |
| **RAD-DINO** | CXR vision-only | ViT (DINOv2) | 2024 | [arXiv:2401.10815](https://arxiv.org/abs/2401.10815) | [HF](https://huggingface.co/microsoft/rad-dino) |
| **CheXagent** | CXR instruction VLM | CXR enc. + clinical LLM | 2024 | [arXiv:2401.12208](https://arxiv.org/abs/2401.12208) | [GitHub](https://github.com/Stanford-AIMI/CheXagent) |
| **ELIXR** | CXR + LLM adapter | image enc. → PaLM 2 | 2023 | [arXiv:2308.01317](https://arxiv.org/abs/2308.01317) | [HF](https://huggingface.co/google/cxr-foundation) |
| **LLaVA-Rad** | CXR RG (small LMM) | BiomedCLIP-CXR + 7B LLM | 2024 (pub. 2025) | [arXiv:2403.08002](https://arxiv.org/abs/2403.08002) | [GitHub](https://github.com/microsoft/LLaVA-Rad) |
| **CT-CLIP / CT-RATE** | 3D CT + reports | 3D ViT + CLIP | 2024 | [arXiv:2403.17834](https://arxiv.org/abs/2403.17834) | [GitHub](https://github.com/ibrahimethemhamamci/CT-CLIP) |
| **Flamingo-CXR** | CXR few-shot | Flamingo-based | 2023 | [arXiv:2311.18260](https://arxiv.org/abs/2311.18260) | (closed) |

---

## 🧠 Generalist Biomedical Multimodal LLMs

| Model | Modalities | Params | Year | Paper | Code |
|---|---|---|---|---|---|
| **LLaVA-Med** | Image + clinical dialog (Vicuna/LLaMA) | 7B | 2023 | [NeurIPS 2023 / arXiv:2306.00890](https://arxiv.org/abs/2306.00890) | [GitHub](https://github.com/microsoft/LLaVA-Med) |
| **LLaVA-Med v1.5** | Image+text (Mistral) | 7B | 2024 | (release) | [HF](https://huggingface.co/microsoft/llava-med-v1.5-mistral-7b) |
| **Med-Flamingo** | Few-shot interleaved | 9B | 2023 | [ML4H 2023 / arXiv:2307.15189](https://arxiv.org/abs/2307.15189) | [GitHub](https://github.com/snap-stanford/med-flamingo) |
| **BiomedGPT** | Vision+language+MM | Base/Large/XL | 2023 (Nat. Med. 2024) | [arXiv:2305.17100](https://arxiv.org/abs/2305.17100) | [GitHub](https://github.com/taokz/BiomedGPT) |
| **Med-PaLM M** | Text+image+signals+genomics | PaLM-E based | 2023 | [arXiv:2307.14334](https://arxiv.org/abs/2307.14334) | (closed) |
| **Med-Gemini (1.0/1.5)** | Multimodal + long-context | Gemini family | 2024 | [arXiv:2404.18416](https://arxiv.org/abs/2404.18416), [arXiv:2405.03162](https://arxiv.org/abs/2405.03162) | (closed) |
| **MedGemma** | Open MM medical | 4B/27B | 2024 | (Google release) | [HF](https://huggingface.co/google/medgemma-4b-it) |
| **MedDr** | Generalist diagnosis VLM | – | 2024 | [arXiv:2404.15127](https://arxiv.org/abs/2404.15127) | [GitHub](https://github.com/sunanhe/MedDr) |
| **PMC-LLaMA** | Biomed LLM | 7B/13B | 2023 | [arXiv:2304.14454](https://arxiv.org/abs/2304.14454) | [GitHub](https://github.com/chaoyi-wu/PMC-LLaMA) |
| **Meditron** | Medical LLM | 7B/70B | 2023 | [arXiv:2311.16079](https://arxiv.org/abs/2311.16079) | [GitHub](https://github.com/epfLLM/meditron) |
| **Clinical Camel** | Medical chat | 70B | 2023 | [arXiv:2305.12031](https://arxiv.org/abs/2305.12031) | [GitHub](https://github.com/bowang-lab/clinical-camel) |
| **Llama3-Med** | Hi-res biomed VLM | 8B | 2024 | [arXiv:2406.09454](https://arxiv.org/abs/2406.09454) | — |
| **HuatuoGPT-Vision** | Bilingual medical VLM | 7B/34B | 2024 | [arXiv:2406.19280](https://arxiv.org/abs/2406.19280) | [GitHub](https://github.com/FreedomIntelligence/HuatuoGPT-Vision) |

---

## 🏥 EHR Foundation Models

| Model | Input | Paradigm | Year | Paper | Code |
|---|---|---|---|---|---|
| **CLMBR / CLMBR-T-base** (141M params, 2.57M Stanford patients) | Structured OMOP | Autoregressive | 2020 / 2024 | [Steinberg 2021](https://doi.org/10.1016/j.jbi.2021.103670) · [Wornow 2024](https://pmc.ncbi.nlm.nih.gov/articles/PMC11211479/) | [GitHub](https://github.com/som-shahlab/ehrshot-benchmark) |
| **GatorTron** (90B clinical words) | Clinical text | BERT-style | 2022 | [npj Digital Medicine](https://www.nature.com/articles/s41746-022-00742-2) | [HF](https://huggingface.co/UFNLP/gatortron-base) |
| **ClinicalBERT** | Clinical notes | BERT | 2019 | [arXiv:1904.05342](https://arxiv.org/abs/1904.05342) | [GitHub](https://github.com/EmilyAlsentzer/clinicalBERT) |
| **Med-BERT** | Structured ICD | BERT | 2021 | [npj DM](https://www.nature.com/articles/s41746-021-00455-y) | [GitHub](https://github.com/ZhiGroup/Med-BERT) |
| **BEHRT** | EHR codes | BERT-style | 2020 | [Sci. Rep.](https://www.nature.com/articles/s41598-020-62922-y) | [GitHub](https://github.com/deepmedicine/BEHRT) |
| **Foresight** | EHR timelines | GPT-style | 2024 | [Lancet Digital Health](https://doi.org/10.1016/S2589-7500(24)00025-6) | [GitHub](https://github.com/CogStack/foresight) |
| **MOTOR** (+4.6 % C-stat over SOTA, 19 tasks, 3 databases) | EHR (time-to-event) | TTE-aware FM | 2024 | [arXiv:2301.03150](https://arxiv.org/abs/2301.03150) | [GitHub](https://github.com/som-shahlab/motor) |
| **ETHOS** | EHR event streams | GPT next-event | 2024 | [NEJM AI](https://ai.nejm.org/doi/full/10.1056/AIoa2300213) | [GitHub](https://github.com/ipolharvard/ethos) |
| **Delphi** | Disease history | Generative transformer | 2025 | [Nature 2025](https://doi.org/10.1038/s41586-025-08923-1) | – |
| **EHRMamba** | EHR (Mamba) | SSM | 2025 | [arXiv:2405.14567](https://arxiv.org/abs/2405.14567) | — |
| **ClinicalMamba** | Notes (Mamba) | SSM | 2024 | [arXiv:2403.05795](https://arxiv.org/abs/2403.05795) | [GitHub](https://github.com/whaleloops/ClinicalMamba) |

---

## 🧬 Omics / Single-Cell Foundation Models

| Model | Modality | Pretraining | Year | Paper | Code |
|---|---|---|---|---|---|
| **scGPT** | scRNA-seq (+ multi-omics) | **33M cells across 51 organs/tissues & 441 studies (CELLxGENE)** | 2024 | [Nature Methods](https://www.nature.com/articles/s41592-024-02201-0) | [GitHub](https://github.com/bowang-lab/scGPT) |
| **scBERT** | scRNA-seq | 1M cells, Performer | 2022 | [Nat. Mach. Intell.](https://www.nature.com/articles/s42256-022-00534-z) | [GitHub](https://github.com/TencentAILabHealthcare/scBERT) |
| **Geneformer** | scRNA-seq | 30M cells, ranked tokens | 2023 | [Nature](https://www.nature.com/articles/s41586-023-06139-9) | [HF](https://huggingface.co/ctheodoris/Geneformer) |
| **scFoundation** | scRNA-seq | 50M cells, 100M params | 2024 | [Nature Methods](https://www.nature.com/articles/s41592-024-02305-7) | [GitHub](https://github.com/biomap-research/scFoundation) |
| **UCE (Universal Cell Embedding)** | scRNA cross-species | 36M cells | 2024 | [bioRxiv](https://www.biorxiv.org/content/10.1101/2023.11.28.568918v1) | [GitHub](https://github.com/snap-stanford/UCE) |
| **Nucleotide Transformer** | DNA | Multi-species genomes (50M–2.5B params) | 2025 | [Nature Methods](https://www.nature.com/articles/s41592-024-02523-z) | [GitHub](https://github.com/instadeepai/nucleotide-transformer) |
| **DNABERT-2** | DNA | Multi-species + BPE + ALiBi | 2024 (ICLR) | [arXiv:2306.15006](https://arxiv.org/abs/2306.15006) | [GitHub](https://github.com/MAGICS-LAB/DNABERT_2) |
| **HyenaDNA** | DNA (1M-token context) | Human genome, Hyena | 2023 (NeurIPS) | [arXiv:2306.15794](https://arxiv.org/abs/2306.15794) | [GitHub](https://github.com/HazyResearch/hyena-dna) |
| **Evo** | DNA/RNA/protein | 7B StripedHyena, prokaryote+phage, 131kb context | 2024 | [Science](https://doi.org/10.1126/science.ado9336) | [GitHub](https://github.com/evo-design/evo) |
| **ESM-2 / ESMFold** | Protein | – | 2022 | [Science](https://www.science.org/doi/10.1126/science.ade2574) | [GitHub](https://github.com/facebookresearch/esm) |
| **AlphaFold-3** | Protein + ligands | – | 2024 | [Nature](https://doi.org/10.1038/s41586-024-07487-w) | [GitHub](https://github.com/google-deepmind/alphafold3) |
| **AlphaGenome** | Genome regulatory variants | – | 2025 | (DeepMind) | — |

---

[← Back to main README](./README.md) · [→ Task-Specific Models](./README_TASK_SPECIFIC_MODELS.md)
