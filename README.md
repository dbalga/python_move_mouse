# python_move_mouse

If you sometimes work from home (home office), you know the situation when you need to skip somewhere for a while... If you do it, your computer begins to light on orange (Teams status icon), you are "not available" and your coworkers start to ask where were you so long... 

My script written in Python is checking every x seconds (it is a variable) if  your working day  is at the end already, and if it is not yet, it is moving your mouse very quickly to the Start button and clicks to avoid your computer / Teams go to the "not available" state. At the beginning, the scripts checks the resolutions of your screen to be able to precisively hit the start button as well as the curernt time (checking the end of the working day).
The part of the script is a logging system which creates a text file and writes a time stamp after every iteration of the script.
