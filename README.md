### Anime Recommendation System

- **Motivation:**
    As an avid anime enthusiast, I've long been captivated by the medium's vibrant characters, compelling narratives, and imaginative worlds. This passion led me to an intriguing realization: the joy of discovering new anime could be significantly enhanced through personalized recommendations. This insight sparked my journey to develop an Anime Recommendation System, a project that perfectly marries my love for anime with my expertise in data science and machine learning. The goal of this project was to create a sophisticated platform capable of suggesting anime titles based on individual preferences.
    
    By leveraging advanced algorithms and comprehensive datasets, I aimed to craft a personalized discovery experience for both myself and fellow anime aficionados. This endeavor presented an exciting opportunity to apply data-driven techniques to a domain I'm deeply passionate about. It allowed me to explore the intricate relationships between various anime attributes and viewer preferences, ultimately translating these insights into meaningful recommendations.
    
- **Description:**
    This project involves creating a recommendation system for animes using collaborative filtering and content-based filtering techniques. The system is designed to provide personalized anime recommendations based on user preferences and anime attributes.
    
- **Tools and Technologies:**
    Python, Pandas, Scikit-learn, TensorFlow, Keras, and tkinter
    
- **Approach:**
    The program implements a comprehensive anime recommendation system utilizing collaborative filtering and statistical analysis techniques. The process begins with data preprocessing, where user and anime data are imported, normalized, and encoded. Principal Component Analysis (PCA) is applied to reduce dimensionality, followed by KMeans clustering to identify user segments. The program extracts and normalizes embedding weights from a trained neural network model to find similar animes based on user preferences. The recommendation system is integrated with a graphical user interface (GUI) to allow users to input anime names and receive recommendations.
    
- **Data Exploration:**

  ![Data Exploration 1](https://private-user-images.githubusercontent.com/49876969/348380570-50d29ab5-6884-4857-8aa6-ec1ad8e5fc6b.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4OTYxOTAsIm5iZiI6MTcyMDg5NTg5MCwicGF0aCI6Ii80OTg3Njk2OS8zNDgzODA1NzAtNTBkMjlhYjUtNjg4NC00ODU3LThhYTYtZWMxYWQ4ZTVmYzZiLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDE4MzgxMFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWExODVlNjM1MWJhZjg0NDI2ODYxNmRiMGUxMjZhNDBjYmM5MTVhOTdiNTZjODQ4NjE3ZTdkNDc4ZTQ2NDU2NzEmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.XF1wLvQc0Rm0PPSSgdp6Ll1_UlNFJLGscqJqW_gsYhg)

  ![Data Exploration 2](https://private-user-images.githubusercontent.com/49876969/348380570-50d29ab5-6884-4857-8aa6-ec1ad8e5fc6b.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4OTYxOTAsIm5iZiI6MTcyMDg5NTg5MCwicGF0aCI6Ii80OTg3Njk2OS8zNDgzODA1NzAtNTBkMjlhYjUtNjg4NC00ODU3LThhYTYtZWMxYWQ4ZTVmYzZiLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDE4MzgxMFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWExODVlNjM1MWJhZjg0NDI2ODYxNmRiMGUxMjZhNDBjYmM5MTVhOTdiNTZjODQ4NjE3ZTdkNDc4ZTQ2NDU2NzEmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.XF1wLvQc0Rm0PPSSgdp6Ll1_UlNFJLGscqJqW_gsYhg)

  ![Data Exploration 3](https://private-user-images.githubusercontent.com/49876969/348380737-a9f69661-11c3-42a0-8a63-335db4adac22.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4OTYyMTksIm5iZiI6MTcyMDg5NTkxOSwicGF0aCI6Ii80OTg3Njk2OS8zNDgzODA3MzctYTlmNjk2NjEtMTFjMy00MmEwLThhNjMtMzM1ZGI0YWRhYzIyLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDE4MzgzOVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTE2ZmQ3NTk0OTdlOTNlOWFlMzg3MjQ5YmYzOWU4YWUzMjU3M2YyMWNjMDFkYmM0NjFmNWI3ZDEyZDUzNjIzZGQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.U7JvG-jcEVZlav-7aDCqxyJQFOanrUA7snGe01SDias)

- **Recommendation Output:**

  ![Recommendation Output 1](https://private-user-images.githubusercontent.com/49876969/348381609-7272e8ca-466b-4088-9045-d9b2a03ce0a9.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4OTYyNTksIm5iZiI6MTcyMDg5NTk1OSwicGF0aCI6Ii80OTg3Njk2OS8zNDgzODE2MDktNzI3MmU4Y2EtNDY2Yi00MDg4LTkwNDUtZDliMmEwM2NlMGE5LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDE4MzkxOVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTE0NDc4NGFmMmVjN2IzNmExZmJlYzc4MGQ2MDFiZmRlNWE3N2E1ZGQ3ZTZlN2RmMTI0YTYwM2UxNjliOWM1YWMmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.Bo7BqyOP3mDAtSnRyMHV8zOltpdz3KuVeLj47JiHNlY)

  ![Recommendation Output 2](https://private-user-images.githubusercontent.com/49876969/348381075-76be8b6e-4768-45a7-9312-75cd9f7e3077.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4OTYyODAsIm5iZiI6MTcyMDg5NTk4MCwicGF0aCI6Ii80OTg3Njk2OS8zNDgzODEwNzUtNzZiZThiNmUtNDc2OC00NWE3LTkzMTItNzVjZDlmN2UzMDc3LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDE4Mzk0MFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWMwYTJjMjQxNzI5ZmMzZTQ4ZDIwZDI0MGM3Yzk2ZWZmODc3NDk3MDU3ODk5OWUzZDczYjliYmQ0OWZkNjk3ZTkmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.Y3d2ubxLGvNB_lSzONnBXtXTWnUxDaPAUuhrYWdz4XY)

  ![Recommendation Outpout 3](https://private-user-images.githubusercontent.com/49876969/348398404-c3905634-cca1-4d80-a51b-ecc255754ded.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4OTYzMjIsIm5iZiI6MTcyMDg5NjAyMiwicGF0aCI6Ii80OTg3Njk2OS8zNDgzOTg0MDQtYzM5MDU2MzQtY2NhMS00ZDgwLWE1MWItZWNjMjU1NzU0ZGVkLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDE4NDAyMlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTIxMmU5NWUzYmZiYzBiMDZjMWY1OWM0MDY4OTUxYTZkZTY4ODRmZDQ2ZmMyMzk1NTBkYWU4YjBhODA1OTI5NDkmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.9m17nDsQ_ai6dC2TIocfFuipv37gACYVR0j9aky1TcQ)

- **Code Repository:**
    [Anime Recommendation System](https://github.com/DSM2499/recomendation_system)

- **Dataset:**
    [MyAnimeList Dataset](https://www.kaggle.com/datasets/dbdmobile/myanimelist-dataset)

- **Results:**
    Achieved a satisfactory level of accuracy and user satisfaction with the recommendations provided.

- **Acknowledgement:**
    In developing this Anime Recommendation System, I had the privilege of collaborating with my talented colleague, Sajid. Their exceptional design skills and collaborative spirit were instrumental in elevating this project from a data-driven concept to a fully-realized, user-friendly application. Sajid's contributions were crucial in translating complex algorithms into an intuitive interface, significantly enhancing the user experience of our Anime Recommendation App.
    
    This collaboration underscores the importance of interdisciplinary teamwork in bringing data science projects to life. While my expertise lay in developing the underlying recommendation algorithms and data analysis, Sajid's design acumen ensured that our technical achievements were presented in an accessible and visually appealing manner.
    
    Our partnership on this project exemplifies the synergy between data science and user experience design, resulting in a more robust and engaging final product. This experience has reinforced my belief in the power of diverse skill sets and collaborative problem-solving in tackling complex data challenges.
    
    I'm grateful for Sajid's invaluable contributions, which have undoubtedly enhanced the overall quality and impact of this project. Their involvement has not only improved the end result but also enriched my own learning experience, providing insights into the crucial role of design in data-driven applications.
    
- **Future Work:**
    Exploring hybrid recommendation systems and real-time recommendation updates.
