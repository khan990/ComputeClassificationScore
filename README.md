# ComputeClassificationScore
python module to compute machine learning classification score.

	ClassifierScore.py is python translation of code provided at
	http://www.mathworks.com/matlabcentral/fileexchange/37758-performance-measures-for-classification/content/Evaluate.m
	
	With changes only to return of function CalculateScore(), it can compute
	1. accuracy
	2. sensitivity
	3. specificity
	4. precision
	5. recall
	6. f_measure
	
	Note:
		Null value exception may arise while computing precision. Some changes are needed to be made to make it bug free.
		This function was tested with python 3. numpy, sklearn and collection packages required.
	
##Requirements
	1. numpy
	2. sklearn
	3. collection
