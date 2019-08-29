<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　蘑菇大帝是矮人的后裔，但不是每个人都能够见得到他。只有少数被选中的人才能见到大帝。<br/>
　　我们知道只有<i>LCM</i>(<i>k</i><sup>2<sup><i>l</i></sup></sup> + 1, <i>k</i><sup>2<sup><i>l</i> + 1</sup></sup> + 1, ..., <i>k</i><sup>2<sup><i>r</i></sup></sup> + 1)个矮人可以看到蘑菇大帝。其中正整数 <i>k</i>，<i>l</i>，<i>r，</i>是蘑菇大帝用一种矮人平民所不清楚的复杂方式自己选择的。<br/>
　　矮人历史学家决定记录下对蘑菇大帝的每次拜访人数。对于每次拜访，矮人历史学家知道蘑菇大帝为这次拜访选择的三个正整数 <i>k</i><sub><i>i</i>，</sub><i>l</i><sub><i>i</i>，</sub><i>r</i><sub><i>i</i></sub>。他们还知道一个素数<i>p</i><sub><i>i</i></sub>。请帮助他们计算每次拜访能见到蘑菇大帝的矮人数目模<i>p</i><sub><i>i</i></sub>的余数。<br/>
　　<b>其中，</b><i>LCM</i>(<i>a</i><sub>1</sub>, <i>a</i><sub>2</sub>, ..., <i>a</i><sub><i>n</i></sub>)<b>表示</b><i>a</i><sub>1</sub>, <i>a</i><sub>2</sub>, ..., <i>a</i><sub><i>n</i></sub><b>的最小公倍数。假设对于任意的x，</b><i>x</i><sup>0</sup> = 1。</div>
# 输入格式

<div class="pdcont">　　输入的第一行包含一个整数 <i>t</i> (1 ≤ <i>t</i> ≤ 10<sup>5</sup>) ，表示对大帝的拜访次数。<br/>
　　接下来的t行每行包含四个用空格隔开的整数<i>k</i><sub><i>i</i>，</sub><i>l</i><sub><i>i</i>，</sub><i>r</i><sub><i>i</i>，</sub><i>p</i><sub><i>i</i></sub> (1 ≤ <i>k</i><sub><i>i</i></sub> ≤ 10<sup>6</sup>; 0 ≤ <i>l</i><sub><i>i</i></sub> ≤ <i>r</i><sub><i>i</i></sub> ≤ 10<sup>18</sup>; 2 ≤ <i>p</i><sub><i>i</i></sub> ≤ 10<sup>9</sup>)，分别表示蘑菇大帝选择的数与素数模。<br/>
　　数据保证对于每次拜访<i>p</i><sub><i>i</i></sub>都是素数。</div>
# 输出格式

<div class="pdcont">　　对于每次拜访在单独的一行中输出能看到大帝的矮人数目模<i>p</i><sub><i>i</i></sub>的余数。请按照输入的顺序依次输出。</div>
# 样例输入

<div class="pddata">2<br/>
3 1 10 2<br/>
5 0 4 3</div>
# 样例输出

<div class="pddata">0<br/>
0</div>
# 数据规模和约定

<div class="pdcont">　　对5%的数据<i>k</i><sub><i>i </i></sub>= 1。<br/>
　　对另外5%的数据<i>p</i><sub><i>i </i></sub>= 2。<br/>
　　对另外20%的数据 0 ≤ <i>l</i><sub><i>i</i></sub> ≤ <i>r</i><sub><i>i</i></sub> ≤ 10。<br/>
　　对100%的数据1 ≤ <i>k</i><sub><i>i</i></sub> ≤ 10<sup>6</sup>; 0 ≤ <i>l</i><sub><i>i</i></sub> ≤ <i>r</i><sub><i>i</i></sub> ≤ 10<sup>18</sup>; 2 ≤ <i>p</i><sub><i>i</i></sub> ≤ 10<sup>9</sup></div>

</div>