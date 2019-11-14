
# Content

A sports company is planning to advertise in a tournament. It is a single round-robin tournament, that's to say competitors play with all the others once. The company thinks that the advertising impact is proportional to the so called `competitiveness degree`(CD) of the tournament.

CD is calculated in the following way: We assume there're $N$ competitors in the tournament and of course $\frac{N\times (N - 1)}{2}$ matches in total. For each competitor we define two values $S$ and $E$ which stand for skill and experience. We say a match between competitor $i$ and competitor $j$ is competitive if and only if $S\_i + E\_i \geq S\_j$ and $S\_j + E\_j \geq S\_i$. CD equals to the number of competitive matches among all $\frac{N\times (N - 1)}{2}$ matches in the tournament.

# Standard Input

One integer $T$ ($T \leq 20$) on the first line indicates the number of cases. The first line of each case contains one integer $N$ ($1\leq N\leq 10000$) -- the number of competitors. Then $N$ lines follows. The $i\_{th}$ line contains two integer $S\_i$ and $E\_i$ ($1\leq S\_i, E\_i\leq 100000000$) which are defined in the description.

# Standard Output

For each case, print the value of CD on a line.

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
2
1 2
4 1
2
1 2
2 2
5
1 9
5 4
3 4
2 2
6 2</td><td>0
1
8</td></tr></table>


# Constraints



# Note



# Source


