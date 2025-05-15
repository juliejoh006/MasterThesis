# Master Thesis
## Unveiling Gender Bias in Norwegian Large Language Models through Decision Tree Extraction

This repository contains the code and analysis for my master's thesis at Oslo Metropolitan University (OsloMet), focused on understanding and explaining **gender bias** in Norwegian Large Language Models (LLMs) using **Decision Tree (DT) extraction**.

### Project Objective

To explore whether and how gender bias manifests in Norwegian and multilingual LLMs by:

- Generating occupation-related predictions using LLMs
- Comparing LLM predictions to real-world labor market statistics from **Statistics Norway (SSB)**
- Using **Decision Trees** as surrogate models for interpretable analysis
- Applying fairness metrics such as:
  - **Disparate Impact Ratio (DIR)**
  - **Equal Opportunity Difference (EOD)**
- Visualizing gender representation, salary gaps, and amplification patterns

### Key Concepts

- **Explainable AI (XAI)**: Interpreting LLM behavior using Decision Trees and SHAP
- **Bias Metrics**: Quantifying disparity in model output vs. real data
- **Fidelity Analysis**: Measuring how well DTs replicate LLM decisions
- **Embedding-Level Bias**: Using LPBS and WEAT to assess biases in word embeddings

### Project Structure

- `master_LLM_DT.ipynb`: Main notebook with the complete pipeline
