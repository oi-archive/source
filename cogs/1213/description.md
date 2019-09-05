# 题目描述


<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【题目描述】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"></span> 
</p>
<p style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;color:#333333;font-size:14.399999618530273px;text-align:left;background-color:#FFFFFF;">
	有一本书总共有n页，你可以查询n次，而且它告诉你
</p>
<p style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;color:#333333;font-size:14.399999618530273px;text-align:left;background-color:#FFFFFF;">
	每一次可以查询的页码为ai &lt;= i &lt;= bi,即从第ai页到第bi页。问你最少可以查询几次能把这本书所有
</p>
<p style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;color:#333333;font-size:14.399999618530273px;text-align:left;background-color:#FFFFFF;">
	的页码都可以查询到。
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;background-color:#FFE500;color:#003399;">保證一定存在解。</span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输入格式】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:14.399999618530273px;line-height:normal;background-color:#FFFFFF;">the first line is a number N (1&lt;=N&lt;=5000), indicating the number of pages of the book. Then n lines follows. On the i-th line, there will be two integers ai and bi (ai&lt;=i&lt;=bi)</span><span></span></span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输出格式】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:14.399999618530273px;line-height:normal;background-color:#FFFFFF;"> a single integer, which is the minimum number of queries to get all the signatures.</span></span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例输入】</span> 
</h3>
<pre>輸入樣例1:
3
1 1
2 2
3 3
輸入樣例2:
3 
1 1
1 3
3 3 
</pre>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例输出】</span> 
</h3>
<pre>輸出樣例1:3
輸出樣例2:1
</pre>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【提示】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;line-height:19.200000762939453px;background-color:#FFE500;color:#003399;">看不懂</span><span style="background-color:#FFE500;color:#003399;"></span><span style="background-color:#FFE500;color:#003399;">英语的请面壁1小时。</span></span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;background-color:#E53333;color:#FFFFFF;"><span style="background-color:#E53333;color:#FFFFFF;">本题是为了练习<a href="../problem/problem.php?pid=521" target="_blank">NOIP2010《引水入城》</a>一题的第二问。</span></span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【来源】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:16px;font-weight:bold;line-height:normal;background-color:#EEEEEE;">ZOJ Problem Set - 3197 <span style="color:#0000FF;font-family:&#39;WenQuanYi Micro Hei Mono&#39;, &#39;WenQuanYi Micro Hei&#39;, &#39;Microsoft Yahei Mono&#39;, &#39;Microsoft Yahei&#39;, sans-serif;font-size:24px;line-height:normal;background-color:#FFFFFF;"><a href="http://acm.zju.edu.cn/onlinejudge/showProblem.do?problemCode=3197" target="_blank">Google Book</a></span></span></span> 
</p>
<p>
	<br/>
</p>
