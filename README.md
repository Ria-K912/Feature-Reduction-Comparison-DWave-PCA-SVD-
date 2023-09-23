# Feature-Reduction-Comparison-DWave-PCA-SVD-
In this repositiory, I have used four different datasets - ECG Heart Disease Datatset, Air Pollution Dataset, Secom Dataset and Road Accidient Dataset.
I have used classical algorithms like PCA and SVD  to reduce the number of features in each of the dataset and see how much variance of the data is captured by the reduced number of features
Then, I applied the new Hybrid Solver Plug-In Feature Selection of D-Wave and made a comparison of the variance of data captured by the reduced number of features using PCA, SVD and D-Wave Plug-In Feature Selection
It has been evidient across all the four datasets that D-Wave performs better than the classical algorithms when the reduced number of features are from 1 to 3 (or4)
