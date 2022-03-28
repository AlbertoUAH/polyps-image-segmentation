# Polyps classification on colonoscopy images via deep learning

__Author__: Fernández Hernández, Alberto.

__Date__: 2022-01-09

__In progress...__

![In progress icon](https://i.gifer.com/origin/82/82a1ed531e333926a8ca2a00c277e0d1.gif)

# __Summary__

The main purpose of this project is:

1. "Offline" Polyps segmentation using traditional U-Net model

![Unet segmentation sample output](./media/unet_segmentation_sample.png)

2. "Oline" Polyps segmentation in video capsule endoscopy using a lightweight model

Best model: MobileNet_v2 architecture - NanoNet version

__Intersection over Union score (IoU)__:

| Data type | IoU score |
| --------- | --------- |
| _train_ | 0.7398 | 
| _val_ | 0.7003 |  
| _test_ | 0.7150401 |
