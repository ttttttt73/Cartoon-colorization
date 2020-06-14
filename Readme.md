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


Please download [car dataset](https://drive.google.com/file/d/1Jw2_ZjYtZRXqkQNwdOGzVIrKI4DDTGyi/view?usp=sharing) and place in :   
Mask-RCNN-Shiny/car_dataset


## Create car/background datasets   

>cd Mask-RCNN-Shiny   
>jupyter notebook   
>run foreground.ipynb # extraction foreground   
>run background.ipynb # extraction background   

## Train   

>copy to /pre_project/pix2pix/datasets/'dataset_name'   
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
