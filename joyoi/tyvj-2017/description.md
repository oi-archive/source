# 

 
 # 题目描述 
　　　这是一个古老的问题。钢琴10级的Rainbow好久都没有练习钢琴了，他想借助魔法迅速恢复自己的功力。于是，他翻出了一本魔法书，上面详细地给出了恢复功力的方法。<br>　　　魔法书是这样写的：“要恢复功力，你必须找到魔法师Freda，Freda会给你N个数字，第i个数字用a[i]表示。你可以进行无数次替换操作，直到你满意为止。每次替换操作，你可以选择两个数字p和q&nbsp;(p、q不相等）并用a[p]&nbsp;xor&nbsp;a[q]来替换掉a[p]。最后，你能够获得的功力就是Sigma{a[i]}(1&lt;=i&lt;=n)”。<br>　　　Rainbow当然想尽可能多的恢复他的功力了，Freda也想帮助Rainbow尽可能多的恢复功力。但是他们都弱爆了有木有！他们都不知道Rainbow最大可能获得的功力是多少T_T。请你来帮助他们。<br><br> 

 
 # 输入格式 
　　　第一行一个整数N，表示Freda给出的数字个数。<br>　　　接下来N行一行一个整数，第i+1行的数字表示a[i].<br><br> 

 
 # 输出格式 
　　　一行一个整数Ans，表示Rainbow最多能恢复的功力。<br><br> 

 
 # 提示 
样例解释<br>　　　一种可能的替换过程如下：<br>　　　Freda给出数字的时候，a[1]=1,&nbsp;a[2]=2,&nbsp;a[3]=3.<br>　　　Rainbow的第一次替换，用a[1]&nbsp;xor&nbsp;a[2]&nbsp;替换掉a[2]，&nbsp;此时a[1]=1,&nbsp;a[2]=3,&nbsp;a[3]=3.<br>　　　Rainbow的第二次替换，用a[1]&nbsp;xor&nbsp;a[2]&nbsp;替换掉a[1],&nbsp;此时a[1]=2,&nbsp;a[2]=3,&nbsp;a[3]=3.<br>　　　再怎么替换也不可能使数字的总和增大了，所以答案为8.<br>数据规模与约定<br>　　　对于10%的数据，N&lt;=5.<br>　　　对于30%的数据，N&lt;=100.<br>　　　对于60%的数据，N&lt;=1000.<br>　　　对于100%的数据，N&lt;=100000,&nbsp;0&lt;=&nbsp;a[i]&nbsp;&lt;=&nbsp;10^12.<br><br>From&nbsp;-&nbsp;This_poet<br>Contact&nbsp;me&nbsp;-&nbsp;This_poet@126.com/Freda.RD.Shi@gmail.com<br>This_poet's&nbsp;Blog&nbsp;-&nbsp;http://thispoet.blogcn.com<br><br> 
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
1 
2 
3


</td><td>8


</td></tr></table>
