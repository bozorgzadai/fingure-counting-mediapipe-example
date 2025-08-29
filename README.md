# Finger Counting with Mediapipe

This repository demonstrates real-time hand tracking and finger counting using OpenCV and Mediapipe.

## Project Structure

- [`find_landmark.py`](find_landmark.py): Visualizes hand landmarks using Mediapipe and OpenCV.
- [`handTrackingModule.py`](handTrackingModule.py): Contains the [`handDetector`](handTrackingModule.py) class for hand detection and landmark extraction.
- [`finger_counting.ipynb`](finger_counting.ipynb): Jupyter notebook for real-time finger counting and displaying corresponding images.
- [`fingersImage/`](fingersImage): Contains images (`1.PNG` to `6.PNG`) representing different finger counts.

## Requirements

- Python 3.7+
- OpenCV (`cv2`)
- Mediapipe

Install dependencies:
```sh
pip install opencv-python mediapipe
```

## Usage

### Hand Landmark Visualization

Run:
```sh
python find_landmark.py
```
Press `q` to exit.

### Finger Counting

Open [`finger_counting.ipynb`](finger_counting.ipynb) in Jupyter Notebook and run all cells. The webcam feed will show detected fingers and display the corresponding image.

### Hand Tracking Module

You can use the [`handDetector`](handTrackingModule.py) class in your own scripts for hand detection and landmark extraction.

## Credits

- Hand Tracking Module by Murtaza Hassan ([YouTube](http://www.youtube.com/c/MurtazasWorkshopRoboticsandAI))

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.