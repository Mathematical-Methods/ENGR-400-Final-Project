# ENGR-400-Final-Project
Hi, my name is Gabriel Dimonde!

NOTE: This repository is NOT a fully built project! This is intended as a preview of ability in Python applied in machine learning.

The ENGR 400 Final Project.ipynb file is the result of a class project of mine. The class was Practical Engineering Applications of Machine Learning. It seems like Github allows a preview of this document if you double-click it.
In it you will see my code, my comments, ChatGPT's code, how the autoencoders were built, their attempts at micrograph image reconstruction, transfer learning from the autoencoders, training of the image classifier, and their evaluations. 

Despite all of this, the resulting image classifiers were no better than a Dummy Classifier that choose the most common class...yay failure! 

In hindsight, the image information was bottlenecked too much in both autoencoders. There was no way to describe a high carbon steel micrograph with the amount of numbers (size of latent space vector) I tried to use. If I were to work on this again, then I would train the autoencoders with a different size latent space vector and subsequently try to use T-SNE (T-distributed stochastic neighbor embedding) to evaluate how far apart or different the classes are from one another. This would help to decide if the autoencoder needs to be changed. 

too long; didn't read:
I think I know what to do now. 

Here are some image comparisons of the autoencoder reconstructions: