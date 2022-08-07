# Cryptocurrencies
BootCamp Week 18. Unsupervised Machine Learning 

# Overview
Cryptocurrencies is a trending market and its very easy to get confused among all the different options that the market have. In this project, we were asked to create a report about all the cryptocurrencies are on the trading market and how could be grouped in a more understandable to a potential clients. Since we don´t have a known output, I will use Unsupervised Machine Learning to group the cryptocurrencies using a clustering K-means algorithm and data visualization to show the results. 

  The steps to process this data were:
  
        1. Preprocess the data to get it able to ML Analysis. 
        2. Reducing data dimensions using PCA (Personal Component Analysis).  
        3. Clustering data using K-means Algorithm
        4. Visualizing Results.

# Results
From the original 1,253 cryptocurrencies in the original data file, after the filtering process we worked with only 532 cryptos. Then I reduced data dimensions  to three principal components and I created a new DataFrame. In the next deliverable I plot an Elbow Curve using to find the best value for clustering groups. After that,in order to prepare the data for the clustering process.
 
### *Elbow Curve*
<img width="775" alt="Elbow Curve" src="https://user-images.githubusercontent.com/102195803/183267892-207eec93-db2d-4957-afa9-f694ca1c7817.png">

### *Clustered DataFrame*
<img width="755" alt="Clustered DataFrame" src="https://user-images.githubusercontent.com/102195803/183267899-aa59fd0b-c4a5-4dc6-bdf9-225385f6c2d4.png">

# *Visualization Data

### *3-D PCA by Clusters plots*
<img width="450" alt="3D plot" src="https://user-images.githubusercontent.com/102195803/183267788-507b0828-5afd-45b2-bde4-0362f893940f.png">

### *Tradable Cryptocurrencies*
<img width="550" alt="Tradable crytocurrencies table" src="https://user-images.githubusercontent.com/102195803/183267820-8e3e2591-b45f-4b5d-9b8f-af47bb67c279.png">

### *Scatter plot with the "TotalCoinsMined" vs "TotalCoinsSupply" grouped by cluster*
<img width="660" alt="Scatter plot" src="https://user-images.githubusercontent.com/102195803/183267843-d0a31788-84b3-4afa-ad58-7cc018cb8940.png">
