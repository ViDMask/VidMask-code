# VidMask-code

# Welcome to the VidMask-code wiki!

# Vidmask - Large dataset for Facemask detection.
Vidmask is a large dataset for face mask detection. The Vidmask data was trained on state-of-art deep learning models to identify the mAP and FPS score for real time usage. 

## ViDmask Dataset
The link to the dataset : [ViDmask](https://drive.google.com/file/d/143oAqbL8VUnfz8w8h1AwYrAwZCQBiVYR/view?usp=sharing)
### Description
The dataset consists of videos from public sources of people wearing masks. The videos are converted to frames and labelled for object detection. The annotations are in TXT format, it contains 12000 video frames and their labels. Each model in this paper is trained using custom dataset :ViDmask.
All the models have their pretrained models used, for transfer learning. The config files in each were modified to accommodate the custom dataset 
That is number of classes =2 and the class name as ['mask','nomask']. 

## The deep learning models used for facemask detection:

### YOLOR: [code](https://github.com/WongKinYiu/yolor.git)


### YOLOv5: [code](https://github.com/ultralytics/yolov5.git)


### YOLOv4: [code](https://github.com/Tianxiaomo/pytorch-YOLOv4.git)


### YOLOV4 tiny:[code](https://github.com/Tianxiaomo/pytorch-YOLOv4.git)


### Detectron2( MaskRCNN with resnet101 and FPN):[code](https://github.com/facebookresearch/detectron2.git)

