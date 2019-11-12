# 题目描述


<p>
<b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;color:#E56600;background-color:#003399;"><span style="line-height:173%;font-weight:normal;font-family:&#39;Microsoft YaHei&#39;;font-size:16px;color:#E56600;background-color:#003399;">Source: ZJOI2007 </span></span></b><span style="font-size:16px;line-height:28px;color:#E56600;font-family:&#39;Microsoft YaHei&#39;;"> </span> 
</p>
<p>
<span style="color:#e56600;font-family:&#39;&#39;Microsoft YaHei&#39;&#39;;"><span style="font-size:16px;line-height:28px;">BZOJ上本题的链接：<a href="https://www.lydsy.com/JudgeOnline/problem.php?id=1058">http://61.187.179.132/JudgeOnline/problem.php?id=1058</a></span></span> 
</p>
<p>
<span style="color:#e56600;font-family:&#39;&#39;Microsoft YaHei&#39;&#39;;">***关于本题的时限问题：原比赛时本题的时限为每个测试点10ms，而BZOJ上则是一共15秒，为了提高难度，和BZOJ看齐，我就把本题的时限设为4秒每个测试点。</span> 
</p>
<p>
<b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="line-height:173%;font-weight:normal;font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【问题描述】</span></span></b> 
</p>
<div>
<span style="font-size:12pt;"> </span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">小</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Q</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">的妈妈是一个出纳，经常需要做一些统计报表的工作。今天是妈妈的生日，小</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Q</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">希望可以帮妈妈分担一些工作，作为她的生日礼物之一。</span> 
</div>
<div>
<span style="font-size:12pt;"> </span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">经过仔细观察，小</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Q</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">发现统计一张报表实际上是维护一个非负整数数列，并且进行一些查询操作。</span> 
</div>
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">在最开始的时候，有一个长度为</span><i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">N</span></i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">的整数序列，并且有以下三种操作：</span> 
</div>
<div>
<span style="font-size:12pt;"> </span> 
</div>
<table style="margin:auto auto auto 59.4pt;width:333pt;border-collapse:collapse;" width="444" cellspacing="0" cellpadding="0" border="1">
<tbody>
<tr>
<td style="background-color:transparent;" width="120" valign="top">
<div>
<span style="font-size:12pt;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">INSERT </span><i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">i</span></i> <i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">k</span></i></span> 
</div>
</td>
<td style="background-color:transparent;" width="324" valign="top">
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">在原数列的第</span><i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">i</span></i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">个元素后面添加一个新元素</span><i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">k</span></i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">；如果原数列的第</span><i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">i</span></i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">个元素已经添加了若干元素，则添加在这些元素的最后（见下面的例子）</span> 
</div>
</td>
</tr>
<tr>
<td style="background-color:transparent;" width="120" valign="top">
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">MIN_GAP</span> 
</div>
</td>
<td style="background-color:transparent;" width="324" valign="top">
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">查询相邻两个元素的之间差值（绝对值）的最小值</span> 
</div>
</td>
</tr>
<tr>
<td style="background-color:transparent;" width="120" valign="top">
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">MIN_SORT_GAP</span> 
</div>
</td>
<td style="background-color:transparent;" width="324" valign="top">
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">查询所有元素中最接近的两个元素的差值（绝对值）</span> 
</div>
</td>
</tr>
</tbody>
</table>
<div>
<span style="font-size:12pt;"> </span> 
</div>
<div>
<span style="font-size:12pt;"> </span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">例如一开始的序列为</span> 
</div>
<table style="margin:auto auto auto 104.4pt;border-collapse:collapse;" cellspacing="0" cellpadding="0" border="1">
<tbody>
<tr>
<td style="background-color:transparent;" width="56" valign="top">
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">5</span> 
</div>
</td>
<td style="background-color:transparent;" width="56" valign="top">
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3</span> 
</div>
</td>
<td style="background-color:transparent;" width="56" valign="top">
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1</span> 
</div>
</td>
</tr>
</tbody>
</table>
<div>
</div>
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">执行操作</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">INSERT 2 9</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">将得到：</span> 
</div>
<table style="margin:auto auto auto 104.4pt;border-collapse:collapse;" cellspacing="0" cellpadding="0" border="1">
<tbody>
<tr>
<td style="background-color:transparent;" width="56" valign="top">
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">5</span> 
</div>
</td>
<td style="background-color:transparent;" width="56" valign="top">
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3</span> 
</div>
</td>
<td style="background-color:transparent;" width="56" valign="top">
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">9</span> 
</div>
</td>
<td style="background-color:transparent;" width="56" valign="top">
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1</span> 
</div>
</td>
</tr>
</tbody>
</table>
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">此时</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">MIN_GAP</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">为</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">，</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">MIN_SORT_GAP</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">为</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">。</span> 
</div>
<div>
</div>
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">再执行操作</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">INSERT 2 6</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">将得到：</span> 
</div>
<table style="margin:auto auto auto 104.4pt;border-collapse:collapse;" cellspacing="0" cellpadding="0" border="1">
<tbody>
<tr>
<td style="background-color:transparent;" width="56" valign="top">
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">5</span> 
</div>
</td>
<td style="background-color:transparent;" width="56" valign="top">
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3</span> 
</div>
</td>
<td style="background-color:transparent;" width="56" valign="top">
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">9</span> 
</div>
</td>
<td style="background-color:transparent;" width="56" valign="top">
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">6</span> 
</div>
</td>
<td style="background-color:transparent;" width="56" valign="top">
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1</span> 
</div>
</td>
</tr>
</tbody>
</table>
<div>
</div>
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">注意这个时候原序列的第</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">个元素后面已经添加了一个</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">9</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">，此时添加的</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">6</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">应加在</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">9</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">的后面。这个时候</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">MIN_GAP</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">为</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">，</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">MIN_SORT_GAP</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">为</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">。</span> 
</div>
<div>
<span style="font-size:12pt;"> </span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">于是小</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">Q</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">写了一个程序，使得程序可以自动完成这些操作，但是他发现对于一些大的报表他的程序运行得很慢，你能帮助他改进程序么？</span> 
</div>
<div style="margin:13pt 0cm;">
<b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="line-height:173%;font-weight:normal;font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输入文件】</span></span></b> 
</div>
<div>
<span style="font-size:12pt;"> </span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输入文件</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">form.in</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">第一行包含两个整数</span><i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">N</span></i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">，</span><i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">M</span></i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">，分别表示原数列的长度以及操作的次数。</span> 
</div>
<div>
<span style="font-size:12pt;"> </span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">第二行为</span><i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">N</span></i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">个整数，为初始序列。</span> 
</div>
<div>
<span style="font-size:12pt;"> </span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">接下来的</span><i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">M</span></i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">行每行一个操作，即“</span><span style="font-size:12pt;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">INSERT </span><i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">i</span></i> <i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">k</span></i></span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">”，“</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">MIN_GAP</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">”，“</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">MIN_SORT_GAP</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">”中的一种（无多余空格或者空行）。</span> 
</div>
<div style="margin:13pt 0cm;">
<b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="line-height:173%;font-weight:normal;font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输出文件】</span></span></b> 
</div>
<div>
<span style="font-size:12pt;"> </span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于每一个“</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">MIN_GAP</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">”和“</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">MIN_SORT_GAP</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">”命令，输出一行答案即可。</span> 
</div>
<div style="margin:13pt 0cm;">
<b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="line-height:173%;font-weight:normal;font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例输入】</span></span></b> 
</div>
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 3 5</span> 
</div>
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 5 3 1</span> 
</div>
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> INSERT 2 9</span> 
</div>
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> MIN_SORT_GAP</span> 
</div>
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> INSERT 2 6</span> 
</div>
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> MIN_GAP</span> 
</div>
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> MIN_SORT_GAP</span> 
</div>
<div style="margin:13pt 0cm;">
<b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="line-height:173%;font-weight:normal;font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例输出】</span></span></b> 
</div>
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 2</span> 
</div>
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 2</span> 
</div>
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 1</span> 
</div>
<div style="margin:13pt 0cm;">
<b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="line-height:173%;font-weight:normal;font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【数据规模】</span></span></b> 
</div>
<div>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">30%</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">的数据，</span><i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">N</span></i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">≤ </span><span style="font-size:12pt;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1000 , </span><i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">M</span></i> </span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">≤ </span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">5000</span> 
</div>
<div>
<span style="font-size:12pt;"> </span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">100%</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">的数据，</span><i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">N </span></i><span style="font-size:12pt;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">,</span><i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> M</span></i> </span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">≤500000</span> 
</div>
<p>
<span style="font-size:12pt;"> </span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于所有的数据，序列内的整数不超过</span><span style="font-size:12pt;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">5*10</span><sup><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">8</span></sup></span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">。</span> 
</p>
