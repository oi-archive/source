# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;众所周知,XQ最最亲爱的LP---XZ是一个很聪明的人。但是呢，这次他遇到了一个小麻烦，需要XQ的帮忙。<BR>&nbsp;&nbsp;&nbsp;&nbsp;显然，XQ对LP的请求是有百分之百的信心完成的，可是呢...╮(╯﹏╰）╭...XQ最近实在是太忙了，所以希望你能帮他解决他LP的问题。（众人：鬼的！你就是怕不能完成，你个妻管严！妻！管！严！）<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;原来，XZ被邀请去当策划。XZ的Boss想考验一下他，于是给了他一个难题：<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;有n个队伍举行了m场比赛，若假设无平局且第i个队最终赢了w[i]场比赛<BR>那么对于第i个队，它本赛季的费用我们可以当成c[i]*w[i]^t[i]。(1≤t[i]≤4)。<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;XZ所要做的（也就是你现在所要做的）是使这n个队伍本赛季的总费用，即&nbsp;：c[i]*w[1]^t[1]+c[i]*w[2]^t[2]+...+c[n]*w[n]^t[n]&nbsp;最小。<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;你有办法完成吗？<BR> 

 
 # 输入格式 
读入的第1行是n和m<BR>接下来第二行有n个数，第i个数是t[i]<BR>接下来第三行有n个数，第i个数是c[i]<BR>从第4至3+m行每行两个数，是参加某场比赛的两个队，<BR> 

 
 # 输出格式 
一个数,即最小的费用<BR> 

 
 # 提示 
数据范围:<BR>30%的数据&nbsp;t[i]=1<BR>40%的数据&nbsp;N&lt;=5<BR>70%的数据&nbsp;N&lt;=300<BR>100%的数据&nbsp;N&lt;=1200&nbsp;M&lt;=3000<BR> 
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
<tr><td>3 4
2 2 1
28 27 14
1 2
1 2
2 3
1 3
</td><td>83
</td></tr></table>
