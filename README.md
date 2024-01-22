# Item-based recomendation system using Anime data 

## Overview
This program is designed to gain comprehensive insights into the demographics of anime fans and industry trends, as well as develop an effective item-based recommendation system for animes.

## Prerequisistes
#### Basic Libraries:

pandas: Data manipulation and analysis.
numpy: Mathematical operations on arrays and matrices.
plotly.express: Interactive plotting.
matplotlib.pyplot: Plotting library.
mpl_toolkits.mplot3d.Axes3D: 3D plotting for Matplotlib.
WordCloud: Generating word clouds.
pickle: Serialization and deserialization of Python objects.
warnings: Warning control.

#### Data Preprocessing:
MinMaxScaler: Scaling numerical features to a specified range.
LabelEncoder: Encoding categorical labels with numerical values.
PCA: Principal Component Analysis for dimensionality reduction.

#### Clustering:
KMeans: K-Means clustering algorithm.
silhouette_score: Metric for the goodness of a clustering technique.

#### Model Training:
shuffle: Randomly shuffling data.
train_test_split: Splitting data into training and testing sets.
tensorflow: Machine learning library.

#### Collaborative Filtering:
Input, Embedding, Dot, Flatten, Dense: Layers for building collaborative filtering models.
Model: Model class for defining and training models.
Adam: Optimization algorithm.
collections.defaultdict, collections.Counter: Data structures for counting and default values.

#### Content-Based Filtering:
TfidfVectorizer: Transforming text data to TF-IDF feature vectors.
linear_kernel: Computing linear kernel between vectors.

#### Hypothesis Testing:
scipy.stats: Statistical functions for hypothesis testing.

#### GUI (Graphical User Interface):
tkinter: GUI toolkit for creating desktop applications.
messagebox: Dialogs for displaying messages.
tkhtmlview.HTMLLabel: HTML label for displaying rich text.

## Project Structure
The program uses the K-Means algorithm to cluster the anime data based on their features, providing insights into the different genres and trends in the industry. The program uses a collaborative filtering model with a stochastic gradient descent algorithm to predict user ratings for animes. The program also implements a content-based filtering system, which uses the term frequency-inverse document frequency (TF-IDF) technique to represent the anime data and computes the similarity between animes using the cosine similarity metric. The program includes a graphical user interface (GUI) built using the Tkinter library, which allows users to interact with the system and view the recommendations and other insights.
