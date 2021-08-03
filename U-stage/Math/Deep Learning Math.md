# 1. Structure of Neural Networks
* Repetition of linear transformation and non-linear transformation
* Linear transformation: X -> Z
  * Use of simple mulitplication and addition (aX+b=Z)
* Non-linear transformation: Z -> H
  * Use of activation functions such as ReLU, tanh functions
![plot](https://github.com/hyeong01/AI-boostcamp/blob/main/U-stage/Math/images/layers.PNG)
* Why multi-layer?
  * According to universal approximation theorem, even two-layer neural network can approximate any continous function. However, having more layers allow the model to have less nodes and thus train faster for the same task.
# 2. How Does a Neural Network Train: Back Propagation