# CSC120_LW3_CUSTOM_IMAGE_CLASSIFIER

Student Reflection & Explanation: Custom Image Classifier
1. Dataset Preparation

How did you organize your dataset in Google Drive?
I organized my dataset by creating a main folder called ImageDataset for the project and then separate subfolders for each class of images. For example, I was classifying different types of plants, and each plant type had its own folder containing all its images. This makes it easy for TensorFlow to load the images automatically with labels.

Why is folder structure important for TensorFlow image loading?
Folder structure is important because TensorFlow uses the folder names as class labels when loading images. A consistent and organized structure ensures that each image is correctly labeled, which is essential for the model to learn and make accurate predictions.

2. Model Training

What is the role of convolutional layers in image classification?
Convolutional layers help the model detect patterns in images, such as edges, textures, or shapes. By stacking these layers, the model can learn more complex features and recognize different objects or classes effectively.

Why do we split data into training and validation sets?
We split the data to check how well the model learns. The training set teaches the model, while the validation set helps test if the model can make correct predictions on new, unseen images. This prevents the model from just memorizing the training data and ensures it generalizes well.

3. Performance Analysis

What accuracy did your model achieve?
My model achieved around [insert your accuracy]%, which shows how often it correctly predicted the class of an image.

How did the number of images affect the model’s performance?
Having more images usually improved the model’s performance because it could learn more variations of each class. With fewer images, the model sometimes misclassified similar-looking items, leading to lower accuracy.

4. Critical Thinking

What challenges did you encounter while using your own dataset?
One challenge was that some classes had very few images, which made it hard for the model to learn properly. Also, inconsistent lighting or background in images sometimes confused the model.

How can data augmentation improve your model?
Data augmentation can create new variations of existing images by rotating, flipping, or adjusting brightness. This helps the model learn to recognize objects under different conditions, improving accuracy and reducing overfitting.

5. Application

Suggest a real-world application for your trained model.
This model could be used in:

Agriculture, to identify plant diseases from photos

Retail, to classify products automatically

Wildlife monitoring, to recognize different animal species from camera trap images

How can this system be integrated into a mobile or web application?
The trained model can be saved and loaded in a mobile app using TensorFlow Lite or in a web app using TensorFlow.js. Users can then upload images, and the system will instantly classify them, providing real-time results in an accessible interface.
