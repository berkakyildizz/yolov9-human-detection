### Using YoloV9 for Human Detection
![aa](https://github.com/berkakyildizz/yolov9-human-detection/assets/129900162/5e9db71c-e8f2-4023-8ccb-5141689fd7f1)

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

### This notebook is intended to run the yolov9 model and detect people in an image. For this purpose, the model is run and the people in the running model are detected and the detected people are placed in a box. You will also realize how well the Yolov9 model works as you use it :)

![performance](https://github.com/berkakyildizz/yolov9-human-detection/assets/129900162/8bc6afa1-dd23-4c7b-bb1f-db693f86fa2c)


### Acknowledgements


