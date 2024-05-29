 # Book-Recommendation-System
![Books](https://github.com/AyeshaTehreeem/Book-Recommender/blob/main/book.jpg)

This Book Recommendation System processes data from 2.4 Lakh distinct books and recommends the top 50 books based on overall ratings and user feedback, as well as 5 similar books based on the user's selected input. The system utilizes Flask for the frontend interface and a collaborative filtering algorithm for the backend recommendation engine.

# Features

 __Top 50 recommendations__:

- Provides the top 50 books, each with over 250 ratings.

__Similar Book Recommender__:

- Recommends 5 books similar to the one selected by the user.
- Uses collaborative filtering techniques to find books that share similar characteristics or have been enjoyed by similar users.

# Dataset Used

[Dataset from Kaggle ](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset?select=Books.csv)

The Dataset has 3 different files

- Users.csv
  
(1) User-ID - Unique user id
(2) Location - location of the user
(3) Age - User Age

- Books.csv
  
(1) ISBN - Book ISBN
(2) Book-Title - Book Title
(3) Book-Author - Book Author
(4) Year-Of-Publication - year of publication
(5) Publisher - publisher of the book
(6) Image-URL-S - small image of the book, amazon link
(7) Image-URL-M - medium size image of the book, amazon link
(8) Image-URL-L - large image size of the book, amazon link

- Ratings.csv
  
(1) User-ID - Unique user id
(2) ISBN - Book ISBN
(3) Book-Rating rating
