
# 🤟 ASL Sign Language Recognition

A real-time American Sign Language (ASL) recognition system that uses hand landmarks and a TensorFlow Lite model to predict letters from webcam input. The system includes a live GUI that builds words and converts them into speech using `pyttsx3`.

---

## 📸 Demo

![Demo](assets/demo.gif) <!-- Add a demo GIF or screenshot here -->

---

## 🛠 Tech Stack

- 🐍 Python
- 🖼 OpenCV & CvZone
- 🤖 MediaPipe
- 🧠 TensorFlow Lite (TFLite)
- 🗣 pyttsx3 (text-to-speech)
- 🖥 Tkinter (GUI)

---

## 🚀 Features

- Real-time hand tracking and gesture recognition
- Predicts ASL letters using a TFLite model
- Builds words and converts to speech
- GUI to display letter, word, and clear/reset buttons
- Lightweight, fast, and efficient

---

## 📂 Folder Structure

```
asl-sign-language-recognition/
├── model/
│   └── asl_model.tflite
├── src/
│   ├── main.py
│   ├── gui.py
│   └── utils.py
├── assets/
│   └── demo.gif
├── requirements.txt
└── README.md
```

---

## ⚙️ How to Run

### 📦 Install dependencies
```bash
pip install -r requirements.txt
```

### ▶️ Run the app
```bash
python src/main.py
```

> Make sure your webcam is connected and functional.

---

## 🎯 Future Improvements

- Expand to full-word and sentence recognition
- Add support for custom gestures
- Deploy as a web or mobile app

---

## 🧠 About the Creator

Built with ❤️ by [Naitik Kharat](https://www.linkedin.com/in/naitikkharat/)  
Check out my portfolio: [naitikkharat.github.io/portfolio_Naitik](https://naitikkharat.github.io/portfolio_Naitik/)

---

## 🌟 Don't forget to leave a ⭐ if this project helped you!
