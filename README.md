# Blackjack

This is a multiplayer Blackjack card game with a server and a client. The server acts as the house and creates new tables for players to join through the client. Every player starts with a certain amount of money and must make a minimum bet each round. Players can leave after each round or will be kicked out when they do not have enough money to place the minimum bet. The dealer hits on soft 17 and a new deck of cards is used for each round. All other rules are standard Blackjack rules.

## How to Play

Follow these instructions to run Blackjack on your computer.

### Prerequisites

* Java Development Kit

### Installing

Before you can run the Blackjack server and clients, you need to compile the java files. Navigate to the directory containing the java files. If you would like to change what port the server runs on, change the port number in the server and client files. If you are running the server on a different computer than your clients, change the server IP address in the client file. To change the number of players per table, edit the number in the server file. Finally, just compile all of the java files.

```
javac *.java
```

### Running

Once you have compiled the java files, all you have to do is run the server and client.

```
java Server

java Client
```

## License

This project is licensed under the MIT License. See the [LICENSE.md](LICENSE.md) file for details.