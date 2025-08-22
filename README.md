# 🏥 Hospital Management System

**Hospital Management System** is a Java-based desktop application designed to help manage hospital operations such as handling patient data, saving and loading system state, and providing a user-friendly interface for medical staff.  
This project was developed as part of an **Object-Oriented Programming (OOP)** course.

---

## 📌 Features

- 🧾 Add and manage patient information  
- 💾 Save and load data using serialization  
- 🖥️ Simple graphical user interface (GUI)  
- 📂 Load system state from `.ser` file  
- 🧪 Built with clean OOP principles  

---

## 🛠️ Technologies Used

- **Java** (Core + Swing)  
- **Serialization**  
- **Executable JAR** packaging  
- **Eclipse** / **IntelliJ IDEA** compatible  

---

## 📁 Project Structure

```
Hospital-Management-System/
├── hospital_jar.jar            # Ready-to-run JAR file
├── Hospital.ser                # Saved data file (serialization)
├── Hospital.zip                # Full project archive
├── src/                        # Source code (if uploaded)
├── WITHJAR/                    # Folder with project files
└── README.md                   # This file
```

---

## 🚀 How to Run

### Option 1: Run the JAR file (recommended)

Make sure you have Java installed on your computer.

#### 👉 Double-click method:
1. Download `hospital_jar.jar`  
2. Double-click to launch

#### 👉 Terminal method:
```bash
java -jar hospital_jar.jar
```

---

## 🔄 Loading Saved Data

To restore a previous session:
- Ensure `Hospital.ser` is located in the same directory as the JAR file before launching.
- The application will attempt to load data on startup.

---

## 📜 License

This project was developed for educational purposes. You are free to explore and modify it as needed.
