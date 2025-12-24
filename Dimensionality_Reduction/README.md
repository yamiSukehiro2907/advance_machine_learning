- In unsupervised there is no labeled data so it is difficult to work with

**Curse of dimensionality**: 
- With too many dimension it is hard to create model (too much computation)
- With less dimension it is easy to visualize and interpret the data

### After applying PCA we get exact same number of features with 100 % variance
### We decide the Principal component as features that are giving us the most of the data

### Loss of data with trade-off of important features

## Properties of Principal Component
- We get exact same number of features after PCA , we chose axes which gives us most of the data
- All PCs are orthogonal to each other

### Note: Direction of maximum variance can be found out by calculating the eigen vector

## EigenValue : 
- It tells us how much a matrix stretches or shrinks a direction
- This direction is called EigenVector, and they are principal components.
- det(A - lambda*I) = 0 (here A is the matrix and I is identity matrix , lambda is the eigen vector here)

## Explained Variance Ratio:
- It tells us how much of information we are receiving let's PC1 , PC2 , PC3 are principal components
- EVR = (PC1 + PC2) / (PC1 + PC2 + PC3) (the values used here are eigenvalues)

### It's hard to know the importance of each feature after PCA as the readability is lost