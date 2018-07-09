# Chaos game and the Sierpinski triangle

## Background

Chaos games are essentially random games with a fixed set of instructions. In the case of this example, we will see how chaos games can produce beautiful fractal structures. More information on chaos games can be found here:

https://en.wikipedia.org/wiki/Sierpinski_triangle#Chaos_game

The motivation for this project was this brilliant [video](https://www.youtube.com/watch?v=kbKtFN71Lfs&t=77s) produced by Numberphile. I would recommend watching this for a better context in this project.

## Algorithm

1. Draw an equilateral triangle without its edges. In this case, just plot 3 points for the 3 vertices. Let these be called `A`, `B` and `C` respectively. An example of this is shown in the figure below.

2. Define a random point within the equilateral triangle. 

3. Randomly choose one of the vertices `A`, `B` or `C`.

4. Draw another point halfway between the defined random point from step 2 and the randomly chosen vertex.

5. Repeat this process for `N` iterations.

This iterative process should lead to a beautiful convergence. Let's try this out below!

## Visualizations

### N = 100

<img src="https://github.com/AtreyaSh/chaosGameST/blob/master/images/chaos_game100.png" width="500">

### N = 400

<img src="https://github.com/AtreyaSh/chaosGameST/blob/master/images/chaos_game400.png" width="500">

### N = 1000

<img src="https://github.com/AtreyaSh/chaosGameST/blob/master/images/chaos_game1000.png" width="500">

### N = 2000

<img src="https://github.com/AtreyaSh/chaosGameST/blob/master/images/chaos_game2000.png" width="500">

### N = 10000

<img src="https://github.com/AtreyaSh/chaosGameST/blob/master/images/chaos_game10000.png" width="500">

Math is beautiful!
