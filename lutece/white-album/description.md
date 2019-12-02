
# Content

春希在乐警官的帮助下，迅速破解了方师傅留下的纸条，知道了冬马的所在地。

狡猾的方师傅并没有打算简单得释放冬马。

方师傅的基地有$n$个房间（标号$1$~$n$），经过乐警官的调查，只有从其中的$k$个特定房间才可以离开基地。但是乐警官并不知道冬马被关在哪个房间了。为了保证可以营救冬马，乐警官决定在房间之间挖密道，使得每一个房间都至少能到达一个安全的房间。但是由于方师傅巧妙的设计，并不是每个房间间都能挖密道，并且挖一条密道需要一定的时间。

春希想知道怎么才能在最快的时间内把密道挖好。

# Standard Input

第一行两个整型$n$，$m$，$k$，分别表示房间数，能挖的密道数和特定房间数。 $(1 \leq n \leq 1000,0 \leq m \leq n \times \frac{n-1}{2},1 \leq k \leq n)$

第二行$k$个数，分别为特定房间的编号。

接下来$m$行，每行三个整数$a_i，b_i，c_i$，表示$a_i$号房间和$b_i$号房间能挖密道，耗费的时间为$c_i。(1 \leq a_i,b_i \leq n,c_i \leq 1000000)$

# Standard Output

一个整数，表示最小时间花费。

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
<tr><td>9 14 3
1 8 9
1 2 5
1 3 2
2 3 5
2 4 4
2 5 7
3 5 4
4 5 5
4 6 6
4 7 4
5 7 10
6 7 11
6 8 3
7 8 8
7 9 10</td><td>22</td></tr><tr><td>4 5 1
1
1 2 5
1 3 5
1 4 5
2 3 10
3 4 10</td><td>15</td></tr></table>


# Constraints



# Note



# Source


