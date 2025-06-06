# 🎮 Multiplayer Number Guessing Game (TCP)

Setup instructions:

In one terminal run :
python server.py

In separate terminals (or on different machines)
python client.py

 Gameplay Guide
1. Pre-Game Chat: After joining, players enter a chat room.
2. Any player can start the game by typing \start.
3. Players can also type \board to view the leaderboard.
4. Type normal messages to chat with others before the game.

Starting the Game
Type \start to begin.
Choose a difficulty level:
1: Easy (1–100)
2: Medium (1–150)
3: Hard (1–200)

The game will start for all players simultaneously.

Game Rounds
There are 3 rounds.
1. Each round has a 20-second time limit.
2. Players guess numbers until:
3. Someone guesses correctly (gets 10 points), or Time runs out.
4. Rounds start for all player at same time, and after the times up
5. you have  to enter atleast 1 value to end the round
6. After each round, the correct number is shown.

Scoring
1. +10 points for guessing the correct number.
2. No penalty for wrong guesses.
3. Final leaderboard is displayed at the end of three rounds.

