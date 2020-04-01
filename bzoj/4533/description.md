
# Description

<div class="content"><div>为了写论文，Alex经常要整理大量的数据。<span style="white-space:pre" class="Apple-tab-span">	</span>这一次，Alex面临一个严峻的考验：他需要实现一个数据结构来维护一个点集。 </div>
<div>现在，二维平面上有N个点。Alex 需要实现以下三种操作： </div>
<div>1.<span style="white-space:pre" class="Apple-tab-span">	</span>在点集里添加一个点； </div>
<div>2.<span style="white-space:pre" class="Apple-tab-span">	</span>给出一个点，查询它到点集里所有点的曼哈顿距离的最小值； </div>
<div>3.<span style="white-space:pre" class="Apple-tab-span">	</span>给出一个点，查询它到点集里所有点的曼哈顿距离的最大值。 </div>
<div>两个点的曼哈顿距离定义为它们的横坐标差的绝对值与纵坐标差的绝对值的和。这么困难的问题，Alex当然不会做，只好再次请你帮忙了。 </div>
<p></p></div>

# Input

<div class="content"><div>第一行包含一个整数N，表示点集最初的点数。 </div>
<div>接下来N行，每行两个整数，依次表示每个点的横坐标和纵坐标。 </div>
<div>第N+2行包含一个整数Q，表示询问的数目。 </div>
<div>接下来Q行，每行三个整数，依次表示询问的类型，点的横坐标和纵坐标。0类型表示添加一个点，1类型表示查询到该点的曼哈顿距离的最小值，2类型表示查询最大值。 </div>
<div>1 ≤ N, Q ≤ 100,000，点的坐标是不超过10^9的非负整数</div>
<p></p></div>

# Output

<div class="content"><div>输出若干行，依次表示每个查询操作的答案。 </div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 <br/>
7 5 <br/>
6 2 <br/>
3 1 <br/>
5 <br/>
1 6 1 <br/>
1 5 5 <br/>
2 7 1 <br/>
0 3 2 <br/>
1 1 0 </span></div>

# Sample Output

<div class="content"><span class="sampledata">1 <br/>
2 <br/>
4 <br/>
3 </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

