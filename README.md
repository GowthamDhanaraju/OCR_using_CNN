# Character Recognition Using CNN for OCR

This project implements a Convolutional Neural Network (CNN) to recognize characters for Optical Character Recognition (OCR). The model is designed to classify handwritten or printed characters, providing a foundation for OCR systems.<br>

# CNN Structure used :
   3 Convolution layer with 1 Dense Layer and Output dense layer to classify among the 35 Different Characters.<br>

# Prerequisites
  &emsp; Python 3.8+<br>
   &emsp;TensorFlow/Keras<br>
   &emsp;Libraries: KaggleHub, NumPy, Matplotlib, Pandas, and OpenCV<br>

# Datasets used:
   &emsp;For Training - https://www.kaggle.com/datasets/vaibhao/handwritten-characters<br>
    &emsp; &emsp;Consists of individual chracters to train the CNN Model<br>
  &emsp; For Testing - https://www.kaggle.com/datasets/landlord/handwriting-recognition<br>
    &emsp; &emsp;Words to test the Trained CNN Model <br>

# Results :
   &emsp;The model was run for 70 epochs provided the following results<br>
   &emsp;Training Accuracy: 94.3%<br>
   &emsp;Validation Accuracy: 91.4%<br>

