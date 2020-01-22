# Instance Segmentation using Detectron2

This project is part of a series of projects for the course _Selected Topics in Visual Recognition using Deep Learning_ that I attended during my exchange program at National Chiao Tung University (Taiwan). See `task.pdf` for the details of the assignment. See `report.pdf` for the report containing the representation and the analysis of the produced results.

The purpose of this project is to implement a model for the task of instance segmentation using Tiny PASCAL VOC dataset. Detectron2 platform is used for this task. In particular, the model used is Mask R-CNN with ResNet50 as backbone. ImageNet pre-trained weights are used as a starting point for training ([final model](https://drive.google.com/open?id=1wXp5LAxRCytpSk5JBe3lzdIG5mQ3gk_5)).

## 1. Installation

See ```Detectron2.ipynb``` for the step-by-step instructions to install Detectron2.

### 1.1. Requirements

- Linux, macOS, Windows

- Python >= 3.6

- PyTorch 1.3

- torchvision that matches the PyTorch installation. You can install them together at pytorch.org to make sure of this.

- OpenCV, needed by demo and visualization

- fvcore: ```pip install -U 'git+https://github.com/facebookresearch/fvcore'```

- pycocotools: ```pip install cython; pip install 'git+https://github.com/cocodataset/cocoapi.git#subdirectory=PythonAPI'```

- GCC >= 4.9

## 2. Dataset

Tiny VOC dataset contains only 1349 training images and 100 test images with 20 common object classes (namely aeroplane, bicycle, bird, boat, bottle, bus, car, cat, chair, cow, diningtable, dog, horse, motorbike, person, pottedplant, sheep, sofa, train, tvmonitor).

- [Training set](https://drive.google.com/open?id=1XyBJremI0zY49bh7HKw_o3sRNO9dTNV9)

- [Training annotations](https://drive.google.com/open?id=1J-1Tb-ih7o2kgyz8RlESF4a3iXgDfx76)

- [Test set](https://drive.google.com/open?id=1XuLQ8OvGsx7U9YUHKBbJqc_nStN2cWbv)

- [Test annotations](https://drive.google.com/open?id=1rGV-OMcP_r7kSF4JD3T3EQmjUu5eGCUQ)

## 3. Project Structure

See ```Detectron2.ipynb``` for importing/installing dependencies, loading the dataset, training the model and using it to apply instance segmentation to test images. Make sure to first download the dataset and the annotations before running the notebook.

## 4. Results

<p align="center">
  <img width="307" height="400" src="https://github.com/AlessandroSaviolo/Instance-Segmentation-using-Detectron2/blob/master/results/result1.png">
</p>
<p align="center">
  <img width="400" height="266" src="https://github.com/AlessandroSaviolo/Instance-Segmentation-using-Detectron2/blob/master/results/result2.png">
</p>
<p align="center">
  <img width="400" height="266" src="https://github.com/AlessandroSaviolo/Instance-Segmentation-using-Detectron2/blob/master/results/result3.png">7
</p>
<p align="center">
  <img width="400" height="341" src="https://github.com/AlessandroSaviolo/Instance-Segmentation-using-Detectron2/blob/master/results/result4.png">
</p>


## 5. Credits

The [Detectron2 GitHub Repository](https://github.com/facebookresearch/detectron2) has deeply helped the development of this project.
