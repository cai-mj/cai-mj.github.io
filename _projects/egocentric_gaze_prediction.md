---
title: "Egocentric Gaze Prediction"
collection: projects
permalink: /project/egocentric_gaze_prediction
excerpt: 'This paper is about predicting gaze in egocentric videos by exploiting temporal context between gaze fixations.'
---

<img class="img-responsive" src="/images/ECCV2018_sample.gif">

### Abstract
We present a new computational model for gaze prediction in egocentric videos by exploring patterns in temporal shift of gaze fixations (attention transition) that are dependent on egocentric manipulation tasks.
Our assumption is that the high-level context of how a task is completed in a certain way has a strong influence on attention transition and should be modeled for gaze prediction in natural dynamic scenes.
Specifically, we propose a hybrid model based on deep neural networks which integrates task-dependent attention transition with bottom-up saliency prediction. 
In particular, the task-dependent attention transition is learned with a recurrent neural network to exploit the temporal context of gaze fixations, e.g. looking at a cup after moving gaze away from a grasped bottle.
Experiments on public egocentric activity datasets show that our model significantly outperforms state-of-the-art gaze prediction methods and is able to learn meaningful transition of human attention.  
[[News]](https://www.iis.u-tokyo.ac.jp/en/news/2971/)

### Network architecture
<img class="img-responsive" src="/images/ECCV2018_architecture.jpg">

## Publication:
Y. Huang, <u>M. Cai</u>, Z. Li and Y. Sato, &quot;Predicting Gaze in Egocentric Video by Learning Task-dependent Attention Transition,&quot; <i>European Conference on Computer Vision (**ECCV**)</i>, to appear, 2018. (<font color="blue">oral presentation, acceptance rate: 2%</font>)  
[[Arxiv preprint]](/files/HCLS_eccv_arxiv2018.pdf)
[[Code]](https://github.com/hyf015/egocentric-gaze-prediction)

### Demo video (Youtube)
<iframe width="560" height="315" src="https://www.youtube.com/embed/TiFz-LP3LW4" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
