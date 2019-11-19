
# Content

Tom and Sarah soon have their second anniversary and he wants to buy her something special. Even
though she's very keen on any kind of tree, he thinks that this probably is too big of a gift. So, he
decides to buy her flowers. But not the lame cut off ones that will die after two weeks tops. No,
he wants to buy her flowers that may last forever. Flowers in a flower pot. Now, he has a problem.
Finding the right flowers for his girlfriend isn’t that difficult. However, finding the right flower pot
turns out to be much more complicated. Since he wants the flowers to live as long as possible, he
needs to find the best-fitting flower pot he can find. When he comes to the Arboreal and Crops
Market, he notices that for each bouquet of flowers there is an optimal size written for the flower
pot. However, the offered flower pots do not state their volume. The only information the shop
assistant can provide is the outline of each flower pot given as a function. Since Tom was never
very good in math and his date is in less than an hour, he asks a nearby customer for help: You.
Fortunately, you brought your laptop on your shopping tour. Can you help Tom?

The outline of a flower pot is described by a function $f(x) = a\times e^{-x^2}+b\times \sqrt{x}$
, 
where $x$ is the 
vertical distance from the bottom of the flower pot. The body of the flower pot thus is defined by
the rotational body created when rotating the graph of $f$ around the $x$-axis. The height of a flower
pot is denoted by $h$.

The volumes of two flower pots differ at least by $10^{−4}$ . Also there is only one flower pot closer to
the optimal than any other one, with an accuracy to $10^{−4}$.

# Standard Input

The input always contains one test case which consists of several lines.
The first line contains a decimal number $0< V\leq 10^5$, the optimal size for Tom's favorite flower,
and an integer $0< N\leq 5$, the number of flower pots available.
The next $N$ lines each contain three decimal numbers describing the corresponding $k^{th}$ flower pot:
$0\leq a_k\leq 10$, $0\leq b_k\leq 10$, and $1\leq h_k\leq 10$.
For the sample input the volumes are approximately $34.72348$ and $21.77966$.

# Standard Output

Print one line containing a single integer that describes the index of the best fitting flower pot. The
index of the first flower pot is $0$.

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
<tr><td>25.0 2
1.0 2.0 2.0
2.0 1.0 2.0</td><td>1</td></tr></table>


# Constraints



# Note



# Source


