# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;在全体船员吃饱喝得之后，三大护法决定，择日出发，但由于此前在海上漂泊200多天，船队的船只受到了极大的损坏，身体强壮的夏夜主动请缨，带领一队人马修理船只。于是，负责岛上森林维护的dp女神便带领夏夜到了岛上的原始森林。原始森林中共有n棵树。为了移花岛的可持续发展，dp女神要求夏夜只能在m个区域砍伐，我们可以将这m个区域看成m个区间，树的间距相等，都是1，我们将每个区间设为[x,y]。那么长度为k的区间中就有k棵树。树木的高度不等。现在夏夜想测量一下，每个区间树木砍伐后所得的木材量是多少，而且每次测量后他都会砍下标号为(x+y)div2的那棵作为纪念。以方便他安排人手。(同一个区间的树木可以重复砍伐，我们认为被砍过的树木高度为0)<BR>每棵树的木材量=树的高度*3.14。<BR><BR> 

 
 # 输入格式 
第一行，一个整数n。<BR>第二行，共n个整数，表示每棵树的高度<BR>第三行，一个整数m，表示共m个区间。<BR>以下m行，每个区间[x,y]的左右端点x、y。<BR><BR> 

 
 # 输出格式 
共m行，每行一个数，表示每个区间的木材量。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;结果精确到小数点后两位。<BR><BR> 

 
 # 提示 
对于30%的数据，有n&lt;=5000，m&lt;=5000；<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;对于100%的数据，有n&lt;=200000，m&lt;=200000;<BR><BR>样例解释：<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;第一次砍[1，4]的树后，森林变为：1&nbsp;0&nbsp;3&nbsp;4&nbsp;5<BR>&nbsp;&nbsp;&nbsp;<BR><BR> 
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
<tr><td>5
1 2 3 4 5
2
1 4
2 4

</td><td>31.40
21.98

</td></tr></table>
