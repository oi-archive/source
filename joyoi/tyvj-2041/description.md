# 

 
 # 题目背景 
&nbsp;&nbsp;&nbsp;&nbsp;这天，小X来到了游乐园，他发现了一个挖金币游戏，看似很好玩。<br>&nbsp;&nbsp;&nbsp;&nbsp;这个游戏在一个由N*N个格子组成的方阵中进行。初始时，每个格子中都会放入一枚金币，而游戏开始时，每枚金币都会被移动一次。金币移动小X是看不见的，但游乐场管理员告诉了小X金币的移动方式，那就是把这个方阵看成坐标系，左下角为(1,1),右上角为(N,N),每枚金币都会移动到横纵坐标分别为它原来横纵坐标每一位上的数字分别相乘得到的新数字的地方。而小X最多可以选取N个格子，他所得到的分数就是格子中的金币数的总和。由于方阵最大是10000*10000的，小X算不过来了，他找到了身为oier的你来帮忙。<br> 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;给出N*N方阵的大小N，小X所能选取的格子数M，以及小X期望得到的分数H。游戏方式如背景中所说。如果分数能达到小X的期望值H，则输出小X最多能获得的分数以及分数能达到期望值所需的最少的格子数。若分数达不到期望值H，则输出金币数做多的格子中的金币数。<br> 

 
 # 输入格式 
一行，三个正整数数N、M、H，以空格隔开，意义如题目中所说<br> 

 
 # 输出格式 
一行，一个或两个数，以空格隔开，要求如题目中所说。<br> 

 
 # 提示 
移动方式解释：举例，（123,456）处的金币将会被移动至（1*2*3，4*5*6）即（6,120）。<br>【数据范围与约定】<br>对于20%的数据，保证0＜M≤N≤100<br>对于50%的数据，保证0＜M≤N≤2000<br>对于70%的数据，保证0＜M≤N≤5000<br>对于100%的数据，保证0＜M≤N≤10000<br>内存限制256M<br>zaxs0130<br> 
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
<tr><td>17 3 10

</td><td>12 3

</td></tr></table>
