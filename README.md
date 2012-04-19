Conway Ruby Template
====================

This is a simple Ruby project template for use in a Coderetreat (so you don't have to waste time with the same setup steps).

Please do not contribute implementation here.

Getting Started
---------------

This assumes you have rvm.

    ./configure
    rake

Rules
-----

From the [Wikipedia Article](http://en.wikipedia.org/wiki/Conway%27s_game_of_life):

> The universe of the Game of Life is an infinite two-dimensional orthogonal grid of square cells, each of which is in one of two possible states, alive or dead. Every cell interacts with its eight neighbours, which are the cells that are horizontally, vertically, or diagonally adjacent. At each step in time, the following transitions occur:
>
> 1. Any live cell with fewer than two live neighbours dies, as if caused by under-population.
> 2. Any live cell with two or three live neighbours lives on to the next generation.
> 3. Any live cell with more than three live neighbours dies, as if by overcrowding.
> 4. Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.
>
> The initial pattern constitutes the seed of the system. The first generation is created by applying the above rules simultaneously to every cell in the seed -- births and deaths occur simultaneously, and the discrete moment at which this happens is sometimes called a tick (in other words, each generation is a pure function of the preceding one). The rules continue to be applied repeatedly to create further generations.

Testing
-------

To make test writing easier, there are some implementation-agnostic example "still lifes" and oscillators [from Wikipedia](http://en.wikipedia.org/wiki/Conway%27s_game_of_life#Examples_of_patterns) in `spec/examples/`.  You don't have to use a JSON parser; you can just transform them using a text editor into whatever form you need, etc.

See Also
--------

* [Coderetreat](http://coderetreat.org/)
* [Game of Life Rules](http://coderetreat.org/gol)
