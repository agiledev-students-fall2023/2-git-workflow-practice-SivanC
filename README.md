## Solving Connect 4

[This page](http://blog.gamesolver.org/) contains a set of articles dedicated to
creating, optimizing, and implementing an algorithm to solve the popular board
game Connect 4 (non-proprietary name Four-in-a-Row).

I personally love playing Connect 4 (at least when there's nothing better to
do), and therefore found this blog very intriguing. Learning about the different
algorithms and optimizations that are made to solve the game, as well as the
history of its solving, is very interesting to me. I have also enjoyed following
along with the steps using a different language (I used Scala). My favorite post
is part 6, which introduces the technique of representing the Connect 4 board as
a set of bit arrays (usually implemented with a long long or something like that
to have enough digits). By representing the Connect 4 board with just binary,
the board becomes smaller and faster to access, and non-trivial operations such
as checking for alignments are reduced to simple bit-wise arithmetic. While
unintuitive, it is a very elegant optimization in my opinion.
