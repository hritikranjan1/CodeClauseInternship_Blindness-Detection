# Blindness Detection Project

## Author
**Hritik Ranjan**

## Project Overview
The Blindness Detection project is a Python-based application using OpenCV to detect eyes in an image. This project uses a pre-trained Haar Cascade model to identify eyes, which can be a foundational step in building systems for detecting blindness or other eye-related issues through image analysis.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)
- [Contact](#contact)

## Introduction
The project detects eyes in a given image using OpenCV's Haar Cascade classifier. The goal is to demonstrate how basic computer vision techniques can be used for detecting facial features, which can later be extended for medical applications like blindness detection.

## Features
- **Eye Detection**: Detects eyes in an image using the Haar Cascade model.
- **Image Display**: Shows the image with rectangles drawn around detected eyes.
- **Scalable Model**: The model can be fine-tuned or expanded for more complex eye-related feature detection.

## Installation
To run this project, you need to install Python along with the necessary libraries. Follow these steps:

1. **Clone the repository** (if applicable):
   ```bash
   git clone https://github.com/hritikranjan1/blindness-detection.git
   cd blindness-detection
2.Install dependencies: Make sure you have Python installed, and run the following command to install OpenCV:

    pip install opencv-python

3.Prepare the image: Place your test image named eye_image.jpg in the project directory or change the filename in the code to match your image's name.
Usage

Once the dependencies are installed and the image is prepared, you can run the program as follows:

   1.un the Python script:
   
    python blindness_detection.py

2. Interpretation:

  -  The script will detect eyes in the provided image.
  -   If eyes are detected, a message saying "Eyes detected!" will be printed, and the image will be displayed with rectangles around the eyes.
  -   If no eyes are detected, a message saying "No eyes detected." will appear.
    
## Example Workflow:

    Eyes detected!

An image will appear with rectangles marking the detected eyes.
## License

This project is licensed under the MIT License - see the LICENSE file for details.
## Contact
- Name: Hritik ranjan
- GitHub: https://github.com/hritikranjan1
- LinkedIn: https://www.linkedin.com/in/hritik-ranjan-05a835230/

