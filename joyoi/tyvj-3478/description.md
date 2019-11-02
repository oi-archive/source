# 

 
 # 题目描述 
<p>探案第二部&nbsp;(holmes)<br />
　　我们伟大的&nbsp;Sherlock&bull;Holmes&nbsp;先生最近遇上了一件相当棘手的案子，随着对案情逐渐深入的研究，他开始意识到：此案地域横跨欧洲，而起因可以追溯到50年前！为了尽快搜集各方面的线索，他决定与Dr.&nbsp;Watson分头行动。<br />
　　Holmes列出了若干需要的线索：某处的一些雪茄烟灰；地下室油画上的颜料的呈色；Black兄弟与他们邻里的联系&hellip;&hellip;诸如此类。而搜集这些线索需要一定的时间。不过，有些线索是相关联的，即在得到某个线索的时候，一并可以得出其他结论（我们可以认为这是不需要时间的）<br />
　　请充分相信Holmes先生！他无比敏锐的思维足够将所有线索串联，以完美的推理侦破这件名噪一时的大案！<br />
&nbsp;</p> 

 
 # 输入格式 
<p>　　第一行为N，表示N个需要搜集的线索(N&nbsp;&lt;=&nbsp;1000)<br />
　　接下来N行，每行两个整数ai,bi,&nbsp;分别表示Holmes，Watson搜集第i个线索所需要的时间。（&nbsp;ai,bi&nbsp;&lt;=&nbsp;15&nbsp;）<br />
　　接下来若干行，每行两个整数x,y，表示得到x,&nbsp;同时能够得到y。<br />
&nbsp;</p> 

 
 # 输出格式 
<p>　　一个整数，即搜集所有线索的最小耗时。<br />
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
<tr><td>holmes.in
2
5 6
3 9
1 2
</td><td>holmes.out
5
</td></tr></table>
