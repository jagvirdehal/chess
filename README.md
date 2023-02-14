# Chess Endgame Tablebase

## Overview

This is my attempt at creating a program that is capable of generating a chess endgame tablebase. Currently, the project is written in Python, an environment in which I can rapidly test my programming logic and see a high-level overview of what the code should look like and what the functions should do. However, I would like to write the code in a faster language like C or Go, as small speedups in performance will add up overtime.

## Install

### Manual Install

1. Simply run the chess notebook with Python >= 3.10 and the following prerequisites:
	- chess
	- scipy
	- numpy

## Next steps

Currently the notebook supports generating pawnless endgames in which the enemy king has no pieces (useful for finding fastest checkmate, especially for trickier endgames such as KNNNK). It wouldn't take long to modify a function or two and implement pawns and opposing pieces, but instead I'd rather focus my time on either porting the code, or using my knowledge of chess to create a engine instead. 

I'd like to adapt/pivot this project in one of two directions. Either I could rewrite the code in C/Go to improve the performance and gain experience writing efficient code in these languages, or I could use my knowledge to start from scratch and create a mini chess engine.

