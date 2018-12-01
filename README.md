LIRI BOT (LIRI is a Language Interpretation and Recognition Interface.)

# liri-node-app
Node Application using Spotify API, Bandsintown Api &amp; OMDB API 

#Module use 
1. dotenv (Reading Spotify Api )
2. fs (Read Random.txt)
3. keys 
4. Spotify (Node-Spotify-Api)
5. console.table (Display return data in tabular form)
6. Request (Request - Simplified HTTP client)
7. moment (library for parsing, validating, manipulating, and formatting dates.)

Screenshot: 

![FullApplicationScreenshot](https://github.com/rohitchhetri/liri-node-app/blob/master/screenshot/Screenshot.png)


How to use this LIRI Bot:
1. Download Project Folder in your desktop 

2. In terminal we use differnt condition 

    2a. node liri.js concert-this <anyartistname>
        Using Request Module here     
        ![concert-this](https://github.com/rohitchhetri/liri-node-app/blob/master/screenshot/concert-this.png)


    2b. node liri.js spotify-this-song <anysongname>
        Using console.table module to populate date in Table Structure
        ![spotify-this-song ScreenShot] (https://github.com/rohitchhetri/liri-node-app/blob/master/screenshot/spotify-this-song.png)
 
    2c. node liri.js movie-this titanic
        Using request module
        ![movie-this ScreenShot] (https://github.com/rohitchhetri/liri-node-app/blob/master/screenshot/movie-this.png)

    2d. node liri.js do-what-it-says
        Using fs module to read file from random.txt 
![do-what-it-says ScreenShot] (https://github.com/rohitchhetri/liri-node-app/blob/master/screenshot/do-what-it-says.png)

Enjoy !! 
