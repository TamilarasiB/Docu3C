# Docu3C
AI Prompt Engineer ("The Bollywood Movie Analysis")


**WIKIPEDIA**
  **DATASET SOURCE:**
  Source: https://github.com/BollywoodData/Bollywood-Data
  
  **DESCRIPTION:**
  **male_mentions_centrality.csv** - Contains centrality and mentions of females in movies.
  It has a following column names:
    Movie_name - The name of the movie
    Cast - The male cast in the movie
    Mentions - Number of male characters mentioned in the movie
    Total Centrality - Total count of the centrality of male in the movie
    Count - The count of the male centrality in the movie
    Average Centrality - Average count of the male centrality in the movie
  **female_mentions_centrality.csv** 	- Contains centrality and mentions of males in movies in text.
  It has a following column names:
    Movie_name - The name of the movie
    Cast - The female cast in the movie
    Mentions - Number of female characters mentioned in the movie
    Total Centrality - Total count of the centrality of female in the movie
    Count - The count of the female centrality in the movie
    Average Centrality - Average count of the female centrality in the movie

    
**TRAILER**
  **DATASET SOURCE:**
  Source: https://github.com/BollywoodData/Bollywood-Data
  
  **DESCRIPTION:**
  **complete-data.csv:** It has gender and emotion information for each of the trailers. 
  It has a following column names:
    Frame_number - The frame number of the movie.
    Gender - Describes whether the frame contains male/female.
    Emotion - emotions expressed by the characters.
    Year - The year of the movie release.
    Movie_Name - The name of the movie
**Procedure:**
1. Import necessary libraries for data analysis
2. Analysing the gender importants and how the gender has shown in the movie
Data cleaning for ML
Train module
Mechine Learning model I used LinearRegression
Find the accuracy of the model in testing the model
Checking with input from user and get the ouput(MALE AND FEMALE mention centrality INPUT AND OUTPUT.ipynb)
Comparision between two gender stereotypes like mentions centrolity, adjective
Gender bias link:https://github.com/sutharsang631/bollyhood-movie-analysis/blob/main/gender%20bias.ipynb
Input plot script from the user and to find the Gender bias presence and the count of the gender in the given passage.

**Output**
we need mention_centrality, total_centrality, average_centrality as input and get count as output

**conclusion**
I think this analysis is enough for directors to understand inportants of the gender and find comman thing related between the genders and able to find the count through my analysis
