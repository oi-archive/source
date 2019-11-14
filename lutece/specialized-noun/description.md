
# Content

You have a pile of articles in hand, and you find there’re many specialized nouns in them. To find them manually takes too much work.So you use the two rules below:

specialized noun must occured as a whole in the articles

it must occur at least $N$ times

Use these two rules to filter words, you can find the probability to be a specialized noun is much bigger. You call it a `candidate for specialized noun`.

Now a word is given to you, your task is to judge if it is a candidate for specialized noun.

To simplify the problem, a single character is represented in the form of integer $1-10000$, a word is formed by one or multiple characters.

# Standard Input

The beginning is an integer $T$, which is the number of test case.each presents in the format below:

The first line contains $3$ integers $N$,$P$,$Q$. $N$ represented the minimum frequency to be recognized as candidate for specialized noun; $P$ means number of lines of the articals, $Q$ means number of words to be judged.

Then $P$ lines follow, each line starts with an integer $X$, indicating the number of characters of this line of article, then $X$ integers representing specific characters.

Finally $Q$ lines, each line starts with an integer $Y$, indicating the number of characters of this word to be judged, then $Y$ integers representing specific characters.

$N \leq 10000，P \leq 100，X \leq 100，Q \leq 100，Y \leq 100$

# Standard Output

For each word to be judged, output a line containes either `Yes` or `No`, indicating if the word is candidate for specialized noun. 

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
2 2 3
3 1 2 1
2 2 1
3 1 2 1
2 1 2
2 2 1
2 1 1
5 1 2 1 2 1
3 1 2 1
2 5 5
12 1 2 3 11 12 13 4 5 6 14 15 16
7 4 5 6 7 1 2 3
6 14 15 16 11 12 13
14 11 12 13 14 1 2 3 1 2 3 11 12 13 14
13 4 5 6 14 15 16 11 12 13 11 12 13 14
3 1 2 3
4 1 1 2 3
5 11 12 13 14 1
3 14 15 16
6 4 5 6 14 15 16</td><td>No
No
Yes
Yes
Yes
No
No
Yes
Yes</td></tr></table>


# Constraints



# Note



# Source


