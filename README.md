# 🎨 Air Canvas

Air Canvas is a computer vision project that lets you **draw in the air using hand gestures**.  
It uses **MediaPipe Hands** for hand tracking and **OpenCV** for real-time drawing via your webcam.

---

## 🚀 Features
- Real-time hand tracking using MediaPipe
- Draw on screen using finger movements
- Webcam-based interaction
- Simple and interactive UI
- Python-based implementation

---

## 🛠️ Tech Stack
- **Python 3.11**
- **OpenCV**
- **MediaPipe**
- **NumPy**
- **Matplotlib**

---

## 📁 Project Structure
```
air_canvas/
│
├── src/
│ └── main.py
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Anjalipan37/air_canvas.git
cd air_canvas
2️⃣ Create & activate virtual environment
python -m venv .venv
Windows (PowerShell):

.venv\Scripts\Activate.ps1
3️⃣ Install dependencies
pip install -r requirements.txt
4️⃣ Run the project
py -3.11 src/main.py
Make sure your webcam is connected 📷
```

🖐️ How It Works
MediaPipe detects hand landmarks

Finger positions are tracked frame by frame

Movements are mapped to drawing strokes on a virtual canvas

OpenCV renders everything in real time

🐞 Common Issues
ModuleNotFoundError → Make sure .venv is activated

Webcam not opening → Close other apps using the camera

MediaPipe errors → Ensure Python version is 3.11

📌 Future Improvements
Add color selection using gestures

Eraser mode

Save drawings as images

Multi-hand support

🤝 Contributing
Pull requests are welcome!
Feel free to open an issue for suggestions or bugs.

👤 Author
Anjali Pan
GitHub: @Anjalipan37
