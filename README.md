🌫️ Fog of War Chess
A unique chess variant with Fog of War mechanics — play against AI

🔗 Live demo: [chesslessonspro.com/fogstorm-chess](https://www.chesslessonspro.com/fogstorm-chess/)

Fog of War Chess

What is Fog of War Chess?
Fog of War Chess is a custom chess variant built as a single HTML file with no dependencies.
Unlike standard chess, you can only see squares your pieces control or occupy — the rest of the board is hidden in fog. Enemy pieces appear only when they step into your visible zone.

This forces you to rely on intuition, positional thinking, and space control rather than pure calculation — skills that directly transfer to improving at standard chess.

Features
♟ Full chess rules — castling, en passant, pawn promotion (auto-queen)

🌫️ Fog of War — dynamic visibility based on your pieces' control zones

🤖 AI opponent with 3 difficulty levels:

Easy — random moves, prefers captures

Medium — Minimax depth 2 + move ordering

Hard — Minimax depth 4 with Alpha-Beta pruning + Piece-Square Tables

🎨 Dark UI — clean, responsive design

📱 Mobile friendly — works on desktop and mobile

📦 Zero dependencies — pure HTML + CSS + JS, single file

How to Play
Open fogstorm-chess.html in any browser — no server needed

Select difficulty (Easy / Medium / Hard)

You play White, AI plays Black

You can only see squares your pieces control

Capture the enemy King to win

Fog of War Rules
Visible	Hidden
Your own pieces	Enemy pieces outside your zone
Squares your pieces can move to	Squares not controlled by any of your pieces
Enemy pieces that enter your zone	Everything else
Installation
Just download and open in a browser:

bash
git clone https://github.com/YOUR_USERNAME/fog-of-war-chess.git
cd fog-of-war-chess
open fogstorm-ch
