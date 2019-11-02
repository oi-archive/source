# 

 
 # 题目背景 
<p>蛟川书院模拟试题</p> 

 
 # 题目描述 
<p>农夫tom最近在研究如果发生重大事故，如何让农场里的奶牛逃离问题。他想要确信在紧急情况下，所有的奶牛都有一个安全逃离方案。因为在紧急情况下，奶牛们都会失去观察和判断能力，所以最近tom一直在教奶牛们逃离的方法，他的方法很简单，就是任何时候都只向北方或东方逃离，北方是行坐标减1的方向，东方是列坐标加1的方向。奶牛们虽笨，不过这一点事关自己的生命，所以他们牢记在心，而且也一定会这么做。<br />
当然也会出问题，奶牛们在逃离的方向上会横冲直撞，为了阻止奶牛之间互相冲撞造成伤害，tom要求任何一个奶牛的逃离路线不能经过其它奶牛的初始位置。一个逃离方案是安全的如果它能够满足上面的要求，反之它就是不安全的。<br />
奶牛们所在的土地（农场）被划分成了r行和c列的一个矩形地图。奶牛们都待在这个矩形中的某一个位置。<br />
请帮助tom确定给定的一个地图上是否存在一个安全的逃离方案。<br />
比如，下面的两个图：<br />
左边的例子表示了一个能够安全逃离的地图，因为没有任何一个奶牛的逃离路线上包括其他奶牛。右边的例子表示了一个不安全的地图，因为位于(4,1)的奶牛不论是向东逃离还是向北逃离，它的路线上都会有别的奶牛，从这个图中拿掉任意一头奶牛，这个地图都会变成安全的。<br />
&nbsp;安全&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;不安全<br />
&nbsp;|&nbsp;|&nbsp;|&nbsp;|&nbsp;C--&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;C&nbsp;.&nbsp;.&nbsp;.&nbsp;.&nbsp;.&nbsp;<br />
&nbsp;|&nbsp;|&nbsp;|&nbsp;|&nbsp;C--&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;^&nbsp;.&nbsp;.&nbsp;.&nbsp;.&nbsp;.&nbsp;<br />
&nbsp;|&nbsp;C&nbsp;|&nbsp;|&nbsp;C--&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;.&nbsp;.&nbsp;.&nbsp;.&nbsp;.&nbsp;<br />
&nbsp;C&nbsp;C-+-+----&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;C------&gt;C&nbsp;.&nbsp;<br />
&nbsp;.&nbsp;.&nbsp;C&nbsp;C&nbsp;C--&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;.&nbsp;.&nbsp;.&nbsp;.&nbsp;.&nbsp;.&nbsp;<br />
C表示奶牛，直线表示逃离路线</p> 

 
 # 输入格式 
<p>第1行：两个整数r,c，用1个空格隔开，表示矩形的行数和列数（均不超过50）。<br />
第2行：一个整数n，表示奶牛的个数（不超过100）。<br />
第3到n+2行：共n行，每行有两个整数，之间用1个空格隔开，分别表示这头奶牛所在的行和列。</p> 

 
 # 输出格式 
<p>如果这块土地是安全的，输出0。<br />
如果移走任意一头奶牛这块土地还是不安全，输出-1。<br />
否则输出1，并且在下一行输出移走的那头奶牛的编号，如果有多个奶牛满足要求，输出输入序列中编号最小一个。</p> 

 
 # 提示 
<p>Moe-ing</p> 
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
<tr><td>5 5
5
1 1
2 4
3 1
2 2
2 1
</td><td>1
1
</td></tr></table>
