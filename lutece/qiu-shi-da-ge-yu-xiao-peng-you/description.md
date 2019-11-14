
# Content

秋实大哥以周济天下，锄强扶弱为己任，他常对天长叹：安得广厦千万间，大庇天下寒士俱欢颜。

所以今天他又在给一群小朋友发糖吃。

他让所有的小朋友排成一行，从左到右标号。在接下去的时间中，他有时会给一段区间的小朋友每人$v$颗糖，有时会问第$x$个小朋友手里有几颗糖。

这对于没上过学的孩子来说实在太困难了，所以你看不下去了，请你帮助小朋友回答所有的询问。

# Standard Input

第一行包含两个整数$n$，$m$，表示小朋友的个数，以及接下来你要处理的操作数。

接下来的$m$行，每一行表示下面两种操作之一：
```
0 l r v : 表示秋实大哥给[l,r]这个区间内的小朋友每人v颗糖

1 x : 表示秋实大哥想知道第x个小朋友手里现在有几颗糖
```
$1\leq m, v\leq 100000$，$1\leq l\leq r\leq n$，$1\leq x\leq n$，$1\leq n\leq 100000000$。

# Standard Output

对于每一个$1$  $x$操作，输出一个整数，表示第$x$个小朋友手里现在的糖果数目。

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
<tr><td>3 4
0 1 3 1
1 2
0 2 3 3
1 3</td><td>1
4</td></tr></table>


# Constraints



# Note



# Source


