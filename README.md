# Machine Translation: English to Hindi

## 📌 Project Overview
This project focuses on **Machine Translation (MT)** from English to Hindi using **pre-trained transformer-based models**. We leverage models from Hugging Face, including:
- **Helsinki-NLP/opus-mt-en-hi** (OPUS-MT model)
- **facebook/m2m100_418M** (Multilingual Model from Facebook)
- **facebook/mbart-large-50-many-to-many-mmt** (Multilingual BART for many-to-many translation)

We also evaluate translations using **BLEU Score** and process datasets efficiently with **Hugging Face's datasets library**.

## 🚀 Models Used
| Model | Description |
|--------|------------|
| `Helsinki-NLP/opus-mt-en-hi` | OPUS-MT model trained for English-Hindi translation. |
| `facebook/m2m100_418M` | Facebook’s multilingual model trained on 100 languages. |
| `facebook/mbart-large-50-many-to-many-mmt` | A large multilingual sequence-to-sequence model for translation. |

## 🛠 Libraries Used
- **Transformers** (for model loading and translation)
- **Datasets** (for handling translation datasets)
- **Pipeline** (for an easy-to-use translation workflow)
- **BLEU Score** (for evaluating translation quality)

## 📂 Dataset
We use the **Muennighoff/flores200** dataset, an English-Hindi parallel dataset, for testing the performance of these models. The dataset is loaded using **Hugging Face’s `datasets` library**.

## 📈 Performance Evaluation
The models are compared based on **BLEU scores** and manual evaluation. We analyze:
- **Translation accuracy**
- **Grammar and fluency**
- **Contextual correctness**
