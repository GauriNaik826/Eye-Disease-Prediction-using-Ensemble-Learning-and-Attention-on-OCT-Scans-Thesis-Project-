# Eye Disease Prediction using Ensemble Learning and Attention on OCT Scans

## Abstract
Eye diseases have posed significant challenges for decades, but advancements in technology have opened new avenues for their detection and treatment. Machine learning and deep learning algorithms have become instrumental in this domain, particularly when combined with Optical Coherent Technology (OCT) imaging. 

We propose a novel method for efficient detection of eye diseases from OCT images. Our technique enables the classification of patients into:
- Disease-free (normal eyes)
- Specific conditions such as:
  - **Choroidal Neovascularization (CNV)**
  - **Diabetic Macular Edema (DME)**
  - **Drusen**

In this work, we introduce an end-to-end web application that utilizes machine learning and deep learning techniques for efficient eye disease prediction. The application allows patients to submit their raw OCT scanned images, which undergo segmentation using a trained custom U-Net model. 

The segmented images are then fed into an **ensemble model**, comprising:
1. **InceptionV3**
2. **Xception networks**

These models are enhanced with a **self-attention layer** that leverages the feature maps of individual models to achieve improved classification accuracy. The ensemble model’s output is aggregated to predict and classify various eye diseases. 

Extensive experimentation and optimization have been conducted to ensure the application’s efficiency and optimal performance. Our results demonstrate the effectiveness of the proposed approach in accurate eye disease prediction. The developed web application holds significant potential for:
- Early detection
- Timely intervention

This contributes to improved eye healthcare outcomes.

---

## Methodology

### Overview of the Approach
![System Architecture](https://github.com/user-attachments/assets/5db546bd-1bdd-435a-82e1-22643e2d9322)

### U-Net Segmentation
![U-Net Segmentation](https://github.com/user-attachments/assets/bbaed9bf-5352-4307-bcad-6abd92fa912c)

### Ensemble Model with Attention
![Ensemble Model](https://github.com/user-attachments/assets/03d4a11e-6567-4292-80e3-35d5756e481a)

---

## Results and Analysis

### Performance Metrics
![Performance Metrics](https://github.com/user-attachments/assets/02351e39-764b-4a53-97a1-78efd5ca23ee)

### Visualization of Predictions
![Predicted Results](https://github.com/user-attachments/assets/ff69ba74-f5de-4d94-b5df-67ed2a81ac7f)

### Comparison of Model Accuracy
![Accuracy Comparison](https://github.com/user-attachments/assets/ee02f780-2990-468c-a594-343438b4f943)

### Loss Curve Analysis
![Loss Curves](https://github.com/user-attachments/assets/4149d755-dc99-47ef-b336-c7b754e21747)

### Model Feature Maps
![Feature Maps](https://github.com/user-attachments/assets/c00db62f-d3e6-4f79-a55a-74c2eb6e66ca)

### Attention Visualization
![Attention Mechanism](https://github.com/user-attachments/assets/aeea328b-c23c-4ca5-8dea-4a7a631606c9)

---

## Paper Link
For more details, refer to the published paper:  
[Eye Disease Prediction using Ensemble Learning and Attention on OCT Scans](https://link.springer.com/chapter/10.1007/978-3-031-53960-2_3)

---





