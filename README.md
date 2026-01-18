# Early Detection of Information Disorder Classifiers (TESA + Evolving Social Networks)

**Intended paper:** *Early Detection Effectiveness of Fake News/Information Disorder Classifiers using Target-Based Emotions and Stances on Evolving Social Networks*  

This repository contains code for **reproducibility** (feature engineering + model training).  
**Note:** Original datasets are not included due to size constraints.

---

## Usage

### 1) Feature Engineering
Feature engineering scripts have this in front of them and a number that indicates the order to run them in
- `[Fibvid]`
- `[TS]`

### 2) Model Training
Model training scripts are have this in front of them and a number that indicates the order to run them in
- `[Checked]`

---

## Datasets (Not Included)

The original datasets are not provided in this repository. Please refer to the original dataset publications:

- **FibVID:** *Comprehensive fake news diffusion dataset during the COVID-19 period*  
  DOI: https://doi.org/10.1016/j.tele.2021.101688

- **TruthSeeker:** *The Largest Social Media Ground-Truth Dataset for Real/Fake Content: TruthSeeker*  
  DOI: https://doi.org/10.1109/TCSS.2023.3322303

---

## Feature Engineering Reference (TESA)

Feature engineering follows techniques described in:

- *A Theory-Driven Approach to Fake News/Information Disorder Analysis and Explanation via Target-Based Emotion–Stance Analysis (TESA) and Interpretive Graph Generation (IGG)*  
  DOI: https://doi.org/10.1177/08944393251338403

---

## Pretrained Model Weights

Model weights are available on Hugging Face:

- Target-based emotion analysis:  
  https://huggingface.co/collections/kenchenxingyu/target-based-emotion-analysis

- Target-based stance classification:  
  https://huggingface.co/collections/kenchenxingyu/target-based-stance-classification
