# 

 
 # 题目背景 
某年某月某日，某人在某地用某电脑上的FC模拟器打SMB(超级马里奥兄弟)。<BR>但是他想得到最高的分数，又想顺利通关...无奈之下，只好找到了你来帮助他-&nbsp;- 

 
 # 题目描述 
游戏场景由4种方块组成：<BR>1.地面(用*代表)<BR>2.金币(用0(数字)代表)<BR>3.可以自由行动的空间(用.代表)<BR>4.敌人(用R代表)(敌人也能算做"方块"么...)<BR><BR>其中，出发点在S点，终点是E，注意，只有到达与终点处于同一列的地方才算有分数，如果到达不了则记为0分。<BR>每获得一次同种奖励(金币或杀掉怪物)，Mario所获得的分数会翻一番(上限为25600，起始值为200)。但是注意:吃一次金币再踩掉一次怪物再吃金币不可以获得加成。反之亦然(悲催啊~)<BR>我们规定Mario跳跃高度为h,跳跃持续时间为s,且跳跃是类似这样的过程：<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(0&lt;p&lt;s+1)<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|---p---|<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;h&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|<BR>-----&gt;-|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|--------&gt;<BR><BR>为了简化问题，Mario只能向前移动，速度为1。且重力是瞬间可以将其压到地上的，无论原先高度有多高(...好Xe...没有~这算个*啊是不)，且敌人不能移动。<BR>落到地面以下就算0分，碰到怪物也算0分(踩死不算)。<BR>现在，请你帮他通过程序计算出：对于一个关卡，可以获得的的最大得分。 

 
 # 输入格式 
第一行4个整数,m,n,h,s,其中m,n(1&lt;=m,n&lt;=50)表示地图的长与高,h与s含义如题。<BR>接下来的矩阵大小m*n,表示地图。 

 
 # 输出格式 
一个数，即能获得的最大分数。<BR> 
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
<tr><td>10 5 4 2
.ooo..ooo.
.***..***.
..........
S...RR...E
**********</td><td>12600</td></tr></table>
