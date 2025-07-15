# ECM1410-2425-REFDEF-Coursework

The ECM1410 REFDEF coursework follows the a modified version of the coursework given in term 2 but with different games types and score systems. Should you have any questions or issues while completing the work please contact the module teaching staff.

Due to a current issue with the GitHub classroom account when accepting the assignment you will start with an empty directory. To obtain the starter code, please launch the CodeSpaces link to work on your project and run the following commands in the terminal.

```
curl https://raw.githubusercontent.com/My-UofE/ECM1410-2425-REFDEF-Coursework/refs/heads/main/starter_project.zip -o ./starter_project.zip 
unzip starter_project.zip
rm starter_project.zip
```

Note that you should be able to draw on the work you may have already completed on the original coursework task if you already worked on this. 

The key difference is that instead of the leagues working to record WORDMASTER and DICEROLL games. In particular this means the file GameType.java contains different entries. 

For this assignment the games options (and scoring systems) are:

### WORDLE

 - The result of a WORDLE game for an individual is a score between 0-6 indicating the number of guesses taken to guess a secret word. The fewer guesses the better, however a score of 0 indicates the person failed the game.
 -  To allocate league points each day the player(s) with the lowest non-zero game score wins (i.e. ranking is in order of score low to high) and the winner(s) get awarded 3 league points, the other player(s) in the group with a non-zero score awarded 1 league point. 

or

### TETRIS

 - the result of a TETRIS game for an individual is a score indicating how many levels the player completed in the daily TETRIS game. 
 - To allocate league points each day the player(s) with the greatest score wins (i.e. ranking is in order of score high to low) and the winner(s) get awarded 1 league point. No other players are awarded league points. 


## Testing

For your convenience I have modified the existing test code so that it is updated from setting up leagues referencing the WORDMASTER and DICEROLL games to reference WORDLE and TETRIS instead.

```
curl https://raw.githubusercontent.com/My-UofE/ECM1410-2425-REFDEF-Coursework/refs/heads/main/TestOperation_REFDEF.zip -o ./TestOperation_REFDEF.zip 
unzip TestOperation_REFDEF.zip
```

Then follow the instructions in the `README.md` file inside.

The reference text files contain the expected outputs when I run on the reference completed code. Please review and compare the outputs wto your own, and make sure that you have not included any outputs (e.g. for debugging) in your final code as the grader looks for an exact match between student and reference code outputs.
