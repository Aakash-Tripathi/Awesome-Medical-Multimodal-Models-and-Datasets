# Imaging Datasets

[← Back to main README](./README.md)

---

## 🩻 Radiology — Chest X-ray

| Dataset | Size | Labels | Year | Paper | Link |
|---|---|---|---|---|---|
| **MIMIC-CXR** | 377,110 CXRs / 227,827 studies + reports (BIDMC) | 14 CheXpert labels | 2019 | [Sci. Data](https://www.nature.com/articles/s41597-019-0322-0) | [PhysioNet](https://physionet.org/content/mimic-cxr/) |
| **CheXpert** | 224,316 CXRs (Stanford, Oct 2002 – Jul 2017) | 14 labels (with uncertain) | 2019 | [AAAI 2019](https://arxiv.org/abs/1901.07031) | [Stanford](https://stanfordmlgroup.github.io/competitions/chexpert/) |
| **NIH ChestX-ray14** | 112,120 frontal CXRs, 30,805 patients | 14 NLP-mined labels | 2017 | [CVPR 2017](https://arxiv.org/abs/1705.02315) | [NIH Box](https://nihcc.app.box.com/v/ChestXray-NIHCC) |
| **PadChest** | 160,868 CXRs, 69,882 patients (Spain) | 174 findings + 19 diff. dx | 2020 | [arXiv:1901.07441](https://arxiv.org/abs/1901.07441) | [BIMCV](http://bimcv.cipf.es/bimcv-projects/padchest/) |
| **VinDr-CXR** | 18,000 CXRs, expert bbox | 22 findings | 2021 | [Sci. Data](https://www.nature.com/articles/s41597-022-01498-w) | [PhysioNet](https://physionet.org/content/vindr-cxr/) |
| **Open-i / IU X-ray** | 7,470 CXRs + 3,955 reports | MeSH | 2016 | [JAMIA](https://doi.org/10.1093/jamia/ocv080) | [Open-i](https://openi.nlm.nih.gov/) |
| **CheXmask** | 657,566 anatomical masks (5 CXR DBs) | seg | 2024 | [Sci. Data](https://www.nature.com/articles/s41597-024-03358-1) | — |
| **MS-CXR** | Phrase-grounded captions | bbox + text | 2022 | (BioViL) | [PhysioNet](https://physionet.org/content/ms-cxr/) |

---

## 🧠 3D / Volumetric

| Dataset | Modality | Task | Year | Link |
|---|---|---|---|---|
| **Medical Segmentation Decathlon (MSD)** | CT / MR, 10 tasks | seg | 2022 | [Nat. Comms](https://www.nature.com/articles/s41467-022-30695-9) |
| **BraTS 2018–2024** | Brain MRI multi-parametric | tumor seg + survival | 2018–24 | [arXiv:1811.02629](https://arxiv.org/abs/1811.02629) · [grand-challenge](https://braintumorsegmentation.org/) |
| **LIDC-IDRI** | 1,018 thoracic CTs, 7,371 nodules (4-expert reads) | nodules | 2011 | [Med. Phys.](https://doi.org/10.1118/1.3528204) |
| **AbdomenCT-1K** | 1K abdominal CTs | multi-organ seg | 2021 | [arXiv:2010.14808](https://arxiv.org/abs/2010.14808) |
| **TotalSegmentator dataset** | 1,228 CTs, 117 structures | seg | 2023 | [Radiology AI](https://pubs.rsna.org/doi/10.1148/ryai.230024) |
| **KiTS19 / 21** | Kidney CT | tumor seg | 2019–21 | [grand-challenge](https://kits-challenge.org/) |
| **CT-RATE** | 25K chest CT + reports | RG / MM | 2024 | [arXiv:2403.17834](https://arxiv.org/abs/2403.17834) |
| **AMOS22** | 500 CT + 100 MRI, 15 organs | seg | 2022 | [NeurIPS DB](https://amos22.grand-challenge.org/) |
| **FLARE21 / 22 / 23** | Abdominal CT | seg | 2021–23 | [grand-challenge](https://flare22.grand-challenge.org/) |

---

## 🔬 Histopathology (WSI)

| Dataset | Size | Type | Year | Link |
|---|---|---|---|---|
| **TCGA** | ~30K WSIs / 33 cancers | H&E + multi-omics + clinical | 2008+ | [GDC](https://portal.gdc.cancer.gov/) |
| **CPTAC** | WSIs + mass-spec proteomics | Proteogenomics | 2014+ | [CPTAC](https://proteomics.cancer.gov/programs/cptac) |
| **CAMELYON16** | 400 WSIs (lymph node mets) | metastasis detection | 2017 | [JAMA](https://doi.org/10.1001/jama.2017.14585) · [Challenge](https://camelyon16.grand-challenge.org/) |
| **CAMELYON17** | 1,000 WSIs (patient-level pN-stage) | staging | 2018 | [Challenge](https://camelyon17.grand-challenge.org/) |
| **PANDA** | 10,616 prostate biopsy WSIs | Gleason grading | 2022 | [Nature Medicine](https://doi.org/10.1038/s41591-021-01620-2) · [Challenge](https://panda.grand-challenge.org/) |
| **PAIP 2019 / 2020 / 2021** | Liver / Colon WSIs | cancer | 2019–21 | [PAIP](http://wisepaip.org/paip) |
| **TUPAC16** | Breast mitosis | mitosis count | 2016 | [TUPAC](https://tupac.grand-challenge.org/) |
| **BACH** | Breast histology | 4-class | 2018 | [BACH](https://iciar2018-challenge.grand-challenge.org/) |
| **MIDOG 2021 / 22** | Multi-domain mitosis | detection | 2021–22 | [MIDOG](https://midog.deepmicroscopy.org/) |
| **NCT-CRC-HE-100K** | 100K colorectal patches | tissue class | 2018 | [Zenodo](https://zenodo.org/records/1214456) |
| **PatchCamelyon** | 327K patches | binary mets | 2018 | [GitHub](https://github.com/basveeling/pcam) |

---

## 👁️ Ophthalmology

| Dataset | Size | Task | Year | Link |
|---|---|---|---|---|
| **EyePACS / Kaggle DR** | 88,702 fundus | DR grading | 2015 | [Kaggle](https://www.kaggle.com/c/diabetic-retinopathy-detection) |
| **Messidor / Messidor-2** | 1,200 / 1,748 fundus | DR (0–4) | 2014 | [ADCIS](https://www.adcis.net/en/third-party/messidor/) |
| **APTOS 2019** | 3,662 fundus | DR | 2019 | [Kaggle](https://www.kaggle.com/c/aptos2019-blindness-detection) |
| **ODIR-5K** | 5K fundus, 8 classes | multi-disease | 2019 | [iChallenges](https://odir2019.grand-challenge.org/) |
| **RFMiD** | 3,200 fundus, 45 diseases | classif | 2021 | (IEEE Access) |
| **REFUGE** | Glaucoma | seg + classif | 2018 | [REFUGE](https://refuge.grand-challenge.org/) |
| **OCT (Kermany)** | 84K OCT scans | retinal disease | 2018 | [Cell](https://www.cell.com/cell/fulltext/S0092-8674(18)30154-5) |

---

## 🧴 Dermatology

| Dataset | Size | Task | Year | Link |
|---|---|---|---|---|
| **HAM10000** | **10,015 dermoscopy from 2 sites, collected over 20 years** | 7-class | 2018 | [Sci. Data](https://doi.org/10.1038/sdata.2018.161) |
| **ISIC 2016–2024** | 33K+ dermoscopy | classif + seg | 2016–24 | [ISIC Archive](https://challenge.isic-archive.com/data/) |
| **PAD-UFES-20** | 2,298 smartphone lesion images | 6-class | 2020 | [Data in Brief](https://doi.org/10.1016/j.dib.2020.106221) |
| **DDI** | Diverse skin images | fairness | 2022 | [Sci. Adv.](https://www.science.org/doi/10.1126/sciadv.abq6147) |

---

## 🧬 Other Modalities

| Dataset | Modality | Year | Link |
|---|---|---|---|
| **PTB-XL** | 21K 12-lead ECG | 2020 | [Sci. Data](https://www.nature.com/articles/s41597-020-0495-6) |
| **MIMIC-ECG** | 800K ECGs | 2023 | [PhysioNet](https://physionet.org/content/mimic-iv-ecg/) |
| **BUSI** | Breast ultrasound | 2020 | (Data in Brief) |

---

[← Back to main README](./README.md) · [→ Omics Datasets](./README_DATASETS_OMICS.md)
