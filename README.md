# Emotion-based Image Enhancer

This project is a deep learning-based image enhancement tool that uses facial emotion recognition to apply dynamic image corrections based on detected emotions. Built using OpenCV and the FER (Facial Expression Recognition) library.

## Features

- Real-time emotion detection using the webcam.
- Adjustments to images based on recognized emotions (e.g., brightness, contrast).
- OpenCV and Python integration for efficient image processing.

## Installation

Follow these steps to set up the project:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/ChanYeongKo/emotion-based-image-enhancer.git

2.**Navigate into the project directory**:
   cd emotion-based-image-enhancer
3.**Create a virtual environment**:
   python -m venv venv
4.**Activate the virtual environment**:
  On Windows:
	venv\Scripts\activate
  On macOs/Linux:
	source venv/bin/activate

5.**Install required dependencies**:
   pip install -r requirements.txt


##Usage
-Run the program:
After installing dependencies and setting up the virtual environment, you can start the application:
	python main.py
-Instructions:
	The program will use your webcam to detect facial emotions.
	Based on the emotion detected, it will adjust the image for a better visual experience.


##Contributing
Contributions are welcome! To contribute:
  1. Fork the repository.

  2.Create a new branch (git checkout -b feature-name).

  3.Make your changes.

  4.Commit your changes (git commit -am 'Add feature').

  5.Push to the branch (git push origin feature-name).

  6.Open a pull request.




















