<h1>Fraud detection on Credit Card Transactions dataset</h1>
Unsupervised learning is often a preferred method in fraud detection because it allows the model to identify patterns and anomalies in the data without prior knowledge or labels. Supervised learning, on the other hand, requires labeled data which can be difficult to obtain in the context of fraud detection where the instances of fraud are rare and often go undetected. In unsupervised learning, the algorithm is able to learn the normal patterns of behavior and transactions, and then identify instances that deviate from these patterns as potential fraud. This approach can be more effective in detecting new and unseen types of fraud, as well as in handling imbalanced datasets where the number of non-fraud instances far outweighs the number of fraud instances. Additionally, unsupervised learning can be less prone to biases present in the labeled data, making the results more trustworthy and reliable.
And this is why I made this notebook to show to implement autoencoder model to detect fraud and compare the results with another unsupervised learning model "isolation forest".
<h1>Setup and Requirements</h1>

**Clone this repository:**
```
$ git clone https://github.com/achrafbalij/fraud_detection.git
```
**install requirements:**
```
pip install -r requirements.txt
```

<h1>Data</h1>
The Dataset used is a kaggle dataset "Credit Card Transactions Fraud Detection Dataset". It contains a simulated credit card transaction dataset containing legitimate and fraud transactions from the duration 1st Jan 2019 - 31st Dec 2020. It covers credit cards of 1000 customers doing transactions with a pool of 800 merchants.

You can find the dataset on: "https://www.kaggle.com/datasets/kartik2112/fraud-detection"
