# Matterport Mask R-CNN hacked!


## overview

This repo is a simplification of the [Mask-RCNN-TF2](https://github.com/ahmedfgad/Mask-RCNN-TF2) by [Ahmed Gad](https://github.com/ahmedfgad) with some minor changes in the files:

1. `mrcnn/model.py`
2. `mrcnn/utils.py`

Mask-RCNN-TF2 extends the original [Mask_RCNN](https://github.com/matterport/Mask_RCNN) project by incorporating TensorFlow 2.0. Use this repo or Mask-RCNN-TF2 with TF2 only as TF1 functionality is not supported.

This project has been tested using:

- tensorflow 2.2.0
- keras 2.3.1
- h5py 2.10

## resources

This project does not require installation. To run this successfully it is recommended to uninstall existing versions of TF, Keras, and H5PY as follows:

```
!pip uninstall keras -y
!pip uninstall keras-nightly -y
!pip uninstall keras-Preprocessing -y
!pip uninstall keras-vis -y
!pip uninstall tensorflow -y

!pip install tensorflow==2.2.0
!pip install keras==2.3.1
!pip install h5py==2.10.0
```

Copy the ```mrcnn``` directory into your project and you are good to go.

You will need the COCO weights so make sure you get a copy from [here](https://github.com/matterport/Mask_RCNN/releases/download/v2.0/mask_rcnn_coco.h5).

## usage 

An example of using this project in Google Colab notebooks can be found here (coming shortly)

## Acknowledgements 

A great thank you to both team Matterport for this amazing piece of work, and to Ahmed Gad for making the effort of bring the original project up to date.

## Citation

Use this bibtex to cite the original Matterport repository:
```
@misc{matterport_maskrcnn_2017,
  title={Mask R-CNN for object detection and instance segmentation on Keras and TensorFlow},
  author={Waleed Abdulla},
  year={2017},
  publisher={Github},
  journal={GitHub repository},
  howpublished={\url{https://github.com/matterport/Mask_RCNN}},
}
```


