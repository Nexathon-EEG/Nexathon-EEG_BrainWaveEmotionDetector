# Emotion Detection from EEG Data

This project aims to detect human emotions by analyzing EEG (Electroencephalogram) signals using machine learning techniques. We combine EEG brainwave data with labeled emotional states to build a robust model capable of identifying emotions such as happy, sad, angry, relaxed, and more.

# 📁 Project Structure
- emotions.csv **Labeled emotion dataset**
- README.md **Project documentation**

# 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Nexathon-EEG/Nexathon-EEG_BrainWaveEmotionDetector.git
cd emotion-eeg-detector
```
### 2. Install Dependencies
We recommend using a virtual environment.

```
pip install -r requirements.txt
```

# 🧠 Dataset Overview
- EEG Data: Collected using brainwave sensors. Contains numerical values representing brain activity from different electrodes.
- Emotion Labels: A separate dataset categorizing emotional states associated with the EEG readings.

# 📊 Models & Techniques
- Preprocessing: Normalization, feature selection,fast fourier transform.
- Algorithms: GaussianNB, SVC, LogisticRegression, DecisionTreeClassifier, RandomForestClassifier
- Evaluation: Accuracy, confusion matrix, cross-validation

# 🔮 Goal
- To create a reliable system that can classify emotional states based on real-time brainwave data, potentially useful for mental health monitoring, gaming, meditation apps, and adaptive human-computer interaction.
