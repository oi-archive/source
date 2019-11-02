# 

 
 # 题目背景 
　　吃过草莓刨冰之后，Vani和cl有些疲倦地坐在一个长椅上。<BR>　　“呐，玩得开心吗？”Vani忽然问道。<BR>　　“嗯……很，很开心的说。”<BR>　　“那么，我有一个问题想要问你呢。”<BR>　　cl的脸有点红了起来。<BR>　　“嗯……好吧。问、问吧……我会告诉你的哦……”<BR>　　“那好。对于一个分数A&nbsp;/&nbsp;B……”<BR>　　“嗯……哎？哎？！”<BR>　　“……就是这个问题。我觉得这个问题好纠结啊……”<BR>　　Vani淡定地说完这句话。<BR>　　“啊？！哈啊？！”&nbsp; 

 
 # 题目描述 
　　对于给定的分数&nbsp;A&nbsp;/&nbsp;B，求其在&nbsp;K&nbsp;进制下是有限小数还是循环小数。如果是有限小数，求小数点后的位数；如果是循环小数，则求混循环部分和循环节的长度又分别是多少。<BR>　　注意，循环节指的是最短循环节，且混循环部分的长度也指最短。 

 
 # 输入格式 
　　第一行一个正整数&nbsp;T，表示测试数据的数目。<BR>　　每个测试数据包含三个空格分隔的整数&nbsp;A,&nbsp;B,&nbsp;K。含义如题目所示。 

 
 # 输出格式 
　　对于每个测试数据，在单独的一行内输出两个空格分隔的整数&nbsp;M,&nbsp;R。<BR>　　其中&nbsp;M&nbsp;表示混循环部分的长度，R&nbsp;表示循环节的长度。<BR>　　如果&nbsp;A&nbsp;/&nbsp;B&nbsp;在&nbsp;K&nbsp;进制下是有限小数，则&nbsp;R&nbsp;=&nbsp;0，M&nbsp;为小数点后面的位数；如果&nbsp;A&nbsp;/&nbsp;B&nbsp;在&nbsp;K&nbsp;进制下是纯循环小数，则&nbsp;M&nbsp;=&nbsp;0。 

 
 # 提示 
　　对于&nbsp;50%&nbsp;的数据，B≤100000。<BR>　　对于&nbsp;100%&nbsp;的数据，1≤A&lt;B≤10^12，K≤10^12，T≤10。 
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
1 8 10
17 99 10
217 990 10</td><td>3 0
0 2
1 2</td></tr></table>
