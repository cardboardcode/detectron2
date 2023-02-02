## **What Is This?**

This `README.md` contains a self-isolated manner of **training a custom model** and evaluating its accuracy.

## **Build**

1. Download **balloon** dataset:

```bash
wget https://github.com/matterport/Mask_RCNN/releases/download/v2.1/balloon_dataset.zip
unzip balloon_dataset.zip > /dev/null
```

2. Download **model weights**:

```bash
wget https://dl.fbaipublicfiles.com/detectron2/ImageNetPretrained/MSRA/R-50.pkl
```

### Dataset

WIP

## **Run**

1. Train and generate a `final_model.pth`: 

```bash
python train.py
```

2. Evaluate the custom model:

```bash
python evaluate.py
```