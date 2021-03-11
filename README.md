# Project Introdiction

E-commerce is playing a major role to market and advertise products all over the world, even in countries in
development, as China, Brazil, Mexico among others. It is interesting to analyze e-commerce in such countries.
Brazil currently knows an exponentially growth and the online market expects a penetration of 94 million users.
Hence, Brazil is going to know a rapid e-commerce expansion.
Olist, the largest department store in Brazilian marketplaces, connects small businesses from all over Brazil
and provides a large amount of data concerning the products, the customers, the sellers, the orders and the
reviews around the business.
On another hand, users, reviews are crucial for any business to survive in the e-commerce market. It allows
to control the products’ reputation and to promote the good rated products, by so increase the sales, the
engagement and the rankings. It also serves to develop trust and loyalty to the business. A survey showed that
72% of people had a good opinion about a product if it was good rated.
Regarding the large amount of data provided by the e-commerce industry, this project aims to analyse the
sentiments of customers in text reviews and to predict the future monthly sales amount of products.

# Description of the files in the folder

The Folder "Data" contains the data downloaded in Kaggle at 
https://www.kaggle.com/olistbr/brazilian-ecommerce.
The notebooks .ipynb are the different parts of the project:
- DataManagement.ipynb is the notebook that manages the data.
The outputs of this notebook are the file "data.csv" which is
the cleaned data with all the attributes and "data_sq_cross.csv"
which is the cleaned data with all the attributes plus the 
squared and cross products of attributes
- DescrStats.ipynb is the notebook that deals with descripive 
statistiques
- Lasso.ipynb performs the Lasso method
- NLP_Kmeans.ipynb performs the sentiment analysis using 
Word2Vec and K-means.
- NN_RNN.ipynb performs the neural networks to predict the 
sales amount.