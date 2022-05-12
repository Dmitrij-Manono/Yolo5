# Yolo5
Working Yolov5 Framework, with some tools that help Create / Train / Validate Yolov5 Object Detetection Models


<details>
<summary>Installation</summary>
Python 3.9+ Required
Clone  [repo](https://github.com/ultralytics/yolov5) and install [requirements.txt](https://github.com/ultralytics/yolov5/blob/master/requirements.txt)


```bash
git clone https://github.com/ultralytics/yolov5  # clone
cd yolov5
pip install -r requirements.txt  # install
```

Overwrite Torch for GPU training (not needed if you train on CPU)
```bash
pip install torch==1.8.0+cu101 torchvision==0.9.0+cu101 -f https://download.pytorch.org/whl/torch_stable.html
```

</details>

<details>
<summary>Training</summary>
  
```python
python train.py --img 640 --batch 16 --epochs 3 --data coco128.yaml --weights yolov5s.pt
```

</details>
