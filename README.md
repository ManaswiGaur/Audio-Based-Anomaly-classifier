# 🔊 Audio-Based Anomaly Classifier

A machine learning project that detects anomalies in audio signals using feature extraction and classification techniques. The system processes audio data to identify unusual patterns or sounds that deviate from normal behavior — useful for industrial monitoring, security systems, and quality control.

---

## 📌 Overview

This project trains a model to classify audio recordings as **normal** or **anomalous**. It extracts meaningful features from audio signals (such as MFCCs, spectral features, etc.) and uses them to detect deviations from expected patterns.

---

## 🚀 Features

- Audio signal loading and preprocessing
- Feature extraction (MFCCs, Mel spectrograms, chroma, etc.)
- Anomaly detection and binary classification
- Model evaluation with accuracy metrics and confusion matrix
- Visualization of audio features and results

---

## 🗂️ Project Structure

```
Audio-Based-Anomaly-classifier/
│
├── Audio-Based Anomaly classifier(1).ipynb   # Main notebook
└── README.md
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core language |
| Librosa | Audio loading & feature extraction |
| NumPy / Pandas | Data manipulation |
| Scikit-learn | ML models & evaluation |
| Matplotlib / Seaborn | Visualization |
| Jupyter Notebook | Interactive development |

---

## ⚙️ Setup & Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/ManaswiGaur/Audio-Based-Anomaly-classifier.git
   cd Audio-Based-Anomaly-classifier
   ```

2. **Install dependencies**
   ```bash
   pip install librosa numpy pandas scikit-learn matplotlib seaborn jupyter
   ```

3. **Launch the notebook**
   ```bash
   jupyter notebook "Audio-Based Anomaly classifier(1).ipynb"
   ```

---

## 📊 How It Works

1. **Load Audio** — Read `.wav` or similar audio files
2. **Feature Extraction** — Extract features like MFCCs, zero crossing rate, spectral centroid
3. **Preprocessing** — Normalize and prepare feature vectors
4. **Model Training** — Train a classifier (e.g., SVM, Random Forest, or neural network) to distinguish normal vs. anomalous audio
5. **Evaluation** — Assess performance using accuracy, precision, recall, and F1-score

---

## 📈 Results

The model is evaluated on held-out test data. Key metrics include:

- **Accuracy**
- **Precision & Recall**
- **F1-Score**
- **Confusion Matrix**

---

## 🔮 Future Work

- Real-time audio anomaly detection via microphone input
- Deep learning approach using CNNs on spectrograms
- Expanding to multi-class anomaly types
- Deployment as a REST API or web app

---

## 👤 Author

**Manaswi Gaur**  
[GitHub](https://github.com/ManaswiGaur)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
