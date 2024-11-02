First Loads the data and confirms that the raw dataset has 49 columns Next the VarianceThresholds is applied to the raw dataset with values from 0.0 to 0.5 and the number of remaning features after the transform is applied
are reported. We can see that the number of features in the dataset quickly drops from the unchanged data down to 35 with a threshold of 0.15 .It later drops to 31(18 columns deleted) with a threshold 0f 0.5.A line plot is then
created showing the relationship between the threshold and the number of features in the transformed dataset. we can see that even with a small threshold between 0.15 and 0.4 that a larg number of features(14) are 
removed immediately.
