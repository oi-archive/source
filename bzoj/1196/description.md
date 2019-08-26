
# Description

<div class="content"><div>OI island是一个非常漂亮的岛屿,自开发以来,到这儿来旅游的人很多。然而，由于该岛屿刚刚开发不久，所以那</div>
<div>里的交通情况还是很糟糕。所以，OIER Association组织成立了，旨在建立OI island的交通系统。 OI island有n</div>
<div>个旅游景点，不妨将它们从1到n标号。现在，OIER Association需要修公路将这些景点连接起来。一条公路连接两</div>
<div>个景点。公路有，不妨称它们为一级公路和二级公路。一级公路上的车速快，但是修路的花费要大一些。 OIER As</div>
<div>sociation打算修n-1条公路将这些景点连接起来（使得任意两个景点之间都会有一条路径）。为了保证公路系统的</div>
<div>效率, OIER Association希望在这n-1条公路之中,至少有k条(0≤k≤n-1)一级公路。OIER Association也不希望为</div>
<div>一条公路花费的钱。所以，他们希望在满足上述条件的情况下，花费最多的一条公路的花费尽可能的少。而你的任</div>
<div>务就是，在给定一些可能修建的公路的情况下，选择n-1条公路，满足上面的条件。</div></div>

# Input

<div class="content"><div>第一行有三个数n(1≤n≤10000),k(0≤k≤n-1),m(n-1≤m≤20000)，这些数之间用空格分开。</div>
<div>N和k如前所述，m表示有m对景点之间可以修公路。</div>
<div>以下的m-1行，每一行有4个正整数a,b,c1,c2</div>
<div>（1≤a,b≤n,a≠b,1≤c2≤c1≤30000）</div>
<div>表示在景点a与b之间可以修公路,如果修一级公路,则需要c1的花费,如果修二级公路,则需要c2的花费。</div></div>

# Output

<div class="content"><p>一个数据，表示花费最大的公路的花费。</p></div>

# Sample Input

<div class="content"><span class="sampledata">10 4 20<br/>
3 9 6 3<br/>
1 3 4 1<br/>
5 3 10 2<br/>
8 9 8 7<br/>
6 8 8 3<br/>
7 1 3 2<br/>
4 9 9 5<br/>
10 8 9 1<br/>
2 6 9 1<br/>
6 7 9 8<br/>
2 6 2 1<br/>
3 8 9 5<br/>
3 2 9 6<br/>
1 6 10 3<br/>
5 6 3 1<br/>
2 7 6 1<br/>
7 8 6 2<br/>
10 9 2 1<br/>
7 1 10 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">5</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

