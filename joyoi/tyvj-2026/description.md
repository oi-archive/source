# 

 
 # 题目背景 
小X和他的好友小Y约好了要去穿越丛林，不过好斗的小Y提出要兵分两路，比一比谁走的最快。<br><br> 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;小X与小Y选定了一块n*n的丛林，取左上角为(1,1)，右下角为(n,n)，他们约定好，只能往坐标变大的方向走【从(x,y)到(x+1,y)或者(x,y+1)】，走过2n-1个区域到达(n,n)。在丛林中，环境难免不同，所以在每个1*1的区域内都有一个丛林系数Kij，丛林系数越高也就越难走，因此为了公平起见，小X定义了一个公平值D,这个公平值等于俩人所走过的区域的丛林系数一一对应相减的差的绝对值之和。小X找到了你，他想让你编程帮他计算公平值的最大值。<br> 

 
 # 输入格式 
第一行，一个正整数n<br>接下来的n行，每行n个数，表示丛林中每个区域的丛林系数<br><br> 

 
 # 输出格式 
一个整数Dmax，即公平值的最大值<br><br> 

 
 # 提示 
对于20%的数据，保证0＜n≤20<br>对于50%的数据，保证0＜n≤50<br>对于100%的数据，保证0＜n≤100且对于所有的i，j保证|Kij|≤300<br>zaxs0130<br> 
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
<tr><td>4
1 2 3 4
1 5 3 2
8 1 3 4
3 2 1 5

</td><td>13

</td></tr></table>
