For the second part of this project, we tackle an unsupervised problem concerning a customer segmentation problem. 
The dataset is from http://archive.ics.uci.edu/ml/datasets/Wholesale+customers.
 
Due to the length of the script, as a first step please run the command in line 36. 
The you can execute the hole code. 

A small index of the code:
1)	Initial we import the libraries and the dataset. (lines 1- 43)
2)	Plot the dataset and calculate the statistics. (lines 44- 127)
3)	Preprocessing the data and plot the same graphs for comparison (lines 128-224)
4)	 Clustering algorithms where (lines 225-798)
a.	DBSCAN (lines 233-336)
i.	Optimizing the Hyperparameters (lines 241-267)
ii.	Train the algorithm (lines 268-299)
iii.	Plot the results (lines 300-336)
b.	KMEANS (lines 336-488)
i.	Optimizing the Hyperparameters (lines 345-387)
ii.	Train the algorithm (optimal & comparison models) (lines 388-430)
iii.	Plot the results (lines 431-488)
c.	Gaussian Mixtures (lines 489-643)
i.	Optimizing the Hyperparameters (lines 489-536)
ii.	Train the algorithm (optimal & comparison models) (lines 537-582)
iii.	Plot the results (lines 583-643)
d.	Agglomerative Clustering (lines 644-774)
i.	Optimizing the Hyperparameters (lines 653-677)
ii.	Train the algorithm (optimal & comparison models) (lines 679-718)
iii.	Plot the results (lines 719-774)
5)	Fitting best model to the raw dataset (lines 775-798)