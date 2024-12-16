# Skin Disease Recognition and Classification System

This project aims to develop an end-to-end **skin disease recognition and classification system** that integrates convolutional networks and attention mechanisms to enhance the detection and classification of skin lesions, including melanoma and seven other diseases. 

## Key Features
- **Segmentation Techniques**: Extract diseased skin regions for classification on both original and segmented images, with a comparative performance analysis.
- **Attention Mechanisms**: Utilizes spatial, channel, and self-attention mechanisms for improved classification accuracy and interpretability.
- **Multi-Scale Feature Extraction**: Leverages hierarchical classification to distinguish between benign and malignant lesions before identifying specific diseases.
- **Datasets**: Employs datasets such as ISIC and HAM10000 for training and evaluation.
- **Comparative Analysis**: Analyzes performance differences between attention-based models and baseline models.

## Methodology
1. **Data Preprocessing**: Segmentation to isolate diseased regions.
2. **Model Architecture**:
   - Incorporates multi-scale feature extraction.
   - Implements spatial, channel, and self-attention mechanisms.
3. **Classification Pipeline**:
   - Hierarchical classification to separate benign and malignant lesions.
   - Disease-specific classification for multi-class recognition.
4. **Performance Evaluation**: Comparative analysis of classification accuracy on original vs. segmented images.

## Results
- **Model Performance**: 
  - Models incorporating attention mechanisms significantly outperformed others.
  - The **Inception ResNet V2 with soft attention** achieved the highest performance.
- **Accuracy**:
  - **Multi-class classification**: Excels across seven disease categories.
  - **Binary classification**: Achieved an accuracy of **89.60%** in identifying malignant lesions.
  
## Significance
This approach advances early diagnosis and clinical decision support by improving classification accuracy and interpretability. It demonstrates the potential for real-world clinical applications, particularly in the early detection and management of skin diseases.

## Conclusion
The **Inception ResNet V2 with soft attention** stands out as the most effective model for clinical application, excelling in both multi-class and binary classification tasks.

---

## Team 5:  Members
- **Jaswanth Kranthi Boppana**  
  Email: [jboppana@iu.edu](mailto:jboppana@iu.edu)
- **Pranay Reddy Gundala**  
  Email: [vgundala@iu.edu](mailto:vgundala@iu.edu)
- **Ranvir Singh Virk**  
  Email: [rsvirk@iu.edu](mailto:rsvirk@iu.edu)
- **Venkata Ramakrishna Reddy Dwarampudi**  
  Email: [vedwar@iu.edu](mailto:vedwar@iu.edu)
