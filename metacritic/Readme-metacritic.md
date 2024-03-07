# metacritic
The `metacritic` folder contains 15 files with aggregated critic reviews and ratings from the Metacritic website. 

```
metacritic
└── metaScores
    ├── 2000-metaScores.csv
    ├── 2001-metaScores.csv
    ├── 2002-metaScores.csv
    ├── ... 
    └── 2015-metaScores.csv
```

Each file contains a metascore and the number of critic reviews for a movie collected in that year. 
These files provide a critical view of how movies were received by critics each year.

Below is an example of the `2014-metaScores.csv` file. Each row corresponds to one movie. 
There are 4 columns and 642 rows. 

| Column       | Content                                                      |
|--------------|--------------------------------------------------------------|
| movieID      | Unique identifier for the movie                              |
| title        | Full title of the movie                                      |
| metaScore    | The aggregated score from Metacritic                         |
| nReviews     | The number of critic reviews that contributed to the score   |

Please note that these files also include movies that were not wide-released but, for example, only on streaming platforms or in smaller release.

<fill in @LACHLAN>
This data was collected from Metacritic <link> on <date>.