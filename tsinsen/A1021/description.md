<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　给出两个整数集合A、B，求出他们的交集、并集以及B在A中的余集。</div>
# 输入格式

<div class="pdcont">　　第一行为一个整数n，表示集合A中的元素个数。<br/>
　　第二行有n个互不相同的用空格隔开的整数，表示集合A中的元素。<br/>
　　第三行为一个整数m，表示集合B中的元素个数。<br/>
　　第四行有m个互不相同的用空格隔开的整数，表示集合B中的元素。<br/>
　　集合中的所有元素均为int范围内的整数，n、m&lt;=1000。</div>
# 输出格式

<div class="pdcont">　　第一行按从小到大的顺序输出A、B交集中的所有元素。<br/>
　　第二行按从小到大的顺序输出A、B并集中的所有元素。<br/>
　　第三行按从小到大的顺序输出B在A中的余集中的所有元素。</div>
# 样例输入

<div class="pddata">5<br/>
1 2 3 4 5<br/>
5<br/>
2 4 6 8 10</div>
# 样例输出

<div class="pddata">2 4<br/>
1 2 3 4 5 6 8 10<br/>
1 3 5</div>
# 样例输入

<div class="pddata">4<br/>
1 2 3 4<br/>
3<br/>
5 6 7</div>
# 样例输出

<div class="pddata">1 2 3 4 5 6 7<br/>
1 2 3 4</div>

</div>