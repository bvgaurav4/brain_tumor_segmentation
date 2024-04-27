dataset if from BrsTS 19

https://www.kaggle.com/datasets/aryashah2k/brain-tumor-segmentation-brats-2019

Method 1:
We take the MRI scans and segment it using SLIC (Simple linear Image clustering)
then we label the regions or the segments which are infected or where the tumors are 
present.
unlabeled
Labeled segments:
12 | P a g e
Now we convert this into a graph where the segments are the nodes and the edges are 
present if he segments are in contact with each other the edges are weighted the weights 
are the contact length between the segments, the nodes have features like area, intensity 
and labels if they are infected.
13 | P a g e
Now by sending this to the model (GAT), the models tries to learn the graph substructure 
where the tumors are present .
