# AI News Classifier using RoBERTa and Hugging Face

This project demonstrates how to build a high-accuracy text classification model to categorize news articles into different topics. The model is built using the Hugging Face `transformers` library, fine-tuning a pre-trained `roberta-base` model on the AG News dataset.

The entire project is contained within a single Google Colab notebook (`.ipynb`), which handles everything from data loading and preprocessing to model training, evaluation, and prediction.

## 🚀 Features

* **High-Performance Model:** Utilizes the powerful `roberta-base` model for deep contextual understanding of text.
* **Large-Scale Dataset:** Trained on the AG News dataset, a standard benchmark for news classification.
* **End-to-End Workflow:** A single notebook provides a complete pipeline from data loading to final evaluation.
* **Detailed Evaluation:** Measures performance using accuracy and visualizes results with a confusion matrix.
* **Easy to Use:** Includes a simple prediction function to test the trained model on new, unseen text.

## 📊 Results

After training for just one epoch on the AG News dataset, the model achieves **high accuracy (typically >90%, around 93%)** on the unseen test set.

The confusion matrix below shows a detailed breakdown of the model's performance across the four categories: **World, Sports, Business, and Sci/Tech**. The strong diagonal line indicates that the model is highly effective at correctly classifying articles into their respective topics.

*(You can add a screenshot of your confusion matrix plot here)*

## 🛠️ Tech Stack

* **Primary Language:** Python
* **Environment:** Google Colab (GPU recommended)
* **Core Libraries:**
    * PyTorch
    * Hugging Face `transformers`
    * Hugging Face `datasets`
    * Hugging Face `evaluate`
* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-learn
