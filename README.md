## Anime Recommendation System

### Motivation:

As an avid anime enthusiast, I've long been captivated by the medium's vibrant characters, compelling narratives, and imaginative worlds. This passion led me to an intriguing realization: the joy of discovering new anime could be significantly enhanced through personalized recommendations. This insight sparked my journey to develop an Anime Recommendation System, a project that perfectly marries my love for anime with my expertise in data science and machine learning. The goal of this project was to create a sophisticated platform capable of suggesting anime titles based on individual preferences.
    
By leveraging advanced algorithms and comprehensive datasets, I aimed to craft a personalized discovery experience for both myself and fellow anime aficionados. This endeavor presented an exciting opportunity to apply data-driven techniques to a domain I'm deeply passionate about. It allowed me to explore the intricate relationships between various anime attributes and viewer preferences, ultimately translating these insights into meaningful recommendations.
    
### Description:

This project involves creating a recommendation system for animes using collaborative filtering and content-based filtering techniques. The system is designed to provide personalized anime recommendations based on user preferences and anime attributes.

### Tools and Technologies:
Python, Pandas, Scikit-learn, TensorFlow, Keras, and tkinter
    
### Approach:

The program implements a comprehensive anime recommendation system utilizing collaborative filtering and statistical analysis techniques. The process begins with data preprocessing, where user and anime data are imported, normalized, and encoded. Principal Component Analysis (PCA) is applied to reduce dimensionality, followed by KMeans clustering to identify user segments. The program extracts and normalizes embedding weights from a trained neural network model to find similar animes based on user preferences. The recommendation system is integrated with a graphical user interface (GUI) to allow users to input anime names and receive recommendations.
    
### Data Exploration:

  ![Data Exploration 1](https://github.com/DSM2499/recomendation_system/blob/main/Photos/Anime%20recommendation%20photos/Anime%20Distribution.png)

  ![Data Exploration 2](https://github.com/DSM2499/recomendation_system/blob/main/Photos/Anime%20recommendation%20photos/Anime%20through%20the%20years.png)

  ![Data Exploration 3](https://github.com/DSM2499/recomendation_system/blob/main/Photos/Anime%20recommendation%20photos/Clustering%20for%20users.png)

#### Recommendation Output:

  ![Recommendation Output 1](https://github.com/DSM2499/recomendation_system/blob/main/Photos/Anime%20recommendation%20photos/Portfolio%20Recommendation%20Example.png)

  ![Recommendation Output 2](https://github.com/DSM2499/recomendation_system/blob/main/Photos/Anime%20recommendation%20photos/Recommendation%20GUI.png)

  ![Recommendation Outpout 3](https://github.com/DSM2499/recomendation_system/blob/main/Photos/Anime%20recommendation%20photos/Training%20loss%20vs%20Validation%20Loss%20(1).png)


### Dataset:

[MyAnimeList Dataset](https://www.kaggle.com/datasets/dbdmobile/myanimelist-dataset)

### Results:

Achieved a satisfactory level of accuracy and user satisfaction with the recommendations provided.

### Insights:

- **Insights from Genre Clustering:**
      - Cluster 0:
        
  ![Cluster 0](https://github.com/DSM2499/Portfolio/blob/main/Photos/recommendation%20GI%200.png?raw=true)

  Primary Genres: Comedy, Parody, School, Ecchi, Magic

  Insights: Audience preference for light-hearted, humorous content blending school settings with fantasy elements. Inclusion of Ecchi indicates acceptance of mature themes.

     - Cluster 1:

       ![Cluster 1](https://github.com/DSM2499/Portfolio/blob/main/Photos/recommendation%20GI%201.png?raw=true)

       Primary Genres: Fantasy, Adventure, Action, Comedy, Magic

       Insights: Strong attraction to imaginative, high-energy content featuring magical and action elements within fantasy settings.

     - Cluster 2:

       ![Cluster 2](https://github.com/DSM2499/Portfolio/blob/main/Photos/recommendation%20GI%202.png?raw=true)

       Primary Genres: Romance, Comedy, School, Drama, Ecchi

       Insights: Clear preference for romantic narratives in school settings, with an appetite for emotional depth and some mature content.

     - Cluster 3:

       ![Cluster 3](https://github.com/DSM2499/Portfolio/blob/main/Photos/recommendation%20GI%203.png?raw=true)

       Primary Genres: Sports, Shounen, Comedy, Drama, Action

       Insights: Dominance of sports-themed and youth-targeted content, appealing to viewers who enjoy competitive storylines with emotional and humorous elements.

     - Cluster 4:

       ![Cluster 4](https://github.com/DSM2499/Portfolio/blob/main/Photos/recommendation%20GI%204.png?raw=true)

       Primary Genres: Action, Supernatural, Comedy, Mystery, Shounen

       Insights: Audience drawn to action-packed supernatural themes, with a taste for complex plots and youth-centric narratives.

     - Cluster 5:

       ![Cluster 5](https://github.com/DSM2499/Portfolio/blob/main/Photos/recommendation%20GI%205.png?raw=true)

       Primary Genres: Music, Comedy, Slice of Life, School, Drama

       Insights: Niche combining music themes with realistic, everyday stories, appealing to viewers seeking relatable content with emotional depth.

     - Cluster 6:

       ![Cluster 6](https://github.com/DSM2499/Portfolio/blob/main/Photos/recommendation%20GI%206.png?raw=true)

       Primary Genres: Kids, Comedy, Fantasy, Adventure, Action

       Insights: Strong market for all-ages content, blending imaginative adventures with light-hearted comedy.

     - Cluster 7:

       ![Cluster 7](https://github.com/DSM2499/Portfolio/blob/main/Photos/recommendation%20GI%207.png?raw=true)

       Primary Genres: Hentai, School, Supernatural, Demons, Fantasy

       Insights: Distinct adult-oriented cluster with a focus on darker, fantasy-based narratives and supernatural themes.

     - Cluster 8:
    
        ![Cluster 8](https://github.com/DSM2499/Portfolio/blob/main/Photos/recommendation%20GI%208.png?raw=true)

       Primary Genres: Sci-Fi, Action, Mecha, Adventure, Comedy

       Insights: Clear audience for futuristic, high-energy content, particularly featuring advanced technology and robotic themes.

     - Cluster 9:

       ![Cluster 9](https://github.com/DSM2499/Portfolio/blob/main/Photos/recommendation%20GI%209.png?raw=true)

       Primary Genres: Slice of Life, Comedy, School, Drama, Romance

       Insights: Strong preference for grounded, emotionally engaging stories focusing on everyday life and relationships.


  This cluster analysis provides a nuanced understanding of anime genre preferences, revealing distinct audience segments. These insights can      inform content creation strategies, marketing approaches, and programming decisions in the anime industry.

 - **Anime Duration**
 
    My analysis of anime episode durations reveals key trends in content structure and viewer preferences. These insights offer valuable 
    guidance for content creators, distributors, and streaming platforms in the anime industry.

    ![anime duration](https://github.com/DSM2499/Portfolio/blob/main/Photos/anime%20duration.png?raw=true)

    - Actionable Insights:
       - Maintain focus on standard 24-26 minute episodes to meet primary market demand.
       - Explore opportunities in short-form content (under 10 minutes) to capture quick-viewing audience segments.
       - Utilize shorter episodes in marketing campaigns to attract new viewers with lower time commitment barriers.
       - Create viewing pathways that gradually introduce users to longer-form content, fostering deeper engagement.

    Understanding the distribution of anime episode durations provides crucial insights for strategic decision-making in content creation, 
    platform design, and marketing within the anime industry. By leveraging these findings, stakeholders can enhance user engagement, streamline 
    content production, and develop more effective marketing strategies, ultimately driving growth and viewer satisfaction in the competitive 
    anime market.

  - **Audience Demographic Analysis:**

     ![user gender](https://github.com/DSM2499/Portfolio/blob/main/Photos/anime%20user.png?raw=true)

    ![user age](https://github.com/DSM2499/Portfolio/blob/main/Photos/anime%20age%20distribution.png?raw=true)

    ![user region](https://github.com/DSM2499/Portfolio/blob/main/Photos/anime%20location%20distribution.png?raw=true)

    <p>Our analysis of the anime community reveals a predominantly male audience with significant female representation and a small non-binary user base. The largest demographic consists of users in their early thirties, followed by young adults, with a global reach that includes notable concentrations in Poland, Germany, Brazil, Canada, and several European countries. This diverse audience composition provides valuable guidance for content creation, marketing, and platform development in the anime industry.</p>

    <p>To effectively engage this audience, content strategies should focus on developing gender-inclusive anime that appeals to both male and female viewers while also incorporating themes that resonate with non-binary individuals. Marketing campaigns can be localized to target countries with high user concentrations, with messaging tailored to the predominant age groups. Platform developers should prioritize age-appropriate content recommendations, offer customization options for different gender identities, and implement region-specific features. By leveraging these demographic insights, stakeholders in the anime industry can create more inclusive and engaging experiences, potentially expanding their user base and deepening audience engagement across various demographic segments.</p>

  - **User Engagement Analysis:**

     ![user engagement 1](https://github.com/DSM2499/Portfolio/blob/main/Photos/user%20engagement%20gender.png?raw=true)

    ![user engagement 2](https://github.com/DSM2499/Portfolio/blob/main/Photos/user%20engagement%20age.png?raw=true)

    <p>Anime audience engagement analysis reveals significant trends across gender and age demographics, providing actionable insights for content strategy, marketing, and user experience optimization. Users across all genders demonstrate high completion rates and substantial interest in planning future anime viewing, indicating strong content satisfaction and potential for sustained engagement. Age-wise, engagement peaks in the early 20s and mid-40s, with steady interest across the 25-35 age range, suggesting targeted demographics for focused marketing efforts. However, a notable decline in engagement beyond age 50 presents an opportunity for tailored content and outreach strategies to retain older viewers.</p>

    <p>To capitalize on these insights, content creators should focus on genres with high completion rates and promote upcoming releases to leverage the high 'plan to watch' counts. Marketing campaigns should be tailored to highly engaged age groups and gender preferences, with special attention to developing strategies that appeal to users over 50. Enhancing user experience through personalized recommendations based on completion and planning patterns can further boost engagement. Additionally, addressing the higher drop rates among Non-Binary users through content refinement and implementing community-building features like forums or watch parties can foster deeper user involvement. By integrating these strategies, stakeholders in the anime industry can optimize user engagement, retention, and overall satisfaction across diverse demographic segments.</p>


### Acknowledgement:

In developing this Anime Recommendation System, I had the privilege of collaborating with my talented colleague, Sajid. Their exceptional design skills and collaborative spirit were instrumental in elevating this project from a data-driven concept to a fully-realized, user-friendly application. Sajid's contributions were crucial in translating complex algorithms into an intuitive interface, significantly enhancing the user experience of our Anime Recommendation App.
    
This collaboration underscores the importance of interdisciplinary teamwork in bringing data science projects to life. While my expertise lay in developing the underlying recommendation algorithms and data analysis, Sajid's design acumen ensured that our technical achievements were presented in an accessible and visually appealing manner.
    
Our partnership on this project exemplifies the synergy between data science and user experience design, resulting in a more robust and engaging final product. This experience has reinforced my belief in the power of diverse skill sets and collaborative problem-solving in tackling complex data challenges.
    
I'm grateful for Sajid's invaluable contributions, which have undoubtedly enhanced the overall quality and impact of this project. Their involvement has not only improved the end result but also enriched my own learning experience, providing insights into the crucial role of design in data-driven applications.
    
### Future Work:

Exploring hybrid recommendation systems and real-time recommendation updates.
