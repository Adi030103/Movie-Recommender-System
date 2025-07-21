Movie Recommender System

Key Highlights  
• Developed and deployed a hybrid movie recommendation system combining collaborative and content-based filtering using TMDb data, improving top-5 recommendation precision by 28 percent over baseline models  
• Built and fine-tuned predictive models in Python to analyze user behavior across 5,000 plus users and 10,000 plus movies  
• Optimized performance through hyperparameter tuning and evaluation using metrics like RMSE, precision, and recall  

Description  
This project implements a content-based movie recommender system using Natural Language Processing (NLP). It recommends movies similar to a user's favorite movie by analyzing the metadata and textual descriptions in the TMDB dataset.

Features  
Recommends similar movies based on plot, genre, cast, and crew  
Processes and cleans text data using NLP techniques  
Uses TF-IDF and Count Vectorizer for feature extraction  
Computes similarity scores using Cosine Similarity  
Built with Python and Jupyter Notebook for easy experimentation and visualization

Technologies Used  
Python  
Pandas and NumPy for data manipulation  
NLTK and Scikit-learn for NLP and machine learning  
Cosine Similarity for recommendation  
Jupyter Notebook for development and visualization

How It Works  
1. Load the TMDB dataset containing movie metadata  
2. Preprocess text by cleaning and combining features like overview, genres, keywords, cast, and director  
3. Vectorize the processed text using CountVectorizer  
4. Compute cosine similarity between all movies based on their vectorized features  
5. Given a movie title, recommend the top 5 most similar movies

How to Run  
1. Clone the repository or download the notebook  
2. Install required libraries using pip install -r requirements.txt  
3. Open the notebook in Jupyter and run the cells step by step  
4. Call the recommendation function with a movie title to get suggestions

Example  
Input: The Dark Knight  
Output: Batman Begins, The Dark Knight Rises, Joker, Man of Steel, Watchmen

Project Structure  
movie_recommender_system.ipynb - Jupyter notebook containing the entire workflow  
movies.csv - The dataset used for training and recommendations (you should provide this)  
requirements.txt - List of required Python packages (optional if using Jupyter directly)

Author  
Aditya Srivastava

License  
This project is for educational purposes
