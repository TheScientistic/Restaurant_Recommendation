# Restaurant Reviews Recommendation System
The Restaurant Review Recommendation System is a comprehensive project that combines sentiment analysis and recommendation systemsto assist users in discovering top-rated restaurants based on the sentiment of reviews. This project empowers both consumers and restaurant owners by providing data-driven insights and personalized recommendations.

**Sentiment analysis** is performed on restaurant reviews to gauge the sentiment or emotional tone of the text. The nltk library is used to assign a sentiment score to each review, indicating whether it is positive or negative with pre-defined thresholds.

**Recommendation system** assists users in discovering similar restaurants based on their reviews and sentiment scores. The system utilizes sklearn and TF-IDF (Term Frequency-Inverse Document Frequency) vectorization to convert text descriptions into numerical vectors. Cosine similarity is computed between restaurants' TF-IDF vectors to identify similar restaurants.
Recommendations are provided to users based on their selected restaurant.
