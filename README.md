🏆 Face & Color Recognition using Huskylens & OpenCV
📌 Overview
This repository contains two implementations of AI-based recognition:

Huskylens with Arduino
Face Recognition – Detects and identifies faces using Huskylens AI camera.
OpenCV with Python
Color Recognition – Detects and labels colors in uploaded images.


------------------------
🚀 Project 1: Face Recognition using Huskylens (Arduino)
📌 Requirements
🛠️ Hardware:
Huskylens AI Camera
Arduino Uno (or compatible board)
Jumper wires (for I2C connection)
💾 Software:
Arduino IDE
Huskylens Library (install via Library Manager)

----------------------
How Face Recognition Works?
Huskylens detects a face and assigns it a unique Face ID.
The Face ID is stored and used for recognition.
When the same face is detected, it retrieves the stored ID.
You can assign custom names to specific Face IDs for easier identification.
🖼️ Huskylens Output
![image](https://github.com/user-attachments/assets/23136424-25ff-44bb-adba-d44bf3b9a1bd)

---------------------
🎯 Project 2: Color Recognition using OpenCV (Python)
📌 Requirements
💻 Software:
Python 3.x
OpenCV
NumPy
Google Colab or Jupyter Notebook (if running online)
🎯 How Color Recognition Works?
Loads an image and converts it to HSV color space.
Predefined color ranges are used to detect specific colors (Red, Green, Blue, Yellow).
The script highlights detected colors and labels them.
Displays the processed image with color names.
🖼️ OpenCV Color Recognition Output

![image](https://github.com/user-attachments/assets/288e0e9b-b940-4233-9f84-f8c3a5213a3f)

🛠️ Troubleshooting
🔹 Huskylens Issues
Ensure Huskylens is properly wired and trained for recognition.
Verify that Huskylens is in the correct Face Recognition Mode.
🔹 OpenCV Color Recognition Issues
Ensure the image is not too dark or blurry.
Adjust the HSV color range to improve detection accuracy.

