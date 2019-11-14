
# Description

<div class="content"><p><span style="font-size: medium">贝茜把家搬到了一个小农场，但她常常回到FJ的农场去拜访她的朋友。贝茜很喜欢路边的风景，不想那么快地结束她的旅途，于是她每次回农场，都会选择第二短的路径，而不象我们所习惯的那样，选择最短路。 贝茜所在的乡村有R(1&lt;=R&lt;=100,000)条双向道路，每条路都联结了所有的N(1&lt;=N&lt;=5000)个农场中的某两个。贝茜居住在农场1，她的朋友们居住在农场N（即贝茜每次旅行的目的地）。 贝茜选择的第二短的路径中，可以包含任何一条在最短路中出现的道路，并且，一条路可以重复走多次。当然咯，第二短路的长度必须严格大于最短路（可能有多条）的长度，但它的长度必须不大于所有除最短路外的路径的长度。 </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* 第1行: 两个整数，N和R，用空格隔开 </span></p>
<p><span style="font-size: medium">* 第2..R+1行: 每行包含三个用空格隔开的整数A、B和D，表示存在一条长度为 D(1 &lt;= D &lt;= 5000)的路连接农场A和农场B</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* 第1行: 输出一个整数，即从农场1到农场N的第二短路的长度 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 4<br/>
1 2 100<br/>
2 4 200<br/>
2 3 250<br/>
3 4 100<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">450<br/>
<br/>
输出说明:<br/>
<br/>
    最短路：1 -&gt; 2 -&gt; 4 (长度为100+200=300)<br/>
    第二短路：1 -&gt; 2 -&gt; 3 -&gt; 4 (长度为100+250+100=450)</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

