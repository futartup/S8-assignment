# S8-assignment
S8 assignment submission

# Train CIFAR10 with PyTorch resnet18 model

This repo is subjected to submission of assignment S8. It implements resnet18 model. 
The target is to acheive 85% accuracy in any number of epochs.

## Results and some observations.
1. Highest test accuracy is 84.51% for only one iteration in total number of epochs.
2. The test accuracy keeps on oscillating in range of 83 - 84 % after a definite number of epoch.
3. The training accuracy is always 96-97 % during training.

## Modifications to be done.
1. Now the learning rate is constant. The learning rate needs to be changed after some number of epochs.
2. May be some more transformations can be added to this kind of dataset..

## Prerequisites
- Python 3.6+
- PyTorch 1.0+

## Accuracy
| Model             | Acc.        |
| ----------------- | ----------- |
| [resnet18](https://arxiv.org/abs/1512.03385)          | 93.02%      |


## Learning rate adjustment
The learning rate is constant (0.01) with momentum of 0.9. All these values are maintained in conf.ipynb file.

## File Structure
![Test Image](https://github.com/futartup/S8-assignment/blob/master/FS.png)


