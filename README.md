# ReinforcementLearning_w_Tetris
Using Tetris as a basis to implement reinforcement learning algorithm.  

This project begins with devling into Machine Learning.  More specifically, Reinforcement Learning.  Rather than add lengthy definitions, Here are links to explore these topics:  
[Machine Learning](https://expertsystem.com/machine-learning-definition/)  
[Reinforcement Learning](https://www.geeksforgeeks.org/what-is-reinforcement-learning/)  

After considering several games including Battleship, I decided to pursue a single player game.  Solitaire (the most commonversion is Klondike) was not a good choice because there is not need to act and a shuffled deck has high randomness and a large influence on the play.  Arcade games are more appropriate the the intention.  Tetris has retained its popularity.  I can download for my smart phone, as well as several similar games.

I found an instructional video to build Tetris.  I did not start from scratch.  The row-clearing function is a rewrite.  Plus, a few changes were made in the presentation.

To run the game for pleasure or interest, open an environment such Jupyter Notebook and run the contents of Tetris single cell.ipynb, the only imports used are numpy, pygame, and datetime



Acknowledgement:
The implementation of Tetris was based  on a YouTube video  
Python and Pygame Tutorial - Build Tetris! Full GameDev Course  
https://www.youtube.com/watch?v=zfvxp7PgQ6c  

The code in this project is a modified version of the code in the video.  The most obvious difference is that this version has a random rotation of the 4-block pattern.  

Tetris was created by Alexey Pajitnov in 1984.  A five-cube game, Pentamino, was the basis for the game.  Two modifications can before the success of te faniliar result.  The number of pieces in each shape was reduced from five to four.  Next, the pieces were made to descend into a rectrangular glass.  Tetris was born.  The name of the game "Tetris" Pajitnov combined from 2 words: the name of the original game—"tetramino" and his favorite sport—"tennis".  (Source: https://history-computer.com/ModernComputer/Software/Tetris.html)  

