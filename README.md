# maze-game
Maze-game. This is code for implementing a Peer-to-Peer Distributed system Maze program.  The maze is an N-by-N grid, consisting of N*N “cells”. Each cell contains either no “treasure” or exactly one “treasure”. At the start of the game, there are K treasures placed randomly at the grid. The number of players is arbitrary. Each player can be viewed as running on a separate node in the distributed system. Each player aims to collect as many treasures as possible. A player collects one or more treasures when the player’s location is the same as the treasure’s location. A player cannot occupy a cell that another player occupies. Each player has a current score which equals to the number of treasures the player has collected. The number of remaining treasures in the game will always be K — this means that when a treasure is taken by a player, the game should automatically create a new treasure at some random location.
