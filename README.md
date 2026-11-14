# FauxHate Social Media Corpus (FXMC)

<p align="center">
  <strong>A Multi-Task Annotated Dataset for Fake Content and Hate Speech Detection</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Dataset-FauxHate-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Domain-Social%20Media-purple?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Format-CSV-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" />
</p>

---

## Overview

The **FauxHate Social Media Corpus (FXMC)** is a publicly available annotated dataset designed for multi-task Natural Language Processing (NLP) research on harmful and misleading social media content.

The dataset provides structured annotations to support the identification and analysis of fake content, hate speech, targeted groups, and the severity of harmful expressions.

It supports four major classification tasks:

- **Fake Content Detection** – Identifying fake and non-fake content.
- **Hate Speech Detection** – Distinguishing hateful from non-hateful content.
- **Target Identification** – Identifying the target category of hate speech.
- **Severity Classification** – Categorizing the severity of harmful content.

The dataset is intended to facilitate research in content moderation, harmful content identification, and multi-task learning approaches for social media analysis.

---

## Table of Contents

- [Dataset Statistics](#dataset-statistics)
- [Annotation Framework](#annotation-framework)
  - [1. Fake Content Detection](#1-fake-content-detection)
  - [2. Hate Speech Detection](#2-hate-speech-detection)
  - [3. Target Identification](#3-target-identification)
  - [4. Severity Classification](#4-severity-classification)
- [Dataset Format](#dataset-format)
- [Repository Structure](#repository-structure)
- [Potential Applications](#potential-applications)
- [Citation](#citation)
- [License](#license)

---

## Dataset Statistics

| Attribute | Description |
|:---|:---|
| **Dataset Name** | FauxHate Social Media Corpus |
| **Abbreviation** | FXMC |
| **Total Samples** | 21,011 |
| **Data Format** | CSV |
| **Domain** | Social Media Comments |
| **Language** | English |
| **Annotation Tasks** | 4 |
| **License** | MIT License |

---

## Annotation Framework

The FauxHate Social Media Corpus consists of four annotation tasks, each designed to capture a different dimension of misleading or harmful social media content.

### 1. Fake Content Detection

A binary classification task designed to identify whether a given social media comment contains fake or non-fake content.

| Label | Category |
|:---:|:---|
| `0` | Non-Fake |
| `1` | Fake |

### 2. Hate Speech Detection

A binary classification task designed to identify whether a given comment contains hate speech.

| Label | Category |
|:---:|:---|
| `0` | Non-Hate |
| `1` | Hate |

### 3. Target Identification

A multi-class classification task designed to identify the target category associated with hate speech.

| Label | Category |
|:---:|:---|
| `I` | Individual |
| `O` | Other |
| `R` | Religion |

### 4. Severity Classification

A multi-class classification task designed to categorize the severity level of harmful content.

| Label | Category |
|:---:|:---|
| `L` | Low |
| `M` | Medium |
| `H` | High |

---

## Dataset Format

The dataset is provided in CSV format and contains annotated social media comments.

The annotations support four distinct classification objectives:

| Task | Classification Type | Number of Classes |
|:---|:---|:---:|
| Fake Content Detection | Binary | 2 |
| Hate Speech Detection | Binary | 2 |
| Target Identification | Multi-class | 3 |
| Severity Classification | Multi-class | 3 |

For detailed information regarding the dataset, annotation methodology, and label definitions, refer to the corresponding documentation files available in this repository.

---

## Repository Structure

The repository is organized into the following components:

```text
FXMC/
│
├── dataset/
│
├── documentation/
│
├── sample/
│
├── README.md
│
└── LICENSE
```

---

## Potential Applications

The FauxHate Social Media Corpus can support research and experimentation in several NLP and machine learning domains.

**Research applications include:**

- **Fake News Detection:** Identifying misleading and fabricated social media content.
- **Hate Speech Detection:** Detecting hateful expressions in online discussions.
- **Multi-Task Learning:** Developing models capable of performing multiple classification tasks simultaneously.
- **Transformer-Based NLP:** Evaluating transformer architectures for harmful content classification.
- **Social Media Analytics:** Analyzing patterns in misleading and harmful online content.
- **Content Moderation:** Supporting automated systems for identifying potentially harmful content.

---

## Citation

If you use the FauxHate Social Media Corpus in your research, please cite the associated research publication.

---

## License

This dataset is distributed under the **MIT License**.

See the [LICENSE](LICENSE) file for further details.

---

<p align="center">
  <strong>FauxHate Social Media Corpus (FXMC)</strong>
  <br>
  Advancing Research in Fake Content Detection, Hate Speech Detection, and Multi-Task NLP.
</p>
