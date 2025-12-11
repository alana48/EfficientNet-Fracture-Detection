# Fracture Detection on X-Ray Images using EfficientNet-B3

This repository provides the best-performing deep learning model developed for automated fracture detection on X-ray images. The model is based on the EfficientNet-B3 architecture and was trained using a curated dataset of fracture and non-fracture radiographs.

---

# Overview

Early and accurate detection of bone fractures is critical in clinical decision-making. This project explores a deep learning–based approach to classify X-ray images into fractured or non-fractured. EfficientNet-B3 was selected due to its favorable balance between computational efficiency and representational capacity, making it well suited for medical imaging tasks.

---

# Model Architecture

**Backbone:** EfficientNet-B3  
**Framework:** PyTorch  
**Classification Output:** Binary (Fractured / Non-Fractured)

**Training Strategy:**
- Stratified 5-Fold Cross-Validation  
- Data augmentation to increase robustness  
- Early Stopping and Model Checkpointing  
- Separate hold-out test set for final evaluation  

---

# Performance

With the application of data augmentation, the model achieved strong performance on the hold-out test set:

- **Accuracy:** 93.33%  
- **Precision:** 93.83%  
- **Recall:** 93.33%  
- **F1-Score:** 93.31%  

These results demonstrate that EfficientNet-B3 provides a reliable baseline for automated fracture detection on X-ray images.

---

# Citation

If you use this repository for academic work, please cite:
To be added once the associated article is published.

---


# License

This project is released under the MIT License. See LICENSE for more information.