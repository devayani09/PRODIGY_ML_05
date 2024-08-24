# PRODIGY_ML_05

### Food Item Recognition and Calorie Estimation Model

This project involves developing a deep learning model to recognize food items from images and estimate their calorie content, enabling users to track their dietary intake and make informed food choices. The model is built using the Food-101 dataset, which includes 101 categories of food images.

### Key Features:
- **Data Augmentation**: Applied various transformations like horizontal flipping, zooming, and rotation to enhance the training dataset's diversity.
- **Transfer Learning**: Utilized the VGG16 architecture pre-trained on ImageNet, fine-tuned with additional layers for classification specific to food categories.
- **Model Optimization**: Employed mixed precision training, reduced batch size, and early stopping to speed up the training process while maintaining accuracy.
- **Validation Split**: Automatically split the dataset into training and validation subsets using a single directory, with 20% of the data reserved for validation.
- **Performance**: Achieved accurate classification across 101 food categories, with potential for integration into dietary tracking applications.

The model is trained in a Python environment with TensorFlow/Keras and is saved as `food_recognition_model.h5` for further use and deployment.
