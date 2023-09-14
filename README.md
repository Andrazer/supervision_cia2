## 👋 hello

This script performs traffic flow analysis using YOLOv8, an object-detection method and ByteTrack, a simple yet effective online multi-object tracking method. It uses the supervision package for multiple tasks such as tracking, annotations, etc.

https://github.com/roboflow/supervision/assets/26109316/c9436828-9fbf-4c25-ae8c-60e9c81b3900

## 💻 install

- clone repository and navigate to example directory

    ```bash
    git clone https://github.com/roboflow/supervision.git
    cd supervision/examples/traffic_analysis
    ```

- setup python environment and activate it [optional]

    ```bash
    venv\Scripts\activate
    deactivate
    ```

- install required dependencies

    ```bash
    pip install -r requirements.txt
    ```



## ⚙️ run

```bash
python script.py --source_weights_path yolov8n.pt --source_video_path video.mp4 --confidence_threshold 0.3 --iou_threshold 0.5 --target_video_path traffic_analysis_result.mov
```
