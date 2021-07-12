# MAFA_test_refined

This repository provides the refined labels of [MAFA](https://www.kaggle.com/rahulmangalampalli/mafa-data) test set. The refined 9545 labels is corresponding to 4935 images in MAFA test set.  

The original MAFA dataset is introduced by the paper titled "Detecting Masked Faces in the Wild With LLE-CNNs" in CVPR2017. According to our analysis, however, MAFA test set contains a lot of mislabels with face box or occlusion degree. To evaluate the class-specific masked face accuracy, we correct the original labels.
For more information, please refer to the "LSFD: LSFD: Lightweight Single Stage Masked Face Detector with a CPU Real-time Speed" in ICTC2021.

# USAGE

Download a label file "mafa_test_gt_refined.txt".  
Each line represents labels, **"path/to/the/image|{x1,y1,x2,y2,occlusion}"** corresponding to an image.  
The **occlusion** is 1 (*clean*) or 2 (*masked*).  


# ACKNOWLEDGEMENTS

If you use this repo, please reference the following two works:

MAFA original:
```
@inproceedings{shiming2017mafa,
Author = {Shiming Ge, Jia Li, Qiting Ye, Zand Zhao Luo},
Booktitle = {IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
Title = {Detecting Masked Faces in the Wild with LLE-CNNs},
Year = {2017}}
```

Ours:
```
TODO
```



