# SVM-classifier-wine-dataset

We need to construct an SVM classifier to classify data from Wine Dataset; Our main target is to try to classify Wine's Quality based on the inputs. Please download the dataset from this link (The dataset is originally from UCI: https://archive.ics.uci.edu/ml/datasets/wine+quality)
a. Load Wine dataset and discover its parameters, you may need to normalize data
if it improves your results.
Then use SVM in Sklearn library to classify Wine quality, vary the hyperparameters as follows: Use Kernels of RBF, Linear, and Poly. Use the regularization parameter "C"
as [1,10,50,100] for RBF and Poly, and [1,10,20,30] for Linear Kernel. Add results to a table.
b. Explain your findings of the results from Part a.
-
c. Modify your best kernel model to find a better performing model by changing hyperparameters "C and Gamma" by trying at least 10 different combinations and record results in a table. Comment briefly on your findings.
