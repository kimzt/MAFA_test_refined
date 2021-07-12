# MAFA_test_refined

This repository provides the refined MAFA (https://www.kaggle.com/rahulmangalampalli/mafa-data) test set. The original MAFA test set contains a lot of mislabels, especially in occlusion degree.  
The refined dataset includes 4935 images and 9545 faces.

We first refined MAFA test set. For more detailed information, please refer to the "LSFD: LSFD: Lightweight Single Stage Masked Face Detector with a CPU Real-time Speed" in ICTC 2021.

# USAGE

Download a label file "mafa_test_gt_refined.txt".  
Each line represents labels, **"path/to/the/image|{bbox|occlusion}"** corresponding to an image.  
The **"bbox"** is represented by 'xyxy' format.  
The **"occlusion"** is 1 (*clean*) or 2 (*masked*).  


# ACKNOWLEDGEMENTS

If you use this repo, please reference our work:

'''
not yet published
'''




