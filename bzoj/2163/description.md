
# Description

<div class="content"><p>你去找某bm玩，到了门口才发现要打开他家的大门不是一件容易的事……<br/>
他家的大门外有n个站台，用1到n的正整数编号。你需要对每个站台访问一定次数以后大门才能开启。站台之间有m个单向的传送门，通过传送门到达另一个站台不需要花费任何代价。而如果不通过传送门，你就需要乘坐公共汽车，并花费1单位的钱。值得庆幸的是，任意两个站台之间都有公共汽车直达。<br/>
现在给你每个站台必须访问的次数Fi，对于站台i，你必须恰好访问Fi次（不能超过）。<br/>
我们用u、v、w三个参数描述一个传送门，表示从站台u到站台v有一个最多可以使用w次的传送门（不一定要使用w次）。值得注意的是，对于任意一对传送门(u1,v1)和(u2,v2)，如果有u1&lt;u2，则有v1≤v2；如果有v1&lt;v2，则有u1≤u2；且u1=u2和v1=v2不同时成立。<br/>
你可以从任意的站台开始，从任意的站台结束。出发去开始的站台需要花费1单位的钱。你需要求出打开大门最少需要花费多少单位的钱。<br/>
</p></div>

# Input

<div class="content"><p>第一行包含两个正整数n、m，意义见题目描述。第二行包含n个正整数，第i个数表示Fi。接下来有m行，每行有三个正整数u、v、w，表示从u到v有一个可以使用w次的传送门。</p></div>

# Output

<div class="content"><p>输出一行一个整数，表示打开大门最少花费的钱数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">4 3<br/>
5 5 5 5<br/>
1 2 1<br/>
3 2 1<br/>
3 4 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">17</span></div>

# Hint

<div class="content"><p></p><p>有20%的数据满足n≤10，m≤50；对于所有的w、Fi，满足1≤w,Fi≤10。有50%的数据满足n≤1000，m≤10000。100%的数据满足1≤n≤10000，1≤m≤100000；对于所有的u、v，满足1≤u,v≤n，u≠v；对于所有的w、Fi，满足1≤w,Fi≤50000。以上的每类数据中都存在50%的数据满足对于所有的w、Fi，有w=Fi=1。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

