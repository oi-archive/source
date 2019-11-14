# 

 
 # 题目背景 
2011.2.1 

 
 # 题目描述 
给出一个正整数集合A={x|&nbsp;m&lt;=x&lt;=n}，我们要找到元素个数最多一个A的子集S，使得：对于S中任意两个元素i，j(i&lt;&gt;j)有i@j&lt;&gt;k,其中@为加减乘除四个运算中的一个，而k是一个正整数。<BR><BR>现在我们要求出这个子集S的元素个数<BR> 

 
 # 输入格式 
第一行一个数T，表示输入数据的组数<BR>第二行到第T+1行，每行有一个运算符@，三个数字k,m,n，每个输入元素之间用空格连接，含义见题目<BR> 

 
 # 输出格式 
输出一共T行，第i行对应着输入的第i+1行数据的输出结果 

 
 # 提示 
这个正整数集合A也可以被描述为从m到n的正整数<BR>40%的数据中单个数据点中的运算符@是唯一的<BR>60%的数据中T&lt;=20,<BR>70%的数据中T&lt;=100,n,m,k&lt;1000;<BR>100%的数据中T&lt;=2000,n,m&lt;1000000;k&lt;1000000,保证m&lt;=n;<BR><BR>from&nbsp;西部314&nbsp;&nbsp;TYVJ月赛出题组 
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
<tr><td>4
+ 3 1 3
- 5 1 6
* 2 1 4
/ 2 1 4
</td><td>2
5
3
3
</td></tr></table>
