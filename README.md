# Convolutional neural network for identification of musical instruments.
<img src="https://github.com/misiungs/readme_images/blob/master/rockband.jpg?raw=true" alt="drawing" width="500"/>

# Problem
The goal of the project is to build a model that will be able to classify musical instruments.
A created model should be able to identify an instrument just by looking at a picture.
Five intruments that are typical for a rock band are here considered: drums, guitar, keyboard, microphone and saxophone.

# Approach
First, web scrapper based on selenium is used to gather data from internet.
In total 4845 images is gathered.
After the dataset preparation modeling is done.
Images are augmented to increase model generalization.
For classification VGG19 architecture is utilized.
Training is done without and with transfer learning.


# Conclusions
With transfer learning accuracy of 91.5% has been achieved which is a satisfying result.
To further boost accuracy the size of a training set should be increased.