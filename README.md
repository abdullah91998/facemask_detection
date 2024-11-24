# Facemask_Detection
The project aims to detect whether a person is wearing a face mask or not using computer vision and machine learning techniques. The project utilizes the VGG16 pre-trained deep learning model and a custom dataset consisting of images with and without masks. The project is implemented using the Keras deep learning framework, OpenCV, and Python.

## Dataset
Dataset consists of 7553 RGB images in 2 folders as with_mask and without_mask. Images are named as label with_mask and without_mask. Images of faces with mask are 3725 and images of faces without mask are 3828. This dataset is taken from following link: https://www.kaggle.com/datasets/omkargurav/face-mask-dataset . The custom dataset is created by iterating through all the images in the respective directories using the OpenCV library. The images are resized to 224x224 pixels, as required by the VGG16 model. The dataset is then shuffled randomly to reduce any bias during training.

## ## Methodology
The project demonstrates the use of computer vision and machine learning techniques to detect face masks in real-time. The project utilizes the VGG16 model for feature extraction and the HaarCascade classifier for face detection. The project can be further improved by using other pre-trained models or by training a custom model on a larger dataset.
