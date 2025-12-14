Project Overview

This project addresses the inefficiencies and errors associated with manual classroom attendance. 
I developed an automated system that captures real-time imagery, detects student faces, and logs attendance into a CSV file.

Technical Stack

Face Detection: MTCNN (Multi-task Cascaded Convolutional Networks) & Haar Cascades.
Feature Extraction: FaceNet (for generating 128-d face embeddings).
Classification: Support Vector Machine (SVM).
Tools: Python, OpenCV, Scikit-learn, Pandas.
Data Augmentation: Implemented to improve robustness under different lighting and angles.

Key Features

Real-Time Recognition: Identifies individuals through a live webcam feed.
Automated Logging: Saves attendance (Name, Timestamp) directly to a .csv file.
Custom Dataset: Built a proprietary dataset to handle specific environmental conditions.
Robustness: Integrated data augmentation to handle varying light intensities.

Lessons Learned: Accuracy vs. Functionality

One of the most significant findings in this project was the trade-off between numerical accuracy and practical application. 
While adding data augmentation and diversifying the dataset lowered the "testing accuracy" score, 
it significantly increased the system's ability to recognize faces in real-time environments—the ultimate goal of the project.
