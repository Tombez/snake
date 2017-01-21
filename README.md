# Snake

Want to play snake? Go ahead! ---> [Take me to it.](https://tombez.github.io/snake/)
Try to beat my highscore of 84!

### --- 17-1-2017 D-M-Y ---

This project started two years ago when I made a snake game while learning JavaScript.

Recently I looked at the code I had written, and cringed.
So I made a fresh version of the game 'snake' with my current knowledge.

The fresh version is called 'snake.html'.
The old version is called 'SnakeGameOld.html'.
	It also needs 'SnakeGameOld.js'.
	The code has not been touched for two years, and will never be updated.

The end goal is to develop an algorithm that will beat the snake game everytime.
	(With A*)

The restrictions to the algorithm are similar to a humans,
in the sense that the information given to it is limited.
Only including:

	‣ A two dimensional array of objects representing the squares of the game,
		each has a boolean named 'taken' representing whether there is a snake in that tile.
	‣ A one dimensional array of objects representing the segments of the snake,
		in order from tail to head, each containing an 'x' and 'y' property.
	‣ An integer that when used as an index, corresponds to a point object,
		that when added to another point, moves it in one of four directions,
		right, up, left, or down. In that order.
	‣ A 'point' object named 'apple' representing the location of the apple,
		it contains two integer properties 'x' and 'y'.
		
In addition, it is only allowed to affect the game by simulating user-input.

# Checklist
Things I plan to add to the code:

	‣ A settings panel for the user,					(I know how)
		possible variables they could change:

		‣ Game speed.
		‣ Number of columns.
		‣ Number of rows.
		‣ Tile size.
		‣ Colors. (Maybe)

	‣ Use an icon for the apple.						(I know how)
	‣ Draw only what is needed to the canvas.			(I know how)
	‣ A 'playerBot' which is described above.			(I don't know how)
	‣ Make an implementation in Java.					(Maybe)
	
Things I have already added:
	
	‣ Improved user-input to feel more responsive.
	‣ Made a 'rainbow mode', which draws the snake rainbow colored.
	‣ Simpler code from the original two years ago.
	‣ Removed sound effects. Ew.
	‣ Styled it a little better.
	‣ Improved page formatting.
	‣ Added instructions.
	‣ A cool font.
	‣ Multiple death messages.
	
This entire document is subject to change at any time. (Especially if I make typos.)