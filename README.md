# Smart-Attendance-System
This repository contains a Python project that implements a Smart Attendance System using face recognition technology.
The system provides an efficient and automated way to take attendance in various settings by recognizing and recording the faces of individuals present.

This system captures video from a webcam, identifies individuals based on their facial features, and marks their attendance. Here's a summary of the project:
**Imported Libraries:** The script imports several Python libraries, including OpenCV for computer vision, NumPy for numerical operations, face_recognition for face detection and recognition, os for file operations,
pyttsx3 for text-to-speech, and datetime for handling timestamps.
**Text-to-Speech Initialization:** The code initializes a text-to-speech engine (pyttsx3) for generating voice output.
**Image Resizing Function:** The resize function resizes images to a specified size.
**Student Data Preparation:** The script loads student images from a specified directory, resizes them, converts them to RGB format, and calculates facial encodings for each image.
Student names are extracted from the image file names.
**Attendance Marking Function:** The MarkAttendance function records the attendance of recognized individuals in a CSV file and uses text-to-speech to welcome them to the class or event.
**Encoding Calculation:** The script calculates face encodings for the student images.
**Video Capture:** It captures video frames from the webcam using OpenCV.
**Real-time Face Recognition:** In a loop, it continuously captures frames, resizes them, detects faces in the frames, calculates face encodings for the detected faces, and 
compares these encodings with the encodings of known students. If a match is found, the script marks attendance and displays the name on the video frame.
**Display and Processing:** The script displays the video feed with rectangles around recognized faces and their names and waits for a key press.

This code provides a foundation for creating a smart attendance system using face recognition technology. It can be used for various applications such as tracking attendance in classrooms or at workplace events. 
The system offers real-time recognition and automatic attendance marking while providing a welcoming message to recognized individuals.
