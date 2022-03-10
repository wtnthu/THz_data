# THz-TDS Image Dataset
The THz-TDS Image Dataset provides THz temporal-spatio-spectral data, available from this page, include 7 sample objects, and each object has 60 views. 
<img src='./fig/data_vis.png'>

## Download
**Dataset are available as below:**

https://drive.google.com/drive/folders/11F33tinezQA8TrqHzrH3jZMgGPj11Tye?usp=sharing

The dataset include 4 files:

**Gt:** the Ground-truth image.

**Time:** the time domain signal.

**Amp:** the amplitude compinents from time frequency.

**Phase:** the phase compinents from time frequency.


## About Dataset
The measurement of sample objects by a Printech 3D printer, and use the material of high impact polystyrene (HIPS) for 3D-printing the objects
due to its high penetration of THz waves. We then use our in-house ASOPS THz-TDS system. 
Each sample object is placed on a motorized stage between the source and the receiver. 
With the help of the motorized stage, raster scans are performed on each object in multiple view angles. 
In the scanning phase, we scan the objects covering a rotational range of 180 degrees (step-size: 6 degrees),  a horizontal range of 72mm (step-size: 0.25mm), and a variable vertical range corresponding to the object height (step-size: 0.25mm). 
In this way, we obtain 30 projections of each object, which are then augmented to 60 projections by horizontal flipping. The ground-truths of individual projections are obtained by converting the original 3D printing files into image projections in every view-angle. We use markers to indicate the center of rotation so that we can align the ground-truths with the measured THz data. In this paper, totally 7 objects are printed, measured, and aligned for evaluation. 
