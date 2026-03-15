🧠 NeuroCursor
Eye Controlled Cursor using Python

NeuroCursor is an AI-based eye tracking system that allows users to control their computer cursor using eye movements and blink gestures.
It uses computer vision and facial landmark detection to track the user's eyes in real-time through a webcam.
The system converts eye movement into mouse movement, making the computer accessible without physical mouse interaction.
This project was developed as part of a hackathon innovation focusing on human-computer interaction and accessibility technology.

🚀 Features
Eye Controlled Cursor
The cursor moves based on real-time eye movement detection captured from the webcam.

Blink Gesture Controls.

Gesture	            Action
Double Blink	      Left Click
Triple Blink	      Double Click
Look Down	          Scroll Down
Look Up	            Scroll Up

🖥 Real-Time Computer Vision
Uses facial landmarks detection to accurately track eye positions.
Fast & Lightweight
Runs smoothly using Python libraries without requiring heavy AI models.
Accessibility
Helps users who have difficulty using traditional mouse input devices.

Technologies Used
Python
Computer Vision
Facial Landmark Detection
Webcam Input Processing

📦 Libraries Used
Install the following Python libraries before running the project:
opencv-python
mediapipe
pyautogui
numpy
time

You can install them using:
"pip install opencv-python mediapipe pyautogui numpy"

Note:
time is a built-in Python module and does not require installation.

📂 Project Structure
NeuroCursor/
│
├── main.py          # Main program file
├── README.md        # Project documentation

▶️ How to Run the Project
Follow these steps to run the NeuroCursor system.
1️⃣ Clone the Repository
git clone https://github.com/your-username/neurocursor.git
2️⃣ Navigate to the Project Folder
cd neurocursor
3️⃣ Install Required Libraries
pip install opencv-python mediapipe pyautogui numpy
4️⃣ Run the Program
python main.py
🎯 How It Works

The webcam captures the user's face.
MediaPipe Face Mesh detects facial landmarks.
Eye landmarks are extracted.
Eye movement is analyzed to determine cursor direction.
Blink patterns trigger different mouse actions.
Cursor movement and clicks are performed using PyAutoGUI.

📸 System Requirements
Python 3.8+
Webcam
Windows / Mac / Linux
Minimum 4GB RAM

💡 Future Improvements
Right click gesture
Cursor speed calibration
GUI interface
Better blink detection accuracy
Head movement support

👨‍💻 Authors
Developed by:

Team Codzen
Leaded by Farhaad Ahmad

📜 License
This project is open-source and available under the MIT License.
