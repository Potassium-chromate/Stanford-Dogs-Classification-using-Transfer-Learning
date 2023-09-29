# Stanford-Dogs-Classification-using-Transfer-Learning
This project aims to classify images in the Stanford Dogs Dataset using Transfer Learning, utilizing the InceptionResNetV2 architecture, a proven image classification model. The main objective is to demonstrate the capability of Transfer Learning to quickly develop highly accurate models even with limited labeled data.

# Dataset
The dataset used for this project is the [Stanford Dogs Dataset](http://vision.stanford.edu/aditya86/ImageNetDogs/), consisting of 20,580 images and 120 different dog breeds. The dataset is split into training and testing datasets.

# Dependencies
- Python
- TensorFlow
- PIL (Pillow)
- Numpy
- Pandas
- Matplotlib
- OpenCV (if used)

# Model
This project uses the **InceptionResNetV2** model with weights pre-trained on ImageNet. The top layers are then customized for the specific classification task.

# Results
The trained model classifies the dog breeds with high accuracy. The results, including predicted labels and the respective images names, are stored in an Excel file, result.xlsx.

# Visualizations
The project includes Matplotlib visualizations depicting the model's training and validation accuracy and loss over epochs.

# Acknowledgements
This project is inspired by the Stanford Dogs Dataset and makes use of the InceptionResNetV2 model available in TensorFlow.

# License
This project is licensed under the MIT License.
