---
title: Checkers
publishDate: 2019-12-01 00:00:00
img: /assets/stock-2.jpg
img_alt: A bright pink sheet of paper used to wrap flowers curves in front of rich blue background
description: |
  Implemented functionality of the original game using plain JavaScript and DOM manipulation
  
tags:
  - HTML
  - CSS
  - JavaScript

---

[PLAY HERE ▶️](https://olgaazhel.github.io/checkers-game/)

#### Official Checkers Rules
##### Game Pieces and Board
Checkers is a board game played between two people on an 8x8 checked board like the one shown below. Each player has 12 pieces that are like flat round disks that fit inside each of the boxes on the board. The pieces are placed on every other dark square and then staggered by rows, like shown on the board. Each Checkers player has different colored pieces. Sometimes the pieces are black and red or red and white.

##### Taking a Turn
Typically the darker color pieces moves first. Each player takes their turn by moving a piece. Pieces are always moved diagonally and can be moved in the following ways: Diagonally in the forward direction (towards the opponent) to the next dark square. If there is one of the opponent's pieces next to a piece and an empty space on the other side, you jump your opponent and remove their piece. You can do multiple jumps if they are lined up in the forward direction. *** note: if you have a jump, you have no choice but to take it.

##### King Pieces:
The last row is called the king row. If you get a piece across the board to the opponent's king row, that piece becomes a king. Another piece is placed onto that piece so it is now two pieces high. King pieces can move in both directions, forward and backward. Once a piece is kinged, the player must wait until the next turn to jump out of the king row.

##### Winning the Game
You win the game when the opponent has no more pieces or can't move (even if he/she still has pieces). If neither player can move then it is a draw or a tie.