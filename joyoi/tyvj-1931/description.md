# 

 
 # 题目背景 
applepi捧着编年史,翻啊翻,发现了小猫Freda的故事……<BR>这天，Freda显得无聊，在家自己玩…… 

 
 # 题目描述 
Freda的家在一座有N个节点的树形城堡里。Freda在每个节点（节点标号为1-N，规定1号节点恒为根）上摆放了一个棋子。棋子的颜色只有黑色和白色两种。初始时棋子都是白色，Freda可以随意选定一个节点上的棋子并改变它的颜色。Freda又想在任意时刻知道某棵子树中白色棋子的个数……<BR>于是在编年史的下一页上，applepi&nbsp;“被”发现了这个问题。由于applepi&nbsp;还要忙着看编年史，所以这个任务就交给你了。 

 
 # 输入格式 
第一行为节点数N<BR>之后N-1行给出&nbsp;a,b&nbsp;表示a到b有一条边<BR>之后一行为一个整数M，表示操作的数目<BR>接下来M行<BR>若格式为&nbsp;“C&nbsp;x”，表示Freda选定了x号节点并把它改变颜色<BR>若格式为&nbsp;“Q&nbsp;x”，表示Freda要统计x号节点及其子树中白色棋子的个数 

 
 # 输出格式 
对于每个统计操作,输出一个整数表示以给出节点为根的子树中白色棋子的个数。 

 
 # 提示 
对于30%的数据&nbsp;n&nbsp;≤&nbsp;100,&nbsp;m&nbsp;≤&nbsp;100;<BR>对于50%的数据&nbsp;n&nbsp;≤&nbsp;1000,&nbsp;m&nbsp;≤&nbsp;1000;<BR>对于100%的数据&nbsp;n&nbsp;≤&nbsp;100,000&nbsp;&nbsp;m&nbsp;≤&nbsp;100,000&nbsp;<BR> 
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
<tr><td>3
1 2
1 3
3
Q 1
C 2
Q 1
</td><td>3
2
</td></tr></table>
