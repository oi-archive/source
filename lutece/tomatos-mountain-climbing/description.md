
# Content

omato made an appointment with good friend yakexi to climb mountains, but on the day to climb, tomato got late because he was on a date with his girlfriend, yakexi waited for him for a long time but he didn’t show up, so yakexi just went climbing on his own……A few hours later, a problem comes up, yakexi is lost, so he calls tomato who is on a date, tomato has to end the date in tears for his friend. With a map in his hand, he comes to the foot of the mountain.

Let’s take a look at the map in tomato’s hand. The map is two-dimensional, and the gradient of every mountain is $45$ degrees. Now we know the horizontal distance between tomato and yakexi. In the map, the left most horizontal coordinate is $0$, and tomato always stands there while yakexi likes to stand as high as he can (take the picture below as example, the red line marks the horizontal coordinate of yakexi, then yakexi must be at the place with the blue mark)

Now would you please help tomato to find out which mountain yakexi is on? (if at one spot, there are $2$ mountains of the same height, then output the one with smaller horizontal coordinate. No two mountains share the same coordinate).

![title](/source/lutece/tomatos-mountain-climbing/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMjMzLzIwMTQwMzE4MTQwMzA4NjU1NC5naWY=.gif)

# Standard Input

The first line of the input is an integer $T$, which represents that there are $T$ test cases.

In the first line of every case is a integer $n(1 \leq n \leq 100000)$, representing the number of mountains on the map. In the $2 ~ n+1$ line, two integers in each line, describing the starting and finishing coordinate of every mountain. Then comes to queries, an integer $m$ in each line(m won’t be at the foot of a mountain or the
junction of two mountains), telling the distance between yakexi and tomato. When $m==-1$, query ends. Note: the serial number of mountains is the same as the order of data input, that is to say, the input of the data of the first mountain is seen as mountain $1$. All data varies within the int range.

# Standard Output

For every query, output an integer representing the serial number of the mountain yakexi is on. If there are no mountains, output `0`.

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
7
10 20
20 30
30 40
10 40
30 60
50 60
70 80
0
4
14
24
34
36
44
54
64
74
-1</td><td>0
0
4
4
4
5
5
5
0
7</td></tr></table>


# Constraints



# Note



# Source


