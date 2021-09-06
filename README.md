# LL Basics: Datasets

## Overview
These are example datasets that are open source, cleaned, and free to use for whatever project you would like to use them for. 


### Names in Lyrics

This dataset analyzes songs from the US Billboard Hot 100 from 1958-2017, identifying names from their lyrics. A more complete description of how the data was collected, as well as the visual essay, can be found in the source link.


- Source: [Names in Pop Songs, Data World]https://data.world/the-pudding/names-in-pop-songs
- Gitfile: [names_in_lyrics.csv](https://github.com/learninglab-dev/ll-basics-datasets/blob/main/names_in_lyrics.csv)

#### Description of Data

| Column Name | Data Type | Description | Example | 
| ----------- | --------- | ----------- | ------- |
|artist | categorical, nominal | the name of the artist or band who sang the song | Ed Sheeran | 
| name | categorical, nominal | the name that was included the lyric | Kaleigh |
| song | categorical, nominal | the song title | Galway Girl |
| person | boolean | whether the name likely refers to a person (as opposed to a drug, band, etc) | true |
| sentence | categorical, nominal | an example of the lyrics in the song that include the name | After dancing to Kaleigh, singing to trad tunes |
| year | categorical, ordinal | the earliest year that the song appeared on Billboard Hot 100 | 2017 | 
| highestrank | categorical, ordinal | the highest rank that the song reached on the Billboard Hot 100 | 53




