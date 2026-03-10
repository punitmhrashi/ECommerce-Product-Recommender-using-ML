**What is my project goal :-** The goal of this project is to develop an e-commerce product recommendation system that suggests relevant products to users based on their interests and search activity. The system analyzes user information and product data to generate personalized recommendations.

**Problem Statement :-** Online shopping platforms contain a large number of products, which makes it difficult for users to find suitable items quickly. Traditional search systems mainly rely on keywords and do not consider user preferences. A recommendation system helps solve this problem by suggesting products that match the user’s interests.

**Approach :-** The project follows these steps:

Data Preparation
Synthetic data is generated to represent users, product categories, products, and search history in an e-commerce environment.

User Profile Analysis
The system examines the user’s profile description and interests to understand preferences.

Product Search and Recommendation
When a user requests recommendations or searches for a product, the system retrieves relevant items from the database.

Machine Learning Integration
A language model is used to process user information and improve the quality of recommendations.

API Implementation
FastAPI is used to build APIs that allow the system to retrieve user profiles, search products, generate recommendations, and record feedback.

Feedback Evaluation
Users can provide ratings for recommendations, which helps evaluate the effectiveness of the system.

**Technologies Used :-** 
->  Python
->  FastAPI
->  SQLite Database
->  Qdrant Vector Database
->  FLAN-T5 Language Model
->  Uvicorn Server

**Result :-** The system generates product recommendations based on user interests and previous activity. This helps users discover relevant products more easily and improves the overall shopping experience.
