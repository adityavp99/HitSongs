## Song Popularity Prediction System

### Introduction
The Song Popularity Prediction System aims to predict songs' popularity using machine learning techniques. By analyzing various features of songs, this project aims to provide insights to the music industry on potential hits.

### Objectives
- Develop a predictive model: Create a machine learning model capable of predicting a song's popularity based on its attributes.
- Feature analysis: Identify and analyze key features that influence song popularity.
- Accuracy and performance: Ensure the predictive model has high accuracy and performance.

### Methodology
1. Data Collection: The dataset was downloaded from Kaggle (https://www.kaggle.com/datasets/yasserh/song-popularity-dataset/data).
2. Data Preprocessing: The data underwent cleaning, normalization, and transformation to ensure it was suitable for use in this project.
3. Feature Selection: Key features were selected based on their correlation with song popularity. **Feature Extraction** and **Dimensionality Reduction** techniques like **Principal Component Analysis (PCA)** and **Linear Discriminant Analysis (LDA)** were used.
4. Model Development: Multiple machine learning models, including linear regression, decision trees, random forests, and neural networks, were developed and evaluated.
5. Model Evaluation: Models were evaluated using metrics such as **Mean Squared Error (MSE)** and **R-squared (R²)** to determine their accuracy and performance.

### Results
The random forest model provided the best performance with an R² value of **0.85**, indicating high accuracy in predicting song popularity.
The key features influencing a song's popularity were danceability, energy, loudness, and tempo.
The model successfully predicted whether a song would be a hit with significant accuracy.

### Conclusion
The Song Popularity Prediction System demonstrates the potential of machine learning in forecasting music trends. The project highlights the importance of feature selection and the effectiveness of ensemble learning techniques. Future work includes refining the model with more diverse datasets and exploring additional features such as lyrical content and social media influence.

### Future Work
1. Dataset Expansion: Incorporate more diverse datasets, including different genres and international music charts.
2. Feature Enrichment: Add features like lyrical content analysis and social media engagement metrics.
3. Model Enhancement: Experiment with advanced deep-learning models and ensemble techniques.
4. User Interface Development: Create a user-friendly interface for industry stakeholders to use the prediction system effectively.
