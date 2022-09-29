# Recognition of human activity from
smartphone sensor signals, given that the smartphone is on the person.
This is a masters course work for Applied Data Science and this was performed against an unknown dataset provided by module professor
As said before the context of dataset is unknown. The data preprocessing steps like checking null values, checking for data balance, outliers and it turns out the dataset has dataset imbalance and has lot of outliers. Though the dataset was balanced using up sampling but didnt remove outliers considering the situation of not knowing about dataset and also outliers doesnt mean that they are wrong data. So, considering all these outliers were not removed.
Then feature selection(mutual information) and feature extraction(principal component analysis (pca)) and trained using svm,knn and decision trees. The results between feature selection and feature extraction seems to be almost same and all models predicted an overall accuracy of atleast 95%.
