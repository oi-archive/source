
# Content

A catenym is a pair of words separated by a period such that the last letter of the first word is the same as the first letter of the second. For example, the following are catenyms: 
```
dog.gopher
gopher.rat
rat.tiger
aloha.aloha
arachnid.dog
```
A compound catenym is a sequence of three or more words separated by periods such that each adjacent pair of words forms a catenym. For example, 
```
aloha.aloha.arachnid.dog.gopher.rat.tiger 
```
Given a dictionary of lower case words, you are to find a compound catenym that contains each of the words exactly once.

# Standard Input

The first line of standard input contains $t$, the number of test cases. Each test case begins with $3 \leq n \leq 1000$ - the number of words in the dictionary. $n$ distinct dictionary words follow; each word is a string of between $1$ and $20$ lowercase letters on a line by itself.

# Standard Output

For each test case, output a line giving the lexicographically least compound catenym that contains each dictionary word exactly once. 

Output `***` if there is no solution.

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
6
aloha
arachnid
dog
gopher
rat
tiger
3
oak
maple
elm</td><td>aloha.arachnid.dog.gopher.rat.tiger
***</td></tr></table>


# Constraints



# Note



# Source


