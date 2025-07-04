# currencydetector
indian currency detector through website

Project Overview:
The Currency Detector website is a computer vision-based web application that allows users to upload or capture images of currency notes, and it will identify the denomination and provide information such as currency value, authenticity features, and other details. This is especially useful for educational, assistive, or financial applications.

How the Project Works:
1. User Interface:
Users upload or take a photo of a currency note on the website.
2. Image Processing & Detection:
The uploaded image is sent to a backend model using an API.
The image is analyzed using a trained Machine Learning / Deep Learning model (usually using CNN – Convolutional Neural Networks) to detect and classify the currency denomination.
3. Currency Classification:
Based on image features (design, numbers, symbols), the model classifies the currency (e.g., ₹10, ₹50, ₹100, ₹500, etc.).
Optionally, it can also detect counterfeit notes by checking known features (watermark, security thread, etc.).
4. Result Display:
The denomination and authenticity result is shown on the screen along with additional details like currency facts, security features, or current exchange value (if needed).

Technologies & Languages Used:
Layer	Technologies & Tools
Frontend      	-----HTML, CSS, JavaScript, Bootstrap (for UI)
Backend	        -----Python (Flask or Django)
Image Detection -----	OpenCV, TensorFlow / Keras / PyTorch
API Integration	RESTful API using Flask/Django REST Framework
