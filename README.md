# YOLO-Licence-Plate-Detection
This project implements automatic car license plate detection using YOLO v8, and trained on a custom dataset obtained from Kaggle. The application is deployed using Streamlit for easy user interaction.

## Features
- Upload Media: Allows users to upload images or videos for license plate detection.
- Real-time Processing: Capable of processing both images and videos, displaying results promptly.
- Output Visualization: Displays annotated images or processed videos with bounding boxes around detected license plates and recognized text overlay.

## Installation
1. Clone the repository:
   https://github.com/princ0301/YOLO-Licence-Plate-Detection
   cd YOLO Licence Plate Detection

2. Install Dependencies:
    pip install -r requirements.txt

3. Run the streamlit app
   streamlit run yolo_application.py

# Uses
- Access the Streamlit web interface locally or on a server where the app is deployed.
- Upload an image or video file containing cars with visible license plates.
- Click "Proceed" to start processing.
- The application will display the processed media with annotated license plates and recognized license plate numbers.

# Dependencies
- YOLOv8: Utilized for object detection and localization.
- PyTesseract: For OCR to extract text from license plate regions.
- Streamlit: Framework for deploying and interacting with machine learning applications.
- OpenCV: Image and video processing library used for loading, processing, and saving media files.

# Acknowledgments
- Ultralytics YOLO: For providing a powerful YOLO implementation.
- Kaggle: For the dataset used for training.
- Streamlit Community: For the intuitive framework for deploying ML applications.
