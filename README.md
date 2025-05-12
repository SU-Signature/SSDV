# SSDV: An Offline Signature Detection and Verification Dataset

Welcome to the official repository for **SSDV (Sabancı Signature Detection and Verification)**, a dataset developed for robust offline signature detection and verification. This repository accompanies our paper:

> **SSDV: An Offline Signature Detection and Verification Dataset**  
> Semih Gülüm, Seçilay Kutal, Erchan Aptoula, Berrin Yanıkoğlu  
> Sabancı University, Istanbul, Turkey  
> *(Presented at IEEE SIU, 2025)*

---

## 🧾 Overview

Signatures are a long-standing form of authentication in various sectors including government, legal, and commercial applications. The **SSDV dataset** simulates real-world scenarios for offline signature detection and verification, offering:

- Genuine and forged signatures.
- Document-level annotations for signature locations.
- Variations in document noise and complexity.

Our goal is to support research on:
- Signature detection from scanned documents.
- Offline signature verification under realistic conditions.

---

## 📁 Dataset Structure

The dataset is structured as follows:
```bash
SSDV
├───  README.md # Dataset description and citation
└─── dataset/
    ├─── images/ # Scanned document images
    │   ├─── test/ # Test partition
    │   └─── train/ # Train partition
    └─── labels/ # XML/JSON annotations for signature bounding boxes
        ├─── test/ # Test partition
        └─── train/ # Train partition
```

> 📌 If you are interested in obtaining the dataset, please refer to the [License & Access](#lock-license--access) section.

---

## 🔍 Tasks Supported

- **Signature Detection**: Localizing signatures on scanned documents.
- **Signature Verification**: Distinguishing genuine vs forged signatures.

---

## 📊 Comparison with Existing Datasets

| Dataset Name                   | Participants | Genuines | Forgeries | Total Samples | Noise Included | Detection Support |
|--------------------------------|--------------|----------|-----------|----------------|----------------|-------------------|
| [UTSig](https://paperswithcode.com/dataset/utsig)                      | 115          | 12       | 6         | 8,280          | ✗              | ✗                 |
| [CEDAR](https://paperswithcode.com/dataset/cedar-signature)                      | 55           | 24       | 24        | 31,680         | ✗              | ✗                 |
| [HanSig](https://github.com/hsinmin/HanSig)                     | 238          | 20       | 20        | 95,200         | ✗              | ✗                 |
| [BHSig260](https://www.kaggle.com/datasets/ishanikathuria/handwritten-signature-datasets)                  | 260          | 24       | 30        | 187,200        | ✗              | ✗                 |
| [MCYT-75](https://bidalab.eps.uam.es/listdatabases?id=MCYT_SignatureOff_75)                   | 75           | 15       | 15        | 16,875         | ✗              | ✗                 |
| [SigDutch](https://tc11.cvc.uab.es/datasets/SigWiComp2013_1/task_1_1)                   | 27           | 10       | 10        | 2,700          | ✗              | ✗                 |
| [SigJapanese](https://tc11.cvc.uab.es/datasets/sigwicomp2013_1/task_2_1)               | 31           | 42       | 36        | 46,872         | ✗              | ✗                 |
| [Brazilian (PUC-PR)]()        | 60           | 40       | 20        | 48,000         | ✗              | ✗                 |
| [GPDS-960 Corpus](https://figshare.com/articles/dataset/GPDS960signature_database/1287360)           | 4,000        | 24       | 30        | 2,800,000      | ✗              | ✗                 |
| **SSDV Dataset**              | 100          | 10       | 5         | 3,000          | ✔              | ✔                 |



---

## Authors

- [Semih Gülüm](https://github.com/semihstp)
- [Seçilay Kutal](https://github.com/seccily)
- [Erchan Aptoula](https://sites.google.com/view/erchan-aptoula/)
- [Berrin Yanıkoğlu](https://scholar.google.com.tr/citations?user=CyWTeecAAAAJ&hl=tr)

## License

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
