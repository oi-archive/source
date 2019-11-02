# 

 
 # 题目背景 
<p>小Q有着心爱的幸运数字。</p> 

 
 # 题目描述 
<p>小Q认为，在这个世界上，有一群数字会偏爱他，为他带来好运。</p>

<p>生活中有不少的人会把自己喜欢的数字当成自己的幸运数字，但是，其实正确的幸运数字是靠计算出来的，小Q也是这么认为的。</p>

<p>小Q知道，为他带来好运的数字，一定满足下面的条件：</p>

<p><strong>如果数字X是他的幸运数字，则X在m进制下的表示为x<sub>1</sub>x<sub>2</sub>...x<sub>k</sub>，一定有x<sub>1</sub>&lt;=x<sub>2</sub>&lt;=...&lt;=x<sub>k，其中k可以表示X在m进制下的位数</sub>。</strong></p>

<p>这样的数字对于他来说是无穷多个的，但是他只喜欢在m进制下位数不超过n的幸运数字，你知道这是多少个数字吗？小Q不会算，于是想请你帮他解决这个问题。</p>

<p>这个答案可能很大，你只需要输出答案对一个质数p取模的值即可。</p> 

 
 # 输入格式 
<p>共一行，三个正整数n、m和p，保证p是质数。</p> 

 
 # 输出格式 
<p>共一行，表示答案对p取模的值。</p> 

 
 # 提示 
<h4>数据范围</h4>

<p>前20%的数据满足&nbsp;n&nbsp;&lt;=&nbsp;18,&nbsp;m&nbsp;&lt;=&nbsp;10。</p>

<p>前40%的数据满足&nbsp;n&nbsp;&lt;=&nbsp;100,&nbsp;m&nbsp;&lt;=&nbsp;100。</p>

<p>前60%的数据满足&nbsp;n&nbsp;&lt;=&nbsp;1000,&nbsp;m&nbsp;&lt;=&nbsp;1000。</p>

<p>前80%的数据满足&nbsp;n&nbsp;&lt;=&nbsp;10^7,&nbsp;m&nbsp;&lt;=&nbsp;10^7,&nbsp;n&nbsp;+&nbsp;m&nbsp;&lt;=&nbsp;p。</p>

<p>100%的数据满足&nbsp;n&nbsp;&lt;=&nbsp;10^18,&nbsp;2&nbsp;&lt;=&nbsp;m&nbsp;&lt;=&nbsp;10^18,&nbsp;p&nbsp;&lt;=&nbsp;10000079。</p>

<h4>来源</h4>

<p>tangjz</p> 
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
<tr><td>4 10 10000079
</td><td>715
</td></tr></table>
