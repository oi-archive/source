# 题目描述


<h3>
【题目描述】
</h3>
<p>
小k同学正在玩一个游戏，在游戏中他扮演了一个马戏团的老板，现在小k同学需要利用马戏团中的A只猫和B只狗举办一次表演，表演之前他让观众进行了投票，投票的类容是：我想看到第___号猫/狗的表演，不想看到第___号猫/狗的表演。注意到每个观众都是更喜欢猫或更喜欢狗，所以两个空后面一定会被勾上不同的内容。喜欢猫的观众会在第一空后面选择猫，第二空后面选择狗；反之就会在第一空后面选择狗，第二空后面选择猫。对于每一个观众，只有当TA投票的内容都被满足了（即TA想看到的动物出场表演，TA不想看到的动物不参与表演）的时候，TA才会来看表演。当然啦，看表演是要付门票钱的，作为马戏团的老板，小k自然是希望来的人越多越好了。他想找到一个安排动物表演的方案，使得来看表演的观众尽量多。
</p>
<h3>
【输入格式】
</h3>
<p>
第1行3个正整数n,m,k，分别表示猫、狗和观众的数量
</p>
<p>
第2~k+1行，每行描述了一个观众的投票内容。
</p>
<p>
首先输入一个字符C或D紧接着是一个数字，表示某个观众想看到的动物，然后是一个空格隔开，接下去又是一个C或D加上一个数字，表示这个观众不想看到的动物，同一行中一定不会出现两个C或两个D。
</p>
<h3>
【输出格式】
</h3>
<p>
输出一行一个正整数，表示小k在最优的安排下可以吸引多少观众来看表演。
</p>
<h3>
【样例输入】
</h3>
<pre>1 2 4
C1 D1
C1 D1
C1 D2
D2 C1
</pre>
<h3>
【样例输出】
</h3>
<pre>3</pre>
<h3>
【提示】
</h3>
<p>
对于25%的数据n,m≤10,k≤25;
</p>
<p>
对于100%的数据，n,m≤300,k≤500.
</p>
<h3>
【来源】
</h3>
<p>
搬运 by HZOI 2016
</p>
