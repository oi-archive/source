
# Content

Liao is a power person, he is good at anything especially Search Algorithm, his motto is “There is nothing that cannot be solved by Search once, if there is, then Search twice!” So, for any NP-hard   problem, Liao can always get the best answer by Liao’s Search Algorithm. How powerful he is! . Everyone is confused with Liao’s talent, because they can’t believe that! People believe that Liao can solve NP-hard problem just depend on a secret item called 772002! 

Now people want to check whether Liao is really a talent person, they request Liao to solve an easy problem, but during the solving time, Liao must take 772002 to another person.

But Liao has his own pride, he doesn’t want to solve this easy problem and you are a fan of Liao, you want help Liao to solve this problem!

The problem is a hard Data Structure problem. You are given a positive integer sequence $a\_1$，$a\_2$，…，$a\_N$ of length $N$ , and there are three kinds of operations you need to complete.

* $Operation$ $1$ ：Change $a\_l，a\_{l+1}，…  a\_r$ to $y$.

* $Operation$ $2$ ：Change $a\_i$  into $Function( a_i , x  )$  ,for all $i ∈[ l ,r ]$，

* $Operation$ $3$ ：Query $ \sum_{i=l}^r a\_i$ 

* $Funcition( x ,y )$=$max$⁡$($ $1$ , $min$$⁡($  $\lfloor\frac{x}{2}\rfloor$ , $gcd(x,y)$  $)$  $)$

# Standard Input

The first line only contains an positive integer $T$ ( $T \leq 3$ ) , represents there are $T$ test cases.

For each test case:

The first line contains two positive integers $N$ and $Q$. $1 \leq N \leq 10^6  ,1 \leq Q \leq 10^6$

The next line contains $N$ positive integer  , represent $a_1，a_2，…，a_N$.  ( $1 \leq a_i \leq 10^6$ )

The next $Q$ lines, first contains an integer $x$, indicating the kind of operation.

If x is 1 , then three positive integers $l$，$r$，$y$ . It means you need to change $a\_l，a\_{l+1}，…  a\_r$ to $y$ . $1 \leq l \leq r \leq N ,1 \leq y \leq 10^6$.

If x is 2 , then three positive integers $l$，$r$，$x$ . It means you need to Change $a_i$  into $Function( a_i ,x  )$  ,for all $i ∈[ l ,r ]$. $1 \leq l \leq r \leq N ,1 \leq x \leq 10^6$

If x is 3 , then two positive integers $l$，$r$ . It means you need to output  $ \sum_{i=l}^r a\_i$ . $1 \leq l \leq r \leq N $

# Standard Output

For each operation 3, output one integer represent the answer.

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
5 4
1 2 3 4 5
3 1 5
1 1 3 4
2 1 4 4
3 1 4
</td><td>15
8
</td></tr></table>


# Constraints



# Note

For the Sample input

The first operation is query a[1] + a[2] + a[3] + a[4] + a[5] , so you need to output 15

After the second operation, the sequence is 4 4 4 4 5

After the third operation, the sequence is 2 2 2 2 5

The forth operation is query a[1] + a[2] + a[3] + a[4] , so you need to output 8

# Source


