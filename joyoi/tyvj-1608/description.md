# 

 
 # 题目背景 
AndyBear&nbsp;生日模拟赛&nbsp;第二题<BR> 

 
 # 题目描述 
晴朗的上午，小熊BIBO抱着一罐糖，出去找好朋友，两只小兔子。从小熊家出来，穿过小树林，在一个有向日葵的路口向右拐，这就是小兔子家了。小熊BIBO见到好朋友，开心的不得了，BIBO要做的第一件事，是分糖，因为大熊说过，好东西是不可以独享的。<BR>糖罐里有N颗糖，小熊BIBO要挑出m颗来给两只小兔子，剩下的留着自己吃。&nbsp;对于这n颗糖中的每一颗，这两只小兔子都有各自的喜欢程度Ai和Bi。小熊BIBO想让挑出来这m颗糖的“Ai和”与“Bi和”的差尽量小，在满足“Ai和”与“Bi和”的差最小的情况下呢，要让“Ai和”与“Bi和”的和尽量大。&nbsp;小熊BIBO可不擅长算数，所以想请你告诉她，如果选m颗糖，“Ai和”与“Bi和”的最小差是多少，还有在满足这个最小差的情况下，最大和是多少。 

 
 # 输入格式 
输入文件的第一行，有两个数字，n和m，代表小熊BIBO要从n颗糖中挑出m颗。<BR>接下来有n行，每行两个数字Ai和Bi，代表第i颗糖的Ai值和Bi值。 

 
 # 输出格式 
输出应该包含两行数字。<BR>第一行是这m颗糖的“Ai和”与“Bi和”的差的最小值。<BR>第二行是在满足第一行答案的选糖所有方案中，“Ai和”与“Bi和”的最大值。<BR><BR>请注意，本题中提及的“差”，均是指两数相减的绝对值，即&nbsp;|A-B|。 

 
 # 提示 
对于10%的数据,&nbsp;0&lt;n&lt;=5,<BR>对于30%的数据，0&lt;n&lt;=50,<BR>对于100%的数据,&nbsp;0&lt;n&lt;=200,&nbsp;0&lt;m&lt;=20,&nbsp;0&lt;=Ai,Bi&lt;=20.<BR>输入数据均为整数。 
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
<tr><td>4 2
1 2
2 3
4 1
6 2
</td><td>2
10

解释：挑出的是第二颗和第三颗糖。</td></tr></table>
