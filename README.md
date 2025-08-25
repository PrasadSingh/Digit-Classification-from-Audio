# Digit-Classification-from-Audio
Model to classify spoken digits using audio data

# Spoken Digit Recognition (0–9) — Lightweight Prototype

A fast, clean, and interpretable audio classification system that listens to spoken digits and predicts the correct digit (0–9). Built for clarity, responsiveness, and extensibility—and developed in collaboration with an LLM assistant to showcase modern dev workflows.

---

##  Repository Overview

- `notebook.ipynb` — Full Colab-based pipeline.
- `utils.py` — Modular helper functions for feature extraction and model handling.
- `requirements.txt` — Dependencies: `numpy`, `pandas`, `librosa`, `scikit-learn`, `matplotlib`, `soundfile`.

---

##  Why It Stands Out

- **Modeling Choices**  
  - Combines classic audio features: **MFCCs + log-Mel spectrograms** for effective digit representation.  
  - Uses **Logistic Regression**—lightweight, interpretable, and real-time friendly.

- **Performance & Evaluation**  
  - Test Accuracy: ~**XX%** (varying slightly by random seed split).  
  - Evaluation supported by a **Confusion Matrix** for digit-level insights.

- **Responsiveness**  
  - Real-time inference: prediction takes milliseconds.  
  - Includes an audio playback of predictions in the notebook for human validation.

- **Clean Code Architecture**  
  - Modular design: feature extraction, scaling, model training, evaluation, and interactive test demos.

- **LLM Collaboration Highlight**  
  - Developed with guidance from a language model (e.g., Gemini AI assistant(included in Collab) throughout:
    - Selecting feature representation and model architecture.
    - Debugging audio-feature alignment.
    - Designing evaluation workflows and model training flow.
  - Documented with markdown ⭐ to clearly show AI-assisted development decisions.

---
