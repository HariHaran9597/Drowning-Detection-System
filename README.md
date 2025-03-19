# AI Lifeguard: Drowning Detection System

## Overview
The **AI Lifeguard** is a real-time drowning detection system that uses computer vision and deep learning to monitor swimming pools and alert lifeguards in case of emergencies. The system is built using **YOLOv8** for object detection and **MediaPipe Pose** for pose estimation, ensuring high accuracy and fast response times.

## Features
- **Real-Time Drowning Detection**: Detects drowning incidents using pose estimation and object detection.
- **Alert System**: Sends real-time alerts via Telegram or email when drowning is detected.
- **Web Interface**: A Flask-based web app for uploading images/videos and viewing results.
- **Multi-Camera Support**: Can monitor multiple pools or angles simultaneously.

## Tech Stack
- **Deep Learning**: YOLOv8, MediaPipe Pose
- **Backend**: Flask (Python)
- **Frontend**: HTML, CSS, JavaScript
- **Deployment**: Google Colab (for testing), Heroku/Vercel (for production)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ai-lifeguard.git
   cd ai-lifeguard
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Flask app:
   ```bash
   python app.py
   ```

## Usage
1. Open the web interface at [http://localhost:5000](http://localhost:5000).
2. Upload an image or video of a swimming pool.
3. The system will process the file, detect drowning incidents, and display the results.
4. If drowning is detected, an alert will be sent via Telegram or email.

## Results
- **mAP50**: 0.847  
- **Precision**: 0.826  
- **Recall**: 0.799  

## Future Work
- Add support for live video streaming.
- Integrate with IoT devices (e.g., sirens, lights).
- Improve model accuracy with more data and advanced architectures.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
