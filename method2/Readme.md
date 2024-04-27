MEthod 2 

In this Method we take the images of the brain scans and then converts the 
images into graphs where each pixel is a node and its adjacent 8 node are 
connected to it.
On to this graph v take the adjacency Matrix and perform Graph 
convolution operation like Neighborhood Aggregation, Feature Transformation.
Then this matrix is sent to a CNN model with 26 layers which trained for 10 
epochs

dataset
https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri