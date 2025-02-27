# Secure Data Hiding in Image Using Steganography

## 📌 Project Overview
This project implements **image steganography** using Python and OpenCV, enabling users to securely hide and retrieve secret messages within images. The technique ensures that the image remains visually unchanged while embedding the hidden data.

## 🚀 Features
- **Steganography-Based Data Hiding** – Conceal messages within image pixels.
- **Secure Passcode Protection** – Only users with the correct passcode can retrieve the hidden message.
- **Lossless Image Modification** – The original image quality is preserved.
- **Lightweight & Efficient** – Runs smoothly on low-resource machines.

## 🛠️ Technologies Used
- **Python** – Core programming language.
- **OpenCV** – Image processing and pixel manipulation.
- **OS Module** – File handling operations.
- **String Module** – ASCII encoding of messages.


## 📖 How to Use
1. **Encryption Process**  
   - Run `steganography.ipynb`  
   - Enter the secret message  
   - Provide a passcode for security  
   - The encrypted image will be saved as `encryptedImage.jpg`  

2. **Decryption Process**  
   - Open the program and enter the correct passcode  
   - The hidden message will be revealed if authentication is successful  
