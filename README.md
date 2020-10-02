# NINA-Dataset-Demo

The video, along with its relative subtitle file, shows the environmental sensing activity for road safety relying on audio stream captured inside the car cabin.
Audio recognition model is trained upon the NINA Dataset.

Subtitles show the class of the event detected as long as all the other classes with relative probabilities (in smaller fonts).

The {file}.mkv audio track is split and in spectrogram segments and each segment classified with a previously trained CNN model.

To note that each segment lasts about 0.5s, and only one class is assigned to a segment. Therefore, if the event falls at near the end of the segment, the class will be assigned since the beginning resulting in a small delay between the displayed class and the event itself.

## How to reproduce the demo
* Open the {file}.mkv file with VLC (or any other video player)
* Add the subtitle_{file}.srt subtitle file. On VLC: Subtitles menu -> add subtitle file...
* Enjoy the demo

