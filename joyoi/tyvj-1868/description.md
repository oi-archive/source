# 

 
 # 题目描述 
认识到了游泳的巨大安全隐患之后，小朋友们都决定不去游泳了。于是，游泳馆冷清了下来。为了能因时制宜、因事制宜，游泳馆决定在游泳项目之外，还开设头脑风暴项目。<BR>头脑风暴当中有这样一道题目：<BR>给出一个LEN位的数字A，你可以删除数字A当中的N位，删除之后得到一个LEN-N位的数字B，你的目标就是使这个数字B最小。<BR>头脑风暴规定，第一名的选手可以获得奖品哦~还等什么，快来参加吧！ 

 
 # 输入格式 
第一行LEN位0~9的整数，表示数字A.<BR>第二行一个整数N，表示你可以进行的删除操作的次数。<BR>数据保证数字A没有前导0.<BR>由于LEN可以从数字A间接得到，因此不直接给出LEN的大小。 

 
 # 输出格式 
一行，表示数字A在一系列操作之后的最小值，即数字B.<BR>如果数字B有前导0，请不要输出前导0.<BR>特别地，如果数字B为0，请输出一个数字“0”（不含引号）. 

 
 # 提示 
样例解释：删掉数字A的第1&nbsp;3&nbsp;4位，得到数字B为“01”，去除前导0，输出1.<BR>对于50%的数据，LEN&lt;=100000.<BR>对于100%的数据，LEN&lt;=5000000,0&lt;=N&lt;=LEN.From&nbsp;-&nbsp;This_poet<BR>Contact&nbsp;me&nbsp;-&nbsp;This_poet@126.com/Freda.RD.Shi@gmail.com<BR>This_poet's&nbsp;Blog&nbsp;-&nbsp;http://thispoet.blogcn.com 
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
<tr><td>20131
3</td><td>1
</td></tr></table>
