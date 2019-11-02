# 

 
 # 题目描述 
　　　这是一个古老的问题。事情发生在Rainbow&nbsp;5岁那年，他想凭借自己的力量探明山坡的形状。于是，他使用魔法获得了这座山坡的一些信息：<br>　　　1.山坡共分为N段，用1~N依次标号。所以，我们可以认为有N+1个拐点，用0~N依次标号。<br>　　　2.每段上坡都是“上升”或者“下降”的。记第i个拐点的高度为h[i]，如果第j段山坡是下降的，那么h[j]=h[j-1]-1,&nbsp;否则h[j]=h[j-1]+1.&nbsp;换句话说，对于任意i满足1&lt;=i&lt;=N，都有abs(h[i]-h[i-1])=1.<br>　　　3.由于这座山坡至少还是hill，所以，对于0&lt;=i&lt;=N，都有h[i]&nbsp;&gt;=&nbsp;0.<br>　　　4.通过拐点的高度，我们可以得出山坡的升降信息，用字符串s[1..N]表示。如果h[i]-h[i-1]=1，则s[i]=‘U’,否则s[i]=‘D’.<br>　　　现在，Rainbow已经得到了这座山坡的一部分升降信息st（即要求st必须是s的子串）以及h[0]和h[N]的高度&gt;_&lt;请你帮小Rainbow判断一下，是否存在满足条件的山坡呢~~？<br><br> 

 
 # 输入格式 
　　　第一行用空格隔开的三个整数N，h[0]，h[N]，表示山坡的总长度、h[0]的高度、h[N]的高度。<br>　　　接下来一个字符串st，表示Rainbow知道的“上升”或“下降”信息，&nbsp;‘U’表示上升，&nbsp;‘D’表示下降。<br><br> 

 
 # 输出格式 
　　　如果存在满足条件的山坡，输出一行”lala”(不含引号），否则输出一行“T_T”（不含引号）.<br><br> 

 
 # 提示 
样例解释<br>　　　对于样例1，存在唯一的合法解h[]={0,1,2,3,4}，总的升降情况为”UUUU”。<br>　　　对于样例2，存在两个合法的解：h[]={100000,100001,100000,99999,100000}，h[]={100000,99999,99998,99999,100000}.总的升降情况s分别为”UDDU”和”DDUU”。<br>　　　对于样例3，不存在合法解=&nbsp;=。<br>数据规模与约定<br>　　　对于100%的数据，1&lt;=N&lt;=100000,&nbsp;1&lt;=st的长度在&lt;=N,&nbsp;st中的每个字符都是’U’或者’D’，0&lt;=h[0],&nbsp;h[N]&nbsp;&lt;=&nbsp;100000.<br><br>From&nbsp;-&nbsp;This_poet<br>Contact&nbsp;me&nbsp;-&nbsp;This_poet@126.com/Freda.RD.Shi@gmail.com<br>This_poet's&nbsp;Blog&nbsp;-&nbsp;http://thispoet.blogcn.com<br><br> 
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
<tr><td>样例输入1
　　　4 0 4
　　　UU

样例输入2
　　　4 100000 100000 
　　　DDU

样例输入3
　　　4 0 0 
　　　DDU

</td><td>样例输出1
　　　lala


样例输出2
　　　lala


样例输出3
　　　T_T

</td></tr></table>
