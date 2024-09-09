# Elevator
OVERVIEW:
This Java project implements a deck of playing cards, with features such as shuffling, drawing cards, and sorting them using different Comparator strategies. The cards can be sorted by various criteria, including suit and rank.


FEATURES:

Generate a standard deck of 52 playing cards.
Shuffle the deck randomly.
Draw cards from the deck.
Sort drawn cards using multiple comparators for different sorting logic.


TECHNOLOGIES:
Language:Java
IDE:Any Java-compatible IDE (e.g., IntelliJ, Eclipse)
Version Control:Gite 

SETUP AND INSSTALLATION:

Clone the repository:git clone https:(https://github.com/assistantgimini/Elevator.git)
Open the project in your preferred Java IDE.
Run the Main class to shuffle, draw, and sort the cards.

USAGE:

DECK PERATION:

Shuffle the deck: Shuffle the deck randomly using shuffle().
Draw cards: Draw a card using drawCard() and retrieve the drawn card list.
Sorting: Cards can be sorted using different Comparator strategies for custom sorting by suit and rank.

CAMPARATOR OPTIONS:

cardComparator_1:Sorts by even/odd ordinal of the suit, then by suit and rank.
cardComparator_2:Similar to cardComparator_1 with natural ordering.
cardComparator_3:Sorts by even/odd ordinal, suit ordinal, and rank value.
cardComparator_4:Sorts by suit value and rank value (used in the example).

CLASS STRUCTRE:
Suit:
Enum representing the four suits (Hearts, Spades, Diamonds, Clubs).
Rank:
Enum representing card ranks (Ace, 2-10, Jack, Queen, King).
Card:
Represents an individual card with a suit and rank.
Deck:
Manages the collection of Card objects, including shuffle and draw operations.
Main:
Entry point that demonstrates shuffling, drawing, and sorting cards.

CONTRIBUTING:

Contributions are welcome! Please submit a pull request if you'd like to contribute, or open an issue for bug reports or feature suggestions.

License
This project is licensed under the MIT License.

