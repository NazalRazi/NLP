

# SwiftLink: Smart Emergency Response System

**Cross-Lingual Text Classification for Emergency Dispatch using mBERT**

## 📌 Project Overview

**SwiftLink** is an AI-powered emergency classification system designed to bridge the gap in emergency communication. Using Multilingual BERT (mBERT), the system can categorize emergency distress calls or texts into **Medical**, **Fire**, or **Police** categories, even when the input is in Malayalam, English, or "Manglish" (Malayalam written in Roman script).

## 🚀 Key Features

* **Cross-Lingual Support**: Handles English and Malayalam interchangeably without manual translation.
* **Contextual Understanding**: Distinguishes between similar keywords (e.g., "burning chest" vs "burning house") using transformer-based attention mechanisms.
* **Instant Response Protocol**: Provides immediate first-aid or safety instructions based on the detected category.
* **Interactive Dashboard**: A custom-built UI for dispatchers to monitor incoming alerts in real-time.

## 🛠️ Tech Stack

* **Model**: `bert-base-multilingual-cased` (mBERT)
* **Frameworks**: PyTorch, Hugging Face Transformers
* **Language**: Python
* **Tools**: Google Colab, Scikit-learn, Pandas

## 📊 Performance & Evaluation

The model was evaluated using a **Confusion Matrix** to ensure reliability in high-stakes emergency scenarios.

* **Accuracy**: Achieved significant validation accuracy across multiple languages.
* **Robustness**: Tested against phonetic Malayalam (Manglish) to ensure local usability in regions like Kerala and Karnataka.

## 🏗️ Project Architecture

1. **Data Acquisition**: Curated dataset of emergency phrases in English and Malayalam.
2. **Preprocessing**: Sub-tokenization using mBERT's WordPiece tokenizer.
3. **Training**: Fine-tuning the pre-trained mBERT model on the classification task.
4. **Deployment**: Interactive UI using `ipywidgets` for real-time inference.

## 📥 Installation & Usage

```bash
# Clone the repository
git clone https://github.com/yourusername/SwiftLink.git

# Install dependencies
pip install torch transformers pandas scikit-learn

```

To run the project, open `SwiftLink.ipynb` in Google Colab and run all cells.

## 👥 Contributors

* **Nazal Razi** - 3rd Year B.E. Student
