This project is a Django-based web application that allows users to upload MRI scans and detect brain tumors using a Convolutional Neural Network (CNN) model.

📌 Project Overview

      Tech Stack: Django (Backend) + Bootstrap (Frontend)
      Machine Learning Model: CNN trained using TensorFlow/Keras
      Dataset: Publicly available brain MRI dataset
  
      Classification Categories:

        Glioma Tumor
        Meningioma Tumor
        Pituitary Tumor
        No Tumor (Healthy Brain)

      🚀 Features

✅ Upload MRI images for tumor detection
✅ Uses a trained CNN model for classification
✅ Supports four tumor categories: Glioma, Meningioma, Pituitary, No Tumor
✅ User-friendly web interface built with Django
✅ Displays prediction results with an alert message

🛠️ Technology Stack
1️⃣ Backend: Django (Python)

Django is a high-level Python web framework used for building scalable applications.

    1) Handles user input (image uploads)

    2) Processes model predictions using views.py

    3) Manages database models using Django ORM

2️⃣ Frontend: HTML, CSS, Bootstrap

The web interface is designed using Bootstrap for responsiveness and minimal styling.

   1) HTML templates (templates/) for rendering pages

   2) Bootstrap for styling forms, buttons, and layout

   3) JavaScript for interactive elements

3️⃣ Machine Learning: TensorFlow/Keras

The brain tumor detection model is built using a Convolutional Neural Network (CNN).

    1) TensorFlow/Keras for building, training, and saving the model

    2) Image processing (resizing, normalization)

    3) Prediction API integrated with Django

4️⃣ Database: SQLite (Default, Can Be Switched)

Django uses SQLite as the default database, but you can configure PostgreSQL or MySQL.

    1) Stores uploaded images and metadata

    2) Manages user sessions

5️⃣ Model Deployment: TensorFlow SavedModel Format (.h5)

    1) The trained CNN model is saved in .h5 format for easy loading in Django.

    2) Predictions are executed on the server-side when users upload MRI images.
