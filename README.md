# Tea Image Recognition Model

## Overview

This project is a simple image classification model created as part of an internship task. The model classifies images into one of two categories:

* Black Tea
* Green Tea

The model was created using **Google Teachable Machine** and is used through a Python script with **TensorFlow** and a **Keras (.keras)** model.

## How the Model Was Created

1. Opened **Google Teachable Machine**.
2. Created an **Image Project**.
3. Added two classes:

   * Black Tea
   * Green Tea
     
4. Uploaded training images for each class.
5. Trained the model.
6. Evaluated the model.
7. Exported the trained model.

## Project Files

* `model.keras` – The trained image classification model.
* `labels.txt` – Contains the class labels.
* `predict.py` – Python script used to classify an input image.
* `README.md` – Project documentation.

## How to Run

1. Place the image you want to classify in the project folder.
2. Replace the image path in the python script with your image path.
3. Run the prediction script:
4. The model will output the predicted class (Black Tea or Green Tea) along with its confidence score.

## Features

* Simple image classification
* Classifies Black Tea and Green Tea images
* Uses a TensorFlow/Keras model exported from Google Teachable Machine
* Beginner-friendly project

This project was developed as a learning exercise during an internship. It demonstrates the basic workflow of creating an image classification model using Google Teachable Machine and running predictions with Python.
