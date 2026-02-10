# 🌍 WMT 2025 – Low-Resource Indic Machine Translation (JU-NLP)

## 🚀 Project Overview

This repository contains our official submission to the **WMT 2025 Shared Task on Machine Translation**, presented in the paper:

**“JU-NLP: Improving Low-Resource Indic Translation System with Efficient LoRA-Based Adaptation”**

The project focuses on improving **neural machine translation (NMT)** performance for **low-resource Indic languages** such as **Assamese, Manipuri, Mizo, and Bodo** by combining strong preprocessing strategies with **parameter-efficient fine-tuning (LoRA)** on large multilingual models.

Participation in WMT reflects applied research experience in **large-scale MT systems**, **multilingual NLP**, and **shared-task benchmarking**.

---

## 🏆 Task Description

**Conference:** WMT 2025 (Tenth Conference on Machine Translation)
**Track:** Shared Task – Low-Resource Indic Machine Translation
**Domain:** Multilingual Neural Machine Translation (NMT)

The task addresses key challenges in Indic MT:

* Scarcity of parallel corpora
* Script and orthographic diversity
* Rich morphology
* Domain mismatch between training and test data

---

## 🧠 Proposed Approach

We propose a **unified multilingual NMT framework** that leverages both **large pre-trained models** and **efficient adaptation techniques**.

### 🔹 Core Components

1. **Language-Specific Preprocessing**

   * Script normalization
   * Noise removal and filtering
   * Token-level consistency handling

2. **Pre-trained Backbone Models**

   * **NLLB-200** for multilingual translation
   * **mBART** as a strong encoder–decoder baseline

3. **Parameter-Efficient Fine-Tuning**

   * **LoRA (Low-Rank Adaptation)** applied to attention layers
   * Reduces memory footprint while retaining performance

4. **Unified Multilingual Training**

   * Single model trained across multiple Indic languages
   * Improves cross-lingual transfer for extremely low-resource pairs

---

## ⚙️ Training Details

* **Framework:** PyTorch, Hugging Face Transformers
* **Fine-Tuning Strategy:** LoRA-based adaptation
* **Optimization:** AdamW
* **Training Setup:** GPU-accelerated
* **Evaluation:** BLEU and shared-task evaluation metrics

The LoRA-based approach significantly lowers computational cost compared to full fine-tuning while maintaining competitive translation quality.

---

## 🏆 Leaderboard Achievements & Results

Based on the **official WMT 2025 Indic MT shared task leaderboard**, JU-NLP achieved **strong and competitive rankings** across multiple low-resource Indic language pairs among **17 participating teams worldwide**. fileciteturn2file0

### 🔹 Key Achievements (JU-NLP)

* ✅ **Participated in WMT 2025 Low-Resource Indic MT Shared Task**
* 🌍 Competed against **17 international teams** from academia and industry
* 🏅 Achieved **Top-3 ranking** in multiple language directions

### 🔸 Notable Language-wise Results

**Manipuri → English (mni-en)**

* 🥇 **Rank 1** out of all teams
* **BLEU:** 8.10 (Highest on leaderboard)

**English → Manipuri (en-mni)**

* 🥈 **Rank 2** overall
* **BLEU:** 4.12

**Mizo → English (lus-en)**

* 🥇 **Rank 1** overall
* **BLEU:** 12.30

**English → Mizo (en-lus)**

* 🥇 **Rank 1** overall
* **BLEU:** 15.83

**English → Bodo (en-bodo)**

* 🥉 **Rank 3** overall
* **BLEU:** 19.71

These results demonstrate the effectiveness of our **LoRA-based multilingual adaptation strategy**, particularly for **extremely low-resource Indic languages**.

---

## 📁 Project Structure

```
├── data/               # Parallel corpora and processed datasets
├── preprocessing/      # Language-specific preprocessing scripts
├── src/                # Training and evaluation code
├── models/             # Fine-tuned MT checkpoints
├── results/            # Translation outputs and scores
├── requirements.txt    # Dependencies
└── README.md           # Project documentation
```

---

## 📌 Key Contributions

* Applied **LoRA-based adaptation** to Indic MT at scale
* Built a **unified multilingual translation system**
* Addressed real-world challenges in **low-resource NLP**
* Validated approach in an **international shared task (WMT)**

---

## ⚠️ Limitations

* Performance still constrained by data scarcity
* Domain mismatch affects generalization
* Some languages require deeper linguistic normalization

---

## 🔮 Future Work

* Incorporate synthetic data generation (back-translation)
* Explore domain-adaptive fine-tuning
* Extend to additional Indic languages
* Investigate instruction-tuned MT models

---

## 🎯 Why This Project Matters

This project demonstrates hands-on experience with:

* Large-scale **multilingual NLP systems**
* **Low-resource language processing**
* Parameter-efficient adaptation of foundation models
* Research-driven ML development

Relevant roles:

* Machine Learning Engineer
* NLP Engineer
* Research Engineer (NLP)

---

## 📬 Contact
* **Haranath Mondal**
Data Analyst | Aspiring Data Scientist | NLP & ML Research Enthusiast

- **Final leaderboard:** https://drive.google.com/file/d/1Fh7Giu6kbMXnlRsleGgGsxRKiIYmrbgN/view
- **GitHub:** https://github.com/haranathx
- **LinkedIn:** https://www.linkedin.com/in/haranathmondal/  
- **Email:** haranathx@gmail.com
- **Portfolio:** https://haranathx.vercel.app

---

## 📄 Paper Reference

If you use this work, please cite:

> JU-NLP: Improving Low-Resource Indic Translation System with Efficient LoRA-Based Adaptation.
> Proceedings of the Tenth Conference on Machine Translation (WMT 2025).

---

⭐ If you find this repository useful, consider starring it!
