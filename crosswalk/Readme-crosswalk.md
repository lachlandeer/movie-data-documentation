# crosswalk

The `crosswalk` folder contains 6 files that serve as a mapping tool between the different datasets. 

```
crosswalk
├── chicago_mojo.csv
├── gnip_mojo.csv
├── hsx_mojo.csv
├── mojo_meta.csv
├── mojo_nielsen.csv
└── numbers_mojo.csv
```

For instance, the `hsx_mojo.csv` file includes a simple mapping of identifiers as shown below.

```
| movie_id         | symbol            |
|------------------|-------------------|
| 100foot          | THFTJ             |
| 1952             | 1952              |
| 21jumpstreet2    | 21JS2             |
```

Each identifier from the symbol column is matched with its corresponding movie_id, ensuring that data can be cross-referenced in the hsx files.

<fill in @LACHLAN>
This data was collected from ... <link> on <date>.