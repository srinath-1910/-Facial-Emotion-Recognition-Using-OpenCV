# Facial Emotion Recognition - Multi Classification

## Overview
This project is a Facial Emotion Recognition system that classifies human emotions from facial images using machine learning and deep learning techniques. It is implemented in Python and utilizes OpenCV, TensorFlow/Keras, and other libraries for image processing and model training.

## Features
- Multi-class emotion classification (e.g., Happy, Sad, Angry, Neutral, etc.)
- Image pre-processing using OpenCV
- Deep learning model training using TensorFlow/Keras
- GUI implementation using Tkinter (if applicable)

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- Jupyter Notebook (optional)
- Required Python libraries (listed in `requirements.txt`)

### Install Dependencies
```bash
pip install -r requirements.txt
```

## Usage
1. Clone this repository:
```bash
git clone https://github.com/yourusername/Facial-Emotion-Recognition.git
```
2. Navigate to the project directory:
```bash
cd Facial-Emotion-Recognition
```
3. Run the Jupyter Notebook:
```bash
jupyter notebook "Facial Emotion Recognition - Multi Classification.ipynb"
```
4. Follow the notebook instructions to train and evaluate the model.

## Dataset
This project uses a facial emotion dataset (e.g., FER2013). Ensure you download and place the dataset in the appropriate directory before training the model.

## Model
The model is built using Convolutional Neural Networks (CNNs) with TensorFlow/Keras. It processes facial images to predict emotions.

## Results
Once trained, the model can predict emotions on new facial images. Sample results will be displayed in the notebook.

## Future Improvements
- Improve model accuracy with more data augmentation
- Implement real-time emotion detection using OpenCV
- Deploy as a web application

## Contributing
Feel free to fork this repository, make improvements, and submit pull requests.



# Emotion Recognition -cv2

This is a Python project that utilizes the `facial_emotion_recognition` library and OpenCV to detect and display facial emotions in real time using a webcam.

## Features
- Real-time facial emotion recognition.
- Uses OpenCV for video capture and display.
- Works on CPU.

## Prerequisites
Ensure you have the following installed:
- Python 3.x
- OpenCV (`cv2`)
- `facial_emotion_recognition` library

## Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/emotion-recognition.git
   cd emotion-recognition
   ```
2. Install the required dependencies:
   ```sh
   pip install opencv-python facial_emotion_recognition
   ```

## Usage
Run the script to start the emotion recognition:
```sh
python emotionRecognition.py
```

Press `ESC` to exit the application.






