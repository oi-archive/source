<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　给出N个单位时间任务，其中第i个任务可以选择在Si到Ti间的某一个时刻完成，且完成后能获得Vi的收益。注意一个时刻最多只能完成一个任务，而一个任务如果要做也只需要一个时刻。求能够得到的最大收益。</div>
# 输入格式

<div class="pdcont">　　输入文件的第一行包含一个整数N，表示可供选择的任务个数。接下来的第2至第N+1行每行包括三个数，其中第i+1行依次为Si，Ti和Vi。</div>
# 输出格式

<div class="pdcont">　　输出仅包含一个数，为所能获得的最大收益。</div>
# 样例输入

<div class="pddata">2<br/>
1 1 1<br/>
1 1 2</div>
# 样例输出

<div class="pddata">2</div>
# 样例一的注释

<div class="pdcont">　　选择第二个任务可以得到价值2。</div>
# 样例输入

<div class="pddata">3<br/>
1 1 5<br/>
2 2 3<br/>
1 2 4</div>
# 样例输出

<div class="pddata">9</div>
# 样例二的注释

<div class="pdcont">　　在第一个时刻完成任务一，在第二个时刻完成任务三，这样得到最大总价值9。</div>
# 样例输入

<div class="pddata">6<br/>
1 2 10<br/>
2 3 10<br/>
3 4 10<br/>
4 5 10<br/>
1 1 5<br/>
5 5 6</div>
# 样例输出

<div class="pddata">46</div>
# 样例三的注释

<div class="pdcont">　　时刻1完成第一个任务，时刻2完成第二个任务，时刻3完成第三个任务，时刻4完成第四个任务，时刻5完成第六个任务，所得的总收益是10+10+10+10+6=46，为最大收益。</div>
# 数据规模和约定

<div class="pdcont">　　在占12%分数的数据中有N≤20。<br/>
　　在占30%分数的数据中有N≤500。<br/>
　　在所有数据中，N≤5000，1≤Si≤Ti≤10<sup>8</sup>，1≤Vi≤10<sup>8</sup>。</div>

</div>