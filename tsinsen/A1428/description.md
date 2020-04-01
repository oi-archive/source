<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　Polycarp 的班上有n个学生，每个学生在班上都有一个最好的朋友，需要注意的是：如果学生a的最好朋友是学生b，学生b的最好朋友不一定是a。<br/>
　　现在 Polycarp 要把学生分成多个两人组，每个组由一个学生与他最好的朋友组成。当然，一个人只能在一个组中，且有可能存在有人不能被分到组中的情况。Polycarp想要分出最多的两人组，如果有多种方案， Polycarp 希望男-女组合尽量多。</div>
# 输入格式

<div class="pdcont">　　第一行一个整数 <i>n</i> (2 ≤ <i>n</i> ≤ 10<sup>5</sup>)，表示学生数。<br/>
　　下面n行，每行两个整数  <i>f</i><sub><i>i</i></sub>, <i>s</i><sub><i>i</i></sub> (1 ≤ <i>f</i><sub><i>i</i></sub> ≤ <i>n</i>, <i>f</i><sub><i>i</i></sub> ≠ <i>i</i>, 1 ≤ <i>s</i><sub><i>i</i></sub> ≤ 2),   <i>f</i><sub><i>i</i></sub> 表示第i个学生的最好朋友， <i>s</i><sub><i>i</i></sub>  表示第i个学生性别（ <i>s</i><sub><i>i</i></sub>  =1表男生， <i>s</i><sub><i>i</i></sub>  =2表女生）。</div>
# 输出格式

<div class="pdcont">　　第一行输出两个整数  <i>t</i>, <i>e</i>, ， <i>t</i> 表示最大组数， <i>e</i> 表示组数最大情况下最多可以有多少男女组合。<br/>
　　下面t行，每行两个数  <i>a</i><sub><i>i</i></sub>, <i>b</i><sub><i>i</i></sub> (1 ≤ <i>a</i><sub><i>i</i></sub>, <i>b</i><sub><i>i</i></sub> ≤ <i>n</i>) ，表示一组中的两个学生的标号。输出顺序任意，多解情况输出任意解。</div>
# 样例输入

<div class="pddata">5<br/>
5 2<br/>
3 2<br/>
5 1<br/>
2 1<br/>
4 2</div>
# 样例输出

<div class="pddata">2 2<br/>
5 3<br/>
4 2</div>
# 数据规模和约定

<div class="pdcont">　　对于20%的数据满足， 2 ≤ <i>n</i> ≤ 20<br/>
　　对于另外20%的数据满足，2 ≤ <i>n</i> ≤ 100<sup> </sup><br/>
　　对于100%的数据满足，2 ≤ <i>n</i> ≤ 10<sup>5</sup></div>

</div>