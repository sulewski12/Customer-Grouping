# Customer Segmentation

### Project description and motivation

Having a dataset of various information on credit card users and their tendencies in buying products, my objective was to develop a customer segmentation that will
help to define marketing strategy for the company.<br>
Tha dataset has around 9000 entries that summarizes the behaviour of credit card holders.<br>
In the project I go through various clustering techniques - K-Means, Gaussian Mixtures, Spectral Clustering, Autoencoders. With a help of all of them I come up with a most optimal
number of clusters, visualise them in 2D and 3D and offer a final customer segmentation.<br>
That's a real world data science task that helps to encounter the obstacles and challenges which companies are facing.<br>

![UI](https://github.com/sulewski12/Customer-Grouping/blob/main/cluster.png)

### Data description

The dataset I used was taken from https://www.kaggle.com/arjunbhasin2013/ccdata.<br>
It contains around 9000 entries divided between 18 columns.

### EDA, Model implementation and taken steps

A detailed explanation what steps I've taken throughout the project is included within the jupyter notebook.

### Further work and improvements

The only thing that stops me from modifications, improvements and testings of the new ideas on this project is my lack of time. As soon as I find some time, I'll get back to it. Here are some ideas:

- Implementing DBSCAN algorithm, it may bring some interesting and different insights from the ones we got from performing other algorithms.
- There's still a lot of room left for improvements and experiments in feature engineering. I did not create any new features that could help the models to perform better.
- Removing outliers found in the interquartile range.
- Adding "static" 3D visualisations. They're less impressive but more online-friendly, as the Plotly is not supported in many services.

### Helpful resources

While working on this project I found below mentioned sources very helpful:

- https://www.kaggle.com/roshansharma/mall-customers-clustering-analysis
- https://www.kaggle.com/datark1/customers-clustering-k-means-dbscan-and-ap
- Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow, II Edition, O'Reilly, Aurelien Geron, 2019

<i>November 2020, Paweł Sulewski</i>
