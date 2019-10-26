
# Content

As you might haer breofe, Elnigsh words are eieasr to be riozceengd tahn you may thnik. Snfiteiicc rearsech prveod that for a spiifecc word, as long as we don’t caghne the fisrt and the last letetr, no mtaetr how we slhfufe the ohetr lretets in the word, it can sitll be rogzienced. Hree “Slhffue” just manes chningag tsohe lettres’ poiintoss rndoamly. 

Now you are given an article written by bearchild. All the words in the article are written in lowercase letters. The words are separated by a single whitespace. But evil zplinti1 has changed some letters in the article, bearchild needs to recover the words, he wonders the minimum steps to do so.

Here is what zplinti1 will do, first he will choose an interval $[L, R]$, and a lowercase letter $X$. Then he will change all the letters from the $L\_{th}$ to the $R\_{th}$ in the article, into the letter $X$. **Please note that in his operation, only letters will be counted, not for whitespaces**. For example, for the article `hello world`, the $1\_{st}$ letter will be `h`, the $5\_{th}$ letter will be `o`, **and the $6\_{th}$ letter will be `w`**. If zplinti1 chooses $L=3, R=8, X=$`a`, then the article will be `heaaa aaald`.

To answer bearchild’s question, you are also given two numbers $L$ and $R$. Suppose you can only change the letters from the $L\_{th}$ to the $R\_{th}$ in the article as you like, what is the minimum number of letters you need to change, in order to make **the most words** in the article to be recognized? **As before, whitespaces are not counted, and shouldn’t be changed.**

# Standard Input

The first line of input contains a number $T$, indicating the number of test cases. ($T\leq 20$)

For each test case, first will be an number $n$, indicating the number of words bearchild writes ($1\leq n\leq 100,000$). Then $n$ lines follow, each with a string $s$, it is the each word bearchild writes. The total length of the words will not exceed $100,000$, all the words contains lowercase letters only.

Then a number $q$ comes, it is the number of operations ($q\leq 100,000$) . For each operation, if it is a changing operation, it will contain $4$ integers, the first integer will be $1$, then three numbers $L$, $R$ and a letter $X$, which means zplinti1 will change all the letters from $L\_{th}$ to the $R\_{th}$ to letter $X$.

If it is a query operation, it will contain $3$ integers, the first integer will be $2$, then two numbers $L$ and $R$ will follow, as described in the description.
($1\leq L\leq R\leq n$, $X$ will be a lowercase letter)

# Standard Output

For each case, output `Case #i: ` first. ($i$ is the number of the test case, from $1$ to $T$). Then for each query operation, output the answer in the same line, separated by a single whitespace.

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
3
abc
ba
bca
7
2 1 8
1 2 6 c
2 1 8
2 3 6
1 4 7 b
2 1 8
2 5 6</td><td>Case #1: 0 4 3 3 1</td></tr></table>


# Constraints



# Note

If you do have difficulty reading the first paragraph, the original words are as follows:

*As you might hear before, English words are easier to be recognized than you may think. Scientific research proved that for a specific word, as long as we don’t change the first and the last letter, no matter how we shuffle the other letters in the word, it can still be recognized. Here “shuffle” just means changing those letters’ positions randomly. *

# Source


