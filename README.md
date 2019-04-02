# Programming Puzzels


## Complete Search
* Iterative Single Scan
- [x] UVa 00102 - Ecological Bin Packing
- [x] UVa 00256 - Quirksome Squares
- [x] UVa 00927 - Integer Sequence from
- [x] UVa 01237 - Expert Enough
- [ ] UVa 10976 - Fractions Again?
- [ ] UVa 11001 - Necklace
- [ ] UVa 11078 - Open Credit System
          
* Iterative Double Scan
- [x] UVa 00105 - The Skyline Problem (height map, sweep left-right)
- [x] UVa 00347 - Run, Run, Runaround (simulate the process)
- [x] UVa 00471 - Magic Numbers (somewhat similar to UVa 725)
- [ ] UVa 00617 - Nonstop Travel (try all integer speeds from 30 to 60 mph) 
- [ ] UVa 00725 - Division (elaborated in this section)
- [ ] UVa 01260 - Sales * (LA 4843, Daejeon10, check all)
- [ ] UVa 10041 - Vito’s Family (try all possible location of Vito’s House) 
- [ ] UVa 10487 - Closest Sums
- [ ] UVa 10730 - Antiarithmetic?
- [ ] UVa 11242 - Tour de France * (plus sorting)
- [ ] UVa 12488 - Start Grid (2 nested loops; simulate overtaking process)
- [ ] UVa 12583 - Memory Overflow (2 nested loops; be careful of overcounting)

* Iterative Triple Scan
- [ ] UVa 00154 - Recycling (3 nested loops)
- [x] UVa 00188 - Perfect Hash (3 nested loops, until the answer is found)
- [ ] UVa 00441 - Lotto * (6 nested loops)
- [ ] UVa 00626 - Ecosystem (3 nested loops)
- [ ] UVa 00703 - Triple Ties
- [ ] UVa 00735 - Dart-a-Mania * (3 nested loops, then count)
- [ ] UVa 10102 - The Path in the ... *
- [ ] UVa 10502 - Counting Rectangles (6 nested loops, rectangle, not too hard)
- [ ] UVa 10662 - The Wedding (3 nested loops)
- [ ] UVa 10908 - Largest Square (4 nested loops, square, not too hard)
- [ ] UVa 11059 - Maximum Product (3 nested loops, input is small)
- [ ] UVa 11975 - Tele-loto (3 nested loops, simulate the game as asked)
- [ ] UVa 12498 - Ant’s Shopping Mall (3 nested loops)
- [ ] UVa 12515 - Movie Police (3 nested loops)

* Iterative Three or More Scans
- [x] UVa 00253 - Cube painting (try all, similar problem in UVa 11959)
- [x] UVa 00296 - Safebreaker
- [x] UVa 00386 - Perfect Cubes (4 nested loops with pruning)
- [ ] UVa 10125 - Sumsets (sort; 4 nested loops; plus binary search)
- [ ] UVa 10177 - (2/3/4)-D Sqr/Rects
- [ ] UVa 10360 - Rat Attack (also solvable using 10242 DP max sum)
- [ ] UVa 10365 - Blocks (use 3 nested loops with pruning)
- [ ] UVa 10483 - The Sum Equals
- [ ] UVa 10660 - Citizen attention
- [ ] UVa 10973 - Triangle Counting (3 nested loops with pruning)
- [ ] UVa 11108 - Tautology (5 nested loops, try all 25 = 32 values with pruning)
- [ ] UVa 11236 - Grocery Store
- [ ] UVa 11342 - Three-square
- [ ] UVa 11548 - Blackboard Bonanza (4 nested loops, string, pruning)
- [ ] UVa 11565 - Simple Equations * (3 nested loops with pruning)
- [ ] UVa 11804 - Argentina (5 nested loops)
- [ ] UVa 11959 - Dice (try all possible dice positions, compare with the 2nd one)

* Iterative (Fancy Techniques)
- [x] UVa 00140 - Bandwidth (max n is just 8, use next permutation; the algo- rithm inside next permutation is iterative)
- [x] UVa 00234 - Switching Channels (use next permutation, simulation)
- [ ] UVa 00435 - Block Voting (only 220 possible coalition combinations)
- [ ] UVa 00639 - Don’t Get Rooked (generate 216 combinations and prune)
- [ ] UVa 01047 - Zones *
- [ ] UVa 01064 - Network (LA 3808, WorldFinals Tokyo07, permutation of up to 5 messages, simulation, mind the word ‘consecutive’)
- [ ] UVa 11205 - The Broken Pedometer (try all 215 bitmask)
- [ ] UVa 11412 - Dig the Holes (next permutation, find one possibility from 6!)
- [ ] UVa 11553 - Grid Game *
- [ ] UVa 11742 - Social Constraints (discussed in this section)
- [ ] UVa 12249 - Overlapping Scenes (LA 4994, KualaLumpur10, try all permu- tations, a bit of string matching)
- [ ] UVa 12346 - Water Gate Management (LA 5723, Phuket11, try all 2n com- binations, pick the best one)
- [ ] UVa 12348 - Fun Coloring (LA 5725, Phuket11, try all 2n combinations)
- [ ] UVa 12406 - Help Dexter (try all 2p possible bitmasks, change ‘0’s to ‘2’s)
- [ ] UVa 12455 - Bars * (discussed in this section)

* Recursive Backtracking (Easy)
- [ ] UVa 00167 - The Sultan Successor (8-queens chess problem)
- [ ] UVa 00380 - Call Forwarding (simple backtracking, but we have to work with strings, see Section 6.2)
- [ ] UVa 00539 - The Settlers ... (longest simple path in a small general graph)
- [ ] UVa 00624 - CD * (input size is small, backtracking is enough)
- [ ] UVa 00628 - Passwords (backtracking, follow the rules in description)
- [ ] UVa 00677 - All Walks of length “n” ... (print all solutions with backtracking)
- [ ] UVa 00729 - The Hamming Distance ... (generate all possible bit strings)
- [ ] UVa 00750 - 8 Queens Chess Problem (discussed in this section with sample source code)
- [ ] UVa 10276 - Hanoi Tower Troubles Again (insert a number one by one)
- [ ] UVa 10344 - 23 Out of 5 (rearrange the 5 operands and the 3 operators)
- [ ] UVa 10452 - Marcus, help (at each pos, Indy can go forth/left/right; try all)
- [ ] UVa 10576 - Y2K Accounting Bug * (generate all, prune, take max)
- [ ] UVa 11085 - Back to the 8-Queens * (see UVa 750, pre-calculation)

* Recursive Backtracking (Medium)
- [x] UVa 00222 - Budget Travel
- [ ] UVa 00301 - Transportation (222 with pruning is possible)
- [ ] UVa 00331 - Mapping the Swaps (n ≤ 5...)
- [ ] UVa 00487 - Boggle Blitz (use map to store the generated words)
- [ ] UVa 00524 - Prime Ring Problem * (also see Section 5.5.1)
- [ ] UVa 00571 - Jugs (solution can be suboptimal, add flag to avoid cycling) 
- [ ] UVa 00574 - Sum It Up * (print all solutions with backtracking)
- [ ] UVa 00598 - Bundling Newspaper (print all solutions with backtracking)
- [ ] UVa 00775 - Hamiltonian Cycle
- [ ] UVa 10001 - Garden of Eden 
- [ ] UVa 10063 - Knuth’s Permutation (do as asked)
- [ ] UVa 10460 - Find the Permuted String (similar nature with UVa 10063)
- [ ] UVa 10475 - Help the Leaders (generate and prune; try all)
- [ ] UVa 10503 - The dominoes solitaire
- [ ] UVa 10506 - Ouroboros
- [ ] UVa 10950 - Bad Code
- [ ] UVa 11201 - The Problem with the 
- [ ] UVa 11961 - DNA 

* Recursive Backtrack (Harder)
- [ ] UVa 00129 - Krypton Factor 
- [ ] UVa 00165 - Stamps (requires some DP too; can be pre-calculated)
- [ ] UVa 00193 - Graph Coloring * (Max Independent Set, input is small)
- [x] UVa 00208 - Firetruck (backtracking with some pruning)
- [ ] UVa 00416 - LED Test * (backtrack, try all)
- [ ] UVa 00433 - Bank (Not Quite O.C.R.) (similar to UVa 416)
- [ ] UVa 00565 - Pizza Anyone? (backtracking with lots of pruning)
- [ ] UVa 00861 - Little Bishops
- [ ] UVa 00868 - Numerical maze
- [ ] UVa 01262 - Password 
- [ ] UVa 10094 - Place the Guards
- [ ] UVa 10128 - Queue
- [ ] UVa 10582 - ASCII Labyrinth
- [ ] UVa 11090 - Going in Cycle


## Divide and Conquer
* Binary Search 
* Bisection Method 
* Other


## Greedy
* Classic
* Containing Sorting
* Non Classic



## Dynamic Programming
* Max 1D Range Sum

* Max 2D Range Sum
* Longest Increasing Subsequence (LIS)
* 0-1 Knapsack (Subset Sum)
* Coin Change
* Travelling Salesman Problem (TSP)
* Non Classical 
* Other Classic 
  * Floyd Warshall's for All -Pairs Shortest Path problem
  * String Alignment (Edit Distance)
  * Longest Common Subsequence
  * Matrix Chain Multiplication
  * Max (Weighted) Independent Set (on Trees)
