
# Content

Here is a maze with N × M room.

You start from the room ($SR, SC$) and want to go to the room located at ($TR, TC$). However, there are many traps and monsters in this maze.

There are 4 types of rooms：
>#####1. Blank->('.').  which has nothing.
>#####2. Rock->('#').  which you can not enter it.
>#####3. Trap->('a'~'z'), which once you enter it, you will suffer (Trap-'a'+1) damage(s). After you leave,the trap will reset so it can be triggered next time.
>#####4. Monster->('A'~'Z'). If you go into a monster room or any room adjacent to a monster room, the monster will immediately rush up to you and fight with you. You will kill it, but you will get hurt too, suffering (Monster-'A'+1) damage(s). And the monster will not revive.

Two rooms are adjacent if and only if they share an edge.  You can take 1 step to go from a room to another adjacent room.

The safest path is a lowest total damage path. Among all safest path,find the path with lowest steps.

# Standard Input

The first line contains two integers N and M ($1 \leq N, M \leq 500$).

The second line contains 4 integers $SR, SC, TR, TC$ ($1 \leq SR, TR \leq N$ and $1 \leq SC, TC \leq M$).

For the next $N$ lines, each line contains $M$ characters indicating the map of maze. 
Each type of room is marked as:

>#####1. Blank->('.')
>#####2. Rock->('#')
>#####3. Trap: from 'a'~'z'
>#####4. Monster: from 'A'~'Z'

The damage you suffer from the trap 'a' is 1,'b' is 2..and so on. 

The damage you suffer from the monster 'A' is 1... and 'Z' is 26.

The room ($SR, SC$) and ($TR, TC$) are always blank rooms and will not be adjacent to any monster room.

# Standard Output

Output the lowest total damage and the lowest steps in all safest path.

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
<tr><td>3 5
1 1 3 5
..b..
.zC#.
..a..</td><td>4 6</td></tr></table>


# Constraints



# Note



# Source


