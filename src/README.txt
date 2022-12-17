The working codes include two parts: Depth-aware and Laplacian-steered Neural Style Transfer part and FCN part. 

For Depth-aware and Laplacian-steered Neural Style Transfer part, the ipynb evolved from Problem set 6 of EECS 504: Foundation of Computer Vision from UMich. 

Compared with the original version, we changed the pretrained VGG 19 network part, updated the data preprocessing and dataloader part, added the realization of Depth loss, Laplacian loss and demonstrated the Image Merging part.

Problem set 6 of EECS 504: Foundation of Computer Vision from UMich download:
https://www.eecs.umich.edu/courses/eecs442-ahowens/fa22/psets/ps6.pdf

For Semantic Segmentation part, this FCN is mainly inspired by open source online deep learning course Dive into Deep Learning with site: 
https://d2l.ai/chapter_computer-vision/fcn.html. 

We read through the course and reimplemented the main body of FCN. In Dive into Deep Learning, the backbone of FCN is ResNet-18. We implemented a ResNet-34 backbone version here. Therefore, the main structure might be similar, But almost all the details are reimplemented and modified. In accuracy measurement part, I use the functions from wkentaro's pytorch-fcn to calculate the Confusion Matrix and accuracy. 

FCN Pytorch code inspired from Github:
https://github.com/wkentaro/pytorch-fcn/blob/main/torchfcn/utils.py
