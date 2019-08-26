
# Description

<div class="content"><p>一天，小m在平面上画了N个黑点和N个白点，按以下方式来连边，构成一个有向完全图。 1. i和j同色，随机选择i→j或j→i。 2. i和j异色，若D(i, j)&gt;D，则白点→黑点，否则黑点→白点。 这里的D(i, j)指的是曼哈顿距离(|xi-xj|+|yi-yj|)，D为给定值。 然后，小m发现有很多三角形很漂亮，漂亮三角形的定义如下： 1. 三个顶点i、j和k颜色不完全相同 2. 它们之间的连的边是i→j、j→k、k→i。 请你求出漂亮三角形至少有多少个，至多有多少个。</p></div>

# Input

<div class="content"><p>第一行两个正整数N和D，接下来N行Xi Yi描述第i个白点的坐标，再接下来N行Xj Yj描述第j个黑点的坐标。其中0 ≤ D, |X|, |Y| ≤ 10^8。</p></div>

# Output

<div class="content"><p>两个数依次为漂亮三角形最少时的个数，最多时的个数，中间用一个空格隔开。</p></div>

# Sample Input

<div class="content"><span class="sampledata">2 1<br/>
1 2<br/>
1 1<br/>
3 1<br/>
2 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0 2</span></div>

# Hint

<div class="content"><p></p><p>对于10%的数据满足：N ≤ 5 对于40%的数据满足：N ≤ 1,000 对于100%的数据满足：N ≤ 100,000</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By Mt">By Mt</a></p></div>

