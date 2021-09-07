# LL Basics: Datasets

### Overview
These are example datasets that are open source, cleaned, and free to use for whatever project you would like to use them for. 


## Names in Lyrics

This dataset analyzes songs from the US Billboard Hot 100 from 1958-2017, identifying names from their lyrics. A more complete description of how the data was collected, as well as the visual essay, can be found in the source link.



- Source: [Names in Pop Songs, Data World](https://data.world/the-pudding/names-in-pop-songs)
- Gitfile: [names_in_lyrics.csv](https://github.com/learninglab-dev/ll-basics-datasets/blob/main/names_in_lyrics.csv)
- Cleaning: None


Number of Entries: 20,626

| Column Name | Data Type | Description | Example | 
| ----------- | --------- | ----------- | ------- |
|artist | categorical| the name of the artist or band who sang the song | Ed Sheeran | 
| name | categorical | the name that was included the lyric | Kaleigh |
| song | categorical| the song title | Galway Girl |
| person | boolean | whether the name likely refers to a person (as opposed to a drug, band, etc) | true |
| sentence | categorical| an example of the lyrics in the song that include the name | After dancing to Kaleigh, singing to trad tunes |
| year | categorical| the earliest year that the song appeared on Billboard Hot 100 | 2017 | 
| highestrank | numerical, ordinal | the highest rank that the song reached on the Billboard Hot 100 | 53

Example Questions: 
- Which is the most referenced name ever?
- Which song includes the most different names? 
- Do different names trend in different years? 

## COVID-19 Data

This case surveillance public use dataset has 19 elements for all COVID-19 cases shared with CDC and includes demographics, geography (county and state of residence), any exposure history, disease severity indicators and outcomes, and presence of any underlying medical conditions and risk behaviors. 



- Source: [CDC](https://data.cdc.gov/Case-Surveillance/COVID-19-Case-Surveillance-Public-Use-Data-with-Ge/n8mc-b4w4)
- Git file: 
- Cleaning: This file is updated every two weeks and the original dataset has 27million+ entries. To make this more accessible, the file has been reduced to January - June 2021. 



Number of entries: 

| Column Name | Data Type | Description | Example | 
| ----------- | --------- | ----------- | ------- |
| case_month | categorical, ordinal| date related to the illness of specimen collection, or date received by CDC | 2020-06| 
| res_state | categorical | State of Residence |OH | 
| state_fips_code | categorical | State FIPS code |39|
| res_county | categorical | County of Residence |Belmont | 
| county_fips_code | categorical | County FIPS code | 39013| 
| age_group | categorical, ordinal | Age group (0 - 17 years; 18 to 49 years; 50 to 64 years; 65 + years; Unknown; Missing; NA, if value suppressed for privacy protection.) | 0-17 years |
| sex | categorical | sex F/M/Unknown/Missing/NA | NA |
| race | categorical | race identification | White |
| ethnicity | categorical |hispanic or not | Not Hispanic |
| case_positive_specimen_interval | qauntitative | weeks btwn earliest date and adate of first positive test | 0 |
| case_onset_interval | quantitative | weeks between earliest date and date of symptom onset | 0|
| process | categorical | method of identification | Clinical Evaluation | 
| exposure_yn | categorical | essentially, were they quarantining or were they doing things that could have exposed them to covid? | Yes | 
| current_status | categorical | current status of this person? | Confirmed case |
| symptom_status | categorical | Symptomatic status of this person? | Symptomatic
| hosp_yn | categorical | was the patient hospitalized? | No| 
| icu_yn | categorical | admitted to ICU? | No| 
| death_yn |categorical | did they die? | No | 
| underlying_conditions_yn | categorical | Did they have an underlying condition on this (list)? | No | 

Example Questions: 
- What is the probability that, if a patient is hospitalized, they are also admitted to the ICU? 
- Which demographic(s) are most represented in the data? 
- Are there correlations between demographics, underlying conditions, and death rates? (It has become increasingly evident that our medical system has glaring disparities in how patients of different races and genders receive treatment. Are there any patterns here that reflect that?)

## Academy Award Winners

Description 

- Source: [Kaggle](https://www.kaggle.com/dharmikdonga/academy-awards-dataset-oscars)
- Git file: [Link](https://github.com/learninglab-dev/ll-basics-datasets/blob/main/oscars.xlsx)
- Cleaning: None



| Column Name | Data Type | Description | Example | 
| ----------- | --------- | ----------- | ------- |
| year_film | categorical | the year in which the film was released | 1999 |
| year_ceremony | categorical | oscar ceremony year | 2000 | 
| ceremony | categorical, ordinal | oscar ceremony number | 72 |
| category | categorical | the oscar award category | Costume Design |
| gender | categorical | gender of the nominee | Female |
| name | categorical | name of the nominee | Jenny Beaven |
| race | categorical | race of the nominee | White |
| film | categorical | name of the movie | Anna and the King |
| winner | binary | false (nomination), true (winner) | false | 

Example Questions: 
- What is the ratio of female nominees and winners to male nominees and winners? 
- Which movie was nominated for the most awards? Which actor/actress? Which won the most? 
- Have the oscars become more diversified over time? Along which axes? 

