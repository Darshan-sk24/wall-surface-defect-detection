#  Wall Surface Defect Detection

##  Project Description

This project focuses on identifying and classifying defects on wall surfaces using deep learning and image classification techniques. It aims to automate the detection of cracks, damp spots, peeling paint, and other visual defects commonly found on walls. The system is designed to assist in maintenance, quality checks, and construction site inspections by minimizing human effort and increasing reliability in surface evaluation.



##  Objectives

- Detect surface-level anomalies in wall images.
- Classify different types of wall defects such as cracks, dampness, and paint peel-off.
- Utilize pretrained deep learning models like VGG16 and MobileNet for efficient feature extraction and classification.
- Develop a portable and adaptable system suitable for real-world use.



##  Tools and Technologies

- Python
- Google Colab (for development and training)
- TensorFlow / Keras
- OpenCV
- NumPy / Pandas
- Matplotlib / Seaborn
- VGG16 / MobileNet (Pretrained CNN Models)



##  Dataset

- The model was trained on a custom dataset consisting of labeled images of different wall defects.
- Categories included:
  - Cracks
  - Efflorescence
  - Peeling Paint
  - Mold / Dampness
- Images were resized and augmented for better generalization and accuracy.

s

##  Model Overview

- Transfer Learning was used with models like VGG16 and MobileNet to leverage pre-trained weights.
- Final layers were customized for binary or multi-class classification based on defect type.
- Training was performed on Google Colab using GPU acceleration for faster computation.



##  Evaluation Metrics

- Accuracy
- Precision & Recall
- Confusion Matrix
- Loss & Accuracy Curves

The model achieved high accuracy on the validation dataset and performed well on unseen test images, showing strong generalization capability.


##  How to Run the Project

1. Open the provided `.ipynb` file in Google Colab.
2. Upload or link the dataset folder in your Colab environment.
3. Run the notebook cells step by step:
   - Import Libraries
   - Load and Preprocess Dataset
   - Initialize and Compile Model
   - Train the Model
   - Evaluate and Test with New Images
4. Optionally, export the trained model using `.h5` format.



##  Output

- The model outputs the predicted defect type for input wall images.
- Visualizations include:
  - Training vs Validation Accuracy
  - Training vs Validation Loss
  - Sample predictions with image labels



##  Future Enhancements

- Deploy the model as a web or mobile app for live wall scanning.
- Expand dataset to include more real-world wall defect scenarios.
- Integrate with IoT devices for automated inspection.



##  Author

Darshan S K  
Wall Surface Defect Detection using Deep Learning  
(https://github.com/Darshan-sk24/wall-surface-defect-detection)


