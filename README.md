# Cryptocurrencies

**Overview of the Project**
For this project, Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. So, they’ve asked me to create a report that includes the cryptocurrencies currently on the trading market and how they could be grouped to create a classification system for the new investment.

Our data for this analysis is not ideal, so it will need to be processed to fit the machine learning models. Since there is no known output for what we are looking for, it is decided to use unsupervised learning. To group the cryptocurrencies, we decided on a clustering algorithm. We’ll use data visualizations to share relevant findings with the board of Accountability Accounting.

**Results: Four Deliverables**

- Deliverable 1: Process the Data for PCA
I preprocessed the dataset in order to perform PCA in Deliverable 2 and used the get_dummies() method to create variables for the text features, and then stored in a new DataFrame.

![Crypto_1](https://github.com/FUNMIIB/Cryptocurrencies/blob/main/Crypto_1.png)


- Deliverable 2: Reducing Data Dimensions Using PCA
I reduced the dimensions of the X DataFrame to three principal components and place these dimensions in a new DataFrame.

![Crypto_2](https://github.com/FUNMIIB/Cryptocurrencies/blob/main/Crypto_2.png)

- Deliverable 3: Clustering Cryptocurrencies Using K-means
I created an elbow curve using hvPlot to find the best value for K from the DataFrame created in Deliverable 2. Then, I ran the K-means algorithm to predict the K clusters for the cryptocurrencies’ data.

![Cryto_3](https://github.com/FUNMIIB/Cryptocurrencies/blob/main/Crypto_3.png)

- Deliverable 4: Visualizing Cryptocurrencies Results 
I used Plotly Express and hvplot to visualize the distinct groups that correspond to the three principal components I created in Deliverable 2, and then created a table with all the currently tradable cryptocurrencies using the hvplot.table() function.

![Crpto_4](https://github.com/FUNMIIB/Cryptocurrencies/blob/main/Crypto_4.png)

