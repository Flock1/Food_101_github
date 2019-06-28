Both, the codes run on food 101 dataset using ResNet50 CNN however, I have used two different techniques of transfer learning

## 1) fine tuning

## 2) feature extraction

# Fine Tuning:

I used the all the pre-trained layers of ResNet50 and I created a convolution layer as the final layer and trained it. 

Even though I achieved 70% accuracy while training, test results weren't as good. I tried various methods including training from sctrach, using fully connected layer instead of convokution layer, different learing rates.

# Feature Extraction:

In this method, I used the CNN to get the features of the the images and stored them in a csv file (file is in GBs, so I couldn't add it to the repo)

Those features were used to train a regression model and predict the classes. The regression model is attached as a `cpickle` file


