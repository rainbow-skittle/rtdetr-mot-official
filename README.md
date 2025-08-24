 I’ve been working with the official PyTorch implementation of DETR provided by lyuwenyu github link: https://github.com/lyuwenyu/RT-DETR/tree/main/rtdetr_pytorch

Initially, I trained the model on a small subset of the dataset for 25 epochs, but the accuracy was relatively low. To improve this, I later split the dataset into an 
80-20 train-validation set and retrained the model for few epochs. This adjustment led to a noticeable improvement in accuracy and generalization.

I’ve attached the corresponding Jupyter notebooks, which include inference and evaluation steps.
