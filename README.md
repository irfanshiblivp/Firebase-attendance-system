# 🎓 Firebase Attendance System – Teacher's Dashboard  

A **web-based attendance management system** that allows teachers to mark student attendance and save it in **Firebase Realtime Database**. Designed for ease of use, it provides a simple and efficient way to record attendance with just a few clicks.  

---

## ✨ Features  
✔️ **User-Friendly Interface** – Simple checkbox-based attendance marking.  
✔️ **Firebase Integration** – Automatically saves attendance records.  
✔️ **Real-Time Storage** – Data is stored securely in Firebase.  
✔️ **Automated Timestamp** – Records the **date** and **time** of attendance.  
✔️ **Customizable Student List** – Easily update names, roll numbers, and classes.  

---

## 🚀 How to Set Up  

### 1️⃣ **Download & Save the File**  
- Save the provided code as an **HTML file** (e.g., `attendance.html`).  
- Open it in any **web browser** (Chrome, Edge, Firefox).  

### 2️⃣ **Configure Firebase**  
- Open the **HTML file** and locate this section:  
  ```js
  const firebaseConfig = {
    apiKey: "YOUR_API_KEY",
    databaseURL: "YOUR_DATABASE_URL",
    appId: "YOUR_APP_ID"
  };
  
