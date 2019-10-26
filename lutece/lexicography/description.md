
# Content

An anagram of a string is any string that can be formed using the same letters as the original. (We consider the original string an anagram of itself as well.) For example, the string ACM has the following 6 anagrams, as given in alphabetical order:

![title](/source/lutece/lexicography/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTA3OC8yMDE1MDQxODIzMjQ1MjMxMDE3LmpwZw==.jpg)

As another example, the string ICPC has the following 12 anagrams (in alphabetical order):

![title](/source/lutece/lexicography/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTA3OC8yMDE1MDQxODIzMjUwODg0NDE4LmpwZw==.jpg)

Given a string and a rank K, you are to determine the Kth such anagram according to alphabetical order.

# Standard Input

Each test case will be designated on a single line containing the original word followed by the desired rank K. Words will use uppercase letters (i.e., A through Z) and will have length at most 16. The value of K will be in the range from 1 to the number of distinct anagrams of the given word. A line of the form "# 0" designates the end of the input.

# Standard Output

For each test, display the Kth anagram of the original string.

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
<tr><td>ACM 5
ICPC 12
REGION 274
# 0</td><td>MAC
PICC
IGNORE</td></tr></table>


# Constraints



# Note

The value of K could be almost 245 in the largest tests, so you should use type long in Java, or type long long in C++ to store K.

# Source


