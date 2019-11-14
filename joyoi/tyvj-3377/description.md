# 

 
 # 题目描述 
<p>
恶魔城（SATANIC.pas\c\cpp）<br><br>【题目描述】<br>　　上帝需要创造一位战士去消灭撒旦，这位战士必须要穿过恶魔城才能与撒旦决斗。恶魔城内有M条连接N个路口（从1到N编号）的街道，每一条街道都是单向的（也就是说你不能逆着该街道指定的方向走），并且在城内无论怎么走都不可能走回原来走过的地方。开始的时候，战士的生命力（HP）为INITHP、站在１号路口，而撒旦在第N号路口等待着他。每一条街道上都有许多魔鬼，但是也有一些街道已经被上帝派去的天使占领了。当战士经过连接i号向j号路口的街道时，如果占领该街道的是恶魔，那么他的HP先加倍然后减少L[i,j]，我们记为A[i,j]=-L[i,j]；如果占领该街道的是天使，那么他的HP就会先加倍然后增加L[i,j]，我们记为A[i,j]=+L[i,j]；如果该街道不存在，那么A[i,j]=0。如果某一时刻战士的HP<=0，那么他会死亡。因为这个战士将非常无敌，当他见到撒旦的时候只要还活着，就能一口气把撒旦消灭，所以上帝不希望让他的INITHP过高。</p> 

 
 # 输入格式 
<p>
　　输入文件SATANIC.in给定N，A[1..N,1..N]，求最小的INITHP，使这个战士能够活着见到撒旦。<br><br></p> 

 
 # 输出格式 
<p>
　　输出文件SATANIC.out输出所求最小的INITHP。</p> 
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
<tr><td>4
0 -4 0 –10
0 0 +3 0
0 0 0 –14
0 0 0 0
</td><td>4</td></tr></table>
