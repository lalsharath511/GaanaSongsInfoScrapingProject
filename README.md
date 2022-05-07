# GaanaSongsInfoScrapingProject
This Web Scraping Project Here we have collected Malayalam songs info from https://gaana.com/album/malayalam

# scraping malayalam song titles and track on Gaana

TODO(intro):
 - Introduction about web scraping
 - Introduction about Gaana and problem statement
 - Mention the tools you are using(Python,request,Beautiful Soup,Pandas)
 
 
 Here are the steps we follow:
 - We are going to scrape https://gaana.com/album/malayalam
 - We will get a list of topics.For each topic, we'll get topic title,topic page Url
 - For each topic,we'll get 40 topic from the topic page
 - For each title page, we will get track name,artist name,duration,track url
 - For each topic we will create a csv file in the following format:
 
 track_name,artists_name,track_duration,track_url
 Teaser Theme,Ravi Basrur,02:16,https://gaana.com/song/teaser-theme-from-kgf-chapter-2-1
  
  
  # scrape the list of song titles from Gaana
  
  explaning how we will do it.
  
  - use requests to download the page
  - user BS4 to parse and extract information
  - convert to a Pandas dataframe
  
  
  
  # write a single function to:

1 get list of titles from the titles page
2 get list of all tracks from individual titles
3 for each titles create csv of the track for the title
  
