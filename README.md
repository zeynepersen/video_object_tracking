# Object Tracking and Counting from Videos

This project implements object tracking and counting using the YOLOv8 model. The object tracking part uses the `ultralytics` YOLO library to track objects across frames, while the object counting part counts the number of objects passing through a defined region in the video.

## Vehicle Model Detection and Tracking
In this video, vehicles on a road (cars, trucks, etc.) are detected and tracked. Using the YOLOv8 model, each vehicle is accurately classified by its type (car, truck, etc.) and tracked with a unique ID. Throughout the video, the vehicles' movements are monitored, and their positions on the road are visualized.
<p align="center">
  <img src="https://github.com/user-attachments/assets/221b3ebc-8ba8-48d9-a008-c3fc054b274b" width="500" />
</p>


## Human Counting and Area Tracking
the number of people entering and exiting a predefined area is counted. As individuals cross the designated region, their entries and exits are tracked and updated in real time. The video visualizes the count of people passing through this area, making it suitable for security surveillance, crowd control, or customer interaction analysis. The counting process is continuously updated as people move in and out of the monitored zone.

<p align="center">
  <img src="https://github.com/user-attachments/assets/25410ce1-d48b-4581-9761-05c559f4babf" width="500" />
</p>

## Requirements

Before running the project, make sure you have the following dependencies installed:

- Python 3.x
- OpenCV (`cv2`)
- Ultralytics YOLOv8
- NumPy
- Google Colab (for file handling and downloading)

You can install the necessary dependencies via pip:

```bash
pip install opencv-python-headless ultralytics numpy
