# 

 
 # 题目描述 
Coder&nbsp;Space的邀请<BR><BR>tyvj上线了新的oi论坛Coder&nbsp;Space，为了提高论坛的软实力，吸引更多的oier，admin决定邀请oi界许多知名的大牛入驻CS,&nbsp;但邀请上某位神牛是需要花费一定时间的，而不同的人邀请同一位神牛所花费的时间也不同（比如可能你跟这位神牛关系好，可以更快的邀请到他/她）。<BR><BR>于是admin把这个任务分配给了小A和小C，让他们在maxtime时间内邀请尽可能多的大牛。<BR><BR>小A和小C商量着列出了一张有n位神牛的表，这张表有n+1行，第一行是两个数n,maxtime&nbsp;，随后n行，每行有两个数字timea[i],timec[i]，分别表示小A和小C邀请第i位神牛所花费的时间，列完表后两人商量了一下就分头行动去了。<BR>不过聪明的你现在不幸发现了这张表，于是你决定计算一下小A和小C这两个家伙理论上在maxtime内所能邀请到的最多的神牛数和邀请最多神牛所花费的最短时间。<BR>若邀请不上任何一人则输出-1。<BR> 

 
 # 输入格式 
如题所述,读入题目中的那张表。 

 
 # 输出格式 
如题所述,在maxtime内所能邀请到的最多的神牛数和邀请最多神牛所花费的最短时间。分两行输出。 

 
 # 提示 
对样例的解释：有3位神牛，时限是1000，小A邀请1、3神牛，小C邀请2神牛，能邀请到3位神牛，花费时间4。<BR><BR>时限1s<BR><BR><BR>0&lt;=n&lt;=100<BR>0&lt;=maxtime&lt;=1000<BR>0&lt;=timea,timec&lt;=maxlongintZzy原创 
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
<tr><td>3 1000
1 4
2 3
3 6</td><td>3
4</td></tr></table>
