MS-speech-recognition
=========================

MS is a speech recognition assistant, which will use many API to get a maximum integration with every software on your system. For the moment MS can just control (in a minimalistic way) Banshee to play music, stop it and change the song.
Also, the algorithm to match what the user says is bad for the moment, but I'm working on it.
For the speech recognition, it uses Google Speech or PocketSphinx, but I can not get good results with PocketSphinx for the moment, so I advise you to use Google Speech.

Dependencies :
---------------

1. PocketSphinx
2. Python 2.7
3. Gstreamer
4. espeak

For Linux : 

  1. sphinxbase-utils
  2. python-sphinxbase
  3. pocketsphinx-utils
  4. gstreamer0.10-pocketsphinx
  5. python-minimal
  6. espeak


How to :
--------

For the moment there are 3 ways to use MS :

1. launch "ms.py" and interact with MS by typing.
2. Speech Recognition using Google Speech :launch "google-speech.py" and interact with MS by voice.
3. Speech Recognition using PocketSphinx : launch "pocketsphinx-recognition.py" and (try to) interact with MS(doesn't give good results for now).
