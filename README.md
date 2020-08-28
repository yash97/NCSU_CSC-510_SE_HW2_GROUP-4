# CSC 510 Software Engineering HW2 GROUP-4

[![Build Status](https://travis-ci.com/bhoomi2807/NCSU_CSC-510_SE_HW2_GROUP-4.svg?branch=master)](https://travis-ci.com/bhoomi2807/NCSU_CSC-510_SE_HW2_GROUP-4) <a href="https://doi.org/10.5281/zenodo.3995130"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.3995130.svg" alt="DOI"></a>

This repository is part of CSC 510 Software Engineering HW2 and HW3. It contains the [Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life) implementation in Julia, Ruby and Scala.

- [Julia](https://github.com/bhoomi2807/NCSU_CSC-510_SE_HW2_GROUP-4/tree/master/Julia) contains the code for Game of Life written in Julia.
- [Ruby](https://github.com/bhoomi2807/NCSU_CSC-510_SE_HW2_GROUP-4/tree/master/Ruby) contains the code for Game of Life written in Ruby.
- [Scala](https://github.com/bhoomi2807/NCSU_CSC-510_SE_HW2_GROUP-4/tree/master/Scala) contains the code for Game of Life written in Scala.

[SCIRPT.md](https://github.com/bhoomi2807/NCSU_CSC-510_SE_HW2_GROUP-4/blob/master/Script.md) has the instructions to conduct the experiment.<br>
[RESULT.md](https://github.com/bhoomi2807/NCSU_CSC-510_SE_HW2_GROUP-4/blob/master/RESULTS.md) has the observations and conclusion (For HW3).

## Game of Life
The game consists of a grid where in each cell value represents if the cell is alive or dead.
1 -> Alive
0 -> Dead

The game has 3 tunable parameters:
  - Grid size
  - Number of cells alive
  - Generations
  
The output will be the grid after guven number of generations based on following rules,

     C   N                 new C
     1   0,1             ->  0  // Lonely
     1   4,5,6,7,8       ->  0  // Overcrowded
     1   2,3             ->  1  // Lives
     0   3               ->  1  // It takes three to give birth!
     0   0,1,2,4,5,6,7,8 ->  0  // Barren

## Execution Instructions
1. Online Compiler:<br>
Copy and paste the code in online compilers like [Repl](https://repl.it/), [JDoodle](https://www.jdoodle.com/), [OnlineGDB](https://www.onlinegdb.com/), etc.

2. Local Execution:<br>
Go to a specific language's README page to find detailed instructions.

## Group 4 Details:
1. [Alisha Shahane](mailto:asshahan@ncsu.edu) (asshahan)<br>
2. [Shruti Kangle](mailto:sskangle@ncsu.edu) (sskangle)<br>
3. [Bhoomi Shah](mailto:bshah2@ncsu.edu) (bshah2)<br>
4. [Poorva Kulkarni](mailto:pnkulkar@ncsu.edu) (pnkulkar)<br>
5. [Rohan Pillai](mailto:rspillai@ncsu.edu) (rspillai)<br>
