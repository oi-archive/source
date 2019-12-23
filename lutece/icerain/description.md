
# Content

There will be $m$ persons to hold a wedding ceremony. As a nice girl, icerain want to choose at least one gift for each person.

There are $n$ gifts in a shop, the ith has a value $w_i$. When icerain is confusing how to select the gifts, a magician said to her that "after you choosing the gifts, you can choose an integer $x$ in the rang of $[0, 2^{30} - 1]$, and I can change the values of the gifts you chosen from $w_i$ to $w_i$ $\oplus$ $x$", "$\oplus$" means bitwise xor operation.

How lovely she is, but icerain is more confused about how to select the gifts and choose the number $x$. Can you help her to choose **at least** $m$ gifts and the number $x$ such that the average value of the gifts you chosen is as large as possible.

# Standard Input

The first line contains two integers $n$ and $m$.

The next line contains $n$ integers $w_1, w_2, ..., w_n$.

$1 \leq m \leq 20$, $m \leq n \leq 10000$, $0 \leq w_i \leq 2^{30}-1$.

# Standard Output

The maximum average value in the form of irreducible fraction.

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
<tr><td>4 2
1 1 1 1</td><td>1073741823/1</td></tr></table>


# Constraints



# Note



# Source


