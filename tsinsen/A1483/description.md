<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　有一个N*N的方格表，每个格子里有一个数，第i行第j列的数等于A<sub>i</sub>*B<sub>j</sub>。小B从左上角走到右下角，每次只能向右或向下走一步，他会把经过的数累加起来，并使这个总和最小。他决定走T次，第i次从第P<sub>i</sub>行第Q<sub>i</sub>列的点走到第R<sub>i</sub>行第S<sub>i</sub>列的点，问每一次经过的数的最小总和。</div>
# 输入格式

<div class="pdcont">　　第一行包括两个整数N, T，分别表示方格表的大小和询问数量。<br/>
　　第二行N个整数，表示A<sub>1</sub>,A<sub>2</sub>, … ,A<sub>N</sub>。<b>在全部20个测试数据中，这一行的数是随机生成的。</b><br/>
　　第三行N个整数，表示B<sub>1</sub>,B<sub>2</sub>, … ,B<sub>N</sub>。<b>在全部20个测试数据中，这一行的数是随机生成的。</b><br/>
　　接下来T行，每行四个整数P<sub>i</sub>，Q<sub>i</sub>，R<sub>i</sub>，S<sub>i</sub> (P<sub>i</sub>≤R<sub>i</sub>，Q<sub>i</sub>≤S<sub>i</sub>)，含义如题所述。</div>
# 输出格式

<div class="pdcont">　　输出T行，每行一个整数，表示答案。</div>
# 样例输入

<div class="pddata">3 4<br/>
1 2 3<br/>
2 3 4<br/>
1 1 1 1<br/>
1 3 1 3<br/>
1 1 3 3<br/>
1 1 3 1</div>
# 样例输出

<div class="pddata">2<br/>
4<br/>
29<br/>
12</div>
# 数据规模和约定

<div class="pdcont">　　对于20%的数据，N≤100，T≤100。<br/>
　　对于50%的数据，N≤3000，T≤1000。<br/>
　　对于70%的数据，N≤50000，T≤20000。<br/>
　　对于100%的数据，N≤200000，T≤50000，1≤A<sub>i</sub>, B<sub>i</sub>≤10<sup>6</sup>。保证询问合法，除样例外，所有的Ai, Bi均为随机生成的。</div>

</div>