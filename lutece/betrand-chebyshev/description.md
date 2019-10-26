
# Content

Zplinti1 has recently learn `rand()` function in C/C++. He is so excited, since he finds using that function is easy and convenient. For example, if you want to generate a integer randomly from $0$ to $9$, he can simply write `rand()%10`.

However, `rand()` function can’t generate a number which is too large. The maximum number is $32767$, by default. Zplinti1 is not satisfied with that!

Clever as he is, he quickly gets a way: he can multiply some `rand()` functions together, to get a much larger number. If he write `( rand()%10000 ) * ( rand()%10000 )`, he can get a number as large as $9999\times 9999$.

Unfortunately, one of his friends, bearchild, soon finds the problem: some numbers might not be got using his way described above. Zplinti1 wants to find the minimum number that cannot be got.

More precisely, we have $n$ numbers, from $a\_0$ to $a\_{n-1}$. And for number $a\_i$, it is a value randomly chosen from $0$ to $b\_i$, then we set $X$ as the product of those $n$ numbers, what is the minimum positive number that cannot be the value of $X$? If there is no problem with the new function, output `Good Function`.

# Standard Input

The first line of input contains a number $T$, indicating the number of cases. ($T\leq 1000$)

For each case, the first line is a number $n$ ($1\leq n \leq 10,000$). The second line contains $n$ numbers from $b\_0$ to $b\_{n-1}$, all those numbers are positive numbers less than $1,000,000,000$.

# Standard Output

For each case, output `Case #i: ` first. ($i$ is the number of the test case, from $1$ to $T$). Then output the minimum value that $X$ cannot be, or `Good Function`, as described above.

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
2
2 3
2
4 5
3
4 7 11
3
1 1 2</td><td>Case #1: 5
Case #2: 7
Case #3: 13
Case #4: Good Function</td></tr></table>


# Constraints



# Note

As you can see, the maximum number zplinti1 can get is the product of $b\_0$ to $b\_{n-1}$, when each `rand()` function get its largest number. If the answer you get is larger than this maximum, you have to output `Good Function`, and it is the only case you need to output that.

# Source


