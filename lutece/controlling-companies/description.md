
# Content

Some companies are partial owners of other companies because they have acquired part of their total shares of stock. For example, Ford owns $12\%$ of Mazda. It is said that a company $A$ controls company $B$ if at least one of the following conditions is satisfied:

* Company $A$ = Company $B$
* Company $A$ owns more than $50\%$ of Company $B$
* Company $A$ controls $K$ ($K\geq 1$) companies denoted $C\_1, \cdots, C\_K$ with each company $C\_i$ owning $x\_i\%$ of company $B$ and $x\_1 + \cdots + x\_K > 50\%$.

Given a list of triples $(i,j,p)$ which denote company $i$ owning $p\%$ of company $j$, calculate all the pairs $(h,s)$ in which company $h$ controls company $s$. There are at most $100$ companies.

Write a program to read the list of triples $(i,j,p)$ where $i$, $j$ and $p$ are positive integers all in the range $[1\cdots 100]$ and find all the pairs $(h,s)$ so that company $h$ controls company $s$.

# Standard Input

Line $1$: $n$, the number of input triples to follow

Line $2\cdots n+1$: Three integers per line as a triple $(i,j,p)$ described above.

# Standard Output

List $0$ or more companies that control other companies. Each line contains two integers that denote that the company whose number is the first integer controls the company whose number is the second integer. Order the lines in ascending order of the first integer (and ascending order of the second integer to break ties). Do not print that a company controls itself.

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
1 2 80
2 3 80
3 1 20</td><td>1 2
1 3
2 3</td></tr></table>


# Constraints



# Note



# Source


