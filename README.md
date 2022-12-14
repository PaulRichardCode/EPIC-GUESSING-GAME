# EPIC-GUESSING-GAME
I built this game with html css and a lot of javascript. It is my most remarkable project yet and believe more is yet to come. Web development is for me. And i cant wait to build more cool projects just like this one.
This JavaScript code creates a memory game in which the player is presented with a grid of cards, each of which is initially faced down. When the player clicks on a card, it flips over and reveals its image. The player's goal is to find pairs of matching cards.

The code begins by defining an array called cardArray that contains objects representing the cards in the game. Each object has a name property, which specifies the name of the card, and an img property, which specifies the URL of the image to be displayed on the card.

Next, the code uses the sort() method to randomly shuffle the order of the cards in the cardArray. This ensures that the game will be different each time it is played.

The code then uses the querySelector() method to get references to the #grid and #result elements in the HTML page. These elements represent the game grid and the element that displays the player's score, respectively.

The code then defines several variables: cardChoosen and cardWon are arrays that track the cards that have been chosen and the cards that have been successfully matched, respectively. cardChoosenId is an array that tracks the IDs of the chosen cards.

The code then defines a createBoard() function that creates the game board. This function uses a for loop to iterate over the cardArray. For each card in the array, the function creates an img element and sets its src attribute to the URL of the "blank" image. It also sets the element's data-id attribute to the index of the card in the cardArray, so that the card's name and image can be retrieved later. Finally, the function adds an event listener to the img element that calls the flipCard() function when the element is clicked.

After the createBoard() function is defined, the code calls it to create the game board.

The flipCard() function is called when the player clicks on a card. 
