# 题目描述


<p>
	<span style="font-family:Microsoft YaHei;font-size:18px;">试题二:工业时代 </span><br/>
<br/>
<span style="font-family:Microsoft YaHei;font-size:18px;">【试题描述】 </span><br/>
<span style="font-family:Microsoft YaHei;font-size:18px;">小FF的第一片矿区已经开始运作了， 他着手开展第二片矿区…… </span><br/>
<span style="font-family:Microsoft YaHei;font-size:18px;">小FF的第二片矿区， 也是”NewBe_One“计划的核心部分，因为在这片矿区里面有全宇宙最稀有的两种矿物，科学家称其为NEW矿和BE矿。 </span><br/>
<span style="font-family:Microsoft YaHei;font-size:18px;">矿区是被划分成一个n*m的矩形区域。 小FF探明了每一小块区域里的NEW矿和BE矿的蕴藏量， 并且小FF还在矿区的北边和西边分别设置了NEW矿和BE矿的收集站。你的任务是设计一个管道运输系统，使得运送的NEW矿和BE矿的总量最多。 </span><br/>
<span style="font-family:Microsoft YaHei;font-size:18px;">管道的型号有两种，一种是东西向，一种是南北向。在一个格子内你能建造一种管道，但不能两种都建。如果两个同类型管道首位相接，它们就可以被连接起来。 </span><br/>
<span style="font-family:Microsoft YaHei;font-size:18px;">另
外这些矿物都十分不稳定，因此它们在运送过程中都不能拐弯。这就意味着如果某个格子上建有南北向管道，但是它北边的格子建有东西向管道，那么这根南北向管
道内运送的任何东西都将丢失。进一步地，运到NEW矿收集站的BE矿也会丢失，运到BE矿收集站的NEW矿也会丢失。 </span><br/>
<span style="font-family:Microsoft YaHei;font-size:18px;"></span><img src="/upload/image/20120814/20120814171046_77637.png" alt=""/><br/>
<span style="font-family:Microsoft YaHei;font-size:18px;">【输入格式】 </span><br/>
<span style="font-family:Microsoft YaHei;font-size:18px;">第一行包含两个整数n和m，表示矿区大小。 </span><br/>
<span style="font-family:Microsoft YaHei;font-size:18px;">以下n行，每行m个整数，其中第i行第j个整数G[ i , j ] 描述各个格子上的BE矿数量。接下来以类似的矩阵表示各个格子上的NEW矿数量。 </span><br/>
<span style="font-family:Microsoft YaHei;font-size:18px;">【输出格式】 </span><br/>
<span style="font-family:Microsoft YaHei;font-size:18px;">仅一个整数， 表示最多可以采集到的NEW矿和BE矿的总量。 </span><br/>
<span style="font-family:Microsoft YaHei;font-size:18px;">【输入样例】 </span><br/>
<span style="font-family:Microsoft YaHei;font-size:18px;">4 4 </span><br/>
<span style="font-family:Microsoft YaHei;font-size:18px;">0 0 10 9 </span><br/>
<span style="font-family:Microsoft YaHei;font-size:18px;">1 3 10 0 </span><br/>
<span style="font-family:Microsoft YaHei;font-size:18px;">4 2 1 3 </span><br/>
<span style="font-family:Microsoft YaHei;font-size:18px;">1 1 20 0 </span><br/>
<span style="font-family:Microsoft YaHei;font-size:18px;">10 0 0 0 </span><br/>
<span style="font-family:Microsoft YaHei;font-size:18px;">1 1 1 30 </span><br/>
<span style="font-family:Microsoft YaHei;font-size:18px;">0 0 5 5 </span><br/>
<span style="font-family:Microsoft YaHei;font-size:18px;">5 10 10 10 </span><br/>
<span style="font-family:Microsoft YaHei;font-size:18px;">【输出样例】 </span><br/>
<span style="font-family:Microsoft YaHei;font-size:18px;">98 </span><br/>
<span style="font-family:Microsoft YaHei;font-size:18px;">【数据范围】 </span><br/>
<span style="font-family:Microsoft YaHei;font-size:18px;">对于30%的数据： 0&lt;= n，m &lt;=100; </span><br/>
<span style="font-family:Microsoft YaHei;font-size:18px;">对于100%的数据： 0&lt;= n, m &lt;=1000; </span><br/>
<span style="font-family:Microsoft YaHei;font-size:18px;">0&lt;= G[ i, j ] &lt;=1000.</span> 
</p>
