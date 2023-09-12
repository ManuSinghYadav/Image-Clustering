# Image Clustering

This project focuses on clustering images into the following categories:

1. Cats or Dogs
2. Humans
3. Food

### Approach Taken

For this task, I have adopted the following approach:

1. **Feature Extraction**: I utilized a pre-trained Convolutional Neural Network (CNN) model, specifically **VGG16**, to extract meaningful features from the images. 

2. **Dimensionality Reduction**: To reduce the dimensionality of the feature vectors, I applied Principal Component Analysis (**PCA**).

3. **Determining Optimal Clusters**: Using the elbow method, I determined the optimal number of clusters for the image data.

4. **Clustering Algorithm**: Finally, I implemented image clustering using the **K-Means clustering** algorithm.

This project aims to group similar images into clusters based on their features, which can be valuable for various applications like image organization and content-based image retrieval.
