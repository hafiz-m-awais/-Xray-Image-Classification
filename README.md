# X-ray Image Classification Using ResNet-18

## Overview
This project focuses on classifying X-ray images into two categories: **Normal** and **Pneumonia**. The model was built using the **ResNet-18** architecture and fine-tuned on a labeled X-ray dataset. Transfer learning was employed to improve accuracy and reduce training time.

## Key Features
- **Transfer Learning**: Used ResNet-18 pre-trained on ImageNet.
- **Binary Classification**: Labels include `NORMAL` and `PNEUMONIA`.
- **Performance Metrics**:
  - Accuracy: 78%
  - F1-Score: 82%

## Technologies Used
- Python
- PyTorch
- Matplotlib, Seaborn
- Google Colab 

## Dataset
The dataset contains X-ray images of the chest categorized as Normal or Pneumonia. It is split into training, validation, and test sets:
- **Training**: 70%
- **Validation**: 20%
- **Testing**: 10%

## Results
- **Model**: ResNet-18 fine-tuned with transfer learning.
- **Performance**:
  - Test Accuracy: 78%
  - F1-Score: 82%

## File Descriptions
- **`fine_tune_resnet18.ipynb`**: Colab notebook for fine-tuning ResNet-18 on the X-ray dataset.
- **`data`**: Contains training, validation, and test datasets.

## Instructions to Run
### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/Xray-Image-Classification.git
cd Xray-Image-Classification
