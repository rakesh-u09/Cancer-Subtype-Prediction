# Cancer-Subtype-Prediction


Cancer is caused as a result of unconstrained cell growth. It has several subtypes, 
identification of these subtypes in a quick and efficient manner is crucial in the treatment of 
cancer patients. In this project the TCGA RNA-Seq dataset is chosen for training the Deep 
Learning based CNN model to predict the subtypes of cancer. Several pre-processing methods 
such as handling missing data, feature selection and normalization are applied. The goal of 
cancer diagnosis is to classify tumors and identify indicators for each malignancy so that 
construct a learning system that can detect cancer early on.
In the field of cancer type prediction using gene expression data, various CNN 
(Convolutional Neural Network) models have been proposed. Each model is designed to tackle 
specific aspects related to modeling gene expression data and improving the accuracy of cancer 
type prediction 
The feature selection technique used is Recursive Feature Elimination, it helps select 
50 genes out of the available 20,531 genes. The gene data corresponding to each patient is 
stored in a NumPy array. The array is then used to create heat maps with the help of imshow() 
matplotlib function. The dataset contains 33 labels. The CNN model consists of 7 convolutional 
layers, each consisting of a kernel size of 3x3, 7 pooling layers, 7 batch normalization layers, 
2 dense layers and 1 dropout layer. ReLu is the activation function used for the layers. Softmax 
is the activation function used for the last dense layer. To avoid overfitting a dropout rate of 
0.15 is used. The model provides a test accuracy of 73.87%.
