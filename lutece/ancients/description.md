
# Content

In the ancient time, there was a kingdom called ACM ruled by Lxhgww. Lxhgww was such a great king who led his people to a prosperous time.

According to historical records, Lxhgww invited Haibo, the greatest sage at that time, to help build up the transport network of ACM. Haibo built up a tree-like network connecting all the cities, in which all the roads are one-way, and the capital was the root node. The network was so well-built that there was exactly one path from the capital to each other city.

At that time, Kingdom ACM was heavily threatened by Kingdom MCM. In order to protect his people, Lxhgww sent soldiers to cities. Thanks to historians, we can find all the commands given by Lxhgww. The command has two values, $X$ and $K$. It means sending $K$ soldiers to City $X$, sending $K + 1$ soldiers to sons of City $X$, sending $K + 2$ soldiers to sons of sons of City $X$ and so on. Sons of a city are the cities where people can get by passing through roads starting from that city. It is easy to see that each city has at most one father. Initially there are no soldiers in any city.

![title](/source/lutece/ancients/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNTY3LzIwMTQwODI3MTgzNjEyNDA5MTkuanBn.jpg)

The only missing information about Kingdom ACM is the capital place. We have discovered all the roads built without any direction information and all commands given by Lxhgww. Moreover, we believe that the capital guaranteed that the number of soldiers sent by Lxhgww is minimum, that is to say, if Lxhgww chose another city to be the capital, soldiers sent would be no less than those under the previous capital. Please find the potential capital city.

# Standard Input

The first line of the input will be an integer $T$ ($T \leq 20$) indicating the number of cases.

For each case, the first line contains two integers: $N$ $C$, representing the number of cities in Kingdom ACM and number of commands given by Lxhgww. 

Then $N - 1$ lines follow, each in the format of `X Y` gives a road connecting City $X$ and City $Y$. **Note that we do not know the direction of this road.**

The following $C$ lines list Lxhgww's commands in the format of `X K`. A city may appear several times in the commands.

$1 \leq N \leq 30000$, $0 \leq C \leq 100000$, $0 \leq K \leq 1000$.

$1 \leq X , Y \leq N$, $X \neq Y$.

# Standard Output

For each case, you need to output two lines. Print `Case #k: S` first in a single line, in which $k$ represents the case number which starts from $1$, $S$ is the minimum number of soldiers sent. Then output all potential capital cities in the following line in **ascending order**. Separate the cities by a single space.

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
<tr><td>1
5 2
1 5
1 3
1 2
2 4
1 1
3 1</td><td>Case #1: 6
2 4</td></tr></table>


# Constraints



# Note

**Huge input/output. Please use `scanf/printf` for `C/C++`.**

For the first case, the numbers of soldiers sent for each city to be capital are $11, 6, 21, 6, 9$.

# Source


