
# Content

JiangAn's bathroom is divided into $N$ ($1\leq N\leq 50$) rooms labeled from $1$ to $N$. And there are some compartments in each room. If the compartment is available, it will be labeled with a number. Otherwise it will be labeled with `XX`. Each number of the compartment in one room is uniqueness.

The compartments in one room are arranged only in the shape of `U` (Such as the room $1$ and room $2$ in sample) or `II` (for example the sample of room $3$). If a student wants to have a shower, he should swipe his card on the machine firstly. In order to facilitate your understanding, we would name this machine with A. The machine A will assign an available compartment for him randomly. And this compartment is marked as in use at the same time.

When he finished his shower, he should swipe his card again on machine B. The machine B will calculate the cost and this compartment is marked as available again. As we know, many people don't like the compartments in corners, (Such as No.$01$, No.$05$, No.$08$ and No.$12$ compartments in room $1$, No.$15$, No.$17$, No.$20$ compartments in room $2$, And No.$01$, No.$05$, No.$06$, No.$10$ compartments in room $3$) At least I don't. zsasuke doesn't like the compartments in 
corners too. And he also doesn't like the compartment whose 
the room number connecting the compartment number is a prime number. 
(Such as room $1$ No.$01$ compartment, $101$ is a prime number).

Every time zsasuke is assigned to a compartment he doesn't like, he will immediately swipe his card on machine B to cancel this allocation, then swipe his card on machine A again. He won't stop this until he is assigned to a satisfactory compartment. (What a selfish person! Students in queue after him must curse him...) But sometimes, it may take many times to get a satisfactory compartment. Recently, our clever zsasuke think of a new idea that he can take many cards to the bathroom. (We assumed that he borrowed enough cards from his schoolmates, what a selfish person!) If his first card is assigned to a unsatisfactory compartment, he will immediately swipe the second card on machine A to get a new compartment (Do not need to cancel previous assigning), until the compartment he got is satisfactory.

zsasuke wants to know how much the new method better than the old one. So can you do him a favor, What is expecting number of times zsasuke needs to swiping his card(s) on machine A to get a satisfactory compartment for the two methods respectively?

# Standard Input

The first line of the input is an integer $T$ which stands for the number of test cases.

For each test case, the first line is an integer $N$ and $N$ lines follow which stands for the information of each room.

For each room, the first line is an integer $L$, indicating that this room has $L$ lines. The following $L$ lines stand for the map of the room and each line has at most $600$ chars. We guarantee the arrangement of compartments in the room strictly correspond with the description above.

The shape of every compartment is strictly as follows:
```
----
|##|
----
```

The `##` is either a number of exactly $2$ digits (leading zeros may 
appeared) or `XX`. Otherwise it is not a compartment.
Here is sad news that zsasuke's teammate, onmylove has used this 
map paper as scratch paper. So on the map there may appear some other
redundant chars. But fortunately, the redundant chars will not 
cover the origin compartments, or make up any new compartments.
After the description of room there is a line contains an integer
M which stands for how many people taking a shower when zsasuke come
to the bathroom. And following $M$ lines, each line contains two integers $X$ and $Y$,
which stands for the No.$Y$ compartment in room $X$ is used now.

# Standard Output

For each test case, output one line contain two floating-point numbers 
(rounded to $6$ digits after decimal point), which stands for the expecting
number of times zsasuke needs for old and new methods respectively, separated by a space.
If there is no usable compartment, output a line with `No available room!`.

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
3
11
----     ----
|01|     |12|
----     ----
|02|     |11|
----     ----
|03|     |10|
----     ----
|04|     |09|
-------------
|05|06|07|08|
-------------
9
----  ----
|XX|  |20|
----  ----
|13|  |19|
----  ----
|14|  |18|
----------
|15|16|17|
----------
11
----  ---- :)
|01|  |10| Orz
----01---- =.=||
|02|==|09|
----- ---- ---
|03|04|08| |11|
---------- ---
|04|  |07|
----  ----
|05|  |06|
----  ----
5
1 2
1 3
2 13
3 02
3 09</td><td>2.272727 2.166667</td></tr></table>


# Constraints



# Note



# Source


