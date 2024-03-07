# nielsen-ads

The `nielsen-ads` folder contains advertising data for movies across different media channels, obtained from Nielsen. 
The data is segmented into categories such as cinema, television, internet, and other advertising platforms for the years 2014 and 2015. 

```
nielsen-ads
└── CSV
    ├── movies_cinema_2014.csv
    ├── movies_cinema_2015.csv
    ├── movies_fsi_2014.csv
    ├── movies_fsi_2015.csv
    ├── movies_internet_2014.csv
    ├── movies_internet_2015.csv
    ├── movies_magazines_2014.csv
    ├── movies_magazines_2015.csv
    ├── movies_nationaltv_2014.csv
    ├── movies_nationaltv_2015.csv
    ├── movies_newspaper_2014.csv
    ├── movies_newspaper_2015.csv
    ├── movies_outdoor_2014.csv
    ├── movies_outdoor_2015.csv
    ├── movies_radio_2014.csv
    ├── movies_radio_2015.csv
    ├── movies_spottv_2014.csv
    └── movies_spottv_2015.csv
```
## `CSV`
These files provide information on the advertising spendings for each movie, offering insights into the marketing strategies and intensity of the advertising by studios and distributors. Each file is named according to the media channel and year the movie was released, for example, `movies_nationaltv_2014.csv` contains information on national TV advertising in 2014.

### File Example: `movies_nationaltv_2014.csv`

An example of the data structure for the `movies_nationaltv_2014.csv` file is as follows:

Each row provides specific details about an ad's airing, such as codes related to the TV program, date, time, spend, duration, and demographic viewership figures.

In total, this file contains 108 columns and 2.490.790 rows.

| Column                                   | Example Value |
|------------------------------------------|---------------|
| UC_dim_Bridge_occ_ImpNationalTV_key      | 4024487       |
| TVProgSubCode                            | PW            |
| ...                                      | ...           |
| AdDate                                   | 2014-10-05    |
| AdTime                                   | 16:43:08      |
| ...                                      | ...           |
| Spend                                    | 119200        |
| Duration                                 | 30            |
| ...                                      | ...           |

Note: This table only includes a selection of columns from the actual dataset. 

Also note that the files on National and Spot TV cover around 90% of all advertising spendings. 

<fill in @LACHLAN>
This data was collected from Nielsen <link> on <date>.

