# Work-PAII.-CC
Trabalho de grupo de programação e algoritmos 2
 
 Trabalho de Grupo de Programação e Algoritmos 2
 Membros- Claúdia Teixeira, Cristiana Costa e Inês Costa 
 
 K-Pop Hits Through The Year 2020 & 2021

 ![Aespa_-_Savage](https://user-images.githubusercontent.com/104781648/172174382-c09c8061-5fbf-4efd-b537-ce211641fcee.jpeg)

 https://www.kaggle.com/datasets/sberj127/kpop-hits-through-the-years?resource=download&select=KPopHits2021.csv
 
 Dicionário: 
 
 title: Title of the song
 
 artist/s: The artist who sang or covered or made the instrumental of the song
 
danceability: How suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity. A value of 0.0 is least danceable and 1.0 is most danceable.

energy:Perceptual measure of intensity and activity based on its dynamic range, perceived loudness, timbre, onset rate, and general entropy. The values range from 0.0 to 1.0.

key: Key the track is in. Integers map to pitches using standard Pitch Class notation.

loudness: Overall loudness of a track in decibels. Loudness values are averaged across the entire track. Values usually range between -60 and 0 db.

mode: Type of scale from which its melodic content is derived. Major is represented by 1 and minor is 0

speechiness: Detects the presence of spoken words in a track. The more exclusively speech-like the recording, the closer to 1.0 the attribute value. Values above 0.66 describe tracks that are probably made entirely of spoken words. Values between 0.33 and 0.66 describe tracks that may contain both music and speech, either in sections or layered, including such cases as rap music. Values below 0.33 most likely represent music and other non-speech-like tracks.

acousticness: Confidence measure of whether the track is acoustic. Values range from 0.0 to 1.0. 1.0 represents high confidence the track is acoustic.

title	Song's Title
artist	Song's artist
genre	Genre of song
year released	Year the song was released
added	Day song was added to Spotify's Top Hits playlist
bpm	Beats Per Minute - The tempo of the song
nrgy	Energy - How energetic the song is
dnce	Danceability - How easy it is to dance to the song
dB	Decibel - How loud the song is
live	How likely the song is a live recording
val	How positive the mood of the song is
dur	Duration of the song
acous	How acoustic the song is
spch	The more the song is focused on spoken word
pop	Popularity of the song (not a ranking)
top year	Year the song was a top hit
artist type	Tells if artist is solo, duo, trio, or a band



About Dataset
What is the data?
The datasets contain the top songs from the said era or year accordingly (as presented in the name of each dataset). Note that only the KPopHits90s dataset represents an era (1989-2001). Although there is a lack of easily available and reliable sources to show the actual K-Pop hits per year during the 90s, this era was still included as this time period was when the first generation of K-Pop stars appeared. Each of the other datasets represent a specific year after the 90s.

How was it obtained?
A song is considered to be a K-Pop hit during that era or year if it is included in the annual series of K-Pop Hits playlists, which is created officially by Apple Music. Note that for the dataset that represents the 90s, the playlist 90s K-Pop Essentials was used as the reference.

These playlists were transferred into Spotify through the Tune My Music site. After transferring, the site also presented all the missing songs from each Spotify playlist when compared to the original Apple Music playlists.
Any data besides the names and artists of the hit songs were not directly obtained from Apple Music since these other details of songs in this music service are only available for those enrolled as members of the Apple Developer Program.
The presented missing songs from each playlist was manually searched and, if found, added to the respective Spotify playlist.
For the songs that were found, there are three types: (1) the song by the original artist, (2) the instrumental of the original song and (3) a cover of the song. When the first type is not found, the two other types are searched and are compared to each other. The one that sounded the most like the original song (from the Apple Music playlist) is chosen as the substitute in the Spotify playlist.
Presented is a link containing all the missing data per playlist (when the initial Spotify playlists were compared to the original Apple Music playlists) and the action done to each one.
The necessary identification details and specific audio features of each track were obtained through the use of the Spotipy library and Spotify Web API documentation.
Why did you make this?
As someone who has a particular curiosity to the field of data science and a genuine love for the musicality in the K-Pop scene, this data set was created to make something out of the strong interest I have for these separate subjects.

Acknowledgements
I would like to express my sincere gratitude to Apple Music for creating the annual K-Pop playlists, Spotify for making their API very accessible, Spotipy for making it easier to get the desired data from the Spotify Web API, Tune My Music for automating the process of transferring one's library into another service's library and, of course, all those involved in the making of these songs and artists included in these datasets for creating such high quality music and concepts digestible even for the general public.






