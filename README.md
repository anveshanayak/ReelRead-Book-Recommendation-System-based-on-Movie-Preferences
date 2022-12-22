# Book-Recommendation-System-based-on-Movie-Prefferences
ML model trained using Graph Neural Networks


People often find watching movie adaptations of books, less cumbersome and more relaxing than reading the original books itself. 
Moreover the number of people that truly spare time to read novels has only been declining ever since numerous online streaming platforms have taken over the internet/entertainment industry. Our project helps discover and revive users interest in the marvellous world of books by recommending the perfect book to start off with based on their movie preferences.

Data:
CSV files used-
Keywords.csv-id,keywords

Metadata_movies.csv- adult,belongs_to_collection,budget,genres,homepage,id,imdb_id,original_language,original_title,overview,popularity,poster_path,production_companies,production_countries,release_date,revenue,runtime,spoken_languages,status,tagline,title,video,vote_average,vote_count

Data.csv-index,title,genre,summary

Graph Data:

Unweighted Graph –
   Nodes-200
   Edges- 16726
Weighted Graph –
   Nodes-200
   Edges - 16726
 
Process:
3 Cosine similarity matrices were created-
Movies cosine similarity
Books cosine similarity
Movies vs Books cosine similarity

We have implemented 3 Link Prediction ML models:
Traditional link prediction method using Jaccard Coefficient
Link prediction using Graph Neural Networks
              I. GCN
              II.GraphSage

Results:

Accuracy provided by our models:
GCN Model-0.8676
GraphSage-0.8655

Jaccard coefficient- AUC 0.83
Adamic-Adar- AUC 0.85
Preferential Attachment- AUC 0.86



