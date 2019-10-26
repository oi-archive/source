
# Content

It was a dark and stormy night that ripped the roof and gates off the stalls that hold Farmer John's cows. Happily, many of the cows were on vacation, so the barn was not completely full.

The cows spend the night in stalls that are arranged adjacent to each other in a long line. Some stalls have cows in them; some do not. All stalls are the same width.

Farmer John must quickly erect new boards in front of the stalls, since the doors were lost. His new lumber supplier will supply him boards of any length he wishes, but the supplier can only deliver a small number of total boards. Farmer John wishes to minimize the total length of the boards he must purchase.

Given $M$ ($1\leq M\leq 50$), the maximum number of boards that can be purchased; $S$ ($1\leq S\leq 200$), the total number of stalls; $C$ ($1\leq C\leq S$) the number of cows in the stalls, and the $C$ occupied stall numbers ($1\leq stall\ number\leq S$), calculate the minimum number of stalls that must be blocked in order to block all the stalls that have cows in them.

Print your answer as the total number of stalls blocked.

# Standard Input

Line $1$: $M$, $S$, and $C$ (space separated)

Lines $2-C+1$: Each line contains one integer, the number of an occupied stall.

# Standard Output

A single line with one integer that represents the total number of stalls blocked.

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
<tr><td>4 50 18
3
4
6
8
14
15
16
17
21
25
26
27
30
31
40
41
42
43</td><td>25</td></tr></table>


# Constraints



# Note



# Source


