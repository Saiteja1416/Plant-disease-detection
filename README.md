# Large-Scale Crop Monitoring and Disease Detection System

## Project Overview

This project presents an AI-based crop monitoring and disease detection system using Computer Vision and Deep Learning. The system analyzes crop leaf images and automatically identifies the crop and disease condition.

## Technology Used

- Python
- Google Colab
- TensorFlow / Keras
- MobileNetV2
- Computer Vision
- Deep Learning
- PlantVillage Dataset

## Dataset

The model was trained and evaluated using the PlantVillage dataset containing 38 crop/disease classes.

- Training Images: 43,444
- Validation Images: 10,861
- Number of Classes: 38
- Image Size: 224 × 224 pixels

## Model

MobileNetV2 was used with ImageNet transfer learning. Data augmentation and dropout were applied to improve model generalization.

## Results

The trained model achieved:

| Metric | Result |
|---|---:|
| Validation Accuracy | 94.34% |
| Macro Precision | 93.59% |
| Macro Recall | 91.72% |
| Macro F1-Score | 92.24% |
| Weighted F1-Score | 94.15% |

## Features

- Crop disease classification
- Healthy/diseased identification
- Confidence score
- Disease-management recommendations
- Batch image monitoring
- Grad-CAM explainability

## Project Team

1. M. Saiteja – 23EG102B25
2. S. Sainath – 23EG102B43
3. A. Vinith – 24EG502B15
4. S. Bhargava – 24EG502B22

**Department:** EEE  
**University:** Anurag University  
**Project Guide:** T. Dinesh  
**Academic Year:** 2026–27

## Repository Contents

- `Crop_Disease_Detection_MobileNetV2.ipynb` – Google Colab implementation
- `crop_disease_mobilenetv2.keras` – trained MobileNetV2 model
- `crop_monitoring_results.csv` – batch prediction results
- `Crop_Disease_Detection_Project_Documentation_Final.docx` – project documentation

## How to Run

1. Open the `.ipynb` notebook in Google Colab.
2. Enable GPU runtime.
3. Upload/mount the required dataset.
4. Run the notebook cells in sequence.
5. Use the prediction section to test crop leaf images.

## Conclusion

The proposed system demonstrates the application of deep learning for automated crop disease detection. The MobileNetV2 model achieved 94.34% validation accuracy across 38 classes and can support faster and scalable crop-health monitoring.
