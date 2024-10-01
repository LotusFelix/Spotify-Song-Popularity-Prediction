# Spotify-Song-Popularity-Prediction
This project intelligently leverages machine learning to predict the popularity of a song

The data is drawn from here: https://www.kaggle.com/cnic92/spotify-past-decades-songs-50s10s. The only change that has been made is to the first column where "Number" has been re-named as "Id". 

This data repo contains 7 datasets (.csv files), each representing a Spotify's "All out ..s" type of playlist. Those playlists collect the most popular/iconic songs from the decade. 

For each song, a set of attributes have been reported in order to perform some data analysis. The attributes have been scraped from this amazing website. In particular, according to the website the attributes are:

top genre: genre of the song

year: year of the song (due to re-releases, the year might not correspond to the release year of the original song)

bpm(beats per minute): beats per minute

nrgy(energy): energy of a song, the higher the value the more energetic the song is

dnce(danceability): the higher the value, the easier it is to dance to this song.

dB(loudness): the higher the value, the louder the song.

live(liveness): the higher the value, the more likely the song is a live recording.

val(valence): the higher the value, the more positive mood for the song.

dur(duration): the duration of the song.

acous(acousticness): the higher the value the more acoustic the song is.

spch(speechiness): the higher the value the more spoken word the song contains.

pop(popularity): the higher the value the more popular the song is.

The performance of the model will be determined by the RMSE.
