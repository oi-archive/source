# 

 
 # 题目背景 
NOIP2009&nbsp;第二题<BR> 

 
 # 题目描述 
Hanks博士是BT（Bio-Tech，生物技术）领域的知名专家，他的儿子名叫Hankson。现在，刚刚放学回家的Hankson正在思考一个有趣的问题。<BR>今天在课堂上，老师讲解了如何求两个正整数c1和c2的最大公约数和最小公倍数。现在Hankson认为自己已经熟练地掌握了这些知识，他开始思考一个“求公约数”和“求公倍数”之类问题的“逆问题”，这个问题是这样的：已知正整数a0,a1,b0,b1，设某未知正整数x满足：<BR>1、&nbsp;&nbsp;x和a0的最大公约数是a1；<BR>2、&nbsp;&nbsp;x和b0的最小公倍数是b1。<BR>Hankson的“逆问题”就是求出满足条件的正整数x。但稍加思索之后，他发现这样的x并不唯一，甚至可能不存在。因此他转而开始考虑如何求解满足条件的x的个数。请你帮助他编程求解这个问题。<BR><BR> 

 
 # 输入格式 
&nbsp;&nbsp;输入第一行为一个正整数n，表示有n组输入数据。接下来的n行每行一组输入数据，为四个正整数a0，a1，b0，b1，每两个整数之间用一个空格隔开。输入数据保证a0能被a1整除，b1能被b0整除。<BR> 

 
 # 输出格式 
输出共n行。每组输入数据的输出结果占一行，为一个整数。<BR>对于每组数据：若不存在这样的x，请输出0；<BR>若存在这样的x，请输出满足条件的x的个数；<BR> 

 
 # 提示 
各个测试点1s<BR> 
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
<tr><td>2
41 1 96 288
95 1 37 1776
</td><td>6
2

</td></tr></table>
