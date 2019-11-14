
# Description

<div class="content"><div>天才大学生quailty热衷于解决NP-Hard问题，你如果AC 了这道题，就可以成为他真正的粉丝。图染色问题：给定</div>
<div>无向图G和一个正整数k。对于图中的每个点，选择一个在[1,k]之间的整数作为其颜色。你需要保证对于每条边，</div>
<div>其两端点的颜色均不相同。简单k路径问题：给定无向图G和一个正整数k。请找到一条经过了恰好k条边的简单路径</div>
<div>。即，你需要找到一个长度为k+1的序列v_1,v_2,...,v_{k+1}，满足1&lt;=v_i&lt;=n，且任意两个v均不相同，同时v_i</div>
<div>与v_{i+1}之间存在一条边。现在给定无向图G和一个正整数k，quailty知道你没有他的水平，所以你只需解决上面</div>
<div>的任意一个问题就可以成为他的粉丝。</div></div>

# Input

<div class="content"><div>第一行包含一个正整数T(1&lt;=T&lt;=1000)，表示测试数据的组数。</div>
<div>对于每组数据，第一行包含三个正整数n,m,k(1&lt;=n&lt;=1000,1&lt;=m&lt;=10000,1&lt;=k&lt;=n)，分别表示图的点数与边数。</div>
<div>接下来m行，每行两个正整数a,b(1&lt;=a,b&lt;=n)，表示a到b之间存在一条无向边。</div>
<div>输入数据保证不存在重边与自环，且总边数不超过100000。</div></div>

# Output

<div class="content"><div>对于每组数据：</div>
<div>若选择了图染色问题，请输出“color”，然后输出n个在1到k之间的正整数，分别表示每个点的颜色。</div>
<div>若选择了简单路径问题，请输出“path”，然后输出k+1个在1到n之间的正整数，分别表示路径上每个点的编号。</div>
<div>若有多组可行解，输出任意一组。</div></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
4 5 2<br/>
1 2<br/>
2 3<br/>
3 4<br/>
4 1<br/>
1 3<br/>
3 3 3<br/>
1 2<br/>
2 3<br/>
3 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">path 3 2 1<br/>
color 1 2 3<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=本OJ付费获得">本OJ付费获得</a></p></div>

