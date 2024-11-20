# Personalized Content and Product Recommendation System

### Overview

The goal of this project is to build a recommendation system that provides personalized recommendations and targeted offers for users based on historical product data, customer preferences, and past behaviors.

The dataset used in this project consists of **gift card metadata**, including features such as title, description, price, average rating, and customer reviews. This system utilizes machine learning algorithms to:
1. Clean and preprocess the data.
2. Perform feature engineering.
3. Build a recommendation engine using content-based filtering and similarity measures.
4. Evaluate the model using metrics such as MAE, RMSE, Precision, Recall, and F1 Score.

### Project Workflow
1. **Data Loading and Cleaning**:
    - Loaded a dataset containing gift card details in JSON format.
    - Handled missing values, duplicates, and incorrect data types.

2. **Feature Engineering**:
    - Created new features such as `popularity_score`, `title_length`, and `description_length`.
    - Encoded categorical variables using One-Hot Encoding.
    - Simulated user-item interactions to build a `user-item matrix`.

3. **Recommendation System**:
    - Built a content-based recommendation engine using cosine similarity.
    - Added functionality to generate recommendations for a given product title.

4. **Evaluation**:
    - Evaluated the model using metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), Precision, Recall, and F1 Score.

5. **Visualization**:
    - Created visualizations for insights into the dataset:
      - Distribution of ratings and prices.
      - Average ratings by store and category.
      - Boxplots for rating distributions by category.

### Evaluation Metrics:

- Mean Absolute Error (MAE): 0.4191
- Root Mean Squared Error (RMSE): 0.5086
- Precision: 0.8846
- Recall: 0.8214
- F1 Score: 0.8519

### Future Improvements

- Combine content-based and collaborative filtering for improved performance.
- Use neural networks (e.g., AutoEncoders or Neural Collaborative Filtering) for better recommendations.
- Implement a real-time recommendation pipeline using tools like Apache Kafka.
- Incorporate user feedback to dynamically adjust recommendations.
- Create a web-based dashboard using Streamlit or Flask to showcase recommendations interactively.
