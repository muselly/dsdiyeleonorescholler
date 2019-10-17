# dsdiyeleonorescholler

DataCamp Project: Emotions in Music 
Data Set Description

Dataset: http://cvml.unige.ch/databases/DEAM/

Overview: 
This dataset contains annotations of valence and arousal of 2058 songs. There are three types of data: annotations, metadata, musical excerpts (MEMD_audio), and features. The songs are separated in 3 set: 1 development set (744 songs) and 2 evaluation sets (1000 and 58 songs respectively)

Annotations: 
-	Annotations are either organized per song or per rater
-	Per song
o	Annotations of valence and arousal on a continuous scale [-1;1], only starting after 15 seconds (because of instability of ratings at start)
o	Annotations are done per 500ms (2Hz) of each excerpt (dynamic folder): data organized as song_id, sample_1500ms, sample_15500ms, … , sample_626500ms 
o	Average Ratings: averaged ratings (arousal an valence) values on a 9 pt scale [1,9]) of the whole song across raters (song_id, valence_mean, valence_std, arousal_mean, arousal_std) in the song_level folder 
-	Per rater
o	10 raters per song 
o	Rated general values of arousal and valence at song-level and at 2Hz 

Metadata: 
-	Artist, song title, start and end time of the segment, genre

Audio files:
-	45 s excerpts (except for the 2015 evaluation set for which the full songs were annotated) 
-	44100Hz of frequency sampling

Features: 
-	For each 45s execrpt, the acoustic properties for each 500ms segments are listed 
o	There are about 261 properties for each 500ms segment
o	Not always clear what those features represent 




