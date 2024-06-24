# Cigarette-Detection-System

**Overview**
This project aims to detect cigarettes in images and video feeds using the YOLOv8 model. The system is built using Flask for the web application, OpenCV for image and video processing, and Ultralytics' YOLO for object detection. It can be used to monitor public or prohibited areas to detect the presence of cigarettes.

**Features**
•	Real-time detection: Detect cigarettes in real-time using webcam or video files.
•	Image detection: Upload images to detect cigarettes.
•	Web interface: Simple and user-friendly web interface to interact with the system.
•	High accuracy: Achieved 94.4% accuracy with the YOLOv8 model.

**Prerequisites**
•	Python 3.7+
•	Flask
•	OpenCV
•	Ultralytics YOLO

**Installation**
1.	Clone the repository:
git clone https://github.com/your-username/Cigarette-Detection-System.git
cd Cigarette-Detection-System
2.	Install the required packages:
pip install -r requirements.txt
3.	Place your YOLOv8 model (best.pt) in the static directory.

**Usage**
Running the Application
1.	Start the Flask server:
python app.py
2.	Open your web browser and navigate to http://127.0.0.1:5000.

**Using the Web Interface**
Image Detection
1.	On the landing page, click on the "Upload Image" button.
2.	Select an image file (jpg, jpeg, png) and upload it.
3.	The system will process the image and display the detection results.

**Project Structure**
Cigarette-Detection-System/
│
├── static/
│   ├── best.pt                 # YOLOv8 model
│   ├── uploads/                # Directory to save uploaded files
│   └── index.js                # JavaScript for front-end interactions
│
├── templates/
│   └── index.html              # HTML file for the web interface
│
├── app.py                      # Flask application
├── requirements.txt            # Required Python packages
└── README.md                   # Project readme file

Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.
License
This project is licensed under the MIT License - see the LICENSE file for details.
Acknowledgments
•	The YOLOv8 model was provided by Ultralytics.
•	The dataset used for training the model was sourced from Roboflow.

