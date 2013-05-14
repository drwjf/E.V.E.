Jarvis
=====

The beginnings of a Jarvis computer.
Jarvis will receive vocal or textual questions and return relevant web results accompanied by speech.

Based on Pi-Voice by Rob McCann.

Currently able to say a line of text that is hardcoded into the program. 

Dependencies:
pyaudio
audiotools
requests
pydub

Next Steps:
1. implement command parsing
2. catch exceptions such as no internet connection

Other Details:
-Jarvis should be able to execute a set of commands, 
 e.g. search, open, youtube. 
-Jarvis should handle errors with interpretation and ask for reiteration. 
-It would be nice if Jarvis could listen for the end of a query, 
but if not, Jarvis should be able to listen for as long as a button is pressed or at least for a specified amount of time.
