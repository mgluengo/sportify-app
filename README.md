![Header](https://raw.githubusercontent.com/mgluengo/sportifyapp/master/images/header.png "Header")

## Concept

> :point_right: [Find here the full project presentation](https://speakerdeck.com/mgluengo/sportify-app)


Sportify is the ultimate app for sports lovers!  

The app **finds venues for specific sports** wherever you are, keeps you up to date with the latest **sports events** in your area, and suggests the perfect **playlists from Spotify**, so you can give it all while you work out! :running_woman: :notes:

![mockup](https://raw.githubusercontent.com/mgluengo/sportifyapp/master/images/mockup.png "Mockup")

## Challenge

- :woman_student: **Context**: 3rd project for the **Data Analytics Bootcamp** at Ironhack (April 2022). 

- :dart: **Goal**: put our knowledge of **APIs** and **web scraping** into practice. 

- :stopwatch: **Time**: during the bootcamp we worked in **hackathon** mode, so the full project (ideation, design, development, and final pitch) was completed in **3 afternoons**. 


## Tech
[![Python](https://img.shields.io/badge/Python-F7DF1E?style=for-the-badge&logo=python&logoColor=white&labelColor=101010)]()
[![Pandas](https://img.shields.io/badge/Pandas-3A1C66?style=for-the-badge&logo=pandas&logoColor=white&labelColor=101010)]()
[![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-232F3E?style=for-the-badge&logo=beautifoul-soup&logoColor=white&labelColor=101010)]()
[![Spotify](https://img.shields.io/badge/Spotify_API-3DDC84?style=for-the-badge&logo=spotify&logoColor=white&labelColor=101010)]()
[![Decathlon](https://img.shields.io/badge/Decathlon_API-14a1f0?style=for-the-badge&logo=decathlon&logoColor=white&labelColor=101010)]()
[![OpenCage](https://img.shields.io/badge/OpenCage_API-47A248?style=for-the-badge&logo=opencage&logoColor=white&labelColor=101010)]()
[![VSCode](https://img.shields.io/badge/VSCode-14a1f0?style=for-the-badge&logo=visualstudiocode&logoColor=white&labelColor=101010)]()

### Links to data sources:
- [OpenCage Geocoding API](https://opencagedata.com)
- [Decathlon sports places API + Decathlon sports ID](https://developers.decathlon.com/products/sport-places/docs)
- [Spotify API](https://developer.spotify.com/documentation/web-api/) *(Used 4 endpoints: Categories, Playlists, Tracks, and Devices)*
- [World's Marathons (web scraped)](https://worldsmarathons.com/)

## How it works

Based on the user's location and the selected workout, Sportify:
1. **Shows  sports venues** nearby to practice the sport they choose.
2. **Shows sports events** happening near them sorted by date.
3. Suggests **lists of songs** from Spotify to play while they work out + automatically plays songs on their device (authentication needed).

### User flow

![userflow](https://raw.githubusercontent.com/mgluengo/sportifyapp/master/images/userflow.png "Userflow")

### Behind the scenes

Task 1 - Find sports venues
![sportsvenues](https://raw.githubusercontent.com/mgluengo/sportifyapp/master/images/sportsvenues.png "Venues")

Task 3 - Suggest playlists for workouts
![playlists](https://raw.githubusercontent.com/mgluengo/sportifyapp/master/images/sportsmusic.png "Playlist")

## MVP Limitations

### Data limitations
- **Sports venues**: 
  - Most common sports only (e.g. running, swimming, yoga).
  - Decathlon's API data sometimes incomplete/outdated.  
- **Sports events**: Lisbon only (demo purposes).
- **Playlists**: options predefined for sports available in this version.

### Other limitations
- **UI**: Sportify can only be accessed from the terminal.
- **Database** to store/access data not built yet (dataframes only). 

## Next steps
- **Data**: add sports events and venues for more locations, more music options.
- Build **database**.
- User **interfaces** (e.g. smartwatches and smart speaker devices).
- New **functionalities** (e.g. find sports stores nearby). 

## Team Members

[![GitHub](https://img.shields.io/badge/GitHub-asier3-F7DF1E?style=for-the-badge&logo=github&logoColor=white&labelColor=101010)](https://github.com/asier3)

[![GitHub](https://img.shields.io/badge/GitHub-mgluengo-F7DF1E?style=for-the-badge&logo=github&logoColor=white&labelColor=101010)](https://github.com/mgluengo)

[![Giada](https://img.shields.io/badge/Giada_Sartori-F7DF1E?style=for-the-badge&logo=&logoColor=white&labelColor=101010)]()

</br>

> *SPORTIFY: BE ACTIVE ANYWHERE YOU GO!*