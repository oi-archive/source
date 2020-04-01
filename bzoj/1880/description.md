
# Description

<div class="content">最近，Elaxia和w**的关系特别好，他们很想整天在一起，但是大学的学习太紧张了，他们
必须合理地安排两个人在一起的时间。Elaxia和w**每天都要奔波于宿舍和实验室之间，他们
希望在节约时间的前提下，一起走的时间尽可能的长。
现在已知的是Elaxia和w**所在的宿舍和实验室的编号以及学校的地图：地图上有N个路
口，M条路，经过每条路都需要一定的时间。
具体地说，就是要求无向图中，两对点间最短路的最长公共路径。</div>

# Input

<div class="content">第一行：两个整数N和M（含义如题目描述）。
第二行：四个整数x1、y1、x2、y2（1 ≤ x1 ≤ N，1 ≤ y1 ≤ N，1 ≤ x2 ≤ N，1 ≤
≤ N），分别表示Elaxia的宿舍和实验室及w**的宿舍和实验室的标号（两对点分别
x1,y1和x2,y2）。
接下来M行：每行三个整数，u、v、l（1 ≤ u ≤ N，1 ≤ v ≤ N，1 ≤ l ≤ 10000），表
u和v之间有一条路，经过这条路所需要的时间为l。
出出出格格格式式式：：：
一行，一个整数，表示每天两人在一起的时间（即最长公共路径的长度）。</div>

# Output

<div class="content">一行，一个整数，表示每天两人在一起的时间（即最长公共路径的长度）</div>

# Sample Input

<div class="content"><span class="sampledata">9 10<br/>
1 6 7 8<br/>
1 2 1<br/>
2 5 2<br/>
2 3 3<br/>
3 4 2<br/>
3 9 5<br/>
4 5 3<br/>
4 6 4<br/>
4 7 2<br/>
5 8 1<br/>
7 9 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3</span></div>

# Hint

<div class="content"><p>对于30%的数据，N ≤ 100；<br/>
对于60%的数据，N ≤ 1000；<br/>
对于100%的数据，N ≤ 1500，输入数据保证没有重边和自环。</p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Day2">Day2</a></p></div>

