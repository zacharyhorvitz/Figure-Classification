# Figure-Classification
Caffe Deep Learning for Scientific Figure Classification

This repository contains 2 directories, one for a binary (line vs. all other types) classification, and one for a 7 category classification.

To run, take the following ec2 instance image:

https://us-west-2.console.aws.amazon.com/ec2/v2/home?region=us-west-2#LaunchInstanceWizard:

Delete the caffe directory, and add the one provided bellow.
Steps for running the net can be found in the following links.
If you want to see the current status/train the net, you can just run resume_training.sh in the zachrun directory from the home directory. Make sure it points to the correct solverstate.



INSTALLATION: http://caffe.berkeleyvision.org/installation.html
CONFIGURATION TUTORIAL: http://caffe.berkeleyvision.org/gathered/examples/imagenet.html

The net is a convolutional neural net (CNN) based on the 2012 Nips Paper by Krizhevsky et al. 


TO DO:
-In the process of adding the caffe home directories.