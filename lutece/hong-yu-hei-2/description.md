
# Content

Iahub and Sorin are the best competitive programmers in their town. However, they can't both qualify to an important contest. The selection will be made with the help of a single problem. Blatnatalag, a friend of Iahub, managed to get hold of the problem before the contest. Because he wants to make sure Iahub will be the one qualified, he tells Iahub the following task.

You're given an (1-based) array a with n elements. Let's define function $f(i,j) (1\le i,j\le n)$ as $(i-j)^2+g(i,j)^2$. Function g is calculated by the following pseudo-code:

```
int g(int i, int j) {
    int sum = 0;
    for (int k = min(i, j) + 1; k <= max(i, j); k = k + 1)
        sum = sum + a[k];
    return sum;
}
```

Find a value $min\_{i\ne j}f(i,j)$.

Probably by now Iahub already figured out the solution to this problem. Can you?

# Standard Input

The first line of input contains a single integer n. Next line contains n integers a[1], a[2], ..., a[n]

# Standard Output

Output a single integer — the value of $min\_{i\ne j} f(i,j)$.

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
1 0 0 -1</td><td>1</td></tr></table>


# Constraints



# Note

20% $1 \le n \le 1000$  
100% $1 \le n \le 100000$ $0\le |a_i| \le 10000$

# Source


