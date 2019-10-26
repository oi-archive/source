
# Content

There are $n$ warehouses numbered with $1,2,\cdots,n$.

In each warehouse, there are $x_i$ stuff numbered with $1,2,\cdots,x_i$.

Now there is a robot facing to the $1^{st}$ warehouse. Every time the robot will pick up the stuff with the smallest number from the warehouse which it face to, and then turns to the next warehouse with stuff (the next of $n^{th}$ is $1^{st}$).

As a warehouse administrator, I want to find out the $k^{th}$ stuff that the robot picked up was in which warehouse and was the which number in that warehouse.

# Standard Input

The first line contains two numbers $n,m (1 \le n,m \le 10^5)$, indicating the number of warehouses and the number of queries.

The second line contains $n$ numbers $x_i (1 \le x_i \le 10^9)$, indicating the number of stuff in each warehouses.

Next $m$ lines each line contains one number $k (1 \le k \le \sum_{i=1}^n x_i )$, indicating the query.

# Standard Output

For each query output one line.

Each line contains two number $a,b$, the $k^{th}$ stuff was in $a^{th}$ warehouse and was the $b^{th}$ stuff in that warehouse.

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
<tr><td>3 6
1 2 3
1
2
3
4
5
6</td><td>1 1
2 1
3 1
2 2
3 2
3 3</td></tr></table>


# Constraints



# Note



# Source


