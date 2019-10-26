
# Content

Ye.Dong likes playing flying chess very much, so he wants Ye.Han to play with him.

To simplify the problem, we define the rules as follows:

1. Ye.Dong and Ye.Han both have two plane chesses. All chesses are at point $0$ at the very begining. When two planes of a person both reach the destination(point $N$), he'll win the game.
2. If one of the planes of a person has not reach the destination(point $N$), the another plane of his cannot take off.
3. Two people throw a dice by turns, and the number($1$~$6$) is the steps that the taken-off plane will fly forwards.
4. The plane, which has not taken off(in other words, at the point $0$), can take off(fly from point $0$ to point $1$) only if he throws a dice and get the number $6$.
5. If a plane of person A will fly to point $x(1 < x < N)$, and there is already one plane belonging to person B, the personA's plane will reach the point x, and the personB's will return to point 0.
6. We assume that $N = 5$ and you are at the point $3$ now, then you will reach the destination(point $N$) if you get the number $2, 3, 4, 5, 6$ after throwing a dice.
7. Ye.Dong takes the first turn.

Now you know the number they'll get after throwing a dice. Your task is to find out who will win the game.

# Standard Input

The first line contains only one integer, $T$, which is the number of test cases.

For each case:

The first line contains two integers, $N$ and $M (1 \leq N, M \leq 10000)$. $N$ is the number of the destination point. They both will throw a dice for $M$ times.

The following two lines both contain $M$ integers, representing the number of dice of Ye.Dong and Ye.Han will get.

# Standard Output

For each case:

Print `Ye.Dong` if Ye.Dong wins; print `Ye.Han` if Ye.Han wins.

If no one wins after $M$ turns, print `Tie.`

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
<tr><td>3
5 5
6 4 6 2 2 
6 4 6 4 6
5 5
6 4 6 2 2 
6 4 6 2 2
5 2
6 1
1 1</td><td>Ye.Han
Ye.Han
Tie.</td></tr></table>


# Constraints



# Note

For Sample $1$:
1. Ye.Dong:	plane$1$ -> $1$
2. Ye.Han:	plane$1$ -> $1$
3. Ye.Dong:	plane$1$ -> $5$ (destination point $N$)
4. Ye.Han:	plane$1$ -> $5$ (destination point $N$)
5. Ye.Dong:	plane$2$ -> $1$
6. Ye.Han:	plane$2$ -> $1$
7. Ye.Dong:	plane$2$ -> $3$
8. Ye.Han:	plane$2$ -> $5$ (destination point $N$)
Ye.Han wins
(There are still some numbers of dice. You can just assume that they are killing the time. = =!)

For Sample $2$:
1. Ye.Dong:	plane$1$ -> $1$
2. Ye.Han:	plane$1$ -> $1$
3. Ye.Dong:	plane$1$ -> $5$ (destination point $N$)
4. Ye.Han:	plane$1$ -> $5$ (destination point $N$)
5. Ye.Dong:	plane$2$ -> $1$
6. Ye.Han:	plane$2$ -> $1$
7. Ye.Dong:	plane$2$ -> $3$
8. Ye.Han:	plane$2$ -> $3$, and then Ye.Dong's plane$2$ will return back to point $0$
9. Ye.Dong:	the number is not $6$, so the plane$2$ cannot take off
10. Ye.Han:	plane$2$ -> $5$ (destination point $N$)
Ye.Han wins

# Source


