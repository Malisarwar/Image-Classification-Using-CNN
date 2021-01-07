## Transfer Learning using keras Library
This repository shows how we can use transfer learning in keras with the example of training 6 classes using classification model which is ResNet style Architecture’s pre-trained weights. The ResNet is CNN models trained on huge datasets of images of different categories.

Transfer Learning is a common method in deep learning which pre-trained frameworks are used as an initial point of departure for image 
processing and also the speech recognition challenges, considering the massive computational and currently spends needed to construct algorithms on such concerns.

### Why Transfer Learning?

If you just have inadequate knowledge to manage a new domain through a specific neural network and you'll have a wide preexisting datapool that can also be adapted to your query, then the transfer learning is useful. 
You can only have 1K images, but you can learn a great many low and 
Midlevel concepts by tapping into current CNN, like ResNet, qualified in more than 1 million images.

### Fine Tuning:

If the algorithm has merged on fresh data, you will attempt to unfreeze each and part of the base model and recruit ’s entire end to
end system at a very low learning rate.That was necessary to do the same following the stabilization of the model by frozen layers.When you combine spontaneously training layers with training layers who carry pre-trained features, completely at random layers can trigger very wide elevation improvements throughout training, which could kill the pre-trained functionalities. Then it comes fine tuning of system.

In this code, I have done test of transfer learning. After reading Test data I have finding out Stochastic Gradient Decent with learning rate, apply ResNet with transfer learning to classification the image dataset.

## DataSet
While uploading data, i am facing issues. Later on I'll upload data


