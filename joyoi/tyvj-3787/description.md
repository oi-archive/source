# 

 
 # 题目背景 
<p>大家都听说过斐波那契数列吧。<br />
<img align="absmiddle" alt="$$ F_{0}=0, F_{1}=1, F_{n+2} = F_{n+1} + F_{n} \space\space (n \in \mathbb{N^*}) $$" src="/source/joyoi/tyvj-3787/img/eb1d5c1b99fe6ab685d865db3223a0fd.latex" /><br />
上述的数式是斐波那契数列的递推式。我们在原有的定义上追加：<br />
<img align="absmiddle" alt="$$ F_{n-2} = F_{n} - F_{n-1} \space\space (n \in \mathbb{Z}) $$" src="/source/joyoi/tyvj-3787/img/b7cc317bca4d6f391677683d589634d2.latex" /><br />
于是有&nbsp;<img align="absmiddle" alt="$F_{-6}=-8$" src="/source/joyoi/tyvj-3787/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_JEZfey02fT0tOCQ=.latex" />、<img align="absmiddle" alt="$F_{-3}=2$" src="/source/joyoi/tyvj-3787/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_JEZfey0zfT0yJA==.latex" />&nbsp;之类的项。</p> 

 
 # 题目描述 
<p>现给定n和m，请求出<img align="absmiddle" alt="$F_{n}$" src="/source/joyoi/tyvj-3787/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_JEZfe259JA==.latex" />除以m的最小正余数（即&nbsp;<img align="absmiddle" alt="$F_{n} \mod m$" src="/source/joyoi/tyvj-3787/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_JEZfe259JmFtcDtzcGFjZTtcbW9kJmFtcDtzcGFjZTttJA==.latex" />）。</p> 

 
 # 输入格式 
<p>以空格分隔的n和m。</p> 

 
 # 输出格式 
<p><img align="absmiddle" alt="$F_{n} \mod m$" src="/source/joyoi/tyvj-3787/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_JEZfe259JmFtcDtzcGFjZTtcbW9kJmFtcDtzcGFjZTttJA==.latex" />&nbsp;的值。</p> 

 
 # 提示 
<p>20%的数据，<img align="absmiddle" alt="\small -10^5 \leq n \leq 10^5" src="/source/joyoi/tyvj-3787/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_XHNtYWxsJmFtcDtzcGFjZTstMTBeNSZhbXA7c3BhY2U7XGxlcSZhbXA7c3BhY2U7biZhbXA7c3BhY2U7XGxlcSZhbXA7c3BhY2U7MTBeNQ==.latex" />，<img align="absmiddle" alt="\small 2 \leq m \leq 10^4" src="/source/joyoi/tyvj-3787/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_XHNtYWxsJmFtcDtzcGFjZTsyJmFtcDtzcGFjZTtcbGVxJmFtcDtzcGFjZTttJmFtcDtzcGFjZTtcbGVxJmFtcDtzcGFjZTsxMF40.latex" />；<br />
40%的数据，<img align="absmiddle" alt="\small -10^{7} \leq n \leq 10^{7}" src="/source/joyoi/tyvj-3787/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_XHNtYWxsJmFtcDtzcGFjZTstMTBeezd9JmFtcDtzcGFjZTtcbGVxJmFtcDtzcGFjZTtuJmFtcDtzcGFjZTtcbGVxJmFtcDtzcGFjZTsxMF57N30=.latex" />；<br />
60%的数据，<img align="absmiddle" alt="\small -10^{18} \leq n \leq 10^{18}" src="/source/joyoi/tyvj-3787/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_XHNtYWxsJmFtcDtzcGFjZTstMTBeezE4fSZhbXA7c3BhY2U7XGxlcSZhbXA7c3BhY2U7biZhbXA7c3BhY2U7XGxlcSZhbXA7c3BhY2U7MTBeezE4fQ==.latex" />；<br />
100%的数据，<img align="absmiddle" alt="\small -10^{512} \leq n \leq 10^{512}" src="/source/joyoi/tyvj-3787/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_XHNtYWxsJmFtcDtzcGFjZTstMTBeezUxMn0mYW1wO3NwYWNlO1xsZXEmYW1wO3NwYWNlO24mYW1wO3NwYWNlO1xsZXEmYW1wO3NwYWNlOzEwXns1MTJ9.latex" />，<img align="absmiddle" alt="\small 2 \leq m \leq 10^{9}" src="/source/joyoi/tyvj-3787/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_XHNtYWxsJmFtcDtzcGFjZTsyJmFtcDtzcGFjZTtcbGVxJmFtcDtzcGFjZTttJmFtcDtzcGFjZTtcbGVxJmFtcDtzcGFjZTsxMF57OX0=.latex" />。</p> 
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
<tr><td>-18068520 418482411</td><td>159352869</td></tr></table>
