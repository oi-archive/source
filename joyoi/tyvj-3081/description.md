# 

 
 # 题目描述 
<p>
　　你要组织一个由你公司的人参加的聚会。你希望聚会非常愉快，尽可能多地找些有趣的热闹。但是劝你不要同时邀请某个人和他的上司，因为这可能带来争吵。给定N个人(姓名，他幽默的系数，以及他上司的名字)，编程找到能使幽默系数和最大的若干个人。</p> 

 
 # 输入格式 
<p>
　　第一行一个整数N(N < 100)。接下来有N行，每一行描述一个人的信息，信息之间用空格隔开。姓名是长度不超过20的字符串，幽默系数是在0到100之间的整数。</p> 

 
 # 输出格式 
<p>
　　所邀请的人最大的幽默系数和。</p> 

 
 # 提示 
<p>
【问题分析】<br>　　用动态规划求解。首先，很显然公司的人员关系构成了一棵树。设f[a]为a参加会议的情况下，以他为根的子树取得的最大幽默值；g[a]为a不参加会议的情况下，以他为根的子树取得的最大幽默值。那么，状态转移方程就是：<br>　　f[a]=g[b1]+g[b2]+…+g[bk]+1<br>　　g[a]=max(f[b1], g[b1])+max(f[b2], g[b2])+…+max(f[bk], g[bk])<br>　　其中b1, b2, …, bk为a的子结点。<br>　　最后的答案就是max(f[root], g[root])，root是树根。<br></p> 
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
BART 1 HOMER
HOMER 2 MONTGOMERY
MONTGOMERY 1 NOBODY
LISA 3 HOMER
SMITHERS 4 MONTGOMERY
</td><td>8</td></tr></table>
