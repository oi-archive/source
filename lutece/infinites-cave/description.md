
# Content

It is said that the people of Infinite lived in caves. A tribe's caves were connected to each other with paths. The paths were so designed that there was one and only one path to each cave. So the caves and the paths formed a tree. There was a main cave, which connected the world outside. The Infinite people always carved a map of the tribe's caves on the wall of the main cave. 

Recently a famous scientist Chiara has just discovered Infinite's tribe. What a heart-stirring discovery! She is eager to explore it. Since the terrain is very complex and dangerous, she designed a robot xqq to explore the caves. 

Xqq will be landed into the main cave, where he will begin his adventure. It doesn't have to return to the main cave, because the messages of his exploration will be sent immediately to Chiara while he is on the way. 

Xqq can only walk $x$ meters before it runs out of energy. So the problem arises: given the map of the tribe's caves and a set of $x$ , how many caves can be explored at most?

# Standard Input

There are multiple test cases in the input file. Each test case starts with a single number $n (0 \leq n \leq 500)$, which is the number of caves, followed by $n - 1$ lines describing the map. Each of the $n - 1$ lines contains three integers separated by blanks: $i$, $j$, and $d (1 \leq d \leq 10000)$. It means that the $i$-th cave's parent cave is the $j$-th cave and the distance is $d$ meters. A parent cave of cave i is the first cave to enter on the path from $i$ to the main cave. Caves are numbered from $0$ to $n - 1$. Then there is an integer $q (1 \leq q \leq 1000)$, which is the number of queries, followed by $q$ lines. For one query, there is one integer $x (0 \leq x \leq 5000000)$, the maximum distance that Xqq can travel. $n = 0$ indicates the end of input file.

# Standard Output

For each test case, output $q$ lines in the format as indicated in the sample output, each line contains one integer, the maximum number of caves the robot is able to visit.

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
1 0 5 
2 0 3 
3 
3 
10 
11 
0</td><td>Case 1: 
2 
2 
3</td></tr></table>


# Constraints



# Note



# Source


