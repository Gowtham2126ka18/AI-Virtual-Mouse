# 🖐️ AI-Based Virtual Mouse Using Hand Gestures

A real-time AI-powered virtual mouse system that allows users to control mouse movement and actions using hand gestures captured through a webcam. This project uses computer vision and hand landmark detection to enable touchless human–computer interaction.

---

## 📌 Project Overview

This project replaces the traditional physical mouse with a gesture-based control system. By detecting hand landmarks and recognizing finger gestures, the system performs mouse operations such as moving the cursor, left click, right click, and drag.

It is designed as a beginner-to-intermediate level AI project and is suitable for learning:
- Computer Vision
- Gesture Recognition
- Human–Computer Interaction (HCI)

---

## 🚀 Features

- Real-time hand detection using webcam  
- Smooth and stable cursor movement  
- Gesture-based left click and right click  
- Drag and hold functionality  
- No external hardware required  
- Touchless interaction  

---

## 🛠️ Tech Stack

- **Language:** Python  
- **Libraries:**  
  - OpenCV  
  - MediaPipe  
  - NumPy  
  - AutoPy  

---

## 📂 Project Structure

```
AI-Virtual-Mouse/
│
├── main.py
├── HandDetectionModule.py
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md
```

---

## 🧠 How It Works

1. Webcam captures live video frames  
2. MediaPipe detects a single hand and extracts 21 landmarks  
3. Open fingers are identified based on landmark positions  
4. Specific gestures are mapped to mouse actions  
5. AutoPy executes mouse movement and click operations  

---

## ✋ Gesture Mapping

| Gesture | Mouse Action |
|------|-------------|
| Index finger open | Cursor movement |
| Index + Middle fingers touching | Left click |
| Thumb + Index fingers touching | Right click |
| Index + Middle + Ring fingers | Drag / Hold |
| No valid gesture | No action |

---

## ⚙️ Installation

### Prerequisites
- Python 3.8 or higher  
- Working webcam  
- Windows / macOS / Linux  

### Install Dependencies
```
pip install -r requirements.txt
```

---

## ▶️ How to Run

```
python main.py
```

### Best Practices
- Use good lighting conditions  
- Keep only one hand visible  
- Maintain a steady hand position  

---

## 🖥️ Output

- Live webcam feed with hand landmarks  
- Smooth mouse cursor movement  
- Gesture-controlled click and drag actions  

---

## ✅ Advantages

- Touchless control  
- Low-cost solution  
- Easy to understand and modify  
- Useful for accessibility and smart systems  

---

## ⚠️ Limitations

- Requires proper lighting  
- Supports only one hand  
- Webcam-dependent performance  

---

## 🔮 Future Enhancements

- Multi-hand support  
- Gesture-based scrolling  
- Custom gesture configuration  
- Voice + gesture hybrid system  
- Mobile camera integration  

---

## 📚 Use Cases

- Assistive technology  
- Touchless computer interaction  
- Smart environments  
- AI and computer vision learning projects  

---

## 👨‍💻 Author

**Gowtham Chakkarawarthi B**  
AI / ML Enthusiast  
Coimbatore, India  

---

## 📄 License

This project is licensed under the **MIT License**.
