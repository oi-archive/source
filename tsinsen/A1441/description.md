# 题面



<div class="pdcont"><b>【问题描述】</b><br/>
　　小Gerald和教练Mike在玩一个有趣的游戏。游戏是这样的，一开始有n个糖果和m个石头，Gerald和Mike轮流行动，Mike先行动。Gerald每次会吃掉一个糖果或者一个石头。Mike每次根据Gerald吃掉的糖果和石头数目给分，假设Gerald吃掉了a个糖果b个石头，那么得分就是f(a,b)，f函数会在下面的输入格式部分定义。Gerald不允许把糖果或者石头全部吃完。请告诉Gerald他最多能得到的分数是多少，同时告诉他该怎么吃才能达到这个分数。<br/>
<br/>
<b>【输入格式】</b><br/>
　　输入第一行包括三个整数n, m, p。n, m的含义如题目所述。第二行包含n个整数x<sub>0</sub>, x<sub>1</sub>…x<sub>n-1</sub>，第三行包括m个整数y<sub>0</sub>, y<sub>1</sub>…y<sub>m-1</sub>。f函数就定义为f(a,b)=(x<sub>a</sub>+y<sub>b</sub>)mod p.<br/>
<br/>
<b>【输出格式】</b><br/>
　　输出第一行包含一个整数，代表Gerald最多能获得的分数。第二行是一个包含n+m-2个’S’或’C’的字符串，其中第i个字符是’S’表示第i次吃的是石头，是’C’表示第i次吃的是糖果。<br/>
<br/>
<b>【样例输入1</b><b>】</b><br/>
　　2 2 10<br/>
　　0 0<br/>
　　0 1<br/>
<br/>
<b>【样例输出1</b><b>】</b><br/>
　　2<br/>
　　SC<br/>
<br/>
<b>【样例输入2</b><b>】</b><br/>
　　3 3 10<br/>
　　0 2 0<br/>
　　0 0 2<br/>
<br/>
<b>【样例输出2</b><b>】</b><br/>
　　10<br/>
　　CSSC<br/>
<br/>
<b>【样例输入3</b><b>】</b><br/>
　　3 3 2<br/>
　　0 1 1<br/>
　　1 1 0<br/>
<br/>
<b>【样例输出3</b><b>】</b><br/>
　　4<br/>
　　SCSC<br/>
<br/>
<b>【数据规模和约定】</b><br/>
　　对于10%的数据n,m&lt;=2.<br/>
　　对于30%的数据n,m&lt;=10.<br/>
　　对于60%的数据n,m&lt;=2000.<br/>
　　对于100%的数据n,m&lt;=20000, p&lt;=10<sup>9</sup>, 0&lt;=x<sub>i</sub>,y<sub>i</sub>&lt;=20000.</div>



