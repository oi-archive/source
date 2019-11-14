# 

 
 # 题目背景 
<p>这里有一箱子硬币，它们看上去似乎是相同的，但实际上面朝上的概率都不同。</p> 

 
 # 题目描述 
<p>现在，箱子里有n枚硬币，第i枚硬币面朝上的概率为<img align="absmiddle" alt="\small p_i" src="/source/joyoi/tyvj-3788/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_XHNtYWxsJmFtcDtzcGFjZTtwX2k=.latex" />，请求出至少u枚、最多不超过v枚硬币朝上的概率。</p> 

 
 # 输入格式 
<p>一行以空格分隔的n和k；<br />
一行以空格分隔的<img align="absmiddle" alt="\small p_1, p_2, \ldots, p_n" src="/source/joyoi/tyvj-3788/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_XHNtYWxsJmFtcDtzcGFjZTtwXzEsJmFtcDtzcGFjZTtwXzIsJmFtcDtzcGFjZTtcbGRvdHMsJmFtcDtzcGFjZTtwX24=.latex" />，<img align="absmiddle" alt="\small p_i" src="/source/joyoi/tyvj-3788/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_XHNtYWxsJmFtcDtzcGFjZTtwX2k=.latex" />为3位小数。</p> 

 
 # 输出格式 
<p>至少u枚、最多不超过v枚硬币朝上的概率，精确到小数点后6位。</p> 

 
 # 提示 
<p>50%的数据，<img align="absmiddle" alt="\small 1 \leq n \leq 10,000" src="/source/joyoi/tyvj-3788/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_XHNtYWxsJmFtcDtzcGFjZTsxJmFtcDtzcGFjZTtcbGVxJmFtcDtzcGFjZTtuJmFtcDtzcGFjZTtcbGVxJmFtcDtzcGFjZTsxMCwwMDA=.latex" />；<br />
100%的数据，<img align="absmiddle" alt="\small 1 \leq n \leq 25,000" src="/source/joyoi/tyvj-3788/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_XHNtYWxsJmFtcDtzcGFjZTsxJmFtcDtzcGFjZTtcbGVxJmFtcDtzcGFjZTtuJmFtcDtzcGFjZTtcbGVxJmFtcDtzcGFjZTsyNSwwMDA=.latex" />，<img align="absmiddle" alt="\small 0 \leq u, v \leq n" src="/source/joyoi/tyvj-3788/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_XHNtYWxsJmFtcDtzcGFjZTswJmFtcDtzcGFjZTtcbGVxJmFtcDtzcGFjZTt1LCZhbXA7c3BhY2U7diZhbXA7c3BhY2U7XGxlcSZhbXA7c3BhY2U7bg==.latex" />，<img align="absmiddle" alt="\small 0.0 \leq p_i \leq 1.0" src="/source/joyoi/tyvj-3788/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_XHNtYWxsJmFtcDtzcGFjZTswLjAmYW1wO3NwYWNlO1xsZXEmYW1wO3NwYWNlO3BfaSZhbXA7c3BhY2U7XGxlcSZhbXA7c3BhY2U7MS4w.0" />。</p> 
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
<tr><td>6 2 4
0.333 0.697 0.666 0.226 0.675 0.154</td><td>0.831689</td></tr></table>
