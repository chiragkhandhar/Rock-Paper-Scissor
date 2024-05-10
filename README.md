# Rock Paper Scissors x99

<p align="center">
   <a style="text-decoration:none">
    <img src="https://img.shields.io/badge/Latest%20Version-v1.0-blue" alt="version" />
  </a>
  <a style="text-decoration:none">
    <img src="https://img.shields.io/badge/Platform-JavaScript-brightgreen" alt="Platform" />
  </a>
   <a style="text-decoration:none" href="https://chiragkhandhar.github.io/Rock-Paper-Scissor" target="_blank">
    <img src="https://img.shields.io/badge/Play-Game-red" alt="Platform" />
  </a>
</p>

![image](https://user-images.githubusercontent.com/37962354/82131215-7c08dc00-9798-11ea-9dfe-1b18cafdf801.png)

## Overview

This is the more intense version of Rock Paper Scissors (RPS). Rather than selecting just one of Rock, Paper, or Scissors each player will select three moves. Each move will consist of a type (Rock, Paper, or Scissors) as well as a strength value. Each player will have 99 total points to use as strength between all three of their moves. For example, an example set of moves might be:

- Move 1: Rock - 30 Strength Points
- Move 2: Rock - 60 Strength Points
- Move 3: Paper - 9 Strength Points


The strength for each move must be at least 1.

After each player's moves are chosen, they will compare  oves in the order they were selected. If two moves have different types (for example, Rock vs Scissors), then normal RPS rules will apply (in this case, Rock beats Scissors).
However, if two types are the same, then the move with more strength will win. If both strength values are
equal, then a tie is declared.

The player that wins the majority of the three rounds will be the winner of the game.


## Deployments

You can play this game [here](https://chiragkhandhar.github.io/Rock-Paper-Scissor-x99/)


## Developer Testing

A testing suite has been provided for you, checking for all essential functionality and edge cases. Mocha is used as a testing framework.

To run these tests, first open the root project directory in your terminal. Then run `npm install` to install all necessary testing dependencies (you will only need to do this step once).
Finally, run `npm run test`. You will see a list of tests that ran with information about whether or not each test passed. After this list, you will see more specific output
about why each failing test failed.

As you implement functionality, run the tests to ensure you are creating correctly named variables and functions that return the proper values. The tests will additionally help you identify edge cases that you may not have anticipated
when first writing the functions.

## Contributing:

* This project is free and open source, if you like my work, please consider:
    
    * Follow me on GitHub
    * Star this project
    * Endorse me [here](https://www.linkedin.com/in/chirag-khandhar/)


## Stay tuned 📢
