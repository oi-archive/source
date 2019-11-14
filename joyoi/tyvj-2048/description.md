# 

 
 # 题目描述 
经过一番努力，Freda和Rainbow来到了魔力铁路的1号站台。它们知道，魔力铁路不同于普通的铁路，下面有一段关于魔力铁路的介绍。<br>魔力铁路一共有N座站台，从第i(1&lt;i&lt;=N)号站台出发可以到达第i-1号站台。同时，对于每个i(1&lt;=i&lt;=N)，你需要规定x[i]为1~N当中的任意一个数字，表示从第i号站台出发可以到达的另外一个站台，当然，你也可以把x[i]规定为i或者i-1。<br>Rainbow和Freda想知道，有多少种不同的规定x[i]的方案，使得它们能够到达N号站台呢？方案A、B不同的条件是：存在一个i（1&lt;=i&lt;=N）使得方案A中的x[i]与方案B中的x[i]不同。Freda最讨厌乱七八糟的上万位数字了，所以，记得把答案mod&nbsp;1000000007（10^9+7）哦lala~<br><br> 

 
 # 输入格式 
一行一个整数N，表示站台的总数。<br> 

 
 # 输出格式 
一行一个整数Ans，表示Freda和Rainbow能够到达N号站台的方案数。<br> 

 
 # 提示 
样例解释<br>12种可能的方案如下(每行代表一种方案)：<br>x[1]	x[2]	x[3]<br>2	3	1<br>2	3	2<br>2	3	3<br>3	1	1<br>3	1	2<br>3	1	3<br>3	2	1<br>3	2	2<br>3	2	3<br>3	3	1<br>3	3	2<br>3	3	3<br><br><br>数据范围与约定<br>对于30%的数据，N&lt;=5.<br>对于50%的数据，N&lt;=10.<br>对于70%的数据，N&lt;=100.<br>对于100%的数据，0&lt;N&lt;=5000.<br><br>From&nbsp;-&nbsp;This_poet<br>Contact&nbsp;me&nbsp;-&nbsp;This_poet@126.com/Freda.RD.Shi@gmail.com<br>This_poet's&nbsp;Blog&nbsp;-&nbsp;http://thispoet.blogcn.com<br> 
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
<tr><td>3
</td><td>12
</td></tr></table>
