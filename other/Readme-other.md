# other

The `other` folder is a collection of datasets. There are 5 different files that include data on metascores, sequels, economic factors, and production budgets.

```
other
├── metascore_extra.csv
├── sequels.csv
├── usa_cpi.csv
├── usa_population.csv
└── wiki_budgets.csv
```


## `metascore_extra`

The `metascore_extra.csv` file contains additional data to the main metascore data in the `metacritic` folder. 

The file contains 3 columns and 17 rows.

| Column       | Content                                                      |
|--------------|--------------------------------------------------------------|
| mojo_id      | Unique identifier for the movie                              |
| metascore    | The aggregated score from Metacritic                         |
| n_reviews    | The number of critic reviews that contributed to the score   |



## `sequels`

The `sequels.csv` file indicates whether a movie is a sequel or part of a series.
The file contains 3 columns and 252 rows. 

| Column       | Content                                                                              |
|--------------|--------------------------------------------------------------------------------------|
| movie_id     | Unique identifier for the movie                                                      |
| is_sequel    | Indicates whether the movie is a sequel (TRUE) or not (FALSE)                        |
| is_series    | Indicates whether the movie is part of a series or franchise (TRUE) or not (FALSE)   |



## usa_cpi

The `usa_cpi.csv` file contains information on the Consumer Price Index (CPI) in the United States from years 1956 to 2017.

The file contains 2 columns and 62 rows.

| Column       | Content                                                      |
|--------------|--------------------------------------------------------------|
| date         | The date of collecting the CPI (YYYY-01-01)                  |
| cpi          | The Consumer Price Index of the corresponding year           |



## usa_population

The `usa_population.csv` file contains information on the population in the United States from years 1929 to 2016.

The file contains 2 columns and 88 rows.

| Column        | Content                                                      |
|---------------|--------------------------------------------------------------|
| date          | The date of collecting the population (YYYY-01-01)           |
| pop_thousands | The population of the corresponding year (in thousands)      |



## wiki_budgets

The `wiki_budgets.csv` file contains information on the production budget of 15 movies. 

The file contains 2 columns and 15 rows.

| Column            | Content                                                      |
|-------------------|--------------------------------------------------------------|
| movie_id          | Unique identifier for the movie                              |
| production_budget | Budget for producing the movie                               |


<fill in @LACHLAN>
These datasets were collected from ... <link> on <date>.