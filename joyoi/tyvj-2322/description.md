# 

 
 # 题目描述 
<p>
两个人A,B玩游戏,A先走,B后走.<br>每次操作是任意选一个1~N中的数,再它累加到C上,C的初值为0.<br>加完后C必须是质数,如果谁使得当前的C不是质数则输掉.不妨认<br>为B是天才一个,他的策略总是完美的.现在你要如何才能打败他.<br>例如N=5时.<br>你可以选3,则C=3<br>B可以选2,C=5<br>你此时如果选5,则C=10,你就输掉了.<br></p> 

 
 # 输入格式 
<p>
第一行一个数据T,T<=10000表示有T组数据.<br>接下来每行一个整数N,1<N<=1000<br><br></p> 

 
 # 输出格式 
<p>
针对每个数据,如果B获胜则输出"B",反之输出"A",并且输出一个数字Num<br>表示你第一步选择Num将获得胜利.如果存在多个解,输出最小的那个.<br></p> 
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
3
4

</td><td>A 3
B</td></tr></table>
