# Character Recognition Using CNN for OCR

This project implements a Convolutional Neural Network (CNN) to recognize characters for Optical Character Recognition (OCR). The model is designed to classify handwritten or printed characters, providing a foundation for OCR systems.<br>

# CNN Structure used :
   3 Convolution layer with 1 Dense Layer and Output dense layer to classify among the 35 Different Characters.<br>

# Prerequisites
   Python 3.8+<br>
   TensorFlow/Keras<br>
   Libraries: KaggleHub, NumPy, Matplotlib, Pandas, and OpenCV<br>

# Datasets used:
   For Training - https://www.kaggle.com/datasets/vaibhao/handwritten-characters<br>
     Consists of individual chracters to train the CNN Model<br>
   For Testing - https://www.kaggle.com/datasets/landlord/handwriting-recognition<br>
     Words to test the Trained CNN Model <br>

# Results :
   The model was run for 70 epochs provided the following results<br>
   Training Accuracy: 94.3%<br>
   Validation Accuracy: 91.4%<br>

