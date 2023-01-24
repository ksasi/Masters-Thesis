# [Bias and Fairness in Low Resolution Image Recognition](https://ksasi.github.io/pdfs/MT19AIE308-Report.pdf)

This repository contains details related to my Masters Thesis - ***"[Bias and Fairness in Low Resolution Image Recognition](https://ksasi.github.io/pdfs/MT19AIE308-slide.pdf)"*** completed under the guidance of [Dr. Mayank Vatsa](http://home.iitj.ac.in/~mvatsa/) and [Dr. Richa Singh](http://home.iitj.ac.in/~richa/)

## Abstract:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Recent image recognition algorithms showed great performance, which was possible due to advancements in deep learning methods. These methods find application in variety of scenarios such as recognising
species, surveillance, identifying missing persons, identifying objects from drones during floods etc. However, current methods assume the availability of images of very high resolution. Obtaining images of high resolution is not always possible due to large distance of the object and inherent limitations in the
acquisition device such as camera. Hence it is important to develop robust algorithms that can also work
with low resolution and very low resolution images. It is also essential that these algorithms are not
biased and are fair to different sub groups.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Recent algorithms in the literature showed decent improvement in performance. However, bias and
fairness was not taken into consideration in the current algorithms specially in components that use
generative models.Hence, there is enormous scope to further improve the performance of image recognition
with low resolution along with developing fair algorithms. In this work, we attempted to cover existing
literature. We showed experimentally that this problem needs further research for improved performance.
We had also showed that existing generative models specifically GANs are prone to bias and fairness issues
and can cause cause disparate impact. Lastly we proposed methods and techniques to debiase existing
generative models. We hope these techniques can be used to develop fair algorithms for low resolution
image recognition.

## Code:

* Low Resolution face recognition - [Github Link](https://github.com/ksasi/face-recognition)
* Bias and Fairness in GANs - [Github Link](https://github.com/ksasi/fairDL)
* FairDistillation in GANs - [Github Link](https://github.com/ksasi/fair-distill)
