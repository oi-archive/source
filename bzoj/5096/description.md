
# Description

<div class="content"><div>小Q和tangjz正在玩一个有趣的游戏，在这个游戏中，有两个长度分别为n和m的数列a_1,a_2,...,a_n,b_1,b_2,...</div>
<div>,b_m。你需要将这两个数列合并成一个长度为n+m的新数列c，但是不得改变a和b中每个数的先后顺序。游戏的得分</div>
<div>即为c中最长上升子序列的长度。游戏高手小Q使用最佳策略玩出了一个理论最高分k，接下来轮到tangjz玩。小Q知</div>
<div>道tangjz也会使用最佳策略，因此他决定从中偷偷删去一些数(甚至删光)，使得tangjz无论如何也玩不到k分。因</div>
<div>为视角问题，每个位置的数删去的代价都不尽相同，请写一个程序帮助小Q计算最小的总代价。</div>
<div></div></div>

# Input

<div class="content"><p>第一行包含一个正整数n(1&lt;=n&lt;=100)，表示序列a的长度。</p>
<div>第二行包含n个正整数a_1,a_2,...,a_n(1&lt;=a_i&lt;=1000)，表示序列a。</div>
<div>第三行包含n个正整数wa_1,wa_2,...,wa_n(1&lt;=wa_i&lt;=10^6)，分别表示删去a中每个位置的数的代价。</div>
<div>第四行包含一个正整数m(1&lt;=m&lt;=100)，表示序列b的长度。</div>
<div>第五行包含m个正整数b_1,b_2,...,b_m(1&lt;=b_i&lt;=1000)，表示序列b。</div>
<div>第六行包含m个正整数wb_1,wb_2,...,wb_m(1&lt;=wb_i&lt;=10^6)，分别表示删去b中每个位置的数的代价。</div>
<div>输入数据保证a中无重复数字，b中无重复数字，a与b也没有重复数字。</div>
<div></div></div>

# Output

<div class="content"><div>输出一行一个整数，即最小总代价。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
7 1 5<br/>
1 2 3<br/>
3<br/>
9 8 6<br/>
3 2 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=claris原创，本oj版权所有,翻版必究">claris原创，本oj版权所有,翻版必究</a></p></div>

