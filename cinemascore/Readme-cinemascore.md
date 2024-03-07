# cinemascore

The `cinemascore` folder contains data on movie audience scores from CinemaScore. 
This data is organized by year in individual CSV files. 

```
cinemascore
└── data
    ├── cinemaScore-2009-wide.csv
    ├── cinemaScore-2010-wide.csv
    ├── cinemaScore-2011-wide.csv
    ├── cinemaScore-2012-wide.csv
    ├── cinemaScore-2013-wide.csv
    ├── cinemaScore-2014-wide.csv
    ├── cinemaScore-2015-wide.csv
    └── cinemaScore-2016-wide.csv`
```

## data

The `data` folder contains eight CSV files, each for one year from 2009 to 2016. 
Each file has 4 columns with information on the movie ID, title, release date, and audience score.
Each row represents one movie.

Below is an example of the structure for one of the CSV files in the data folder.

| Column       | Content                                                    |
|--------------|------------------------------------------------------------|
| movie_id     | Unique identifier for the movie                            |
| title        | Full title of the movie                                    |
| releaseDate  | The date when the movie was released (YYYY-MM-DD)          |
| titleSearch  | CinemaScore grade ranging from C- to A+                    |

<fill in @LACHLAN>
This data was collected from ... <link> on <date>. 