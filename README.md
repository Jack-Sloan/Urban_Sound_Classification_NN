## Audio Classification
In this project, used PyTorch to create a Convolutional Neural Network for audio classification.

The dataset I used to train the model was imported from: https://www.kaggle.com/datasets/rupakroy/urban-sound-8k?select=UrbanSound8K_README.txt

This project was done on my local machine, and so the scripts contained in audio-info.ipynb and normalize_audio.ipynb will not work because some paths to placeholder folders are not included in this repository.

### audio-info.ipynb: 
Consolidates audio metadata into Excel files using FFmpeg bash commands (Audio_Metadata_0.xlsx is before preprocessing, Audio_Metadata_1.xlsx is after) 

### normalize_audio.ipynb
Preprocesses all 8732 audio files by normalizing sampling rate, bit depth, and volume for all files

### UrbSound_Classification.ipynb
This is the script for the Custom dataset class and Classification Neural Network