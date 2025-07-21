# 🧠 AI-Based Virtual Keyboard

Welcome to the future of typing! This project presents an AI-powered virtual keyboard that uses **hand tracking via webcam**. Users can type by simply touching two fingers together, eliminating the need for physical input devices.

---

## 🔗 Live Demo

Check out the project in action on GitHub Pages:  
[🔗 View Live](#) *(replace with actual link once deployed)*

---

## 🖼️ Preview


### 👋 Hand Detection  
<img width="782" height="591" alt="image (2)" src="https://github.com/user-attachments/assets/af3a4c77-ae77-47aa-9fcc-1054ba0ace98" />


### 💡 Virtual Typing Output  
![Typing Output](./path-to-image/typing-output.png)<img width="1572" height="855" alt="image (3)" src="https://github.com/user-attachments/assets/2f02a726-ed54-4926-b700-0e697dcd06d1" />


---


  
### 2️⃣ **Logic Layer (Application Layer)**
- Built using: Python + MediaPipe + OpenCV
- Responsibilities:
  - Webcam access and video processing
  - Hand landmark detection
  - Finger-touch gesture detection
  - Key detection logic

### 3️⃣ **Data Layer**
- Data involved:
  - Typed characters buffer
  - Login credentials (stored securely)
  - Typed logs (optional)
- Can be extended to:
  - Firebase / MongoDB for user data
  - Logs for analysis

---


## 🚀 How It Works

1. Webcam activates and captures live hand input.
2. MediaPipe detects 21 hand landmarks.
3. Touch detection is calculated using landmark distances.
4. If two fingertips (e.g., index + thumb) touch inside a keyboard area, the mapped character is added to the output.


📌 Future Improvements
Multilingual virtual keyboard (Hindi, Tamil, etc.)

Predictive text using NLP

Voice-to-text integration

Real-time word suggestion using AI
