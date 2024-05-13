                                      TomatoVision : Robotic Eyes on Tomato Health through Ensemble Learning

Dataset Overview:
This dataset, sourced from Kaggle, consists of images captured within a greenhouse in Ecuador, specifically targeting tomato plants for automated detection of leaf conditions. The images were acquired using an autonomous robot equipped with a Raspberry Pi and a high-resolution 16-bit camera. The dataset comprises four labels:

Dried Leaves :  Images of tomato leaves showing signs of desiccation and dryness
Healthy Leaves : Images depicting normal, unaffected tomato leaves.
Leaves with Stains :  Images of tomato leaves exhibiting various types of stains or discolorations.
Leaves with Yellow Stains: Images specifically highlighting tomato leaves with yellow stains, indicative of certain illnesses or conditions.
![Data](https://github.com/AnjaliJha1221/AuTOMATO---Tomato-Leaf-Illness-Detection/blob/main/leaves.png "Data")


Solution Implemented:
Developed an ensemble model for tomato leaf illness detection, leveraging the strengths of multiple base models. The ensemble model achieved an impressive 98% test accuracy. For this, utilized the averaging method during model training.
![Methodology](https://github.com/AnjaliJha1221/AuTOMATO---Tomato-Leaf-Illness-Detection/blob/main/Screenshot%202024-05-13%20103922.png "Methodology")


Base Models and Test Accuracies:
CNN: 94.99%
InceptionV3: 61.00%
ResNet: 46.00%
VGG: 97.00%

Conclusion:
The ensemble model demonstrated robust performance in detecting various tomato leaf conditions with a high accuracy of 98%.
![Curve](https://github.com/AnjaliJha1221/AuTOMATO---Tomato-Leaf-Illness-Detection/blob/main/Train%26val_curve.png "Curve")

Result
Performance Metrics
![Performance Metrics](https://github.com/AnjaliJha1221/AuTOMATO---Tomato-Leaf-Illness-Detection/blob/main/performance%20metrics.png "Performance Metrics")

Confusion Matrix
![CM](https://github.com/AnjaliJha1221/AuTOMATO---Tomato-Leaf-Illness-Detection/blob/main/confusion%20matrix.png "CM")
Prediction Images
![Predictions](https://github.com/AnjaliJha1221/AuTOMATO---Tomato-Leaf-Illness-Detection/blob/main/predictions.png "Data")
