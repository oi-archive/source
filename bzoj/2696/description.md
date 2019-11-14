
# Description

<div class="content"><p><span style="font-size: medium">神犇航空有K架飞机，为了简化问题，我们认为每架飞机都是相同的。神犇航空的世界中有N个机场，以0..N-1编号，其中0号为基地机场，每天0时刻起飞机才可以从该机场起飞，并不晚于T时刻回到该机场。一天，神犇航空接到了M个包机请求，每个请求为在s时刻从a机场起飞，在恰好t时刻到达b机场，可以净获利c。设计一种方案，使得总收益最大。<br/>
</span></p></div>

# Input

<div class="content"><div class="pdcont"><span style="font-size: medium">　　第一行，4个正整数N,M,K,T，如题目描述中所述；<br/>
　　以下N行，每行N个整数，描述一个N*N的矩阵t，t­<sub>i,j</sub>表示从机场i空载飞至机场j，需要时间t<sub>i,j</sub>；<br/>
　　以下N行, 每行N个整数，描述一个N*N的矩阵f，f­<sub>i,j</sub>表示从机场i空载飞至机场j，需要费用f<sub>i,j</sub>；<br/>
　　以下M行，每行5个整数描述一个请求，依次为a,b,s,t,c。<br/>
</span></div></div>

# Output

<div class="content"><div class="pdcont"><span style="font-size: medium">　　仅一行，一个整数，表示最大收益。<br/>
</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">2 1 1 10<br/>
0 5<br/>
5 0<br/>
0 5<br/>
5 0<br/>
0 1 0 5 10<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>数据规模及约定<br/><br/>
　　对于10%的测试数据，K=1；<br/><br/>
　　另有20%的测试数据，K=2；<br/><br/>
　　对于全部的测试数据，N,M&lt;=200，K&lt;=10，T&lt;=3000，ti,j&lt;=200，fi,j&lt;=2000，0&lt;=a,b&lt;N，0&lt;=s&lt;=t&lt;=T，0&lt;=c&lt;=10000，ti,i=fi,i=0，ti,j&lt;=ti,k+tk,j，fi,j&lt;=fi,k+fk,j。<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

