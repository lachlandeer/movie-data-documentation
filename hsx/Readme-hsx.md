# hsx

The `hsx` folder contains 2 files with information on the Hollywood Stock Exchange prediction of movie box office earnings.

```
hsx
├── HSX_release_2014.csv
└── HSX_release_2015.csv
```

These files contain information on the HSX prediction in 2014 and 2015.
Each row shows the expected box office earnings for each movie on one day.
There are 5 columns and 279,698 rows.

| Column                  | Content                                                      |
| ----------------------- | ------------------------------------------------------------ |
| name                    | Full title of the movie                                      |
| symbol                  | Unique identifier for the movie                              |
| date(st.release_date)   | Release Date of the Movie (M/D/YYYY)                         |
| daily_close             | Predicted Box Office earnings for Day x (in million dollars) |
| date(dh.update_date)    | Day x (M/D/YYYY)                                             | 

<fill in @LACHLAN>
This data was collected from Hollywood Stock Exchange <link> on <date>. 
