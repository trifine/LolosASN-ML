# MACHINE LEARNING

## Overview
The Machine Learning component of this application involves building a classification model using Neural Networks and a content-based news recommendation system utilizing NLP models. We employ BeautifulSoup for scraping news articles. The classification model provides feedback to users based on their test results, while the recommendation system suggests similar news articles based on NLP analysis.

## Dataset
1. **Classification Model**

We used the Mockaroo platform to create the dataset

2. **Recommendation System**

The dataset we use comes from CNBC, Kompas, CNN, Detik and Kompas.com. We collected article titles, news links, image links, and some content from the articles. To retrieve this dataset, we used the Beautiful Soup HTML parser method. 

## How to replicate our projects
### 01 Data Preprocessing

To run this model you need to follow these steps:

- Download the datasets [here][link-id]
- Upload the dataset in your notebook environment
- Install the required libraries
- Pre-process the data

### 02 Modelling

- Tokenize to vectorize the text corpus
- Build and compile the model with the architectures as mentioned [above](#model-architecture)
- Do a model evaluation
- Convert the model to `.h5` format
