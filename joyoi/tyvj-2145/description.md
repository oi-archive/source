# 

 
 # 题目描述 
<p>道路安全部门最近计划部署从&nbsp;A&nbsp;市到&nbsp;B&nbsp;市的道路监控系统，以提高该部门对于紧急事件的应对能力。A市到B市的道路网可以描述为一个无向图G=(V,&nbsp;E),&nbsp;其中&nbsp;V&nbsp;表示道路网中的节点集合,&nbsp;E&nbsp;表示连接节点的双向道路集合。所有的节点由&nbsp;1~n&nbsp;进行编号，其中&nbsp;n&nbsp;为节点个数。A&nbsp;市所处的节点为&nbsp;s,&nbsp;B&nbsp;市所处的节点为&nbsp;t。&nbsp;</p>

<p>该部门计划在其中一些道路中安装监控设备，以降低整个道路网的响应难度。当紧急事件发生时，部门需要派遣一些人力到一些道路中进行执勤，以使得任何一条从节点&nbsp;s&nbsp;到达节点&nbsp;t&nbsp;的路径都经过至少一条监控道路（安装了监控设备或者有人执勤）。因此响应难度定义为需要派遣人力的最少道路数，以使得任何一条从&nbsp;s&nbsp;到&nbsp;t&nbsp;的路径都经过至少一条监控道路。&nbsp;</p>

<p>由于自然环境不同，在不同的道路安装监控设备的代价也可能不同。具体而言，对于一条边&nbsp;e，其安装设备的代价为&nbsp;W(e)。由于经费有限，他们希望找到一个方案，使得该道路网的响应难度不超过&nbsp;k。请你帮助他们寻找一个尽可能经济的部署方案。&nbsp;</p> 

 
 # 输入格式 
<p>输入文件的第一行为三个整数&nbsp;n，m&nbsp;和&nbsp;k，分别表示道路网中的节点数、道路数以及响应难度的上限值。&nbsp;</p>

<p>输入文件第二行包含两个整数&nbsp;s&nbsp;和&nbsp;t，表示&nbsp;A&nbsp;市与&nbsp;B&nbsp;市的节点编号。&nbsp;<br />
接下来&nbsp;m&nbsp;行，每行三个正整数&nbsp;a<sub>i</sub>，b<sub>i</sub>，w<sub>i</sub>，表示一条连接节点&nbsp;a<sub>i</sub>&nbsp;和节点&nbsp;b<sub>i</sub>的道路，其安装监控设备的费用为&nbsp;w<sub>i</sub>。&nbsp;</p> 

 
 # 输出格式 
<p>输出文件第一行包含一个值&nbsp;s，表示选手提供的方案中将在&nbsp;s&nbsp;条道路上安装监控设备。接下来&nbsp;s&nbsp;行每行包含一个整数&nbsp;p<sub>i</sub>，表示在输入文件中的第&nbsp;p<sub>i</sub>&nbsp;条道路上安装监控设备（边从&nbsp;1&nbsp;开始编号）。&nbsp;</p> 

 
 # 提示 
<h3>评分标准</h3>

<p>对于每个测试点，如果你没有输出或者输出不合法则得&nbsp;0&nbsp;分。&nbsp;</p>

<p>对于每个测试点，我们设有五个评分参数&nbsp;m1、m2、m3、m4&nbsp;和&nbsp;m5。假设选手的方案中费用为&nbsp;c，&nbsp;</p>

<p>若&nbsp;c&nbsp;&lt;&nbsp;m1，得&nbsp;12&nbsp;分；&nbsp;</p>

<p>若&nbsp;c&nbsp;=&nbsp;m1，得&nbsp;10&nbsp;分；&nbsp;</p>

<p>若&nbsp;m1&nbsp;&lt;&nbsp;c&nbsp;&le;&nbsp;m2，得&nbsp;8&nbsp;分；&nbsp;</p>

<p>若&nbsp;m2&nbsp;&lt;&nbsp;c&nbsp;&le;&nbsp;m3，得&nbsp;5&nbsp;分；</p>

<p>若&nbsp;m3&nbsp;&lt;&nbsp;c&nbsp;&le;&nbsp;m4，得&nbsp;3&nbsp;分；</p>

<p>若&nbsp;c&nbsp;&lt;&nbsp;m5，得&nbsp;1&nbsp;分；&nbsp;</p>

<p>否则，得&nbsp;0&nbsp;分。&nbsp;</p>

<p><a href="http://7xta2e.com1.z0.glb.clouddn.com/tyvj2145.zip">点击下载资源。</a></p>

<h3>资源使用方法</h3>

<p>在你的目录下有一个名为&nbsp;checker&nbsp;的程序可以用来检查你的输出，你可以在终端中使用以下命令来检查你的输出：&nbsp;</p>

<pre class="ckeditor-code vb">
./checker&nbsp;&nbsp;N</pre>

<p>其中&nbsp;N&nbsp;为测试点的编号，例如，要测试第&nbsp;3&nbsp;个测试点可以使用<br />
&nbsp;</p>

<pre class="ckeditor-code vb">
./checker&nbsp;&nbsp;3</pre>

<p><span style="line-height: 1.6em;">该程序会检测你的输出是否合法。如果方案合法，程序还会给出该方案的部</span><span style="line-height: 1.6em;">署费用总和。&nbsp;</span></p> 
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
1 3
1 2 1
2 3 10
1 3 5
</td><td>1
1</td></tr></table>
