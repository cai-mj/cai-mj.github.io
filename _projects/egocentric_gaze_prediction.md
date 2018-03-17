
<img class="img-responsive" src="/images/ECCV2018_architecture.jpg">
### Abstract
We present a new computational model for gaze prediction in egocentric videos by exploring patterns in temporal shift of gaze fixations (attention transition) that are dependent on egocentric manipulation tasks.
Our assumption is that the high-level context of how a task is completed in a certain way has a strong influence on attention transition and should be modeled for gaze prediction in natural dynamic scenes.
Specifically, we propose a hybrid model based on deep neural networks which integrates task-dependent attention transition with bottom-up saliency prediction. 
In particular, the task-dependent attention transition is learned with a recurrent neural network to exploit the temporal context of gaze fixations, e.g. looking at a cup after moving gaze away from a grasped bottle.
Experiments on public egocentric activity datasets show that our model significantly outperforms state-of-the-art gaze prediction methods and is able to learn meaningful transition of human attention.

Video results can be watched [[here]](https://github.com/cai-mj/UTJA_dataset)