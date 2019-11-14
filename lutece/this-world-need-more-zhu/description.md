
# Content

As we all know,Zhu is the most powerful man.He has the infinite power to protest the world.We need more men like Zhu!

In Duoladuo,this place is like a tree.There are n points and n-1 edges.And the root is 1.Each point can reach other points.Each point has a value a[i] named Zhu power.

Liao is a curious baby,he has m questions to ask Zhu.But now Zhu is busy,he wants you to help him answer Liao's questions.

Liao's question will be like"op u v a b".

if op is "1",the u is equal to v.Liao wants to know the GCD of the sum of numbers thats appears a times and the sum of numbers that appears b times in subtree u.

if op is "2",Liao wants to know the GCD of the sum of numbers thats appears a times and the sum of numbers that appears b times on the path from u to v.

GCD is greatest common divisor.

notice:we can know GCD(x,0) = x.

# Standard Input

In the first line contains a single positive integer T, indicating number of test case.

In the second line there are two numbers n,m.n is the size of Duoladuo.m is the number of Liao's questions.

The next line contains n integers A1, A2, ...AN, means the value of i point.

In the next n-1 line contains tow numbers u,v.It means there is a edge between point u and point v.


The next m lines will be the Liao's question: 

1 u v a b.

2 u v a b.

$1\le T\le 10,1\le n\le 100000,1\le m\le 100000,1\le op\le 2,1\le u,v\le n,1\le a,b\le n,1\le A[i] \le 1000000000$.

# Standard Output

For each case, output Case #i:. (ii is the number of the test case, from 1 to T). 

Then, you need to output the answer for every Liao's questions.

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
5 5
1 2 4 1 2
1 2
2 3
3 4
4 5
1 1 1 1 1
1 1 1 1 2
2 1 5 1 1
2 1 5 1 2
2 1 1 2 2
</td><td>Case #1:
4
1
4
1
0</td></tr></table>


# Constraints



# Note

The query1: gcd(4,4) = 4

The query2: gcd(4,1+2)=1

The query3: gcd(4,4) = 4

The query4: gcd(4,1+2) = 1

The query5: gcd(0,0) = 0

# Source


