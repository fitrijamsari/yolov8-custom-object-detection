# yolov8-custom-object-detection

Custom object detection repository from train, predict and validate using yolov8.

# SETUP INSTRUCTION

## CREATE PROJECT ENV

1. Create a conda environment with python version 3.8

```bash
conda create --name yolov8 python=3.8
```

2. Activate the environment:

```bash
conda activate yolov8
```

3. [Install pythorch locally](https://pytorch.org/get-started/locally/)

4. Install the ultralytics package from PyPI

```bash
pip install ultralytics
```

4. Test the installation
   To test if the installation in correct, we can run a sample prediction on an image.

```bash
yolo predict model=yolov8n.pt source='https://ultralytics.com/images/zidane.jpg'
```

Result of prediction on zidane.jpg will appear e.g. 384x640 2 persons, 1 tie, 85.9ms

# SOURCE:

1. [Quick Setup Ultralytics](https://docs.ultralytics.com/quickstart/#conda-docker-image)
