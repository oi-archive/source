# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;森林里面有n棵贵重的树，你需要将它们保护起来。保护树木的方法是给它<BR>们做一个围栏（专业术语叫“凸包”），但围栏本身需要用这些树来做，因此需<BR>要砍下一些树。砍掉哪些树才能让损失的价值最小呢？如果有个解，取被砍掉的<BR>树的数目最小的一组。你可以认为在这样的限制下解是唯一的。 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;输入文件forest.in的第一行表示一个正整数n(2&lt;=n&lt;=15)，即树木的总数。<BR>以下n行每行四个0~10,000之间的整数x，y，v，l，表示树木的位置，价值和高<BR>度。各个树编号为1~n。 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;输出文件forest.out的第一行表示最优解时浪费的长度（保留两位小数）。<BR>第二行以递增的顺序依次打印各个被砍掉的树编号。 

 
 # 提示 
SCOI2004&nbsp;day1&nbsp;T1 
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
<tr><td>6
0 0 8 3
1 4 3 2
2 1 7 1
4 1 2 3
3 5 4 6
2 3 9 8
</td><td>3.16
2 4 5
</td></tr></table>
