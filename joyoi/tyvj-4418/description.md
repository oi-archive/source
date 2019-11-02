# 

 
 # 题目描述 
<p>【原文】</p>

<p>A&nbsp;factory&nbsp;is&nbsp;running&nbsp;a&nbsp;production&nbsp;line.&nbsp;Two&nbsp;operations&nbsp;have&nbsp;to&nbsp;be&nbsp;performed&nbsp;on&nbsp;each&nbsp;job:&nbsp;first&nbsp;operation&nbsp;&quot;A&quot;,&nbsp;then&nbsp;operation&nbsp;&quot;B&quot;.&nbsp;There&nbsp;is&nbsp;a&nbsp;certain&nbsp;number&nbsp;of&nbsp;machines&nbsp;capable&nbsp;of&nbsp;performing&nbsp;each&nbsp;operation.&nbsp;Figure&nbsp;1&nbsp;shows&nbsp;the&nbsp;organisation&nbsp;of&nbsp;the&nbsp;production&nbsp;line&nbsp;that&nbsp;works&nbsp;as&nbsp;follows.&nbsp;A&nbsp;type&nbsp;&quot;A&quot;&nbsp;machine&nbsp;takes&nbsp;a&nbsp;job&nbsp;from&nbsp;the&nbsp;input&nbsp;container,&nbsp;performs&nbsp;operation&nbsp;&quot;A&quot;&nbsp;and&nbsp;puts&nbsp;the&nbsp;job&nbsp;into&nbsp;the&nbsp;intermediate&nbsp;container.&nbsp;A&nbsp;type&nbsp;&quot;B&quot;&nbsp;machine&nbsp;takes&nbsp;a&nbsp;job&nbsp;from&nbsp;the&nbsp;intermediate&nbsp;container,&nbsp;performs&nbsp;operation&nbsp;&quot;B&quot;&nbsp;and&nbsp;puts&nbsp;the&nbsp;job&nbsp;into&nbsp;the&nbsp;output&nbsp;container.&nbsp;All&nbsp;machines&nbsp;can&nbsp;work&nbsp;in&nbsp;parallel&nbsp;and&nbsp;independently&nbsp;of&nbsp;each&nbsp;other,&nbsp;and&nbsp;the&nbsp;size&nbsp;of&nbsp;each&nbsp;container&nbsp;is&nbsp;unlimited.&nbsp;The&nbsp;machines&nbsp;have&nbsp;different&nbsp;performance&nbsp;characteristics,&nbsp;a&nbsp;given&nbsp;machine&nbsp;works&nbsp;with&nbsp;a&nbsp;given&nbsp;processing&nbsp;time.</p>

<p>Give&nbsp;the&nbsp;earliest&nbsp;time&nbsp;operation&nbsp;&ldquo;A&rdquo;&nbsp;can&nbsp;be&nbsp;completed&nbsp;for&nbsp;all&nbsp;N&nbsp;jobs&nbsp;provided&nbsp;that&nbsp;the&nbsp;jobs&nbsp;are&nbsp;available&nbsp;at&nbsp;time&nbsp;0.&nbsp;(Subtask&nbsp;A).&nbsp;Also&nbsp;compute&nbsp;the&nbsp;minimal&nbsp;amount&nbsp;of&nbsp;time&nbsp;that&nbsp;is&nbsp;necessary&nbsp;to&nbsp;perform&nbsp;both&nbsp;operations&nbsp;on&nbsp;N&nbsp;jobs&nbsp;(Subtask&nbsp;B).</p>

<p>【翻译】</p>

<p>某工厂出产一种产品，该产品需要两道工序，第一道为工序A，第二道为工序B。该工厂的每一台机器要么完成工序A，要么完成工序B，分别称之为A类机器和B类机器。如图1所示，A类机器从原材料库中提取原料，加工后放入半成品库，B类机器从半成品库中提取半成品，把它加工为成品，并放入成品库，共中每个库的容量都是不受限的，工厂的所有机器均可以并行独立地工作，由于每台机器的速度不同，完成自己相应工序所需时间就可能不同。</p>

<p><strong>子任务A：</strong></p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;请编一程序，计算要完成N个半成品（工序A）最少需要多少时间。</p>

<p><strong>子任务B：</strong></p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;请编一程序，计算要完成N个成品（工序A＋工序B）最少需要多少时间。</p> 

 
 # 输入格式 
<p>【原文】</p>

<p>The&nbsp;file&nbsp;INPUT.TXT&nbsp;contains&nbsp;positive&nbsp;integers&nbsp;in&nbsp;five&nbsp;lines.&nbsp;The&nbsp;first&nbsp;line&nbsp;contains&nbsp;N,&nbsp;the&nbsp;number&nbsp;of&nbsp;jobs&nbsp;(1&lt;=N&lt;=1000).&nbsp;On&nbsp;the&nbsp;second&nbsp;line,&nbsp;the&nbsp;number&nbsp;M1&nbsp;of&nbsp;type&nbsp;&quot;A&quot;&nbsp;machines&nbsp;(1&lt;=M1&lt;=30)&nbsp;is&nbsp;given.&nbsp;In&nbsp;the&nbsp;third&nbsp;line&nbsp;there&nbsp;are&nbsp;M1&nbsp;integers,&nbsp;the&nbsp;job&nbsp;processing&nbsp;times&nbsp;of&nbsp;each&nbsp;type&nbsp;&quot;A&quot;&nbsp;machine.&nbsp;The&nbsp;fourth&nbsp;and&nbsp;the&nbsp;fifth&nbsp;line&nbsp;contain&nbsp;the&nbsp;number&nbsp;M2&nbsp;of&nbsp;type&nbsp;&quot;B&quot;&nbsp;machines&nbsp;(1&lt;=M2&lt;=30)&nbsp;and&nbsp;the&nbsp;job&nbsp;processing&nbsp;times&nbsp;of&nbsp;each&nbsp;type&nbsp;&quot;B&quot;&nbsp;machine,&nbsp;respectively.&nbsp;The&nbsp;job&nbsp;processing&nbsp;time&nbsp;is&nbsp;measured&nbsp;in&nbsp;units&nbsp;of&nbsp;time,&nbsp;which&nbsp;includes&nbsp;the&nbsp;time&nbsp;needed&nbsp;for&nbsp;taking&nbsp;a&nbsp;job&nbsp;from&nbsp;a&nbsp;container&nbsp;before&nbsp;processing&nbsp;and&nbsp;putting&nbsp;it&nbsp;into&nbsp;a&nbsp;container&nbsp;after&nbsp;processing.&nbsp;Each&nbsp;processing&nbsp;time&nbsp;is&nbsp;at&nbsp;least&nbsp;1&nbsp;and&nbsp;at&nbsp;most&nbsp;20.</p>

<p>【翻译】</p>

<p>文件INPUT.TXT包括5行正整数，第一行是所需完成的成品个数（1&lt;=N&lt;=1000）。第二行是A类机器的数目M1（1&lt;=M1&lt;=30）。第三行有M1个数，依次表示每台A类机器完成工序A所需时间。第四行是B类机器的数目M2（1&lt;=M2&lt;=30）。第五行有M2个数，依次表示每台B类机器完成工序B所需时间。所有工序所需时间最大为20，最小为1。</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;每道工序开始时从库中取物品的时间和结束时放物品入库的时间都已经包含在加工时间内。</p>

<p>&nbsp;&nbsp;&nbsp;&nbsp;一行中若有多个数字，两数之间以一个空格分隔。</p> 

 
 # 输出格式 
<p>【原文】</p>

<p>Your&nbsp;program&nbsp;should&nbsp;write&nbsp;two&nbsp;lines&nbsp;to&nbsp;file&nbsp;OUTPUT.TXT.&nbsp;The&nbsp;first&nbsp;line&nbsp;should&nbsp;contain&nbsp;one&nbsp;positive&nbsp;integer:&nbsp;the&nbsp;solution&nbsp;of&nbsp;subtask&nbsp;A.&nbsp;The&nbsp;second&nbsp;line&nbsp;should&nbsp;contain&nbsp;the&nbsp;solution&nbsp;of&nbsp;subtask&nbsp;B.&nbsp;</p>

<p>【翻译】</p>

<p>输出文件名为OUTPUT.TXT，包含两行。第一行是一个正整数，表示子任务A的解。第二行也是一个正整数，表示子任务B的解。</p> 
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
2
1 1		
3		
3 1 4		
</td><td>3
5</td></tr></table>
