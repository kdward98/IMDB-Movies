# IMDB-Movies

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tables](#tables)
- [Results/Findings](#Results/Findings)
### Project Overview
---

This data analysis project aims to provide insights into IMDB ratings of movies over the time span of 100 years (1920-2020). In addition to IMDB ratings, other areas that tie into the success rates of the films such as Gross,Meta Scores, Certification, Directors, and Runtimes. All of these things are looked into and evaluated to see what correlation if any have an effect on the overall success rates of the movies within this dataset. 

### Data Sources

IMDB_top_1000: The primary dataset used for this analysis is the "IMDB_top_1000.csv" file, containing detailed information about the top 1000 movies made over 1920 to 2020.The dataset was retrieved from Kaggle. Can be found here [https://www.kaggle.com/datasets/harshitshankhdhar/imdb-dataset-of-top-1000-movies-and-tv-shows]

### Tools

- SQL - Data Cleaning
- SQL Server - Data Analysis
- Tableau - Creating reports
### Data Cleaning/Preparation

In the initial data preparation phase, we performed the following tasks:
1. Data loading and inspection.
2. Handling missing values.
3. Data cleaning and formatting.

### Exploratory Data Analysis

EDA involved exploring the Movie data to answer key questions, such as:

- Is there a correlation between runtime and IMDB rating ? 
- Does meta score have any correlation to the overall gross of the films ? 
- What are the top 10 movies of all time and how many earnings have they accrued ? 

###  Tables 
gross of top 10 films based on imdb rating 
<img width="1109" alt="gross of top 10 films by imdb rating " src="https://github.com/user-attachments/assets/539b0e09-e368-42c7-99b6-0276826e2092">
runtime of top 10 films based on imdb rating 
<img width="1112" alt="runtime of top 10 films" src="https://github.com/user-attachments/assets/63d09b8e-d54b-4134-aa6e-5b176972886f">
movies made by certification type 
<img width="1116" alt="movies made by certification type" src="https://github.com/user-attachments/assets/e7681bb0-a347-4ad2-9a8c-7d94da61b853">
avg imdb rating per genre
<img width="1111" alt="avg imdb rating per genre " src="https://github.com/user-attachments/assets/14506c7c-2c46-4431-b413-4011cd30c201">
meta score ratings per genre
<img width="1118" alt="meta score ratings per genre " src="https://github.com/user-attachments/assets/38786406-ecaa-458f-a5c6-1edbb7dd8706">
earnings per genre
<img width="1117" alt="earnings per genre " src="https://github.com/user-attachments/assets/c4295808-8513-41f4-ab84-4e87406ee11c">
earnings per certificate
<img width="1116" alt="earnings per certificate " src="https://github.com/user-attachments/assets/c67bbc48-5091-487e-9c4d-ad49da681f59">
imdb ratings per director
<img width="1116" alt="imdb rating per director" src="https://github.com/user-attachments/assets/4e8e47be-863c-4952-b33d-1c64e1beaa25">
stars that appear the most 
<img width="1122" alt="stars that appear the most " src="https://github.com/user-attachments/assets/b8688835-abd7-4b8a-b77f-36ada987472e">

### visualizations 

![avg imdb rating per certificate](https://github.com/user-attachments/assets/12440cdf-ead0-43d6-aa6d-7188965b4b26)

![IMDB rating per genre ](https://github.com/user-attachments/assets/8f004cb5-6bae-4e26-8d5c-6d5602fe9d8d)

![meta score rating per genre](https://github.com/user-attachments/assets/c5444374-fdea-4c16-92f1-602efac3ab08)

![earnings per certificate ](https://github.com/user-attachments/assets/e569267b-6a2a-44cc-ac8d-02b92794c04f)

![avg imdb rating per director ](https://github.com/user-attachments/assets/dc0b3b2b-ebb3-4307-a4ac-be80f3ce14f5)

![Sheet 7-2](https://github.com/user-attachments/assets/6f034d6d-e6ae-43bc-953e-2e388d66b575)

![Sheet 6-2](https://github.com/user-attachments/assets/38f145f5-c38a-4f9a-948e-55f98e92133e)

### Results/Findings

The analysis results are summarized as follows:
1.Shawshank Redemption by Frank Darabont has the highest IMDB rating however, The Dark Knight by Christopher Nolan amassed the most amount of money among the top 10 films with the highest IMDB ratings. 
2.There seems to be a positive correlation between runtime and IMDB rating 
3.Certificate type U had the most  amount of movies fall under it, followed by A
4.Animation, Drama, War had the highest average IMDB rating at 8.5 
5.Mystery romance thriller had the highest Meta score rating at 100
6.Action adventure sci-fi had the highest gross earnings per genre 
7.Certificate UA amassed the highest total gross of all certificates 



