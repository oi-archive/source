
# Content

`eom`是`jjjj`手下的清洁工，今天他又被叫去给`jjjj`的广场扫垃圾。广场可以被视作一个$n*m$的矩形地区，在其中一些块会有垃圾挡住行人的通行，于是`jjjj`叫`eom`要把一些垃圾清除使得干净的地区都能互相连通。偷懒的`eom`想要知道他至少要打扫多少块地区才能达到`jjjj`的要求？

# Standard Input

第一行为两个整数$n$和$m$，表示城市有$n$行$m$列。

接下来$n$行每行有$m$个字符，'1'表示有垃圾，'0'表示空地。

# Standard Output

输出一个整数表示最少需要打扫多少块地上的垃圾。

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
<tr><td>5 3
000
001
110
000
010</td><td>1</td></tr></table>


# Constraints

$nm\le 80$

# Note

样例中打扫区域(2,3),(3,1)或(3,2)都能使空地联通

# Source


