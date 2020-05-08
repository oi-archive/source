
# Content

春希和雪菜在一起很久了，但由于经济原因，他们还是住在那间小房间里。他们为了能够早日获得一个更好的房子，把大量的收入积攒了起来。

为了减少消费，除了银行存款之外，他们把现金也存进了若干个储蓄罐中。每个储蓄罐有一把钥匙，他们把这些钥匙也放进了储蓄罐。

终于，两人有了足够的积蓄，也做好了搬家的全部准备。即将搬家之时，两人得知雪菜已怀有身孕。双喜临门之下，春希想打破所有储蓄罐，拿出其中的现金，但细心的雪菜却希望打破尽量少的储蓄罐，使用钥匙打开其余储蓄罐，你能帮她计算出最少需要打破多少个储蓄罐吗？

![v400300.png](/source/lutece/xue-cai-de-xin-jia/img/aHR0cHM6Ly9oZXJhbm8uY29kaW5nLm5ldC9wL1BpY1BsYWNlL2QvUGljUGxhY2UvZ2l0L3Jhdy9tYXN0ZXIvdjQwMDMwMF9yZXNpemUucG5n.png)

# Standard Input

第一行，一个数字 $n$，表示储蓄罐数量。
第二行，$n$ 个整数 $a_1\dots a_n$，表示第 $i$ 个储蓄罐的钥匙在第 $a_i$ 个储蓄罐中。

# Standard Output

一个整数，表示最少需要打破的储蓄罐数量。

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
<tr><td>6
1 3 2 1 5 1
</td><td>3</td></tr></table>


# Constraints

$0<n\leq 10^6$
$1\leq a_i\leq n$

# Note

1. 输入量较大，如果使用 `iostream`，请关闭同步：`std::ios::sync_with_stdio(0); std::cin.tie(0);`
2. 请尽量考虑数据结构相关知识点，使用其他方面的算法不保证不会遇到卡常等问题哦（当然常数控制好过了也给分，不必重做）

# Source


