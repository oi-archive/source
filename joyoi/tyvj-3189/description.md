# 

 
 # 题目背景 
<p>无</p> 

 
 # 题目描述 
<p>农夫约翰在他的农场有&nbsp;N座山&nbsp;(1&nbsp;&lt;&nbsp;=&nbsp;N&nbsp;&lt;&nbsp;=&nbsp;1,000），每座高度为0..100。在冬天，因为有这山有丰富的雪，&nbsp;FJ经常经营一个滑雪训练营。</p>

<p>不幸的是,FJ刚刚发现了一个新的税收,他正在评估在明年农场作为滑雪训练营的支出。&nbsp;&nbsp;当仔细阅读了规则，他发现滑雪训练营的税收标准是最高和最低的山丘之间的差要比17大。因此，如果他缩短他高的山，增加他矮的山的高度，&nbsp;FJ能够避税只要最高和最低的山丘之间新的差至多为17。</p>

<p>如果改变X单位山的高度花X&nbsp;^&nbsp;2个单位的钱，求FJ将需要支付的最低金额？&nbsp;FJ只愿意用一个整数量来改变每个山的高度。</p> 

 
 # 输入格式 
<p>*&nbsp;第&nbsp;1&nbsp;行:&nbsp;一个整数&nbsp;N.</p>

<p>*&nbsp;第&nbsp;2..1+N&nbsp;行:&nbsp;每一行包含一个小山的高度。</p> 

 
 # 输出格式 
<p>*&nbsp;第&nbsp;1&nbsp;行:&nbsp;FJ需要支付来修改他的小山海拔最大与最小之间的差至多为17个单位的最低金额。</p> 

 
 # 提示 
<p><strong>输入说明</strong><strong>:</strong></p>

<p>FJ的农场有5座山，分别是海拔1，4，20，21，和24。</p>

<p><strong>输出说明</strong><strong>:</strong></p>

<p>FJ保持高度4，20，和21。他把高1的山加到高度4（成本=3^2=9）。他把高24的山改为高21的山，也以3^2=9的代价。</p> 
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
1
4
20
21
24
</td><td>18
</td></tr></table>
