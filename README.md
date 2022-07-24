# Bird-Audio-Recognition
### This project has been executed by making a sliding window that classifies different chunks of audio.
the data is taken from the Z by HP Unlocked Challenge 3 dataset.
Mel spectrograms were extracted for all of the Audios in "Spectrogram_extraction.ipynb"
in the file "data_preprocessing.ipynb"is the data is prepared to be trained on the ML model.
The 'model.ipynb' file is then used for training the model on the data.
Finally as sliding window is created across the audio in file "Sliding_window.ipynb", which divides the audio wrt average capuchin bird call intervals and then feeds it to the classifier
