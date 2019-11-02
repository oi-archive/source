# 

 
 # 题目描述 
<p>
蜗牛的房子遗失在了一棵树的某个叶子结点上，它要从根结点出发开始寻找它的房子。有一些中间结点可能会住着一些虫子，这些虫子会告诉蜗牛它的房子是否在以这个中间结点为根的子树上，这样蜗牛就不用白跑路了。当然，如果有些结点没有住着虫子的话，那么可怜的蜗牛只有靠自己决定访问顺序来探索了。假设蜗牛走过一条边的耗费都是1，且房子遗失在每个叶子结点的概率都是相等的，那么请问蜗牛找到他的房子的最小数学期望值？<br>我们约定，树上的结点数n最多为1000，每个结点的分叉数k最多为8。<br>例如在下面的这棵树当中：<br><img border="0" src="/source/joyoi/tyvj-2666/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjY2Ni9wcm9ibGVtc19pbWFnZXMvMzEzNS8xODY1LmpwZw==.jpg"> <br>蜗牛从根结点1出发开始寻找它的房子，它的房子可能遗失在2、4、5。在结点3上住着一只虫子，它会告诉蜗牛，以3为根的子树上是否有蜗牛的房子。蜗牛有两种走法。蜗牛可以先访问2，如果它在那儿不能找到房子，那么它要回到根结点1，再通过3来访问结点4（或5），如果还是不能找到它的房子，那么它又要回到结点3，再去访问结点5（或4）。在这种走法中，当房子分别位于2、4、5的时候，蜗牛需要走的步数分别是1、4、6，期望值是(1+4+6)/3=11/3。显然，这种走法没有充分发挥虫子在这里起到的作用。在另一种走法中，蜗牛先访问结点3，它可以从住在3上的虫子那里得知它的房子是否存在于4或5的信息。在这种走法中，当房子分别位于2、4、5的时候，蜗牛需要走的步数分别是3、2、4，期望值是(3+2+4)/3=3。这种走法合理的利用了虫子提供的信息，得到了更优的数学期望值。 <br><br></p> 

 
 # 输入格式 
<p>
The input contains several sets of test data. Each set begins with a line containing one integer N, no more than 1000, which indicates the number of key points in the tree. Then follow N lines describing the N key points. For convenience, we number all the key points from 1 to N. The key point numbered with 1 is always the first fork of the tree. Other numbers may be any key points in the tree except the first fork. The i-th line in these N lines describes the key point with number i. Each line consists of one integer and one uppercase character 'Y' or 'N' separated by a single space, which represents the number of the previous key point and whether there lives a worm ('Y' means lives and 'N' means not). The previous key point means the neighboring key point in the shortest path between this key point and the key point numbered 1. In the above illustration, the previous key point of point 2 or 3 is point 1, while the previous key point of point 4 or 5 is point 3. This integer is -1 for the key point 1, means it has no previous key point. You can assume a fork has at most eight branches. The first set in the sample input describes the above illustration. <br><br>A test case of N = 0 indicates the end of input, and should not be processed. <br></p> 

 
 # 输出格式 
<p>
Output one line for each set of input data. The line contains one float number with exactly four digits after the decimal point, which is the mathematical expectation value. <br></p> 
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
-1 N
1 N
1 Y
3 N
3 N
10
-1 N
1 Y
1 N
2 N
2 N
2 N
3 N
3 Y
8 N
8 N
6
-1 N
1 N
1 Y
1 N
3 N
3 N
0
</td><td>3.0000
5.0000
3.5000</td></tr></table>
