
# Content

在`zh`和`hqf`讲完了dp专题之后，两人准备了一个计划：毁灭UESTC清水河校区东湖！  
为了完成这个必将记录史册的计划，`zh`和`hqf`在校外挖了另一个湖：灭湖。而毁灭东湖的方式便是使得东湖中的水全部消失。他们挖了很多水渠来形成一个排水系统，使得东湖中的水能够全部引到灭湖之中，并且他们可以控制流入水渠的水流量。`zh`和`hqf`知道每一条水渠每分钟可以流过的水量和排水系统的准确布局（起点为东湖而终点为灭湖的一张网）。根据这些信息，计算从东湖排水到灭湖的最大流量，使得他们俩可以尽快引完东湖中的水（只有这样才能高效率的moyu）。对于给出的每条水渠，水只能沿着一个方向流动，但请注意可能会出现水环形流动的情形。

# Standard Input

第1行: 两个用空格分开的整数N (1 <= N <= 200) 和 M (2 <= M <= 10000)。N是水渠交叉点的数量，交点1是东湖，交点N是灭湖。M是`zh`和`hqf`已经挖好的水渠的数量。  
第2行到第M+1行: 每行有三个整数，Si, Ei, 和 Ci。Si 和 Ei (1 <= Si, Ei <= N) 指明水渠两端的交点，水从Si 流向Ei。Ci (0 <= Ci <= 20000)是这条水渠的最大容量。

# Standard Output

输出一个整数，即排水的最大流量。

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
<tr><td>4 4  
1 3 10  
1 2 20  
1 4 30  
2 4 10  </td><td>40</td></tr></table>


# Constraints



# Note



# Source


