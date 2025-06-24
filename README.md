# Flood Detection and Prediction System

Welcome to the **Flood Detection and Prediction System**! This project leverages advanced machine learning models and satellite imagery to identify and predict flood scenarios. It provides a user-friendly interface for real-time predictions, making it a valuable tool for disaster management and early warning systems.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contact](#contact)

## Introduction
The Flood Detection and Prediction System is designed to:
- Classify images as flooded or non-flooded using **MobileNet**.
- Segment flood areas using a **Deep Convolutional Neural Network (DCNN)**.
- Calculate the **Normalized Difference Water Index (NDWI)** for identifying water bodies in satellite images.  

This project aims to provide an efficient and scalable solution for flood analysis, helping communities and organizations prepare for and mitigate the effects of flooding.

## Features
- **Real-Time Detection**: Classify and segment flood areas instantly.
- **NDWI Analysis**: Extract water body regions from satellite imagery.
- **Scalable Architecture**: Handle large datasets for disaster management.
- **Web Integration**: A Flask-based web application for uploading and analyzing images.
- **User-Friendly Interface**: View detailed results, including segmented images and predictions.

## Installation
To set up the project on your local machine:

1. Clone the repository:
    ```sh
    git clone https://github.com/YourUsername/Flood-Detection-System.git
    cd Flood-Detection-System
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv venv
    source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

4. (Optional) Download and set up the dataset:
    - Place the dataset in the `data/` directory.
    - Ensure the dataset follows the structure specified in the project documentation.

5. Start the Flask application:
    ```sh
    flask run
    ```

6. Access the application:
    Open your web browser and navigate to `http://127.0.0.1:5000/`.

## Usage
1. **Upload an Image**: Navigate to the upload page and select an image file.
2. **Analyze Results**:
   - The system will classify the image as `Flooded` or `Not Flooded`.
   - It will provide segmented results highlighting the flood-affected areas.
   - If enabled, NDWI analysis will show water body detection results.
3. **Download Outputs**: Save the processed and segmented images for further use.



## Contact
For inquiries, suggestions, or support, feel free to reach out:

- **Email**: [kavyasrivj271@gmail.com](mailto:kavyasrivj271@gmail.com)  
- **GitHub**: [https://github.com/kav-xx/](https://github.com/kav-xx/)  


