<div align="center">

# AI Empathetic Chatbot with Multimodal Fusion

[![Python](https://img.shields.io/badge/Python-3.11-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-Deep_Learning-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)](https://tensorflow.org)
[![OpenCV](https://img.shields.io/badge/OpenCV-Computer_Vision-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)](https://opencv.org)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-NLP-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co)
[![Domain](https://img.shields.io/badge/Domain-Affective_Computing-ec4899?style=for-the-badge)](.)

> A chatbot that understands how you feel - by reading your face, voice, and words simultaneously.

</div>

---

## The Core Idea

Most chatbots only understand **what** you say. This one understands **how** you feel by fusing three emotional signals together:

```
Your Face  ---> CNN Facial Expression Recognition  --->|
Your Voice ---> Speech Emotion Recognition         --->|---> Fusion ---> Empathetic Response
Your Words ---> NLP Sentiment Analysis             --->|
```

---

## Modalities

| Signal | Model | What It Detects |
|---|---|---|
| **Facial Expression** | CNN (custom trained) | Happy, Sad, Angry, Surprised, Neutral, Fear |
| **Speech Emotion** | Audio feature extraction + classifier | Arousal, valence, emotion category |
| **Text Sentiment** | HuggingFace Transformers | Positive, Negative, Neutral |
| **Fusion Layer** | Weighted ensemble | Combined emotional state score |

---

## Features

- Real-time webcam facial emotion detection
- Microphone input for speech emotion analysis
- NLP pipeline for text understanding
- Adaptive responses based on detected emotional state
- Full web application interface

---

## Tech Stack

```
TensorFlow / Keras   - CNN model training and inference
OpenCV               - face detection and video capture
HuggingFace          - transformer NLP models
librosa              - audio feature extraction (MFCCs)
Flask / Streamlit    - web app framework
```

---

## Run Locally

```bash
git clone https://github.com/arunima-anil/AI-Empathetic-Chatbot-with-Multimodal-Fusion-
cd AI-Empathetic-Chatbot-with-Multimodal-Fusion-
pip install -r requirement.txt
python APP/app.py
```

---

<div align="center">Built as part of AI & Data Science portfolio | <a href="https://github.com/arunima-anil">@arunima-anil</a></div>
