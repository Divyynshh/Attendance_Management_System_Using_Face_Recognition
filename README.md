# Attendance Management System using Face Recognition 📸✅

---

## Project Description
This project, **Attendance Management System using Face Recognition**, leverages advanced facial recognition technology to simplify attendance tracking. It captures facial data in real time, compares it with the database, and marks attendance automatically. Perfect for educational institutions, corporate offices, or any organization aiming to reduce manual processes and boost efficiency.

### Key Features:
- 🏢 **Real-time Face Recognition**: Seamlessly track attendance using live face recognition.
- 📂 **Secure Database Management**: Store attendance data securely in a database.
- 🔒 **Robust Error Handling**: Handles issues like missing modules, unrecognized faces, or database connectivity.
- 🎥 **Image Storage**: Automatically saves captured images for future reference.

---

## LinkedIn Page 🌐
Connect with me on LinkedIn to explore more projects, ideas, and collaborations: [Divyansh Bansal](www.linkedin.com/in/divyansh-bansal-7a00b42aa).

---

## Screenshots 📸
### Home Screen:
![Home Screen](![image](https://github.com/user-attachments/assets/e8eb4579-2018-45c8-a228-3e3c9b7f2ad4)
)

### Attendance Log:
![Attendance Log](![image](https://github.com/user-attachments/assets/6c4d67e3-d08c-4993-8759-de1582964513)
)

---

## Table of Contents
1. [Setup and Installation](#setup-and-installation)
2. [Features](#key-features)
3. [How It Works](#how-it-works)
4. [Error Handling](#error-handling)
5. [Contributions](#modifications-and-contributions)
6. [Acknowledgments](#acknowledgments)

---

## Setup and Installation ⚙️
### Step 1: Clone the Repository
1. Open your terminal or command prompt.
2. Navigate to your desired directory:
   ```bash
   cd /path/to/your/folder
   ```
3. Clone the repository:
   ```bash
   git clone https://github.com/Vicky-codes17/Attendance_Management_System_Using_Face_Recognition.git
   ```

### Step 2: Install Dependencies
1. Navigate into the project directory:
   ```bash
   cd Attendance_Management_System_Using_Face_Recognition
   ```
2. Install all required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Step 3: Prepare Folders
Ensure the following folders exist:
- **SelfieImages**: To save captured images.
- **TrainingImage**: To store training images for recognition.

### Step 4: Run the Application
Run the main script:
```bash
python main.py
```
Follow the instructions in the interface to start using the system.

---

## How It Works 🔄
1. **Training Images**:
   - Upload training images into the **TrainingImage** folder.
   - The system processes these images to create facial embeddings.

2. **Capture Images**:
   - When a user approaches the camera, the system captures their image in real-time.

3. **Facial Recognition**:
   - The system compares the captured image against the training dataset.

4. **Mark Attendance**:
   - If a match is found, the user’s attendance is marked in the database along with the timestamp.

5. **Attendance Log**:
   - Administrators can view, export, or analyze attendance data.

---

## Error Handling ⚠️
- **Database Connection**:
  Alerts if the database connection fails and provides troubleshooting steps.
- **Camera Access Issues**:
  Notifies the user if the camera is inaccessible or being used by another application.
- **Unrecognized Faces**:
  Logs attendance for manual review if a face is not recognized.
- **Missing Modules**:
  Checks and installs required libraries automatically if missing.

---

## Technologies Used 🤖
1. **Programming Language**: Python
2. **Libraries**:
   - `pymysql`: For database connectivity.
   - `opencv-python`: For face recognition and camera access.
   - `numpy`: For mathematical operations.
   - `face-recognition`: For facial recognition.
   - `pandas`: For data manipulation and storage.
   - `datetime`: For timestamps.
3. **Database**: MySQL
4. **GUI Framework**: Tkinter

---

## Future Enhancements 🚀
- **Mobile App Integration**: Develop a mobile app version for remote attendance marking.
- **Cloud Storage**: Store data on cloud platforms for better accessibility.
- **Multi-Camera Support**: Enable support for multiple cameras simultaneously.
- **Detailed Analytics**: Generate detailed attendance reports with visual insights.

---

## Contributions 🎩
We welcome contributions! Follow these steps to contribute:
1. **Fork the Repository**: Click the "Fork" button on GitHub.
2. **Clone Your Fork**:
   ```bash
   git clone https://github.com/your-username/Attendance_Management_System_Using_Face_Recognition.git
   ```
3. **Create a Branch**:
   ```bash
   git checkout -b feature/your-feature-name
   ```
4. **Make Changes and Commit**:
   ```bash
   git add .
   git commit -m "Add your message here"
   ```
5. **Push Changes**:
   ```bash
   git push origin feature/your-feature-name
   ```
6. **Create a Pull Request** on the original repository.

---

## Acknowledgments 💖
A heartfelt thanks to my mentor, **Mr. Aditya Prashant Ardak**, for guiding me through this project. Special thanks to my teammates for their support and collaboration.

---

## Contact 📞
Feel free to connect with me for project discussions, collaborations, or feedback:
- **Email**: [Divyansh Bansal](bansaldivyansh001@gmail.com)
- **LinkedIn**: [Divyansh Bansal](www.linkedin.com/in/divyansh-bansal-7a00b42aa)
- **GitHub**: [Divyynshh](https://github.com/Divyynshh)

---

Let’s make this project even better together! ✨

