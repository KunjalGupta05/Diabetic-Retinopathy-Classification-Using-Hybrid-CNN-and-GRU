# Diabetic-Retinopathy-Classification-Using-Hybrid-CNN-and-GRU

Diabetic retinopathy (DR) is a leading cause of blindness worldwide, making early and accurate detection crucial. This project implements a deep learning pipeline for the automated detection of diabetic retinopathy using fundus images. The dataset, sourced from the Kaggle APTOS 2019 Blindness Detection competition, consists of 3,662 retina scan images. 

Dataset used:-
https://www.kaggle.com/datasets/sovitrath/diabetic-retinopathy-224x224-2019-data

The below figure is a snippet of the dataset

![image](https://github.com/user-attachments/assets/82f1ea3b-0ee3-4b8f-a415-a5f985ebdf99)

These images, resized to 224x224 pixels, were preprocessed using techniques like Contrast Limited Adaptive Histogram Equalization (CLAHE), noise reduction, and cropping to enhance feature extraction and improve model performance. A hybrid Convolutional Neural Network (CNN) architecture, combined with a Gated Recurrent Unit (GRU) for temporal modeling, was employed to classify the fundus images into different DR severity levels. The dataset was split into training (70%), validation (20%), and test (10%) subsets to ensure a rigorous evaluation framework. The final model achieved an accuracy of 71.93% on the test set, demonstrating its potential in identifying diabetic retinopathy. The best-performing model was saved during training and validation phases, ensuring reliability for real-world clinical scenarios.

This figure is a flowchart of the proposed model in this project.

![image](https://github.com/user-attachments/assets/b140d3e2-c9ad-41cf-927c-7da186e3714d)



