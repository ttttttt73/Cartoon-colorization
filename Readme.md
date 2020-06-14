## Requirements

Cython

pycocotools

scikit-image

imgaug

numpy

matplotlib

Pillow

tensorflow==1.15

keras==2.3.1

jupyter

opencv-python==4.2.0

## STEP


Please donwload and place the [mask_rcnn_coco.h5](https://github.com/matterport/Mask_RCNN/releases/download/v2.0/mask_rcnn_coco.h5) in :   
pre_project/mask r-cnn _ pix2pix dataset/


Please download, unzip and place the [annotations](http://images.cocodataset.org/annotations/annotations_trainval2014.zip) in :   
pre_project/coco/annotations/


Please download car dataset and place in :   
pre_project/car_dataset


Please download car dataset and place in :   
Mask-RCNN-Shiny/car_dataset


## Create car/background datasets   

>cd Mask-RCNN-Shiny   
>jupyter notebook   
>run foreground.ipynb # extraction foreground   
>run background.ipynb # extraction background   

## Train   

>cd pre_project/pix2pix/
>python main.py --phase train --dataset_name='dataset_name'

## Test

>cd pre_project/pix2pix/
>python main.py --phase test

## References

[Mask-RCNN](https://github.com/matterport/Mask_RCNN)   
[Mask-RCNN-Shiny](https://github.com/huuuuusy/Mask-RCNN-Shiny)   
[pix2pix](https://phillipi.github.io/pix2pix/)   
[pix2pix by yenchenlin](https://github.com/yenchenlin/pix2pix-tensorflow)   
[pix2pix (keras)](https://github.com/eriklindernoren/Keras-GAN/tree/master/pix2pix)   
