
# Content

Indira likes stars very much. In her childhood, the star tales were always huge attractions to her, with which she lived, dreamed and grew up. The little girl afterwards didn't become an astronomer though, Indira still loves to collect different stories of the constellations. 88 lovely constellations in the same sky, countless engaging tales at various touches.

When Indira wrote to her boyfriend at the end of each month, she would sometimes put down some of the stories. However, she didn't do so today. After writing for long time, she noticed the boy, who had an irrelevant taste, weren't too keen on these stories. Resigned though, Indira didn't want to give in. As a smart girl majoring in math, she realized that it would bean opportunity to punish the boy.

After reviewing the letter she had finished writing, Indira estimated each sentence with a degree of constellation.She only uses English letters(both uppercase and lowercase), blanks and some half-width characters(where newline characters and blanks may exist, but we can ignore it for simplicity). Each character can be mapped with a unique number:
* `[a...z] -> [0...25]`
* `[A...Z] -> [26...51]`
* `[,] -> [52]` (comma)
* `[.] -> [53]` (period)
* `[!] -> [54]` (exclamatory mark)
* `[?] -> [55]` (question mark)

After we ignore the redundant characters, each sentence can be transformed to a string without blanks, and each of its continuous substrings(where the empty substring is not included) can be seen as a $56$-base number. For instance, `I miss you` can be shorten into `Imissyou`, which contains substrings like (`s`)$\_{56}= (18)\_{10}$, (`is`)$\_{56}= (466)\_{10}$, (`missyou`)$\_{56}=(374677865764)\_{10}$,etc. When the number represented by a substring is divisible by 88(the number of constellations) under base $10$, Indira treats it as a substring of constellation.

The degree of constellation of a sentence is defined to be the number of substrings of constellation in this sentence. It is allowed to begin a substring with letter'a', and same substrings that exists at different positions counts as well.

Indira has got the answers, but she needs your help to check them. Given a letter by Indira, you’re now required to figure out the degree of constellation of each sentence inside.

# Standard Input

An integer $N$ will exist in the first line of input, indicating the number of sentences.

The following $N$ lines, each with a string, showthe sentences in Indira's letter.

# Standard Output

Output thedegree of constellationfor each sentence.

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
You had me at first sight.
I miss you.
Yours, Indira</td><td>4
0
4</td></tr></table>


# Constraints



# Note

The total length of all the sentences(including the blanks) will not exceed $4\times 10^6$. The C style input method is recommended for faster input.

# Source


