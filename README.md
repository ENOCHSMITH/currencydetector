# currencydetector #indian currency detector #indian currency datasets
INDIAN CURRENCY DETECTOR PROJECT 

Purpose Of This Project:

This project was primarily created to assist vision-impaired individuals in identifying Indian currency notes accurately and independently.
In real-life scenarios, many visually impaired people face difficulties when trying to recognize the value of currency notes — especially newer versions introduced by the Reserve Bank of India (RBI) with varying colors, sizes, and layouts. While tactile features do exist, they are not always sufficient or easy to detect.
This inspired the development of a smart, camera-based web application that can recognize the currency value using image detection and then provide audio feedback or large visual prompts, making it more accessible and reliable for everyone.

Why It’s Important:

Many daily tasks like shopping, travel, banking, and donations involve handling cash.
Misidentification may lead to unintended financial loss or dependency on others.
With this software, vision-impaired users can simply capture or scan a currency note, and the system will speak out or display the note value clearly.

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
