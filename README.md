# Bookworm AI Concept 

## Data: 
UCSD scraped goodreads website for this information in 2017. Goodreads does not allow api keys to be used since 2020. The following files are used in the code. 

goodreads_interactions.csv : User interactions between books 

goodreads_books.json.gz : book metadata

book_id_map : maps betweens books in each dataset 

Link to data: https://mengtingwan.github.io/data/goodreads.html#datasets

## Project Overview

The code uses both TF-IDF and cosine similarity to provide recommendations. The system analyzes and compares the content of titles using NLP techniques like TF-IDF. Cosine similarity is used to measure how similar the vectors are representing characteristics, guiding the recommendation process.


References: 

Wan, M., & McAuley, J. (2018). Item recommendation on monotonic behavior chains. In Proceedings of the 12th ACM Conference on Recommender Systems (RecSys '18). ACM.

Wan, M., Misra, R., Nakashole, N., & McAuley, J. (2019). Fine-grained spoiler detection from large-scale review corpora. In Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics (ACL '19).
