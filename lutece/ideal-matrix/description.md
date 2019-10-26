
# Content

Dave has a big matrix with a lowercase in each cell. In this matrix, he find some small matrix very attractive, he call them ieadl matrix.

A matrix is a ieadl matrix when it matches following conditions.
1. For each row,  nomatter you read it from right to left or from left to right, it would be same;
2. For each column, nomatter you read it from bottom to front or from front to bottom, it would be same;

example:
```
  a b a    a b b
  c c c    c c c        
  a b a    a b a
```
Frist one is a ideal matrix. And second is not,beacuse in first row, when you read it from left to right,it is `abb` ,and when you read it from right to left it is `bba`. now he  want to konw biggest size ideal matrix he can find in this big matrix.

# Standard Input

Frist line has tow element $n$, indicate number of rows and number of column.

Following $n$ line, each have $n$ lowercase.

$ 1 \leq n \leq 200$

# Standard Output

One number, indecate the answer.

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
dbda
cfcb
dbdc
defg</td><td>9</td></tr><tr><td>3
abc
def
ghi</td><td>1</td></tr><tr><td>4
abcd
efgh
abcd
abcd
</td><td>3</td></tr></table>


# Constraints



# Note



# Source


