# Speech Emotion Recognition using Librosa library and MLPClassifier
In this project we build a model to recognize emotion from speech using the librosa and Multi Layer Perception Classifier (MLPClassifier) and RAVDESS Dataset. This will be able to recognize emotion from sound files. We will load the data, extract features from it, then split the dataset into training and testing sets. Then, we’ll initialize an MLPClassifier and train the model. Finally, we’ll calculate the accuracy of our model.

### RAVDESS Dataset
This is the Ryerson Audio-Visual Database of Emotional Speech and Song dataset, and is free to download. This dataset has 7356 files rated by 247 individuals 10 times on emotional validity, intensity, and genuineness. The entire dataset is 24.8GB from 24 actors.

Dataset on Google Drive: https://drive.google.com/file/d/1wWsrN2Ep7x6lWqOXfr4rpKGYrJhWc8z7/view

### Librosa Library
Librosa library is used to extract features from sound and music file. Features extracted are mfcc, chroma and mel features.
 - mfcc: Mel Frequency Cepstral Coefficient, represents the short-term power spectrum of a sound
 - chroma: Pertains to the 12 different pitch classes
 - mel: Mel Spectrogram Frequency

## Accuracy Achieved
On testing our model we achieved an accuracy of 75.97% which is good enough!

### Note:
The python notebook file in this repository was run on Google Colab. Since the dataset is uploaded on google drive we directly use that file in the colab. Benifits of using Colab: Fast Dataset Importing, Unzipping, Faster Processing Time, Get 100+ GB Disk Space and RAM of 12+ GB.
#### There is no reason not to use Google Colab ;)

This python mini project is just for educational purposes.
