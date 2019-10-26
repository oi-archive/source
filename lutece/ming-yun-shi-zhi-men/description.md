
# Content

“这一切都是命运石之门的选择！“

凶真博士发明了能够逆转时间的电话微波炉，也就是微型时光机。每次时光机开机时，时光机顶部的数字屏上会随机显示一个数字n，表示此时在什么也不放置的情况下启动微波炉，会回到距离现在n小时之前。凶真博士可以通过烤香蕉的形式改变数字n。如果凶真博士一次烤两根香蕉，数字n会变为原来的两倍。如果凶真博士一次烤三根香蕉，数字n会减去3。如果凶真博士一次烤一根香蕉或三根以上香蕉，时光机就会爆炸。此外，如果在烤香蕉的过程中，n太大(n>500000)或n太小(n≤0)，时光机也会因为太阳黑子带来的压力过大而爆炸。

凶真博士想要回到距离现在m小时之前的世界，他至少要花费多少根香蕉呢？

# Standard Input

两个空格隔开的整数n,m.

1≤n,m≤500000

# Standard Output

一个整数，表示最少需要烤多少个香蕉。

如果怎样烤香蕉都不能回到m小时之前的世界，输出-1.

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
<tr><td>4 5</td><td>5</td></tr><tr><td>4 6</td><td>-1</td></tr></table>


# Constraints



# Note

样例1：可以先烤两根香蕉将n从4变为8，再烤三根香蕉将其变为5.

# Source


