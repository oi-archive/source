
# Content

The $15$-puzzle has been around for over $100$ years; even if you don't know it by that name, you've seen it. It is constructed with $15$ sliding tiles, each with a number from $1$ to $15$ on it, and all packed into a $4$ by $4$ frame with one tile missing. Let's call the missing tile `x`; the object of the puzzle is to arrange the tiles so that they are ordered as: 
```
 1  2  3  4 

 5  6  7  8 

 9 10 11 12 

13 14 15  x
```
where the only legal operation is to exchange `x` with one of the tiles with which it shares an edge. As an example, the following sequence of moves solves a slightly scrambled puzzle: 
```
 1  2  3  4   1  2  3  4   1  2  3  4   1  2  3  4 

 5  6  7  8   5  6  7  8   5  6  7  8   5  6  7  8 

 9  x 10 12   9 10  x 12   9 10 11 12   9 10 11 12 

13 14 11 15  13 14 11 15   13 14  x 15  13 14 15 x 

            r->          d->           r->
```
The letters in the previous row indicate which neighbor of the `x` tile is swapped with the `x` tile at each step; legal values are `r`,`l`,`u` and `d`, for right, left, up, and down, respectively. 

Not all puzzles can be solved; in $1870$, a man named Sam Loyd was famous for distributing an unsolvable version of the puzzle, and 
frustrating many people. In fact, all you have to do to make a regular puzzle into an unsolvable one is to swap two tiles (not counting the missing `x` tile, of course). 

In this problem, you will write a program for solving the less well-known $8$-puzzle, composed of tiles on a three by three 
arrangement. To simplify this problem, you should print the minimum steps only.

# Standard Input

There are multiple test cases.

For each test case, you will receive a description of a configuration of the $8$ puzzle. The description is just a list of the tiles in their initial positions, with the rows listed from top to bottom, and the tiles listed from left to right within a row, where the tiles are represented by numbers $1$ to $8$, plus `x`. For example, this puzzle
```
1 2 3

x 4 6

7 5 8
```
is described by this list:
```
1 2 3 x 4 6 7 5 8 
```

# Standard Output

You will print to standard output either the word `unsolvable`, if the puzzle has no solution.Otherwise, output an integer which equals the minimum steps.

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>1 2 x 4 5 3 7 8 6</td><td>2</td></tr></table>


# Constraints



# Note

Any violent algorithm may gain TLE. So a smart method is expected.

The data used in this problem is unofficial data prepared by hzhua. So any mistake here does not imply mistake in the offcial judge data.

# Source


