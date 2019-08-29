<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　巫师们生活在一些国家中。他们喜欢建造城市和道路。<br/>
　　一个国家原来有k个城市，第j个城市位于点(Xj,Yj)(1&lt;=j&lt;=k)。<br/>
<br/>
<br/>
　　他们决定建造另外n-k个城市，并且第i个城市(k&lt;i&lt;=n)建造在坐<br/>
<br/>
<br/>
　　标(Xi,Yi)处。<br/>
　　X[i]=(a*X[i-1]+b) mod (10^9+9)<br/>
　　Y[i]=(c*Y[i-1]+d) mod (10^9+9)<br/>
　　这里的a,b,c,d是质数，且a!=c，b!=d<br/>
　　n个城市建造完后，巫师们发现了一些惊奇的事。结果表明任意两个不同的城市i，j都有Xi!=Xj且Yi!=Yj。城市建造完了，现在该建造道路了！他们决定用最复杂（当然，也是最强大）的符咒来建造这些道路。使用符咒建造一条联通u,v的<br/>
　　道路(Yu&gt;Yv)，当且仅当任何严格在点u，v形成的拐角中的城市w，都有一个城市s并不在u，v形成的拐角中，并且s的X坐标在w和u的之间，同时Ys&gt;Yv。<br/>
　　拐角的定义：p1(X1,Y1)，p2(X2,Y2)(Y1&lt;Y2)所形成的拐角是满足下列两个条件中的至少一个的点的集合(X,Y)。<br/>
　　·min(X1,X2)&lt;=X&lt;=max(X1,X2) and Y&gt;=Y1<br/>
　　·Y1&lt;=Y&lt;=Y2 and (X-X2)*(X1-X2)&gt;=0<br/>
<br/>
<br/>
<img width="521" height="259" src="source/tsinsen/A1468/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9aEpEYlE3WVI=.do"/><br/>
<br/>
　　这张图片表示两个不同的拐角<br/>
<br/>
<br/>
　　为了测试符咒，巫师们会把它应用于所有X坐标在[L,R]之间的城市，在道路建设完之后，国家政府想要选择最多对有道路连接的城市，并且每个城市最多被选择到一次。你的任务是对给定的m组不同的L，R来计算最多能选出的城市对数。注意不在[L,R]范围内的城市不会影响到道路建设。</div>
# 输入格式

<div class="pdcont">　　第一行包含两个由空格分开的整数n,k(1&lt;=k&lt;=n&lt;=10^5,k&lt;=30)。接下来k行输入第1到k个城市的坐标，第j行包含两个用空格隔开的整数Xj,Yj(0&lt;=Xj,Yj&lt;10^9+9)，代表第j个城市的坐标。接下来一行包含用空格隔开的整数a,b,c,d(2&lt;=a,b,c,d&lt;10^9+9)。保证这些数都是质数且a!=c,b!=d。保证任何两个城市i和j都有Xi!=Xj且Yi!=Yj成立。接下来一行包含一个整数m(1&lt;=m&lt;=10^5)，代表询问的L,R的组数。接下来m行每行两个用空格隔开的整数Li,Ri(0&lt;=Li&lt;=Ri&lt;10^9+9)，意义如上述。</div>
# 输出格式

<div class="pdcont">　　对于每组(Li,Ri)输出一行一个整数，代表最多能选出的城市对数。</div>
# 样例输入

<div class="pddata">6 6<br/>
0 0<br/>
1 1<br/>
2 2<br/>
3 3<br/>
4 4<br/>
5 5<br/>
2 3 3 2<br/>
4<br/>
0 5<br/>
1 4<br/>
2 3<br/>
3 3</div>
# 样例输出

<div class="pddata">3<br/>
2<br/>
1<br/>
0</div>
# 数据规模和约定

<div class="pdcont">　　对于所有数据1&lt;=k&lt;=n&lt;=10^5,k&lt;=30  1&lt;=m&lt;=10^5 0&lt;=Xj,Yj&lt;10^9+9 2&lt;=a,b,c,d&lt;10^9+9 0&lt;=Li&lt;=Ri&lt;10^9+9</div>

</div>