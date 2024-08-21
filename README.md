# Criminal Activity Detection System

## Team Members

- [Mayur Dehade](https://github.com/mayurdehade)
- [Anjali Barde](https://github.com/Anjubarde)
- [Dipak Bhide](https://github.com/dipaksb19)
- [Milind Ghegadmal](https://github.com/milindg123)

## Project Overview

The Criminal Activity Detection System is our final year engineering project aimed at enhancing security by detecting criminal activities and weapons in real-time. The system uses deep learning algorithms to analyze live video feeds or uploaded videos, identifying suspicious activities or weapons and notifying the appropriate authorities.

## Project Features

- **Real-Time Activity Detection**: Uses Convolutional Neural Networks (CNN) to detect criminal activities as they happen.
- **Weapon Detection**: YOLO v7 algorithm identifies weapons in real-time, providing critical information to prevent potential threats.
- **User Authentication**: A secure login system that stores user credentials in an SQLite3 database.
- **Live Camera Feed**: Allows users to monitor live video feeds for real-time detection.
- **Video Upload**: Users can upload pre-recorded videos for analysis.
- **Alert System**: Sends text messages to designated individuals when suspicious activities or weapons are detected.

## Project Modules

1. **User Authentication Module**:

   - Manages user registration and login.
   - Stores user credentials securely in the SQLite3 database.

2. **Live Camera Module**:

   - Activates the live camera feed for real-time activity and weapon detection.
   - Displays results of detection on the user interface.

3. **Video Upload Module**:

   - Allows users to upload pre-recorded videos.
   - Processes the video to detect any criminal activities or weapons.

4. **Detection and Alert Module**:

   - Runs the trained CNN and YOLO v7 models to detect criminal activities and weapons.
   - Sends a text message alert to the respective person upon detection.

5. **Notification Module**:
   - Integrates with a messaging service like Twilio to send real-time alerts.
   - Provides detailed information about the detected activity or weapon in the alert message.

## How It Works

1. **User Login**: The user logs into the system using their credentials.
2. **Choose an Option**:
   - **Start Live Camera**: Activates the camera and starts real-time detection of activities and weapons.
   - **Upload Video**: Allows the user to upload an existing video for analysis.
3. **Detection Process**:
   - The CNN model detects criminal activities.
   - YOLO v7 detects the presence of weapons.
4. **Notification**: Upon detection, the system sends a text message to the designated person, providing details about the detected activity or weapon.

## Project Specifications

- **Programming Language**: Python
- **Framework**: Django
- **Database**: SQLite3 (used for storing user login information)
- **Deep Learning Algorithms**:
  - **CNN (Convolutional Neural Network)**: Detects criminal activities in real-time.
  - **YOLO v7 (You Only Look Once, Version 7)**: Detects weapons in real-time.
- **Training Data**: The models are trained on thousands of images to achieve high accuracy.

## Tech Stack

- **Frontend**: Django
- **Backend**: Python
- **Database**: SQLite3
- **Deep Learning**: TensorFlow, Keras (for CNN and YOLO v7)
- **Communication**: Twilio for sending text messages

  ## Installation and Setup

1. Clone the repository from GitHub:

   `git clone https://github.com/mayurdehade/Criminal-Activity-Detection.git`

2. Navigate to the project directory:

   `cd Criminal-Activity-Detection`

3. Install the required dependencies:

   `pip install -r requirements.txt`

4. Run the Django server:

   `python manage.py runserver`

5. Access the application in your web browser at http://localhost:8000.

## Usage

- Log in to the system using your credentials.
- Choose to either start the live camera or upload a video for analysis.
- View real-time detection results or analysis of the uploaded video.
- Receive text alerts if any criminal activity or weapons are detected.

<!-- ## Contact
If you have any questions or need assistance, feel free to contact me at dehademayur9@gmail.com.

## Contributions
Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.
-->
