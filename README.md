# PCA on MNIST Dataset - Parallelization approach
 I am using parallelization approach like multithreading while working on the dataset for PCA
The dataset is of an image and is a high dimensional dataset since images contains pixel values in the form of matrix. 

There are 60,000 samples for training and 10,000 for testing. 

Each image here is of 28*28 pixels which is flattened to 784 dimensions. 

Our target variable here is a categorical variable with 10 classes labelled 0 to 9. 

Since the images were in gray scale, I converted it into binary by normalizing(i.e., dividing it by 255. Gray scale image pixel value = 0 to 255). 

Principal Component Analysis allows us to get the essence of larger datasets by transforming them into small datasets by using statistical measures, allowing us to easily visualize and analyze the data and at the same time, minimizing the information loss. 

 

Along with high dimensionality, our images contain lot of patterns. PCA helps in retaining such patterns and improves the computational speed by reducing the dimensions. 
I used a simple neural network model for our architecture with which we used 6 layers where 3 layers for dense and 3 layers for dropout. 
got an accuracy of 98% 
