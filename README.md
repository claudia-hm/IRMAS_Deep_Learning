# Instrument Recognition in Musical Audio Signals 
The goal of this project is to recognize and classify predominant instruments in music audio signals. To do so, we have implemented a VGG-like model that is trained with the Mel Log Spectrograms extracted from the data in the IRMAS dataset.

### Getting started
Download a copy of this repository. Extract the zip file and upload it to your drive. The path to the repository folder should be */content/drive/My Drive/DeepLearning_2020/*

Also, download the files in  https://drive.google.com/drive/folders/1PCZbU3EFrr0Ek2II3MtZ8QsX-o3S0cMA?usp=sharing and store them in */content/drive/My Drive/DeepLearning_2020/Data/*

### Prerequisites
Google Colab

### Running the tests
Run the whole notebook. Mount drive when prompted.

The code is structured in the following sections:

0. Preliminaries: mount drive, install required packages, imports, data checking and CPU/GPU warm-up.
1. Data loading and pre-processing: retrieve the audio filenames and compute the Log Mel Spectrograms for the whole dataset.
2. Create custom dataset used to gather batches of images.
3. Define the model: class creation and instantiation of the VGG-like model.
4. Hyperparameters setting
5. Actual training
6. Analysing the output incluiding testing

### Built With
* [PyTorch](https://pytorch.org) - An open source machine learning framework
* [Essentia](https://essentia.upf.edu) - Open-source library and tools for audio and music analysis, description and synthesis

### Authors
* [Claudia Herron Mulet](https://www.linkedin.com/in/claudiaherronmulet/) (claudia.herron01@estudiant.upf.edu)  
* Júlia Riera Perramón (julia.riera02@estudiant.upf.edu)
* [Sara Estévez Manteiga](www.linkedin.com/in/saraestevezmanteiga/) (sara.estevez02@estudiant.upf.edu)


### Acknowledgments
Xavier Favory, researcher at the Audio Signal Processing Lab at UPF, for the code provided to start this project.

Bosch, J. J., Janer, J., Fuhrmann, F., & Herrera, P. “A Comparison of Sound Segregation Techniques for Predominant Instrument Recognition in Musical Audio Signals”, in Proc. ISMIR (pp. 559-564), 2012

