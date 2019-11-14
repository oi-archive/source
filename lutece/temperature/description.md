
# Content

Many people like summer as summer has a lot of advantages, but on the other hand, sometimes summer is also boring. As a student, Tom has complained with summer for many days. Because when having lunch, Tom has a habit of drinking soup. But the temperature of the soup is too high, so Tom need wait for a long time to drink. One day, Tom bought a bowl of soup again, he measured the temperature of the environment is $u\_a$ and the temperature of the soup is $u\_0$, after $t\_1$ minutes, he measured the soup again and the temperature is $u\_1$, but he did not want to measure the temperature all the time until he could drink it. Now Tom asks you for help. Could you help Tom calculate what the temperature of the soup is after $t\_2$ minutes and how long he need to wait for until the temperature of the soup becomes $u\_2$ according to the data which he had measured? You could assume that the temperature of the environment is invariable.

# Standard Input

The first line of the input contains a single integer $T$ ($1\leq T\leq 10$), the number of test cases. Then $T$ cases follow. 

The first line of each case contains $5$ integers, $u\_a$($0<u\_a<100$), $u\_0$($u\_a\leq u\_0\leq 100$), $u\_1$($u\_a\leq u\_1\leq u\_0$), $t\_1$($0<t\_1$), $n$($1\leq n\leq 10$), indicating the temperature of the environment $u\_a$, the original temperature of the soup $u\_0$ and the later temperature of the soup $u\_1$ after $t\_1$ minutes, $n$ indicates that there are $n$ options in the following. Each line of the $n$ lines contains two integers, $p$ and $s$, $p$ is the kind of the option and can only be $0$ or $1$. If $p$ is $0$, you should calculate the time Tom need to wait for until the temperature of the soup becomes $s$($u\_a\leq s\leq u\_0$)(it is guaranteed that temperature s is reachable), or you should calculate the temperature of the soup after $s$($0<s\leq 100$) minutes from original time $t=0$.

# Standard Output

For the $x\_{th}$ test case, first print `Case x:` on a single line.

Then for each option, print a line containing the answer round to two decimal numbers. Print a blank line after each test case.

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
24 100 90 10 2
0 80
1 20</td><td>Case 1:
21.65
81.32</td></tr></table>


# Constraints



# Note

According to Newton’s law of cooling, in a certain temperature range, the rate of change of an object’s temperature is proportional to the temperature difference of the object’s temperature and the environment temperature.

# Source


