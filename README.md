Potato Leaf Disease Classification using CNN

This repository contains a project focused on classifying potato leaf diseases using Convolutional Neural Networks (CNN). The project leverages TensorFlow and Keras for building and training the model, aiming to assist in the early detection and management of potato leaf diseases.
Dataset

The dataset used is from the PlantVillage repository, containing images of potato leaves labeled with various disease categories.
Key Components

    Data Loading and Preprocessing
        Load the dataset and prepare it for training, validation, and testing.
        Apply data augmentation techniques for robust model training.

    Model Architecture
        Build a CNN model using Keras Sequential API.
        Utilize convolutional and pooling layers for feature extraction.

    Model Training
        Train the model on the training dataset with validation for 15 epochs.
        Compile the model with Adam optimizer and Sparse Categorical Crossentropy loss.

    Evaluation and Prediction
        Evaluate the model on the test dataset.
        Predict classes for new images and visualize the results with confidence scores.

Instructions

    Clone the Repository:


    git clone https://github.com/yourusername/potato-leaf-disease-classification.git
    cd potato-leaf-disease-classification

Install Dependencies:


    pip install -r requirements.txt

Prepare the Dataset:

    Ensure your dataset is structured correctly and placed in the "PlantVillage" directory.

Train the Model:


    python train.py

Evaluate the Model:

    python evaluate.py

Classify New Images:

    python classify.py --image_path path/to/image.jpg
