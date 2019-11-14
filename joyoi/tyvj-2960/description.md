# 

 
 # 题目描述 
<p>
　　栈是常用的一种数据结构，有n个元素在栈顶端一侧等待进栈，栈顶端另一侧是出栈序列。你已经知道栈的操作有两种：push和pop，前者是将一个元素进栈，后者是将栈顶元素弹出。现在要使用这两种操作，由一个操作序列可以得到一系列的输出序列。请你编程求出对于给定的n，计算并输出由操作数序列1，2，…，n，经过一系列操作可能得到的输出序列总数。<br><br><center><img src="/source/joyoi/tyvj-2960/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjk2MC9wcm9ibGVtc19pbWFnZXMvMTIwMS8xLmpwZw==.jpg"></img></center></p> 

 
 # 输入格式 
<p>
　　就一个数n(1 ≤ n ≤ 1000)。</p> 

 
 # 输出格式 
<p>
　　一个数，即可能输出序列的总数目。</p> 

 
 # 提示 
<p>
【算法分析】<br>　　在第一章练习里，我们通过回溯的方法计算并输出不同的出栈序列，这里只要求输出不同的出栈序列总数目，所以我们希望能找出相应的递推公式进行处理。<br>　　从排列组合的数学知识可以对此类问题加以解决。<br>　　我们先对n个元素在出栈前可能的位置进行分析，它们有n个等待进栈的位置，全部进栈后在栈里也占n个位置，也就是说n个元素在出栈前最多可能分布在2*n位置上。<br>　　出栈序列其实是从这2n个位置上选择n个位置进行组合，根据组合的原理，从2n个位置选n个，有C(2n,n)个。但是这里不同的是有许多情况是重复的，每次始终有n个连续的空位置，n个连续的空位置在2n个位置里有n+1种，所以重复了n+1次。所以出栈序列的种类数目为：<br>　　C(2n,n)/(n+1)=2n*(2n-1)*(2n-2)…*(n+1)/n!/(n+1)=2n*(2n-1)*(2n-2)*…*(n+2)/n!。<br>　　考虑到这个数据可能比较大，所以用高精度运算来计算这个结果。<br>　　本题实际是一个经典的Catalan数模型。有关Catalan数的详细解释请参考《组合数学》等书。<br>【思考与提高】<br>　　我们知道，在某个状态下，所能做的操作(移动方法)无非有两种：<br>　　（1）将右方的等待进栈的第一个元素进栈；    （2）将栈顶的元素出栈，进入左边的出栈序列。<br>　　设此时右方、栈、左方的元素个数分别为a，b，c。我们就能用(a,b,c)表示出当前的状态。显然n=a+b+c，则c=n-a-b。即已知a和b，c就被确定，所以我们可以用(a,b)来作为状态的表示方法。则起始状态为(n,0)，目标状态为(0,0)。<br>　　又由上面的两种移动方法，我们可类似的得到两种状态转移方式：<br> <br><center><img src="/source/joyoi/tyvj-2960/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjk2MC9wcm9ibGVtc19pbWFnZXMvMTIxMS8xLmJtcA==.bmp"></img></center><br>　　再设f(a,b)为从状态(a,b)通过移动火车变为状态(0,0)的所有移动方法。类似于动态规划的状态转移方程，我们可写出以下递归式：<br>  <br><center><img src="/source/joyoi/tyvj-2960/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjk2MC9wcm9ibGVtc19pbWFnZXMvMTIxMS8yLmJtcA==.bmp"></img></center><br>　　边界值：f(0,0)=1。<br>　　有了这个递归公式后，再写程序就比较简单了，请读者自己写出递归程序。<br> <br></p> 
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
<tr><td>3</td><td>5</td></tr></table>
