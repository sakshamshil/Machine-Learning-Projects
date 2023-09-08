# Movie Recommendation System
Develop a ML-based movie recommendation system which suggest user similar movies based on their inputs.

## Dataset Information

It contains 4803 movies, 24 columns
```
Columns :

index budget	genres	homepage	id	keywords	original_language	original_title	overview
popularity	production_companies	production_countries release_date	revenue	runtime
spoken_languages status tagline title vote_average vote_count cast crew director



Features used for similarity:
'genres', 'keywords', 'tagline', 'cast', 'director'
```

CSV file included in the directory as "movies.csv"

## Libraries Used

* numpy
* pandas
* difflib
* sklearn

## Algorithm Used

* Cosine Similarity Algorithm
