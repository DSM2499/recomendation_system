## Anime Recommendation System

#### Motivation:

As an avid anime enthusiast, I've long been captivated by the medium's vibrant characters, compelling narratives, and imaginative worlds. This passion led me to an intriguing realization: the joy of discovering new anime could be significantly enhanced through personalized recommendations. This insight sparked my journey to develop an Anime Recommendation System, a project that perfectly marries my love for anime with my expertise in data science and machine learning. The goal of this project was to create a sophisticated platform capable of suggesting anime titles based on individual preferences.
    
By leveraging advanced algorithms and comprehensive datasets, I aimed to craft a personalized discovery experience for both myself and fellow anime aficionados. This endeavor presented an exciting opportunity to apply data-driven techniques to a domain I'm deeply passionate about. It allowed me to explore the intricate relationships between various anime attributes and viewer preferences, ultimately translating these insights into meaningful recommendations.
    
#### Description:

This project involves creating a recommendation system for animes using collaborative filtering and content-based filtering techniques. The system is designed to provide personalized anime recommendations based on user preferences and anime attributes.

#### Tools and Technologies:
Python, Pandas, Scikit-learn, TensorFlow, Keras, and tkinter
    
#### Approach:

The program implements a comprehensive anime recommendation system utilizing collaborative filtering and statistical analysis techniques. The process begins with data preprocessing, where user and anime data are imported, normalized, and encoded. Principal Component Analysis (PCA) is applied to reduce dimensionality, followed by KMeans clustering to identify user segments. The program extracts and normalizes embedding weights from a trained neural network model to find similar animes based on user preferences. The recommendation system is integrated with a graphical user interface (GUI) to allow users to input anime names and receive recommendations.
    
#### Data Exploration:

  ![Data Exploration 1](https://github.com/DSM2499/recomendation_system/blob/main/Photos/Anime%20recommendation%20photos/Anime%20Distribution.png)

  ![Data Exploration 2](https://github.com/DSM2499/recomendation_system/blob/main/Photos/Anime%20recommendation%20photos/Anime%20through%20the%20years.png)

  ![Data Exploration 3](https://github.com/DSM2499/recomendation_system/blob/main/Photos/Anime%20recommendation%20photos/Clustering%20for%20users.png)

#### Recommendation Output:

  ![Recommendation Output 1](https://github.com/DSM2499/recomendation_system/blob/main/Photos/Anime%20recommendation%20photos/Portfolio%20Recommendation%20Example.png)

  ![Recommendation Output 2](https://github.com/DSM2499/recomendation_system/blob/main/Photos/Anime%20recommendation%20photos/Recommendation%20GUI.png)

  ![Recommendation Outpout 3](https://github.com/DSM2499/recomendation_system/blob/main/Photos/Anime%20recommendation%20photos/Training%20loss%20vs%20Validation%20Loss%20(1).png)


**Dataset:**
    [MyAnimeList Dataset](https://www.kaggle.com/datasets/dbdmobile/myanimelist-dataset)

**Results:**
    Achieved a satisfactory level of accuracy and user satisfaction with the recommendations provided.

**Acknowledgement:**
    In developing this Anime Recommendation System, I had the privilege of collaborating with my talented colleague, Sajid. Their exceptional design skills and collaborative spirit were instrumental in elevating this project from a data-driven concept to a fully-realized, user-friendly application. Sajid's contributions were crucial in translating complex algorithms into an intuitive interface, significantly enhancing the user experience of our Anime Recommendation App.
    
This collaboration underscores the importance of interdisciplinary teamwork in bringing data science projects to life. While my expertise lay in developing the underlying recommendation algorithms and data analysis, Sajid's design acumen ensured that our technical achievements were presented in an accessible and visually appealing manner.
    
Our partnership on this project exemplifies the synergy between data science and user experience design, resulting in a more robust and engaging final product. This experience has reinforced my belief in the power of diverse skill sets and collaborative problem-solving in tackling complex data challenges.
    
I'm grateful for Sajid's invaluable contributions, which have undoubtedly enhanced the overall quality and impact of this project. Their involvement has not only improved the end result but also enriched my own learning experience, providing insights into the crucial role of design in data-driven applications.
    
**Future Work:**
    Exploring hybrid recommendation systems and real-time recommendation updates.
