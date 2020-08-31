---
layout: archive
title: "Projects"
permalink: /project/
author_profile: true
---

## Conditional GAN with Additive Angular Margin Loss in Discriminator(On Going Research) ##
![pipeline](/images/AAM-GAN.png) {:height="500px" width="500px"}

We have introduced an additive angular margin loss in the classification head of discriminator. 
This loss penalizes the discriminator while predicting the class label. In result, the generator learns to produce images with preserved class features   
Our method has significantly improved the classification accuracy of translated images when compared with the baseline (Star-GAN).
We are performing additional experiments. Our aim is to target CVPR 2021 with the outcome paper.

Supervisors: Dr. Binod Bhattarai, Dr. Bishesh Khanal and Dr. Danda Pani Poudel

## Spine Curvature Estimation from X-ray Images  ##
![pipeline](/images/spine.png) {:height="500px" width="500px"}

In this project, we proposed a novel idea to estimate vertebra landmarks in X-ray images.
- Object Detector to Predict each vertebra as a single object.
- Landmark Estimator to find landmark location in each vertebra.

With this work, we participated in **Accurate Automated Spinal Curvature Estimation MICCAI 2019 Challenge**. I presented the paper at MICCAI 2019 workshop.

Supervisor: Dr. Bishesh Khanal
  


## Estimating Pesticide Concentration with Smartphone  ##
![pipeline](/images/pesticide.png) {:height="500px" width="500px"}

- Prepared a new Image dataset for Food Dye and Pesticide assays to study the smartphone based colorimetric detection using data-driven machine learning approach.
- Accessed machine learning models (SVM, Logistic Regression, Random Forest and ANN) in classifying pesticide concentration labels based on its residue color strength.
We are revising the paper of this work for submission.

Supervisors: Dr. Bishesh Khanal and Dr. Basant Giri

## Synthetic to Real Domain Translation Using Conditional GAN  ##
![pipeline](/images/gan.png) {:height="500px" width="500px"}

In this project, we looked into the problem with the conditional GANs in preserving the shape of the imput image. We solved this problem by using two GANs. 
First GAN trains with unpaired images. The best generated images are distilled using IOU criterion, thus generating good pairs of images. These pairs are then use 
to train a second GAN network (pix2pixHD). The later network trained with distilled examples learn to preserve the shape of the input.

Supervisor: Dr. Binod Bhattarai 
