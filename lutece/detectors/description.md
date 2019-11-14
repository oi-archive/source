
# Content

In every classroom in UESTC, a lot of detectors was suspended from the ceiling above us (see in the picture below).

Every detector is detecting whether someone is in the range of its detecting and to control the light besides it. We assume that one detector control only one light respectively and the range of detecting of every detector is a circle and its radius is $R$.

Now, there are some students in a classroom, and every light in the classroom is off. We assume that the floor and ceiling of the classroom are two $2$-Dimension space. Every student is described by a coordinate indicating the position on the floor, meanwhile every detector is described by a coordinate indicating the position on the ceiling. When a student share the same coordinate with a detector, this student is below the detector. Given the location of every student and every detector, please tell me how many lights will be on after detecting of those detectors.

![title](/source/lutece/detectors/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMzE2LzIwMTQwNDEwMTM1NTU0MzYzMTMuanBn.jpg)

# Standard Input

The first line of the input contains one integer $T$($T\leq 100$), which indicates the number of test cases.

In the every test case, the first line contains three numbers $M$,$N$ and $R$, where $M$ ($1\leq M\leq 100$) is a integer indicates the number of students, and $N$ ($1\leq N\leq 50$) is a integer indicates the number of detectors in this classroom, and $R$ is a real number ($0<R\leq 40$) indicates the detected range of every detector. 

Following two lines, the first line contains $2\times M$ integers, indicate the coordinates of $M$ students $(x,y)$.The second line contains $2\times N$ integers, indicate the coordinates of $N$ detectors $(X,Y)$. ($0\leq x,y,X,Y\leq 100$)

# Standard Output

For each test case, output one line. First ,output `Case #C: `, where $C$ is the number of test case, from $1$ to $T$. Then, output the number of lights that will be on after detecting of those detectors.

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
2 1 1.0
0 0 2 0
1 0
1 2 1.0
1 0
0 0 2 0</td><td>Case #1: 1
Case #2: 2</td></tr></table>


# Constraints



# Note



# Source


