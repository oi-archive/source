
# Description

<div class="content"><div>二维平面上有一个可以活动的箱子位于 (0,0)  ，现在可以对它施加三种操作：</div>
<div>向右方推， 横坐标增加 1</div>
<div>向上方推 ，纵坐标增加 1</div>
<div>向右上方推，横纵坐标均增加 1</div>
<div>而平面上还有 k 个不可活动的箱子位于第一象限的一些整点上，</div>
<div>活动的箱子不能推到这些整点上。可能存在一些不可活动的箱子位于同一个点，可以认为它们垒在了一起。现在希</div>
<div>望将活动的箱子推到直线 x=n 或直线 y=m 上并立即停止活动，问有多少种推法，答案对 p 取模。两种推法视为</div>
<div>相同的，当且仅当它们的操作次数相等且每一次的操作相等。</div>
<p></p></div>

# Input

<div class="content"><div>第一行有一个正整数 t ，表示数据组数。</div>
<div>对于每组测试数据：</div>
<div>第一行有四个非负整数 n,m,k,p ，相邻数字间有一个空格。</div>
<div>接下来 k 行，每行有两个正整数 a,b ，表示一个不可活动的箱子位于 (a,b)  ，相邻数字间有一个空格。</div>
<div>保证 1≤a≤n,1≤b≤m 。 t≤2000,tot≤10^5,1≤N≤10^4,1≤M≤10^9,0≤k≤10,1≤p&lt;2^31</div>
<p></p></div>

# Output

<div class="content"><div>共 t 行，每行对应一组测试数据，为一个非负整数表示答案对 p 取模后的值。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
1 1 0 100<br/>
1 1 1 100<br/>
1 1<br/>
3 3 2 100<br/>
1 1<br/>
2 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
2<br/>
12<br/>
【样例解释】<br/>
对于第二组测试数据，满足条件的推法只有两种，分别是一次向右推，和一次向上推。<br/>
对于第三组测试数据，满足条件的推法都无法推到 (n,m)  <br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By Tangjz">By Tangjz</a></p></div>

