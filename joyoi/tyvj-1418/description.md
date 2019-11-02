# 

 
 # 题目背景 
&nbsp;&nbsp;&nbsp;&nbsp;admin偶然在电脑中发现了这款植物大战僵尸的游戏，在游戏中经常会遇到一个纠结的问题，不知道是先种向日葵，还是攻击的植物，于是便有了本题目…… 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;&lt;注意不是NOI2009的那个植物大战僵尸哦！&gt;<BR>&nbsp;&nbsp;&nbsp;植物大战僵尸是一款非常好玩的娱乐游戏，最近admin迷上了这款游戏，为了更好的打僵尸，决定进行一些计算，而你的任务就是帮助admin计算这些。我们将植物大战僵尸这款游戏进行化简（admin只需要计算这些东西）,现在可以种的植物有n+1个，编号为0..n，第0个为向日葵，是用生产阳光的（植物没了光和作用就生长不了了），剩下的植物都是用于攻击僵尸的。每一个植物有两个参数，向日葵的两个参数为需要的阳光和单位时间可以产生的阳光（阳光供其他植物生长只用）。其他植物的两个参数为单位时间攻击力和种植所需要的阳光。<BR>&nbsp;&nbsp;&nbsp;向日葵由于种子的限制，只能种NUM个，且阳光只能在某一时刻末才能生产出来。其他植物没有数量限制，同时种植也是瞬间的，当然你也可以选择什么都不做。现在admin想知道，经过T个单位时间后，最多单位时间可以产生多少的攻击力？（本题目忽略了原游戏中的攻击范围、攻击种类、僵尸破坏植物等因素）<BR>&nbsp;&nbsp;&nbsp;本题所有操作均在单位时间开始瞬间完成，但是需要注意如果x时间种植了向日葵，由于X末才能产生出阳光，所以需要等到X+1时间才可以使用这些阳光种植植物。&nbsp;<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;输入文件的第1行有6个正整数，分别为n,t,p,need,num,s&nbsp;分别表示有n+1种植物，T为描述中的含义，p为向日葵单位时间可以产生的阳光，need为种植一个向日葵所需要的阳光,NUM为向日葵种子的个数,s为初始状态的阳光数。后第2行到第n+1行，第i行有两个整数，分别表示编号为i-1这个植物种植所需要的阳光w[i]和单位时间可以产生的攻击力v[i]。<BR> 

 
 # 输出格式 
输出文件仅一行，为你帮admin计算出的结果 

 
 # 提示 
数据范围约定：<BR>40%的数据&nbsp;&nbsp;N&lt;=20&nbsp;&nbsp;T&lt;=20&nbsp;<BR>50%的数据&nbsp;&nbsp;N&lt;=100&nbsp;&nbsp;T&lt;=30<BR>60%的数据&nbsp;&nbsp;N&lt;=200&nbsp;&nbsp;T&lt;=100<BR>70%的数据&nbsp;&nbsp;N&lt;=500&nbsp;&nbsp;T&lt;=500<BR>100%的数据&nbsp;N&lt;=1000&nbsp;&nbsp;T&lt;=1000<BR>对于全部数据S&lt;=1000&nbsp;&nbsp;&nbsp;NUM&lt;=100&nbsp;&nbsp;P&lt;=1000&nbsp;&nbsp;NEED&lt;=1000&nbsp;&nbsp;w[i]&lt;=10000&nbsp;&nbsp;v[i]&lt;=10000<BR>保证最终答案在1000W以内<BR><BR>完全原创&nbsp;from&nbsp;admin<BR> 
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
<tr><td>2 1 4 5 1 5
5 10
4 3
</td><td>10
</td></tr></table>
