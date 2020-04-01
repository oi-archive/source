# 

 
 # 题目描述 
<p>花匠栋栋种了一排花，每株花都有自己的高度。花儿越长越大，也越来越挤。栋栋决定把这排中的一部分花移走，将剩下的留在原地，使得剩下的花能有空间长大，同时，栋栋希望剩下的花排列得比较别致。<br />
具体而言，栋栋的花的高度可以看成一列整数ℎ1,&nbsp;ℎ2,&nbsp;&hellip;&nbsp;,&nbsp;ℎn。设当一部分花被移走后，剩下的花的高度依次为g1,&nbsp;g2,&nbsp;&hellip;&nbsp;,&nbsp;gm，则栋栋希望下面两个条件中至少有一个满足：<br />
条件&nbsp;A：对于所有的1&nbsp;&le;&nbsp;i&nbsp;&le;&nbsp;m/2，g2i&nbsp;&gt;&nbsp;g2i&minus;1，且g2i&nbsp;&gt;&nbsp;g2i+1；<br />
条件&nbsp;B：对于所有的1&nbsp;&le;&nbsp;i&nbsp;&le;&nbsp;m/2，g2i&nbsp;&lt;&nbsp;g2i&minus;1，且g2i&nbsp;&lt;&nbsp;g2i+1。<br />
注意上面两个条件在m&nbsp;=&nbsp;1时同时满足，当m&nbsp;&gt;&nbsp;1时最多有一个能满足。<br />
请问，栋栋最多能将多少株花留在原地。</p> 

 
 # 输入格式 
<p>输入的第一行包含一个整数&nbsp;，表示开始时花的株数。&nbsp;<br />
第二行包含&nbsp;个整数，依次为ℎ1,&nbsp;ℎ2,&hellip;&nbsp;,&nbsp;ℎn，表示每株花的高度。</p> 

 
 # 输出格式 
<p>输出一行，包含一个整数m，表示最多能留在原地的花的株数。</p> 

 
 # 提示 
<p>【输入输出样例说明】<br />
有多种方法可以正好保留&nbsp;3&nbsp;株花，例如，留下第&nbsp;1、4、5&nbsp;株，高度分别为&nbsp;5、1、2，满足条件&nbsp;B。<br />
【数据范围】<br />
对于&nbsp;20%的数据，n&nbsp;&le;&nbsp;10；<br />
对于&nbsp;30%的数据，n&nbsp;&le;&nbsp;25；<br />
对于&nbsp;70%的数据，n&nbsp;&le;&nbsp;1000，0&nbsp;&le;&nbsp;ℎi&nbsp;&le;&nbsp;1000；<br />
对于&nbsp;100%的数据，1&nbsp;&le;&nbsp;n&nbsp;&le;&nbsp;100,000，0&nbsp;&le;&nbsp;ℎi&nbsp;&le;&nbsp;1,000,000，所有的ℎi随机生成，所有随机数服从某区间内的均匀分布。</p> 
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
5 3 2 1 2 </td><td>3</td></tr></table>
