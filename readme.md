#### Logic Flow Explanation:

User clicks on one of the choices: rock, paper, or scissors.
The click listener captures the user's choice and calls playGame.
playGame generates a random computer choice using genCompChoice.
It compares both choices:
If the same, declares a draw via drawGame.
Otherwise, applies the classic rock-paper-scissors rules to decide winner:
Rock beats scissors
Paper beats rock
Scissors beat paper
Calls showWinner to update scores and display who won or lost.
Scores increment as appropriate and messages update dynamically.
The cycle repeats with each user click, allowing continuous gameplay.
