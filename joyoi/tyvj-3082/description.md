# 

 
 # 题目描述 
<p>
　　一场可怕的地震后，人们用N个牲口棚(1≤N≤150，编号1..N)重建了农夫John的牧场。由于人们没有时间建设多余的道路，所以现在从一个牲口棚到另一个牲口棚的道路是惟一的。因此，牧场运输系统可以被构建成一棵树。John想要知道另一次地震会造成多严重的破坏。有些道路一旦被毁坏，就会使一棵含有P(1≤P≤N)个牲口棚的子树和剩余的牲口棚分离，John想知道这些道路的最小数目。</p> 

 
 # 输入格式 
<p>
　　第1行：2个整数，N和P<br>　　第2..N行：每行2个整数I和J，表示节点I是节点J的父节点。<br></p> 

 
 # 输出格式 
<p>
　　单独一行，包含一旦被破坏将分离出恰含P个节点的子树的道路的最小数目。</p> 

 
 # 提示 
<p>
【问题分析】<br>　　用树型动态规划求解。定义f(n, m)为在n为根的子树中取m个节点的最小代价，则状态转移方程为：<br>　　f(n, m)=min{f(n0, m0)+f(n1, m1)+f(n2, m2)+…+f(nk, mk)}<br>　　其中，n0, n1, n2, …, nk为n的k个儿子，m0+m1+m2+…+mk=m，并且定义f(ni, 0)=1。<br>　　最后的结果为：<br>　　min{f(root, p), min{f(n, p) | n≠root}}<br><br></p> 
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
<tr><td>11 6						
1 2
1 3
1 4
1 5
2 6
2 7
2 8
4 9
4 10
4 11
</td><td>2



【样例解释】
　　如果道路1-4和1-5被破坏，含有节点（1，2，3，6，7，8）的子树将被分离出来</td></tr></table>
