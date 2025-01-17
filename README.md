# SPCUP2022: Speech Spoof Detection Challenge

The **SPCUP2022 Speech Spoof Detection Challenge**, part of the IEEE Signal Processing Cup, focused on **Synthetic Speech Attribution**. Participants were tasked with designing systems capable of identifying the specific synthesis method used to generate synthetic speech. The challenge also involved detecting speech generated by unknown synthesis algorithms, a critical task in ensuring the robustness of speech-based technologies.

---

## 🔍 Challenge Overview

The primary objective of this challenge was to classify synthetic speech into:
1. Known algorithms (e.g., Algorithm 1, Algorithm 2).
2. Unknown algorithms, requiring systems to generalize beyond the training data.

The figure below illustrates the problem setup, where a system receives an input audio waveform and predicts the synthesis method or detects it as an unknown source:
<img src="spcup_2022_img.png" alt="SPCUP2022 Visualization" width="600"/>

---

## 📂 Dataset
A dataset containing audio speech tracks generated with different speech synthesis techniques.
[SPCUP2022 Dataset](https://www.kaggle.com/datasets/awsaf49/sp22-synthetic-dataset)

---

## 📊 Results

Our method achieved **4th place** in the SPCUP2022 challenge, demonstrating robust performance in both clean and noisy conditions:
- **Part 1 (Clean Data)**: Achieved **96.5% accuracy** on the evaluation set.
- **Part 2 (Noisy Data)**: Achieved **95.5% accuracy** under noisy and distorted conditions.
  

## 📄 Detailed Report
For more detailed information about the dataset, approach, and results, refer to the official report included in this repository:  
[SPCUP2022 Report (PDF)](2022_SPCUP_report.pdf)

---

## References

1. **Official Challenge Page**:  
   [IEEE SPCUP2022](https://signalprocessingsociety.org/community-involvement/ieee-signal-processing-cup-2022)  
   - Provides official details about the challenge, including objectives, dataset composition, evaluation criteria, and participation guidelines.
     
2. **Detailed Report**:  
   [SPCUP2022 Full Report (PDF)](2022_SP_Cup_challenge.pdf)  
   - Contains a comprehensive overview of the challenge, including background, dataset details, methodology, and evaluation criteria.

