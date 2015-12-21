This is a game made with instructor's consent for COMP 2611 project.
<br>*Author: BAI Chunyan

How to play:

Required: MARS(Any version with tools).

You will be needing Bitmap Display and Keyboard and Display MMIO simulator under "Tools" in MARS.

Open Bitmap Display and Keyboard and Display MMIO, connect them to MARS.
The Bitmap Display configuration:
Unit Width: 8						     
Unit Height: 8						     
Display Width: 512					     
Display Height: 512					     
Base Address for Display: 0x10008000 ($gp)

Assembly the code and run it, you'll see a blue snake appearing on the bitmap display. If not, go back to the top of this document and follow the instructions again.

The keyboard input is to be read into the Keyboard MMIO, so make sure to put the cursor there, and in this game, W-up, A-left, S-down, D-right. When one of these keys is pressed, the game starts.

The game ends when the snake hits itself or hits the border.

If any bug occurs during the game, restart it.

Enjoy!

Features of this game:
* Classic and user-friendly interface.
* Control the snake using keyborad(WASD) smoothly.
* The snake is able to eat a randomly-generated block and increase its length.
* The block is generated so that the probability of it colliding with the snake is nearly 0.
* The difficulty will increase each time when one of a set of particular scores was reached.
* The score is counted implicitly(not shown all the time on screen), the score for each block will increase every time the difficulty increases.
* The game ends when the snake hits itself or hits the border. A dialog window with message and your score will be shown, there will be a play again option afterwards.
* Well functioning and almost no bug will occur.
