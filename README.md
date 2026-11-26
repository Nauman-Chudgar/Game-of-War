**Game of War**

A web-based card game implementation of "War" using the Deck of Cards API. Players compete against a computer by drawing cards from a shared deck to see who has the higher value.


**Features**

*Dynamic Deck Integration*: Fetches a new, shuffled deck using the Deck of Cards API.

*Game Logic*: Automatically compares card values (2 through Ace) to determine the winner of each round.

*Score Tracking*: Real-time updates for both the player and computer scores.

*End-Game State*: Detects when the deck is empty and declares the final winner.

*Responsive UI*: A styled interface featuring a card table background and dynamic card image rendering.


**How to Play**

Click New Deck to initialize and shuffle a new deck of cards.

Click Draw to pull two cards—one for the computer and one for you.

The winner of the round is determined by the higher card value. In the event of a tie, "War!" is declared.

Continue drawing until the deck is empty to see the final game result.


**Technologies Used**

HTML5

CSS3 (Flexbox, Google Fonts)

JavaScript (ES6+, Fetch API)

Deck of Cards API