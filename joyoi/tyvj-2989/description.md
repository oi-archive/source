# 

 
 # 题目描述 
<p>
DD和QQ在玩游戏，DD在地上画了一棵树（图论中的树），然后他告诉QQ这棵树的度数序列。QQ马上说这不是一棵树。DD认为自己被QQ鄙视了，他们吵了起来。<br>但DD随后发现自己算错了度数序列，QQ说的是对的。DD很奇怪为什么QQ反应得这么快。<br>现在给出一个图的度数序列，你需要做的就是像QQ一样：判断这是否可能是一棵树的度数序列。<br></p> 

 
 # 输入格式 
<p>
输入只有一行，首先给出一个整数N，表示顶点个数,后面跟着N个整数，表示这个图的度数序列，每个数不超过100。</p> 

 
 # 输出格式 
<p>
如果输入可能是一棵树的度数序列，则输出“Possible”, 否则输出“Impossible”。</p> 

 
 # 提示 
<p>
对于100%的数据，有1<=N<=100</p> 
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
<tr><td>以下是4个样例输入：
1 0
2 1 1
3 2 2 2
3 1 2 1
</td><td>以下是上面4个样例输入对应的输出：
Possible
Possible
Impossible
Possible</td></tr></table>
