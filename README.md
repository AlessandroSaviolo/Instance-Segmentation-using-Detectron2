# Instance segmentation with Detectron2

Implementation of Detectron2 for the task of instance segmentation using Tiny PASCAL VOC dataset. The model used is Mask R-CNN with ResNet50 as backbone. ImageNet pre-trained weights are used as a starting point for training. More information about the project and the code can be found in report.pdf.

## 1. Installation

See the Notebook for the step-by-step instructions to install detectron2.

### 1.1. Requirements

- Linux, macOS, Windows

- Python >= 3.6

- PyTorch 1.3

- torchvision that matches the PyTorch installation. You can install them together at pytorch.org to make sure of this.

- OpenCV, needed by demo and visualization

- fvcore: ```pip install -U 'git+https://github.com/facebookresearch/fvcore'```

- pycocotools: ```pip install cython; pip install 'git+https://github.com/cocodataset/cocoapi.git#subdirectory=PythonAPI'```

- GCC >= 4.9

## 2. Download Dataset

[Training set](https://drive.google.com/open?id=1De1LwcyS4Bv4jMUDP7FwTk3Mlvz4UZVY)

[Training annotations](https://drive.google.com/open?id=1PJlwiTwjOvTeoco58o137qCNhL20eZ2U)

[Test set](https://drive.google.com/open?id=1vrDyKus2H7XsLJ78f_g6XKK3YvF9ZVyZ)

[Test annotations](https://drive.google.com/open?id=1aLxbdYZXIE3PHcqA_Df-odnE8IPnneyD)

## 3. Pre-trained Model

[Final Model](https://drive.google.com/open?id=1wXp5LAxRCytpSk5JBe3lzdIG5mQ3gk_5)

## 4. Results

![Test Image](https://github.com/tograh/testrepository/master/3DTest.png)

![Test Image](https://raw.githubusercontent.com/tograh/testrepository/master/3DTest.png)

### 5. Credits

The [Detectron2 GitHub Repository](https://github.com/facebookresearch/detectron2) has deeply helped the development of this project.
