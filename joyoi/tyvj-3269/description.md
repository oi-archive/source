# 

 
 # 题目背景 
<p>无</p> 

 
 # 题目描述 
<p>奶牛贝茜准备参加越野滑雪的冬季奥运会。她以每秒1米的速度开始。随着时间的推移她变得更累，速度开始减缓。</p>

<p>每次贝茜减慢，她的速度减少：第一次每秒1/2米，第二次每秒1&nbsp;/3米，依此类推。</p>

<p>你被告知贝茜在何时何地减慢速度。比如：</p>

<p>T&nbsp;17</p>

<p>也就是说，贝茜在特定的时间减慢-&nbsp;这里是指比赛开始后17秒进行减速。像这样的事件：</p>

<p>D&nbsp;10</p>

<p>也就是说，贝茜在特定的时间减慢-&nbsp;这里是指比赛开始后10米进行减速。</p>

<p>给出N个这样的事件清单（1&lt;=&nbsp;N&lt;=10,000），请计算所需的时间，贝茜行完整个路程的时间，以秒为单位。</p> 

 
 # 输入格式 
<p>*&nbsp;第&nbsp;1&nbsp;行:&nbsp;整数N.</p>

<p>*&nbsp;第&nbsp;2..1+N&nbsp;行:&nbsp;每一行的形式为&ldquo;T&nbsp;x&rdquo;或&ldquo;D&nbsp;x&rdquo;的，表示时间件或距离。在这两种情况下，x是一个整数，它是保证前贝茜达到总距离的1公里的事件。可能同时发生多个事件，导致贝茜减缓相当多的一次。事件可能不会按顺序列出。</p> 

 
 # 输出格式 
<p>*&nbsp;第&nbsp;1&nbsp;行:&nbsp;贝茜前往1公里所需的时间。</p> 

 
 # 提示 
<p><strong>输入说明</strong><strong>:</strong></p>

<p>贝茜在时间t&nbsp;=30，并在距离d=&nbsp;10减慢。</p>

<p><strong>输出说明</strong><strong>:</strong></p>

<p>贝茜先走10米，1米/秒，用10秒钟。然后，她减慢至1/2米/秒，同时20秒出行接下来的10米。然后，她到达30秒大关，在那里她减速为1/3米/秒。因此，剩下的980米带她用去980*3=2940秒。因此，总的时间是10+&nbsp;20&nbsp;+2940=2970。</p> 
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
<tr><td>2
T 30
D 10
</td><td>2970
</td></tr></table>
