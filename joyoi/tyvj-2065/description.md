# 

 
 # 题目背景 
“圣主applepi于公元2011年9月创造了Nescafe，它在散发了16次光辉之后与公元2011年11月12日被封印为一颗魂珠，贮藏于Nescafe神塔之中。公元2012年9月，圣主带领四大护法重启了Nescafe，如今已经是Nescafe之魂的第30次传播了。不久，它就要被第二次封印，而变成一座神杯……”applepi思索着Nescafe的历史，准备着第二次封印。 

 
 # 题目描述 
Nescafe由n种元素组成（编号为1~n），第i种元素有一个封印区间[ai,bi]。当封印力度E小于ai时，该元素将获得ai的封印能量；当封印力度E在ai到bi之间时，该元素将获得E的封印能量；而当封印力度E大于bi时，该元素将被破坏从而不能获得任何封印能量。现在圣主applepi想选择恰当的E，使得封印获得的总能量尽可能高。为了封印的最后一击尽量完美，就请你写个程序帮他计算一下吧！ 

 
 # 输入格式 
第一行一个整数N。<br>接下来N行每行两个整数ai、bi，第i+1行表示第i种元素的封印区间。 

 
 # 输出格式 
两个用空格隔开的整数，第一个数是能够获得最多总能量的封印力度E，第二个数是获得的总能量大小。当存在多个E能够获得最多总能量时，输出最小的E。 

 
 # 提示 
对于&nbsp;50%&nbsp;的数据，1&lt;=N&lt;=1000，1&lt;=ai&lt;=bi&lt;=10000。&nbsp;<br>对于&nbsp;100%&nbsp;的数据，1&lt;=N&lt;=10^5，1&lt;=ai&lt;=bi&lt;=10^9。 
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
5 10
20 25
</td><td>10 30</td></tr></table>
