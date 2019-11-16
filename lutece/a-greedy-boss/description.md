
# Content

Cloudiris is a greedy boss. On one hand, she wants her workers to work as long as possible. On the other hand, she doesn’t want to pay her workers much salary. She has found a relationship between the money($M$) she pays for a hour’s work and the time($T$) workers would like to work. And the relationship is something like this: $T=a+b \times M+ c \times M \times M$.(the $a, b, c$ here are positive variables that will be specified in the input). The Salary($S$) she pays for each worker will be $S=M \times T$. Now, as Cloudiris’s secretary, you are given $a, b, c$ and the maximum amount salary($S$) she would like to pay for each worker, and you are required to tell her how much money($M$) she should pay for a hour’s work so workers will work as long as possible and at the same time $M \times T$ won’t exceed $S$.

# Standard Input

The first line of the input contains a integer $N$ representing the number of test cases;

The following N lines each contains $4$ real numbers representing $a, b, c$ and $S$.

$S, a, b$ and $c$ will be larger than zero.

The input guarantees that $T$ won’t be larger than $24$ hours.

# Standard Output

For each test case, output one line with a real number $M$, rounded to $2$ digits after decimal point.

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
1 1 1 39
1.5 0.2 0.1 10</td><td>3.00
3.18</td></tr></table>


# Constraints



# Note



# Source


