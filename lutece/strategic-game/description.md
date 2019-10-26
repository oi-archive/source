
# Content

Bob enjoys playing computer games, especially strategic games, but sometimes he cannot find the solution fast enough and then he is very sad. Now he has the following problem. He must defend a medieval city, the roads of which form a tree. He has to put the minimum number of soldiers on the nodes so that they can observe all the edges. Can you help him? 

Your program should find the minimum number of soldiers that Bob has to put for a given tree. 

For example for the tree: 

![title](/source/lutece/strategic-game/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNDIzLzIwMTQwODE0MTgzNDA5NjUwOS5naWY=.gif)

the solution is one soldier ( at the node $1$).

# Standard Input

The input contains several data sets in text format. Each data set represents a tree with the following description:
* the number of nodes
* the description of each node in the following format
  * `node_identifier`: `(number_of_roads) node_identifier1 node_identifier2 ...` 
  * or `node_identifier`: `(0)`

The node identifiers are integer numbers between $0$ and $n-1$, for $n$ nodes ($0 < n \leq 1500$);**the number_of_roads in each line of input will no more than $20$**. Every edge appears only once in the input data.

# Standard Output

The output should be printed on the standard output. For each given input data set, print one integer number in a single line that gives the result (the minimum number of soldiers). An example is given in the following:

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
<tr><td>4
0:(1) 1
1:(2) 2 3
2:(0)
3:(0)
5
3:(3) 1 4 2
1:(1) 0
2:(0)
0:(0)
4:(0)</td><td>1
2</td></tr></table>


# Constraints



# Note



# Source


