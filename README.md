# 🧠 AI-Based Virtual Keyboard (3-Tier Architecture)

Welcome to the future of typing! This project presents an AI-powered virtual keyboard that uses **hand tracking via webcam**. Users can type by simply touching two fingers together, eliminating the need for physical input devices.

---

## 🔗 Live Demo

Check out the project in action on GitHub Pages:  
[🔗 View Live](#) *(replace with actual link once deployed)*

---

## 🖼️ Preview

### 🧩 Home Page  
<img width="1863" height="905" alt="8de44992-21cb-46b7-aa82-96e03663ee1a" src="https://github.com/user-attachments/assets/680d41af-d986-4a47-99de-131bb36d2d0f" />


### 🔐 Login Interface  
<img width="1887" height="917" alt="a6cab665-80ee-44af-be9d-573549e32356" src="https://github.com/user-attachments/assets/38f77a2c-191d-4309-afc1-fc4c4f9a1cbc" />


### 👋 Hand Detection  
<img width="782" height="591" alt="image (2)" src="https://github.com/user-attachments/assets/af3a4c77-ae77-47aa-9fcc-1054ba0ace98" />


### 💡 Virtual Typing Output  
![Typing Output](./path-to-image/typing-output.png)<img width="1572" height="855" alt="image (3)" src="https://github.com/user-attachments/assets/2f02a726-ed54-4926-b700-0e697dcd06d1" />


---

## 🏗️ 3-Tier Architecture

This project follows the **3-tier architecture** approach for clean scalability and separation of concerns:

### 1️⃣ **Presentation Layer (Frontend)**
- Built with: HTML, CSS, JavaScript
- Features:
  - Real-time webcam stream
  - On-screen virtual keyboard
  - Hand detection UI overlays
  - User authentication (login/register)
  
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

## 🛠️ Technologies Used

| Category       | Stack                    |
|----------------|--------------------------|
| Frontend       | HTML, CSS, JavaScript    |
| AI/Logic Layer | Python, MediaPipe, OpenCV|
| UI/Design      | Figma (optional), Canva  |
| Hosting        | GitHub Pages / Streamlit |

---

## 🚀 How It Works

1. Webcam activates and captures live hand input.
2. MediaPipe detects 21 hand landmarks.
3. Touch detection is calculated using landmark distances.
4. If two fingertips (e.g., index + thumb) touch inside a keyboard area, the mapped character is added to the output.

---

## 📥 Installation
