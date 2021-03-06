# 

 
 # 题目描述 
<p>
　　一堆木头棍子共有n根，每根棍子的长度和宽度都是已知的。棍子可以被一台机器一个接一个地加工。机器处理一根棍子之前需要准备时间。准备时间是这样定义的：<br>　　第一根棍子的准备时间为1分钟；<br>　　如果刚处理完长度为L，宽度为W的棍子，那么如果下一个棍子长度为Li，宽度为Wi，并且满足L >＝ Li，W >＝ Wi，这个棍子就不需要准备时间，否则需要1分钟的准备时间；<br>　　计算处理完n根棍子所需要的最短准备时间。比如，你有5根棍子，长度和宽度分别为(4, 9)，(5, 2)，(2, 1)，(3, 5)，(1, 4)，最短准备时间为2（按(4, 9)、(3, 5)、(1, 4)、(5, 2)、(2, 1)的次序进行加工）。<br></p> 

 
 # 输入格式 
<p>
　　第一行是一个整数n(n <＝ 5000)，第2行是2n个整数，分别是L1，W1，L2，w2，…，Ln，Wn。L和W的值均不超过10000，相邻两数之间用空格分开。</p> 

 
 # 输出格式 
<p>
　　仅一行，一个整数，所需要的最短准备时间。</p> 

 
 # 提示 
<p>
【知识准备】<br>　　基本动态规划原理。<br>【算法分析】<br>　　本题的任务，概括来说是：对于给定的一些二元组(x1, y1)，(x2, y2)，(x3, y3)，…，(xn, yn)，确定一些序列的分割：<br>	 <br>	 <br>　　……<br>	 <br>　　这里，要求对于任意的i, j, p（p>1），满足xijp-1≤xijp且yijp-1≤yijp，并且使得k尽可能小（即最小分割）。<br>　　这其实就是著名的不下降序列的最小分割问题。<br>　　一个著名的定理是这样的：最长上升序列的长度等于不上升序列的最小分划（即将平面上的点分划成尽可能少的不相交的不上升序列）。下面我们就来给出这个定理的证明，在证明的过程中，我们甚至可以得到求具体分割方案的方法。<br>　　证明：<br>　　一个显然的结论是最长上升序列的长度小于等于不上升序列的最小分划。因为上升序列中任意两点都不可能属于同一个不上升序列。也就是说，最长上升序列中的所有点分属不同的不上升序列。所以，不上升序列的分划数最少也不会少于最长上升序列的长度。<br>　　关键的是要证明，最长上升序列的长度大于等于不上升序列的最小分划。我们来构造一个不上升序列的分划。<br>　　首先在二维Euclid空间中取出所有的满足如下性质的点(x, y)：对于任意的点(x', y')，总满足x'≤x || y'≤y，即(x，y)的“右上方”没有别的点。可以证明，取出的点集{(x，y)}是一条不上升序列。因为点集中任意两点(x1, y1)和(x2, y2)总满足x1≤x2 || y1≤y2且x2≤x1 || y2≤y1，整理一下即得(x1≤x2)xor(y1≤y2)＝true。所以，把这些点按x升序排列后，得到的y相应的成降序。<br>　　将上面取出的点从空间中去除后，重复上述过程，又可以得到一条新的不上升序列。如此反复……可以得到一个不上升序列的分划(现在还不能肯定这就是最小的分划)。由前面的结论知道，这个分划数必定大于等于最长上升序列的长度。<br>　　我们对得到的不上升序列分划进行分级，先取出的等级最高，最后取出的等级最低。这样就得到k条分属level1，level2，…，levelk的不上升序列。<br>　　这些链上的点满足这样的性质：对于一个属于leveli(i<k)链上的点(x, y)，必然存在一个属于leveli+1的点(x', y')，使得x<x' && y<y'。否则(x, y)在取leveli+l链时就会被取走，不应属于leveli。<br>　　从level1上的一点（x1, y1）开始，取level2的点（x2, y2），x2>x1 && y2>y1，然后取level3的点（x3, y3）……最后必然能取到levelk上的点（xk, yk）。如此得到的序列（x1, y1），（x2, y2），…，（xk, yk），就是一条上升序列。所以，我们前面得到的不上升序列的分划数就不可能大于最长上升序列长度。<br>　　这就证明了最长上升序列的长度大于等于不上升序列的最小分划。再加上“最长上升序列的长度小于等于不上升序列的最小分划”的结论，就证明了最长上升序列的长度等于不上升序列的最小分划。<br>　　这个证明的优点在于，它是一个构造性的证明，并且揭示了最长上升序列与不上升序列最小分划之间的较为深刻的关系。<br>　　根据前面的证明，我们可以很容易得到两种解决本题的方法：<br>　　（1）在给出的二元组中求出最长下降序列的长度（具体实现比较简单，这里就从略了）；<br>　　（2）用类似Topologic排序的方法，构造性的求出不下降序列的最小分割(详细过程见证明)。<br>　　这两种方法的时间复杂度都是O(n2)的。实际上，本题还能优化到O(nlog2n)级，考虑到题目的规模以及本文的侧重点，这里就不详细展开了。此外，前面讲的方法（2），也是求最长双链问题的一个基础。<br><br><br></p> 
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
<tr><td>5								
4 9 5 2 2 1 3 5 1 4
</td><td>2</td></tr></table>
