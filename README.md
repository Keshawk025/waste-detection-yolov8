♻️ Waste Detection & Classification using YOLOv8
📌 Overview

This project is an AI-powered waste detection system built using YOLOv8 to identify and classify different types of waste from images or live camera input. The goal is to automate waste segregation and improve recycling efficiency by using computer vision instead of manual sorting.

Unlike basic image classification models that only tell what type of waste is in a picture, this system performs real-time object detection. That means it can locate multiple waste items in a single image or video frame and classify each one individually.

🔥 Why this project is different

Most waste-classification projects only take a single image and output one label. That is useless in real-world environments where multiple objects appear at once. This project uses YOLOv8, which can:

Detect multiple waste items in a single frame

Draw bounding boxes around each object

Classify them in real time

Work on webcam feeds or uploaded images

This makes the system suitable for smart bins, recycling centers, and automated waste management systems.

🧠 Technologies Used

Python

YOLOv8 (Ultralytics)

OpenCV

NumPy

Matplotlib (for visualization)

🚀 Features

Real-time waste detection

Waste classification (biodegradable / non-biodegradable or custom classes)

Bounding box visualization

Supports both image upload and live camera

Easily extendable to web or mobile apps

🏗️ How it works

Input image or camera feed is captured

YOLOv8 model processes the frame

Waste objects are detected and classified

Results are displayed with bounding boxes and labels

🎯 Use Cases

Smart dustbins

Recycling plants

City waste monitoring

Environmental AI systems

🛠️ Future Improvements

Integrate with a web dashboard

Add waste statistics and analytics

Deploy on edge devices (Raspberry Pi, Jetson Nano)
