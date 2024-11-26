Use this repository to convert cityscapes to COCO format : https://github.com/TillBeemelmanns/cityscapes-to-coco-conversion.git

Then use COCO_to_YOLO.ipynb to convert labels to yolo format.

Use Sample_yolov11.ipynb to run yolov11 on converted dataset.

Output will be saved ina  directory "runs". YOLO will also generate images for metrics automatically and save them there.

I have added first full run here in this repository. I used my personal Nvidia RTX 3050 GPU so i still have to experiment with the model for better training.

Sample runs :

![Random image from datset](C:\projects\YOLOv11_cityscapes\aachen_000001_000019_leftImg8bit.jpg)

