# Deep_Learning_Image_clasification

Project Overview: 
 This project was developed during the summer of 2024, in collaboration with a professor, and focuses on classifying images into seven distinct categories. Each class contains 80 images, making up the dataset used for training and validation.

The goal was to build and evaluate a deep learning model using different transfer learning techniques like VGG16, DenseNet201, and Xception to determine the best-performing architecture for classifying the images.

Dataset:
Classes: 7 categories.
Images per Class: 80 images.
Total Images: 560.
Image Size: Resized to 224x224 pixels.

![image](https://github.com/user-attachments/assets/2bb4df34-dcc7-4d67-855a-d5739c54da76)

![image](https://github.com/user-attachments/assets/6c84c6ab-f884-4c25-9e39-38016a8952b0)


![image](https://github.com/user-attachments/assets/ea241839-c389-4f58-bc64-1ede69764f8f)




Steps Followed:
1. Loading the Dataset
The dataset was loaded from Google Drive into Google Colab for training. Data was divided into training and validation sets.

2. Data Preprocessing
Images were preprocessed using the ImageDataGenerator class, including normalization and resizing to 224x224 pixels.

3. Model Building
I explored multiple models using transfer learning techniques like VGG16, DenseNet201, and Xception.

4. Evaluation
After training, the models were evaluated, and the performance was analyzed based on accuracy. Misclassified samples were also examined to identify potential patterns.

5. Visualization
A graph was plotted comparing the accuracy of the different transfer learning models.
