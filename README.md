# WaterQuality
idk who created the dataset, it has many missing value.
here what im doing in this repo
1. because disolv column have a lot missing value i divide it to two way. fiest is i cluster with k-means with droping disolved and second impute the missing value in it with linear regression
2. Result of droping dissoled i got siloute score 0.2899 with 3 cluster which is good
3. Result with imputation if you see the PCA the blue dots is in green area (third cluster) even the score is good
4. so yeah the end dropiing disolved is the good way whichh first cluster is bad water, second is average water, and third cluser are good 
