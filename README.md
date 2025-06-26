# Safety Helmet Detection using Faster R-CNN (PyTorch)

This project focuses on detecting and localizing safety helmets in images using a **Pretrained Faster R-CNN model built in PyTorch** implementing transfer learning. Ensuring that workers wear helmets in construction and industrial environments is crucial for safety compliance, and this model automates the monitoring process using computer vision.


## Dataset

The dataset used in this project is from Kaggle:

**[Download the Dataset from Kaggle](https://www.kaggle.com/datasets/andrewmvd/hard-hat-detection/data)**

It contains annotated images with people wearing and not wearing helmets, suitable for object detection tasks.


## Project Highlights
• Implemented a Pretrained Faster R-CNN object detection model using PyTorch to detect safety helmets.

• Applied various data augmentation techniques including horizontal flipping, brightness/contrast jittering, sharpening, resizing, and blurring to improve robustness.

• Performed hyperparameter tuning and model optimization for better accuracy and generalization.

• Used Pascal VOC XML annotations for training and bounding box localization.

## Evaluation & Results
Model Architecture: Fast R-CNN using a pre-trained backbone

Evaluation Metric: Mean Average Precision (mAP)

Test Performance:

• Obtained the best mAP = 0.6117 @ IoU=0.50


Visualizations of predictions were plotted using Matplotlib and OpenCV to verify correct bounding box placement and class predictions.
## 👤 Author
### Sourav Dhar

B.Tech + M.Tech in Mechanical & Financial Engineering

Indian Institute of Technology, Kharagpur
