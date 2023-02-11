
<p align=center>
 <img src="../master/gameplay.gif" width=700 height = 450/>
</p>

# Brick Breaker 🎮 








A visually appealing and interactive Brick Breakout Clone made using C++. 

It was made as a final project for my course Introduction to Computing CS101 during my 1st Semester at [National University of Computer and Emerging Sciences](http://nu.edu.pk/).

## How to Run

There's a file named "Brick Breaker.exe". Just run it and the game will start.

If "Brick Breaker.exe" isn't working then the game can be compiled using any of the two ways:

1) The project is compiled using Code Blocks. So, there is a file named "Typing Tutor.cbp". Open it in Code Blocks and the whole project will load up with all files. Then just click "Build and Run" and the game will start. {Add the libgdi32 library in Code Blocks using project->build options->linker settings-> add button (find libgdi32 for your compiler)} 

2) To have the best experience it is HIGHLY RECOMMENDED to compile the main.cpp file of the game using G++
using the command:
 ```g++ -o main.exe mygraphics.cpp myconsole.cpp main.cpp - lgdi32```

## Screenshot

<img src="https://drive.google.com/file/d/18eTdkKtkq81dP-KScJRoJMr5DFkXW1uR/view?usp=share_link" width=700 height=450></img>

About My Game:                      
-----------------------------

--  The game's Interface consists of a mesmerizing menu, a thriving ball and a large number of colored bricks.
 
 --The goal of the game is to prevent the **ball** from crossing the screen's lower boundary whilst scoring as many points as the player can.
 
 -- A Player is provided with 3 lives. Each time the ball misses the paddle on life is deducted and when lives reaches 0, the game ends.
 
--  When the moving moving ball collides with player's paddle it gets **deflected** in the opposite direction and continues its motion until it collides with another surface.

--  The game also consists of colorful bricks which at first glance do appear to be random but each color signifies the brick's **health**.
   
--  The more saturated the brick is, the more power it holds. Some bricks even also take almost 3 Collisions to break!

--  Furthermore, some bricks also hold a **fireball** effect which enables the ball to destroy everything in its way regardless of its health! 
    
-- The game has the facility to save and load as well allowing the player to save his progress and resume it at a later time.

-- In addition to all these, the game also stores the record of 5 highest scores ever making it much more competitive and entertaining.  

--  In order to win the game, the player must break every brick in the game.

<b>P.S: There is a hidden Easter egg in the game so try find it if U can as well ;).</b>

Enjoy !!!!!!!

<h2>Controls:</h2>
<li>On the welcome screen press <b>C</b> to continue.</li>
<li>To access the options available in the main menu press their respective numeral 	     		 key, for instance, to access <b>New Game</b> press <b>1</b> respectively.</li>
<li> Press <b>A</b> to move the paddle in <b>Leftward</b> direction. </li>
<li> Press <b>D</b> to move the paddle in <b>Rightward</b> direction. </li>
<li> Press <b>P</b> to  <b>Pause</b>. </li>
<li> Press <b>R</b> to  <b>Resume</b>.  </li>
<li> Press <b>Q</b> to  <b>Quit</b> .</li> 
<li> Press <b>S</b> to  <b>Save</b> .</li> 
   
