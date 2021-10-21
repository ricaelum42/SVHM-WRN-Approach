# SVHM WRN With Keras

This is an in-class Kaggle Competition. 

SVHN is a real-world image dataset for developing machine learning and object recognition algorithms with minimal requirement on data preprocessing and formatting. It can be seen as similar in flavor to MNIST (e.g., the images are of small cropped digits), but incorporates an order of magnitude more labeled data (over 600,000 digit images) and comes from a significantly harder, unsolved, real world problem (recognizing digits and numbers in natural scene images). SVHN is obtained from house numbers in Google Street View images.

http://ufldl.stanford.edu/housenumbers/

The goal is to, much in the style of MNIST, classify the main digit that appears in the photo. As such there are 10 classes, 1 for each digit. Digit '1' has label 1, '9' has label 9 and '0' has label 10.

The best model is wide-residual network. Achieved 0.972 accuracy in the public leaderboard and 0.971 accuracy in the private leaderboard. Ranked #1 in class.
