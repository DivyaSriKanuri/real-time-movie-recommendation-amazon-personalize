# real-time-movie-recommendation-amazon-personalize
Built a Real-time Personalized Movie Recommendation System using Amazon Personalize and the MovieLens dataset. The system preprocesses user-item interaction data, trains recommendation models on AWS, and delivers personalized suggestions in real time.

Key Contributions:

Preprocessed large-scale movie ratings data with Pandas.

Integrated AWS S3 for dataset storage and pipelines.

Configured dataset groups, schemas, and import jobs in Amazon Personalize.

Trained recommendation models using the User-Personalization recipe.

Deployed a real-time campaign to generate movie recommendations.

Retrieved recommendations through boto3 SDK and displayed user-specific suggestions.

Tech Stack: Python, Pandas, Boto3, AWS S3, Amazon Personalize
