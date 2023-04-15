
# Card Dungeon:

A classic Uno card game but with a twist , no uno cards here , instead a standard deck of 52 cards is what you'll be playing with.

- Maximum of Upto 4 players can play this game.

For anyone who is not familiar with the deck of 52 , here are the cards:
- Cards are divided into 4 groups (4 suits) and each suit contains 13 cards:
    - Diamond   (2,3,4,5,6,7,8,9,10,Ace,King,Queen,Jack)
    - Spades    (2,3,4,5,6,7,8,9,10,Ace,King,Queen,Jack)
    - Clubs     (2,3,4,5,6,7,8,9,10,Ace,King,Queen,Jack)
    - Hearts    (2,3,4,5,6,7,8,9,10,Ace,King,Queen,Jack)

- Since uno has action cards such as ( +2 , +4 , Reverse , skip ) we will be using the face cards ( King , Queen , Jack ) and Ace for those actions instead.

- Each player starts with a hand of 5 cards.


- Players take turns playing cards from their hand, following a set of rules that define what cards can be played when.

- A player can only play a card if it matches either the suit or the rank of the top card on the discard pile.

- If a player cannot play a card, they must draw a card from the draw pile. If the draw pile is empty, the game ends in a draw and no player is declared a winner..

- The game ends when one player runs out of cards who is declared the winner.

- These action cards will trigger the following actions

    - Ace(A): Skip the next player in turn

    - Kings(K): Reverse the sequence of who plays next 

    - Queens(Q): +2

    - Jacks(J): +4

NOTE: Actions are not stackable i.e. if Q is played by player 1 then player two draws two cards and cannot play a Q from his hand on that turn even if available

## How to run the game ?

- Clone the repository.
- Simply run the Main.js which already has the startGame() ready and running
- The number of players is set to 4 , you can change it to anything in the range or ( min of 2) to (max of 2).

# Game flow :

![Game Flow](./Cards_Dungeon/assets/swig1.png "Cards Dungeon")
![Game Flow](./Cards_Dungeon//assets/swig2.png "Cards Dungeon")

# Author

- [Ayan Khan](https://github.com/ayankhan21)

## License

- [MIT](https://opensource.org/license/mit/)