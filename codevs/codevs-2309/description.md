<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>最近，Elaxia和w**的关系特别好，他们很想整天在一起，但是大学的学习太紧张了，他们必须合理地安排两个人在一起的时间。Elaxia和w**每天都要奔波于宿舍和实验室之间，他们希望在节约时间的前提下，一起走的时间尽可能的长。</p>
<p>现在已知的是Elaxia和w**所在的宿舍和实验室的编号以及学校的地图：地图上有N个路口，M条路，经过每条路都需要一定的时间。</p>
<p>具体地说，就是要求无向图中，两对点间最短路的最长公共路径。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行：两个整数N和M（含义如题目描述）。</p>
<p>第二行：四个整数x1、y1、x2、y2（1 ≤ x1 ≤ N，1 ≤ y1 ≤ N，1 ≤ x2 ≤ N，1 ≤y2 ≤ N），分别表示Elaxia的宿舍和实验室及w**的宿舍和实验室的标号（两对点分别为x1,y1和x2,y2）。</p>
<p>接下来M行：每行三个整数，u、v、l（1 ≤ u ≤ N，1 ≤ v ≤ N，1 ≤ l ≤ 10000），表示u和v之间有一条路，经过这条路所需要的时间为l。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行，一个整数，表示每天两人在一起的时间（即最长公共路径的长度）。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>9 10</p>
<p>1 6 7 8</p>
<p>1 2 1</p>
<p>2 5 2</p>
<p>2 3 3</p>
<p>3 4 2</p>
<p>3 9 5</p>
<p>4 5 3</p>
<p>4 6 4</p>
<p>4 7 2</p>
<p>5 8 1</p>
<p>7 9 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据，N ≤ 100；</p>
<p>对于60%的数据，N ≤ 1000；</p>
<p>对于100%的数据，N ≤ 1500，输入数据保证没有重边和自环。</p>
</div>
</div>