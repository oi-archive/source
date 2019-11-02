# 

 
 # 题目背景 
<p>给机房里面新来的几个孩子出的题目，虽然很水，但是数据很强&hellip;&hellip;</p> 

 
 # 题目描述 
<p>图的基础题，你确定你能过吗？（数据已更新）<br />
在一个有向无权图中，给定n(0&lt;&nbsp;n&nbsp;&lt;=&nbsp;8000)个点和m(0&nbsp;&lt;&nbsp;m&nbsp;&lt;=&nbsp;16000)条边，询问多次两点是否连通<br />
<br />
AC者可凭记录向我领取中国红客联盟官方论坛（http://bbs.cnhonker.com/）邀请码一只（要求最后一点1s过，如果你要的话）</p> 

 
 # 输入格式 
<p>第一行两个整数n(0&lt;&nbsp;n&nbsp;&lt;=&nbsp;8000),&nbsp;m(0&nbsp;&lt;&nbsp;m&nbsp;&lt;=&nbsp;16000)分别代表顶点数和边数;<br />
接下来有m行,每行一对整数u,&nbsp;v(0&nbsp;&lt;&nbsp;u,&nbsp;v&nbsp;&lt;&nbsp;n),表示点u,&nbsp;v之间有一条从u指向v的路径;<br />
接下来一个整数q(q&nbsp;&lt;=&nbsp;10000),表示有q组查询;<br />
每组查询两个整数f,&nbsp;t(0&nbsp;&lt;&nbsp;f,&nbsp;t&nbsp;&lt;&nbsp;n&nbsp;)表示询问是否有一条f指向t的路径;</p> 

 
 # 输出格式 
<p>一共q行，每一样一个&nbsp;&ldquo;YES&rdquo;或&ldquo;NO&rdquo;（均为大写，不含引号）表示是否有一条f指向t的路径</p> 

 
 # 提示 
<p>尽管图的点可能很多（8000不多？还要加上10000提问数呢！），但是这是个很稀疏地图&hellip;&hellip;&nbsp;&nbsp;&nbsp;&nbsp;by<br />
苏风臣</p> 
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
1 3
1 5
2 5
2 4
3 2
3
1 2
3 4
1 4
</td><td>YES
YES
YES
</td></tr></table>
