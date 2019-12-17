# Study of RAdam based on the paper "On the Variance of the Adaptive Learning Rate and Beyond" by Liu et Al. (2019a)

```
@article{liu2019radam,
  title={On the Variance of the Adaptive Learning Rate and Beyond},
  author={Liu, Liyuan and Jiang, Haoming and He, Pengcheng and Chen, Weizhu and Liu, Xiaodong and Gao, Jianfeng and Han, Jiawei},
  journal={arXiv preprint arXiv:1908.03265},
  year={2019}
}
```
I also used the code implemented from the paper "On the adequacy of untuned warmup for adaptive optimization" by Jerry Ma and Denis Yarats to test Adam with warmup.


In this project, I compare the performance of RAdam with Adam and Adam with warmup using the Fashion MNIST dataset. More precisely, the code evaluate the robustness of these optimization algorithms to variations of the learning rate. My report 
delves deeper in the theory and the implementation.

## Prerequisites

Here is the list of libraries needed: torch, math , torchvision, pytorch-warmup, tensorflow, tensorboard


## Results

Below are the learning curves I obtained after training with these 3 optimizers with a batch size of 1000.
The performance for Radam : 

![Train Loss](https://github.com/marl917/radam-optimizer/blob/master/images/Accuracy_Radam_lr_r.png)



