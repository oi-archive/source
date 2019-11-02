# 

 
 # 题目背景 
太原成成中学第3次模拟赛&nbsp;第4题 

 
 # 题目描述 
Mrs.Chen是一个很认真很称职的语文老师&nbsp;......<BR>所以,当她看到学生作文里的人物关系描述得非常的麻烦的时候,她非常生气,于是宣布:凡是作文里有冗余关系的,一率罚抄出师表10次...同学们非常的恐惧,于是,每当他们写出一篇作文,都要拿来你这个语文兼OI天才这里,问你有没有冗余的关系&nbsp;......&nbsp;时间一久,你也烦了,于是就想写个程序来代劳&nbsp;...<BR><BR>现在这里有一篇作文,有n句描述人物关系的句子,描述了n个人的关系<BR>每条句子的定义是这样的<BR>X&nbsp;Y<BR>它的意思是:X认识Y&nbsp;Y也认识X<BR><BR>现在要你求出文中冗余关系的数目.<BR><BR>注意:&nbsp;假如A认识B,B认识C,则A也认识C<BR><BR>冗余关系的定义是指&nbsp;:&nbsp;即使没有这条关系,原图的所有关系照样成立.<BR> 

 
 # 输入格式 
第一行,两个整数,表示句子数量(n)，表示人数(m)。<BR>接下来n行,每行两个数,意义在描述里已经说了.&nbsp; 

 
 # 输出格式 
一个整数,表示冗余关系的数目.<BR> 

 
 # 提示 
1&lt;=n,m&lt;=1000<BR>感谢Vivian&nbsp;Snow提供原创题目，admin，tcboy修改题目、数据 
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
<tr><td>3 3
1 2
1 3
2 3
</td><td>1</td></tr></table>
