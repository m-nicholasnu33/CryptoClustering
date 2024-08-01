# CryptoClustering

### This Challenge project utilizes the K-means algorithm and Principle Components Analysis (PCA) to classify crypto currencies according to their price fluctionations across the following time frames:
* 24 hours
* 7 days
* 30 days
* 60 days
* 200 days
* 1 year

### The challenge employs the StandardScaler() module from scikit-learn to normalize the data from the CSV file, ultimately allowing for the data to be analyzed to create clusters to draw insights
### Additionally, the challenge utilizes performance of Principle Component Analysis (PCA), also contributing to cluster analysis for evaluation of the data

### In both instances of using scaled data and PCA, the utilization of K-Means to create elbow plots provides evidence that 4 clusters is optimal within each method.

### It is determined that using 3 principle components allows for an explained variance of 89.5%.

### Scatter Plots ultimately allow for the visual evaluation of the data to evaluate the clean separations.

### Evaluation of the weights of each feature of the PCA analysis allows for identification of the features providing the most influence ont he analysis.

### Note that I completed all work in this challenge without requiring outside assistance...