# 

 
 # 题目背景 
applepi捧着编年史,翻啊翻,发现了小猫rainbow的故事……<BR>这天，rainbow显得无聊，于是去找Freda玩…… 

 
 # 题目描述 
rainbow来到了Freda的城堡。现在rainbow已经搞清楚Freda的城堡有N个房间，M&nbsp;条可以建造的双向通道，以及每条通道的长度。<BR><BR>Freda已经把城堡修建成树形的；但是，为了尽量提高自己的移动效率，Freda一定会使得城堡满足下面的条件：<BR>设Di&nbsp;为&nbsp;如果所有的双向通道都被修建，第i&nbsp;号房间与第1&nbsp;号房间的最短路径长度；<BR>设Si&nbsp;为实际修建的树形城堡中第i&nbsp;号房间与第1&nbsp;号房间的路径长度；<BR>对于所有满足1≤i≤N&nbsp;的整数i，有Si&nbsp;=&nbsp;Di。<BR><BR>Freda和rainbow在一起玩的时候总喜欢探究一些东西，这次它们想知道有多少种不同的城堡修建方案，保证方案数大于0。<BR>于是在编年史的下一页上，applepi&nbsp;“被”发现了这个问题。由于applepi&nbsp;还要忙着看编年史，所以这个任务就交给你了。你只需要输出答案对(2^31)–1取模之后的结果就行了。 

 
 # 输入格式 
第一行有两个整数N&nbsp;和M。<BR>之后&nbsp;M&nbsp;行，每行三个整数X，Y&nbsp;和L，表示可以修建X&nbsp;和Y&nbsp;之间的一条长度为L&nbsp;的通<BR>道。 

 
 # 输出格式 
输出一个整数，表示答案对(2^31)–1取模之后的结果。 

 
 # 提示 
对于30%&nbsp;的数据，2≤N≤5，M≤10。<BR>对于&nbsp;50%&nbsp;的数据，满足条件的方案数不超过10000。<BR>对于&nbsp;100%&nbsp;的数据，2≤N≤1000，N&nbsp;–&nbsp;1≤M≤N(N&nbsp;–&nbsp;1)/2，1≤L≤100。 
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
<tr><td>3 3
1 2 2
1 3 1
2 3 1</td><td>2</td></tr></table>
