# photographer-identification-CNN
Photographer Identification using CNNs (ResNet-18, ResNet-34, ResNet-50, AlexNet,VGG16)
# Photographer Identification Using CNNs

## Project Description
This project aims to identify the photographer of an image using Convolutional Neural Networks (CNNs).  
It explores multiple CNN architectures, including ResNet-18, ResNet-34, ResNet-50,VGG16 and AlexNet, to classify images taken by 48 professional photographers.  
The goal is to predict the photographer from a given image with high accuracy.

---

## Dataset
- Total images: 4800  
- Train set: 4000 images  
- Test set: 800 images  
- Number of classes: 48 (each representing a different photographer)  

**Note:** Dataset images are collected from professional photographers and divided into train and test sets.  

---

## Models Used
- **ResNet-18**  
- **ResNet-34**  
- **ResNet-50**  
- **Custom CNN**  

Each model is trained and evaluated for precision, recall, F1-score, and confusion matrix.

---

Due to the large number of classes (48 photographers), Accuracy,precision, recall, and F1-scores vary significantly across classes.  
Instead of listing all per-class metrics here, the detailed classification reports and confusion matrices for each model are provided in the `results/` folder.

| Model        | Accuracy | Precision | Recall | F1-Score |
|-------------|----------|-----------|--------|----------|
| ResNet-18   |    -     | -         | -      | -        |
| ResNet-34   |    -     | -         | -      | -        |
| ResNet-50   |    -     | -         | -      | -        |
| Custom CNN  |    -     | -         | -      | -        |

📌 **Note:** Check `results/` for the full per-class metrics and confusion matrices.
---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/photographer-identification.git
