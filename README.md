# spotify-wrapped-analysis

## Motivation
Each year since 2016, Spotify has released a "Wrapped" for each user, a feature that summarizes a user's listening habits over the past year. It provides users with a personalized summary of their top artists, tracks, and genres, as well as some other interesting statistics about their listening habits. The feature is usually released in early December and is a popular way for users to reflect on their music consumption over the past year and discover new artists and tracks they may have missed.

The features gives some insights in your personal listening habits, but it is rather on the superficial side. The project is therefore intended to provide a deeper insight into personal listening behavior on Spotify. Based on the membership duration on Spotify, the listening behavior of the past years can also be analyzed or compared to the previous years.

## General info
To get started with the project, you first need your streaming data. The data for this project can be requested directly from Spotify and will be sent to the user after about a period of 1-3 weeks. The Advanced streaming history should be requested for the project, as it also includes streaming data from previous years.

Link to request data:
https://www.spotify.com/de/account/privacy/

The data is sent to you in several json files and has the following columns:

<img width="642" alt="image" src="https://user-images.githubusercontent.com/84801791/211161739-0d4e9340-f1b7-462b-9d6f-a78d231b9238.png">

<img width="625" alt="image" src="https://user-images.githubusercontent.com/84801791/211161752-eca8102f-d841-4cda-9f0a-37e233fbd054.png">


### Data-Preparation
The Juypter-Notebook "Spotify-Data-Extended-Project.ipynb" will show the steps to bring the data in shape to work with.

<ins>Steps included:</ins>
- combine jsons to one dataframe
- separate music streaming history and podcast streaming history
- extend dataframe with additional infos
- calls to Spotify-API to get additional data like genres to your data
- formatting of data

The output of the Data-Preparation-Process will be a cleaned csv-file to work with.

## Visualization
Since the data is now in the appropriate format with additional information, it can be visualized with a suitable software or packages.<br>
I used Tableau to visualize my personal music streaming data from Spotify in a dashboard style.

Link to Visulization:
https://public.tableau.com/app/profile/tobias3760/viz/Spotify-Wrapped/Spotify-Wrapped


## Analysis
This dashboard will now allow you to get a more in-depth look at your personal streaming history over the past few years.

Potential insights:
- number of new discover artists
- total streams each year
- time spend or play on spotify each year
- favorite and most listened artists
- most listend tracks
- top genres you have listened on spotify
- listening behavior based on month, weekday or by hours
- trends over these years and many more...


