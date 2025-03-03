# Number Recognition Tool

## Overview
Number Recognition Tool is a machine learning-based application that recognizes handwritten digits from images. It utilizes Convolutional Neural Networks (CNN) trained on the MNIST dataset to accurately classify digits from 0 to 9. The tool provides a graphical user interface (GUI) that allows users to input an image containing a number and receive its predicted value.

## Features
- Recognizes handwritten digits from images
- Uses CNN for accurate classification
- Interactive GUI for easy image input
- Supports image input from local storage
- Trained on the MNIST dataset

## Technologies Used
- **Programming Language:** Python
- **Libraries:** TensorFlow, Keras, NumPy, OpenCV, Tkinter
- **Dataset:** MNIST (Modified National Institute of Standards and Technology)
- **Development Tools:** Google Colab, Jupyter Notebook, Sublime Text, Spyder

## Installation
To run the Number Recognition Tool, follow these steps:

```sh
# Clone the repository
git clone https://github.com/your-username/number-recognition-tool.git
cd number-recognition-tool

# Install dependencies
pip install tensorflow keras numpy opencv-python tk

# Run the application
python app.py
```

## Usage
- Open the application.
- Upload or draw a handwritten digit on the canvas.
- Click the "Recognize" button to get the predicted number.

## System Requirements
### Hardware:
- Minimum 4 GB RAM
- 1 GB free storage
- Dual-Core CPU

### Software:
- Windows/Linux/MacOS
- Python 3.x
- Any supported IDE (Jupyter Notebook, Spyder, Sublime Text)

## Algorithm Workflow
1. **Preprocessing:** Convert input images to grayscale and normalize pixel values.
2. **Feature Extraction:** Apply CNN layers to extract digit features.
3. **Prediction:** Use trained model to classify the digit.
4. **Display Output:** Show recognized digit in the GUI.

## Future Enhancements
- Improve segmentation algorithms for better accuracy.
- Extend the tool to recognize complex handwritten text.
- Implement a mobile version for real-time recognition.

## Screenshots

### Main Interface
![Main Interface](screenshots/main-interface.png)

### Example Recognition
![Recognition Example](screenshots/recognition-example.png)

### Result 
![Result](screenshots/result.png)


## Contributors
- **Chetna Bhurani** (Original Author)



