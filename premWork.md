### Preliminary Work

* Research Conway’s "Game of Life". Figure out how it works, why it’s
  useful, and how the notion of Turing Completeness is related to this
  topic

1. How does it work? On or Off (alive or dead). White: dead; Black: alive. If a cell no neighbors that are alive, it dies. At lease one neighbor, it will still die. If it has 2 neighbors, it will live. 

Every cell interacts with its eight neighbours, which are the cells that are horizontally, vertically, or diagonally adjacent. At each step in time (generation), the following transitions occur: 

    a. Any live cell < 2 neighbors dies, as if caused by under-population
    b. Any live cell > 2 live neighbors lives on to the next generation
    c. Any live cell > 3 llive neighbors does, as if by overcrowding
    d. Any dead cell with exactly 3 live neighbours becomes a live cell, as if by reproduction

The game takes place in discrete time, with the state of each cell at time t determined by its own state and the states of its eight immediate neighbours at t-1 (the Moore neighbourhood of radius 1), according to the following simple rules:

    1. Any ‘on’ cell (at time t-1) with fewer than two ‘on’ neighbours (at t-1) transitions to an ‘off’ state at time t
    2. Any ‘on’ cell (t-1) with two or three ‘on’ neighbours (t-1) remains ‘on’ at time t
    3. Any ‘on’ cell (t-1) with more than three ‘on’ neighbours (t-1) transitions to an ‘off’ state at time t
    4. And ‘off’ cell (t-1) with exactly three ‘on’ neighbours (t-1) transitions to an ‘on’ state at time t

2. Why is it useful? Patterns within the Game of Life can be much more complex and can even be organized in ways that perform functional operations. Streams of gliders (and other moving objects, generally known as 'spaceships') can be considered as signals which have causal effects on other patterns with which they interact. These interactions can be organized to furnish basic computational procedures such as logic gates (AND, OR, NOT) as well as simple memory counters. Universal Turing Machines have been implemented in practice in Game of Life environments. Practically speaking, CAs have been used in biological and chemical simulations and other areas of research, such as CA-based computer processors, and other numeric techniques. 


3. How is the notion of Turing Completeness is related to this topic? Universal computer, anything that can be computed has Turing Completeness, if it is capable of performing arbitrary, general purpose computation. 

Within a few weeks after the discovery of the glider, John had proven that Game of Life is equivalent to the universal Turing machine. Streams of gliders with signals which have causal effects on other patterns with which they interact. These interactions can be organized to furnish basic computational procedures such as logic gates (AND, OR, NOT) as well as simple memory counters. These properties imply that the Game of Life is theoretically equivalent to a 'Universal Turing Machine'; that is 'Turing complete'. Turing completeness means that, absent any constraints of memory or time, the Game of Life has unlimited computational power. 



