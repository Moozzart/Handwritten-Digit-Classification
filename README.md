# Handwritten-Digit-Classification
1) Download the MNIST handwritten digit dataset. It contains 28X28 images. Flatten them into 784-dimensional binary vectors. Keep aside 20% data for testing and another 20% for validation.                                                                 

2) Now, draw a random subset of 10 dimensions (out of 784). Based on these 10 dimensions only, build a decision tree (using library function). Maximum depth allowed: 5. Calculate accuracy of the tree on validation set.                     

3) Repeat this process for 50 random subsets like this, each of dimension 10.For each of them, build a decision tree of max. depth 5. Calculate accuracy on validation set.   

4) Carry out weighted classification of the test set using these 50 decision trees, along with their validation accuracies as weights. Report the accuracy.     

5) Starting with this ensemble as the initial classifier, implement Adaboost algorithm. At each stage, build a decision tree using entropy based on weighted examples as the heterogeneity measure of each node. Each tree will have maximum depth of 5. Maximum 20 iterations of Adaboost.

6) Using this ensemble, carry out classification on the test set and report accuracy 
