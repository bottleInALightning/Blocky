# Blocky
Blocky is game in which you control a square snaking around the screen.<br> 
The main focus lays on the input box, in which you can insert python code to control blocky.<br>
Do md(4) to move Down 4 fields. (There is also mu (moveUp), mr (moveRight) and ml (moveLeft))<br>
Given variables for you to use are: isBarrierLeft, isBarrierRight, isBarrierTop, isBarrierBottom and isFinished(which seems to currently be broken<br>
The booleans for you to utilise in the parantheses are: isBarrierLeft,isBarrierTop,isBarrierRight,isBarrierDown and isFinished.<br>
As mentioned earlier, the interpreter(which is developed purely in python, without modules) is in development and yet not implemented in the main game.<br>
<br>
You can also manually move blocky via wasd after you clicked the "MM"-Button at the right which stands for manual moving.<br>
<br>
By pressing "q" you open the advanced level creator, by clicking once you set the start point, the second click sets the end point and afterwards you can add as many barriers as you wish to.<br>
If you are finished, just press "q" again and after you fire up the game a second time you should be able to play your level.(It is possible to create impossible and broken level :) )<br>
<br>
# How to run the game<br>
Install pygame [here](https://www.pygame.org/wiki/GettingStarted)<br>
<br>
Clone the repo:<br>
`git clone https://github.com/bottleInALightning/Blocky.git && cd Blocky && cd blocky`<br>
Windows:<br>
`python mainBlocky.py`<br>
Linux:<br>
`python3 mainBlocky.py`<br>
<br>
Enjoy, Lars
