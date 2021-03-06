<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　在一个忍者的帮派里，一些忍者们被选中派遣给顾客，然后依据自己的工作获取报偿。<br/>
　　在这个帮派里，有一名忍者被称之为Master。除了Master以外，每名忍者都有且仅有一个上级。为保密，同时增强忍者们的领导力，所有与他们工作相关的指令总是由上级发送给他的直接下属，而不允许通过其他的方式发送。<br/>
　　现在你要招募一批忍者，并把它们派遣给顾客。你需要为每个被派遣的忍者支付一定的薪水，同时使得支付的薪水总额不超过你的预算。另外，为了发送指令，你需要选择一名忍者作为管理者，要求这个管理者可以向所有被派遣的忍者发送指令，在发送指令时，任何忍者（不管是否被派遣）都可以作为消息的传递人。管理者自己可以被派遣，也可以不被派遣。当然，如果管理者没有被派遣，你就不需要支付管理者的薪水。<br/>
　　你的目标是在预算内使顾客的满意度最大。这里定义顾客的满意度为派遣的忍者总数乘以管理者的领导力，其中每个忍者的领导力也是一定的。<br/>
　　写一个程序，给定每一个忍者<i>i</i>的上级<i>B<sub>i</sub></i>，薪水<i>C<sub>i</sub></i>，领导力<i>L<sub>i</sub></i>，以及支付给忍者们的薪水总预算<i>M</i>，输出在预算内满足上述要求时顾客满意度的最大值。</div>
# 数据规模和约定

<div class="pdcont">　　1 ≤ <i>N</i> ≤ 100,000                              忍者的个数；<br/>
　　1 ≤ <i>M</i> ≤ 1,000,000,000                   薪水总预算；<br/>
　　0 ≤ <i>B<sub>i</sub></i> &lt; <i>i</i>                                         忍者的上级的编号；<br/>
　　1 ≤ <i>C<sub>i</sub></i> ≤ <i>M</i>                                       忍者的薪水；<br/>
　　1 ≤ <i>L<sub>i</sub></i> ≤ 1,000,000,000                   忍者的领导力。<br/>
<br/>
　　对于30%的数据，<i>N</i> ≤ 3000。</div>
# 输入格式

<div class="pdcont">　　从标准输入读入数据。<br/>
　　第一行包含两个整数<i>N</i>和<i>M</i>，其中<i>N</i>表示忍者的个数，<i>M</i>表示薪水的总预算。<br/>
　　接下来<i>N</i>行描述忍者们的上级、薪水以及领导力。其中的第<i>i</i>行包含三个整数<i>B<sub>i </sub></i>, <i>C<sub>i </sub></i>, <i>L<sub>i</sub></i>分别表示第<i>i</i>个忍者的上级，薪水以及领导力。Master满足<i>B<sub>i</sub></i> = 0，并且每一个忍者的上级的编号一定小于自己的编号 <i>B<sub>i</sub></i> &lt; <i>i</i>。</div>
# 输出格式

<div class="pdcont">　　输出到标准输出。<br/>
　　输出一个数，表示在预算内顾客的满意度的最大值。</div>
# 样例输入

<div class="pddata">5 4<br/>
0 3 3<br/>
1 3 5<br/>
2 2 2<br/>
1 2 4<br/>
2 3 1</div>
# 样例输出

<div class="pddata">6</div>
# 样例说明

<div class="pdcont">　　如果我们选择编号为1的忍者作为管理者并且派遣编号为3和编号为4的忍者，薪水总和为4，没有超过总预算4。因为派遣了2个忍者并且管理者的领导力为3，用户的满意度为2 × 3 = 6，是可以得到的用户满意度的最大值。</div>

</div>