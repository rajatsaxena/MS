MS-speech-recognition
=========================

MS is a speech recognition assistant, which will use many API to get a maximum integration with every software on your system.

For the moment MS can just control (in a minimalistic way) Banshee to play music, stop it and change the song.
Also, the algorithm to match what the user says is bad for the moment, but I'm working on it.

For the speech recognition, it uses Google Speech or PocketSphinx, but I can not get good results with PocketSphinx for the moment, so I advise you to use Google Speech.

Later i want to build this project to understad what you are saying and reply to that and also answer your queries.


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


To Do:
----------

1. In the future, you will be able to set it in a configuration file.

2. When you write or speak to MS, it will search in all the .txt in the "data" folder if something match. Then it will launch the action set to this sentence (actions are in the "actions" folder).

3. Also integrating sppech recognition with actions. Depending on what you say MS should take necessary actions.

4. For example if you say play music it should reply by saying playing music and take the appropriate action.
