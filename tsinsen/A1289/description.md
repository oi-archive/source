<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　Albert and Bob are good friends and both love playing basketball. One day, they decide to have a shooting competition. They take turns shooting with Albert shooting first. Every time one shoots, he can choose to make a regular two-point shot or a three-point shot, and he will gain two points for a successful regular two-point shot or three points for a successful three-point shot. However, he will get nothing if his shot misses.<br/>
　　The game ends after each of them has made <i>k</i> shots, and the person with more points will be the winner of the competition. If they two earn the same amount of points, none of them will immediately be the winner, but a new competition will be launched, in which each one shoots k times in turn as previous. The competitions will repeatedly be launched until the points of the two players are different after one competition.<br/>
　　They are both clear about the regular shooting rate and three-point shooting rate of oneself and the other. Please figure out the possibility that Albert wins.</div>
# 输入格式

<div class="pdcont">　　The input contains multiple test cases.<br/>
　　The first line of the input contains one integer <i>T</i>, the number of test cases.<br/>
　　For each test case, the input contains one line with five integers, <i>A</i><sub>2</sub>, <i>A</i><sub>3</sub>, <i>B</i><sub>2</sub>, <i>B</i><sub>3</sub> and <i>k</i>, where <i>A</i><sub>2</sub>*10^<sup>–6</sup>, <i>A</i><sub>3</sub>*10^<sup>–6</sup>, B<sub>2</sub>*10^<sup>–6</sup> and <i>B</i><sub>3</sub>*10^<sup>–6</sup> represent Albert’s regular two-point shooting rate, Albert’s three-point shooting rate, Bob’s regular two-point shooting rate and Bob’s three-point shooting rate, respectively.</div>
# 输出格式

<div class="pdcont">　　For each test case, the output should contain one line with one real number rounded to eight decimal places, the winning possibility of Albert.</div>
# 样例输入

<div class="pddata">4<br/>
900000 800000 900000 800000 1<br/>
900000 80000 900000 80000 1<br/>
900000 800000 900000 800000 2<br/>
800000 10000 460000 290000 1</div>
# 样例输出

<div class="pddata">0.47058824<br/>
0.50000000<br/>
0.48440899<br/>
0.63677130</div>
# Constraints

<div class="pdcont">　　For all test cases, 1 ≤ <i>T</i> ≤ 500, 0 &lt; <i>A</i><sub>2</sub>, <i>A</i><sub>3</sub>, <i>B</i><sub>2</sub>, <i>B</i><sub>3 </sub>&lt; 10^<sup>6</sup>, 0 &lt; <i>k</i> &lt; 20.</div>

</div>