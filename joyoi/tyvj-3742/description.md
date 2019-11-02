# 

 
 # 题目背景 
<p>2141年，在第六次世界大战中幸存的人类（共有a1个）朝着面目全非的地球望了最后一眼，然后踏上了星际移民的旅程。但是他们的飞船突然受到强引力场的吸引，坠毁在一颗未知的星球上&hellip;&hellip;</p>

<p>&nbsp;</p> 

 
 # 题目描述 
<p>机器人科学家X对这颗星球进行了探测，发现刚才的引力来源于一次黑洞吞噬。在这颗星球的周围聚集了q个黑洞，按照黑洞的发展速度每小时每个黑洞都会进行一次吞噬，使一位人类丧生。但是发达的科学技术让人类能够快速繁衍。具体来说，每个人每个小时都能进行一次繁衍，创造出p个新人类，然后自己自爆，为新人类提供能量。我们假设新人类的生长速度足够快（也就是即时拥有繁衍能力），并且人类繁衍之时黑洞不会发生吞噬。现在X想知道，在第n个小时，会剩下多少人类？（为了更好地预言人类的未来，n可能会很大。）</p> 

 
 # 输入格式 
<p>第一行三个整数p,q,a1,第二行一个整数n。</p> 

 
 # 输出格式 
<p>一行一个整数，表示幸存的人类数。（对10^9+7取模）</p> 

 
 # 提示 
<p><span style="line-height: 1.6em;">样例解释：</span><span style="line-height: 1.6em;">在第1,2,3,4小时，分别有5,13,53,253个人类幸存。</span></p>

<p>数据范围：<br />
&nbsp;&nbsp;&nbsp;&nbsp;对20%的数据，满足1&lt;=n&lt;=10^6<br />
&nbsp;&nbsp;&nbsp;&nbsp;对60%的数据，满足1&lt;=n&lt;=10^18<br />
&nbsp;&nbsp;&nbsp;&nbsp;对100%的数据，满足1&lt;=n&lt;=10^3000,0&lt;=p,q,a1&lt;=10^9<br />
&nbsp;&nbsp;&nbsp;&nbsp;存在20%的数据，满足q=0<br />
&nbsp;&nbsp;&nbsp;&nbsp;存在10%的数据，满足p=q+1</p> 
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
<tr><td>5 12 5
4</td><td>253</td></tr></table>
