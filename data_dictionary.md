### Data Dictionary

This data dictionary provides a quick overview of features/variables/columns, alongside data types and descriptions. 

|Feature|Type|Source|Description|
|---|---|---|---|
|**title**|*str*|final.csv|movie title (with year)|
|**genres**|*str*|final.csv|movie genre(s):Action, Adventure, Animation, Children's, Comedy, Crime, Documentary, Drama, Fantasy, Film-Noir, Horror, Musical, Mystery, Romance, Sci-Fi, Thriller, War, Western, (no genres listed)|
|**imdbId**|*int*|final.csv|unique movie Id from [IMDb.com](https://www.imdb.com/)| 
|**userId**|*int*|final.csv|unique user Id from [Movielens](https://grouplens.org/datasets/movielens/)| 
|**rating**|*int*|final.csv|rating give a movie by a user. minimum 20 ratings per user from [Movielens](https://grouplens.org/datasets/movielens/) (range 0.5-5.0)|
|**bechdel_score**|*int*|final.csv|Bechdel-Wallace inclusion rating (range 0-3) from [Bechdel Test Movie LIst](https://bechdeltest.com/)|
