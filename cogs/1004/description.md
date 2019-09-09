# 题目描述


<h2>
	<span style="font-family:Microsoft YaHei;font-size:16px;">题目描述</span> 
</h2>
<div>
	<p>
		<span style="font-family:Microsoft YaHei;font-size:16px;">这天，小X 
幸运地获得了一次进行挖金币游戏的机会，规则如下：在一个N*N 的矩形里，有N*N 个边长为1 
的正方形格子。在游戏中取左下角的格子坐标为（1，1），右上角为（N,N）。在游戏开始前，每一个格子中都会放入一枚金币，而当游戏开始时，每一个格子
中的那一枚金币都会同时进行一次移动，移动后的横、纵坐标值将分别变为原横、纵坐标值每一位上的乘积。当有金币被移动出格子矩形时，将被游戏方收走。小X
 将被允许选取M 
个格子，他将获得他所选取的格子中所有的金币，而他对游戏中获得的金币数有一个期望值H。他想知道他最多能获得的金币数能否达到他的期望值。不过金币移动
的让人眼花缭乱，小X 算不过来了，他找到了你，希望你能用编程解决这个问题。</span> 
	</p>
</div>
<h2>
	<span style="font-family:Microsoft YaHei;font-size:16px;">输入</span> 
</h2>
<div>
	<p>
		<span style="font-family:Microsoft YaHei;font-size:16px;">一行，三个正整数数N、M、H，以空格隔开，意义如题目中所说。</span> 
	</p>
</div>
<h2>
	<span style="font-family:Microsoft YaHei;font-size:16px;">输出</span> 
</h2>
<div>
	<p>
		<span style="font-family:Microsoft YaHei;font-size:16px;">一个或两个正整数数，以空格隔开。若小X 最多能获得的金币数能达到期望值（即大于等于），则输出小X 最多能获得的金币数以及金币总数能达到期望值的格子数的最小值；若小X 最多能获得的金币数不能达到期望值（即小于），则输出金币数最多的那个格子中的金币数。</span> 
	</p>
</div>
<h2>
	<span style="font-family:Microsoft YaHei;font-size:16px;">样例输入</span> 
</h2>
<div>
	<span style="font-family:Microsoft YaHei;font-size:16px;">17 3 10 </span> 
</div>
<h2>
	<span style="font-family:Microsoft YaHei;font-size:16px;">样例输出</span> 
</h2>
<div>
	<span style="font-family:Microsoft YaHei;font-size:16px;">12 3 </span> 
</div>
<h2>
	<span style="font-family:Microsoft YaHei;font-size:16px;">提示</span> 
</h2>
<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;">举例，（123,456）处的金币将会被移动至（1*2*3，4*5*6）即（6,120）。</span> 
</p>
<br/>
<p>
	<span style="font-size:larger;"><span style="font-family:宋体;"><span style="font-family:Microsoft YaHei;font-size:16px;">例如，左图是一个</span><span style="font-family:Microsoft YaHei;font-size:16px;">20*20</span><span style="font-family:Microsoft YaHei;font-size:16px;">的矩形格，蓝色标示出了坐标。已经按照游戏要求在每个格子中放入了一个金币。而在转换后金币将会变成</span><span style="font-family:Microsoft YaHei;font-size:16px;">右图。</span></span></span> 
</p>
<br/>
<p>
	<img src="/upload/image/20120813/20120813153133_61805.png" alt=""/><img src="/upload/image/20120813/20120813153140_10554.png" alt=""/> 
</p>
<br/>
<p>
	<span style="font-family:&#39;宋体&#39;;font-size:14pt;"></span> 
</p>
<br/>
<br/>
<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;">【数据范围与约定】</span> 
</p>
<br/>
<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;">对于20%的数据，保证0＜M≤N≤100</span> 
</p>
<br/>
<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;">对于50%的数据，保证0＜M≤N≤2000</span> 
</p>
<br/>
<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;">对于70%的数据，保证0＜M≤N≤5000</span> 
</p>
<br/>
<p>
	<span style="font-family:Microsoft YaHei;font-size:16px;">对于100%的数据，保证0＜M≤N≤10000</span> 
</p>
<br/>
