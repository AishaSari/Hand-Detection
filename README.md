# Hand Detection  

A simple hand detection program using OpenCV and MediaPipe. This project tracks hand movements in real-time through a webcam and identifies key hand landmarks.  

## Features  
- Real-time hand tracking using MediaPipe Hands  
- Draws hand landmarks and connections on video feed  
- Detects multiple hands simultaneously  
- Efficient and lightweight, running on CPU  

## Requirements  
Ensure you have the following dependencies installed:  
```bash
pip install opencv-python mediapipe
```

## Usage  
Run the script to start hand detection:  
```bash
python hand_detection.py
```
Make sure your webcam is connected and accessible. The program will display the video feed with detected hand landmarks.  

## How It Works  
- Uses **MediaPipe Hands** for landmark detection  
- Captures video from webcam using **OpenCV**  
- Draws detected hand landmarks with unique identifiers  
- Updates in real-time for smooth tracking  

## Notes  
- Works best in well-lit environments  
- Performance may vary based on CPU speed and camera quality  
