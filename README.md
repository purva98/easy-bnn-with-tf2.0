# easy-bnn-with-tf2.0
Here I put some implementations of Bayesian Neural Networks using Keras, TensorFlow Probability and TensorFlow 2.0. It is being used as a personal repo for me to learn about htis wonderful theme. 

### First of all, the TF and TFP versions for my implementation:
As TensorFlow Perobability is having some issues on gathering gradients on neural networks, and I had a lot of work in searching for a solution, I'm putting it here for if you want to reproduce this code. On the GitHub issue, I was told to use the TensorFlow Proability Nightly version, as this one had no gradient issue for this use case.

So, for it to be easier, use TFP in this exact version, and TF 2.0 if you want to use Gradient Tape and @tf.function

Also I documented the code for each TF version, so we can see differences.

#### TensorFlow version: 2.0.0-beta1


#### TensorFlow Probability version: 0.9.0-dev20190912


I also implemented a model optimized in "raw TensorFlow 1.14", and compared its performance with TF 2.0. I saved the notebooks in html for anyone to see. The first epoch of TF2 on training is longer (maybe due to variable and graph initializations"), but after that, it has a 10% faster e a standard deviation 80% smaller than TF 1.14. 

Even though I did implement my model independently, I must give credit to zhulingchen GitHub user, as he made and excelent tutorial, without the one I wouldn't be able to implement my humble model. 


By the way, here is the link for his repository: https://github.com/zhulingchen/tfp-tutorial

#### Todo: illustrate decision process from probabilistic Neural Net sampling
