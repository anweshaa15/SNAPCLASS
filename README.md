 📸 SnapClass

An AI-powered Smart Attendance Management System built with Python and Streamlit.

SnapClass is an intelligent attendance management system that automates attendance using Face Recognition and AI-powered identification. It provides separate interfaces for teachers and students, allowing seamless classroom management, student enrollment, and attendance tracking through an interactive web application.

---

 ✨ Features

- 👤 AI-powered face recognition
- 👨‍🏫 Separate Teacher and Student dashboards
- 📝 Automatic attendance management
- 📱 QR code-based classroom joining
- 🔒 Secure user authentication
- ☁️ Cloud database integration with Supabase
- 🌐 Interactive web interface built with Streamlit

---

🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| 🐍 Python | Core programming language |
| 🌐 Streamlit | Interactive web application |
| 😊 dlib & face_recognition_models | Face recognition using pre-trained models |
| 📊 Scikit-learn | Face embedding comparison and machine learning utilities |
| 🔢 NumPy | Numerical computations |
| 🐼 Pandas | Attendance data management |
| ☁️ Supabase | Backend database and authentication |
| 🔒 bcrypt | Password hashing and secure authentication |
| 🔳 Segno | QR code generation |
| 🖼️ Pillow | Image processing |
| 🎤 Librosa | Audio processing |
| 🗣️ Resemblyzer | Speaker embedding generation |

---

📂 Project Structure

```text
SnapClass/
├── src/
│   ├── components/
│   ├── pipelines/
│   ├── screens/
│   └── ui/
├── app.py
├── requirements.txt
└── README.md
```

---

⚙️ How It Works

1️⃣ Users log in as a **Teacher** or **Student**.

2️⃣ Teachers create and manage classrooms.

3️⃣ Students join classrooms using a **QR code** or join code.

4️⃣ The system identifies registered users using **AI-powered face recognition**.

5️⃣ Attendance is automatically recorded and securely stored in **Supabase**.

---

⭐ **If you found this project useful, consider giving it a star on GitHub!**
