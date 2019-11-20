
# Content

A company wants to hire a new employee. The selection process consists of several attention tests, one of them consists in: each candidate must type each character he sees in a flashing screen, using a given keyboard. You are asked to write down a program to score the candidates, given the original sequence of characters, and what the candidate actually typed. Scoring is based on the kind of actions the candidate may perform. For each character flashing in the screen, she may only:
1. Correctly type the character;
2. Omit the character;
3. By mistake, type a different character.

The score or penalty given to each action depends on the keyboard layout considered. The keyboard is a matrix of $n$ rows and $m$ columns.

The distance between the characters at coordinates $(i\_1,j\_1)$ and $(i\_2,j\_2)$ is given by the maximum of $|i\_1- i\_2|$ and $|j\_1-j\_2|$. For example, in the keyboard below ($3$ rows by $5$ columns), the distance between the character `a`, at $(2,1)$, and the character `h` at $(3,5)$ is $4$, and the distance between the character `o` and `h` is $2$. In this example, the largest distance between any two characters is $4$. For any keyboard the largest distance between any two characters is conventionally referred to by $TOP$.

 ![title](/source/lutece/transcript/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNDMzLzIwMTQwODE0MjAwMzQ4MzYwMTMuanBn.jpg)

The score given to the correct transcription of one character is $TOP+1$. The penalty given for the omission of one character (action $2$) is $TOP+1$. The score given for changing a character for another (action $3$) is $TOP+1$ minus the distance between the two characters involved in the mistake. For example, considering the keyboard shown above, the following action scores apply: Score for the correct transcript of one character: $5$; Penalty for the omission of one character: $5$; Score for changing character `o` to character `h`: $5-2=3$.

A scoring of a test is the sum of the scores given to each character typed minus the sum of the penalties for each character omitted. Since the scoring is only done after the test finishes, it is not possible to be sure about when specific actions were realized (e.g, did the candidate skip a character, or mistyped it?). To avoid complaints, the final score given is the highest possible value for scoring the candidate, according to the rules explained above. For example, if the text to transcribe is `time` and the candidate types `yme`, we may score it in several ways:
* To omit `t`, change `i` for `y` and correctly transcribe `m` and `e`;
* To change `t` for `y`, omit `i` and correctly transcribe `m` and `e`;
* To change `t` for `y`, change `i` for `m`, omit `m` and correctly transcribe `e`;
* To change `t` for `y`, change `i` for `m`, change `m` for `e` and omit `e`.

Each one of these possibilities has one score associated ($9, 8, 7$ and $3$ points, respectively). Thus, the candidate’s final score is $9$ points. Write a program that, considering the shape of a keyboard, the text to be transcribed by the candidate, and the actual transcript produced by the candidate returns the final score of the candidate.

# Standard Input

The input file contains several test cases, each of them as described below. The first line contains an integer $N$, stating the number of rows in the keyboard. The next $N$ lines, all with the same length, contain a string with the sequence of characters in the corresponding keyboard row. The keyboard will not have more than $20$ rows and $30$ columns. Then, the next two lines contain the text to be transcribed by the candidate, and the text typed by the candidate. These texts will be no longer than $500$ characters each.

# Standard Output

For each test case, a single line containing an integer stating the final score of the candidate.

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
egyim
anows
uflth
time
yme</td><td>9</td></tr></table>


# Constraints



# Note



# Source


