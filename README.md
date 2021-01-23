# **Mask Detector**
 A mask detector using YoloV5

 ## **Installation**

Clone the repository, then cd to mask_detector and run:

```bash
pip install -r requirements.txt
```

## **Detection**

### For detection on images or videos

```bash
python detect.py --source <path_to_folder/image/video> --weights ./weights/best_yolo5m.pt --conf 0.6
```

### For live detection with camera

```bash
python detect.py --source 0 --weights ./weights/best_yolo5m.pt --conf 0.6
```

**Note:** Your will find the detection results in: ```runs/detect/exp<Number>```

