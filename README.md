# celebrity-face-recognition-cv
 Computer Vision project using MobileNetV2 to recognize celebrity faces
#  Celebrity Facial Recognition System

A high-performance Deep Learning project that identifies celebrity faces using **Transfer Learning**. This project demonstrates the practical application of Convolutional Neural Networks (CNNs) in a real-world classification task.

##  Overview
The goal of this project is to recognize various celebrities from a dataset. By using a pre-trained **MobileNetV2** model, I was able to leverage "Transfer Learning" to achieve high accuracy without needing weeks of training time.

## Tech Stack & Skills
- **Frameworks:** TensorFlow, Keras
- **Computer Vision:** OpenCV (cv2)
- **Architecture:** MobileNetV2 (Pre-trained on ImageNet)
- **Data Science:** NumPy, Matplotlib, Scikit-learn
- **Key Techniques:** Data Augmentation, Dropout, Batch Normalization, Learning Rate Decay

## Key Results
> **Note: Because the Jupyter Notebook output was cleared to ensure fast loading on GitHub, please refer to the screenshots below or the included PDF report.

### 1. Model in Action
*(A screenshot of who our code identifying a celebriy face correctly is here)*
![Recognition Result](result_preview.png)

### 2. Performance Graphs
The model shows strong convergence with the following accuracy and loss curves:
![Accuracy Curve](accuracy_plot.png)

## 📁 Repository Structure
- `celebrity_recognition.ipynb`: Cleaned source code and model architecture.
- `Project_Report.pdf`: Full detailed analysis, methodology, and final results.
- `requirements.txt`: List of Python libraries required to reproduce the environment.

## ⚙️ How to Use
1. Clone this repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
