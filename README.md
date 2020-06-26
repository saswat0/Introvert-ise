# Introvertise

### Walkthrough

The [YOLOv5](https://github.com/ultralytics/yolov5 "YOLOv5") model is used to detect people after which, they are classified as "*Risky*" and "*Safe*" based on their distance from one another.

### Dependencies
-   Python3.7+
-   PyTorch >=1.5

### Setup
*   Install requirements
    ```
    $ pip install -U -r requirements.txt
    ```

### Usage

*   Run on a video file
    ```bash
    $ python detect.py --source <path_to_video_file>
    ```
*   Run on webcam
    ```bash
    $ python detect.py --source 0
    ```