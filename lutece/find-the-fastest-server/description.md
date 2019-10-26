
# Content

Wizmann is famous for his excellent coding skills, who often shares his code on the Internet. However, the hopeless network in BUPT makes it hard for him to visit some open source websites. In order to connect these websites faster, Wizmann decides to write a program to find the fastest server no matter where he is. Due to his poor knowledge in algorithms,he needs your help to accomplish this goal.

To simplify your task, we can regard the whole network as an undirected graph. The vertices in the graph represent the hosts in the network, and the edges stand for the cables connecting them. Of course, there are some main servers, which we can also regard as vertices too. The weight on an edge indicates the average delay time on this cable.

Wizmann hopes that your program would be able to answer such queries:once he inputs the host's ID, the program should output the minimum delay time to connect from his host to the fastest server.

# Standard Input

The first line of input is an integer $T$ ($T\le 40$), which indicates the number of test cases.

In each test case, the first line consists of two integers $N$ and $M$($1\le N\le 10^4$, $1\le M\le 10^5$), which indicate the number of vertices and edges. Each of the next $M$ lines shows three integers $u$, $v$ and $w$($1\le u,v\le N$, $0< w \le 10^4$), which represent the two terminals' ID of the cable and the average time delay of this cable. The next line contains the number of servers $K$($1\le K\le 10^3$), and the following $K$ integers in the next line describe each server’s ID.

Following the description of the graph structure, there is an integer $Q$ ($1\le Q\le 10^4$) indicating the number of queries. Then each of the next $Q$ lines contains only one integer, which indicates the host ID that Wizmann queries. 

You may assume that the queried IDs are all of the hosts, and there’re no self-cables in the network.

# Standard Output

For each query, output one integer which means the minimum delay time between the querying host and the fastest server to it. If the queried host cannot connect to any server, you should just output $-1$. 

Output a blank line AFTER each test case.

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
3 2
1 2 2
2 3 3
2
1 3
1
2
4 4
1 2 2
2 3 4
3 4 1
4 1 3
2
2 4
2
1
3</td><td>2

2
1</td></tr></table>


# Constraints



# Note



# Source


