
# Content

baihacker chooses the easy mode and is borned in $X$ star. The 
lowest temperature of $X$ star is $0$ degree and the highest is 
$1000$ degree. 

The technology of $X$ star is so advanced that the relation 
department can predict the temperature of the coming $1000$ 
days. The temperature of each day is independent. When the
temperature difference of two consecutive days is larger 
than $K$, the people will be ill, so the relation department 
employ $Y$ company to control the temperature such that no
people will be ill for the temperature difference.

The cost of change the temperature $S$ degree of a day is $S\times S$.
When temperature difference of two consecutive days is $D$, 
then $Y$ company have to pay $A\times D$ for maintaining his honor.

As the CTO of Y company, you are to calculate the cheapest cost.

# Standard Input

The first line of the input is an integer $T$ which stands for
the number of test cases. Then $T$ test cases follow.

The first line of each test case is $3$ integers $N, K, A$ seperated
by a space. Then $N$ integers seperated by a space in a line to 
represent the temperatures in the coming $n$ days.

constraints:
* $A, K$ is in the range of $[0, 1000]$.
* $N$ is in the range of $[1, 1000]$.
* The temperature after adjusted can not be below $0$ or higher than $1000$.
* $T$ is no more than $150$.

# Standard Output

For each test case, output the cheapest cost in a single line.
The cost is defined as the sum of changing the temperator and 
maintaining their honor.

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
1 1 1
1
3 1 10
1 2 3</td><td>0
2</td></tr></table>


# Constraints



# Note



# Source


