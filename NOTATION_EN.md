# Muso Notation

Inspired by Algebraic Chess Notation!

## Board

A standard board is 9x7 in width and height.

The board squares are notated with the file (horizontally) with letters and the rank (vertically) with numbers, with the perspective starting from Red.

The letters for the files are ordered `abcdefghi`.

A square is notated with the file followed by the rank, with the bottom left corner being `a1`. For example, `c3`, `i7`, &c.

[insert image here with files and ranks marked]

## Pieces

*Muso* has 7 pieces, with 5 of them being unique. The piece letter precedes the file and rank position. The following are the corresponding notations for the pieces:
pipi = `p`
akesi = `A`
kala = `K`
kijetesantakalu = `U`
waso = `W`
soweli = `S`

All moves must be notated with the origin space first and then the destination space after. This is to prevent the numerous notation ambiguities that arise when notating *Muso*.

Notating the piece is optional. If notating the piece, put it before the origin space.

## Actions

There are four basic actions in *Muso*. The action follows the file and rank position of a piece. The following are the corresponding notations for the actions:

Capturing = `x` after origin space and but before the destination space
Stacking = `^` after the destination space
Carrying = `+` after the destination space
Promoting = `=`, replacing the destination space, followed by the piece letter

## Movement examples

If a *pipi* on `c2` captures a piece on `b3`, it would be notated as `c2xb3`.
If a *pipi* on `h4` stacks on top of a piece on `i4`, it would be notated as `h4i4^`.
If a *pipi* on `e2` carries a *kili* to `e1`, it would be notated as `e2e1+`.
If a *kili* promotes to a kijetesantakalu on `e1`, it would be notated as `e1=U`.

## Passing

A pass of a turn is notated with simply the word `Pass`.
`(some notation here) 27. Pass Pass 28. Pass (1)-(1)`

## Starting position

`0.` indicates the starting position. Because *Muso* allows for unique arrangement of the pieces in the back rank, this must be specified in the notation. Additionally, different *kili* counts are notated *before* the arrangement of pieces per side.

Example without *kili*: `0. AUSWK KWSUA`
Example with *kili*: `0. 5 AUSWK KWSUA`

## Wins and losses

Notate the points in this format at the end of the notation:
`X-Y`
Put the number in parenthesis if the player's score is effectively zero.

## Example

TODO
