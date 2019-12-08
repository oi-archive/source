# 

 
 # 题目描述 
<p>小W来到一个迷宫游玩，他发现迷宫非常特别。这个迷宫共有N层楼，配备了一个特别的电梯。迷宫的每一层都可以停电梯，而且第i层&nbsp;(1&lt;=i&lt;=N)上有一个数字Ki(0&lt;=Ki&lt;=N)，电梯内只提供四个按钮：开，关，上，下。上下的层数等于当前楼层上的那个数字。当然，如果不能满足要求，相应的按钮就会失灵。例如：4&nbsp;2&nbsp;1&nbsp;2&nbsp;5代表了Ki(K1=4,K2=2,&hellip;&hellip;)，从一楼开始。在一楼，按&ldquo;上&rdquo;可以到5楼，按&ldquo;下&rdquo;是不起作用的，因为没有-3楼。进入迷宫中的人都想尽可能地少按电梯到达目的地，假如给你出发楼层A和目的楼层B，请你帮忙求出从A层到B层至少要按几次按钮。</p> 

 
 # 输入格式 
<p>输入文件共有二行，第一行为三个用空格隔开的正整数，表示N,A,B(1&le;N&le;200,&nbsp;1&le;A,B&le;N)，第二行为N个用空格隔开的正整数，表示Ki。</p> 

 
 # 输出格式 
<p>输出文件仅一行，即最少按键次数（这里只统计按&lsquo;上&rsquo;或&lsquo;下&rsquo;的次数）,若无法到达，则输出-1。</p> 
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
<tr><td>5 1 5
4 2 1 2 5
</td><td>1</td></tr></table>
