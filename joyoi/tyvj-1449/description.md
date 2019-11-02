# 

 
 # 题目背景 
对于一只猫咪来说，它是有九条命的。但是并不是所有的猫咪都是这样，只有那些造化很高的猫咪才能死而复生。而且对于这样的猫咪，如果它能够活到第九条命，那么它最终可以变成任何一种它想成为的动物（当然也可以继续做猫咪啦），我们称这样的猫咪为猫神。现在一只获得了进化机会的猫咪，受到了女神snowharmony的考验。 

 
 # 题目描述 
它拥有t个单位的时间，在每个单位时间里，它可以选择沉默、叫一声“喵”、或者叫两声“喵喵”。对于每个单位时间，均有一个实数v[i]，猫咪叫一声可获得v[i]的进化量，叫两声可以获得(v[i])^2的进化量，然而它在某个单位时间如果叫了两声，下一单位时间必须保持沉默来休息。<BR>女神Snowharmony要求它以一定的方式叫，只有它最终获得了最大的进化量，它才能进化为猫神，从而变为它想成为的动物——人族zsw95。<BR>请你帮助它计算最大进化量，使他进化为为猫神zsw95。<BR> 

 
 # 输入格式 
输入：<BR>第一行一个整数t。<BR>第二行，t个实数v[i]。<BR> 

 
 # 输出格式 
最大的进化量，保留四位小数。 

 
 # 提示 
1&lt;=t&lt;=800000,-255.00&lt;=v[i]&lt;=255.00<BR>计算结果不超过maxlongint来源：lydliyudong&nbsp;&nbsp;&nbsp;&nbsp;Tyvj&nbsp;February二月月赛第二场&nbsp;&nbsp;第1道 
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
9 2 1
</td><td>82.0000</td></tr></table>
