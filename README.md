
# Emotion Detection Using AI

## Overview

This project is designed to detect emotions from facial expressions using deep learning models. It utilizes pre-trained models to classify emotions based on input images.

## Requirements

To run this project, you need to ensure that your Python environment has the necessary libraries installed and is compatible with the project's requirements. This project has been tested with specific versions of TensorFlow and Keras. Compatibility issues may arise if different versions are used.

### Required Libraries

- TensorFlow 2.4.0
- Other dependencies are included with TensorFlow, but additional packages may be required based on your environment.

### Setup

1. **Create a Conda Environment:**

   Create a new Conda environment for this project:
   conda create --name emotion-detection-env python=3.8
   conda activate emotion-detection-env

Install Dependencies:

# Install TensorFlow (which includes Keras):


# Anaconda
Copy code
pip install tensorflow==2.4.0
Run the Project:

Navigate to the project directory and execute the script:



# Anaconda 
Copy code
python test.py


# Notes
Compatibility: Ensure that the versions of TensorFlow and Keras match those specified in this project. Using incompatible versions may lead to errors. If you encounter issues, refer to the TensorFlow compatibility guide for more details.
GPU Support: If you have a GPU and want to enable GPU support, make sure to install the correct CUDA and cuDNN versions. For CPU-only usage, this warning can be ignored.
