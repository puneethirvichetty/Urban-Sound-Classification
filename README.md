The Data Set Can Be Downloaded using the following link ( https://goo.gl/8hY5ER ). It downloads a compressed tar file of size around 6GB.
On extracting it, it contains two folders named 'audio' and 'metadata'.
Audio folder contains 10 folders with name fold1, fold2 and so on, each having approximately 800 audio files of 4s each.
Metadata folder contains a .csv file having various columns such as file_id, label, class_id corresponding to label, salience etc.
Complete description can be found here https://urbansounddataset.weebly.com/urbansound8k.html
## Research Paper and Resources I followed :
- https://github.com/meyda/meyda/wiki/audio-features
- https://github.com/tyiannak/pyAudioAnalysis/wiki/3.-Feature-Extraction
- https://medium.com/@ageitgey/machine-learning-is-fun-part-6-how-to-do-speech-recognition-with-deep-learning-28293c162f7a
- https://towardsdatascience.com/urban-sound-classification-part-1-99137c6335f9
- https://www.analyticsvidhya.com/blog/2017/08/audio-voice-processing-deep-learning/
## Library I used
- ### Librosa
 - which can be installed using
 > pip install librosa
- Librosa library can read audio files and convert them to there amplitude values for each sample of audio. Let us say there is an audio file of 4s and sampling rate of audio file is 22050 Hz. This means that audio file is made using amplitude samples such that 22050 samples of amplitudes are recorded in each second. Hence a 4s audio file with sampling rate 22050 can be expressed as an array of 4*22050=88200 size
- ### Used CNN TO classify Sound
