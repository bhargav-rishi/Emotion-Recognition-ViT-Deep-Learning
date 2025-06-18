# Emotion Recognition from Speech using Vision Transformer (ViT) - Deep Learning
![Built With](https://img.shields.io/badge/Built%20With-Python%20%7C%20PyTorch%20%7C%20Transformers%20%7C%20Deep%20Learning-blue)
![Language](https://img.shields.io/badge/Language-Python-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

This project applies deep learning to classify emotions based on audio input. Audio recordings are first converted into mel spectrogram images, which are then used as input to a fine-tuned Vision Transformer (ViT) model. The pipeline includes data preprocessing, model training with hyperparameter tuning via Optuna, performance evaluation, and real-world testing on natural vs acted speech samples. This project was developed as part of the Deep Learning course at the University of South Florida - Muma College of Business

---

## Project Overview

- **Input:** `.wav` audio files
- **Preprocessing:** Convert audio to mel spectrograms using Librosa
- **Model:** Vision Transformer (ViT) from Hugging Face
- **Training Framework:** PyTorch
- **Tuning:** Optuna used to find best learning rate, optimizer, batch size
- **Evaluation:** Accuracy, macro F1-score, confusion matrix
- **Real-world Test:** Emotion prediction from self-recorded speech in both natural and exaggerated tones

---

## Repository Structure

```
Emotion-Recognition-ViT-Deep-Learning/
├── DL_Individual_Project.ipynb
├── README.md
```



---

## Evaluation Metrics

| Metric        | Value |
|---------------|-------|
| Accuracy      | 74%   |
| Macro F1-Score| 0.75  |
| Weighted F1   | 0.74  |

Confusion matrix and classification report are available inside the notebook.

---

## Key Features

- Converts audio to mel spectrograms for visual analysis
- Fine-tuned Vision Transformer with Optuna hyperparameter search
- High interpretability and compatibility with real-world speech inputs
- Real vs acted emotion testing to evaluate generalization

---

## Business Applications

- Call center customer emotion tracking
- Voice assistant sentiment analysis
- Wellness/mental health monitoring through speech
- Emotion-aware robots and virtual caretakers

---

## Future Improvements

- Expand dataset with natural, conversational audio
- Explore raw audio models like Wav2Vec for end-to-end comparison
- Integrate into live emotion-aware agent or chatbot

---

Built using PyTorch and Hugging Face Transformers.
