<html>
<head>
  </head>
<body>
  <h1> Dimensionality Reduction
  </h1>
  <h2> --Laplacian eigenmaps
  </h2>
  <p> High-dimensional data is difficult to interpret. One approach to simplification is to assume that the data lie on an embedded non-linear manifold. If the manifold is of low enough dimension, the data can be visualized in the low-dimensional space.Laplacian eigenmaps uses spectral techniques to perform dimensionality reduction. It builds a graph from neighborhood information of the data set. Each data points serves as a node on the graph and connectivity between nodes is governed by the proximity of neighboring points. The graph thus generated can be considered as a discrete approximation of the low-dimensional manifold on the high-dimensional space. 
  </p>
  <h2> Method Introduction </h2>
Step 1 Calculate the distance between data points. <br>
Step 2 Connect neighboring points by n nearest neighbors.<br>
Step 3 Adjacency matrix(A), degree matrix(D), laplacian matrix(L=D-A) <br>
Step 4 Compute eigenvalues and eigenvectors for the generalized eigenvector problem Lf=λDf <br>
Step 5 Use the eigenvectors for embedding <br>

<h2> 3D example </h2>
