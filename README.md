<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Chinese Song Recommender
*Any song you want, we can find you a Chinese match*

*Data-analytics, BCN & October-2020*

## Project Description
Chinese_song_recommender - 
In summary: 
1. User inputs a song. 
2. If the song is the Billboard Top100, the program will output another song from the Billboard top 100. For this we used webscrapping from the Billboards100 and worked with a panda dataframe
3. If it isn´t in the top 100, the program uses the spotify API to suggest you a chinese song from a random song someone decides to input. For this we had to first use the API to find the audio features of the user_input. Then we created a large playlist of chinese songs. Of which we create a panda data frame of their audio features.  Once we have this playlist we use clustering to divide songs into different groups by audio features.  For this we used advanced methods like clustering, kmeans. Once we had this, we would return another random output from the playlist clusters created. 
