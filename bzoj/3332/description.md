
# Description

<div class="content"><p><span style="font-size: medium">圣诞节将至。一年一度的难题又摆在wyx面前——如何给妹纸送礼物。<br/>
wyx的后宫有n人，这n人之间有着复杂的关系网，相互认识的人有m对。wyx想要量化后宫之间的亲密度，于是准备给每对认识关系估一个亲密度。亲密度是个正整数，值越大说明越亲密。当然有可能有些后宫之间不直接认识，为此wyx定义了一个值f(i,j)，代表从第i个后宫开始不断经过认识的人到j，经过的亲密度最小的一对关系的最大值。不过也有可能有些后宫的朋友圈互相独立，怎么也没法通过认识的人互相到达，那么f(i,j)就为-1。<br/>
举个例子，wyx的后宫有4人，编号为1~4。后宫1和2之间的亲密度为3，后宫2和3之间的亲密度为4，后宫1和3之间的亲密度为2，后宫4由于不明原因被孤立了。那么f(1,2)=f(1,3)=3，f(2,3)=4，f(1,4)=f(2,4)=f(3,4)=-1。<br/>
wyx认为了解后宫之间的亲密程度对于他选择礼物有着很重大的意义，于是他找了几个路人，测出了所有后宫之间的f(i,j)值。不过wyx怀疑路人在坑爹，他想知道，是否能找到一组后宫之间的亲密度方案满足路人测出的f(i,j)值？由于他还要去把妹，这个问题就交给你了。</span></p>
<p><span style="font-size: medium"><br/>
</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行一个正整数T，代表数据组数。</span></p>
<p><span style="font-size: medium">接下来T组数据，每组数据第一行两个正整数n、m，代表点数和边数。</span></p>
<p><span style="font-size: medium">接下来m行，每行两个正整数代表一条边。<br/>
接下来n行每行n个整数，代表所有的f(i,j)值。</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">对于每组数据，输出 &#34;Yes&#34; 或者 &#34;No&#34;。（详细参看样例输出）</span></p></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
<br/>
<br/>
3<br/>
4 5<br/>
1 2<br/>
1 3<br/>
1 4<br/>
2 3<br/>
2 4<br/>
0 5 5 5<br/>
5 0 5 5<br/>
5 5 0 4<br/>
5 5 4 0<br/>
4 4<br/>
1 2<br/>
1 3<br/>
2 3<br/>
2 4<br/>
0 4 4 4<br/>
4 0 4 5<br/>
4 4 0 4<br/>
4 5 4 0<br/>
4 2<br/>
1 2<br/>
2 3<br/>
0 3 3 -1<br/>
3 0 4 -1<br/>
3 4 0 -1<br/>
-1 -1 -1 0<br/>
<br/>
 <br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
Case #1: No<br/>
<br/>
Case #2: Yes<br/>
<br/>
Case #3: Yes<br/>
<br/>
 </span></div>

# Hint

<div class="content"><p></p><p></p><br/>
<p>数据范围</p><br/>
<p>T ≤ 30</p><br/>
<p>n ≤ 1000</p><br/>
<p>m ≤ 300000</p><br/>
<p>f(i,j)=-1 或者 1 ≤ f(i,j) ≤ 32767</p><br/>
<p>注意输入量奇大无比！<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=kanari提供题面和标程，zhonghaoxi提供数据
">kanari提供题面和标程，zhonghaoxi提供数据<br/>
</a></p></div>

