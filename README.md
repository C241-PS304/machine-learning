# Skin Track - Machine Learning Path
Bangkit 2024 Product-based Capstone

Team ID: C241-PS304

(ML) M694D4KX2638 – Fathimah Azzahra – Universitas Multi Data Palembang

(ML) M006D4KY3012 – Ariq Hafizh Baiquny – Universitas Brawijaya

(ML) M004D4KY1424 – Muhammad Fauzan Ariyatmoko – Institut Teknologi Sepuluh Nopember

# Dataset
Dataset used during experiments:

## Kaggle:
1. https://www.kaggle.com/datasets/pkompally/dark-circle
2. https://www.kaggle.com/datasets/mohit335448/ageing-dataset
3. https://www.kaggle.com/datasets/osmankagankurnaz/acne-dataset-in-yolov8-format
4. https://www.kaggle.com/datasets/cubeai/acne-detection-for-yolov8
5. https://www.kaggle.com/datasets/nayanchaure/acne-dataset

## Robloflow:
1. https://universe.roboflow.com/kritsakorn/acne-kbm0q
2. https://universe.roboflow.com/augment-gkvan/skin-problems-detection
3. https://app.roboflow.com/ariqhb/face-face
4. https://universe.roboflow.com/cobadataid/cobadata.id/dataset/7
5. https://universe.roboflow.com/dataset-jerawat/capstone-bjc8v/dataset/1

# Model and Result
Using the YoloV8s model with an image size of 1024 and an epoch count of 50
![image](https://github.com/C241-PS304/machine-learning/assets/161464447/74045865-eeb1-4837-b10c-c86ed19c8b19)
Then here is the normalized confusion matrix
![confusion_matrix_normalized](https://github.com/C241-PS304/machine-learning/assets/161464447/17e4100e-d2ef-4ce9-a5eb-0603c7c24725)
And also the following are the matrix results of various parameters
![results](https://github.com/C241-PS304/machine-learning/assets/161464447/755843d0-a53c-4158-96df-5c3c7f9ef998)
The last is the validation result of the model created from the training results.
![val_batch2_labels](https://github.com/C241-PS304/machine-learning/assets/161464447/ab28c9b2-f8e1-4385-a28c-dc3b143d3f17)

The dataset finally used:
https://app.roboflow.com/dataset-jerawat/capstone-bjc8v/12 


