This is my first Javascript project in TOP!
It will be a game of Rock Paper Scissors in the console.
To do:
    -create a function called computerPlay() that will randomly return either "Rock", "Paper", or "Scissors".
    -create a function called playerPrompt() that will prompt the user for an input of either "Rock", "Paper", or "Scissors"
        -the player input parameter will be case-insensitive (ex- "rock", "ROCK", "RocK" etc...)
    -write a function that plays a single round of RPS, the function takes two parameters:
      function playRound (playerSelection, computerSelection) {
          //code that returns a string to declare the winner, "You lose!  Paper beats Rock."
      }
    -create a function called game() which plays 5 rounds of RPS, look playRound 5 times with a For Loop (look up an example) and update two variables called playerScore and computerScore each round.  Output the results of the 5 rounds with an alert message at the end that tallies up the scores.