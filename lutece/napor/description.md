
# Content

Little Mirko wasn’t paying attention in math class, so the teacher has decided to give him a tedious 
assignment to solve during the weekend. 

The teacher has given him a text consisting of N lines, containing only digits and lower case letters of 
the English alphabet. Mirko has to find all numbers in the text and print them out in a **nondecreasing 
sequence**. He also has to **omit** any **leading zeros** that the numbers may have in the text. 

The numbers can be uniquely determined by scanning through the text and always taking the largest 
possible number, i.e. delimited only by letters or line beginnings/ends. For example, the solution of 
`01a2b3456cde478` is $1$, $2$, $478$, $3456$. 

Since Mirko is as slow as the snail from the previous task, he has asked you to write him a program to
quickly solve his assignment, so that he can go play with Slavko as soon as possible.

# Standard Input

The first line of input contains the integer $N$ ($1 \leq N \leq 100$), the number of lines of the text. 

The next $N$ lines contain the text, consisting exclusively of lowercase English letters and decimal digits. 
Each line of the text is at most $100$ characters long.

# Standard Output

The output must contain $M$ lines, where $M$ is the number of numbers found in the provided text. Each 
line must contain a single number from the text. The numbers must be arranged in a nondecreasing 
sequence. 

**Note**: The test data will ensure that $M$ will never exceed $500$.

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
lo3za4 
01</td><td>1 
3 
4</td></tr><tr><td>4 
43silos0 
zita002 
le2sim 
231233</td><td>0 
2 
2 
43 
231233</td></tr><tr><td>4 
01bond 
02james007 
03bond 
04austinpowers000</td><td>0 
1 
2 
3 
4 
7</td></tr></table>


# Constraints



# Note



# Source


