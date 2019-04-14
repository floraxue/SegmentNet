# SegmentNet

CS 282A Final Project: SegmentNet - Revealing the Secrets of Ancient Roman Concrete with Image Segmentation

## Problem Statement and Background 

### Problem Statement

The purpose of this project is to use image segmentation to identify and quantify different com- ponents in CT images of ancient Roman concrete. Appropriate deep neural network models will be practiced and verified for the image segmentation of other CT images of mineral and concrete material samples.

### Background

Ancient Roman concrete was used as building material during Roman Imperial times for a large number of famous constructions with different functions. Well-known examples are the Pont du Gard in France and the Aqua Alexandrina in Rome. Ancient Roman concrete, unlike modern con- crete, has an exceptional durability, low-carbon footprint and potential to aid the development of next generation of building materials. The structures of cracks and pores in ancient Roman concrete are some of the reasons for its great durability, which we would like to investigate using neural networks. The locations, volumes and distribution of different components in the ancient Roman concrete will be achieved based on the segmentation results.

As part of the first step in this investigation, image segmentation methods will be used to inspect CT images of concrete. Few researches have been done on image segmentation of concrete’s CT images using machine learning methods. Related researches are image segmentation of mineral CT images. Rod et al. \[2019] classified mineral compositions of polymer composite using Random Forest Classification on CT images. Chauhan et al. \[2016\] evaluated the performance and accuracy of seven machine learning algorithms to segment rock grains, matrix and pore from CT images of rocks. To the extent of our knowledge, neural network methods have not yet been applied to the segmentation of mineral or concrete CT images. So we would like to apply several different state- of-the-art neural network architectures to this project, including the Mask R-CNN (He et al.), the Faster R-CNN (Ren et al.) and Dilated residual networks (Yu et al.).

