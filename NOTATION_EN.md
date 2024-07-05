# musi soweli Notation

Inspired by Algebraic Chess Notation!

## Board

A standard board is 9x7 in width and height.

The board squares are notated with the file (horizontally) with letters and the rank (vertically) with numbers, with the perspective starting from Red.

The letters for the files are ordered `mnptkswlj`.

A square is notated with the file followed by the rank, with the bottom left corner being `m1`. For example, `p3`, `m4`, &c.

[insert image here with files and ranks marked]

## Pieces

*musi soweli* has 7 pieces, with 5 of them being unique. The piece letter precedes the file and rank position. The following are the corresponding notations for the pieces:
pipi = no piece letter. write the space it's on and the space it moves to
akesi = `A`
kala = `K`
kijetesantakalu = `U`
waso = `W`
soweli = `S`

If a *pipi* on `p2` moves to `p3`, it would be notated as `p2p3`. If an *akesi* moves to `w1`, it would be notated as `Aw1`.

If there is an ambiguity in a piece move, notate the file it's moving from. If not applicable, notate the rank it's moving from. If both are ambiguous, notate both.

## Actions

There are four basic actions in *musi soweli*. The action follows the file and rank position of a piece. The following are the corresponding notations for the actions:

Capturing = `x` after the piece letter and any disambiguations but before the other parts of the move
Stacking = `^`
Carrying = `+`
Promoting = `=`, followed by the piece letter

If a *pipi* on `p2` captures a piece on `n3`, it would be notated as `p2xn3`.
If a *pipi* on `l4` stacks on top of a piece on `j4`, it would be notated as `l4j4^`.
If a *kijetesantakalu* carries a *kili* to `k1`, it would be notated as `Uk1+`.
If a *kili* promotes to a kijetesantakalu on `k1`, it would be notated, it would be notated as `k1=U`.

## Passing

A pass of a turn is notated with simply the word `Pass`.
`(some notation here) 27. Pass Pass 28. Pass (1)-(1)`

## Starting position

`0.` indicates the starting position. Because *musi soweli* allows for unique arrangement of the pieces in the back rank, this must be specified in the notation. Additionally, different *kili* counts are notated *before* the arrangement of pieces per side.

Example without *kili*: `0. AUSWK KWSUA`
Example with *kili*: `0. 5 AUSWK KWSUA`

## Wins and losses

Notate the points in this format at the end of the notation:
`X-Y`
Put the number in parenthesis if the player resigns.

## Example

TODO
