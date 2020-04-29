

this repo acts as open source python implementation to the demo porposed by landingAI

## System Architecture


## How to use the repo

### 1.clone the repo

### 2. Install dependencies (reccommended in virtual environment)

``` 
virtualenv -p python3 venv
source venv/bin/activate
pip install -r requirements.txt
```

###  3.download YOLOV3 pretrained weights and architecture 

``` 
mkdir yolo_weights
cd yolo_weights
wget https://pjreddie.com/media/files/yolov3.weights
wget https://raw.githubusercontent.com/pjreddie/darknet/master/cfg/yolov3.cfg
wget https://raw.githubusercontent.com/pjreddie/darknet/master/data/coco.names
```

### 4.run the code

``` 
python main.py --video 'video path'
```

## check sample result of the implementation

![my results](mydemo.gif)

## Citation

test video taken from http://www.robots.ox.ac.uk/ActiveVision/Research/Projects/2009bbenfold_headpose/Datasets/TownCentreXVID.avi

``` 
@article{yolov3, 
  title={YOLOv3: An Incremental Improvement}, 
  author={Redmon, Joseph and Farhadi, Ali}, 
  journal = {arXiv}, 
  year={2018}
}
```

