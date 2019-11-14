
# Content

为了解决日渐增长的人口问题，Mstdream率领一个小组到达火星开发新的居住地
地球到火星有一架太空电梯，电梯一次最多承载2个人，最大载重为k
小组一共有n个人，第i个人重量为vi.人们排成一队等候上电梯
上电梯的规则是这样的：
1.	如果电梯是空的，下一个人可以上去
2.	如果电梯有一个人，并且下一个人上电梯不会超重，下一个人可以上去，否则太空电梯会将前一个人载到火星后返回接下一个人
3.	如果电梯有两个人，下一个人不能上去。
由于管理出现了失误！人们排队的顺序发生了变化.假设人们的顺序是未知的，Mstdream想知道，太空电梯最多会跑多少趟？

# Standard Input

第一行两个数n，k
第二行开始n行，每行一个数代表vi

# Standard Output

输出一个数，代表最坏情况下太空电梯需要跑的趟数

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
<tr><td>6 6
1
2
3
3
4
5
</td><td>5</td></tr></table>


# Constraints



# Note

最坏情况下排队的顺序如下：（2）（5 1）（3）（4）（3）
50% n<=10
100%: n<=100000,k<=10000000000,vi<=k

# Source


