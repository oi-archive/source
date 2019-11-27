
# Content

朝为田舍郎，暮登天子堂。秋实大哥从小就怀抱有远大的理想，所以他开了一家快餐店。

秋实大哥根据菜的口感，给每一道菜一个唯一的$CID$，同时对于前来的客人，根据他们的口味喜好，秋实大哥会给每一个客人一个$PID$。

对于一个标号为$PID$的客人，他对标号为$CID$的菜的喜爱程度为$PID\wedge CID$($\wedge$表示按位异或），该值越大表示越喜欢。

秋实大哥实在太忙了，现在他需要你来帮忙照看一下他的店铺。

# Standard Input

第一行包含一个整数$n$，表示秋实大哥的餐馆内现在有$n$道菜。

接下来一行包含$n$个整数，分别表示每一道菜的$CID$。

接下来一行包含一个整数$m$，表示接下来发生了$m$件事。

接下来的$m$行，每一行为以下两种事件之一：
```
0 c : 表示秋实大哥最新研制出一道标号为c的菜
1 p : 表示来了一位标号为p的客人，请你在已有的菜中找出一道他最喜爱的菜
```
$1\leq n，m\leq 100000$，$0\leq PID，CID\leq 1000000$。

# Standard Output

对于每一个$1$  $p$事件输出一个整数，表示该客人最喜欢的菜的标号。

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
1
3
1 1
0 2
1 1</td><td>1
2</td></tr></table>


# Constraints



# Note



# Source


