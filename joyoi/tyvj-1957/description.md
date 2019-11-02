# 

 
 # 题目背景 
vani和cl2在一片树林里捉迷藏…… 

 
 # 题目描述 
这片树林里有N座房子，M条有向道路，组成了一张有向无环图。<BR>树林里的树非常茂密，足以遮挡视线，但是沿着道路望去，却是视野开阔。如果从房子A沿着路走下去能够到达B，那么在A和B里的人是能够相互望见的。<BR>现在cl2要在这N座房子里选择K座作为藏身点，同时vani也专挑cl2作为藏身点的房子进去寻找，为了避免被vani看见，cl2要求这K个藏身点的任意两个之间都没有路径相连。<BR>为了让vani更难找到自己，cl2想知道最多能选出多少个藏身点？ 

 
 # 输入格式 
第一行两个整数N，M。<BR>接下来M行每行两个整数x、y，表示一条从x到y的有向道路。 

 
 # 输出格式 
一个整数K，表示最多能选取的藏身点个数。 

 
 # 提示 
对于20%&nbsp;的数据，N≤10，M&lt;=20。<BR>对于60%&nbsp;的数据,&nbsp;N≤100，M&lt;=1000。<BR>对于100%&nbsp;的数据，N≤200，M&lt;=30000，1&lt;=x,y&lt;=N。 
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
<tr><td>4 4
1 2
3 2
3 4
4 2</td><td>2</td></tr></table>
