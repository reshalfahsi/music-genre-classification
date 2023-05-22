# Music Genre Classification

Classify input audio into a particular genre of music. First, the audio is preprocessed via [MFCC](https://en.wikipedia.org/wiki/Mel-frequency_cepstrum). Next, using MLP, we obtain the probability distribution of 10 classes of music genres. Before applying MLP to the MFCC, the cepstral coefficients with the length of the number of sequence of time has to be averaged and subjected to [CMVN](https://en.wikipedia.org/wiki/Cepstral_mean_and_variance_normalization). The project is available in [this notebook](https://github.com/reshalfahsi/music-genre-classification/blob/master/MusicGenreClassification.ipynb). It covers:
 
 - Step-by-step MFCC from the Scratch with Visualization

   <p align="center"> <img src="https://github.com/reshalfahsi/music-genre-classification/blob/master/mfcc.png" alt="MFCC" > </p>

 - MFCC + ANN

   <p align="center"> <img src="https://github.com/reshalfahsi/music-genre-classification/blob/master/classification.png" alt="Classification" > </p>

## Credit

 - [Vanilla STFT and MFCC](https://github.com/brihijoshi/vanilla-stft-mfcc)
 - [GTZAN Dataset](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification)
 - [Librosa](https://github.com/librosa/librosa)
 - [SpeechPy](https://github.com/astorfi/speechpy)
 - [PyTorch Lightning](https://github.com/Lightning-AI/lightning)
