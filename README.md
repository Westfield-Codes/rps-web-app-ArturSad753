### To Do

1. **done** Preview this MarkDown file with Control+Shift+V
1. **done** index.html: Set the value of document element with id = rounds to "odd numbers only" if an even number is entered. Do not display this message as an alert.
1. **done** setRounds(): replace if (rounds % 2 == 0) with if (rounds % 2 == 0 || isNaN(rounds)) so that people can't click past that error (isNan = "is not a number")
1. **done** chooser.html: Create a div in chooser.html with id = result and write "Choose a move" inside it. 
1. **done** findWinner(): Display the findWinner message inside that result div, replacing "Choose a Move" when there is a winner. Do not display that message as an alert. 
1. **done** findWinner(): Replace that result message with the "We both picked" alert message if u and c are the same. Do not display that message as an alert. 
1. **done** style.css: To the body element, apply the css rule position:relative;
1. **done** chooser.html: create a div with id = scoreBox above statsBox, and in that div, write: Score: loading
1. **done** style.css: Apply these css rules to a #scoreBox selector: position:absolute; right:10px; top: 10px; border:1px solid black; background:white; padding:10px;
1. **done** setRounds(): if rounds was odd, create an array called score and set it to [0,0]. 
1. **done** setRounds(): store the score array to local storage using JSON.stringify(score).
1. **done** showRound(): get score from local storage, JSON.parsed.
1. **done** showRound(): replace "Score: loading" in scoreBox with score.toString()
1. **done** findWinner(): store the winner in local storage as winner.
1. **done** findWinner(): After you added 1 to the round, get the score array from local storage, JSON.parsed. 
1. **done** findWinner(): create a players array with the two players, "You" first. This should match the values in winArray. 
1. **done** findWinner(): set win equal to the index of the winner in players[]. So if winner is "I", it is players[1] so win = 1. 
1. **done** findWinner(): increase by one the value of the element in the score array with index win
1. **done** findWinner(): display the updated score in the scoreBox div with "Score : " + score.toString;
1. **done** findWinner(): store the score array, stringified, in local storage.
1. **done** gameover.html: add the scorebox div above the play again button
1. **done** gameover.html: Give scoreBox div the class "over" 
1. **done** style.css Style class over (.over) with font-size:24pt, margin:auto, position:static!important, width:10em, text-align:center.
1. **done** gameover.html: load a new function called endGame() when the <body> loads (like you did in chooser.html)
1. **done** script.js: create a new function called endGame(){}
1. **done** endgame(): Get the score array from local storage, JSON.parsed
1. **done** endgame(): Decide who won based on the scores, and set winner equal to this value ("You" or "I")
1. **done** endgame(): Create a variable called message, and begin it winner + " won,"
1. **done** endgame(): Add the score to message, but array.join the values with " to " instead of a comma. 
1. **done** endgame(): Display the message, something like "You won, 2 to 1" in scoreBox. 
1. CodeSpace: If all this is working, save the branch now. 
1. CodeSpace: Create a new branch called rps web-refactored. 
1. script.js: Go over all the code.  If you see any repeated lines, make new a function for those if possible.  
1. findWinner(): If one player wins more than half the rounds, end the game (shift to gameover.html).
1. CodeSpace: When you are sure it works, pull request this branch to main, then merge it.  
1. HTML + CSS: Style your pages to match your wireframes. 