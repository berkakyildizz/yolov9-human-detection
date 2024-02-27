### Using YoloV9 for Human Detection

# Installation
### 1- First Step pip Yolov9 

```python
pip install yolov9pip
```

### 2- [Go to this address](https://github.com/WongKinYiu/yolov9) At this address, download the file named yolov9-c.pt from the evaluation section and copy this file to whichever virtual notebook you are working in, or copy it to the directory you are working in. 
### For Example: 
```
C:/Users/userstoo/AppData/Local/anaconda3/envs/yolov9_gpu/yolov9-pip/yolov9/yolov9-c.pt
```

### 3- Run the codes in the human-detection.ipynb file. I also set model.classes = [0], but if you want all classes in the model to be predicted and box plots drawn, you should change it to model.classes = None.  
```
model.classes = [0] # Just Person Classes
model.classes = None # All Classes 
```

### What to do
