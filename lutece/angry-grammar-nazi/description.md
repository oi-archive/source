
# Content

Your friend is what we can call a grammar nazi. He spends a lot of time on popular internet discussion forums. Unfortunately, he has a bad temper and loses his mind whenever someone incorrigibly befouls the English language, with unrelenting violations of grammatical and ortographic rules.

In order to avoid smashed keyboards,monitors and coffee-cup holders, you advice your friend to momentarily stop reading and count to ten each time he becomes angry, instead of smashing something.

Your friend becomes angry whenever he reads the following words or sequences of words:
* "u", "ur" instead or "you", "your".
* "would of", "should of" instead of "would have", "should have".
* "lol" instead of "haha". In fact he becomes angry even when a word contains "lol"as a substring. (Even if a word contains multiple occurrences of "lol", such as the word "lolol", he will only become angry once.)

You decide to write a computer program that reads sentences one by one, and for each sentence calculates how many times your friend will have uttered a number after reading said sentence. Your friend does not read out loud, so numbers that are part of the input-sentences should not be counted.

# Standard Input

The first line of the input consists of a single integer $T$, the number of test cases. The following $T$ lines each contain one sentence; that is, one or more words separated by space.

$0 < T \leq 50$

A sentence consists of at most $100$ characters, including spaces.

A word consists only of lower case letters between `a` and `z`, inclusively.

Two adjacent words are separated by exactly one space, and a sentence never has leading or trailing spaces.

# Standard Output

For each test case, output how many times your friend have said a number after reading the sentence.

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
u haz lolcats
my car is green
i have a lollipop
u should of lold</td><td>20
0
10
30</td></tr></table>


# Constraints



# Note



# Source


