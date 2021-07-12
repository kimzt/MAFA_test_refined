# MAFA_test_refined

This repository provides the refined MAFA (https://www.kaggle.com/rahulmangalampalli/mafa-data) test set.  
The original MAFA dataset is introduced by the paper titled "Detecting Masked Faces in the Wild With LLE-CNNs" in CVPR2017. According to our analysis, however, MAFA test set contains a lot of mislabels with occlusion degree.
The refined test set includes 4935 images and 9545 faces.

In addition, we first evaluation the detection accuracy against the refined MAFA test set. For more detailed information, please refer to the "LSFD: LSFD: Lightweight Single Stage Masked Face Detector with a CPU Real-time Speed" in ICTC2021.

# USAGE

Download a label file "mafa_test_gt_refined.txt".  
Each line represents labels, **"path/to/the/image|{bbox|occlusion}"** corresponding to an image.  
The **"bbox"** is represented by 'xyxy' format.  
The **"occlusion"** is 1 (*clean*) or 2 (*masked*).  


# ACKNOWLEDGEMENTS

If you use this repo, please reference our work: (not yet published)

'''
LSFD: LSFD: Lightweight Single Stage Masked Face Detector with a CPU Real-time Speed
'''




