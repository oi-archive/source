# 

 
 # 题目描述 
<p>设<img alt="" src="/source/joyoi/tyvj-2123/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_dD1iXntjfQ==.latex" />，求<img alt="" src="/source/joyoi/tyvj-2123/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_YV57dH0lMjBcbW9kJTIwbQ==.latex" />​</p> 

 
 # 输入格式 
<p style="word-wrap: break-word; margin: 5px 0px; color: rgb(0, 0, 0); font-family: 'sans serif', tahoma, verdana, helvetica; font-size: 12px; line-height: 18px;"><span style="font-size: 14px;"><span style="font-family: 'Microsoft YaHei';">第一行一个整数k，代表数据种类。</span></span></p>

<p style="word-wrap: break-word; margin: 5px 0px; color: rgb(0, 0, 0); font-family: 'sans serif', tahoma, verdana, helvetica; font-size: 12px; line-height: 18px;"><span style="font-size: 14px;"><span style="font-family: 'Microsoft YaHei';">第二行四个整数，分别为a,b,c,m</span></span></p> 

 
 # 输出格式 
<p><span style="color: rgb(0, 0, 0); font-family: 'Microsoft YaHei'; font-size: 14px; line-height: 21px;">输出一行一个整数，代表答案</span></p> 

 
 # 提示 
<p style="word-wrap: break-word; margin: 5px 0px; color: rgb(0, 0, 0); font-family: 'sans serif', tahoma, verdana, helvetica; font-size: 12px; line-height: 18px;"><span style="font-size: 14px;"><span style="font-family: 'Microsoft YaHei';"><span style="line-height: 21px;">对于前20%的数据，k=1，<img alt="" src="/source/joyoi/tyvj-2123/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_MVxsZXElMjBjXGxlcSUyMDEwMDA=.latex" />&nbsp;，&nbsp;b最大1000位</span></span></span></p>

<p style="word-wrap: break-word; margin: 5px 0px; color: rgb(0, 0, 0); font-family: 'sans serif', tahoma, verdana, helvetica; font-size: 12px; line-height: 18px;"><span style="font-size: 14px;"><span style="font-family: 'Microsoft YaHei';">对于另外80%的数据，k=2或k=3，<span style="line-height: 21px;"><img alt="" src="/source/joyoi/tyvj-2123/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_MVxsZXElMjBiJTIwXGxlcSUyMDJeezMwfQ==.latex" />，<img alt="" src="/source/joyoi/tyvj-2123/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_MVxsZXElMjBjXGxlcSUyMDEwXnt4fQ==.latex" />，</span></span></span><span style="color: rgb(0, 0, 0); font-family: 'Microsoft YaHei'; font-size: 14px; line-height: 21px;">保证</span><img alt="" src="/source/joyoi/tyvj-2123/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_KGEsbSk9MQ==.latex" style="color: rgb(0, 0, 0); font-family: 'Microsoft YaHei'; font-size: 14px; line-height: 21px;" />即a,m互质</p>

<p style="word-wrap: break-word; margin: 5px 0px; color: rgb(0, 0, 0); font-family: 'sans serif', tahoma, verdana, helvetica; font-size: 12px; line-height: 18px;"><span style="font-size: 14px;"><span style="font-family: 'Microsoft YaHei';"><span style="line-height: 21px;">对于其中40%的数据，k=2，<img alt="" src="/source/joyoi/tyvj-2123/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_bQ==.latex" />是质数，等于<img alt="" src="/source/joyoi/tyvj-2123/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_MTAwMDAwMDA3.latex" />，其余数据k=3</span></span></span></p>

<p style="word-wrap: break-word; margin: 5px 0px; color: rgb(0, 0, 0); font-family: 'sans serif', tahoma, verdana, helvetica; font-size: 12px; line-height: 18px;"><span style="font-size: 14px;"><span style="font-family: 'Microsoft YaHei';"><span style="line-height: 21px;">​</span></span></span><span style="color: rgb(0, 0, 0); font-family: 'Microsoft YaHei'; font-size: 14px; line-height: 21px;">对于全部数据，<img alt="" src="/source/joyoi/tyvj-2123/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_eCUyMD0lMjAxMF57NX0=.latex" />，<img alt="" src="/source/joyoi/tyvj-2123/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_MVxsZXElMjBtXGxlcTEwMDAwMDAwNw==.latex" />,&nbsp;<img alt="" src="/source/joyoi/tyvj-2123/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_MVxsZXElMjBhXGxlcSUyMDJeezMwfQ==.latex" />​</span></p> 
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
<tr><td>1
281514 4280159603401295423469474122349607303871805666321582754879978596293118087683730302398266977801640430 10 77194755
</td><td>15397911</td></tr><tr><td>2
2 3 3 100000007</td><td>34217721</td></tr></table>
