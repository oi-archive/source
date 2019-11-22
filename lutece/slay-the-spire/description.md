
# Content

Slay The Spire is a rogue-like video game with deck-building card game mechanics. The goal is to work through several levels of a spire, each level having a monster with a boss character at the end of the level.

This day The Ironclad called Mengnan hopes to conquer this spire again. Mengnan is the one with careful plans so he would like to know if he is able to achieve this challenge with calculation.

Mengnan starts the game with $m$ health point and $99$ gold. When it drops to zero, Mengnan will fall down and have to restart from the bottom of the spire. The upper limit of Mengnan's health point is $1000000$. As for gold, this time Mengnan will not use any of them.

Mengnan is not a rash guy. Mengnan brings a smoke with himself. He can use (for only once) the smoke to escape fighting with the monster of any level except the last level guarded by boss, and go to the next level straightly. 

Mengnan is a tough guy. Mengnan can get a health point recovery with $4$ points when he climbs up one level (whether using smoke).

Mengnan has two relics which are beneficial for his fight. Golden Idol makes Mengnan gain $25\%$ more gold after each battle and Magic Flower brings $50\%$ more healing whenever Mengnan gets a headlth recovery.

Mengnan spares his every free time to practice this game. He knows well the monster of each level so that he knows he will drop a health point with $a[i]$ points if he fights with the monster of the $ith$ level.

Now Mengnan asks you, the master of Slay The Spire, to tell him if he could succeed if he optimizes his plan.

# Standard Input

On the first line of the input are two integers $m$ ($1 \leq m \leq 10000$) and $n$ ($1 \leq n \leq 100000$), indicating the health point when Mengnan starts this game and the number of levels of the spire.

​	On the second line of the input are n integers $a[i]$, indicating the health point Mengnan will drop if he fights with the monster of the $ith$ ($0 \leq a[i] \leq 100$) level.

# Standard Output

Print if Mengnan can win this game. If he can somehow then print `YES`, else print `NO`. Note that the answer is case sensitive.

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
<tr><td>10 5
1 2 3 4 10</td><td>YES</td></tr><tr><td>10 3
10 10 10</td><td>YES</td></tr></table>


# Constraints



# Note

It seems like using the smoke when its necessary (or Mengnan'll be dead) is not always the best choice.

# Source


