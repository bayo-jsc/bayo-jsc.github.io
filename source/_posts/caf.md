---
title: CAF dataset, over 8.000 faces of famous actresses
---

We now public the CAF (stands for **C**ropped **A**ctresses' **F**aces) dataset includes 8303 images of famous actresses' faces.

![caf](http://i.imgur.com/qJbd8Ig.jpg)

## Characteristic

+ Each image is a face of one famous actress. One actress may have some vary quantities of images.

+ Each image has the size of 512x512 (square), and is RGB color mode.

+ Each image is labeled with name of the actress plus one unique id, e.g. `Gal_Gadot_0_7.jpg`.

## Technology

+ We crawled 10.000 images from Google Images, select first 8 pics of each actress.

+ We use `dlib` to detect faces then crop. But because `dlib` only detects faces, so in order to include hair, neck, ... we have to extend the boundary of images to 1.5 times larger.

+ Lastly, we preprocess by hand and eyes, to check for bad quality or ugly images and remove them.

## Copyright

The CAF dataset is for research purposes, we do not have any copyright of the images.

## Download

[Google Drive](https://drive.google.com/file/d/0Bz1EQO3FGCUbZWM0N1dlVXc3Yzg/view) [779MB]

If you use CAF dataset for your research, please cite:

> [Hiep Pham](https://github.com/hiepph), [Dung Nguyen Pham Thien](https://github.com/pexea12), *CAF dataset - over 8.000 faces of famous actresses*, 2017. http://blog.bayo.vn/caf/

## Contacts

+ Hiep Pham: **hiepph[at]bayo.vn**
+ Dung Nguyen Pham Thien: **dungnt[at]bayo.vn**
