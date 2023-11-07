---
title: "Investigating the impact of class-dependent label noise in medical image classification"
collection: publications
permalink: /publication/class_dependent_label_noise
excerpt: '**Bidur Khanal**, SM Kamrul Hasan, Bishesh Khanal, and Cristian A. Linte. "*Investigating the impact of class-dependent label noise in medical image classification.*" In Medical Imaging 2023: Image Processing, vol. 12464, pp. 728-733. SPIE, 2023.'

date: 2023-04-03
venue: 'SPIE Medical Imaging'
---
Abstract: Label noise is inevitable in medical image databases developed for deep learning due to the inter-observer
variability caused by the different levels of expertise of the experts annotating the images, and, in some cases,
the automated methods that generate labels from medical reports. It is known that incorrect annotations or
label noise can degrade the actual performance of supervised deep learning models and can bias the model’s
evaluation. Existing literature show that noise in one class has minimal impact on the model’s performance
for another class in natural image classification problems where different target classes have a relatively distinct
shape and share minimal visual cues for knowledge transfer among the classes. However, it is not clear how classdependent
label noise affects the model’s performance when operating on medical images, for which different
output classes can be difficult to distinguish even for experts, and there is a high possibility of knowledge transfer
across classes during the training period. We hypothesize that for medical image classification tasks where the
different classes share a very similar shape with differences only in texture, the noisy label for one class might
affect the performance across other classes, unlike the case when the target classes have different shapes and
are visually distinct. In this paper, we study this hypothesis using two publicly available datasets: a 2D organ
classification dataset with target organ classes being visually distinct, and a histopathology image classification
dataset where the target classes look very similar visually. Our results show that the label noise in one class has
a much higher impact on the model’s performance on other classes for the histopathology dataset compared to
the organ dataset.

**Bidur Khanal**, SM Kamrul Hasan, Bishesh Khanal, and Cristian A. Linte. *"Investigating the impact of class-dependent label noise in medical image classification."* In Medical Imaging 2023: Image Processing, vol. 12464, pp. 728-733. SPIE, 2023.

[Download paper here](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12464/1246437/Investigating-the-impact-of-class-dependent-label-noise-in-medical/10.1117/12.2654420.full)



