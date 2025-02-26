# Image-Based Steganography Tool

## Overview
This Python script allows users to hide a secret message inside an image and retrieve it using a passcode. It employs basic steganography techniques by modifying pixel values to encode the message.

## Features
- Encrypts a text message into an image.
- Requires a passcode for decryption.
- Uses OpenCV for image processing.

## Requirements
Ensure you have the following dependencies installed before running the script:

```bash
pip install opencv-python
```

## Usage

### Encryption
1. Place your image file in the script directory and rename it to `mypic.jpg` or update the code with the correct filename.
2. Run the script:
   ```bash
   python script.py
   ```
3. Enter the secret message when prompted.
4. Set a passcode for encryption.
5. The script will generate and save `encryptedImage.jpg`.

### Decryption
1. Run the script again.
2. Enter the passcode when prompted.
3. If the passcode is correct, the hidden message will be displayed.
4. If incorrect, access is denied.

## Notes
- This method of steganography is simplistic and may not be secure against sophisticated attacks.
- Ensure the image used has enough pixels to accommodate the message.

## Disclaimer
This tool is for educational purposes only. Use it responsibly and ensure compliance with applicable laws and regulations.

