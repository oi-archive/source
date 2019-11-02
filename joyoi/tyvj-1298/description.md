# 

 
 # 题目描述 
<p>&nbsp;&nbsp;一天，小B买了一袋上好的红富士苹果N个（而且这些苹果长得都不一样），因为他是住校生，买东西很不方便，于是他准备带这些苹果到学校享用。小B好不容易将这些苹果带到了学校，但他的两个室友已经在床上等他好久了（别想多了，他们只是很关注小B手上的苹果）。小B心想：好，我就象征性地给你们一人一个就是了。谁料，那两个室友早已算好了，他们用的袋子和小B的袋子一摸一样（就连污垢的形状也是一样的&hellip;），也只有那两个室友才知道哪个袋子是哪个人的，他们直接把小B的那一袋抢了过来，然后把苹果倒了出来。这下小B分不清楚哪个袋子是哪个袋子了。（PS：每个人都有一个袋子）<br />
&nbsp;&nbsp;&nbsp;&nbsp;具体的分苹果方式：小B可以给某一个或者两个袋子不装任何苹果，也可以给所有袋子都装上苹果。<br />
现在小B只是想知道的是分苹果的方法有多少种。<br />
&nbsp;</p> 

 
 # 输入格式 
<p>输入数据只有一行，为n和k<br />
n是指n个苹果<br />
k是指结果要mod&nbsp;k</p> 

 
 # 输出格式 
<p>输出数据亦有一行，为所有方案数M。</p> 

 
 # 提示 
<p>【数据规模】<br />
&nbsp;&nbsp;对于40%的数据：&nbsp;&nbsp;n&lt;=10,000<br />
&nbsp;&nbsp;对于100%的数据：&nbsp;n&lt;=1,000,000,000;k&lt;maxlongint<br />
<br />
【解释】我们以N=3为例。有3个苹果，其编号分别为1,2,3。那么就有一下五种情况：<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0&nbsp;|&nbsp;0&nbsp;|&nbsp;1,2,3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0&nbsp;|&nbsp;1&nbsp;|&nbsp;2,3<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0&nbsp;|&nbsp;2&nbsp;|&nbsp;1,3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0&nbsp;|&nbsp;3&nbsp;|&nbsp;1,2<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1&nbsp;|&nbsp;2&nbsp;|&nbsp;3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;（每个袋子用&quot;|&quot;分开）<br />
<br />
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
<tr><td>11 10000
</td><td>9525
</td></tr></table>
