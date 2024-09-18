# Anime Recommendation System

## Motivation:

As an avid anime enthusiast, I've long been captivated by the medium's vibrant characters, compelling narratives, and imaginative worlds. This passion led me to an intriguing realization: the joy of discovering new anime could be significantly enhanced through personalized recommendations. This insight sparked my journey to develop an Anime Recommendation System, a project that perfectly marries my love for anime with my expertise in data science and machine learning. The goal of this project was to create a sophisticated platform capable of suggesting anime titles based on individual preferences.
    
## Problem Statement:

As the anime industry continues to grow, users face challenges in finding new content that alogns with their preferences. I recognized the need and implemented a personalized recommendation system to provide users with relavent anime suggestions. 

## Solution:
To address this I decided to develop a content-based recommendation system that implements a TF-IDF Vectorizor for string processing and a cosine-similarity sparse matrix to find similar animes based on their genres, title and rating by users.
    
## Approach:

1. **Data Collection and Preprocessing**:
   - The dataset was found on Kaggle - [dataset](https://www.kaggle.com/datasets/dbdmobile/myanimelist-dataset)
   - Missing values were handled and features (like genres) were tokenized for analysis.
2. **Building a Cosine Similarity Sparse Matrix**:
    - A cosine similarity matrix was computed to measure the similarities between different anime titles based on the user ratings and genres.
3. **Recommender Function**:
    - A function was developed to provide the top 10 recommendations for a given anime title. This function uses a pre-calculated cosime matrix to make processing faster. The function returns a dataframe what contains the 10 most similar animes along with their genres and scores.

## Results
The recommendation system successfully provides users with tailored anime recommendations, thereby enhancing their viewing experience. Users are now able to discover new anime that closely aligns with their interests, reducing churn and increasing satisfaction.



## Future Work
Several potential improvements have been identified for the current recommendation system:
- **Hybrid Recommendation System:** A significant enhancement would be the development of a hybrid recommendation system that combines collaborative filtering with the existing content-based approach. This would allow for more robust recommendations by leveraging both user preference data and item similarities. By blending these two techniques, the system can better understand user behavior and suggest more relevant anime titles, thus improving overall recommendation quality.
- **Integration of TensorFlow models:** Implementing a TensorFlow-based model is another promising improvement. This model would be capable of learning deeper relationships between anime titles and user preferences, allowing the system to capture more complex patterns in the data. With the ability to fine-tune model parameters and incorporate neural network architectures, the system could offer more accurate and personalized recommendations.
- **Real Time Data Streams:** he current model is trained on data from 2023, which limits its ability to recommend newly released anime. A real-time data streaming feature would enable the system to continuously update its dataset, ensuring it remains current and capable of recommending the latest anime releases. This real-time integration would significantly enhance the user experience by providing up-to-date recommendations based on the most recent data.

These improvements would not only increase the precision of the recommendations but also future-proof the system for evolving user preferences and new content.
