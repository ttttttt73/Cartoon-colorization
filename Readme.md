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


Please donwload, unzip, and place the mask_rcnn_coco.h5 in :   
pre_project/mask r-cnn _ pix2pix dataset/


Please download and place the annotations in :   
pre_project/coco/annotations/


modify your directory path:   
coco.py
line 114 → annotation's path


modify your directory path:   
Mask R-CNN_Making_dataset_Background.ipynb
cell 13 → target_directory(output directory)
cell 14 → glob(input image's path)


## References

[Mask-RCNN](https://github.com/matterport/Mask_RCNN)

[pix2pix](https://phillipi.github.io/pix2pix/)
