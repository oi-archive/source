# 

 
 # 题目背景 
--&nbsp;昨天，BDEZ,5F秘密基地&nbsp;--<BR>&nbsp;&nbsp;&nbsp;&nbsp;话说我们的中中经过救援行动的一番折腾，终于不幸透支，休克住院……于是乎BDEZ的OIer们经过商议，决定过两天跑到医院慰问中中…… 

 
 # 题目描述 
BDEZ的OIer们还有别的事情要做，不可能一直呆在医院陪中中，所以OIer们经过紧急会议决定：所有人排成一列，所有人按时间表a访问，针对第i个同学，其访问的时间为a[i]分钟。<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;回到这边，在经过一番惨无人道的体力折磨后，已经透支的中中老师急需大量的RP来回复自己的体力。众所周知中中有一个类似某人的吸RP大法，且对方的RP越高，中中吸的速度越快——当然谁不想早点出院呢。所以我们的中中当然要在速度上动一点心眼啦。<BR>&nbsp;&nbsp;&nbsp;&nbsp;比如看见RP高的童鞋，中中就会用自己的各种方法强迫对方多待一会，顺手多给自己招点RP。不过中中不愿意在RP太低的童鞋上浪费自己的时间，理所当然的RP低的同鞋就会被中中想方设法的减少待在这里的时间。<BR>&nbsp;&nbsp;&nbsp;&nbsp;病房是没有电脑的，中中不可能说自己编个程序解决了。于是他想到了身在屏幕前的你。 

 
 # 输入格式 
第一行两个数N,K,N个人，K次询问<BR>第二行N个数，表示OIer们的时间表<BR>第3..k+2行操作如下<BR>C&nbsp;i&nbsp;j:查询从i到j的j-i+1个OIer的访问时间<BR>+&nbsp;i&nbsp;j&nbsp;x:让从i到j的j-i+1个OIer多呆x分钟<BR>-&nbsp;i&nbsp;j&nbsp;x:让从i到j的j-i+1个OIer少呆x分钟 

 
 # 输出格式 
对于每个C询问，输出一个整数，表示从i到j的j-i+1个OIer的访问时间 

 
 # 提示 
n&nbsp;&lt;=&nbsp;500&nbsp;k&nbsp;&lt;=&nbsp;500&nbsp;30%<BR>n&nbsp;&lt;=&nbsp;1000&nbsp;k&nbsp;&lt;=&nbsp;1000&nbsp;50%<BR>n&nbsp;&lt;=&nbsp;50000&nbsp;k&nbsp;&lt;=&nbsp;50000&nbsp;100%<BR>0&lt;=i&lt;=j&lt;=n 
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
<tr><td>12 6
4 14 77 33 9 7 19 42 74 1 69 84
+ 3 11 24
+ 6 7 7
- 1 4 45
+ 4 5 5
+ 8 9 12
C 1 12
</td><td>517</td></tr></table>
