# oscars

The `oscars` folder contains 1 file with historical data from the nominees and winners of the Oscars Academy Awards.

```
oscars
└── data
    └── oscars-database.csv
```

## `data`
The `data` folder contains one file `oscars-database.csv`.
This file contains information on nominees and winners across various Oscar award categories from 1927 to 2015.
In total there is information on 88 award ceremonies, the first one being for the 1927/1928 season and the last one in 2015.
Each row corresponds to one Oscar nomination. There are 6 columns and 9964 rows. 

| Column    | Content                                            |
|-----------|----------------------------------------------------|
| Year      | The year of the Oscar award (YYYY)                 |
| Ceremony  | The number of the ceremony  (from 1 to 88)         |
| Award     | The category of the award (e.g. Cinematography)    |
| Winner    | Indicates if the nominee won (1) or not (N/A)      |
| Name      | Name of the nominee                                |
| Film      | Film(s) associated with the nomination             |

<fill in @LACHLAN>
This data was collected from the Oscars Database <link> on <date>.