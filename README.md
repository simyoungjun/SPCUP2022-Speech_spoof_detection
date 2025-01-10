# SPCUP2022: Speech Spoof Detection Challenge

The **SPCUP2022 Speech Spoof Detection Challenge**, part of the IEEE Signal Processing Cup, focused on **Synthetic Speech Attribution**. Participants were tasked with identifying the specific synthesis method used to generate a given synthetic speech recording, a critical step in ensuring the security of speech-related technologies.

---

## 🔍 Challenge Overview

The challenge aimed to develop systems capable of distinguishing between various speech synthesis methods, including:
- **Text-to-Speech (TTS)** techniques.
- **Voice Conversion (VC)** methods.

Participants were provided with audio recordings generated using multiple synthesis methods. The evaluation focused on the system's ability to correctly classify the synthesis technique, particularly in challenging, perturbed conditions.

---

## 📂 Dataset

- The dataset included **synthetically generated speech** using different synthesis techniques.
- Split into training and evaluation sets, each containing multiple classes corresponding to synthesis methods.
- Provided in a time-domain format, requiring feature extraction (e.g., **log-mel spectrograms**) for model training.

---

## 🛠️ Approach

1. **Feature Extraction**:
   - Extracted **log-mel spectrograms** to represent speech signals in the time-frequency domain.

2. **Model Architecture**:
   - Employed **Convolutional Neural Networks (CNNs)** to capture spatial hierarchies in spectrograms.
   - Used an ensemble of CNNs for improved robustness and generalization.

3. **Semi-Supervised Learning**:
   - Applied semi-supervised techniques to handle unknown synthesis methods and improve classification performance.

---

## 📊 Results

- **Best Accuracy**: Achieved state-of-the-art performance on strongly perturbed evaluation conditions.
- **Equal Error Rate (EER)**: Demonstrated significant improvement compared to baseline models.

---



## 📄 References

1. **Official Challenge Page**:  
   [IEEE SPCUP2022](https://signalprocessingsociety.org/community-involvement/ieee-signal-processing-cup-2022)  
   - Provides official details about the challenge, including objectives, dataset composition, evaluation criteria, and participation guidelines.

2. **Paper**:  
   [Syn-Att: Synthetic Speech Attribution via Semi-Supervised Unknown Multi-Class Ensemble of CNNs](https://arxiv.org/abs/2309.08146)  
   - Describes a CNN-based approach combined with semi-supervised learning techniques for synthetic speech classification, specifically tailored for SPCUP2022.
