# Tensorflow Notebooks
## Tipps/Feedbacks
- [ ] The roles of the various layers in a convnet: https://ujjwalkarn.me/2016/08/11/intuitive-explanation-convnets/
- [ ] Weight init: http://cs231n.github.io/neural-networks-2/#init
- [ ] Note that you can interchange the max pooling and nonlinear layer (as long as the nonlinear activation function is an increasing function, you can try to prove this mathematically). If the max pooling is applied before the nonlinear activation, the number of nonlinear activation function reduces, so this should give you some speed up!
- [ ] Convolutional networks with multiple convolutional layers with increasing depth (e.g. 32, 64, 128), a small convolutional filter (3x3) and stride (1x1) , small max pooling size (2x2) and stride (2x2) usually work best. Be sure to check out http://cs231n.github.io/convolutional-networks/#architectures for a detailed discussion of and tips for building convolutional network architectures.
- [ ] See if your network performs better if you replace the nonlinear activation by tf.nn.elu. Check out this paper for more details https://arxiv.org/abs/1511.07289
