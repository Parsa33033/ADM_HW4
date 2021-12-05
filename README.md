# ADM_HW4

#### Due to the difficulties of pushing large files and folders, we have not included large files in the repository. But, further instructions are provided in the notebook for running the code and how to add necessary files to the project.


## Files and folders descriptions

1. __`AudioSignals.ipynb`__:
   > This script has only been used for one of it's functions and we have actually created our own functions for getting the peaks and 
   > signatures from a song.
   > the only function that has been used from this script is load_audio_picks()
2. __`dataset.csv`__:
   > This is a dataset containing the infomation for the songs in the mp3s-32 folder. 
   - Note: due to the large size of mp3s-32k folder we have not pushed it to the repository. But affiliated instructions of where to include the folder is provided in the homework4.ipynb notebook file if further running of the code is necessary.
    - Each row contains the information as below:
        - title: the title of the song
        - band: the name of the band
        - album: the name of the album
        - track: the path to the song in the data folder which contains all the wav files
3. __`homework4.ipynp`__:
   > The main jpyter notebook which contains the answers to the questions of the homework number 4.

4. __`song_buckets.pkl`__:

> A pickle file containing the dictionary created which serves the same purpose as buckets for LSH.

5. __`song_minhash_signature.csv`__:

> This is a dataset containing the minhash of each song with its title
- Each row contains:
    - index: index of the song in the dataset.csv
    - title: the title of the song
    - artist: the name of the artist
    - minhash_signature: the minhash signature of the song