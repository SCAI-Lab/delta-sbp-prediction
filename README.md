# delta-sbp-prediction

This repository contains the official implementation of our multimodal deep learning framework for real-time beat-to-beat ΔSBP (delta Systolic Blood Pressure) estimation using physiological signals and demographic data.

---

## Summary

We propose a hybrid CNN–BiLSTM–attention model that fuses:

- **Photoplethysmogram (PPG)**
- **Electrocardiogram (ECG)**
- **Demographic features** (e.g., age, gender, BMI)

The model is pretrained on the **Aurora BP dataset** and fine-tuned on a clinical **SCI (Spinal Cord Injury) cohort** via transfer learning. It satisfies international standards for BP monitoring systems (AAMI, BHS, IEEE 1708a-2019).

---


##  Citation
If you use this codebase, please cite our paper (coming soon).

---

##  Repository Structure

```text
├── src/                
├── supplementary_materials/
├── README.md
├── LICENSE
└── requirements.txt     # Python dependencies



