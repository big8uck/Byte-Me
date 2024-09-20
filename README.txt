There's now several different files as can be seen within the file. The AI is not meant
to be used by the user, although feel free to look at the code and how its being ran.
The AI file allows the file keep track of the ai the user is playing against and also
validate the user's moves (this hasn't been fully implemented yet). 

The camera.py is still under work, it needs to be slightly adjusted for the tracking
of the projection. We need to place a black mat on the table to do this, so we will
fully perfect it once this is done. Find dots will need to be also implemented fully aswell, as
it is dependent on camera.py.

The main, is going to be fully implemented with the find_dots.py once the camera is set up.
The main will then allow the user to move their pieces, which will be tracked by the camera.py 
and then the find dots will return and validate these positions.

The new file projection_try2.py can just be ran as long as tkinter is installed. Once it is ran
it will create a fully working Checkers game where the user (the black pieces) can be dragged and played
and the computer will play against the user. The moves are all valid and can also become king pieces,
if they reach the edge of the board.