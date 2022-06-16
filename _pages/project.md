---
layout: archive
title: "Projects"
permalink: /project/
author_profile: true
---

## 1. How Does Heterogeneous Label Noise Impact Generalization in Neural Nets? ##

<img src="/images/label_noise.png" width="700" height="700"/>

Incorrectly labeled examples, or label noise, is common in real-world
computer vision datasets. While the impact of label noise on learning in deep
neural networks has been studied in prior work, these studies have exclusively
focused on homogeneous label noise, i.e., the degree of label noise is the same
across all categories. However, in the real-world, label noise is often heterogeneous, with some categories being affected to a greater extent than others. Here,
we address this gap in the literature. We hypothesized that heterogeneous label
noise would only affect the classes that had label noise unless there was transfer
from those classes to the classes without label noise. To test this hypothesis, we
designed a series of computer vision studies using MNIST, CIFAR-10, CIFAR100, and MS-COCO where we imposed heterogeneous label noise during the
training of multi-class, multi-task, and multi-label systems. Our results provide
evidence in support of our hypothesis: label noise only affects the class affected
by it unless there is transfer.

## 2. Efficient Online Continual Learning ##

Working on developing efficient online learning classifier that is capable of learning from single pass
through the dataset while being computationally efficient. For this work, we proposed a large-margin regularized multi-linear discriminant analysis algorithm which can dynamically create and collapse modes observed in the stream of data.


## 3. Label Geometry Aware Discriminator for Conditional Generative Networks ##

<img src="/images/AAM-GAN.png" width="700" height="700"/>

Multi-domain image-to-image translation with conditional Generative Adversarial Networks (GANs) can generate highly photo realistic images with desired target classes, yet these synthetic images have not always been helpful to improve downstream supervised tasks such as image classification. Improving downstream tasks with synthetic examples requires generating images with high fidelity to the unknown conditional distribution of the target class, which many labeled conditional GANs attempt to achieve by adding soft-max cross-entropy loss based auxiliary classifier in the discriminator. As recent studies suggest that the soft-max loss in Euclidean space of deep feature does not leverage their intrinsic angular distribution, we propose to replace this loss in auxiliary classifier with an additive angular margin (AAM) loss that takes benefit of the intrinsic angular distribution, and promotes intra-class compactness and inter-class separation to help generator synthesize high fidelity images. We validate our method on RaFD and CIFAR-100, two challenging face expression and natural image classification data set. Our method outperforms state-of-the-art methods in several different evaluation criteria including recently proposed GAN-train and GAN-test metrics designed to assess the impact of synthetic data on downstream classification task, assessing the usefulness in data augmentation for supervised tasks with prediction accuracy score and average confidence score, and the well known FID metric.


## 4. Spine Curvature Estimation from X-ray Images  ##

<img src="/images/spine.png" width="700" height="700"/>

Correct evaluation and treatment of Scoliosis require accu-
rate estimation of spinal curvature. Current gold standard is to manually
estimate Cobb Angles in spinal X-ray images which is time consuming
and has high inter-rater variability. We propose an automatic method
with a novel framework that first detects vertebrae as objects followed
by a landmark detector that estimates the 4 landmark corners of each
vertebra separately. Cobb Angles are calculated using the slope of each
vertebra obtained from the predicted landmarks. For inference on test
data, we perform pre and post processings that include cropping, outlier
rejection and smoothing of the predicted landmarks. The results were as-
sessed in AASCE MICCAI challenge 2019 which showed a promise with
a SMAPE score of 25.69 on the challenge test set.

With this work, we participated in **Accurate Automated Spinal Curvature Estimation MICCAI 2019 Challenge**. 



## 5. Estimating Pesticide Concentration with Smartphone  ##

<img src="/images/pesticide.png" width="800" height="800"/>

Paper-based analytical devices (PADs) employing colorimetric detection and smartphone images have gained wider acceptance in a variety of measurement applications. PADs are primarily meant to be used in field settings where assay and imaging conditions greatly vary, resulting in less accurate results. Recently, machine-learning (ML)-assisted models have been used in image analysis. We evaluated a combination of four ML models-logistic regression, support vector machine (SVM), random forest, and artificial neural network (ANN)-as well as three image color spaces, RGB, HSV, and LAB, for their ability to accurately predict analyte concentrations. We used images of PADs taken at varying lighting conditions, with different cameras and users for food color and enzyme inhibition assays to create training and test datasets. The prediction accuracy was higher for food color than enzyme inhibition assays in most of the ML models and color space combinations. All models better predicted coarse-level classifications than fine-grained concentration classes. ML models using the sample color along with a reference color increased the models' ability to predict the result in which the reference color may have partially factored out the variation in ambient assay and imaging conditions. The best concentration class prediction accuracy obtained for food color was 0.966 when using the ANN model and LAB color space. The accuracy for enzyme inhibition assay was 0.908 when using the SVM model and LAB color space. Appropriate models and color space combinations can be useful to analyze large numbers of samples on PADs as a powerful low-cost quick field-testing tool.



## 6. Synthetic to Real Domain Translation Using Conditional GAN  ##

<img src="/images/gan.png" width="700" height="700"/>

In this project, we looked into the problem with the conditional GANs in preserving the shape of the imput image. We solved this problem by using two GANs. 
First GAN trains with unpaired images. The best generated images are distilled using IOU criterion, thus generating good pairs of images. These pairs are then use 
to train a second GAN network (pix2pixHD). The later network trained with distilled examples learn to preserve the shape of the input.


