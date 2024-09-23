# venvBuilderTD
![image](https://github.com/user-attachments/assets/28076da8-5af4-4a5b-9253-5c24d5208107)


## Requirements
- git to fetch this respository
- Touchdesigner 2023.xxxx
- Sample needs a Nvidia GPU with Cuda support (with some tiny modifcation the example works also on non cuda devices)
- Windows
  
## Install 

The repository contains lfs marked files. Make sure to clone the repository and fetch all lfs files!

```bash
git clone https://github.com/ioannismihailidis/venvBuilderTD.git
cd venvBuilderTD
git lfs fetch --all
```

or (deprecated)

```bash
git lfs clone https://github.com/ioannismihailidis/venvBuilderTD.git
```


## Sample _yolov8_detection_ 

Features:
- running yolov8 in realtime from an Input TOP
- usage of pip package supervision for additional annoation and tracking
- tensorRT model export feature


## Sample _yolov8_detection_cudatop_

Features:
- much faster TOP to tensor processing by using effectice cuda to tensor workflow provided by https://github.com/IntentDev/TopArray/
- same features as above
  

## Sample _sam2_ (Segment Anything 2)

Work in progress.
