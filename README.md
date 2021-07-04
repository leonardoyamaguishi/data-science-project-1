# A Data Science Interpretation On E-Commerce Revenue And Customer Experience
## A Decision Tree algorithm to interpret how Average Monthly Revenue and Customer Experience are related.

<br/>

### Installations: 
* [Python 3.9.1](https://www.python.org) [1]
* [Datetime](https://docs.python.org/3/library/datetime.html) [2]
* [Random](https://docs.python.org/3/library/random.html) [3]
* [Pandas](https://pandas.pydata.org) [4]
* [NumPy](https://numpy.org) [5]
* [Matplotlib](https://matplotlib.org) [6]
* [Seaborn](https://seaborn.pydata.org) [7]
* [Scikit-learn](https://scikit-learn.org/stable/) [8]
* [Jupyter Notebook](https://jupyter.org) [9]

<br/>

### Project Motivation:
From atmospheric fragrances to specific product placements, physical stores often rely on different strategies to enhance Customer Experience in order to increase Customer Loyalty, and thus revenue.

But, what about e-commerce? What are the most important drivers for the customer's buying decision? The seller's review scores? Comments related to shipping?

The objective of this study is to **train a Decision Tree algorithm and interpret its results to understand how the average monthly revenue of a seller can be related to its Customer Experience data**.

The hypothesis is that different Customer Experience characteristics could influence the revenue with different magnitudes. Ideally, a model such as this could assist in Customer Experience investment decisions in order to optimize the revenue.

The complete discussion of the results is available in my Medium post [here](https://leonardo-yamaguishi.medium.com/a-data-science-view-on-e-commerce-revenue-and-customer-experience-c416f15d3587) [12].

The data analysed in this post is the "Brazilian E-Commerce Public Dataset by Olist" [10]. A dataset from orders made at the Olist Store from 2016 to 2018 in different Brazilian marketplaces.

The dataset covers almost 100,000 orders from 3,095 sellers and provides data such as shipping dates, reviews and geographical data from sellers and customers. This analysis was focused on delivered orders.

The chosen inputs for the algorithm and the reason they were chosen:

* ***The ratio of shipments within the expected delivery date informed to the client:*** customers often refer to shipping deadlines in the comment section available to other (possible) clients;

* ***The average star rating of the seller:*** this information summarises product quality, shipping and service;

* ***If the seller offers products that belong to top selling categories:*** offering products from top selling categories indicates whether a seller has commonly desired products;

* ***The population density of the region in which the seller is located:*** [11] the hypothesis is that sellers located in regions with higher population densities are more likely to be closer to their customers, an interesting factor for customers that desire their products to be delivered faster;

### File Descriptions:

**asset:**  This folder contains plots from the modelling phase.

**data:** This folder contains the raw data and the processed data used for the Exploratory Analysis and Modelling.

**notebooks:** This folder contains the Jupyter Notebooks used for Data Preparation, Exploratory Analysis and Modelling.

### How to interact with this project:

By accessing the notebooks on the "notebooks" folder, it is possible to read and edit the code developed for this project. A brief description of the notebooks is available below:

***data_preparation:*** Notebook used for joining and filtering the datasets in order to obtain the final dataset used for the model.

***EDA:*** Exploratory Analysis of the selected data.

***modelling:*** Training, selection and interpretation of the models.

### References:

[1] PYTHON. Python. Disponível em: https://www.python.org. Acesso em: 04 jul. 2021.

[2] PYTHON. Datetime — Basic date and time types. Available in: https://docs.python.org/3/library/datetime.html. 

[3] PYTHON. Random — Generate pseudo-random numbers. Available in: https://docs.python.org/3/library/random.html. 

[4] PANDAS. Pandas. Available in: https://pandas.pydata.org. 

[5] NUMPY. NumPy. Available in: https://numpy.org. 

[6] MATPLOTLIB. Matplotlib. Available in: https://matplotlib.org. 

[7] SEABORN. Seaborn. Available in: https://seaborn.pydata.org. 

[8] SCIKIT-LEARN. Scikit-learn: machine learning in python. Machine Learning in Python. Available in: https://scikit-learn.org/stable/. 

[9] JUPYTER. Jupyter. Available in: https://jupyter.org. 

[10] OLIST. Brazilian E-Commerce Public Dataset by Olist. Available in: https://www.kaggle.com/olistbr/brazilian-ecommerce.

[11] INSTITUTO BRASILEIRO DE GEOGRAFIA E ESTATÍSTICA. Cidades e Estados. Available in: https://www.ibge.gov.br/cidades-e-estados.html?.

[12] YAMAGUISHI, Leonardo. A Data Science Interpretation On E-Commerce Revenue And Customer Experience. Available in: https://leonardo-yamaguishi.medium.com/a-data-science-view-on-e-commerce-revenue-and-customer-experience-c416f15d3587.
