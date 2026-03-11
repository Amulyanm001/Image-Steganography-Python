# Image Steganography using Python

This project hides secret messages inside an image using Python and OpenCV.

## Features
- Hide secret text messages inside images
- Password protected message extraction
- Image selection using Tkinter file dialog
- Automatic encrypted image generation

## Technologies Used
- Python
- OpenCV
- NumPy
- Tkinter

## How it Works
The program modifies pixel values of the image to store ASCII values of the secret message. The encrypted image appears visually unchanged but contains hidden data that can be extracted with the correct passcode.

## How to Run

Install dependencies:

pip install opencv-python numpy

Run the program:

python Steganography.py

## Example

Encryption:
1. Select image
2. Enter secret message
3. Enter passcode

Decryption:
1. Select encrypted image
2. Enter passcode
3. Message will be revealed

## Author
Amulya N M
