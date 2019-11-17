# 

 
 # 题目背景 
<h3>来源</h3>

<p>IOI2013&nbsp;中国国家队选拔赛&nbsp;第二试</p>

<h3>版权</h3>

<p>tyvj不拥有该题目的版权。如果无意侵犯了您的权益，请联系管理员，本站将及时删除,以免发生不必要的矛盾。</p> 

 
 # 题目描述 
<p>通过代数基本定理，我们知道若计算重根，一个&nbsp;n&nbsp;次的多项式在复数域内恰好有n&nbsp;个零点(函数值为0&nbsp;的点)。现给定一个整系数多项式&nbsp;F[x]，它的&nbsp;n&nbsp;个零点恰好都是有理数（即可以写成两个整数相除的形式）；同时，若我们把它所有的非零零点（函数自变量不为&nbsp;0，函数值为&nbsp;0）去重，则可以得到&nbsp;r&nbsp;个互不相同的非零零点，其中第i&nbsp;个非零零点可以被表示成下式：&nbsp;</p>

<p><img alt="" src="/source/joyoi/tyvj-4452/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotNDQ1Mi9odHRwOi8vY2V4b3UuaW1nNDcud2FsOC5jb20vaW1nNDcvNTQzMjEyXzIwMTYwNDE1MTgzMDE5LzE0NjE4MzUwODM4NS5wbmc=.png" style="width: 97px; height: 64px;" /></p>

<p>式中&nbsp;sgn<sub>i</sub>&nbsp;表示第&nbsp;i&nbsp;个零点的符号，p<sub>i</sub>&nbsp;和&nbsp;q<sub>i</sub>&nbsp;为互质的两个正整数。现在告诉你&nbsp;F[x]，要求你输出将它因式分解后的形式。&nbsp;</p> 

 
 # 输入格式 
<p>输入只有一行，包含多项式&nbsp;F[x]。&nbsp;多项式一定是如下的形式：&nbsp;</p>

<p><img alt="" src="/source/joyoi/tyvj-4452/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotNDQ1Mi9odHRwOi8vY2V4b3UuaW1nNDcud2FsOC5jb20vaW1nNDcvNTQzMjEyXzIwMTYwNDE1MTgzMDE5LzE0NjE4NDAzNjY2OC5wbmc=.png" style="width: 310px; height: 31px;" /></p>

<p>次数一定为从高到低，其中a<sub>i</sub>为整数，并且若a<sub>i</sub>为&nbsp;0，则省略该项，若a<sub>i</sub>为负数，则省略之前的加号，若&nbsp;a<sub>i</sub>&nbsp;的绝对值为&nbsp;1&nbsp;且&nbsp;i&nbsp;不为&nbsp;0，则不输出&nbsp;1，并且保证a<sub>n</sub>&nbsp;不为&nbsp;0。<span style="line-height: 1.6em;">&nbsp;</span></p>

<p>详见样例输入。&nbsp;</p> 

 
 # 输出格式 
<p>输出一行，表示因式分解后的形式，格式如下：<img alt="" src="/source/joyoi/tyvj-4452/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotNDQ1Mi9odHRwOi8vY2V4b3UuaW1nNDcud2FsOC5jb20vaW1nNDcvNTQzMjEyXzIwMTYwNDE1MTgzMDE5LzE0NjE4NDAzNjcxMi5wbmc=.png" style="width: 427px; height: 27px;" /></p>

<p>其中&nbsp;u，v&nbsp;互质，且&nbsp;v&nbsp;为正整数。&nbsp;</p>

<p>其中ui/vi从小到大排列，若&nbsp;ui/vi&nbsp;=&nbsp;0&nbsp;则该项为&nbsp;x^ti，若&nbsp;ui/vi&nbsp;为负数，则省略加号，若&nbsp;vi&nbsp;为&nbsp;1，则省略/vi。</p>

<p>若&nbsp;ti&nbsp;为&nbsp;1&nbsp;则省略^&nbsp;ti。若&nbsp;an&nbsp;为&nbsp;&plusmn;1&nbsp;则将&nbsp;1&nbsp;省略。详见样例输出。&nbsp;</p> 

 
 # 提示 
<h3>数据规模及约定</h3>

<p><img alt="" src="/source/joyoi/tyvj-4452/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotNDQ1Mi9odHRwOi8vY2V4b3UuaW1nNDcud2FsOC5jb20vaW1nNDcvNTQzMjEyXzIwMTYwNDE1MTgzMDE5LzE0NjE4NDA3OTE1Mi5wbmc=.png" style="width: 637px; height: 634px;" /></p>

<h3>评测</h3>

<p>求不要卡评测o(&gt;﹏&lt;)o，好吗？\(^o^)/~</p> 
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
<tr><td>8x^7-258x^5+2112x^3-512x</td><td>8(x-4)^2(x-1/2)x(x+1/2)(x+4)^2</td></tr><tr><td>-x^2+2x-1</td><td>-(x-1)^2</td></tr></table>
