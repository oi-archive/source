# 

 
 # 题目背景 
<p>noip2013day2</p> 

 
 # 题目描述 
<p>&nbsp;</p>

<p>&nbsp;</p>

<p>花匠栋栋种了一排花，每株花都有自己的高度。花儿越长越大，也越来越挤。栋栋决定<br />
把这排中的一部分花移走，将剩下的留在原地，使得剩下的花能有空间长大，同时，栋栋希<br />
望剩下的花排列得比较别致。<br />
具体而言，栋栋的花的高度可以看成一列整数ℎ<sub>1</sub>,&nbsp;ℎ<sub>2</sub>,&nbsp;&hellip;&nbsp;,&nbsp;ℎ<sub>n</sub>设当一部分花被移走后，<br />
剩下的花的高度依次为g<sub>1</sub>,g<sub>2</sub>,&hellip;,g<sub>m</sub>则栋栋希望下面两个条件中至少有一个满足：</p>

<p>条件A:对于所有的1&le;i&le;m&nbsp;div&nbsp;2,有g<sub>2i</sub>&gt;g<sub>2i-1</sub>,对于所有的1&le;i&lt;m&nbsp;div&nbsp;2,有g<sub>2i</sub>&gt;g<sub>2i+1</sub></p>

<p>条件B:对于所有的1&le;i&le;m&nbsp;div&nbsp;2,有g<sub>2i</sub>&lt;g<sub>2i-1</sub>,对于所有的1&le;i&lt;m&nbsp;div&nbsp;2,有g<sub>2i</sub>&lt;g<sub>2i+1</sub></p>

<p>注意上面两个条件在m=&nbsp;1时同时满足，当m&gt;&nbsp;1时最多有一个能满足。<br />
请问，栋栋最多能将多少株花留在原地。<br />
&nbsp;</p> 

 
 # 输入格式 
<p>输入的第一行包含一个整数n表示开始时花的株数。<br />
第二行包含n整数，依次为ℎ1,&nbsp;ℎ2,&nbsp;&hellip;&nbsp;,&nbsp;ℎn表示每株花的高度。</p> 

 
 # 输出格式 
<p>输出一行，包含一个整数m,表示最多能留在原地的花的株数。</p> 

 
 # 提示 
<p>&nbsp;</p>

<p>对于&nbsp;20%的数据，&nbsp;n&le;&nbsp;10；<br />
对于&nbsp;30%的数据，&nbsp;n&le;&nbsp;25；<br />
对于&nbsp;70%的数据，&nbsp;n&le;&nbsp;1000，&nbsp;0&nbsp;&le;&nbsp;ℎi<span style="line-height: 1.6em;">&le;&nbsp;1000</span><span style="line-height: 1.6em;">；</span></p>

<p>对于&nbsp;100%的数据，&nbsp;1&nbsp;&le;n&nbsp;&le;&nbsp;100,000，&nbsp;0&nbsp;&le;&nbsp;ℎi&le;&nbsp;1,000,000。</p>

<p>by&nbsp;460289052<br />
&nbsp;</p> 
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
<tr><td>5
5 3 2 1 2</td><td>3</td></tr></table>
