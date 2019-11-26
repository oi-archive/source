# 

 
 # 题目描述 
　　　外星人有n只眼睛，排成一排，从左到右标号为1&nbsp;to&nbsp;n.&nbsp;他睡觉的时候会给自己带上眼罩，每个眼罩的内侧都有一个大写字母。当他早上起来睁开眼睛时，他想看到beautiful&nbsp;words.<br>　　　外星人还有一个习惯就是，睁眼时他会选择四个数字a,&nbsp;b,&nbsp;c,&nbsp;d,&nbsp;(1&lt;=&nbsp;a&nbsp;&lt;=&nbsp;b&nbsp;&lt;&nbsp;c&nbsp;&lt;=&nbsp;d&nbsp;&lt;=&nbsp;n)&nbsp;，他将睁开在a&nbsp;&lt;=&nbsp;i&nbsp;&lt;=&nbsp;b&nbsp;和c&nbsp;&lt;=&nbsp;i&nbsp;&lt;=&nbsp;d这个范围内的所有眼睛。设一个beautiful&nbsp;word为字符串s，并且把外星人从左到右看到的字母按顺序拼接成一个字符串串t，如果s和t相同，那么我们认为外星人能够看到s这个beautiful&nbsp;word。你知道他心目中有m个beautiful&nbsp;word。请问在他现在带这个眼罩，任意选择a,b,c,d四个数字的时候，他睁开眼可能看到的beautiful&nbsp;word有多少个？ 

 
 # 输入格式 
第一行是一个长度为n的字符串s，表示眼罩上的字母。<br>第二行包含一个整数m，表示beautiful&nbsp;words的个数。<br>接下来的m行，每行一个beautiful&nbsp;words，pi，全由大写字母组成。<br>由于n可以由s的长度间接得出，故不给出n的大小。 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;只有一个整数，可能看到的beautiful&nbsp;words&nbsp;的个数 

 
 # 提示 
样例解释<br>&nbsp;&nbsp;&nbsp;&nbsp;外星人能够看到ABBA这个beautiful&nbsp;word，此时选择的a、b、c、d的值可能是1,2,4,5或1,2,6,7<br>数据范围与约定<br>&nbsp;&nbsp;&nbsp;&nbsp;对于100%的数据，0&lt;n&lt;=10000.From&nbsp;-&nbsp;This_poet<br>Contact&nbsp;me&nbsp;-&nbsp;This_poet@126.com/Freda.RD.Shi@gmail.com<br>This_poet's&nbsp;Blog&nbsp;-&nbsp;http://thispoet.blogcn.com 
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
<tr><td>ABCBABA
2
BAAB
ABBA
</td><td>1
</td></tr></table>
