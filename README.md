# HandTrackMouse 🖐️➡️🖱️

Control your computer mouse with your **hand gestures** using **OpenCV**, **MediaPipe**, and **Python**.  
This project turns your webcam into a smart controller where you can move the cursor, left-click, and right-click — all without touching a mouse.  

---

## ✨ Features
- 🎯 **Hand Tracking** in real-time using MediaPipe.  
- 🖱️ **Mouse Control**: Move cursor smoothly across the screen.  
- 👆 **Left Click**: Triggered when thumb and index finger touch.  
- 🤟 **Right Click**: Triggered when thumb and middle finger touch.  
- ⚡ **Smooth Cursor Movement** with configurable sensitivity.  

---

## 🚀 How It Works
- **Index + Thumb** → Left Click.  
- **Middle + Thumb** → Right Click.  
- **Palm movement** → Cursor movement.  
- Uses **linear interpolation** to smooth the cursor motion.  

---

## 🛠️ Installation
Clone the repo and install the required dependencies:

```bash
git clone https://github.com/your-username/HandTrackMouse.git
cd HandTrackMouse
pip install -r requirements.txt
