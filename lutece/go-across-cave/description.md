
# Content

Several ACMers are standing at the entrance of a dark cave. The ACMers must all pass through the cave and stand together at the exit. Unfortunately, a variety of circumstances can make it impossible for them to all pass through the cave together at the same time. Therefore, they may have to take turns going through the cave in smaller groups. There is only one map though, and it is impossible to navigate the cave without it, so whenever a group of ACMers is inside the cave, one member of that group must be holding the map. When a group of ACMers walks through the cave, either from the entrance or the exit, they must traverse an old bridge to get to the other side of the cave. The entire group inside the cave must cross the bridge together at the same time. The bridge cannot hold more than bridgeStrength kilograms, or it will collapse. You are given ACMersWeights, where the $i$-th element is the weight of the $i$-th traveler in kilograms. ACMers may walk through the cave alone. Although, when ACMers walk through the cave in a group of two or more, each ACMers must trust at least one of the other ACMers in the group. You are given trustTable, where the $j$-th character of the i-th element is `Y` if ACMers $i$ trusts ACMers $j$, and `N` otherwise. Note that the trust relation is not necessarily symmetric. ACMers walk at different speeds, but when they go through the cave, they must stick together and walk at the same speed. Therefore, when a group of ACMers walks through the cave, they must walk at the speed of the slowest ACMers in the group.

You are given a ACMersTimes, where the $i$-th element is the amount of time it takes the i-th ACMers to walk through the cave in any direction. Return the minimal total time required for all the travelers to end up together at the exit of the cave. If it is impossible, return `-1` instead.

# Standard Input

First is an integer indicating the number of cases.

The first line of each case contains an integer $N$, representing the number of people$[1,13]$.

The second line contains $N$ integers. Each one represents an ACMersWeights $[1,1000]$.

The third line contains $N$ integers. Each one represents an ACMersTimes $[1, 1000]$.

Following $N$ lines is the $N \times N$ trustTable. Each line of trustTable will contain $N$ uppercase letters `Y` and `N`. The $i$-th character of the $i$-th element of trustTable will always be `Y`.

The last line contains an integer representing BridgeStrength $[1，5000]$.

# Standard Output

One line, the least time required for all travelers to end up together at the exit of the cave.

If impossible, Output `-1`.

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
<tr><td>2
3
1 1 1
2 3 4
YYY
YYY
YYY
2
3
1 1 1
2 3 4
YYY
YYY
NYY
2</td><td>9
10</td></tr></table>


# Constraints



# Note



# Source


