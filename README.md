# BuddhismEval

**Bilingual Benchmark for Buddhist Ethics & Reasoning**  
*Nethmi Muthugala & Deyi Xiong*  
Tianjin University  
[neth.muthugala1@gmail.com](mailto:neth.muthugala1@gmail.com) • [dyxiong@tju.edu.cn](mailto:dyxiong@tju.edu.cn)

---

## 📖 Overview

Despite rapid advances in LLMs, their ability to engage with culturally embedded, low-resource philosophies like Theravāda Buddhism remains under-explored—especially in Sinhala. **BuddhismEval** is the first **bilingual** (English & Sinhala) multiple-choice benchmark designed to evaluate LLMs on:

1. **Factual Understanding**  
2. **Interpretative & Philosophical Analysis**  
3. **Ethical & Moral Reasoning**  
4. **Practical Life Advice**  
5. **Comparative & Analytical Reasoning**  
6. **Cultural & Historical Embedding**

It comprises:

- **English MCQs:** 1,242 questions  
- **Sinhala MCQs:** 1,023 questions  
- **Parallel Dhammapada corpus:** verse-aligned English ↔ Sinhala

---

## 📂 Dataset

All files (CSV) and scripts are available on Hugging Face:

> **Hugging Face:**  
> [https://huggingface.co/datasets/Nethmi14/BuddhismEval](https://huggingface.co/datasets/Nethmi14/BuddhismEval)

### Key properties

- **Tasks:** Multiple-choice QA  
- **Formats:** CSV   
- **Languages:** English, Sinhala  
- **Size:** 1K–10K examples per split  
- **License:** CC-BY-4.0  

---

## ⚙️ Installation

```bash
git clone https://github.com/<your-org>/BuddhismEval.git
cd BuddhismEval
pip install -r requirements.txt
```

## ⚙️ requirements.txt
```
datasets
pandas
openpyxl
requests
```

## ⚙️ License

```
This repository and all dataset assets are released under CC-BY-4.0.
```



