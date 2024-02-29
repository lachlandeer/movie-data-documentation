# mojo
The 'mojo' folder contains a 'boxoffice' folder and a 'charac' folder. 
Below is an overview, and after is a more detailed explanation.

```
mojo
├── boxoffice
│   ├── daily
│   │   ├── 2013 
│   │   │   └── .csv files
│   │   ├── 2014
│   │   │   └── .csv files
│   │   └── 2015                                               
│   │       └── .csv files
│   │
│   ├── weekend    
│   │   ├── 2013 
│   │   │   └── .csv files
│   │   ├── 2014
│   │   │   └── .csv files
│   │   └── 2015                                               
│   │       └── .csv files
│   │
│   └── weekly
│       ├── 2013 
│       │   └── .csv files
│       ├── 2014
│       │   └── .csv files
│       └── 2015                                               
│           └── .csv files
└── charac
        ├── movie-charac-wide-2014.csv
        └── movie-charac-wide-2015.csv       
```

## **boxoffice**

The `boxoffice` folder has seperate folders for 2013, 2014, and 2015.
Each of those contains daily, weekly, and weekend box office earnings for all movies. 
There is one .csv file for each movie.
Each row in the .csv files represents the box office data for that movie on a given day, week, or weekend.

In total, there are 145 movies in 2013; 147 in 2014; and 158 in 2015.

Below is an example of one file in the daily/2014/ folder.
There are 8 columns.

| Column          | Content                                                      |
|-----------------|--------------------------------------------------------------|
| movie_id        | Unique identifier for the movie                              |
| year            | The year the movie is released                               |
| date            | The date of the recorded earnings (Format: MMM. DD, YYYY)    |
| rank            | The rank of the movie in terms of daily box office earnings  |
| boxOffice       | The earnings for that day in USD                             |
| theatres        | The number of theaters the movie was shown in                |
| grossBoxOffice  | The cumulative gross earnings up to that date                |
| dayOfRelease    | The number of days since the movie was released              |                                           | 


## **charac**
The `charac` folder contains two wide dataframes with movie characteristics for 2014 and 2015. 
These files contains 22 columns (i.e. movie characteristics) and 152 rows (i.e. movies) for 2014; and 158 rows for 2015.

| Column                   | Content                                                |
| ------------------------ | ------------------------------------------------------ |
| movie_id                 | Unique identifier for the movie                        |
| movie_title              | Full title of the movie                                |
| domestic_total_gross     | Total gross revenue in the domestic market             |
| foreign_total_gross      | Total gross revenue in foreign markets                 |
| opening_weekend          | Opening weekend box office earnings                    |
| opening_weekend_limited  | Opening weekend box office earnings in limited release |
| opening_weekend_wide     | Opening weekend box office earnings in wide release    |
| release_date             | Release date of the movie (YYYY-MM-DD)                 |
| close_date               | Date when the movie closed in theaters (YYYY-MM-DD)    |
| in_release_days          | Number of days the movie was in theaters               |
| runtime_mins             | Duration of the movie in minutes                       |
| rating                   | Movie rating                                           |
| genre                    | Genre of the movie                                     |
| distributor              | Movie distributor                                      |
| director                 | Director of the movie                                  |
| producer                 | Producer(s) of the movie                               |
| production_budget        | Budget for producing the movie                         |
| widest_release_theaters  | Number of theaters with the widest release             |
| actors                   | Main actors in the movie                               |
| writers                  | Writers of the movie                                   |
| cinematographers         | Cinematographer(s) of the movie                        |
| composers                | Composer(s) of the movie                               |

<fill in @LACHLAN>
This data was scraped from Box Office Mojo <link> on <date>. 