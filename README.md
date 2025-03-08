# Card Game

This is a simple card game implemented in C# targeting .NET 8. The game involves creating a deck of cards, shuffling them, and dealing them to players. The game then determines the winner based on the total value of the cards in each player's hand.

## Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)

## Getting Started

### Clone the Repository
git clone https://github.com/lentswe215/Multi_Player_Card_Game.git cd Multi_Player_Card_Game

### Build the Project

Open a terminal in the project directory and run:
dotnet build


### Run the Project

To run the project, use the following command:
dotnet run


### Project Structure

- `Program.cs`: The entry point of the application.
- `Game/Deck.cs`: Contains the `Deck` class which handles the creation and shuffling of the deck.
- `Game/Game.cs`: Contains the `Game` class which manages the game logic.
- `Game/Player.cs`: Contains the `Player` class which represents a player in the game.
- `Helpers/Calculator.cs`: Contains helper methods for calculating card and suit points.

### How to Play

1. The game starts by creating a deck of cards and shuffling them.
2. Six players are created, and each player is dealt 5 cards.
3. The total value of each player's hand is calculated.
4. The player with the highest total value wins. In case of a tie, the suit points are used to determine the winner.

### Example Output

Starting the game!
----------------------------------------------------------------------------------------
Player 1's hand:
- Q of Hearts
- A of Diamonds
- 10 of Clubs
- Q of Hearts
- 5 of Clubs
Player 1's hand total: 50
----------------------------------------------------------------------------------------
Player 2's hand:
- 10 of Diamonds
- K of Diamonds
- 2 of Diamonds
- J of Diamonds
- 8 of Hearts
Player 2's hand total: 44
----------------------------------------------------------------------------------------
Player 3's hand:
- 9 of Diamonds
- 10 of Spades
- 4 of Hearts
- 5 of Hearts
- 6 of Spades
Player 3's hand total: 34
----------------------------------------------------------------------------------------
Player 4's hand:
- 7 of Clubs
- A of Clubs
- K of Hearts
- J of Spades
- 2 of Hearts
Player 4's hand total: 44
----------------------------------------------------------------------------------------
Player 5's hand:
- 6 of Hearts
- J of Spades
- 4 of Spades
- 8 of Diamonds
- 3 of Diamonds
Player 5's hand total: 32
----------------------------------------------------------------------------------------
Player 6's hand:
- 7 of Spades
- 9 of Clubs
- J of Clubs
- 9 of Spades
- 8 of Clubs
Player 6's hand total: 44
----------------------------------------------------------------------------------------
* Player 1 wins with a hand total of 50! *

----------------------------------------------------------------------------------------
Game over!

Press any key to exit...
