
# Content

After Ender had defeated the evil alien which is called `bugger` by us human, his life become boring. Having played dota for $42$ weeks, he finally realized that the essence of the life is boring. 

![.*](/source/lutece/ender-s-game/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTc1LzIwMTQwMjAyMjM0NzUzNzMxMzUucG5n.png)

In order to let the life not so boring any more and make our society harmonious, our wise commander came up with a boring game. Ender caught $n$ buggers in the cage. The $i\_{th}$ bugger has two kinds of fight abilities. The attack ability $A\_i$ and the defend ability $D\_i$. Our cruel Ender wants to let every bugger fight with each other in the cage. Every two buggers in this cage must exactly fight once with each other. 

Easily, you can realize that the total number of fights would be exactly $\frac{n\times(n-1)}{2}$. When bugger $i$ fight with bugger $j$, our heart-twisted Ender will gain some happy points whose value is $H\_{ij}$ ( $i < j$ ). The happy point can be calculated by the following equation:

$$H\_{ij}=Max(A\_i-A\_j, D\_i-D_j)-Min(A\_i-A\_j, D\_i-D\_j), ( i < j )$$

Ender is eagerly want to know the total happy point he can get. As a subaltern of Ender, you must help Ender to calculator it, or you will be fired. You know in this period of economic crisis, a job is so hard to get.So try your best to help Ender.

# Standard Input

The first line of the inputs is $T$(no more than $10$), which stands for the number of test cases you need to solve, for each case you must solve it independently and print the answer as the requests. 

After $T$, the inputs will be each test case. The first line of each case will be $N$, representing for the number of buggers in the cage（$0 < N\leq 200000$). There will be $N$ lines following. The $i+1\_{th}$ line of the input will has two integer $A\_i$ and $D\_i$, represent the $i\_{th}$ bugger's attackability and defend ability. All the values appeared in the input are $32$-bit signed integer.

# Standard Output

Please output the answer for all test cases.

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
3
2 1
1 2
5 3
1
10 1</td><td>6
0</td></tr></table>


# Constraints



# Note

The sum of the happy points may be huge and you’d better use `long long` instead of `int`. Honor to the great science fiction Ender’s game by Orson Scott Card.

# Source


