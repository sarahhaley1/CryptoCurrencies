# CryptoCurrencies
Unsupervised Machine Learning
  - packages used: Pandas, path, plotly, and scikit learn

## OverView of CryptoCurrencies Analysis
### Background 
A prominent investment bank client for the Accountability Accounting Advisory Services Team is interested in oddering a new cryptocurrency investment portfolio for its customers. This analysis is to create a report for the investment bank regarding the different cyrptocurrency methods available to them and what would be the most beneficial form of currency to add. 
Steps:
1. Preprocess database
2. Reduce Dimension with Principal Component Analysis
3. Cluster using K-means
4. Visualization of Classification results in scatterplot

### Purpose
Using unsupervised leanrning, through clustering, this analysis prepares a layout of information on cryptocurrencies for those who are looking to join the cryptocurrency market. Through classification this analysis includes what cryptocurrencies are on the trading market and how they further could be classified into groups for the new investment plan. The data needs to be cleaned and classified in order to fit the machine learning models and the fact that there is no output to go off of, undupervised learning is the process for classification. 

### Results
In the analysis there is a frame produced of the different cryptocurrencies that are tradeable for the investment bank. There is need for further investigation, as this is an unsupervised method. The conclusions we came to are that there are 532 tradable crypto currencies. 
elbowCurve.png![image](https://user-images.githubusercontent.com/66536405/113926833-8ca3b580-97a1-11eb-99b0-6d762e1291bb.png)
This result shows that the best k means result is where n=4 based on the elbow in the curve.
3DPCA.png![image](https://user-images.githubusercontent.com/66536405/113926852-92010000-97a1-11eb-814c-3b02aec30bec.png)
3-D scatter plot from reduction of dimensions to 3 PCs
1DPCA.png![image](https://user-images.githubusercontent.com/66536405/113926865-94fbf080-97a1-11eb-8f93-db9018fe7c0f.png)
1-D scatter plot from reduction of dimensions to 2 PCs


### Summary
In this analysis there were 532 tradeable cryptocurrencies identified. To determine the performance for the Bank's investors, there would need to be further analysis done within the found clusters. 
