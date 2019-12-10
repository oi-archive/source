# 

 
 # 题目背景 
2010年11月3日，是一个难忘的日子。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;腾讯发布消息：存360则，不留QQ。留QQ，则须卸360。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;360则表示360与QQ可以共存。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;这也就标志着腾讯与360的大战就此开始！<BR><BR> 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;现在，腾讯与360由于身处异地，非常迫切地想在最短的时间内相遇，然后干一架。但是由于双方的技术员都在努力地编程序想干掉对方，所以他们希望你来帮他们找到一个最好的方案使得相遇的时间最短。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;在此我们定义"相遇"为：两个人皆在同一个有编号的城市上就可以了，并且这两个人均可以站在原地等另外一个人。也就是说，在这里我们不考虑两人在路中间相遇。<BR><BR> 

 
 # 输入格式 
输入数据第一行：N和M（用空格隔开）&nbsp;表示这是一个N个点的图并且有M条边<BR>第二行到第M+1行&nbsp;为这个图的详细信息。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;每行共有被空格隔开的三个数：a&nbsp;b&nbsp;c。表示编号为a的城市到编号为b的城市<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;有一个双向边，并且要过这条双向边所需要花费的时间为c。<BR>最后一行有两个数：S和T，S表示腾讯所处的城市（也就是深圳），T表示360所处的<BR>城市（也就是北京）<BR><BR> 

 
 # 输出格式 
输出只有一行，D，表示二者"相遇"的最短时间。当然，如果无法相遇则输出"Peace!"<BR> 

 
 # 提示 
[数据范围]每组都是n=5000&nbsp;m=5000&nbsp;并且保证运算过程中的所有值都不会超过117901063<BR><BR><BR> 
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
<tr><td>3 3
1 2 1 
2 3 1
1 3 1
1 3

</td><td>1
</td></tr></table>
