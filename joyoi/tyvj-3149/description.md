# 

 
 # 题目描述 
<p>
　　转眼之间，新学期已经过去几个月了，F大学计算机系的W教授决定对他的学生进行一次测试。为了测试学生对树结构的认识，同时也检验他们的编程能力，教授把测试的内容定为：要求学生们编程按编号顺序打印出节点个数不少于m的所有二叉树。<br>　　二叉树编号规则如下：<br>　　仅有一个元素的树编号为1。<br>　　当满足以下条件之一时，定义二叉树a的编号比b大：<br>　　　　1． a的节点数比b多。<br>　　　　2． 若a的节点数与b相等，且a的左子树编号比b的左子树大。<br>　　　　3． a的节点数和左子树编号都和b相等，且a的右子树编号比b的右子树大。<br>　　二叉树的元素用大写X表示。<br>　　例如：<br><br><center><img src="/source/joyoi/tyvj-3149/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzE0OS9wcm9ibGVtc19pbWFnZXMvMTQzNi8xLmJtcA==.bmp"></img></center>　　　 <br>　　打印二叉树的格式为：<br>　　（ 左子树 ）{若左子树为空，则省略} X{根} （ 右子树 ）{若右子树为空，则省略}<br>　　例如在上图中，编号为2 的树可表示为：X（X）；<br>　　　　　　　　　编号为3 的树可表示为：（X）X；<br>　　　　　　　　　编号为5 的树可表示为：X（（X）X）；<br>　　当然当m较大时，检验答案对错的工作也是很繁重的，所以教授只打算对其中的若干个编号的二叉树进行抽查，他想麻烦你在测试开始前把标准答案先准备好（教授的测试卷会事先交给你）。<br></p> 

 
 # 输入格式 
<p>
　　输入文件为教授的测试卷，至少1行，至多10行，每行一个数N（1<=N<=10^8）,即要抽查的二叉树的编号，以零结束。</p> 

 
 # 输出格式 
<p>
　　输出文件是你求出的标准答案，对每一个编号输出其对应的二叉树，每个二叉树占一行，零不用输出。</p> 
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
<tr><td>2
5
0
</td><td>X（X）
X（（X）X）</td></tr></table>
