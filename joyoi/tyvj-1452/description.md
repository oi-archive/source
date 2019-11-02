# 

 
 # 题目背景 
寒假来了，各科老师疯狂地留寒假作业。Sjynoip同学就面临着这些作业。<BR> 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;各科老师们疯狂地留作业。其中有些作业使人心情愉悦，有些作业使人烦闷无比；而由于作业的重要程度不同，有些作业要在做完了另外一些作业后做，比如说“默写课文”就必须在“背诵课文”之后才能完成（当然不算打表抄一遍的T_T）。<BR>&nbsp;&nbsp;&nbsp;&nbsp;现在要你来设计一个程序，选出要做的作业，来使人做完作业后心情最为高兴。<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行为总作业数n，以下又有n行，其中第i+1行的格式与含义是<BR>	Vi&nbsp;m&nbsp;N1&nbsp;N2&nbsp;…&nbsp;Nm<BR>&nbsp;&nbsp;&nbsp;&nbsp;依次为：这一份作业（第i份）对人心情指数的影响Vi（让人心情愉悦的为正，让人烦闷无比的为负，影响为（-10000≤Vi≤10000之间））；做它之前要完成的作业的份数m；做它之前要做的作业的编号N1&nbsp;N2&nbsp;N3&nbsp;…&nbsp;Nm。<BR>&nbsp;&nbsp;&nbsp;&nbsp;假设一开始的心情指数为0。寒假的时间足够做完所有选择的作业。<BR><BR>特别注解：<BR>&nbsp;1."做它之前要完成的作业"并不是指读入所有在它之前需要完成的。比如我们读入：【在a3之前需要完成a2】，而又读入：【在a2之前要完成a1】，那么a1当然也必须在a3之前完成。<BR>2.对于m&gt;1的情况，例如我们读入【a3前需要完成a2和a1】，此时a1&nbsp;a2的先后顺序是随便的。但是如果我们又读入了【a2前需要完成a1】，那么你当然就要按照a1&nbsp;a2&nbsp;a3的顺序来做作业了。<BR> 

 
 # 输出格式 
一个数，即完成作业后最高的心情指数，不超过maxlongint 

 
 # 提示 
对于50%的数据，0&lt;=m&lt;=1；<BR>对于100%的数据，0&lt;=m&lt;=n&lt;=500，-10000&lt;=vi&lt;=10000，且均为整数。来源：zsw95提供题目描述&nbsp;lydliyudong提供数据,题解和程序&nbsp;&nbsp;&nbsp;&nbsp;<BR>Tyvj&nbsp;February二月月赛第二场&nbsp;&nbsp;第4道 
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
-4 0
1 0
2 1 2
-1 2 1 2
-3 1 3
5 2 3 4</td><td>3</td></tr></table>
