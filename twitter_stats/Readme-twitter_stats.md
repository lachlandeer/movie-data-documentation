# twitter_stats

The `twitter_stats` folder contains different datasets derived from Twitter. It shows the volume and sentiment of tweets about movies on an hourly or minute level.

```
twitter_stats
├── chicago
│   ├── hourly-0.05
│   │   ├── counts
│   │   │   └── .csv files
│   │   └── stats
│   │       └── .csv files
│   └── minute-0.05
│       └── counts
│           └── .csv files
└── gnip
    ├── hourly-0.05
    │   ├── counts
    │   │   └── .csv files
    │   └── stats
    │       └── .csv files
    └── minute-0.05
        └── counts
            └── .csv files

```

## `chicago` and `gnip`
There are two different data providers:
- The `chicago` folder contains 37 CSV files in both counts and stats. 
- The `gnip` folder contains 10 CSV files in both counts and stats. 

Focusing on `counts`, the files correspond to individual movies or sets of movies, with in each file the information on the number and sentiment of tweets of a specific movie on an hourly (in `hourly-0.05`) or minute (in `minute-0.05`) level. 

Below is an example of the file `chicago/hourly-0.05/counts/DeerAntMan.csv`.
There are 4 columns and 29116 rows.

| Column          | Content                                                             |
|-----------------|---------------------------------------------------------------------|
| date            | Timestamp of the aggregated tweets, formatted as `YYYY-MM-DD HH:MM:SS` |
| vaderClassifier | Sentiment of that tweet (2 = positive / 1 = neutral / 0 = negative)  |
| nTweets         | The number of tweets  within that particular hour          |
| movieName       | Unique identifier for the movie                |

\\
For example, the row below indicates that on January 16, 2016, there were 3 negative tweets about the movie antman between 15:00:00 and 16:00:00 hrs.

| date                | vaderClassifier | nTweets | movieName |
|---------------------|-----------------|---------|-----------|
| 2016-01-16 15:00:00 | 1               | 3       | antman    |


<fill in @LACHLAN>
This data was collected from the Twitter API <link> on <date>. 