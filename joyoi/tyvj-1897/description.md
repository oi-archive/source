# 

 
 # 题目描述 
已知有两个字串&nbsp;A$,&nbsp;B$&nbsp;及一组字串变换的规则（至多6个规则）:<BR>　　A1$&nbsp;-&gt;&nbsp;B1$<BR>　　A2$&nbsp;-&gt;&nbsp;B2$<BR>　　规则的含义为：在&nbsp;A＄中的子串&nbsp;A1$&nbsp;可以变换为&nbsp;B1$、A2$&nbsp;可以变换为&nbsp;B2$&nbsp;…。<BR>　　例如：A$＝'abcd'　B$＝'xyz'<BR>　　变换规则为：<BR>　　‘abc’-&gt;‘xu’　‘ud’-&gt;‘y’　‘y’-&gt;‘yz’<BR><BR>　　则此时，A$&nbsp;可以经过一系列的变换变为&nbsp;B$，其变换的过程为：<BR>　　‘abcd’-&gt;‘xud’-&gt;‘xy’-&gt;‘xyz’<BR><BR>　　共进行了三次变换，使得&nbsp;A$&nbsp;变换为B$。 

 
 # 输入格式 
第一行A$&nbsp;B$<BR>下面的行为变化规则<BR>A1$&nbsp;B1$&nbsp;\<BR>A2$&nbsp;B2$&nbsp;|-&gt;&nbsp;变换规则<BR>...&nbsp;...&nbsp;/&nbsp;<BR>所有字符串长度的上限为&nbsp;20。 

 
 # 输出格式 
若在&nbsp;10&nbsp;步（包含&nbsp;10步）以内能将&nbsp;A$&nbsp;变换为&nbsp;B$&nbsp;，则输出最少的变换步数；<BR>否则输出"NO&nbsp;ANSWER!" 

 
 # 提示 
Noip2002提高组第2题 
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
<tr><td>abcd xyz
abc xu
ud y
y yz
</td><td>3
</td></tr></table>
