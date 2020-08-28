---
title: "Egocentric Hand Segmentation"
collection: projects
permalink: /project/egocentric_hand_segmentation
excerpt: 'This paper is about generalizing hand segmentation in egocentric videos with uncertainty-guided model adaptation.'
---

<img class="img-responsive" src="/images/CVPR2020_task.gif">

### Abstract
Although the performance of hand segmentation in egocentric videos has been significantly improved by using CNNs, it still remains a challenging issue 
to generalize the trained models to new domains, e.g., unseen environments. In this work, we solve the hand segmentation generalization problem without 
requiring segmentation labels in the target domain. To this end, we propose a Bayesian CNN-based model adaptation framework for hand segmentation, which 
introduces and considers two key factors: 1) prediction uncertainty when the model is applied in a new domain and 2) common information about hand shapes 
shared across domains. Consequently, we propose an iterative self-training method for hand segmentation in the new domain, which is guided by the model 
uncertainty estimated by a Bayesian CNN. We further use an adversarial component in our framework to utilize shared information about hand shapes to 
constrain the model adaptation process. 
Experiments on multiple egocentric datasets show that the proposed method significantly improves the generalization performance of hand segmentation.

## Method Overview
<img class="img-responsive" src="/images/CVPR2020_method.png">

## Publication:
<u>M. Cai</u>, F. Lu and Y. Sato, &quot;Generalizing Hand Segmentation in Egocentric Videos with Uncertainty-Guided Model Adaptation,&quot; <i>IEEE Conference 
on Computer Vision and Pattern Recognition (**CVPR**)</i>, 2020. (<font color="blue">acceptance rate: 22%</font>)  
[[paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Cai_Generalizing_Hand_Segmentation_in_Egocentric_Videos_With_Uncertainty-Guided_Model_Adaptation_CVPR_2020_paper.pdf)
[[Code]](https://github.com/cai-mj/UMA)
