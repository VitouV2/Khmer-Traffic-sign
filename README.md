# *Khmer-Traffic-sign*
This dataset contains traffic signs commonly found on Cambodian roads. It’s made for training and testing machine-learning models such as image classification, detection, and recognition.
## **DownLoad DataSet**
Link : (https://drive.google.com/drive/folders/135j3uPuS6t3z1lmQMN8dulFwxORqADXw?usp=sharing)


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
│ ├── Keep Right
│ ├── Right Road
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
# **Classes (15 Total)**

1. Cross Road
2. Keep Right
3. Left Road
4. Right Road
5. Maximum Speed 40
6. No Entry
7. No Parking
8. No Turn Right
9. No U Turn
10. Pedestrian Crossing
11. Road Junction on The Left
12. Road Junction on The Right
13. Slow Down
14. Stop
15. Traffic Lights
##
# **Dataset Information**
- Total classes: 15
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
