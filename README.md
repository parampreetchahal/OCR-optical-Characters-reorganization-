
# Simple OCR (Optical Character Recognition) Project

This project is a simple Optical Character Recognition (OCR) tool developed in Python. It uses various image processing techniques and the Tesseract OCR engine to extract text from images.

## Features

- **Image Preprocessing**: The project includes functions for preprocessing images, such as converting to grayscale, inverting colors, and removing noise.
- **Text Deskewing**: It automatically detects and corrects skew in the input image to improve OCR accuracy.
- **OCR Using Tesseract**: The Tesseract OCR engine is used to recognize text from the preprocessed images.
- **Support for Different Image Formats**: The project supports various image formats such as PNG, JPEG, and WEBP.

## Libraries Used

- **OpenCV**: OpenCV (Open Source Computer Vision Library) is used for image processing tasks such as grayscale conversion, noise removal, and deskewing.
- **Matplotlib**: Matplotlib is used for displaying images during the development process.
- **NumPy**: NumPy is used for numerical operations and array manipulation.
- **Pytesseract**: Pytesseract is a Python wrapper for Google's Tesseract-OCR Engine. It is used for text recognition from images.
- **PIL (Python Imaging Library)**: PIL is used for opening, manipulating, and saving many different image file formats.

## Usage

1. Install the required dependencies using `pip install -r requirements.txt`.
2. Run the `ocr.py` script, providing the path to the input image as an argument.
   ```
   python ocr.py input_image.png
   ```

## Example

Here's an example of how to use the project:

```python
python ocr.py C:\\Users\\XYZ\\Downloads\\input_image.png
```

This will preprocess the image, perform OCR using Tesseract, and display the extracted text.

---
