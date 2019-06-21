### What is image classification really?


#### INTRODUCTION

If you're thinking of building vision systems in the future which can work with the same precision with that of humans,
then this tutorial session can help you get started.

This workflow of this session is as follows:

1. An abstract explanation of What/Why/When is Deep learning.
2. Formulating our vision problem
3. Finding, labelling and cleaning data
4. Picking framework and computer infrastructure
5. Troubleshooting training and ensuring reproducibility
6. Evaluating final model


Welcome to the start of your computer vision journey, probably! In today’s session you’ll set up your deep learning architecture,
and train your first image classification model (a convolutional neural network, or CNN), which will learn to distinguish dogs from cats. 

We learn today how to classify dogs from cats. Rather than understanding the mathematical details of how this works, we start by learning the nuts and bolts of how to get the computer to complete the task. We will also cover aspect of deep learning such as transfer learning and also use a technique called ‘fine-tuning’ using pre-trained networks, perhaps the most important skill for any deep learning practitioner


#### Dataset structure

The dataset is strucuted in the following format:

```
dataset/
            train/
                  cat0.jpg
                  dog1.jpg
                  cat23.jpg
                  ....
                  
            test/
                  cat34.jpg
                  dog14.jpg
                  cat56.jpg
                  ....       
```
