# Image-Editing-Application
Simple Image Editing App using Streamlit
This is a simple image editing app built with Python using Streamlit, OpenCV, PIL (Pillow), and NumPy. The app provides various image editing features, including:

Face and Eye Detection: It uses Haar Cascade files for detecting faces and eyes in images.

Image Processing Libraries:

OpenCV: Used for various image manipulation tasks.
PIL (Pillow): Used for opening, manipulating, and saving images.
NumPy: Used for numerical operations on image data.
Image Editing Features:

Grayscale: Convert images to grayscale.
Sharpeness: Enhance the sharpness of images.
Brightness: Adjust the brightness of images.
Cartoonize: Apply a cartoon effect to images.
Cannize: Apply a cannabis (stylized) effect to images.
Blurring: Apply various blurring techniques to images.
Contrast: Adjust the contrast of images.
Installation
Clone this repository to your local machine:

bash git clone https://github.com/yourusername/simple-image-editor.git cd simple-image-editor

Create a virtual environment (optional but recommended):

bash python -m venv venv source venv/bin/activate # On Windows, use venv\Scripts\activate

Install the required dependencies:

bash pip install -r requirements.txt

Usage
To run the app, use the following command:

streamlit run app.py
