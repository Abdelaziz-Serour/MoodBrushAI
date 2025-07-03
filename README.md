# MoodBrushAI 🧠🎨

**Real-time emotion-aware drawing system** using YOLOv8 for facial expression detection and MediaPipe for hand gesture control.

## Features
- 😀 Draw with green if you're happy
- 😢 Draw with red if you're sad
- ✋ Use closed hand (fist) to draw with your finger
- Built using: YOLOv8, MediaPipe, OpenCV

## How it Works
1. YOLOv8 detects facial expression (happy/sad)
2. MediaPipe tracks your hand and fingers
3. When hand is closed, the fingertip is used as a drawing brush
4. Color of the brush changes based on your mood

## Demo
![Demo GIF or Video](demo/output_video.mp4)

## Installation

```bash
pip install -r requirements.txt
python src/app.py
 
