# 

 
 # 题目描述 
虫族已经消灭了神族。邪恶的虫族还想消灭掉人族，于是又向人族发起了战争。经过激烈的战斗，人族凭着团结的精神，视死如归的斗志把虫族打得落花流水。然而事&nbsp;情还没结束，虫族是天生邪恶的，一有机会它们便要消灭人族，我们要先发制虫。正所谓斩草不除根，春风吹又生，为了人族子孙后代的幸福，人族不能放过余下的&nbsp;虫族，一只也不能放过！当时战斗形势是：所有余下虫族集中在一个星球上，虫族也意识到它们不是顽抗的时候,&nbsp;逃跑是它们唯一的出路,而且为了能有所生还，它们会分散的逃跑，但我们人族早有准备啦，军师派出多名探子，探出虫族逃跑的所有可能经过的路线，我们会派兵在其中若干条路上等待并消灭它们。虫族所在星球&nbsp;编号为&nbsp;0&nbsp;，另外还有&nbsp;N&nbsp;个星球，分别编号为&nbsp;1&nbsp;，&nbsp;2&nbsp;，&nbsp;…&nbsp;，&nbsp;N-1&nbsp;，&nbsp;N&nbsp;。建立一个原点在&nbsp;0&nbsp;号星球的三维坐标系，另&nbsp;N&nbsp;个星球的坐标为（&nbsp;X&nbsp;i&nbsp;，&nbsp;Y&nbsp;i&nbsp;，&nbsp;Z&nbsp;i&nbsp;），&nbsp;i=1&nbsp;，&nbsp;2&nbsp;，&nbsp;…&nbsp;，&nbsp;N-1&nbsp;，&nbsp;N&nbsp;。虫族已经建立了在这（&nbsp;N+1&nbsp;）个星球之间的交通设备，具体的说，有某种不明交通工具&nbsp;M&nbsp;架，每架能且只能连接两个不同的星球使虫族能从连接的两个星球中的任一个到达另一个。探子已经探出这&nbsp;M&nbsp;架交通工具连接的星球对。军师要派兵在若干个虫族的通路中埋伏，要使所有虫都逃不了，但是要在某条通路中埋伏要派兵数目等于该通路连接的两个星球的距离的&nbsp;平方，军师希望用最少的兵力达到不让一只虫逃掉的目的，你要帮他算算最少用兵数目。军师指出，若有某一只虫能逃离星球&nbsp;0&nbsp;到达另一个星球&nbsp;i&nbsp;，并且星球&nbsp;i&nbsp;与星球&nbsp;0&nbsp;的距离大于&nbsp;R&nbsp;，则该虫算逃掉了，它这时能用某种不明方法离开到很远很远的地方，然后重新繁衍出虫族，再来消灭我们人族，这正是我们要避免的。注意人族可以派兵埋伏于与&nbsp;星球&nbsp;0&nbsp;距离大于&nbsp;R&nbsp;的地方。&nbsp;<BR> 

 
 # 输入格式 
N&nbsp;M&nbsp;R&nbsp;<BR>X1&nbsp;Y1&nbsp;Z1<BR>X2&nbsp;Y2&nbsp;Z2<BR>…<BR>XN&nbsp;YN&nbsp;ZN<BR>T1a&nbsp;T1b<BR>T2a&nbsp;T2b<BR>…<BR>Tma&nbsp;Tmb<BR>以&nbsp;上的输入均为整数，同行整数用&nbsp;1&nbsp;个或多个空格隔开。第一行：&nbsp;N&nbsp;（&nbsp;1&lt;=&nbsp;N&nbsp;&lt;=50&nbsp;）为除星球&nbsp;0&nbsp;外的星球数，&nbsp;M&nbsp;(&nbsp;0&lt;=&nbsp;M&nbsp;&lt;=&nbsp;N*(N+1)/2&nbsp;)&nbsp;为虫族交通工具数目，&nbsp;R(1&lt;=&nbsp;R&lt;=10000&nbsp;)&nbsp;为虫族逃离界限，意义见上。往下&nbsp;N&nbsp;行：（&nbsp;X&nbsp;i&nbsp;，&nbsp;Y&nbsp;i&nbsp;，&nbsp;Z&nbsp;i&nbsp;）分别描述星球&nbsp;i&nbsp;的坐标，&nbsp;i=1&nbsp;，&nbsp;2&nbsp;，&nbsp;…&nbsp;，&nbsp;N-1&nbsp;，&nbsp;N.&nbsp;(-1000&nbsp;&lt;=&nbsp;X&nbsp;i&nbsp;,&nbsp;Y&nbsp;i&nbsp;,&nbsp;Z&nbsp;i&nbsp;&lt;=&nbsp;1000)<BR>再往下&nbsp;M&nbsp;行：&nbsp;T&nbsp;ia&nbsp;T&nbsp;ib&nbsp;分别描述第&nbsp;i&nbsp;个交通工具连接的两个星球。&nbsp;0&nbsp;&lt;=&nbsp;T&nbsp;ia&nbsp;,&nbsp;T&nbsp;ib&nbsp;&lt;=&nbsp;N&nbsp;并且&nbsp;T&nbsp;ia&nbsp;不等于&nbsp;T&nbsp;ib&nbsp;,&nbsp;并且若&nbsp;T&nbsp;ia&nbsp;T&nbsp;ib&nbsp;出现了，往下就不会再有&nbsp;T&nbsp;ia&nbsp;T&nbsp;ib&nbsp;或&nbsp;T&nbsp;ib&nbsp;T&nbsp;ia&nbsp;，既每对点最多出现一次。&nbsp;<BR><BR> 

 
 # 输出格式 
仅一个整数，即所用的最少兵力。 
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
<tr><td>sample1:
1 1 2
1 1 1
0 1

sample2:
1 1 1
1 1 1
0 1


</td><td>sample1:
0

sample2:
3
</td></tr></table>
