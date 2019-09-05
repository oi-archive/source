# 题目描述


<p>
Farmer John has bought property in the Caribbean and is going to try to raise dairy cows on a big farm composed of islands. Set in his ways, he wants to surround all the islands with fence.Each island in the farm has the shape of a polygon. He fences the islands one side at a time (between a consecutive pair of vertices) and proceeds clockwise around a given island with his fencing operations. Since he wants to fence all the islands, he must at some point travel to any other islands using a boat.
</p>
<p>
He can start fencing at any vertex and, at any vertex he encounters,travel to some vertex on another island, fence all the way around it, and then IMMEDIATELY return back to the same vertex on the original island using the same path he traveled before. Each boat trip has a cost defined by a supplied matrix.
</p>
<p>
The islands are described by a set of N (3 &lt;= N &lt;= 500) pairs of vertices V1,V2 (1 &lt;= V1 &lt;= N; 1 &lt;= V2 &lt;= N) although you must figure out how to assemble them into islands. The vertices are conveniently numbered 1..N.
</p>
<p>
The cost of traveling by boat between each pair of vertices is given by a symmetric cost matrix whose elements fall in the range 0..1000.
</p>
<p>
What is the minimum cost of surrounding the islands with the fence?
</p>
<p>
  约翰在加勒比海买下地产，准备在这里的若干个岛屿上养奶牛．所以，他要给所有岛屿围上篱笆．每个岛屿都是多边形．他沿着岛屿的一条边界朝一个方向走，有时候坐船到另一个岛去．他可以从任意一个多边形顶点开始修篱笆的工作；在任意一个到达的顶点，他可以坐船去另一个岛屿的某个顶点，但修完那个岛的篱笆，他必须马上原路返回原来出发的那个岛屿顶点．任意两个顶点间都有航线，每条航线都需要一定的费用．请帮约翰计算最少的费用，让他修完所有篱笆．
</p>
<p>
 
</p>
<p>
PROBLEM NAME: surround
</p>
<p>
INPUT FORMAT:
</p>
<p>
* Line 1: A single integer: N
</p>
<p>
* Lines 2..N+1: Each line describes an island&#39;s border with two space-separated integers: V1 and V2
</p>
<p>
* Lines N+2..2*N+1: Line i-N-1 contains N integers that describe row i of the cost matrix: Row_i
</p>
<p>
<br/>
</p>
<p>
SAMPLE INPUT (file surround.in):
</p>
<p>
12
</p>
<p>
1 7
</p>
<p>
7 3
</p>
<p>
3 6
</p>
<p>
6 10
</p>
<p>
10 1
</p>
<p>
2 12
</p>
<p>
2 9
</p>
<p>
8 9
</p>
<p>
8 12
</p>
<p>
11 5
</p>
<p>
5 4
</p>
<p>
11 4
</p>
<p>
0 15 9 20 25 8 10 13 17 8 8 7
</p>
<p>
15 0 12 12 10 10 8 15 15 8 8 9
</p>
<p>
9 12 0 25 20 18 16 14 13 7 12 12
</p>
<p>
20 12 25 0 8 13 14 15 15 10 10 10
</p>
<p>
25 10 20 8 0 16 20 18 17 18 9 11
</p>
<p>
8 10 18 13 16 0 10 9 11 10 8 12
</p>
<p>
10 8 16 14 20 10 0 18 20 6 16 15
</p>
<p>
13 15 14 15 18 9 18 0 5 12 12 13
</p>
<p>
17 15 13 15 17 11 20 5 0 22 8 10
</p>
<p>
8 8 7 10 18 10 6 12 22 0 11 12
</p>
<p>
8 8 12 10 9 8 16 12 8 11 0 9
</p>
<p>
7 9 12 10 11 12 15 13 10 12 9 0
</p>
<p>
<br/>
</p>
<p>
INPUT DETAILS:
</p>
<p>
<br/>
</p>
<p>
 1        10            4
</p>
<p>
   xxxxxxx              x
</p>
<p>
  xxxxxxxxx            xxxx
</p>
<p>
7 xxxxxxxxxxx 6        xxxxxxx
</p>
<p>
xxxxxxxxxxx       11 xxxxxxxxxx 5
</p>
<p>
 xxxxxxx
</p>
<p>
  xxx
</p>
<p>
 3         12 xxxxxxx 2
</p>
<p>
             xxxxxxxx
</p>
<p>
             xxxxxxxx
</p>
<p>
            xxxxxxxxx
</p>
<p>
            xxxxxxxxx
</p>
<p>
           xxxxxxxxxx
</p>
<p>
           xxxxxxxxxx
</p>
<p>
         8 xxxxxxxxxx 9
</p>
<p>
<br/>
</p>
<p>
The example describes three islands: {1,7,3,6,10}, {4,5,11} and {2,9,8,12}. The travel costs are provided as a matrix. For example,the travel cost from vertex 1 to 2 is 15.
</p>
<p>
<br/>
</p>
<p>
OUTPUT FORMAT:
</p>
<p>
* Line 1: A single integer that specifies the minimum cost of building
</p>
<p>
       the fence
</p>
<p>
<br/>
</p>
<p>
SAMPLE OUTPUT (file surround.out):
</p>
<p>
30
</p>
<p>
<br/>
</p>
<p>
OUTPUT DETAILS:
</p>
<p>
There is more than one solution. One is: FJ starts from vertex 3 then 7 and stops at 1, travels to 11 followed by 4,5,11. He then returns back to 1, and travels to 12 followed by 2,9,8,12. Finally,he returns back to 1 and continues with 10,6,3,7. The costs are 8 * 2 = 16 for traveling from 1 to 11 and returning back, and 7 * 2 = 14 for traveling from 1 to 12 and back -- a total cost of 30.
</p>
