# Linear and Non-Linear Dimensionality Reduction Techniques


### Steps to run the project
- Create a new python virtual env
- Install requirements required to run the code 
`pip install -r requirements.txt`
- Run the .ipynb notebook files

### Reports
- Report folder contains both Linear and Non-Linear Dimensionality Reduction Techniques 
- Linear Dimensionality Reduction with Principal Component Analysis (PCA) `pca.pdf`
- Non-Linear Dimensionality Reduction with Autoencoders `autoencoders.pdf`

### Linear Dimensionality Reduction with Principal Component Analysis (PCA)
- PCA essentially learns a linear transformation that projects the data into another space
- This project aims to understand the PCA technique in depth
- PCA is coded from scratch and various plots are used to visualize the results
- IIIT-CFW dataset of 8 celeberities each containing 100 face smaples is used
- The dimension of face image is 32 * 32 * 3
- Ploted eigen spectrum for the data.
- Plotted % of variance preserved vs principal components used
- Compared the results of using the data with and without PCA on linear regression.


### Non-Linear Dimensionality Reduction with Autoencoders
- CIFAR 10 is used as the dataset from this project
- 3 models of autoencoders are developed using pytorch
  - encoder and decoder is fully connected layers - Autoencoder1
  - encoder and decoder is combination of convolution layers + fully connected layers - Autoencoder2
  - encoder and decoder is fully convolutional layers - Autoencoder3
- Performance of these 3 models is evaluated and compared against each other
- A detail comparision is made between PCA and Autoencoders