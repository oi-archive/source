
# Content

Many students won prizes in UESTC Annual Amateur Contest last year. Yangsir asked Loveqinqin to send prizes to the winners' dormitories. Poor Loveqinqin found that these dormitories were scattered on several different floors of the dorm building.

Loveqinqin drew the map of the dorm building as showed in the following picture. Rooms colored red contained winners. Loveqinqin can only go to upstairs throught the stairs at either end of each floor.  

![title](/source/lutece/easy-problem-1/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNTU5LzIwMTQwODI2MTMyOTQwMjYxMTguanBn.jpg)

Assume that it takes Loveqinqin one minute to walk from a room to a neighbour room. Going through the stairs from Floor $i$ to Floor $i + 1$ also takes one minute. Note that if a room is near to the stairs, the time Loveqinqin needs to walk between stairs and that room is one minute. 

Loveqinqin could start at either end of the Floor $1$ and would stop at either end of the topmost floor. Please find a route which takes the minimum minutes, through which Loveqinqin can send prizes to all winners.

# Standard Input

There are multiple test cases. The first line of the input will be an integer $T$ ($T \leq 100$) indicating the number of test cases.

For each test case, in the first line there are two numbers: $N$ $M$, indicating the number of floors ($1 \leq N \leq 100$) and the width of each floor ($1 \leq M \leq 100$). The following $N$ lines describe the distribution of the winners. The first line is about Floor $1$, the second line is about Floor $2$, ..., the last line is about Floor $N$. 

We use `*` to denote a room containing winners, `.` to denote other rooms, `s` to denote stairs. We guarantee that the width of each floor equals $M$. The two ends of each lines are the only places where `s` appears.

# Standard Output

For each test case, print `Case #t: ` first, in which $t$ is the number of the test case starting from $1$. Then output the minimum minutes.

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
1 4
s*.s
3 3
s.s
s*s
s.s
4 4
s*.s
s.*s
s..s
s*.s
4 6
s*...s
s..**s
s.*..s
s..*.s</td><td>Case #1: 2
Case #2: 4
Case #3: 11
Case #4: 20</td></tr></table>


# Constraints



# Note

In the first case, Loveqinqin has to return to one of the ends of the first floor.

**This is really an easy problem. Come on!!!**

# Source


