# 

 
 # 题目描述 
Rainbow和Freda通过一次偶然的机会来到了魔界。魔界的大门上赫然写着：<br>小盆友们，欢迎来到魔界~！乃们需要解决这样一个问题才能进入哦lala~<br>有N枚骰子，其中第i（1&lt;=i&lt;=N）枚骰子有a[i]面。掷出第i枚骰子时，这a[i]面中只有一面朝上，而且这a[i]面每面朝上的概率都相等，为1/a[i].<br>门上还写道：这N个骰子，显然一共有M=Sigma(a[i])个面。你们要做的就是把1~M这M个数字不重不漏地写到这M个面上。同时掷出这N个骰子，你们的得分就是这N个骰子朝上的面上的数字之和。你们要做的，就是使你们的得分的期望值最大哦~<br> 

 
 # 输入格式 
第一行一个整数N，表示骰子的数目。<br>第二行N个整数，第i个整数a[i]表示第i个骰子有多少个面。<br> 

 
 # 输出格式 
一行一个实数Ans，表示Freda和Rainbow得分的最大期望值，保留三位小数。 

 
 # 提示 
样例解释<br>在第一个骰子的唯一一面写上5,第二个骰子的四面分别写上1,2,3,4。这样得分的期望就是5/1+(1+2+3+4)/4=7.5了。<br><br>数据范围与约定<br>对于30%的数据，N&lt;=10<br>对于50%的数据，N&lt;=1000.<br>对于100%的数据，0&lt;N&lt;=50000&nbsp;,0&lt;a[i]&lt;=100.<br>From&nbsp;-&nbsp;This_poet<br>Contact&nbsp;me&nbsp;-&nbsp;This_poet@126.com/Freda.RD.Shi@gmail.com<br>This_poet's&nbsp;Blog&nbsp;-&nbsp;http://thispoet.blogcn.com 
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
1 4
</td><td>7.500</td></tr></table>
