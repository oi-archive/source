# 

 
 # 题目背景 
此为平衡树系列最后一道：二逼平衡树 

 
 # 题目描述 
您需要写一种数据结构（可参考题目标题），来维护一个有序数列，其中需要提供以下操作：<BR>1.查询k在区间内的排名<BR>2.查询区间内排名为k的值<BR>3.修改某一位值上的数值<BR>4.查询k在区间内的前驱(前驱定义为小于x，且最大的数)<BR>5.查询k在区间内的后继(后继定义为大于x，且最小的数) 

 
 # 输入格式 
第一行两个数&nbsp;n,m&nbsp;表示长度为n的有序序列和m个操作<BR>第二行有n个数，表示有序序列<BR>下面有m行，opt表示操作标号<BR>若opt=1&nbsp;则为操作1，之后有三个数l,r,k&nbsp;表示查询k在区间[l,r]的排名<BR>若opt=2&nbsp;则为操作2，之后有三个数l,r,k&nbsp;表示查询区间[l,r]内排名为k的数<BR>若opt=3&nbsp;则为操作3，之后有两个数pos,k&nbsp;表示将pos位置的数修改为k<BR>若opt=4&nbsp;则为操作4，之后有三个数l,r,k&nbsp;表示查询区间[l,r]内k的前驱<BR>若opt=5&nbsp;则为操作5，之后有三个数l,r,k&nbsp;表示查询区间[l,r]内k的后继 

 
 # 输出格式 
对于操作1,2,4,5各输出一行，表示查询结果 

 
 # 提示 
n,m&lt;=50000&nbsp;&nbsp;&nbsp;保证有序序列所有值在任何时刻满足[0,10^8] 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>9 6
4 2 2 1 9 4 0 1 1
2 1 4 3
3 4 10
2 1 4 3
1 2 5 9
4 3 9 5
5 2 8 5
</td><td>2
4
3
4
9
</td></tr></table>
