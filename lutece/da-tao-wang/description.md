
# Content

love8909遇到危险了！！！他被困在一个迷宫中，彷徨而无助。现在需要你来帮助他走出困境。他只能记住指定长度的指令(指令的长度由MinLen和MaxLen限定)，并循环执行，而且他只会向下或向右（很奇怪吧^_^）。他在地图的左上角，你需要告诉他一个运动序列，即向下`D`或向右`R`，使他能够成功走出这个图且不碰到陷阱。
如果还不明白，可以参看图片。图片1，2对应样例的第1组，图片3对应样例的第2组。

![.*](/source/lutece/da-tao-wang/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTUxLzIwMTQwMjAyMjEzNzM0MjU2MTQuanBn.jpg)

![.*](/source/lutece/da-tao-wang/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTUxLzIwMTQwMjAyMjEzNzQxNzY1MTUuanBn.jpg)

![.*](/source/lutece/da-tao-wang/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTUxLzIwMTQwMjAyMjEzNzQ5MjE0MTYuanBn.jpg)

# Standard Input

第一行为$1$个整数$T$，表示有$T$组测试数据

第二行为$4$个整数$Height$, $Width$, $MinLen$, $MaxLen$，分别表示地图的高，宽，命令序列的最小和最大长度。$3\leq Height, Width\leq 60$, $2\leq MinLen\leq MaxLen \leq 35$

第三行至第$Height+2$行为地图信息。其中`.`表示空地，`X`表示陷阱。

# Standard Output

只有一行，为命令序列（只含`D`, `R`）。

注意：如果有多解，输入命令长度最短的；依然有多解，输出字典序最小的（`D`的字典序比`R`小），数据保证一定存在一组解。

字典序：字符串从前往后依次比较，第一个字符不同的位置，字符较小的字符串字典序较小，详情参见字典。

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
3 3 2 2
.X.
...
X..
5 5 2 3
..X.X
....X
.....
.XX..
XX..X</td><td>DR
DRR</td></tr></table>


# Constraints



# Note



# Source


