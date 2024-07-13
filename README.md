# Self-Organizing-Maps
<br>
<br>
Self-Organizing Maps (SOM) are a type of artificial neural network used for unsupervised learning. Introduced by Teuvo Kohonen in the 1980s, SOMs are primarily used for dimensionality reduction and data visualization. They map high-dimensional data into a lower-dimensional (usually two-dimensional) grid, preserving the topological relationships of the data.
<br>
<br>
steps:
<br>
<br>
Initialization: Nodes (neurons) in the SOM are initialized with random weight vectors.
<br>
<br>
Training:
---Competition: For each input vector, find the best matching unit (BMU), the neuron whose weight vector is closest to the input vector.
<br>
---Cooperation: Update the BMU and its neighboring neurons to become more like the input vector. The neighborhood function determines the extent of this update.
<br>
<br>
Adaptation: The learning rate and neighborhood radius decrease over time.
<br>
<br>
Convergence: The map converges when the updates become negligible, meaning the weights stabilize.
