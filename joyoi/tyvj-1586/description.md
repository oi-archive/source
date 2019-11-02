# 

 
 # 题目描述 
Henryy岛是个度假胜地，每年吸引着数以万计的游客到来。岛上有着有多精<BR>品店，不过大多数精品店出售的是一种可以&nbsp;DIY&nbsp;的项链。这种项链是一些奇怪<BR>的海洋生物的外壳，把他们串起来好看又小巧。但是串这些外壳也是有技巧的，<BR>要做到好看又小巧真的不容易。&nbsp;<BR>假设每个外壳有好几个可以用来连接其他外壳的连接点，每个连接点我们用<BR>大写英文字母A-Z&nbsp;表示（不会有同一种连接点多次出现在一个外壳上）。两个外<BR>壳可以连接，当且仅当他们有公共的连接点。而且每个连接点最多与另外一个连<BR>接点相连接。如果所有被串起来的外壳，没有多余的连接点（也就是说不可能再<BR>串一个外壳），这样串起来的所有外壳，我们叫做“外壳串”。而项链将由这些的<BR>“外壳串”再次串起来。项链的串法就没有这么复杂了，它直接用绳子串起来就<BR>可以拉。&nbsp;<BR>现在的问题是，在众多的外壳中，应该如何选择才可以串出一个最为庞大的<BR>项链（外壳要最多）&nbsp;。&nbsp; 

 
 # 输入格式 
【输入文件】&nbsp;<BR>第一行是一个整数&nbsp;N（0&lt;=N&lt;=26），表示有&nbsp;N&nbsp;个外壳。接下来有&nbsp;N&nbsp;行，<BR>每行是一个以A-Z&nbsp;字母组成的字串，表示一个外壳。&nbsp; 

 
 # 输出格式 
【输出文件】&nbsp;<BR>输出最多可以由多少个外壳串出一串项链。&nbsp; 

 
 # 提示 
【样例说明】&nbsp;<BR>使用&nbsp;ABD、AB、BA、AC&nbsp;和&nbsp;BCD，其中&nbsp;ABD&nbsp;和&nbsp;BCD&nbsp;串剩&nbsp;A&nbsp;和&nbsp;C，分别<BR>于AB&nbsp;和&nbsp;AC&nbsp;连接后剩下的与&nbsp;BA连接即可。&nbsp;&nbsp;&nbsp;<BR> 
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
<tr><td>【样例输入】 
6 
ABD 
AB 
BA 
ABE 
AC 
BCD 
</td><td>【样例输出】 
5
</td></tr></table>
