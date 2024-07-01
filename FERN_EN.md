# FERN

**This document is an active work in progress, and is written by a community member, *Walrus*.**

FEN notation is a system to turn a chess board state into a string of text. FERN (Forsyth-Edwards-[the creator's, walrus, last name] Notation) is a similar system for *musi soweli*. As is, FERN only works for two-player games.

A FERN string consists of 5 parts appended together. the positions of the pieces, the pieces each side has available to them, the kili left on each kasi space, whose turn it is, and the turn count. A space separates each part.

key:
pipi = `p`, akesi = `a`, kala = `k`, kijetesantakalu = `u`, waso = `w`, soweli = `s`, kili = `i`
red = CAPS, black = lowercase
A red kala is "K". a black kijetesantakalu is "u".

## Position

From red's perspective:

For each row, top to bottom:

From left to right:

If a space is occupied, mark down what occupies it. if it is a stack, mark down "[bottom]-[top]"

If a space is unoccupied, mark "1". if the next is unoccupied as well, mark "2" instead. Keep on with this until you reach an occupied space, or the end of the row

When a row is finished, append a "/".

The start of a game could be: 2uusaa2/2ppppp2/9/i7i/9/2PPPPP2/2KKSWW2

## Pieces available

First, write the pieces of red's that have been captured, discounting pipi, in alphabetical order. Then, the number of pipi captured. Then a "/". Finally, do the same first two steps for black's pieces.

If red has had 2 kala, a waso, and 3 pipi captured, and black had 4 pipi captured, the string would be: KKW3/4

## Kili remaining

[number of kili available to be placed on red's left kasi space]/[... red's right]. Discount kili that are already placed.
At the start of the game, this is 4/4

## Turn parity

l for red (loje), p for black (pimeja)

## Turn number

Starts at 1. Every second move, this is incremented by 1.

At the start of a game, the FERN string could be:
`2uusaa2/2ppppp2/9/i7i/9/2PPPPP2/2KKSWW2 0/0 4/4 l 0`
