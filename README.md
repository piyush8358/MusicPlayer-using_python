# MusicPlayer using python  
Firstly Need to install pygame,tkinter and some music from anywhere
# #pip install pygame 
# #pip install tkinter 

# #Explanation of code functions:

First line imports the mixer module from pygame, then we import tkinter.
Next, we import the font module from the tkinter library. 

Tk() is a top level widget that is used to create the main application window in which we will be building our python project.song corresponding to the index which is passed.

The title() method is used to give a name to python mp3 player application which is displayed at the top.mixer.init() is used to initialize the mixer module so that we can use it’s various functions in our application.

Listbox() widget is used to create a listbox in which we will store our songs.

We have passed various parameters, first is the root specifying that the widget should be placed in the python mp3 player window.

Then, bg is for background color, fg is for foreground color.selectbackground and selectforeground basically change the background and the foreground color of a particular item upon selecting it.grid() widget is a geometry manager which organizes the widgets properly in a grid-based fashion before placing it in the root window. columnspan=9 gives a space of 9 columns to our listbox widget.

Button() widget is used to create a button. We want the buttons in our main window so the input root is given. Then the text which will be displayed on the button is specified and at last in the command input a function is given which will be called when the button is clicked.

Play() function is used to play the selected song , we use the .get() method to get the selected song, then we load the song and play it using the next two lines.

Pause() function is used to pause the song, we do not need to pass any argument to the mixer.music.pause() function.

Stop() function is used to stop the song, we use mixer.music.stop() function to stop the song.

Resume() function is used to resume the song using mixer.music.unpause() function.

Refernce :
https://data-flair.training/blogs/python-mp3-player/

https://www.studytonight.com/tkinter/music-player-application-using-tkinter

# Demo Video of MusicPlayer :
https://user-images.githubusercontent.com/96904569/152142750-d6a2c173-f99e-448e-b5f9-82284e15286e.mp4

