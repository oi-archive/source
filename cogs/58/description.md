# 题目描述


<b><span style="font-size:large;">题目描述</span></b> 
<div>
有一座延绵不断、跌宕起伏的山，最低处海拔为0，最高处海拔不超过8848米，从这座山的一端走到另一端的过程中，每走1米海拔就升高或降低1米。有Q个登山队计划在这座山的不同区段登山，当他们攀到各自区段的最高峰时，就会插上队旗。请你写一个程序找出他们插旗的高度。
</div>
<div>
 
</div>
<div>
<b>输入文件</b> 
</div>
<div>
 
</div>
<div>
第1行，一个整数N(N&lt;=10^6)，表示山两端的跨度。
</div>
<div>
接下来N+1行，每行一个非负整数Hi，表示该位置的海拔高度，其中H<sub>0</sub>=H<sub>n</sub>=0。
</div>
<div>
然后是一个正整数Q(Q&lt;=7000)，表示登山队的数量。
</div>
<div>
接下来Q行，每行两个数Ai, Bi，表示第i个登山队攀爬的区段[Ai,Bi]，其中0&lt;=Ai&lt;=Bi&lt;=N。
</div>
<div>
 
</div>
<div>
<b>输出文件</b> 
</div>
<div>
 
</div>
<div>
Q行，每行为一个整数，表示第i个登山队插旗的高度。
</div>
<div>
 <span><!--[if gte vml 1]>
<![endif]--><br/>
<!--[if gte mso 9]><![endif]--></span> 
</div>
<div>
<b>样例输入</b> 
</div>
<div>
10
</div>
<div>
0
</div>
<div>
1
</div>
<div>
2
</div>
<div>
3
</div>
<div>
2
</div>
<div>
3
</div>
<div>
4
</div>
<div>
3
</div>
<div>
2
</div>
<div>
1
</div>
<div>
0
</div>
<div>
5
</div>
<div>
0 10
</div>
<div>
2 4
</div>
<div>
3 7
</div>
<div>
7 9
</div>
<div>
8 8
</div>
<div>
 
</div>
<div>
<b>样例输出</b> 
</div>
<div>
4
</div>
<div>
3
</div>
<div>
4
</div>
<div>
3
</div>
<div>
2
</div>
<p>
 
</p>
