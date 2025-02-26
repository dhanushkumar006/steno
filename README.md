Image-Based Steganography Tool

Overview

This Python script allows users to hide a secret message inside an image and retrieve it using a passcode. It employs basic steganography techniques by modifying pixel values to encode the message.

Features

Encrypts a text message into an image.

Requires a passcode for decryption.

Uses OpenCV for image processing.

Requirements

Ensure you have the following dependencies installed before running the script:

pip install opencv-python

Usage

Encryption

Place your image file in the script directory and rename it to mypic.jpg or update the code with the correct filename.

Run the script:

python script.py

Enter the secret message when prompted.

Set a passcode for encryption.

The script will generate and save encryptedImage.jpg.

Decryption

Run the script again.

Enter the passcode when prompted.

If the passcode is correct, the hidden message will be displayed.

If incorrect, access is denied.

Notes

This method of steganography is simplistic and may not be secure against sophisticated attacks.

Ensure the image used has enough pixels to accommodate the message.

Disclaimer

This tool is for educational purposes only. Use it responsibly and ensure compliance with applicable laws and regulations.

