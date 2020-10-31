Download data from here :  https://www.dropbox.com/s/4jw31k5mlzcmgis/genres.tar.gz?dl=0
Goal : Given audio files for songs , identify which genre they fall in 

First, the audio file currently in .au format needs to be converted the .wav format. I used SOX to convert the audio files to .wav format. 
The convert-to-wav.py file converts the .au audio files to .wav audio files

MusicGenreIdentification_features.ipynb file processes the features for the audio files in .wav format. The following features have been extracted from the Spectrogam:

Mel-frequency cepstral coefficients (MFCC)(20 in number)
Spectral Centroid,
Zero Crossing Rate
Chroma Frequencies
Spectral Roll-off.

The extracted features are stored is in genres_data.csv file.
The rest is the Data Modelling part.

