# Learning-Project
Hand Gesture Control for YouTube

Hands-Free Video Playback Control Using Computer Vision

This project introduces an innovative, vision-based system that allows users to control YouTube videos using hand gestures. By combining hand tracking, gesture recognition, and web automation, the system enables intuitive actions such as play, pause, volume control, and more – all without touching the keyboard or mouse.

📌 Features

✋ Real-time hand tracking using MediaPipe

🤖 Gesture recognition with customizable gesture mappings

▶️ YouTube video control using PyAutoGUI / JavaScript injection

🔊 Volume and playback control (play, pause, next, previous, volume up/down)

⚡ Low-latency, real-time processing

📺 Works with any YouTube video in any browser

💻 Cross-platform (Windows / macOS / Linux)

🧰 Tech Stack
Component	Technology
Hand Tracking	MediaPipe Hands
Gesture Recognition	Python + Custom Rule-Based Logic
Web Control	PyAutoGUI / Selenium / JavaScript
Computer Vision	OpenCV
Programming Language	Python 3.x
📸 How It Works

The webcam captures real-time video frames.

The system processes each frame using MediaPipe to detect hands and landmarks.

Custom logic identifies specific gestures (e.g., open palm, closed fist, swipe).

Recognized gestures trigger actions on the YouTube player (Pause, Play, Volume, etc.).

🖼️ Gesture Mapping (Example)
Gesture	Action
✋ Open Palm	Pause / Play
👊 Fist	Mute / Unmute
👉 Index Finger Up	Increase Volume
✌️ Two Fingers	Decrease Volume
👉 Swipe Right	Next Video
👉 Swipe Left	Previous Video

You can modify gesture mappings in gesture_config.py.
