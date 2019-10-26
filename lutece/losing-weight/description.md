
# Content

LSJ is trying hard to lose weight. But we all know,it's a long way to go, because LSJ just can't resist the temptation of the delicious food. As we all know, there are so many kinds of delicacies in the world. Suppose we now have m kinds of delicacies. Everyday, LSJ can get n dishes of delicacies, we call it a `LSJ sequence`: $d\_1,d\_2,d\_3\cdots d\_n$. And $d\_i=x$($1\leq i\leq n$ and $1\leq x\leq m$), specifying that the $i\_{th}$ dish is a $x$ delicacy. LSJ is very lazy and gluttonous. Everyday, he just chooses some dishes for his dinner, that is a sequence: $d\_{i\_1},d\_{i\_2},d\_{i\_3}\cdots d\_{i\_k}$, $1\leq i\_1<i\_2<\cdots <i\_k\leq n$, and then eats them all! So, LSJ is fatter and fatter day by day…

As a good friend of LSJ, LYM often feels anxious about LSJ's health. She has tried but failed so many times to persuade LSJ to eat less! Finally, LYM comes up with an idea, hoping that it will stop LSJ from overeating. LSJ and LYM make an agreement: LYM gives a sequence of length $k$: $f\_1,f\_2,\cdots f\_k$($1\leq k\leq n$ and $1\leq f\_k\leq m$),if LSJ could find:$d\_{i\_1}=f\_1, d\_{i\_2}=f\_2, d\_{i\_3}=f\_3\cdots d\_{i\_k}=f\_k$ ($1\leq i\_1<i\_2<\cdots <i\_k\leq n$) in `LSJ sequence`, LSJ could eat them all;But however,if LSJ couldn't find them, he can't eat anything thus to lose some weight, we call this $f\_1,f\_2,f\_3\cdots f\_k$ a `LYM sequence`.

Everyday in the morning, LYM can get `LSJ sequence`, but LYM is also so lazy,╮(╯▽╰)╭. She will pick up a number $k$ randomly, but she doesn't know if there exists a `LYM sequence` of length $k$. So she comes to you, the clever ACMer ,please give her the answer.

# Standard Input

In the first line of the input is an integer $T$, indicates the number of test cases. In each test case,the first line contains two integers, $n$($1\leq n\leq 1000000$), $m$($1\leq m\leq 1000$). The second line contains $n$ integers,indicating `LSJ sequence`.Then a line contains one integer $k$($1\leq k\leq n$).

# Standard Output

For each test case, output one line. First ,output `Case #C: `, where $C$ is the number of test case, from $1$ to $T$. Then, if LYM could find a `LYM sequence` length of $k$,output `Great! LSJ will lose some weight...` on a single line,otherwise just output `Horrible! LSJ will become fatter...`.

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
5 3
2 3 1 3 2
2
5 3
2 3 1 3 2
1</td><td>Case #1: Great! LSJ will lose some weight...
Case #2: Horrible! LSJ will become fatter...</td></tr></table>


# Constraints



# Note

1. In the first case,LYM can find a `LYM sequence`of length $2$: `1 1`
2. In the second case,there are three sequence length of $1$: `1,2,3`; But LSJ could find any of them in `LSJ sequence`,so there doesn't exist a `LYM sequence` length of $1$. 
3. In fact we all know,LSJ tries to lose weight by doing exercise rather than going on a diet.

# Source


