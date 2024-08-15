# Image Cropper App
This is a Streamlit application that allows users to upload an image, crop it according to their desired dimensions, and download the cropped image.

## Features
Image Upload: Upload an image file in JPG, JPEG, or PNG format.

Crop Settings: Use sliders to set the dimensions (left, top, right, bottom) for cropping the image.

Cropped Image Preview: View the cropped image in real-time.

Download Cropped Image: Download the cropped image as a PNG file.

## Installation
To run the application, ensure that you have Python, Streamlit, and Pillow installed on your machine.

Install Python (if not already installed) from the official Python website.

Install the required packages using pip:
```bash
pip install streamlit pillow
```

## Usage
Clone or download the repository containing the img_cropper.py file.

Navigate to the directory containing the img_cropper.py file.

Run the Streamlit app using the following command:

```bash
streamlit run img_cropper.py
```

## Application Layout
Title: The app is titled "Image Cropper".

Image Upload: Upload an image file (JPG, JPEG, PNG) using the "Choose an image file" uploader.

Original Image Display: The uploaded image is displayed with the caption "Original Image".

### Crop Settings:
Left: Slider to adjust the left boundary of the crop area.

Top: Slider to adjust the top boundary of the crop area.

Right: Slider to adjust the right boundary of the crop area.

Bottom: Slider to adjust the bottom boundary of the crop area.

Cropped Image Display: The cropped image is displayed with the caption "Cropped Image".

Download Cropped Image: A download link is provided to download the cropped image as a PNG file.
## Customization
You can modify the initial values, titles, and layout of the app according to your needs by editing the image_cropper_app.py file.

## License
This project is open-source and available under the MIT License.
