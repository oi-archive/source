# 

 
 # 题目描述 
<p>给定一个节点&nbsp;1&nbsp;和节点&nbsp;N&nbsp;连通的正权无向图&nbsp;G，请你删除不超过&nbsp;K&nbsp;条边，使得节点&nbsp;1&nbsp;和节点&nbsp;N&nbsp;仍然连通的同时，且这两点之间的最短路尽可能长。&nbsp;</p> 

 
 # 输入格式 
<p>本题为提交答案试题，输入文件&nbsp;shortest1.in~shortest10.in已经在选手目录下。&nbsp;<br />
输入文件&nbsp;shortest*.in&nbsp;的第一行包含三个正整数&nbsp;N，M&nbsp;和&nbsp;K。其中&nbsp;N&nbsp;表示节<br />
点数，M&nbsp;表示边数，节点的编号由&nbsp;1&nbsp;至&nbsp;N，边的编号由&nbsp;1&nbsp;至&nbsp;M。接下来&nbsp;M&nbsp;行，每行三个正整数&nbsp;u，v&nbsp;和&nbsp;w，表示有一条连接节点&nbsp;u&nbsp;和节点&nbsp;v&nbsp;的边，权值为&nbsp;w。&nbsp;</p> 

 
 # 输出格式 
<p>输出文件&nbsp;shortest*.out&nbsp;的第一行包含一个非负整数&nbsp;T&nbsp;(T&nbsp;&le;&nbsp;K)，表示需要删掉的边数。&nbsp;<br />
接下来&nbsp;T&nbsp;行，每行一个&nbsp;1&nbsp;到&nbsp;M&nbsp;之间的整数&nbsp;x，表示删掉输入中的第&nbsp;x&nbsp;条边。你需要保证这&nbsp;T&nbsp;个整数互不相同。&nbsp;</p> 

 
 # 提示 
<h3>样例说明</h3>

<p>样例中从节点&nbsp;1&nbsp;到&nbsp;3&nbsp;的最短路径长度为&nbsp;1，删去第三条边之后，最短路径长度为&nbsp;2。</p>

<h3>原评分标准</h3>

<p>对于每个测试点，设有评分四个参数&nbsp;s1,&nbsp;s2,&nbsp;s3,&nbsp;s4。假设你的方案的最短路为ans。&nbsp;</p>

<p>如果你没有输出，或者输出不合法，或者最短路不存在，得&nbsp;0&nbsp;分。</p>

<p>如果最短路存在，得&nbsp;1&nbsp;分。&nbsp;</p>

<p>如果&nbsp;ans&nbsp;&ge;&nbsp;s1，得&nbsp;3&nbsp;分。&nbsp;</p>

<p>如果&nbsp;ans&nbsp;&ge;&nbsp;s2，得&nbsp;5&nbsp;分。&nbsp;</p>

<p>如果&nbsp;ans&nbsp;&ge;&nbsp;s3，得&nbsp;8&nbsp;分。&nbsp;</p>

<p>如果&nbsp;ans&nbsp;=&nbsp;s4，得&nbsp;10&nbsp;分。&nbsp;</p>

<p>如果&nbsp;ans&nbsp;&gt;&nbsp;s4，得&nbsp;12&nbsp;分。&nbsp;</p>

<p>取满足条件的分数中的最高得分为该测试点你的得分。&nbsp;</p>

<h3>如何测试你的输出</h3>

<p>在你的目录下有一个名为&nbsp;checker&nbsp;的程序可以用来检查你的输出，你可以在终端中使用以下命令来检查你的输出：&nbsp;</p>

<pre class="ckeditor-code vb">
./checker&nbsp;&nbsp;N</pre>

<p>其中&nbsp;N&nbsp;为测试点的编号，例如，要测试第&nbsp;3&nbsp;个测试点可以使用</p>

<pre class="ckeditor-code vb">
./checker&nbsp;&nbsp;3</pre>

<p>该程序会检测你的输出方案是否合法。如果方案合法，程序还会给出该方案的最短路的长度值。&nbsp;</p>

<p><a href="http://7xta2e.com2.z0.glb.clouddn.com/Tyvj3705.zip">点击下载输入文件和checker。</a></p>

<h3>SPJ</h3>

<p><strong><u>因系统兼容性问题，此题的spj无法正常显示评测结果。即：只要编译正确，您此题便AC。但事实上您不一定真的AC。这时候您需要手动点击每一个测试点的详情，查看您的真实得分。</u></strong></p> 
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
<tr><td>3 3 1
1 2 1
2 3 1
1 3 1
</td><td>1
3
</td></tr></table>
