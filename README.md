# 👨‍💻 Smart Attendance System

A modern Python-based attendance system that uses real-time face recognition through your webcam to **automatically log Clock In and Clock Out times**. Built with `face_recognition`, `OpenCV`, and enhanced with an intuitive **PyQt5-based GUI**. Optional Firebase integration is available for cloud-based attendance tracking.

---

## 🚀 Project Highlights

- 🧠 Intelligent face recognition using machine learning
- 🖼️ Beautiful desktop GUI with PyQt5
- 🕒 Clock In / Clock Out automation
- 📊 Logs stored in local CSV (`history.csv`)
- ☁️ Optional cloud sync via Firebase
- 🛑 Detects and skips unrecognized faces
- 🔐 Supports login screen and access control

---

## 🛠️ Tech Stack

| Technology        | Usage                               |
|------------------|--------------------------------------|
| **Python**        | Programming Language                 |
| **OpenCV**        | Image/Video processing               |
| **face_recognition** | Face detection & comparison      |
| **PyQt5**         | GUI interface                        |
| **Pandas / CSV**  | Attendance data storage              |
| **Firebase** (optional) | Real-time cloud sync         |
| **Pickle**        | Encode & store known faces locally   |

---

## 📁 Project Structure

| File/Folder         | Description                                      |
|---------------------|--------------------------------------------------|
| `mainwindow.py`     | Main PyQt5 window logic                          |
| `mainwindow.ui`     | GUI layout for main window (Qt Designer)         |
| `out_window.py`     | Clock In/Out result window logic                 |
| `outputwindow.ui`   | GUI for output window (Qt Designer)              |
| `history.csv`       | Attendance log file                              |
| `icon.png`          | App icon                                         |
| `logo.png`          | Logo for GUI                                     |
| `resource.qrc`      | Qt resource linker for icons/images              |
| `resource.py`       | Auto-generated from `.qrc` file                  |

---

## 📸 Sample Attendance Log

Here’s how your `history.csv` will look after usage:

| Name   | Date      | Time     | Status    |
|--------|-----------|----------|-----------|
| Abhay  | 24/06/03  | 19:50:27 | Clock In  |
| Abhay  | 24/06/03  | 20:00:10 | Clock Out |
| Akshat | 24/06/03  | 20:02:20 | Clock In  |
| Akshat | 24/06/03  | 20:05:44 | Clock Out |

---

## 💻 Getting Started

### 🔹 Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/face-attendance-system.git
cd face-attendance-system

🔹 Step 2: Install Required Dependencies
pip install opencv-python face_recognition numpy pandas pyqt5 pyrebase4

🔹 Step 3: (Optional) Firebase Setup
Create a Firebase Realtime Database project

Copy your Firebase credentials into firebaseConfig.py

🔹 Step 4: Encode Known Faces
python encode.py

🔹 Step 5: Run the Application
python mainwindow.py

🔐 Optional Features:-
🧑‍💻 Admin login screen (GUI authentication)

📩 Email alerts for unknown face detection

📈 Real-time dashboard via Firebase

😷 Face mask detection integration

🔊 Voice alerts for Clock In/Out confirmation

🛠️ Future Enhancements :-
🌐 Web dashboard using Flask or Streamlit

📱 Mobile camera integration

📊 Google Sheets sync for attendance logs

🤖 Anti-spoofing & emotion detection

📄 License
This project is licensed under the MIT License.
Feel free to use, modify, and share for academic or professional projects.

👨‍🎓 Author
Abhay Singh
🎓 B.Tech in Computer Science & Engineering – PSIT Kanpur
📧 singhabhay1516@gmail.com
🌐 https://www.linkedin.com/in/abhaysingh0224/ 

⭐ If you found this project helpful, don’t forget to star the repository on GitHub!

