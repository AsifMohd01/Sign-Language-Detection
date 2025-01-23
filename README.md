# Sign Language Detection 

This project aims to detect sign language gestures using a camera, translate them into corresponding text, and display the meaning in real-time. The tool uses machine learning, computer vision, and deep learning techniques to achieve this.

## Technologies Used:
- **Backend**: Python
- **Machine Learning**: TensorFlow (CNN)
- **Video Processing**: OpenCV
- **Gesture Detection**: Mediapipe
- **Database**: MySQL (optional, for storing data)
- **Serialization**: Pickle (for storing trained model)

## Features:
- Real-time gesture recognition using a camera.
- Gesture-to-text translation of sign language.
- Uses CNN for gesture classification.
- OpenCV for video processing.
- TensorFlow for machine learning model.

## Setup:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sign-language-detection.git
   cd sign-language-detection
## Create a virtual environment:
 python -m venv venv

## Activate the virtual environment:

## On Windows:

bash
venv\Scripts\activate
On macOS/Linux:

## On Mac
bash
source venv/bin/activate

## Install the required dependencies:
  bash
  pip install tensorflow opencv-python mediapipe mysql-connector-python

## Run the project:
  bash
  python app.py

