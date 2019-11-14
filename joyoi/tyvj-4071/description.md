# 

 
 # 题目描述 
<p>科学家在火星表面发现一个由若干个洞穴和连接它们的若干条隧道组成的一个系统。科学家们使用一种远程遥控机器人来对这个系统进行探测。经研究发现，每一对洞穴之间有且仅有一条路径相连。麻烦的是在这些洞穴里面经常有一些反应发生，这些反应会生成放射性同位素从而增加洞穴的放射性级别，这有可能对进行探测工作的遥控机器人造成损坏。因此现在我们想知道某些对洞穴的路径上放射性级别最大是多少。</p> 

 
 # 输入格式 
<p>输入第一行包含一个整数N，表示总共有N个洞穴，以下N&nbsp;&ndash;&nbsp;1行每行两个整数表示相应的隧道连接的洞穴的编号。接下来一行包含一个整数Q，以下Q行每行开头是一个字母C，然后是两个整数U和V。字母C可能是&lsquo;I&rsquo;或&lsquo;G&rsquo;，如果C是&lsquo;I&rsquo;，那么表示第U(1&nbsp;&le;&nbsp;U&nbsp;&le;&nbsp;N)个洞穴的放射性级别增加V(0&nbsp;&le;&nbsp;V&nbsp;&le;&nbsp;100000)；否则表示询问洞穴U和洞穴V之间路径（包含U和V）上的最大放射性级别(1&nbsp;&le;&nbsp;U,&nbsp;V&nbsp;&le;&nbsp;N)。</p> 

 
 # 输出格式 
<p>对于每一个&lsquo;G&rsquo;询问，输出其路径上的最大放射性级别。</p> 

 
 # 提示 
<p>对于20%的数据，有1&nbsp;&le;&nbsp;N,&nbsp;Q&nbsp;&le;&nbsp;1000；</p>

<p>对于100%的数据，有1&nbsp;&le;&nbsp;N,&nbsp;Q&nbsp;&le;&nbsp;100000。</p> 
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
<tr><td>41 22 32 46I 1 1G 1 1G 3 4I 2 3G 1 1G 3 4</td><td>1013</td></tr></table>
