
# Content

There is a kind of special fish in the East Lake where is closed to campus of Wuhan University. It’s hard to say which gender of those fish are, because every fish believes itself as a male, and it may attack one of some other fish who is believed to be female by it. 

A fish will spawn after it has been attacked. Each fish can attack one other fish and can only be attacked once. No matter a fish is attacked or not, it can still try to attack another fish which is believed to be female by it. 

There is a value we assigned to each fish and the spawns that two fish spawned also have a value which can be calculated by `XOR` operator through the value of its parents. 

We want to know the maximum possibility of the sum of the spawns.

# Standard Input

The input consists of multiply test cases. The first line of each test case contains an integer $n$ ($0 < n\leq 100$), which is the number of the fish. The next line consists of n integers, indicating the $value$ ($0 < value\leq 100$) of each fish. The next $n$ lines, each line contains $n$ integers, represent a $01$ matrix. The $i\_{th}$ fish believes the $j\_{th}$ fish is female if and only if the $value$ in row $i$ and column $j$ if $1$. The last test case is followed by a zero, which means the end of the input.

# Standard Output

Output the value for each test in a single line.

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
<tr><td>3 
1 2 3 
011 
101 
110 
0</td><td>6</td></tr></table>


# Constraints



# Note



# Source


