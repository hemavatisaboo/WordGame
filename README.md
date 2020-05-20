# WordGame
Simple words making game using python 3

* Main file to start game is `WordGame.ipynb` .
* Guessed words are validated from `words_wordgame.txt` file.

#### How To Play:
* At the start of the game, player is provided with 7 random letters.
* Player have to create meaningful words from those letters.
* Letters can be used only once. 
* Score is calculated as: `length of word * letter_score + bonus`
  * `letter_score` is sum of points for each letter as provided in variable `SCRABBLE_LETTER_VALUES`.
  * `bonus`=50 if all letters are used.

Note: Assignment for edx course [MITx:6.00.1x Introduction to Computer Science and Programming Using Python](https://courses.edx.org/courses/course-v1:MITx+6.00.1x_6+2T2015/course/)
