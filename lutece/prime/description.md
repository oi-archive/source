
# Content

宿管有一套神奇的系统控制来控制寝室的灯的开关：

![title](/source/lutece/prime/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTg0Mi8yMDE4MDIyMTE1MDMyNTc0MDMucG5n.png)
共有N盏灯，标号为1到N，有M个标有不同质数的开关，开关可以控制所有标号为其标号倍数的灯，按一次开关，所有其控制的灭着的灯都点亮，所有其控制的亮着的灯将熄灭。现在，宿管可以无限的按所有开关，所有灯初始状态为熄灭，请求出最多能点亮几盏灯。

# Standard Input

输入有多组数据，第一行一个正整数T表示数据组数。
每组数据第一行两个整数N，M。
第二行M个不同的质数表示开关上的标号，保证所有标号<=N。

对于100%的数据，T<=10,N<=1000。 所有标号不相等，M≤N以内质数数。

# Standard Output

对于每组数据输出一行一个整数表示最多亮灯数。

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
10 2
2 5
21 4
2 3 5 7
100 1
5
100 3
3 19 7</td><td>5
11
20
42</td></tr></table>


# Constraints



# Note



# Source


