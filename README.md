# Feature-Reduction-Comparison-DWave-PCA-SVD-
In this repository, I have used four datasets - ECG Heart Disease Dataset, Air Pollution Dataset, Secom Dataset, and Road Accident Dataset.
I have used classical algorithms like PCA and SVD  to reduce the number of features in each of the datasets and see how much variance of the data is captured by the reduced number of features.
Then, I applied the new Hybrid Solver Plug-In Feature Selection of D-Wave and made a comparison of the variance of data captured by the reduced number of features using PCA, SVD, and D-Wave Plug-In Feature Selection.
It has been evident across all four datasets that D-Wave performs better than the classical algorithms when the reduced number of features is from 1 to 3 (or4).
