# Cat -dog-Classifier-Model

The **Cat-Dog Classifier Model** is a deep learning project that uses a CNN to classify images as either cats or dogs. The model is trained on a dataset of labeled images, where the input images are resized to 100x100 pixels with three color channels (RGB) and normalized to a range of 0 to 1 for efficient training. The CNN architecture consists of convolutional layers to extract features, pooling layers to reduce feature map dimensions, and dense layers to perform binary classification using a sigmoid activation function. The model is compiled with the binary cross-entropy loss function and optimized using the Adam optimizer. During training, the model learns patterns in the data over five epochs. For predictions, if the model's output probability is greater than 0.5, the image is classified as a dog; otherwise, it is classified as a cat. This project demonstrates a simple and effective approach to binary image classification using deep learning.

## Importing Libraries and Preprocessing the Dataset
![Importing lib and preprocessing](https://github.com/user-attachments/assets/a54d83a0-f9ee-47e7-bab2-1da629fb2ecc)


## Randomly Generating a image and Train the model
![Random Image preview and Model Training](https://github.com/user-attachments/assets/71415543-6c73-4002-ba34-88ed64336f05)


## Result
![Final Result](https://github.com/user-attachments/assets/f0df5058-72d7-4966-82a6-cf487e2a4449)
