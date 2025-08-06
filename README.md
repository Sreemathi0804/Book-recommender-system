# Book-recommender-system

COMPANY: CODTECH IT SOLUTIONS

NAME: SREEMATHI.R

INTERN ID: CT06DH682

DOMAIN: MACHINE LEARNING

DURATION: 6 WEEKS

MENTOR: NEELA SANTOSH

This project is a Book Recommendation System using Collaborative Filtering based on user ratings. 
The system suggests books that a user may like by identifying similar users and recommending books they have rated highly.
It uses cosine similarity to calculate similarity between users.

📌 Objective
The main aim is to provide personalized book suggestions to users based on their rating behavior, helping them discover books they are likely to enjoy.

🧰 Technologies Used
Python
Google Colab
pandas
scikit-learn

📁 Dataset
We use a subset of the Book-Crossing Dataset, which includes:
BX-Books.csv: Book details
BX-Book-Ratings.csv: User ratings for books
To improve performance, we filter:
Users who rated more than 50 books
Books with more than 20 ratings

🧠 How It Works
Clean and filter the dataset
Create a user-item matrix
Compute cosine similarity between users
Recommend books liked by similar users but not yet rated by the target user

SAMPLE OUTPUT:
User ID: 11676  
Top 5 Recommended Books:
✔️ The Hobbit  
✔️ Harry Potter and the Chamber of Secrets  
✔️ Twilight  
✔️ The Catcher in the Rye  
✔️ The Da Vinci Code  
