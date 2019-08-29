<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　从前有一场比赛叫ACM ICPC v2.0.这个比赛和传说中的ACM ICPC差的不是很多。比如说，每个参与者最多只能参加总决赛两次。但是有个显著的差别：每个队伍要包含<i>n</i>个人。<br/>
　　由于参加了好多届总决赛但没拿过牌，学生和校方觉得是时候要对准备环节做出改变了。特别地，第一次革新决定要改变组队结构。经过长期对其他学校表现的研究，他们成功得到了一些有趣的信息：关于拿牌的概率与队中参加过的以往决赛的人数的关系。更正式的，我们知道了<i>n</i> + 1个实数 <i>p</i><sub>0</sub> ≤ <i>p</i><sub>1</sub> ≤ ... ≤ <i>p</i><sub><i>n</i></sub>, <i>p</i><sub><i>i</i></sub>表示队中有<i>i</i>人参加过的以往决赛，<i>n</i> - <i>i</i>人是第一次参加决赛拿牌的概率。<br/>
　　尽管有这么有用的数据，但校方还是不能知道怎样的组队策略才能让得牌的平均概率最大（我们假设我们要得到的结果是在很久很久之后，并有无穷无尽的学生资源）。你能得到的最优策略吗？校方暂时只要知道的最大平均概率。<br/>
　　更正式的，假设第<i>k</i>届总决赛学校派出了一支队，这个队有<i>a</i><sub><i>k</i></sub>个人参加了以前的决赛 (0 ≤ <i>a</i><sub><i>k</i></sub> ≤ <i>n</i>).因为每个人最多只能参加决赛最多两次，所以下面这个条件一定是对的:<img width="176" height="43" src="source/tsinsen/A1435/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9Ujc4VE5qYUU=.do"/>，你的任务是选择数列<img width="62" height="21" src="source/tsinsen/A1435/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9NE1tSGVCYUE=.do"/>，使极限<img width="128" height="62" src="source/tsinsen/A1435/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9Mk1teWVnTUI=.do"/>存在并最大。<br/>
　　因为<img width="62" height="21" src="source/tsinsen/A1435/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9bWpmMkFmN1k=.do"/>是一个无穷数列，你只要输出Ψ的最大值就够了。</div>
# 输入格式

<div class="pdcont">　　第一行包含一个整数<i>n</i> (3 ≤ <i>n</i> ≤ 100), <i>n</i>表示队伍的人数。第二行包含 n + 1个实数 <i>p</i><sub><i>i</i></sub> (0 ≤ <i>i</i> ≤ <i>n</i>, 0 ≤ <i>p</i><sub><i>i</i></sub> ≤ 1) ,表示有i人参加过的以往决赛拿牌的概率，<i>p</i><sub><i>i</i></sub>最多有刘为小数。对于所有0 ≤ <i>i</i> ≤ <i>n</i> - 1满足条件<i>p</i><sub><i>i</i></sub> ≤ <i>p</i><sub><i>i</i> + 1</sub>。</div>
# 输出格式

<div class="pdcont">　　输出一个实数，使用最优策略时每年的期望奖牌数。允许结果有10<sup> - 6</sup>的绝对或相对误差。</div>
# 样例输入

<pre class="pddata">3
0.115590 0.384031 0.443128 0.562356
</pre>

# 样例输出

<pre class="pddata">0.4286122500
</pre>

# 样例输入

<pre class="pddata">3
1 1 1 1
</pre>

# 样例输出

<pre class="pddata">0.9999999999
</pre>

# 数据规模和约定

<div class="pdcont">　　对于20%的数据1 ≤ n ≤ 10；<br/>
　　对于50%的数据1 ≤ n ≤ 20；<br/>
　　对于70%的数据1 ≤ n ≤ 70；<br/>
　　对于100%的数据1 ≤ n ≤ 100；</div>

</div>