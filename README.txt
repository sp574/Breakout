This is an arcade game I built with a partner this spring. Total time spent on this was about 15 hours. The Breakout7.jar can be found in the repository and run on any computer. 
I also added extensions that were not required by the course.
Extensions: 
 * (1) We added looping background music and implemented sound effects to play when the ball
 * collides with different objects in the game.
 * (2) Also, a background image was added to create a more user-friendly atmosphere and a more graphic design of the game.
 * (3) We also added "hearts" in the top left corner of the game that show the player
 * how many lives they have left. The hearts are removed each time the player misses the ball
 * (4) Also, "Try Again" was implemented. When the player loses the ball 3 times, 
 * the game will promt the player to "Try Again" by clicking their mouse
 * (5) A big extension we added was "Power Ups". During the 'setup' part of the code, we randomly 
 * create 'power up bricks' using Math.random() and 'if-statements'. In order for this to work properly,
 * we had to create a separate class PowerUp that extends GRect. Basically, it has the same 
 * constructors in it as class Brick, except the constructors in class PowerUp add colors to 'power up bricks'.
 * 'Power up bricks' have a black outline, which separates them from the rest of the bricks. When a 'power up brick'
 * is hit, either the paddle will change in length or the speed of the ball will decrease/increase. 
 * Overall, these extensions were added with the main concern of creating a more enjoyable game while satisfying
 * the assignment specifications and not going over the scope of the course. By these graphical features that we added, we
 * believe the game is more enjoyable and interacts more compactly with the user.