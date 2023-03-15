
# __Web Scrapping Popular Youtube Tech Channels with Selenium__
#### Data Mining, Data Wrangling, and Exploratory Data Analysis

<br>

## About the Data

Web scraping was performed on the _Top 10 Tech Channels_ on Youtube using _[Selenium](https://selenium-python.readthedocs.io/)_ (an automated browser (driver) controlled using python, which is often used in web scraping and web testing). 

<br>

## Sample of Data Collected

The average number of videos per channel was around 200.  In total, the data from 2000 videos was scrapped. 

## Sample Output(Clean Data)

![Screenshot (3979)](https://user-images.githubusercontent.com/33378412/225193184-b31021af-c1aa-4482-a3f0-5c442ff19871.png)

## Video Scraping Visualization

<img src="https://raw.githubusercontent.com/drusho/webscrape_youtube/main/reports/figures/word_frequency (wordcloud).png" >
  
<img src="https://user-images.githubusercontent.com/33378412/225193815-e535a953-34d5-483b-8b06-5173e7d1d73f.png" >

<img src="https://user-images.githubusercontent.com/33378412/225194977-52713fbc-c9f6-4f39-ae42-61221540d423.png">
<br>
<br>

## Take Aways

  <img src="https://raw.githubusercontent.com/drusho/webscrape_youtube/main/reports/figures/correlation (dataframe).png">

1. Video Comment numbers have very little correlation to any data that was obtained in this project.
   
2. The following seem to be seems to be highly correlated.
   * Channel Views and Subscribers
   * Interactions and Video Views

3. Video titles fall into 5 topic groups.

    #### Kmeans and PCA used to create clusters for video titles
    
    <img src="https://user-images.githubusercontent.com/33378412/225195396-0355447b-3e9b-4a7c-960a-f9b496afb687.png">

   * Iphone (kmeans 0)
   * Samsung (kmeans 1)
   * Reviews (kmeans 2)
   * Unboxing (kmeans 3)
   * How-to (kmeans 4)

4. 70% of the the most viewed videos are about phones.

   <img src="https://raw.githubusercontent.com/drusho/webscrape_youtube/main/reports/figures/top_10_youtube_videos_by_views (dataframe).png" >


5. Join Date (Date a Youtube Channel was created) does not seem to have any relationship to number of subscribers or overall cha

   <img src="https://raw.githubusercontent.com/drusho/webscrape_youtube/main/reports/figures/channels_ordered_by_join_date_(dataframe).png" >

<br>
<br>

## Colab Link

[Data Analysis of Youtube Tech Channels](https://colab.research.google.com/drive/1UxpBBsypGqUj7816zyvGNhJcPfaxBP_c?usp=sharing)
