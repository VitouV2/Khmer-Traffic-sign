# *Khmer-Traffic-sign*
This dataset contains traffic signs commonly found on Cambodian roads. It’s made for training and testing machine-learning models such as image classification, detection, and recognition.
##

# **Folder Structure**
```
KhmerTrafficSign/
├── Train/
├── Test/
└── Validation/
```
## **Dataset Structure**
```
KhmerTrafficSign/
│
├── Train/
│ ├── Cross Road
│ ├── Left Road
│ ├── Maximum Speed 40
│ ├── No Entry
│ ├── No Parking
│ ├── No Turn Right
│ ├── No U Turn
│ ├── Pedestrian Crossing
│ ├── Road Junction on The Left
│ ├── Road Junction on The Right
│ ├── Slow Down
│ ├── Stop
│ └── Traffic Lights
│
├── Test/ (optional)
└── Validation/ (optional)
```
# **Classes (13 Total)**

1. Cross Road
2. Left Road
3. Maximum Speed 40
4. No Entry
5. No Parking
6. No Turn Right
7. No U Turn
8. Pedestrian Crossing
9. Road Junction on The Left
10.Road Junction on The Right
11. Slow Down
12. Stop
13. Traffic Lights
##
# **Dataset Information**
- Total classes: 13
- Image format: JPG / PNG
- Resolution: varies
- Use cases: classification, recognition, model training
##
# **How to Use**
Python (OpenCV)

```
import cv2
img = cv2.imread("Train/Stop/img_001.jpg")
```

## 📄 License
MIT License
