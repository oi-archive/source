# 题目描述


<h2>
	<span style="font-family:Microsoft YaHei;font-size:16px;">题目描述</span> 
</h2>
<p>
	<br/>
</p>
<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;">小X和他的好友小Y约好了要去穿越丛林，不过好斗的小Y提出要兵分两路，比
一比谁走的最快。他们选定了一块n*n的丛林，取左上角为(1,1)，右下角为(n,n)，在每个1*1的区域内都有一个丛林系数Kij，丛林系数越高也
就越难走。他们约定好，只能往坐标变大的方向走【从(x,y)到(x+1,y)或者(x,y+1)】，从(1,1)走过2n-1个区域到达(n,n)。在
丛林中，环境难免不同，因此为了公平起见，小X定义了一个公平值D,这个公平值等于俩人所走过的区域的丛林系数一一对应相减的差的绝对值之和，即</span> 
</p>
<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;">\[ D=\sum_{i=1}^{2n-1} |kx_i-ky_i| \]</span> <span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">(kx，ky分别为小X，小Y走过的每一个区域的丛林系数）。小X找到了你，他想让你编程帮他计算公平值的最大值。</span> 
</p>
<p>
	<br/>
</p>
<h2>
	<span style="font-family:Microsoft YaHei;font-size:16px;">输入</span> 
</h2>
<div>
	<p>
		<span style="font-family:Microsoft YaHei;font-size:16px;">第一行，一个正整数n</span> 
	</p>
	<p>
		<span style="font-family:Microsoft YaHei;font-size:16px;">接下来的n行，每行n个整数，表示丛林中每个区域的丛林系数</span> 
	</p>
	<p>
		<span style="font-family:Microsoft YaHei;font-size:16px;">注意：OJ使用I/O读写，最终评测使用文件读写，文件名为forest.in</span> 
	</p>
</div>
<h2>
	<span style="font-family:Microsoft YaHei;font-size:16px;">输出</span> 
</h2>
<div>
	<p>
		<span style="font-family:Microsoft YaHei;font-size:16px;">一个整数Dmax，即公平值的最大值</span> 
	</p>
	<p>
		<span style="font-family:Microsoft YaHei;font-size:16px;">注意：OJ使用I/O读写，最终评测使用文件读写，文件名为forest.out</span> 
	</p>
</div>
<h2>
	<span style="font-family:Microsoft YaHei;font-size:16px;">样例输入</span> 
</h2>
<div>
	<span style="font-family:Microsoft YaHei;font-size:16px;">4
1 2 3 4
1 5 3 2
8 1 3 4
3 2 1 5</span> 
</div>
<h2>
	<span style="font-family:Microsoft YaHei;font-size:16px;">样例输出</span> 
</h2>
<div>
	<span style="font-family:Microsoft YaHei;font-size:16px;">13</span> 
</div>
<h2>
	<span style="font-family:Microsoft YaHei;font-size:16px;">提示</span> 
</h2>
<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;">【数据范围与约定】</span> 
</p>
<br/>
<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;">对于20%的数据，保证0＜n≤20</span> 
</p>
<br/>
<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;">对于50%的数据，保证0＜n≤50</span> 
</p>
<br/>
<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;">对于100%的数据，保证0＜n≤100且对于所有的i，j保证|Kij|≤300</span> 
</p>
<br/>
<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;">请注意，最终评测使用文件读写，文件名在输入输出格式中有</span> 
</p>
<br/>
<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;">请注意查看答疑贴，程序请发到邮箱，最后统一评测</span> 
</p>
