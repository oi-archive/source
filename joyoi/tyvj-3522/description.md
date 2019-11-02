# 

 
 # 题目描述 
<p>
　　呵呵，有一天我做了一个梦，梦见了一种很奇怪的电梯。大楼的每一层楼都可以停电梯，而且第i层楼(1 <= i <= N)上有一个数字Ki(0 <= Ki <= N)。电梯只有四个按钮：开，关，上，下。上下的层数等于当前楼层上的那个数字。当然，如果不能满足要求，相应的按钮就会失灵。例如：3 3 1 2 5代表了Ki(K1=3,K2=3,……)，从一楼开始。在一楼，按“上”可以到4楼，按“下”是不起作用的，因为没有-2楼。那么，从A楼到B楼至少要按几次按钮呢？<br><br></p> 

 
 # 输入格式 
<p>
　　输入文件共有二行，第一行为三个用空格隔开的正整数，表示N,A,B(1≤N≤200, 1≤A,B≤N)，第二行为N个用空格隔开的正整数，表示Ki。</p> 

 
 # 输出格式 
<p>
　　输出文件仅一行，即最少按键次数,若无法到达，则输出-1。</p> 
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
3 3 1 2 5
</td><td>3</td></tr></table>
