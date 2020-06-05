# Dice-Challenge

##About
This is a simple Dice challenge.
The aim was to know how to manipulate the DOM using JQUERY

##How it works
To Play the game open the index.html.
There are 2 dices with 2 players on screen which would render different outputs depending on the output of a genreated random number.
Each time you refresh the browser you get different results leading to a WIN||DRAW||LOOSE
Inoder to get the final result,We compare the 2 random generated random numbers and display the output.

#Generating Random numbers
var randomNumber = Math.floor(Math.random() * 6) + 1; // 1-6


#The logic behind
// If player 1 wins
if (randomNumber1 > randomNumber2) {
  document.querySelector('h1').innerHTML = '🚩 Play 1 Wins!'
}
else if (randomNumber2 > randomNumber1) {
  document.querySelector('h1').innerHTML = 'Player 2 Wins! 🚩'
}else {
  document.querySelector('h1').innerHTML = 'Draw!'
}


##Hack learned
If you are wondering how I rendered different Images each time a number was generated.
The hack is to get different Dice images each with a unique face.
In this presentation I had dice 1-6 images

