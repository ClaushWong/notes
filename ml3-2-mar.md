# k-Nearest Neighbors (KNN)

- Simplest machine learning algorithm
- Build a model consists only for storing the training dataset
- Make prediction through find the closest data points in the training dataset
- Lazy learner
- Used in statistical estimation and pattern recognition already in beginning of 1970's 

- simplese version (k=1), kNN algo only considers exactly one nearest neighbor
- kNN algo itself is fairly straightfoward and can be summarized by the following steps:
> 1. Choose number of k and a distance metric
> 2. Find the k-nearest neighbors of the sample that we want to clasify
> 3. Assign the class label by majority vote `when k > 1`

- kNN Algorithm
- ![knn-1](https://cdn.discordapp.com/attachments/346967448781717505/683847093764358153/unknown.png)
- ![knn-2](https://cdn.discordapp.com/attachments/346967448781717505/683847147539398665/unknown.png)
- ![knn-3](https://cdn.discordapp.com/attachments/346967448781717505/683847189071790247/unknown.png)
- ![knn-4](https://cdn.discordapp.com/attachments/346967448781717505/683847227273379846/unknown.png)

- 2 variables need to be determined
> 1. Value of `k`
> 2. Distance measures algorithm `Euclidean, Manhattan, Minkowski`
- model is easy to understand and often gives reasonable performance whthout a lot of adjustment

- Example (Loan application)
- Features : Age, Loan
- Target : Default

- ![data](https://cdn.discordapp.com/attachments/346967448781717505/683849202102435858/unknown.png)

- Q: Classify an unknown case (Age: 48, Loan: 142,000) using Euclidean distance

- If `k=1`, then the nearest neighbor is the last case in the training set with `Default=Y`
- `D = sqrt((48-33)^2 + (142000-150000)^2) = 8000.01 >> Default= Y`
- With `k=3' there are 2 `Default=Y` and 1 `Default=N` out of three closest neighbors. 
- Prediction for the unknown case is again `Default=Y`

- More data, more time is consumed for calculating all the kNN
- More data, more storage needed because there is no so-called `training-process` so all the data cannot be discard
- More features, more complexity the calculation it will be

- Example of code
`from sklearn.neighbors import kNeighborsClassifier

knn = kNeighborsClassifier(n_neighbors=5,p=2,metric='minkowski')

knn.fit(X_train_std,y_train)

plot_decision_regions(X_combined_std, y_combined,classifier=knn, test_idx=range(105,150))

plt.xlabel(‘petal length [standardized]’)

plt.ylabel(‘petal width [standardized]’)

plt.legend(loc=‘upper left’)

plt.show() 
`
