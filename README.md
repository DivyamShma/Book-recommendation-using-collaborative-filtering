# Book-recommendation-using-collaborative-filtering

**Dataset link** - https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset
 
**Python 3+ Dependencies** - pandas, numpy, sklearn (cosine similarity), jupyter notebook/ VS code

## Project Description 
This project provides two different models for recommendation of books. First is popularity based recommendation which counts the number of ratings given to a book (should be higher than 250) and takes average of all the ratings given to it, giving the most popular or the books with the highest average.
Second model is using collaborative filtering and cosine similarity. We make a 2D matrix with book titles and user ids, user ids who have rated more than 200 books and books which have more than 50 ratings were chosen. Then it was converted to a 2D sparse matrix continaing ratings from all users to all books, those users that had not given any ratings were given 0 by default. Next cosine similarity was used to find the closet book to recommend 
 
