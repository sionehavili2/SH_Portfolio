# [Speed Game](https://github.com/jsantos-weber/Speed)
This was a group project that combined the efforts of 3 developers to build a web-based version of the popular card game Speed. Although we were not able to finish the project during the course of the semester, we were able to build most of the functionality using sockets. 
![Speed](https://github.com/jsantos-weber/JuanSantos-3750-Portfolio/blob/main/img/Speed.png)
## Features 
- Using Encryption, allow users to create a profile. Usernames are stored in addition to a unique randomly generated salt, and an encrypted salt + password. The password is not sent across as a direct string but rather encrypted and store along with the salt to confirm login. 
- A backend implementation of a standard 52-card deck. This includes dividing the cards into different piles for each player. The cards will be shuffled and not appear in sequential order. 
- Using socket.io, created an emoting chat system to allow users to send emojis to each other.
- Communication between the back end and the front end constantly to allow for gameplay to take place.
- Using socket.io, created a system to allow users to create lobby rooms and for others to join that room.
### The start of the gameplay process works as follows:
- Upon a second player joining a game, both players must each push a button to indicate they are ready to start a game. 
- Once ready, a 3-second countdown will appear before dealing out the cards to each respective player. 
- The cards are divided in the backend and sent to the front end. Each player will only be able to view their own cards.
- ![Shuffle](https://github.com/jsantos-weber/Speed/blob/main/img/ShuffleDeck.png)
- If a player leaves, both players are sent back to the main lobby.
## Challenges 
- The use of sockets was new to us as a group. Using socket.io, we were able to allow users to join lobbies, chat rooms, and even game rooms together. 
- ![Sockets](https://github.com/jsantos-weber/Speed/blob/main/img/Sockets.png)
- Sending card piles to each player within the same game as JSON objects from the backend to the front end was a challenge. The challenge came in being able to send card piles to users in the same game, but without being able to show the other player what cards they had.
- ![Display](https://github.com/jsantos-weber/Speed/blob/main/img/Display.png)
## Socket Technology
### Emoji Chat Lobby
![Chat](https://github.com/jsantos-weber/JuanSantos-3750-Portfolio/blob/main/img/Chat.png)

### Users are allowed to create lobbies
![Lobby](https://github.com/jsantos-weber/JuanSantos-3750-Portfolio/blob/main/img/Lobbies.png)

### Ready status is easily visible
![Ready](https://github.com/jsantos-weber/JuanSantos-3750-Portfolio/blob/main/img/Ready.png)

### Cards are dealt to each player, only being able to view their own cards
![Cards Dealt](https://github.com/jsantos-weber/JuanSantos-3750-Portfolio/blob/main/img/Cards%20Dealt.png)


## SH_Portfolio
* Portfolio structured for viewers to directly access project files/code

## [Tic Tac Toe Game](https://sionehavili2.github.io/react-tictactoe/)
* Allows user to play a game of tic tac toe
* ![picture](/tictactoe1.png) ![piture 2](/tictactoe2.png)

# [Connect Four](https://sionehavili2.github.io/connectFour/)
* Play a game of Connect Four
* ![picture3](/connectFour.png)
