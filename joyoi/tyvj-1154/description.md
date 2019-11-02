# 

 
 # 题目背景 
话说小q的高中生活开始了~ 

 
 # 题目描述 
一天，小q冲到了食堂却发现饭卡没带（囧。。。），只好回去取，再回去的途中他还想知道他所排的队的情况，所以他让一个同学帮忙监视。（初始队列为0）<BR>	同学知道队列的进出情况。（具体请看样例）<BR>	针对小q的提问&nbsp;同学得回答现在队伍里有多少人，还想知道队伍中最高的身高是多少。（想打架？？？。。。） 

 
 # 输入格式 
第一行&nbsp;一个数&nbsp;n&nbsp;表示一共有多少个命令（包括进、出、询问）<BR>接下来n行<BR>	第一个数为p<BR>		若p为1则表示小q询问队列里有多少人。<BR>		若p为2则表示最前面的已经买完饭了&nbsp;出队了<BR>		若p为3则表示最后面的又来了1个人&nbsp;后面还有一个数为身高（大于0小于maxint）<BR>		若p为4则表示询问在队中最高的身高为多少（如果没人请输出0）<BR> 

 
 # 输出格式 
据每个p=1或4时的情况的回答（每行一个）<BR> 

 
 # 提示 
40%的数据&nbsp;保证n&lt;=&nbsp;1000<BR>80%的数据&nbsp;保证n&lt;=100000<BR>100%的数据&nbsp;保证&nbsp;n&lt;=&nbsp;800000&nbsp;身高&lt;=100<BR>lemon_TsyD&nbsp;原创 
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
1
3 50
3 40
2
4</td><td>0
40</td></tr></table>
