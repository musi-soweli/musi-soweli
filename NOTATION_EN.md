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
pipi = `P`
akesi = `A`
kala = `K`
kijetesantakalu = `U`
waso = `W`
soweli = `S`

If a *pipi* moves to `p3`, it would be notated as `Pp3`. If an *akesi* moves to `w1`, it would be notated as `Aw1`.
If there is an ambiguity in a piece move, notate the file it's moving from. If not applicable, notate the rank it's moving from. If both are ambiguous, notate both.

## Actions

There are four basic actions in *musi soweli*. The action follows the file and rank position of a piece. The following are the corresponding notations for the actions:

Capturing = `x` after the piece letter and any disambiguations but before the other parts of the move
Stacking = `^`
Carrying = `+`
Promoting = `=`, followed by the piece letter

If a *pipi* captures a piece on `n3`, it would be notated as `Pxn3`. (similar to chess notation)
If a *pipi* stacks on top of a piece on `j4`, it would be notated as `Pj4^`.
If a *kijetesantakalu* carries a *kili* to `k1`, it would be notated as `Uk1+`.
If a *kili* promotes to a kijetesantakalu on `k1`, it would be notated, it would be notated as `k1=U`.

## Starting position

`0.` indicates the starting position. Because *musi soweli* allows for unique arrangement of the pieces in the back rank, this must be specified in the notation. Additionally, different *kili* counts are notated *before* the arrangement of pieces per side.

Example without *kili*: `0. AUSWK KWSUA`
Example with *kili*: `0. 5 AUSWK KWSUA`

## Wins and losses

Notate the points in this format at the end of the notation:
`X-Y`
Put the number in parenthesis if the player resigns.

## Example

`0. 4 UKSKW WKUSA 1. Pw3 Pw5 2. Pk3 Wm5 3. Ut3 Kt6^ 4. Ktk2 Kt5+ 4. Kk3^ Aw5^ 5. Pp3 Pp5 6. Wj3 Us5 7. Kss2^ Pk5 8. Kss3 Pp4 9. Un4^ Wn4#^ 10. Pn4#^ Sp7 11. Kkk4+ Kk4#^ 12. Kk4#^ Pk4#^ 13. Sk4#^ Aj5 14. Ww1 Pw4 15. Ws2^ Pl4^ 16. Sk3 Pw4+ 17. Ps5# Ps5#+ 18. Wl4^ Al4#^ 19. Pl4#^ Pw6 20. Pl3+ Pss6+ 21. Pl4^ Ps7+ 22. Sw3 Ps5 23. Pl5 Pl5# 24. Sw5 Pk7+ 25. Ss5# Pl4^ 26. Ss7 k7=U 27. Sw7 Pk6 28. Sw4 Pl5+ 29. Sl4^ Pw5+ 30. Sw4+ Ps6 31. Sw1+ Ut5 32. Pm4+ Un4^ 33. Sk1+ Ut4+ 34. Sp1 Pn4^ 35. Sp7# Up7#+ 36. k4=S Pn5+ 37. Pn5#^ Un5#^ 38. Sp1 Pw6+ 39. Sp5 Um3 40. Sp7^ Pw7+ 41. Sp1+ Pws7+ 42. Pt3 Pk7+ 43. Sp4 Up4# 44. Pp4# Pk6 45. Pn4^ Pt6 46. Pp4+ 2-1`
