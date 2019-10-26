
# Content

The trick to boiling vegetables is to make sure all pieces are about the same size. If they are not, the small ones get too soft or the large ones get undercooked (or both). Fortunately, you have heard of the kitchen knife, but your parents’ warnings of using sharp instruments still echoes in your head. Therefore you better use it as little as possible. You can take a piece of a vegetable of weight w and cut it arbitrarily in two pieces of weight $w\_{left}$ and $w\_{right}$, where $w\_{left} +w\_{right} = w$. This operation constitutes a `cut`. Given a set of pieces of vegetables, determine the minimum number of cuts needed to make the ratio between the smallest and the largest resulting piece go above a given threshold.

# Standard Input

The input starts with a floating point number $T$ with $2$ decimal digits, $0.5 < T < 1$, and a positive integer $N \leq 1 000$. Next follow $N$ positive integer weights $w\_1,w\_2, \cdots ,w\_N$. All weights are less than $10^6$.

# Standard Output

Output the minimum number of cuts needed to make the ratio between the resulting minimum weight piece and the resulting maximum weight piece be above $T$. You may assume that the number of cuts needed is less than $500$.

To avoid issues with floating point numbers, you can assume that the optimal answer for ratio $T$ is the same as for ratio $T + 0.0001$.

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
<tr><td>0.99 3
2000 3000 4000</td><td>6</td></tr><tr><td>0.80 2
1000 1400</td><td>3</td></tr></table>


# Constraints



# Note



# Source


