# Docu3C
AI Prompt Engineer ("The Bollywood Movie Analysis")

    
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
    
    Movie_Name - The name of the movie. 

    
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
    
    
**Procedure:**

Import necessary libraries for data analysis.
Analysing the gender importants and how the gender has shown in the movie.
Data cleaning for Machine Learning. 
Plot the dataset with graph as a visual representation.
Train the model with the dataset.
Machine Learning model using LinearRegression.
Find the accuracy of the model in testing the module.
Check the input from user and get the ouput - Male_Female_Centrality.ipynb
Comparision between two gender stereotypes with male and female like mentions and centrality.
Input plot script from the user and to find the Gender bias presence and the count of the gender in the given passage.

**Output**

we need mention_centrality, total_centrality, average_centrality as input and get count as output

**conclusion**

I think this analysis is enough for directors to understand inportants of the gender and find comman thing related between the genders and able to find the count through my analysis
