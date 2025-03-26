# MRI-Images-Detection-Using-Computer-Vision
  

This project leverages **deep learning and computer vision** to detect brain tumors from MRI scans, aiming to enhance early diagnosis and improve patient outcomes. By utilizing a **Convolutional Neural Network (CNN) with transfer learning**, the model achieves high accuracy in classifying MRI images as tumor-positive or tumor-negative.  

## Key Features  

### **1. Data Preprocessing & Augmentation**  
- MRI images are normalized, resized, and augmented to improve generalization and model performance.  
- Preprocessing steps include contrast enhancement, noise reduction, and grayscale conversion.  

### **2. Model Architecture & Training**  
- The model is built using a **CNN-based architecture**, incorporating transfer learning for optimized feature extraction.  
- Fine-tuned on a curated dataset to improve classification accuracy.  
- Training involves multiple epochs with validation to prevent overfitting.  

### **3. Performance Evaluation**  
- Utilizes key metrics such as **accuracy, precision, recall, and F1-score** to assess model effectiveness.  
- Includes a **confusion matrix and classification report** to visualize performance on test data.  

### **4. Deployment & User Interface**  
- The trained model is deployed using **Flask**, allowing users to upload MRI images for real-time tumor detection.  
- The web-based interface provides **instant classification results** with probability scores.  

This project demonstrates the **potential of AI-driven medical imaging solutions** in aiding early tumor detection and diagnosis, reducing the workload on radiologists and improving patient care.
