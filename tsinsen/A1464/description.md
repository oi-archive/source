<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　有一个长度为n的排列A,你想通过一些询问知道它是什么样的.<br/>
　　每次你构造一个长度为k(0&lt;k&lt;=m)的序列B,满足1&lt;=Bi&lt;=n且B中没有相同的元素,<br/>
　　系统会根据序列B生成一个长度为k的序列C , Ci的值为j(Aj==Bi).<br/>
　　然后系统随机洗牌C序列后返回给你,问至少要多少次询问才能知道A究竟是什么.</div>
# 输入格式

<div class="pdcont">　　本题每个测试点有多组数据.<br/>
　　输入第一行仅一个数t,表示数据组数.<br/>
　　接下来t行每一行包含两个正整数n,m,意义见问题描述.</div>
# 输出格式

<div class="pdcont">　　对于每组数据,输出至少需要几次询问.</div>
# 样例输入

<div class="pddata">5<br/>
4 1<br/>
4 2<br/>
7 3<br/>
1 1<br/>
42 7</div>
# 样例输出

<div class="pddata">3<br/>
2<br/>
3<br/>
0<br/>
11</div>
# 福利数据一

<div class="pdcont">　　1<br/>
　　5 3</div>
# 福利数据二

<div class="pdcont">　　1<br/>
　　8 4</div>
# 数据规模和约定

<div class="pdcont">　　对于10%的数据,乃福利数据.<br/>
　　另有10%的数据,n&lt;=10.<br/>
　　另有20%的数据,n&lt;=50.<br/>
　　另有10%的数据,n==m&lt;=10^9.<br/>
　　剩余50%的数据,n,m&lt;=10^9.<br/>
　　对于所有数据满足t&lt;=1000,m&lt;=n.</div>

</div>