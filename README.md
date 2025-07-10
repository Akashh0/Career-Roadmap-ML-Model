# 🔍 Career Path Recommendation using BERT

This repository contains the **BERT-based Machine Learning model** used in the Career Guidance system. It interprets user input (interests, education, goals) and recommends suitable career paths using advanced NLP.

---

## 🚀 Overview

The model leverages **BERT (Bidirectional Encoder Representations from Transformers)** to understand natural language and provide context-aware career suggestions.

- 🔤 Input: Free-text responses from users (e.g., "I like designing and solving complex problems")
- 🧠 Model: Fine-tuned BERT for text classification or QA
- 🎯 Output: Top 3 recommended career domains (e.g., "Systems Engineer", "Product Designer", "AI Researcher")

---

## 🛠️ Tech Stack

- **Model**: `bert-base-uncased` (Hugging Face Transformers)
- **Frameworks**: TensorFlow
- **Tokenizer**: WordPiece tokenizer
- **Backend Integration**: Django REST Framework (Future Plan)

---

## 🧪 Sample Prediction

```python
Input: "I'm passionate about biology and want to help people."

Output: ["Medical Researcher", "Clinical Biologist", "Pharmaceutical Analyst"]
```

### ⚙️ Setup & Inference

# 1. Clone the repo
git clone https://github.com/yourusername/career-bert-model.git
cd career-bert-model

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run prediction
python predict.py --input "I enjoy analyzing data and finding patterns"

###🎯 Use Case
##This model is integrated into a larger Career Guidance web application, where users submit their info and receive AI-driven career suggestions instantly.