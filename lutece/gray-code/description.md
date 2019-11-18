
# Content

The reflected binary code, also known as Gray code after Frank Gray, is a binary numeral system where two successive values differ in only onebit (binary digit). The reflected binary code was originally designed to prevent spurious output from electromechanical switches. Today, Gray codes are widely used to facilitate error correction in digital communications such as digital terrestrial television and some cable TV systems.

![title](/source/lutece/gray-code/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTE4Ni8yMDE1MDgwNDIwMTgzODc4NDIucG5n.png)

Now , you are given a binary number of length n including ‘0’ , ’1’ and ‘?’(? means that you can use either 0 or 1 to fill this position) and n integers(a1,a2,….,an) . A certain binary number corresponds to a gray code only. If the ith bit of this gray code is 1,you can get the point ai.
Can you tell me how many points you can get at most?

For instance, the binary number “00?0” may be “0000” or “0010”,and the corresponding gray code are “0000” or “0011”.You can choose “0000” getting nothing or “0011” getting the point a3 and a4.

# Standard Input

The first line of the input contains the number of test cases T.

Each test case begins with string with ‘0’,’1’ and ‘?’.

The next line contains  n (1<=n<=200000) integers (n is the length of the string).

a1 a2 a3 … an (1<=ai<=1000)

# Standard Output

For each test case, output “Case #x: ans”, in which x is the case number counted from one,’ans’ is the points you can get at most

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
00?0
1 2 4 8
????
1 2 4 8
</td><td>Case #1: 12
Case #2: 15</td></tr></table>


# Constraints



# Note

https://en.wikipedia.org/wiki/Gray_code

http://baike.baidu.com/view/358724.htm

# Source


