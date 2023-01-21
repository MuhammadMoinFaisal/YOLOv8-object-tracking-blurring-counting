<H1 align="center">
YOLOv8 Object Tracking (ID + Trails) Blurring and Counting </H1>

## Google Colab File Link (A Single Click Solution)
The google colab file link for yolov8 object tracking, blurring and vehicle counting is provided below, you can check the implementation in Google Colab, and its a single click implementation
,you just need to select the Run Time as GPU, and click on Run All.

[`Google Colab File`](https://colab.research.google.com/drive/1U6cnTQ0JwCg4kdHxYSl2NAhU4wK18oAu?usp=sharing)

## YOLOv8 Segmentation with DeepSORT Object Tracking

[`Github Repo Link`](https://github.com/MuhammadMoinFaisal/YOLOv8_Segmentation_DeepSORT_Object_Tracking.git)

## Steps to run Code

- Clone the repository
```
git clone https://github.com/MuhammadMoinFaisal/YOLOv8-object-tracking-blurring-counting.git
```
- Goto the cloned folder.
```
cd YOLOv8-object-tracking-blurring-counting
```
- Install the dependecies
```
pip install -e '.[dev]'

```

- Setting the Directory.
```
cd ultralytics/yolo/v8/detect

```
- Downloading the DeepSORT Files From The Google Drive 
```

https://drive.google.com/drive/folders/1kna8eWGrSfzaR6DtNJ8_GchGgPMv3VC8?usp=sharing
```
- After downloading the DeepSORT Zip file from the drive, unzip it go into the subfolders and place the deep_sort_pytorch folder into the yolo/v8/detect folder

- Downloading a Sample Video from the Google Drive
```
gdown https://drive.google.com/uc?id=1_kt1alzcLRVxet-Drx0mt_KFSd3vrtHU
```

- Run the code with mentioned command below.

- For yolov8 object detection, Tracking,  blurring and object counting
```
python predict.py model=yolov8l.pt source="test1.mp4" show=True
```

### RESULTS

#### YOLOv8 Object Detection, Tracking, Blurring and Counting 
![](./figure/figure1.png)

#### YOLOv8 Object Detection, Tracking, Blurring and Counting 

![](./figure/figure2.png)

### Watch the Complete Step by Step Explanation

- Video Tutorial Link  [`YouTube Link`](https://www.youtube.com/watch?v=9jRRZ-WL698)


[![Watch the Complete Tutorial for the Step by Step Explanation](https://img.youtube.com/vi/9jRRZ-WL698/0.jpg)]([https://www.youtube.com/watch?v=StTqXEQ2l-Y](https://www.youtube.com/watch?v=9jRRZ-WL698))

