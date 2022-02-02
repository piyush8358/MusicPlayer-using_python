# MusicPlayer using python  
Firstly Need to install pygame,tkinter and some music from anywhere
# #pip install pygame 
# #pip install tkinter 

# #Explanation of code functions:

First line imports the mixer module from pygame, then we import tkinter.
Next, we import the font module from the tkinter library. 

Tk() is a top level widget that is used to create the main application window in which we will be building our python project.song corresponding to the index which is passed.

Play() function is used to play the selected song , we use the .get() method to get the selected song, then we load the song and play it using the next two lines.

Pause() function is used to pause the song, we do not need to pass any argument to the mixer.music.pause() function.

Stop() function is used to stop the song, we use mixer.music.stop() function to stop the song.

Resume() function is used to resume the song using mixer.music.unpause() function.

Refernce :
https://data-flair.training/blogs/python-mp3-player/

https://www.studytonight.com/tkinter/music-player-application-using-tkinter
