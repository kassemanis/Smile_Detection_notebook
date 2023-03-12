# Smile Detection Jupyter Notebook

This Jupyter Notebook provides a Python implementation for smile detection using TensorFlow, Keras, OpenCV, and Haar Cascades.

## Requirements

* Python 3.x
* TensorFlow
* Keras
* matplotlib
* imutils
* OpenCV
* IPython
* google-colab
* NumPy
* SciPy
* Six

## Installation

1. Clone or download the repository.
3. Open the Jupyter Notebook `smile_detection.ipynb`.

## Usage

1. Run the Jupyter Notebook by typing `jupyter notebook` in the terminal and navigating to the `smile_detection.ipynb` file.
2. Follow the instructions provided in the notebook to detect smiles in images and videos.

## Methodology

This implementation uses Haar Cascades, a machine learning-based approach for object detection in images and videos. A Haar Cascade is a set of trained classifiers that can be used to detect specific objects in images or videos. The implementation uses a pre-trained Haar Cascade classifier for face detection and another for smile detection. These classifiers are used to detect the presence of a face and a smile in each frame of the video or image.

The smile detection model is based on a Convolutional Neural Network (CNN) architecture. The model is trained on a dataset of images of smiling and non-smiling faces using TensorFlow and Keras. The trained model is then used to classify each detected face as smiling or non-smiling.

## Credits

The smile detection implementation in this notebook is based on Adrian Rosebrock's article on PyImageSearch: Smile detection with OpenCV, Python, and deep learning. The Haar Cascades used in this implementation are from the OpenCV GitHub repository: https://github.com/opencv/opencv/tree/master/data/haarcascades. The smile detection model is trained on a subset of the CelebA dataset.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## All rights reserved

© Bouali Kassem Anis, MSc student at the University of Debrecen. All rights reserved.
