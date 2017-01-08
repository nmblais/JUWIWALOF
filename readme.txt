
JUWIWALOF (Just-what-I-was-looking-for), a simple dice game.

=============================================================

The board:

9 rows and 6 columns.

Introduction:

The bottom two rows are the "dice".
The top row records the results of obtaining a double.
The rows in between are the credits (6 per columns)

The goal of the game is to obtains all six doubles without
exhausting the credits at any one column.

How to play:

The player controls the game using the keyboard.

Arrow Keys:

Up -- roll the two dice.        (Button labeled "BOTH")
Left -- roll the "buttom" die.  (Button labeled "LEFT")
Right -- roll the "top" die.    (Button labeled "RIGHT")
Down -- abort a turn.           (Button labeled "PASS")

Spacebar:

re-arrange credits on the board. (Button labeled "CREDITS")

Escape:

Quit the game.                    (Button labeled "QUIT")

New Game:

Start a new game.                 (Button labeled "NEW")

Sound:

Toggle sound on and off           (Button labeled "SOUND")

=============================================================
The rules:

The play starts by playing the two dice (up arrow).
If a double is obtained, the top row records the results by
changing color at the location of the corresponding double.
No credit is lost.

If a double is not obtained, the player can choose between:
playing the two dice again (up arrow),
playing the bottom die (left arrow),
playing the top die (right arrow),
aborting the turn (down arrow).

If a double is obtained, the result is recorded and
no credits is lost.

If a double is not obtained, two credits are lost (one for
each roll).

Aborting the turn also loses two credits.

One credit is lost if a double is obtained another time.

the player is allowed to re-order the credits before a turn
by pressing the spacebar.

The game ends when:
all six doubles are obtained (win)
at least one column has no credits left (lost)
the player press the "escape" key and quit the game.

=============================================================
The game is written in C++ (11) (Visual Studio 2015) (Thanks)
The graphic used SFML 2.4.1 (Thanks)
The GUI library is TGUI 0.7 (Thanks)

Disclaimer:

This present program is for resposible people only.
=============================================================

Normand M. Blais, Jan 8, 2017

