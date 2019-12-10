# 

 
 # 题目背景 
<p>【温馨提示】下面有翻译</p>

<p>【原文】</p>

<p>A&nbsp;number&nbsp;of&nbsp;schools&nbsp;are&nbsp;connected&nbsp;to&nbsp;a&nbsp;computer&nbsp;network.&nbsp;Agreements&nbsp;have&nbsp;been&nbsp;developed&nbsp;among&nbsp;those&nbsp;schools:&nbsp;each&nbsp;school&nbsp;maintains&nbsp;a&nbsp;list&nbsp;of&nbsp;schools&nbsp;to&nbsp;which&nbsp;it&nbsp;distributes&nbsp;software&nbsp;(the&nbsp;&ldquo;receiving&nbsp;schools&rdquo;).&nbsp;Note&nbsp;that&nbsp;if&nbsp;B&nbsp;is&nbsp;in&nbsp;the&nbsp;distribution&nbsp;list&nbsp;of&nbsp;school&nbsp;A,&nbsp;then&nbsp;A&nbsp;does&nbsp;not&nbsp;necessarily&nbsp;appear&nbsp;in&nbsp;the&nbsp;list&nbsp;of&nbsp;school&nbsp;B.</p>

<p>You&nbsp;are&nbsp;to&nbsp;write&nbsp;a&nbsp;program&nbsp;that&nbsp;computes&nbsp;the&nbsp;minimal&nbsp;number&nbsp;of&nbsp;schools&nbsp;that&nbsp;must&nbsp;receive&nbsp;a&nbsp;copy&nbsp;of&nbsp;the&nbsp;new&nbsp;software&nbsp;in&nbsp;order&nbsp;for&nbsp;the&nbsp;software&nbsp;to&nbsp;reach&nbsp;all&nbsp;schools&nbsp;in&nbsp;the&nbsp;network&nbsp;according&nbsp;to&nbsp;the&nbsp;agreement&nbsp;(Subtask&nbsp;A).&nbsp;As&nbsp;a&nbsp;further&nbsp;task,&nbsp;we&nbsp;want&nbsp;to&nbsp;ensure&nbsp;that&nbsp;by&nbsp;sending&nbsp;the&nbsp;copy&nbsp;of&nbsp;new&nbsp;software&nbsp;to&nbsp;an&nbsp;arbitrary&nbsp;school,&nbsp;this&nbsp;software&nbsp;will&nbsp;reach&nbsp;all&nbsp;schools&nbsp;in&nbsp;the&nbsp;network.&nbsp;To&nbsp;achieve&nbsp;this&nbsp;goal&nbsp;we&nbsp;may&nbsp;have&nbsp;to&nbsp;extend&nbsp;the&nbsp;lists&nbsp;of&nbsp;receivers&nbsp;by&nbsp;new&nbsp;members.&nbsp;Compute&nbsp;the&nbsp;minimal&nbsp;number&nbsp;of&nbsp;extensions&nbsp;that&nbsp;have&nbsp;to&nbsp;be&nbsp;made&nbsp;so&nbsp;that&nbsp;whatever&nbsp;school&nbsp;we&nbsp;send&nbsp;the&nbsp;new&nbsp;software&nbsp;to,&nbsp;it&nbsp;will&nbsp;reach&nbsp;all&nbsp;other&nbsp;schools&nbsp;(Subtask&nbsp;B).&nbsp;One&nbsp;extension&nbsp;means&nbsp;introducing&nbsp;one&nbsp;new&nbsp;member&nbsp;into&nbsp;the&nbsp;list&nbsp;of&nbsp;receivers&nbsp;of&nbsp;one&nbsp;school.</p>

<h3>Input&nbsp;Data</h3>

<p>The&nbsp;first&nbsp;line&nbsp;of&nbsp;file&nbsp;INPUT.TXT&nbsp;contains&nbsp;an&nbsp;integer&nbsp;N:&nbsp;the&nbsp;number&nbsp;of&nbsp;schools&nbsp;in&nbsp;the&nbsp;network&nbsp;(2&lt;=N&lt;=100).&nbsp;The&nbsp;schools&nbsp;are&nbsp;identified&nbsp;by&nbsp;the&nbsp;first&nbsp;N&nbsp;positive&nbsp;integers.&nbsp;Each&nbsp;of&nbsp;the&nbsp;next&nbsp;N&nbsp;lines&nbsp;describes&nbsp;a&nbsp;list&nbsp;of&nbsp;receivers.&nbsp;The&nbsp;line&nbsp;i+1&nbsp;contains&nbsp;the&nbsp;identifiers&nbsp;of&nbsp;the&nbsp;receivers&nbsp;of&nbsp;school&nbsp;i.&nbsp;Each&nbsp;list&nbsp;ends&nbsp;with&nbsp;a&nbsp;0.&nbsp;An&nbsp;empty&nbsp;list&nbsp;contains&nbsp;a&nbsp;0&nbsp;alone&nbsp;in&nbsp;the&nbsp;line.</p>

<h3>Output&nbsp;Data</h3>

<p>Your&nbsp;program&nbsp;should&nbsp;write&nbsp;two&nbsp;lines&nbsp;to&nbsp;the&nbsp;file&nbsp;OUTPUT.TXT.&nbsp;The&nbsp;first&nbsp;line&nbsp;should&nbsp;contain&nbsp;one&nbsp;positive&nbsp;integer:&nbsp;the&nbsp;solution&nbsp;of&nbsp;subtask&nbsp;A.&nbsp;The&nbsp;second&nbsp;line&nbsp;should&nbsp;contain&nbsp;the&nbsp;solution&nbsp;of&nbsp;subtask&nbsp;B.&nbsp;</p> 

 
 # 题目描述 
<p>一些学校联接在一个计算机网络上，学校之间存在软件支援协议，每个学校都有它应支援的学校名单（A学校支援学校B，并不表示B学校一定支援学校A）。当某校获得一个新软件时，无论是直接获得还是通过网络获得，该校都应立即将这个软件通过网络传送给它应支援的学校。因此，一个新软件若想让所有联接在网络上的学校都能使用，只需将其提供给一些学校即可。</p>

<h3>子任务A</h3>

<p>&nbsp;&nbsp;&nbsp;&nbsp;请编一个程序，根据学校间支援协议（各个学校的支援名单），计算最少需要将一个新软件直接提供给多少个学校，才能使软件能够通过网络被传送到所有学校。</p>

<h3>任务B</h3>

<p>&nbsp;&nbsp;&nbsp;&nbsp;如果充许在原有支援协议上添加新的支援关系，则总可以形成一种新的协议，使得此时只需将一个新软件提供给任何一个学校，其他所有学校就都可以通过网络获得该软件。编程计算最少需要添加几条新的支援关系。</p> 

 
 # 输入格式 
<p>文件INPUT.TXT的第一行是一个正整数N（2&lt;=N&lt;=100），表示与网络联接的学校总数，随后N行分别表示每个学校要支援的学校。即：第I＋1行表示第I号学校要支援的所有学校代号，最后以0结束。如果一个学校不支援任何其他学校，相应行只会有一个0。一行中若有多个数字，数字之间以一个空格分隔。</p> 

 
 # 输出格式 
<p>文件名为OUTPUT.TXT，包含两行。第一行是一个正整数，表示子任务A的解。第二行是一个正整数，表示子任务B的解。</p> 

 
 # 提示 
<p>如有侵权，请联系管理员删题！</p> 
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
2 4 3 0
4 5 0		
0		
0		
1 0		
</td><td>1
2</td></tr></table>
