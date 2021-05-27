# GoogLeNet-CNN-model-for-image-classification

## Model
The model is based on inception blocks according to the GoogLeNet paper. Many inception blocks are stacked up and trained using GPUs on SVHN dataset on various activation functions such as:
1. tanh
2. ReLu
3. Leaky ReLU

The performance is logged to compare them. The model is saved and then loaded again to finetune the model to train on CIFAR 10 dataset with above mentioned activation functions and the perfromance is logged again to compare them.
