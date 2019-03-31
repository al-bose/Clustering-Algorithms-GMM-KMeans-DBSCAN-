Environment required:
Python 3 -- Anaconda 4.3.0 (64-bit)

For each dataset, it contains 3 columns, with the format: x1 \t x2 \t cluster_label. You need to use the first two columns for clustering, and the last column for evaluation.


Information about code files:

*DataPoints.py
	Helper class/functions.
	
*KMeans.py
	1. The file prints results from the algorithm run on all three datasets.
	2. Points with cluster labels are stored in KMeans.csv (currently stores the result of dataset 3; change the last dataset run for other dataset results).
		
*DBSCAN.py
	1. The file prints results from the algorithm run on all three datasets.
	2. Points with cluster labels are stored in DBSCAN_dataset3.csv (currently stores the result of dataset 3; change the last dataset run for other dataset results).

*GMM.py
	1. The file prints results from the algorithm run on all three datasets.
	2. Points with cluster labels are stored in GMM.csv (currently stores the result of dataset 3; change the last dataset run for other dataset results).
