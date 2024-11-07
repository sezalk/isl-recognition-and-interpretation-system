# Indian Sign Language Recognition and Interpretation System

This project is an implementation of Indian Sign Language (ISL) recognition and interpretation system using the Mediapipe library for hand landmark detection and a Random Forest Classifier for gesture classification. It utilizes computer vision techniques to detect and recognize ISL gestures in real-time using a webcam.

## Overview

The project consists of the following components:

- **Hand Landmark Detection**: Hand landmarks are detected using the Mediapipe library, which provides a robust and accurate method for identifying key points on the hand.
- **Gesture Classification**: Hand gesture classification is performed using a pre-trained Random Forest Classifier. The classifier predicts the ISL gesture based on the hand landmarks detected by the Mediapipe library.
- **Real-time Visual Feedback**: The application provides real-time visual feedback by drawing hand landmarks and connections on the webcam feed, allowing users to see their ISL gestures being recognized.
- **Reference Image Display**: A reference image is displayed alongside the webcam feed for users to compare their gestures with the expected ISL gestures.

## Dependencies

- Python 3.x
- OpenCV
- Mediapipe
- NumPy
- Scikit-learn

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/sezalk/isl-recognition-and-interpretation-system.git

    ```

2. Install dependencies:

    ```bash
    pip install opencv-python mediapipe numpy scikit-learn
    ```

3. Download the pre-trained model file (`model_3.p`) and place it in the project directory.

## Usage

1. Run the application:

    ```bash
    python model.py
    ```

2. Perform Indian Sign Language gestures in front of the webcam and observe the real-time recognition results displayed on the screen.

3. Press 'q' to exit the application.

## Methodology

![image](https://github.com/user-attachments/assets/b717a1c1-aff2-417d-a1dd-c2ca34e8ee11)

## Dataset

![image](https://github.com/user-attachments/assets/b448dcf2-a7ba-4042-a55d-db775f665a6c)

## Pipeline

![image](https://github.com/user-attachments/assets/e69ef973-588d-426f-b816-7aff5a21e724)

## Input/Output

![image](https://github.com/user-attachments/assets/eaa25003-3ba3-4fac-8297-3ad6065beb3f)



