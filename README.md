# Hand Gestures Recognition with Sound

This Python script uses the Mediapipe library to detect hand gestures using a webcam. It recognizes specific hand gestures and plays corresponding sound effects.

## Requirements

- Python 3.x
- OpenCV (`pip install opencv-python`)
- Mediapipe (`pip install mediapipe`)
- Playsound (`pip install playsound`)

## Usage

1. Make sure you have a webcam connected or replace `cv2.VideoCapture(0)` with the video source you want to use.

2. Run the script.

3. The program will use hand landmarks to recognize gestures and play sound effects accordingly.

## Hand Gestures and Sound Effects

- **Hello Gesture**: Wave with your hand. Plays "hello.mp3".
- **No Gesture**: Move your hand downwards. Plays "Noau.mp3".
- **Extended Gesture**: Extend your fingers. Plays "Extendedau.mp3".
- **Rock Gesture**: Make a rock fist. Plays "Rockau.mp3".
- **Super Gesture**: Raise your hand. Plays "Superau.mp3".

## Customization

Feel free to replace the sound files with your own or modify the gestures based on your preferences.

## Credits

- This script uses the [Mediapipe](https://google.github.io/mediapipe/) library for hand tracking.
- Sound effects are from various sources.



