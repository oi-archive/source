# 题目描述


<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">dd_engi 所在的TIANYI 公司要举办一次盛大的公司聚会。可惜的是，由于场地和花费</span><br/>
<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">的原因，不可能所有人都参加。现在的任务是拟定参加聚会人员的名单。</span><br/>
<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">TIANYI 公司的组织架构可以看做一棵有根多叉树。也就是说，在编号为1~N 的所有N</span><br/>
<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">名员工中，除了最高管理者（编号为1）以外，每个员工都有且仅有一位直接上司；最高管</span><br/>
<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">理者则是这棵多叉树的“根”。这很好理解，对吗？另外，我们保证，员工的编号会大于他</span><br/>
<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">的直接上司的编号。</span><br/>
<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">不同的员工对于聚会有着不同的要求，事实上，若邀请第i 位员工（编号为i），在聚会</span><br/>
<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">中满足他的要求需要花费Ci 元。另一方面，不同的员工在聚会中的“兴奋指数”也不同，</span><br/>
<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">第i 位员工参加聚会的兴奋指数是Ei。</span><br/>
<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">选择参加聚会的人员还有一个限制：为了使参加聚会的员工能够尽量放松，若邀请了某</span><br/>
<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">位员工，就不能邀请他的任何一位上司。这里“上司”的定义是这样的：最高管理者没有上</span><br/>
<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">司，其余所有员工的直接上司以及直接上司的所有上司都是他的上司。换句话说，某位员工</span><br/>
<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">的上司就是树中从他的节点走到根节点的路径上经过的所有节点（包括根结点，但不包括他</span><br/>
<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">自身）。</span><br/>
<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">在满足上述限制的前提下，dd_engi 希望参加聚会人员的兴奋指数之和最大，但同时他</span><br/>
<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">被告知，满足所有参加聚会人员的要求的总花费不得超过M 元。那么，参加聚会人员的名</span><br/>
<p>
	<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">单究竟应该怎样确定才最优呢？你需要求出的是最大的总兴奋指数。</span>
</p>
<p>
	<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;"><br/>
</span>
</p>
<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">【输入格式】</span><br/>
<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">第一行，两个空格隔开的整数，N 与M。</span><br/>
<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">第二行，N-1 个整数，分别是第2 位至第N 位员工的直接上司的编号。</span><br/>
<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">第三行，N 个整数，分别是C1、C2……CN。</span><br/>
<p>
	<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">第四行，N 个整数，分别是E1、E2……EN。</span>
</p>
<p>
	<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;"><br/>
</span>
</p>
<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">【输出格式】</span><br/>
<p>
	<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">只需输出一行一个整数，即最大的总兴奋指数。</span>
</p>
<p>
	<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;"><br/>
</span>
</p>
<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">【样例输入】</span><br/>
<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">10 100</span><br/>
<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">1 2 2 1 4 3 5 6 1</span><br/>
<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">12 53 127 32 164 22 199 10 19 17</span><br/>
<p>
	<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">-1 0 3 5 7 -2 9 6 8 13</span>
</p>
<p>
	<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;"><br/>
</span>
</p>
<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">【样例输出】</span><br/>
<p>
	<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">27</span>
</p>
<p>
	<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;"><br/>
</span>
</p>
<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">【数据范围】</span><br/>
<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">30%的数据满足N&lt;=20。</span><br/>
<span style="white-space:nowrap;font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">100%的数据满足1 &lt;= N &lt;= 1024, 0 &lt;= M &lt;= 109, 0 &lt;= Ci &lt;= 1024, -1024 &lt;= Ei &lt;= 1024。</span><br/>
