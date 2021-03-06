<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　小A和小B决定利用假期外出旅行，他们将想去的城市从1到N编号，<b>且编号较小的城市在编号较大的城市的西边</b>，已知各个城市的海拔高度互不相同，记城市i的海拔高度为H<sub>i</sub>，城市i和城市j之间的距离d[i,j]恰好是这两个城市海拔高度之差的绝对值，即                                                  。<br/>
　　旅行过程中，小A和小B轮流开车，第一天小A开车，之后每天轮换一次。他们计划选择一个城市S作为起点，<b>一直向东行驶</b>，并且最多行驶X公里就结束旅行。小A和小B的驾驶风格不同，小B总是<b>沿着前进方向选择</b>一个最近的城市作为目的地，而小A总是<b>沿着前进方向选择</b>第二近的城市作为目的地（注意：<b>本题中如果当前城市到两个城市的距离相同，则认为离海拔低的那个城市更近</b>）。如果其中任何一人无法按照自己的原则选择目的城市，或者到达目的地会使行驶的总距离超出X公里，他们就会结束旅行。<br/>
　　在启程之前，小A想知道两个问题：<br/>
　　1．对于一个给定的X=X<sub>0</sub>，从哪一个城市出发，小A开车行驶的路程总数与小B行驶的路程总数的比值最小（如果小B的行驶路程为0，此时的比值可视为无穷大，且两个无穷大视为相等）。如果从多个城市出发，小A开车行驶的路程总数与小B行驶的路程总数的比值都最小，则输出海拔最高的那个城市。<br/>
　　2. 对任意给定的X=X<sub>i</sub>和出发城市S<sub>i</sub>，小A开车行驶的路程总数以及小B行驶的路程总数。</div>
# 输入格式

<div class="pdcont">　　第一行包含一个整数N，表示城市的数目。<br/>
　　第二行有N个整数，每两个整数之间用一个空格隔开，依次表示城市1到城市N的海拔高度，即H<sub>1</sub>，H<sub>2</sub>，……，H<sub>n</sub>，且每个H<sub>i</sub>都是不同的。<br/>
　　第三行包含一个整数X<sub>0</sub>。<br/>
　　第四行为一个整数M，表示给定M组S<sub>i</sub>和X<sub>i</sub>。<br/>
　　接下来的M行，每行包含2个整数S<sub>i</sub>和X<sub>i</sub>，表示从城市S<sub>i</sub>出发，最多行驶X<sub>i</sub>公里。</div>
# 输出格式

<div class="pdcont">　　输出共M+1行。<br/>
　　第一行包含一个整数S<sub>0</sub>，表示对于给定的X<sub>0</sub>，从编号为S<sub>0</sub>的城市出发，小A开车行驶的路程总数与小B行驶的路程总数的比值最小。<br/>
　　接下来的M行，每行包含2个整数，之间用一个空格隔开，依次表示在给定的S<sub>i</sub>和X<sub>i</sub>下小A行驶的里程总数和小B行驶的里程总数。</div>
# 样例输入

<div class="pddata">4<br/>
2 3 1 4<br/>
3<br/>
4<br/>
1 3<br/>
2 3<br/>
3 3<br/>
4 3</div>
# 样例输出

<div class="pddata">1<br/>
1 1<br/>
2 0<br/>
0 0<br/>
0 0</div>
# 输入输出样例1说明

<div class="pdcont"><img src="data:image/png;base64,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"/><br/>
<br/>
<br/>
<br/>
　　各个城市的海拔高度以及两个城市间的距离如上图所示。<br/>
　　如果从城市1出发，可以到达的城市为2,3,4，这几个城市与城市1的距离分别为1,1,2，但是由于城市3的海拔高度低于城市2，所以我们认为城市3离城市1最近，城市2离城市1第二近，所以小A会走到城市2。到达城市2后，前面可以到达的城市为3,4，这两个城市与城市2的距离分别为2,1，所以城市4离城市2最近，因此小B会走到城市4。到达城市4后，前面已没有可到达的城市，所以旅行结束。<br/>
　　如果从城市2出发，可以到达的城市为3,4，这两个城市与城市2的距离分别为2,1，由于城市3离城市2第二近，所以小A会走到城市3。到达城市3后，前面尚未旅行的城市为4，所以城市4离城市3最近，但是如果要到达城市4，则总路程为2+3=5&gt;3，所以小B会直接在城市3结束旅行。<br/>
　　如果从城市3出发，可以到达的城市为4，由于没有离城市3第二近的城市，因此旅行还未开始就结束了。<br/>
　　如果从城市4出发，没有可以到达的城市，因此旅行还未开始就结束了。</div>
# 样例输入

<div class="pddata">10<br/>
4 5 6 1 2 3 7 8 9 10<br/>
7<br/>
10<br/>
1 7<br/>
2 7<br/>
3 7<br/>
4 7<br/>
5 7<br/>
6 7<br/>
7 7<br/>
8 7<br/>
9 7<br/>
10 7</div>
# 样例输出

<div class="pddata">2<br/>
3 2<br/>
2 4<br/>
2 1<br/>
2 4<br/>
5 1<br/>
5 1<br/>
2 1<br/>
2 0<br/>
0 0<br/>
0 0</div>
# 输入输出样例2说明

<div class="pdcont">　　当X=7时，<br/>
　　如果从城市1出发，则路线为1 -&gt; 2 -&gt; 3 -&gt; 8 -&gt; 9，小A走的距离为1+2=3，小B走的距离为1+1=2。（在城市1时，距离小A最近的城市是2和6，但是城市2的海拔更高，视为与城市1第二近的城市，所以小A最终选择城市2；走到9后，小A只有城市10可以走，没有第2选择可以选，所以没法做出选择，结束旅行）<br/>
　　如果从城市2出发，则路线为2 -&gt; 6 -&gt; 7 ，小A和小B走的距离分别为2，4。<br/>
　　如果从城市3出发，则路线为3 -&gt; 8 -&gt; 9，小A和小B走的距离分别为2，1。<br/>
　　如果从城市4出发，则路线为4 -&gt; 6 -&gt; 7，小A和小B走的距离分别为2，4。<br/>
　　如果从城市5出发，则路线为5 -&gt; 7 -&gt; 8 ，小A和小B走的距离分别为5，1。<br/>
　　如果从城市6出发，则路线为6 -&gt; 8 -&gt; 9，小A和小B走的距离分别为5，1。<br/>
　　如果从城市7出发，则路线为7 -&gt; 9 -&gt; 10，小A和小B走的距离分别为2，1。<br/>
　　如果从城市8出发，则路线为8 -&gt; 10，小A和小B走的距离分别为2，0。<br/>
　　如果从城市9出发，则路线为9，小A和小B走的距离分别为0，0（旅行一开始就结束了）。<br/>
　　如果从城市10出发，则路线为10，小A和小B走的距离分别为0，0。<br/>
　　从城市2或者城市4出发小A行驶的路程总数与小B行驶的路程总数的比值都最小，但是城市2的海拔更高，所以输出第一行为2。</div>
# 数据规模和约定

<div class="pdcont">　　对于30%的数据，有1≤N≤20，1≤M≤20；<br/>
　　对于40%的数据，有1≤N≤100，1≤M≤100；<br/>
　　对于50%的数据，有1≤N≤100，1≤M≤1,000；<br/>
　　对于70%的数据，有1≤N≤1,000，1≤M≤10,000；<br/>
　　对于100%的数据，有1≤N≤100,000，1≤M≤10,000，-1,000,000,000≤H<sub>i</sub>≤1,000,000,000，0≤X<sub>0</sub>≤1,000,000,000，1≤S<sub>i</sub>≤N，0≤X<sub>i</sub>≤1,000,000,000，数据保证H<sub>i</sub>互不相同。</div>

</div>