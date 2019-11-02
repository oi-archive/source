# 

 
 # 题目背景 
<p>POJ&nbsp;1325</p> 

 
 # 题目描述 
<p>【原文】</p>

<p>As&nbsp;we&nbsp;all&nbsp;know,&nbsp;machine&nbsp;scheduling&nbsp;is&nbsp;a&nbsp;very&nbsp;classical&nbsp;problem&nbsp;in&nbsp;computer&nbsp;science&nbsp;and&nbsp;has&nbsp;been&nbsp;studied&nbsp;for&nbsp;a&nbsp;very&nbsp;long&nbsp;history.&nbsp;Scheduling&nbsp;problems&nbsp;differ&nbsp;widely&nbsp;in&nbsp;the&nbsp;nature&nbsp;of&nbsp;the&nbsp;constraints&nbsp;that&nbsp;must&nbsp;be&nbsp;satisfied&nbsp;and&nbsp;the&nbsp;type&nbsp;of&nbsp;schedule&nbsp;desired.&nbsp;Here&nbsp;we&nbsp;consider&nbsp;a&nbsp;2-machine&nbsp;scheduling&nbsp;problem.</p>

<p>There&nbsp;are&nbsp;two&nbsp;machines&nbsp;A&nbsp;and&nbsp;B.&nbsp;Machine&nbsp;A&nbsp;has&nbsp;n&nbsp;kinds&nbsp;of&nbsp;working&nbsp;modes,&nbsp;which&nbsp;is&nbsp;called&nbsp;mode_0,&nbsp;mode_1,&nbsp;...,&nbsp;mode_n-1,&nbsp;likewise&nbsp;machine&nbsp;B&nbsp;has&nbsp;m&nbsp;kinds&nbsp;of&nbsp;working&nbsp;modes,&nbsp;mode_0,&nbsp;mode_1,&nbsp;...&nbsp;,&nbsp;mode_m-1.&nbsp;At&nbsp;the&nbsp;beginning&nbsp;they&nbsp;are&nbsp;both&nbsp;work&nbsp;at&nbsp;mode_0.</p>

<p>For&nbsp;k&nbsp;jobs&nbsp;given,&nbsp;each&nbsp;of&nbsp;them&nbsp;can&nbsp;be&nbsp;processed&nbsp;in&nbsp;either&nbsp;one&nbsp;of&nbsp;the&nbsp;two&nbsp;machines&nbsp;in&nbsp;particular&nbsp;mode.&nbsp;For&nbsp;example,&nbsp;job&nbsp;0&nbsp;can&nbsp;either&nbsp;be&nbsp;processed&nbsp;in&nbsp;machine&nbsp;A&nbsp;at&nbsp;mode_3&nbsp;or&nbsp;in&nbsp;machine&nbsp;B&nbsp;at&nbsp;mode_4,&nbsp;job&nbsp;1&nbsp;can&nbsp;either&nbsp;be&nbsp;processed&nbsp;in&nbsp;machine&nbsp;A&nbsp;at&nbsp;mode_2&nbsp;or&nbsp;in&nbsp;machine&nbsp;B&nbsp;at&nbsp;mode_4,&nbsp;and&nbsp;so&nbsp;on.&nbsp;Thus,&nbsp;for&nbsp;job&nbsp;i,&nbsp;the&nbsp;constraint&nbsp;can&nbsp;be&nbsp;represent&nbsp;as&nbsp;a&nbsp;triple&nbsp;(i,&nbsp;x,&nbsp;y),&nbsp;which&nbsp;means&nbsp;it&nbsp;can&nbsp;be&nbsp;processed&nbsp;either&nbsp;in&nbsp;machine&nbsp;A&nbsp;at&nbsp;mode_x,&nbsp;or&nbsp;in&nbsp;machine&nbsp;B&nbsp;at&nbsp;mode_y.</p>

<p>Obviously,&nbsp;to&nbsp;accomplish&nbsp;all&nbsp;the&nbsp;jobs,&nbsp;we&nbsp;need&nbsp;to&nbsp;change&nbsp;the&nbsp;machine&#39;s&nbsp;working&nbsp;mode&nbsp;from&nbsp;time&nbsp;to&nbsp;time,&nbsp;but&nbsp;unfortunately,&nbsp;the&nbsp;machine&#39;s&nbsp;working&nbsp;mode&nbsp;can&nbsp;only&nbsp;be&nbsp;changed&nbsp;by&nbsp;restarting&nbsp;it&nbsp;manually.&nbsp;By&nbsp;changing&nbsp;the&nbsp;sequence&nbsp;of&nbsp;the&nbsp;jobs&nbsp;and&nbsp;assigning&nbsp;each&nbsp;job&nbsp;to&nbsp;a&nbsp;suitable&nbsp;machine,&nbsp;please&nbsp;write&nbsp;a&nbsp;program&nbsp;to&nbsp;minimize&nbsp;the&nbsp;times&nbsp;of&nbsp;restarting&nbsp;machines.</p>

<p>【翻译】</p>

<p>众所周知，机器调度是计算机科学中的一个非常经典的问题，已经被研究了很长时间了。调度问题由于要满足的约束以及所要求的调度类型，存在着很大的不同。本题我们考虑2-机调度问题。</p>

<p><br />
有两台机器A和B。机器A有n种工作模式，被称为mode_0,&nbsp;mode_1,&nbsp;...,&nbsp;mode_n-1，同样，机器B有m种工作模式，被称为mode_0,&nbsp;mode_1,&nbsp;...&nbsp;,&nbsp;mode_m-1。初始时两台机器在mode_0工作。<br />
给出k项工作，每项工作可以在两台机器中的任一台以特定的模式被处理。例如，job&nbsp;0可以或者在机器A以mode_3处理，或者在机器B以mode_4被处理，job&nbsp;1可以或者在机器A以mode_2处理，或者在机器B以mode_4被处理，等等。则对job&nbsp;i，约束可以表示为一个三元组(i,&nbsp;x,&nbsp;y)，表示job&nbsp;i可以在机器A以mode_&nbsp;x处理，或者在机器B以mode_&nbsp;y被处理。</p>

<p><br />
显然，要完成所有的工作，我们就要一直转换机器的工作模式，但很不幸，机器工作模式的改变只有通过手工重启来进行。通过改变工作的序列，把每项工作安排给一台适当的机器。请您编写一个最小化重启机器次数的程序。</p> 

 
 # 输入格式 
<p>【原文】</p>

<p>The&nbsp;input&nbsp;file&nbsp;for&nbsp;this&nbsp;program&nbsp;consists&nbsp;of&nbsp;several&nbsp;configurations.&nbsp;</p>

<p>The&nbsp;first&nbsp;line&nbsp;of&nbsp;one&nbsp;configuration&nbsp;contains&nbsp;three&nbsp;positive&nbsp;integers:&nbsp;n,&nbsp;m&nbsp;(n,&nbsp;m&nbsp;&lt;&nbsp;100)&nbsp;and&nbsp;k&nbsp;(k&nbsp;&lt;&nbsp;1000).&nbsp;</p>

<p>The&nbsp;following&nbsp;k&nbsp;lines&nbsp;give&nbsp;the&nbsp;constrains&nbsp;of&nbsp;the&nbsp;k&nbsp;jobs,&nbsp;each&nbsp;line&nbsp;is&nbsp;a&nbsp;triple:&nbsp;i,&nbsp;x,&nbsp;y.&nbsp;</p>

<p>The&nbsp;input&nbsp;will&nbsp;be&nbsp;terminated&nbsp;by&nbsp;a&nbsp;line&nbsp;containing&nbsp;a&nbsp;single&nbsp;zero.</p>

<p>【翻译】</p>

<p>输入包含若干测试用例。</p>

<p>每个测试用例的第一行给出3个正整数：n，m&nbsp;（n,&nbsp;m&nbsp;&lt;&nbsp;100）和k（k&nbsp;&lt;&nbsp;1000）。</p>

<p>后面的k行给出k项工作的约束，每行是一个三元组：i，x，y。<br />
以一行给出单个0作为输入结束。</p> 

 
 # 输出格式 
<p>【原文】</p>

<p>The&nbsp;output&nbsp;should&nbsp;be&nbsp;one&nbsp;integer&nbsp;per&nbsp;line,&nbsp;which&nbsp;means&nbsp;the&nbsp;minimal&nbsp;times&nbsp;of&nbsp;restarting&nbsp;machine.</p>

<p>【翻译】</p>

<p>输出一个整数一行，表示重启机器的最少次数。</p> 

 
 # 提示 
<h2>来源&nbsp;</h2>

<p>Beijing&nbsp;2002</p>

<h2>数据</h2>

<p>只有一组数据。欢迎提出新数据，请私信我或在题解/讨论版提出！谢谢！</p>

<h2>版权</h2>

<p style="line-height: 20.8px;">本用户并不拥有该资料版权。如果无意侵犯了您的权益，请私信管理员或本用户。管理员接到通知后请删题，以避免不必要的纠纷，谢谢！</p> 
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
<tr><td>5 5 10
0 1 1
1 1 2
2 1 3
3 1 4
4 2 1
5 2 2
6 2 3
7 2 4
8 3 3
9 4 3
0</td><td>3</td></tr></table>
