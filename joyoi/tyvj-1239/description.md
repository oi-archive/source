# 

 
 # 题目背景 
tyvj20100620比赛,祝大家取得好成绩。^-^<BR> 

 
 # 题目描述 
有九个朋友一起去唱KTV。他们唱的前三首歌总是有这样一个要求：每首歌由三个人来唱，且每个人都只唱一首歌。但是有些朋友不愿一起唱同一首歌，因此并不是所有组合都可以。而且三个人如果能在一起唱歌，他们有一个默契程度，不同的三个人唱歌的默契程度又有不同。<BR>我们给出所有可行的三人组合以及他们的默契度，请你写一个程序找出一个方案，使得这三首歌的默契度之和最大。<BR> 

 
 # 输入格式 
第一行包含一个整数n(1&lt;=n&lt;=100)，为所有可行的组合的数量。<BR>接下来n行，每行四个整数a,b,c,w描述一个可行的组合。表示编号为a,b,c的三人唱同一首歌时默契度为w。<BR> 

 
 # 输出格式 
输出共一行。如果有可行方案，输出三首歌能够达到的最大默契度，如果找不出可行的方案则输出一行“Impossible”。 
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
1 2 3 10
4 5 6 20
7 8 9 30
1 3 5 15
2 4 6 18
</td><td>63</td></tr></table>