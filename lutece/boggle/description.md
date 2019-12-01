
# Content

I am sure, you are a big fan of the board game `Boggle`. 
Don't worry if you are not familiar with the rules, I will explain them to you. 
A Boggle is a $4\times 4$ grid of letters where your job is to find as many words as you can. 
If I play Boggle with (or against) my wife, she always wins, the loser(that's me) then always has to do all these little jobs like to take out the trash. 
So, please help me to win again.

Words in a Boggle can be constructed from adjacent letters (i.e. horizontally, vertically and diagonally), 
but the same dice may only be used once in a word. 
The words have to be listed in our dictionary to be valid. 

Words with $3$ or $4$ letters count $1$ point, words with $5$ letters $2$ points, $6$ letters $3$ points, 
$7$ letters $5$ points. $8$ letter words will give $11$ points. 
If you find more than one word (and I hope you do), points will be summed up to form your score.

# Standard Input

There is only one test case per file. The first line contains the number of words $w$ in the dictionary
($1 < w < 300000$). Then follow $w$ lines, each containing one word. 
Words consist of up to $8$ upper case letters (`A`-`Z`). After the dictionary specification, there is a blank line. 
Then follows the number
of Boggle boards $b$ in one line ($1 < b < 30$). Each boggle is given as a $4\times 4$ grid of upper case letters
in four lines. Boggles are separated by blank lines.

# Standard Output

For each boggle, print one line containing the maximal possible score, the longest word and number
of found words. Words that are twice (or more often) in one Boggle, only count once. If there is
more than one longest word, print the lexicographically smallest one. You may safely assume that
there is at least one valid word in each Boggle.

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
<tr><td>5
ICPC
ACM
CONTEST
GCPC
PROGRAMM

3
ACMA
APCA
TOGI
NEST

PCMM
RXAI
ORCN
GPCG

ICPC
GCPC
ICPC
GCPC</td><td>8 CONTEST 4
14 PROGRAMM 4
2 GCPC 2</td></tr></table>


# Constraints



# Note



# Source


