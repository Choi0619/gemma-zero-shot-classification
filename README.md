# gemma-zero-shot-classification
A project implementing zero-shot classification using the Gemma-2B model for categorizing news articles.
# 🌟 Gemma Zero-Shot News Classification

This project explores the capabilities of the **Gemma-2B model** for zero-shot classification, focusing on categorizing news articles into one of four categories: **World**, **Sports**, **Business**, or **Technology**. The implementation utilizes Hugging Face's powerful tools and tests various approaches to enhance classification performance.

## ✨ Project Overview
- **Objective**: Perform zero-shot classification on the `fancyzhx/ag_news` dataset using the Gemma-2B model.
- **Key Approaches**:
  - **Zero-shot Classification**: Directly predict categories without prior training on labeled data.
  - **Few-shot Learning**: Improves performance by providing example prompts to the model.
  - **Cosine Similarity**: Introduced a similarity-based approach that demonstrated the best performance among these methods.
- **Preprocessing**: Enhanced predictions through text normalization, such as lowercase conversion and whitespace trimming.

## 🔧 How to Use
1. Install required libraries: `datasets`, `transformers`, `tqdm`, `numpy`, `scikit-learn`.
2. Load the `fancyzhx/ag_news` dataset using Hugging Face's `load_dataset`.
3. Explore the classification methods by running the notebook: `Gemma_News_Classification.ipynb`.

🌟 Happy experimenting with Gemma-2B! 🌟
