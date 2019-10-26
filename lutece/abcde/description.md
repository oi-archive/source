
# Content

Binary-coded decimal (BCD) is a kind of binary encodings of decimal numbers where each decimal digit is represented by a fixed number of bits.
 
Awesome Binary-Coded Decimal (ABCD) is, under the above conditions, any number represented by corresponding binary value won't exceed $9$.

For example, in $\\{8,4,2,1\\}$ encoding, $1111$ is $15$, exceed $9$, so $\\{8,4,2,1\\}$ encoding is BCD but not ABCD. In $\\{2,4,2,1\\}$ encoding, any number represented by corresponding binary value won't exceed $9$, so $\\{2,4,2,1\\}$ encoding is ABCD.

![title](/source/lutece/abcde/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTMwNy8yMDE2MDQwMjEwMTU1NTMxODIuUE5H.PNG)

Now, let's talk about ABCDE (Awesome Binary-Coded Decimal Extension).

An n-ABCDE is such a encoding that can only represent $0$ to $n$, and every number from $0$ to $n$ can be represented by one or more binary values. So $\\{2,4,2,1\\}$ is a $9$-ABCDE and $\\{8,4,2,1\\}$ is a $15$-ABCDE as we mentioned above. In addition, $\\{16,8,4,2,1\\}$ is a $31$-ABCDE.

Two encoding will be considered different if they have different length, or they have different number set, with the number of occurrence of each number considered. More precisely, two different coding will have such a number that occur different times.

So, $\\{2,4,2,1\\}$ encoding is the same with the $\\{1,2,2,4\\}$ encoding, but it is different from $\\{2,4,4,1\\}$.

Now, given a number $n$, can you tell me how many different $n$-ABCDEs?

# Standard Input

There is an integer $T$ in the first line, indicates the number of test cases.

For each test, the only line contains a integer $n$.

$1\leq T\leq 5000$

$1\leq n \leq 5000$

# Standard Output

For each test, output an integer in one line, which is the number of different $n$-ABCDEs. As the answer may be too large, output it modulo $(10^9+7)$ (i.e. if the answer is $X$, you should output $X\ \%\ (10^9+7)$).

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
1
2
3
4
5</td><td>1
1
2
2
4</td></tr></table>


# Constraints



# Note

There are four $5$-ABCDEs: $\\{1,1,1,1,1\\}$, $\\{1,1,1,2\\}$, $\\{1,2,2\\}$, $\\{1,1,3\\}$.

# Source


