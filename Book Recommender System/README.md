
## Project Title : Book Recommender System.

**Technologies Used**: 
**Libraries**: Pandas, NumPy, Scikit-learn, NearestNeighbors, Pickle.---
**Languages**: Python.---
**Deployment**: Pickle.

**Overview**:To build a book recommendation system that suggests similar books based on user ratings using a collaborative filtering approach.

**The project follows several steps:**

**Data Preprocessing:** 
- Loaded and merged datasets: Books, Users, and Ratings

- Cleaned and filtered sparse data (e.g., books with very few ratings)

- Removed duplicates and handled missing values

- Focused on popular books (books with a significant number of ratings).

**Feature Engineering**
- Created a pivot table: Users vs Books, with ratings as values

- Filled missing entries with 0 to create a sparse matrix

**Recommendation Algorithm**
- Used K-Nearest Neighbors (KNN) algorithm with cosine similarity to find similar books

- Built a recommender function that returns top similar books based on user input

**Model Deployment**
- Serialized the recommendation model using Pickle

**Manual Testing**

**Conclusion**: 
The book recommender system successfully identifies and suggests similar books by analyzing user rating patterns, enhancing the user experience through personalized recommendations and supporting better content discovery.
