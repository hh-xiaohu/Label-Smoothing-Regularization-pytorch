# Label-Smoothing-Regularization-pytorch
Label Smoothing Regularization implementation using pytorch.

Label smoothing is a mechanism to regularize the classifier layer and is called label-smoothing regularization (LSR). It is proposed to encourage the model to be less confident, since optimizing the log-likelihood of the correct label directly may cause overfitting and reduce the ability of the model to adapt. Label smoothing replaces the ground-truth label y with the weighted sum of itself and some fixed distribution μ. For class k, i.e.


