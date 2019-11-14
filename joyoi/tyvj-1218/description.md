# 

 
 # 题目描述 
<p>有&nbsp;N&nbsp;堆纸牌，编号分别为&nbsp;1，2，&hellip;,&nbsp;N。每堆上有若干张，但纸牌总数必为&nbsp;N&nbsp;的倍数。可以在任一堆上取若干张纸牌，然后移动。<br />
　　移牌规则为：在编号为&nbsp;1&nbsp;堆上取的纸牌，只能移到编号为&nbsp;2&nbsp;的堆上；在编号为&nbsp;N&nbsp;的堆上取的纸牌，只能移到编号为&nbsp;N-1&nbsp;的堆上；其他堆上取的纸牌，可以移到相邻左边或右边的堆上。<br />
　　现在要求找出一种移动方法，用最少的移动次数使每堆上纸牌数都一样多。<br />
<br />
　　例如&nbsp;N=4，4&nbsp;堆纸牌数分别为：<br />
　　①　9　②　8　③　17　④　6<br />
　　移动3次可达到目的：<br />
　　从&nbsp;③&nbsp;取&nbsp;4&nbsp;张牌放到&nbsp;④&nbsp;（9&nbsp;8&nbsp;13&nbsp;10）&nbsp;-&gt;&nbsp;从&nbsp;③&nbsp;取&nbsp;3&nbsp;张牌放到&nbsp;②（9&nbsp;11&nbsp;10&nbsp;10）-&gt;&nbsp;从&nbsp;②&nbsp;取&nbsp;1&nbsp;张牌放到①（10&nbsp;10&nbsp;10&nbsp;10）。</p> 

 
 # 输入格式 
<p>N（N&nbsp;堆纸牌，1&nbsp;&lt;=&nbsp;N&nbsp;&lt;=&nbsp;100）<br />
A1&nbsp;A2&nbsp;&hellip;&nbsp;An&nbsp;（N&nbsp;堆纸牌，每堆纸牌初始数，l&lt;=&nbsp;Ai&nbsp;&lt;=10000）</p> 

 
 # 输出格式 
<p>所有堆均达到相等时的最少移动次数。</p> 

 
 # 提示 
<p>NOIP2002提高组第一题</p> 
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
9 8 17 6
</td><td>3</td></tr></table>
