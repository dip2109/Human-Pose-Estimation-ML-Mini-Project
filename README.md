𝗛𝗨𝗠𝗔𝗡 𝗣𝗢𝗦𝗘 𝗘𝗦𝗧𝗜𝗠𝗔𝗧𝗜𝗢𝗡

This repository contains the implementation and findings of an automated yoga pose recognition system. The system aims to accurately identify and classify yoga poses using deep learning models and computer vision techniques.
We have used dataset containing different yoga poses which is available public. 
Link of dataset:https://www.kaggle.com/datasets/niharika41298/yoga-poses-dataset

The practice of yoga has gained widespread popularity due to its numerous health benefits. With the increasing demand for technology-assisted learning platforms, there is a growing need for accurate methods for recognizing yoga poses. Incorrect posture during yoga practice can lead to serious injury, emphasizing the critical need for precise pose detection and classification.

This project focuses on comparing two deep learning models, Ultralytics and Movenet, for detecting keypoints in yoga poses. These keypoints are subsequently utilized for classification into five distinct yoga poses: downdog, goddess, plank, tree, and warrior2. The evaluation of the models is conducted based on accuracy metrics, with Movenet demonstrating superior performance.

Key Features:
 1. Utilization of YOLOv8 and MoveNet models for yoga pose detection.
 2. Classification of yoga poses into downdog, goddess, plank, tree, and warrior2.
 3. Evaluation of model performance using accuracy metrics, precision, recall, and F1-score.
 4. Dataset preprocessing for normalization and key point extraction.
