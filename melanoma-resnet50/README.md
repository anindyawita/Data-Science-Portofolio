# Melanoma Detection with ResNet-50 

This project leverages **ResNet50 (CNN)** to detect skin cancer **Melanoma** from medical images.  
Goal: build a robust binary classifier (**Benign vs Malignant**) to support early detection.

# Why ResNet-50?

- Deep CNN with residual connections allows training deep networks without vanishing gradient issues.  
- Pretrained on ImageNet transfer learning speeds up training and improves feature extraction on medical images.  
- Effective for complex melanoma images with diverse patterns and textures.

# Dataset

Dataset: [Melanoma Cancer Dataset - Kaggle](https://www.kaggle.com/datasets/bhaveshmittal/melanoma-cancer-dataset)

- Number of images: 13,900 RGB images, resized to 224×224 pixels  
- Classes: Benign vs Malignant  
- Carefully curated, covering a variety of melanoma appearances  
- Purpose: advance dermatology and computer-aided diagnostics, enabling ML models for early detection

# Run in Google Colab

Open and run the notebook directly in Colab:  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/anindyawita/machine-learning/melanoma-resnet50/melanomaresnet50.ipynb)

---

# Results

- Validation Accuracy: +-92%  
- F1-score (macro avg): +-92%  
- Precision / Recall per class:
  - Benign: Precision 89.9%, Recall 94.7%  
  - Malignant: Precision 94.4%, Recall 89.4%  

# Confusion Matrix
![Confusion Matrix](results/confusion_matrix.png)

# Loss & Accuracy Curves
![Loss Curve & Validation Accuracy](results/loss_curve.png)  

