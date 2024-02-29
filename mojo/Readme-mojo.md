## mojo
The 'mojo' folder contains a 'boxoffice' folder and a 'charac' folder. 
Below is an overview, and after is a more detailed explanation.

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


**boxoffice**
Daily, weekly, and monthly box office earnings for all movies. 
There is one .csv file for each movie, and there are different folders for 2013, 2014, and 2015.
In total there are 145 movies in 2013; 147 in 2014; and 158 in 2015.

**charac**
Contains two wide data frames with movie characteristics for the 2014 and 2015 movies separately. 
These files contains 22 columns (i.e. movie characteristics):]

| Column                   | Content                                                |
| ------------------------ | ------------------------------------------------------ |
| movie_id                 | Unique identifier for the movie                        |
| movie_title              | Full movie title                                       |
| domestic_total_gross     | Total gross revenue in the domestic market             |
| foreign_total_gross      | Total gross revenue in foreign markets                 |
| opening_weekend          | Opening weekend box office earnings                    |
| opening_weekend_limited  | Opening weekend box office earnings in limited release |
| opening_weekend_wide     | Opening weekend box office earnings in wide release    |
| release_date             | Release date of the movie                              |
| close_date               | Date when the movie closed in theaters                 |
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
| composers                | Composers of the movie                                 |

<fill in @LACHLAN>
This data was scraped from Box Office Mojo <link> on <date>. 