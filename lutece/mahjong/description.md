
# Content

Mahjong is a wonderful game which origins from China (or maybe Korea because everything is Korean). 

Mahjong is also a complex game. But the game we play here is rather easy. It just contains three suits: stones, bamboos and characters. 

Stones consist of a number of circles. Each circle is said to represent can (筒, tóng) coins with a square hole in the middle. 

Bamboos consist of a number of bamboo sticks. Each stick is said to represent a string (索, suǒ) that holds a hundred coins. Note that $1$ Bamboo is an exception: it has a bird sitting on a bamboo, to prevent alteration. 

Each character represents ten thousand (萬, wàn) coins. 

A player wins the round by creating a standard mahjong hand, which consists of a certain number of melds (namely, four for $13$-tile variations) and a pair. A meld is three tiles which are adjacent in one suit or all the same. A pair is two same tiles. 

Now one player has three tiles in hand. Can you tell what more tile he need to win? 

Note that the number of each tile in Mahjong is four. So if the number of one tile the player has is four, he cannot get this tile anymore.

# Standard Input

The first line contains one integer $T$ indicating the number of test cases. 

For each case, there are thirteen tiles in one line, separated by one space. 

Each tile has two characters. The first character is `1` to `9` and the second is `s` (for stone), `b` (for bamboo), or `c` (for character).

# Standard Output

For each case, output one line containing the case number and all the tiles he needs to win the round, separated by one space. 

If he needs more than one tile, first output stone, then bamboo, finally character, all from $1$ to $9$. 

If he cannot win after get any tile, output `None` instead. 

Please follow the format of the sample output.

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
<tr><td>5 
1b 1b 2b 2b 3b 3b 5s 6s 7s 1c 1c 2c 2c 
3s 4s 4s 5s 5s 5s 6s 6s 7s 9c 9c 4c 5c 
1s 1s 1s 2s 3s 4s 5s 6s 7s 8s 9s 9s 9s 
4b 5b 6b 7b 8b 8b 8b 2b 3b 4b 5s 6s 7s 
4c 5c 6c 9b 9b 9b 9b 1s 2s 3s 2s 3s 4s</td><td>Case 1: 1c 2c
Case 2: 3c 6c
Case 3: 1s 2s 3s 4s 5s 6s 7s 8s 9s
Case 4: 1b 3b 4b 6b 7b 9b
Case 5: None</td></tr></table>


# Constraints



# Note

In case $3$, if the player gets `1s`, he can combine them into four melds `1s1s1s`, `1s2s3s`, `4s5s6s`, `7s8s9s` and a pair `9s9s`. And so it is with `2s` to `9s`.

    2s: 1s1s1s, 3s4s5s, 6s7s8s, 9s9s9s, 2s2s 
    3s: 1s2s3s, 3s4s5s, 6s7s8s, 9s9s9s, 1s1s 
    4s: 1s1s1s, 2s3s4s, 4s5s6s, 7s8s9s, 9s9s 
    5s: 1s1s1s, 2s3s4s, 6s7s8s, 9s9s9s, 5s5s 
    6s: 1s2s3s, 4s5s6s, 6s7s8s, 9s9s9s, 1s1s 
    7s: 1s1s1s, 2s3s4s, 5s6s7s, 7s8s9s, 9s9s 
    8s: 1s1s1s, 2s3s4s, 5s6s7s, 9s9s9s, 8s8s 
    9s: 1s2s3s, 4s5s6s, 7s8s9s, 9s9s9s, 1s1s

# Source


