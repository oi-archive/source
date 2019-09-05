# 题目描述


<p>
<strong>问题描述</strong> 
</p>
<p>
一年一度的GaoDaoKuOI(GDKOI)，一个有趣的程序设计比赛，几周前刚刚结束。黑叔原以为自己将是评委，结果却成了个调度员，这个工作让他很烦恼，倒底发生了什么呢？<br/>
在比赛期间，选手们希望能出去休息一会儿，（特权！别问为什么，他们就是可以。）然而，不允许两个或两个以上的选手一起出去，因此他们必须一个接一个地出去，也就是说，先要求的先出去。如果有两个或者更多的选手在同一时间提交出去的请求，我们认定由名字字典序较小的人先出去。<br/>
这是一个烦人的工作，对吧？黑叔想让你们分担他的烦恼。<br/>
给定请求记录，格式如下：<br/>
T1 C1 D1<br/>
T2 C2 D2<br/>
...<br/>
Tn Cn Dn<br/>
每一行描述了一个请求，其中Ti表示提交请求的时间，Ci表示提交请求选手的名字，Di表示他出去到回来所需要的时间。注意：给你的这些请求是无序的。<br/>
你需要报告所有的事件，格式形如：“xxx went out at time yyy”(不包括双引号)，其中xxx表示选手的名字，yyy表示他被允许离开的时间，你必须按照事件的发生时间升序排列并输出这些事件，你可以通过下面的样例了解到更多的输出细节。<br/>
<br/>
<strong>输入格式：</strong><br/>
第一行有一个正整数N(N&lt;=10000)，表示请求的个数；<br/>
接下来有N行，每行有一个正整数T，一个字符串C以及一个正整数D，代表一个请求，T&lt;=10000000;D&lt;=1000;字符串C中有不超过20个小写字母。<br/>
保证输入数据中没有人重名。<br/>
<br/>
<strong>输出格式：</strong><br/>
按照上面描述的顺序输出所有的事件，一个事件占一行。<br/>
<br/>
<strong>样例：</strong><br/>
hey.in<br/>
2<br/>
10 lq 5<br/>
5 wing 6
</p>
<p>
hey.out<br/>
wing went out at time 5<br/>
lq went out at time 11
</p>
<br/>