# MultiNMT

Multilingual Transformer-based Neural Machine Translation for English, Vietnamese, and Japanese.

---

## Overview

MultiNMT is a research-oriented project exploring multilingual Neural Machine Translation (NMT) using Transformer architectures.

The project focuses on building and evaluating translation systems across:

* English ↔ Vietnamese
* English ↔ Japanese
* Vietnamese ↔ Japanese

with the long-term goal of investigating multilingual transfer learning, low-resource translation, and efficient deployment strategies.

---

## Motivation

Machine Translation remains one of the most impactful applications of Natural Language Processing.

While large multilingual models have achieved remarkable performance, many language pairs still suffer from:

* Limited parallel corpora
* Domain mismatch
* Translation inconsistency
* High deployment costs

This project aims to study how modern Transformer-based architectures can be adapted and evaluated for multilingual translation involving English, Vietnamese, and Japanese.

---

## Research Objectives

### Primary Objectives

* Build multilingual Transformer-based NMT models
* Evaluate translation quality across language pairs
* Compare multilingual and bilingual training strategies
* Analyze translation errors and model limitations

### Secondary Objectives

* Investigate transfer learning between language pairs
* Explore low-resource translation settings
* Study model compression and deployment strategies
* Build production-ready inference pipelines

---

## Language Pairs

| Source     | Target     |
| ---------- | ---------- |
| English    | Vietnamese |
| Vietnamese | English    |
| English    | Japanese   |
| Japanese   | English    |
| Vietnamese | Japanese   |
| Japanese   | Vietnamese |

---

## Planned Architecture

```text
Parallel Corpus
        │
        ▼
Data Cleaning & Normalization
        │
        ▼
Tokenizer Training
        │
        ▼
Transformer Model
        │
        ▼
Training Pipeline
        │
        ▼
BLEU / COMET Evaluation
        │
        ▼
Inference API
```

---

## Tech Stack

### Deep Learning

* PyTorch
* Hugging Face Transformers
* Accelerate

### NLP

* SentencePiece
* SacreBLEU
* COMET

### Infrastructure

* Docker
* FastAPI
* GitHub Actions

---

## Repository Structure

```text
multinmt
│
├── data/
├── experiments/
├── notebooks/
├── src/
│   ├── dataset/
│   ├── models/
│   ├── training/
│   ├── evaluation/
│   └── inference/
│
├── requirements.txt
└── README.md
```

---

## Development Roadmap

### Phase 1 — Data Pipeline

* [ ] Dataset collection
* [ ] Data cleaning
* [ ] Language normalization
* [ ] Train/Validation/Test split

### Phase 2 — Baseline Models

* [ ] Transformer baseline
* [ ] Training pipeline
* [ ] BLEU evaluation

### Phase 3 — Multilingual NMT

* [ ] Shared vocabulary
* [ ] Multilingual training
* [ ] Transfer learning experiments

### Phase 4 — Evaluation

* [ ] BLEU
* [ ] COMET
* [ ] Error analysis
* [ ] Ablation studies

### Phase 5 — Deployment

* [ ] FastAPI service
* [ ] Docker deployment
* [ ] Hugging Face integration

---

## Expected Deliverables

* Multilingual NMT model
* Evaluation benchmark
* Translation API
* Technical report
* Public GitHub repository

---

## Current Status

🚧 Early Development

Currently preparing datasets, training pipelines, and evaluation frameworks.

---

## Future Directions

* Low-resource multilingual translation
* Domain-adaptive machine translation
* Knowledge-enhanced translation
* Efficient inference and quantization
* On-device NMT deployment

---

## Author

Pham Thi Kieu Diem

Software Engineering Student — University of Information Technology (VNU-HCM)

Research Interests:

* Natural Language Processing
* Neural Machine Translation
* Retrieval-Augmented Generation
* Neuro-Symbolic Reasoning
* Trustworthy AI Systems
