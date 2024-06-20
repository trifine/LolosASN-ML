# MACHINE LEARNING

## Overview
The Machine Learning component of this application involves building a classification model using Neural Networks and a content-based news recommendation system utilizing NLP models. We employ BeautifulSoup for scraping news articles. The classification model provides feedback to users based on their test results, while the recommendation system suggests similar news articles based on NLP analysis.

## Dataset
1. **Classification Model**

   We used the Mockaroo platform to create the dataset.

2. **Recommendation System**

   The dataset we use comes from CNBC, Kompas, CNN, Detik and Kompas.com. We collected article titles, news links, image links, and some content from the articles. To retrieve this dataset, we used the BeautifulSoup HTML parser method.

## How to replicate our projects

### Classification Model
To run the classification model, follow these steps:
1. Download the dataset [here](https://github.com/trifine/LolosASN-ML/tree/main/Model%201_Classification/CSV).
2. Upload the dataset in your notebook environment.
3. Install the required libraries.
4. Build and compile the model.
5. Evaluate the model.
6. Convert the model to `.h5` format.

### Recommender System
To run the recommender model, follow these steps:
1. Download the dataset [here](https://github.com/trifine/LolosASN-ML/tree/main/Model%202_Recommender%20Berita/Gathered%20data).
2. Upload the dataset in your notebook environment.
3. Install the required libraries.
4. Tokenize the text corpus to vectorize it.
5. Download GloVe embeddings [here](https://drive.google.com/file/d/11dwk23vdy4smHXUE0QVTFdT1DEWZh-P7/view?usp=drive_link).
6. Build and compile the model.
7. Evaluate the model.
8. Convert the model to `.h5` format.

