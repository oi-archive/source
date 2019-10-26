
# Content

Multiplying factors is one of the most tiresome jobs of algebra, so now you might want to take the help of computers to do that. In this problem you will have to deal with expression of the form, given the value of $n$. To be more specific for $n=2$ you have to find the length of the output $x^2+x(a\_1+a\_2)+a\_1a\_2$, for $n=3$ you have to find the length of the output $x^3+x^2(a\_1+a\_2+a\_3)+x(a\_1a\_2+a\_1a\_3+a\_2a\_3)+a\_1a\_2a\_3$ and so on. In plain text mode this type of strings can be outputted in three lines as:
$x\_3+x\_2(a\_1+a\_2+a\_3)+x(a\_1a\_2+a\_1a\_3+a\_2a\_3)+a\_1a\_2a\_3$

So the length of the result is $40$ when $n=3$. As with growth of $n$ the length grows very fast so you don’t need to output the length but output modulo $10000$ value of the length only. For your convenience you might want to notice that for $n=10$ the initial part of the multiplication answer is:
$x^{10}+x^9(a\_1+a\_2+\cdots + a\_10)+\cdots +a\_1a\_2a\_3a\_4a\_5a\_6a\_7a\_8a\_9a\_{10}$

# Standard Input

The input file contains at most $6000$ lines of inputs. Each line consists of a single integer $n$ ($0<n\leq 1000000000$). Here n means the number of factors that are to be multiplied.

# Standard Output

For each line of input produce one line of output. If the length of the multiplied string is t then for each input you should output the serial of output followed by $t\ mod\ 10000$. Please note that you don’t need to put any unnecessary brackets and also note that you don’t need to output terms like $x\_1$. Show the power of $x$ only when it is greater than $1$.

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
<tr><td>1
2
3
4
5
8
12</td><td>Case 1: 4
Case 2: 16
Case 3: 40
Case 4: 92
Case 5: 208
Case 6: 2332
Case 7: 9439</td></tr></table>


# Constraints



# Note



# Source


