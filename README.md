#  Deep Learning Project Portfolio: CNN Image Classification

This repository showcases two foundational computer vision projects using **Convolutional Neural Networks (CNNs)** built with **TensorFlow/Keras**.  
It demonstrates the full deep learning pipeline — from **data preprocessing** and **model design** to **training**, **evaluation**, and **performance analysis** — across datasets of increasing complexity.

---

## Project Overview

**Project 1 — MNIST (Handwritten Digits)**  
- Image Type: Grayscale (28×28×1)  
- Task Complexity: Foundational pattern recognition  
- Final Accuracy: **98.39%**

**Project 2 — CIFAR-10 (Color Objects)**  
- Image Type: Color (32×32×3)  
- Task Complexity: Complex real-world feature extraction  
- Final Accuracy: **74.16%**

---

##  Project 1: MNIST Classification (Grayscale Digits)

This project served as the initial benchmark to confirm the basic functionality and learning capacity of a CNN.

###  Methodology
- **Architecture:** A shallow CNN with a single `Conv2D` layer, followed by `MaxPooling` and a fully connected `Dense` classifier head.  
- **Preprocessing:** Normalization of image pixels to the range `[0, 1]`.  

### Key Takeaway
The model achieved **98.39% accuracy**, demonstrating that even a small CNN can effectively recognize simple grayscale patterns.  
Most of the model’s misclassifications occurred on **ambiguous digits**, such as a poorly written “3” being classified as an “8”.

---

##  Project 2: CIFAR-10 Classification (Color Objects)

This project introduced a major increase in complexity, using small color images of real-world objects.  
It represented a significant step toward understanding how CNNs handle color, texture, and object abstraction.

### Methodology
- **Architecture:** A deeper CNN with two convolutional blocks, each containing two `Conv2D` layers to progressively capture features from edges to textures and object parts.  
- **Regularization:** Applied `Dropout` (0.25 and 0.5) extensively to reduce overfitting and improve generalization on this relatively small dataset.

### Key Takeaway
The model reached **74.16% accuracy**, showing strong feature learning capability well above random chance (10%).  
Validation accuracy often exceeded training accuracy, suggesting excellent generalization and hinting that further training or augmentation could push performance toward **80%+**.

---

## Technology Stack

- **TensorFlow / Keras** – Core framework for building and training CNN architectures.  
- **NumPy** – Numerical operations and array handling.  
- **Matplotlib** – Visualization of image samples, learning curves, and confusion matrices.  
- **Scikit-learn** – Classification reports and performance metrics.

---

## Future Improvements

- Introduce **Batch Normalization** to improve training stability.  
- Add **Data Augmentation** (rotation, flip, zoom) to increase generalization.  
- Experiment with **Transfer Learning** using pretrained models (e.g., VGG16, ResNet50).  
- Implement **TensorBoard** for richer experiment tracking.

---

## Repository Structure



---

## Export to Google Sheets

The project summary (datasets, performance metrics, and takeaways) can be easily copied into **Google Sheets** for experiment tracking or comparison with future models.

---

## Author

**SADIK ADEN DIRIR**  
Machine Learning Engineer / Deep Learning Enthusiast  
📧 spiritx98@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/sadik-aden-a24440385/) • [GitHub](https://github.com/Sadikn7i)


---
https://github.com/Sadikn7i
⭐ *If you found this project useful, please consider starring the repository!*
