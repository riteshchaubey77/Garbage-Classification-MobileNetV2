# Garbage Classification using MobileNetV2

This project is part of the AICTE Internship - Week 3 Final Submission.

---

## Objective

To classify garbage images into 5 categories using Transfer Learning with MobileNetV2.

---

## Dataset Structure

The dataset is divided into:
- `train/`
- `val/`
- `test/`

Each folder contains the following 5 classes:
- `cardboard`, `glass`, `metal`, `paper`, `trash`

---

## Libraries Used

- Python 3.10
- TensorFlow
- Keras
- scikit-learn
- matplotlib
- seaborn

---

## Model Summary

- Base Model: MobileNetV2 (pretrained on ImageNet)
- Custom Layers: GlobalAveragePooling + Dense
- Output Activation: softmax (5 classes)
- Loss Function: categorical_crossentropy
- Optimizer: Adam

---

## Results

- Test Accuracy: 92.22%
- Confusion matrix and classification report generated

---

## Files Included

- `garbage_classification.ipynb` — Jupyter notebook (main code)
- `garbage_classifier_model.keras` — Trained model
- (Optional) `images/` — Screenshots or visual outputs if added

---

## Note

This repository is created as part of the AICTE Virtual Internship (2025) Week 3 Final Project Submission.  
The project demonstrates transfer learning, image classification, and model evaluation.

---

## Author

**Ritesh Kumar**  
BCA Final Year Student  
GitHub: [@riteshchaubey77](https://github.com/riteshchaubey77)


