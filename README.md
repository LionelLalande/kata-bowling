# Bowling

Original source: https://github.com/ardalis/kata-catalog/blob/main/katas/Bowling%20Game.md

## Description

This simple Kata  should be performed  in pairs  using  Test Driven Development
(TDD).  What matters is the steps that lead to the conclusion, not the conclusion
itself.  Try to make "baby steps" to find a good solution.

## Requirements Specification

A completed  game of bowling  consists of 10 frames.  In each frame, the player 
has two  opportunities to  knock down 10 pins.  The score for  the frame is the
total number of pins knocked down, plus bonuses for *strikes* and *spares*.

A *spare* occurs  when the player  knocks down all  10 pins  in two tries.  The
bonus for that frame is  the number of pins knocked down by the next roll.  For
example,  if you get  a spare  in the 3rd frame,  and in the fourth frame  your
first roll  knocks down 5 pins,  your score in the  3rd frame would be 15 (10 +
bonus of 5).

A *strike* occurs when the player knocks down all 10 pins on the first try. The
bonus for that frame is the value of the next two balls rolled.

In the tenth frame, a player who rolls a spare or strike is allowed to roll the
extra balls  to complete  the frame.  However, no more than  three balls can be
rolled in the tenth frame.

## Requirements Specification

- A game can store all the rolls for a player.
- Each time the player *rolls* the ball, he can knock 0 to 10 *pins* down.
- After each *frame*, the overall *score* can be retrieve.
- The overall *score* can only be computed when all bonuses are known and applicable.

# Resources #
- [Walkthrough by Uncle Bob Martin](http://butunclebob.com/ArticleS.UncleBob.TheBowlingGameKata)
