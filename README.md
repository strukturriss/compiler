# compiler

Welcome to Simusense!

The goal of this project is to build a compiler of my own, corresponding to a language yet to be determined. Its 'hardware' side, entirely implemented in Javascript, simulates an amalgam of 1950s and 1960s computers, including the IBM 1401, the DEC PDP-8/I, and the Burroughs 3500 series.

Simusense is built in modules structured around its main engine, which you can find in the `memory-and-console` commit.

As of 29. 4. 2018, its modules are:

1) the main engine module
2) a HTML interface module
3) the main storage algorithm
4) a module to expand memory, analogous to adding another card stack or tape reel
5) the main parser (which can currently move within memory, retrieve one or more memory slots, and increment a memory space by one)
6) the beginnings of the ALU (a multiplier and a subtractor in modules, and the increment function for adding)
7) an early array definition

---------------

PS: 'Simusense' is of course not my invention - it's from <a href="https://en.wikipedia.org/wiki/Perry_Rhodan">the world's largest (and arguably greatest) Science Fiction series</a>.
