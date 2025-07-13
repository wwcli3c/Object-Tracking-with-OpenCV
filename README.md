# Object-Tracking-with-OpenCV


This project is about computer vision technology using to detect number of cars on highway.vision and image processing. It can be used to analyze images and video footage from cameras and other sources, and it has many applications in highway traffic management. Some ways that OpenCV can be used in this field include:

Object detection: OpenCV can be used to detect objects in images or video footage, such as vehicles, pedestrians, and bicycles. This can be used to monitor traffic flow and detect accidents or congestion.


Project Structure

- `main.py`: The main script. It reads video input, performs motion detection, and applies object tracking.
- `tracker.py`: Contains the `EuclideanDistTracker` class, which assigns unique IDs to objects and tracks them based on their positions.
- `highway.MP4`: The video file used for object detection and tracking. This file must be located in the same directory as `main.py`.



Install OpenCV via pip:

```bash
pip install opencv-python
