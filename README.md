Real-Time Car Parking Detection System using OpenCV and Flask

📌 Project Overview

This project is a Real-Time Car Parking Detection System built using OpenCV, cvzone, and Flask. It processes a parking lot video to detect empty and occupied parking slots and updates a real-time web interface with parking status.

📷 Features

🎥 Real-time video processing using OpenCV

🏢 Parking slot detection with occupancy status

🌐 Flask-based web interface to display live parking updates

🎨 Stylish UI with a car image background

🔄 Automatic updates every 2 seconds for real-time monitoring

🖥 Slot-wise view to see individual parking slot statuses

📂 Project Structure

📁 CarParkingSystem
│── 📄 app.py (Main Flask application)
│── 📂 static
│   ├── carImage.jpg (Background image)
│   ├── style.css (Frontend styling)
│── 📂 templates
│   ├── index.html (Main UI page)
│   ├── slots.html (Parking slot view page)
│── 📄 CarParkPos (Saved parking slot positions)
│── 📄 carPark.mp4 (Sample parking lot video)

🛠 Installation

🔹 Prerequisites

Ensure you have Python 3.7+ installed.

🔹 Install Dependencies

pip install flask opencv-python cvzone numpy pickle

🔹 Run the Application

python app.py

🌍 Usage

Open http://127.0.0.1:5000/ in your browser.

The main page displays Total, Empty, and Occupied parking slots.

Click "View Parking Spots" to see individual slot statuses.

The system continuously processes the video to update parking occupancy.

🎯 Future Enhancements

✅ Integration with Live CCTV Feeds

✅ Deployment on Cloud Platforms (AWS, GCP)

✅ Mobile App for remote monitoring
