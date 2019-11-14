
# Content

Lweb学长是集训队里公认的男神。有一天他要给美美的学姐姐准备礼物。

Lweb学长可是会魔法的哟。为了准备一份礼物，男神要加工n份材料。每一次只能加工相邻的材料。

当男神加工两个魔法值为a,b的材料，男神都要消耗a*b的体力，同时在这个地方合成出魔法值(a+b)%100的材料。

男神为了能节省体力来完成他的礼物。想找聪明的你帮他算一算他所要花费的最小体力。

# Standard Input

第一行一个整数T，表示男神所要准备的礼物数。
之后的T组数据各有两行数据，第一行有一个整数n，表示这份礼物的材料数(1<=n<=100)。
接下来一行有n个整数a(0<=a<100)，表示这件礼物第i份材料的魔法值。

# Standard Output

每组数据一行输出，表示男神制作这份礼物所要的最小体力。

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
2
18 19
3
40 60 20</td><td>342
2400</td></tr></table>


# Constraints



# Note

对于样例 2：

先加工材料40和60，得到0的材料，消耗40$*$60体力，共消耗2400体力；

再加工材料0和20，得到20的材料，消耗0$*$20体力，共消耗2400体力.

# Source


