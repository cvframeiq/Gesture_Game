# 🛩️ Helicopter Finger-Tracking Game

A fun and interactive 2D game that uses real-time hand tracking to control a helicopter using just the tip of your index finger! Navigate through obstacles and score as high as you can. The game gets more challenging as your score increases.

<video src="demo.mp4" controls autoplay loop muted width="500"></video>

---
## 🎮 Features

- 👆 Real-time finger tracking using **Mediapipe**
- 🧠 Motion control using the **index finger tip**
- 🧱 Avoid dynamically placed **obstacles**
- 🚀 Speed increases as your **score increases**
- 🌆 Background changes to building scene as difficulty increases
- 💾 High score is saved in a local `score_` file
- 📷 Built with **OpenCV** and **Python**
---
## 🛠️ Tech Stack

- **Python**
- **OpenCV** – for image processing and camera input
- **Mediapipe** – for real-time hand and finger detection
- **NumPy** – for efficient computation

---

## 🖥️ Installation
1. Clone
    ```shell
    git clone https://github.com/cvframeiq/Gesture_Game.git
    ```
2. Change directory
    ```shell
    cd Gesture_Game
    ```
3. Create virtual environment
   ```shell
    python3 -m venv .venv
    ```
4. Activate the virtual environment
    ```shell
    source .venv/bin/activate
    ```
5. Install requirements
   ```shell
    pip install -r requirements.txt
    ```
6. Run the script
   ```shell
    python3 main.py
    ```
---
## 📁 File Structure

```
..
├── LICENSE
├── README.md
├── Untitled.mp4
├── file_structure.txt
├── main.py
├── requirements.txt
├── score_
└── utils
    ├── __pycache__
    │   └── image_processor.cpython-312.pyc
    ├── background.jpg
    └── image_processor.py

3 directories, 10 files

```
--- 

## 🧠 How it Works
1.	The webcam captures real-time video.
2.	Mediapipe tracks the index finger tip.
3.	The helicopter follows the Y-position of the finger.
4.	The player avoids obstacles that move horizontally across the screen.
5.	As score increases:
   - The speed of obstacles increases.
   - The background changes to add difficulty.

---
## 📄 License

**GNP GPL V3** License. Feel free to use, modify, and distribute this project.

