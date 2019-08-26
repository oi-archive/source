
# Description

<div class="content"><p><span style="font-size: medium">从前有n只跳蚤排成一行做早操，每只跳蚤都有自己的一个弹跳力a[i]。跳蚤国王看着这些跳蚤国欣欣向荣的情景，感到非常高兴。这时跳蚤国王决定理性愉悦一下，查询区间k小值。他每次向它的随从伏特提出这样的问题: 从左往右第x个到第y个跳蚤中，a[i]第k小的值是多少。<br/>
这可难不倒伏特，他在脑袋里使用函数式线段树前缀和的方法水掉了跳蚤国王的询问。<br/>
这时伏特发现有些跳蚤跳久了弹跳力会有变化，有的会增大，有的会减少。<br/>
这可难不倒伏特，他在脑袋里使用树状数组套线段树的方法水掉了跳蚤国王的询问。（orz 主席树）<br/>
这时伏特发现有些迟到的跳蚤会插入到这一行的某个位置上，他感到非常生气，因为……他不会做了。<br/>
请你帮一帮伏特吧。<br/>
快捷版题意：带插入、修改的区间k小值在线查询。</span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行一个正整数n，表示原来有n只跳蚤排成一行做早操。<br/>
第二行有n个用空格隔开的非负整数，从左至右代表每只跳蚤的弹跳力。<br/>
第三行一个正整数q，表示下面有多少个操作。<br/>
下面一共q行，一共三种操作对原序列的操作：（假设此时一共m只跳蚤）<br/>
1. Q x y k: 询问从左至右第x只跳蚤到从左至右第y只跳蚤中，弹跳力第k小的跳蚤的弹跳力是多少。<br/>
    (1 &lt;= x &lt;= y &lt;= m, 1 &lt;= k &lt;= y - x + 1)<br/>
2. M x val: 将从左至右第x只跳蚤的弹跳力改为val。<br/>
    (1 &lt;= x &lt;= m)<br/>
3. I x val: 在从左至右第x只跳蚤的前面插入一只弹跳力为val的跳蚤。即插入后从左至右第x只跳蚤是我刚插入的跳蚤。<br/>
    (1 &lt;= x &lt;= m + 1)</span></p>
<p><span style="font-size: medium">为了体现在线操作，设lastAns为上一次查询的时候程序输出的结果，如果之前没有查询过，则lastAns = 0。<br/>
则输入的时候实际是：<br/>
Q _x _y _k ------&gt; 表示 Q _x^lastAns _y^lastAns _k^lastAns<br/>
M _x _val  ------&gt; 表示 M _x^lastAns _val^lastAns<br/>
I _x _val  ------&gt; 表示 I _x^lastAns _val^lastAns<br/>
简单来说就是操作中输入的整数都要异或上一次询问的结果进行解码。</span></p>
<p><span style="font-size: medium">(祝Pascal的同学早日转C++，就不提供pascal版的描述了。)</span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium">对于每个询问输出回答，每行一个回答。</span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">10<br/>
10 5 8 28 0 19 2 31 1 22 <br/>
30<br/>
I 6 9<br/>
M 1 11<br/>
I 8 17<br/>
M 1 31<br/>
M 6 26<br/>
Q 2 7 6<br/>
I 23 30<br/>
M 31 7<br/>
I 22 27<br/>
M 26 18<br/>
Q 26 17 31<br/>
I 5 2<br/>
I 18 13<br/>
Q 3 3 3<br/>
I 27 19<br/>
Q 23 23 30<br/>
Q 5 13 5<br/>
I 3 0<br/>
M 15 27<br/>
Q 0 28 13<br/>
Q 3 29 11<br/>
M 2 8<br/>
Q 12 5 7<br/>
I 30 19<br/>
M 11 19<br/>
Q 17 8 29<br/>
M 29 4<br/>
Q 3 0 12<br/>
I 7 18<br/>
M 29 27<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">28<br/>
2<br/>
31<br/>
0<br/>
14<br/>
15<br/>
14<br/>
27<br/>
15<br/>
14<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">此题作为一个小小的研究来搞吧～做法有很多～不知道这题究竟有多少种做法。<br/><br/>
请自觉O(log^2n)，我故意卡块状链表，块链A了的请受我深情一拜……<br/><br/>
A掉的同学请在Discuss里面简要说下自己的做法吧～<br/><br/>
原序列长度 &lt;= 35000<br/><br/>
插入个数 &lt;= 35000，修改个数 &lt;= 70000，查询个数 &lt;= 70000  ,0 &lt;= 每时每刻的权值 &lt;= 70000<br/><br/>
由于是OJ上的题，所以数据无梯度。为了防止卡OJ，本题只有4组数据。</span></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=作者 vfleaking">作者 vfleaking</a></p></div>

