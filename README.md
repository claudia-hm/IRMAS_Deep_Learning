# Instrument Recognition in Musical Audio Signals 
The goal of this project is to classify instruments in music audio signals. To do so, we have implemented a VGG-like model that is trained with the Mel Log Spectrograms of the data in the [IRMAS](https://www.upf.edu/web/mtg/irmas) dataset.

### Getting started
Download a copy of this repository. Extract the zip file and upload it to your drive. The path to the repository folder should be */content/drive/My Drive/DeepLearning_2020/*

The data folder in this repository only contains the spectrograms and labels necessary to train and test the model. It does not contain the audio files from where we extracted the images (3.2 GB). However, they are not needed to train and test the model. It may only be needed to recompute the spectrograms or test spectrogram functions, but this is not the goal of the project. To download the whole dataset follow this [link](https://drive.google.com/open?id=1PCZbU3EFrr0Ek2II3MtZ8QsX-o3S0cMA).



### Prerequisites
Google Colab

### Deployment

Run the whole notebook. Mount drive when prompted.

In case you have downloaded the whole audio data you can test spectrogram files and recompute the spectrograms (estimated time 30 minutes) by changing the variable AUDIO_FILES to True.

### Built With
* [PyTorch](https://pytorch.org) - An open source machine learning framework
* [Essentia](https://essentia.upf.edu) - Open-source library and tools for audio and music analysis, description and synthesis

### Authors
* [Claudia Herron Mulet](https://www.linkedin.com/in/claudiaherronmulet/)
* Júlia Riera Perramón
* Sara Estévez Manteiga

### Acknowledgments
Xavier Favory

