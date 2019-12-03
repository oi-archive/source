
# Content

Self-Adapt Test is a computer based test that is widely used such as `GRE`, `GMAT` and `LSAT`. The test continues according to how the test-takers performed, which means, different answer would lead different question ensue. School of Applied Mathematics is preparing a words guessing game in concept of the Self-Adapt Test. In the game, the player could choose any word as beginning to guess the meaning. If the guessing is correct, the system would lead to a certain word while lead to another if the answer is incorrect. For instance, the first word is `abandon`, if you succeed guessing it out, the next word is “abnormal”; if your guessing is wrong, the coming word is `abolish`. In one word, correct answer and incorrect answer would lead different series of words following. Each word to guess has its score, and you can get the score if you guess it correctly or else you would miss it. The game can be stop whenever you like. Now the problem is, in order to gain the total scores greater or equal to $T$ points, what’s the minimum number of words you must guess out correctly? 

Note that each word may appear only once in the game and there’s no cycle in guessing order.

# Standard Input

The first line of the input contains one integer $T$, which indicate the number of test cases.

In each of the test case, the first line contains two integers $N$ ($1 \leq N \leq 2000$) and $S$.($1 \leq S \leq 10^9$) $N$ is the total number of words and $S$ is points mentioned the description. Following N lines are in form of 
$wordA$ $P$ $wordB$ $wordC$.

which means, $P$ is the score for $wordA$,($1 \leq P \leq 10^6$) if you guess $wordA$ correctly, the next word to guess is $wordB$. Conversely, if you commit a incorrect guessing, the next word to guess is $wordC$. If the $wordB$ is `NULL`, means if you guess $wordA$ correctly, there is no next word, so dose the $wordC$. All the words’ length will less than $20$.

# Standard Output

One line for each test case contains only one number indicating the answer. The minimum number of words you must guess out correctly. If you can’t get the points $S$ no matter how you answer guess the words, output `impossible`！

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
3 10
lxhgww 4 hhb hysramp
hhb 6 NULL NULL
hysramp 4 NULL NULL</td><td>2</td></tr></table>


# Constraints



# Note



# Source


