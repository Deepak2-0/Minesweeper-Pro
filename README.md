# Minesweeper-Pro
Question and Rules
The game we designed in Bomberman-1 was all based on luck. Let's extend the same game with the same 9x9 grid and try to help our fellow users get a path to win. But how?


Whenever a user clicks on a cell he/she should be able to see a number based on the following conditions:
Consider a rectangular area around the cell clicked.

Calculate the number of bombs contained in that area.


Display the number in the cell.



One might think what about the cells at the extreme edges

Worry Not!
Consider the following images. These will help you consider various edge cases.








How will it help?
By clicking on various cells user may be able deduce which cells contain bombs. Following the same pattern the user may complete the game.

Users first! 🙏
You have helped users a lot by guiding them the path, but what if they could remember their conclusions out of those helping paths?
For example: The user is sure that some cell contains a bomb, they may want to remember it so that they don't have to make calculations again and again.

Let's get to the point.
Give the users an option to flag a cell as follows:

When users right-clicks on a cell they should see something like this.




This way users can remember that they concluded there's a bomb in that cell and should not click it. If a user left-clicks on this flagged cell, normal flow should continue.

Time for celebration 🎉
If a user has scored 72 points it means he has clicked all the safe cells. A message should be displayed on the screen saying "CONGRATULATIONS! You have won the game"

Along with this message should be a play again button. Keep users engaged!
