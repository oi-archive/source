# 

 
 # 题目背景 
连云港市2011NOIP第一场模拟赛&nbsp;第三题 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;诸葛亮无聊的时候喜欢带兵去进攻魏国，他的手下共有N名武将，每名武将都有一个武力值Ai。由于武将整天不学数学，他们的武力值不能被超过15的质数整除。可是有M对武将存在矛盾，有矛盾的武将不能同时出征。所以诸葛亮需要消除他们之间的矛盾。(定义武将x，y之间存在矛盾当且仅当他们的武力值之积Ax*Ay的约数个数不是奇数)<BR>&nbsp;&nbsp;&nbsp;&nbsp;智慧的诸葛亮想出了一个办法来消除矛盾。具体的做法是:花费C*DS(k)个金币，使某名武将的武力值由Ai变为Ai*k(k为正整数)。(C为给定常数，DS(k)表示k的约数个数)。(可以对任意武将进行任意次操作)<BR>现在诸葛亮想知道他最少需要花费多少金币才能消除武将之间的矛盾，使得他们顺利出征。<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行两个正数N和C。(N为武将的个数，C为描述中的给定常数)<BR>&nbsp;&nbsp;&nbsp;&nbsp;第二行N个正整数，表示A1…AN。(表示N名武将的武力值)<BR>&nbsp;&nbsp;&nbsp;&nbsp;数据保证任意Ai无法被大于15的质数整除。<BR>&nbsp;&nbsp;&nbsp;&nbsp;第三行一个正整数M。(矛盾个数)<BR>&nbsp;&nbsp;&nbsp;&nbsp;以下M行每行两个正整数x，y，表示武将x，y之间存在矛盾。(可能本身已经满足DS(Ax*Ay)为奇数)<BR> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;输出一个正整数，最少需要花费的金币数。（若无解则输出&nbsp;-1） 

 
 # 提示 
[样例解释]<BR>将3号武将的能力值扩大为原来的15倍;<BR>15&nbsp;的约数为1&nbsp;3&nbsp;5&nbsp;15，共4个。因此，费用&nbsp;=&nbsp;4×3&nbsp;=&nbsp;12;<BR>将2号武将的能力值扩大为原来的3倍;<BR>3&nbsp;的约数为&nbsp;1&nbsp;3，共2个。因此，费用&nbsp;=&nbsp;2×3&nbsp;=&nbsp;6;<BR>操作过后N个数分别为&nbsp;2&nbsp;18&nbsp;450&nbsp;50&nbsp;8，可以消除所有矛盾;<BR>总的费用为12&nbsp;+&nbsp;6&nbsp;=&nbsp;18;&nbsp;这是最优方案。<BR>	<BR><BR>[数据规模]<BR>10%的数据，&nbsp;1&nbsp;&lt;&nbsp;Ai&nbsp;&lt;&nbsp;4，N&nbsp;&lt;&nbsp;15，M&nbsp;&lt;&nbsp;100<BR>30%的数据，&nbsp;N&nbsp;≤&nbsp;15，M&nbsp;≤&nbsp;100；<BR>50%的数据，&nbsp;N&nbsp;≤&nbsp;100，M&nbsp;≤&nbsp;1000；<BR>60%的数据，&nbsp;N&nbsp;≤&nbsp;1000，M&nbsp;≤&nbsp;5000；<BR>对于另外10%的数据，&nbsp;M=N-1，任意一个Ai必然与他人有矛盾&nbsp;且&nbsp;1&nbsp;&lt;&nbsp;Ai&nbsp;&lt;&nbsp;4；<BR>对于另外10%的数据，&nbsp;M=N-1，任意一个Ai必然与他人有矛盾；<BR>100%的数据，&nbsp;N&nbsp;≤&nbsp;100000，M&nbsp;≤&nbsp;200000，C&nbsp;&lt;&nbsp;10，任意Ai无法被大于15的质数整除。<BR> 
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
<tr><td>5 3
2 6 30 50 8
3
3 4
1 2
1 3
</td><td>18</td></tr></table>
