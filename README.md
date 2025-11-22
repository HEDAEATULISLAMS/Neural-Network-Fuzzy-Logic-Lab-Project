# Neural-Network-Fuzzy-Logic-Lab-Project
Banglish-Hate-Speech-Detection | CNN-based hate speech detection for Bengali-English mixed text.
# Banglish Hate Speech Detection 🔥

A deep learning-based system for detecting and categorizing hate speech in Banglish (Bengali-English mixed) text using Convolutional Neural Networks (CNNs). Achieves 94.2% accuracy in binary classification and 89.7% in multi-class classification.

## 🚀 Features

- **Real-time Detection**: Process comments in 120ms
- **Hierarchical Classification**: Binary + Multi-class (5 hate types)
- **Custom CNN Architecture**: Parallel convolutional branches
- **Cultural Adaptation**: Specialized for Banglish linguistic patterns
- **Production Ready**: Easy deployment with REST API

## 📊 Performance

| Task | Accuracy | Precision | Recall | F1-Score |
|------|----------|-----------|--------|----------|
| Binary Classification | 94.2% | 94.1% | 94.3% | 94.2% |
| Multi-class Classification | 89.7% | 88.9% | 89.2% | 89.0% |

## 🛠️ Tech Stack

- **Deep Learning**: TensorFlow, Keras
- **Backend**: FastAPI, Python
- **Data Processing**: Pandas, Numpy
- **Visualization**: Matplotlib, Seaborn

## 📁 Dataset

- 2,410 annotated Banglish comments
- 5 hate speech categories: Sexual, Slang, Racial, Religious, Others
- Balanced distribution (50.4% hate vs 49.6% non-hate)
